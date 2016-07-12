#### Test 757892685a40176_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-12 17:44:56.732   289   289 E SMD     : DCD OFF
,07-12 17:44:56.992  6676  6676 D AndroidRuntime: 
07-12 17:44:56.992  6676  6676 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 17:44:56.992  6676  6676 D AndroidRuntime: CheckJNI is OFF
07-12 17:44:56.992  6676  6676 D AndroidRuntime: readGMSProperty: start
07-12 17:44:56.992  6676  6676 D AndroidRuntime: readGMSProperty: already setted!!
07-12 17:44:56.992  6676  6676 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 17:44:56.992  6676  6676 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 17:44:56.992  6676  6676 D AndroidRuntime: readGMSProperty: end
07-12 17:44:56.992  6676  6676 D AndroidRuntime: addProductProperty: start
07-12 17:44:57.112  6676  6676 E AffinityControl: AffinityControl: registerfunction enter
07-12 17:44:57.142  6676  6676 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 17:44:57.152  1017  1218 E PersonaManagerService: inState():  stateMachine is null !!
07-12 17:44:57.152  1017  1218 I PersonaManagerService: PersonaId don't exist
07-12 17:44:57.152  1017  1218 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-12 17:44:57.162  1017  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-12 17:44:57.172  1017  1218 W ActivityManager: mDVFSHelper.acquire()
07-12 17:44:57.172  1017  1218 D FocusedStackFrame: Set to : 0
07-12 17:44:57.182  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.182  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.182  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.182  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:57.192  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-12 17:44:57.192  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-12 17:44:57.192  6687  6687 E Zygote  : MountEmulatedStorage()
07-12 17:44:57.192  6687  6687 E Zygote  : v2
07-12 17:44:57.192  6687  6687 I libpersona: KNOX_SDCARD checking this for 10170
07-12 17:44:57.192  6687  6687 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:57.192  6687  6687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:57.192  1017  1218 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6687 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 17:44:57.192  1017  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-12 17:44:57.192  1017  1218 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-12 17:44:57.192  1017  1218 D InputDispatcher: Focused application set to: xxxx
07-12 17:44:57.192  1017  1218 D InputDispatcher: Focus left window: 1481
07-12 17:44:57.202  6676  6676 D AndroidRuntime: Shutting down VM
07-12 17:44:57.202  6687  6687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:57.202  6687  6687 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-12 17:44:57.212  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-12 17:44:57.212  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-12 17:44:57.212   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-12 17:44:57.222  6687  6687 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:57.222  6687  6687 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:57.222  1017  1498 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-12 17:44:57.222  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:44:57.222  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 17:44:57.232  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:44:57.242  1017  1498 D PersonaManager: isKioskContainerExistOnDevice
07-12 17:44:57.252  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-12 17:44:57.282   259  1161 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-12 17:44:57.282   259   445 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-12 17:44:57.282  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{58ce8de token=android.os.BinderProxy@23b3b83c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-12 17:44:57.292  1481  1481 D Launcher: onTrimMemory. Level: 20
07-12 17:44:57.352  6687  6687 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-12 17:44:57.372  6687  6687 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9429-9430)
07-12 17:44:57.372  6687  6687 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:44:57.402  6687  6687 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {56fd7f6}
07-12 17:44:57.402  6687  6687 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:44:57.402  6687  6687 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:44:57.402  6676  6676 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-12 17:44:57.432  6687  6687 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,07-12 17:44:57.432  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,07-12 17:44:57.442  6687  6687 E SysUtils: ApplicationContext is null in ApplicationStatus,
,07-12 17:44:57.462  6687  6687 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-12 17:44:57.462  6687  6687 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-12 17:44:57.462  6687  6687 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-12 17:44:57.462  6687  6687 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-12 17:44:57.462  6687  6687 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-12 17:44:57.462  6687  6687 I Adreno-EGL: Build Date: 04/06/15 Mon
07-12 17:44:57.462  6687  6687 I Adreno-EGL: Local Branch: 
07-12 17:44:57.462  6687  6687 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-12 17:44:57.462  6687  6687 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-12 17:44:57.462  6687  6687 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,07-12 17:44:57.662  6687  6713 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-12 17:44:57.702  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:44:57.712  6687  6687 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 17:44:57.722  6687  6687 D PhoneWindow: *FMB* installDecor mIsFloating : false
,07-12 17:44:57.722  6687  6687 D PhoneWindow: *FMB* installDecor flags : -2139027200
,07-12 17:44:57.732  6687  6687 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-12 17:44:57.742  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:44:57.742  6687  6687 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 17:44:57.752  1017  1043 W ActivityManager: Activity pause timeout for ActivityRecord{3c5e1aaf u0 com.test.thalitest/.MainActivity t9}
,07-12 17:44:57.812  6687  6726 D OpenGLRenderer: Render dirty regions requested: true
,07-12 17:44:57.822  1017  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-12 17:44:57.822  1017  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 17:44:57.822  1017  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-12 17:44:57.822  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 17:44:57.822  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,07-12 17:44:57.822  6687  6687 V ActivityThread: updateVisibility : ActivityRecord{cec0a39 token=android.os.BinderProxy@2e457083 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-12 17:44:57.832  6687  6687 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,07-12 17:44:57.832  6687  6687 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,07-12 17:44:57.842   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-12 17:44:57.852  1017  1030 D InputDispatcher: Focus entered window: 6687
,07-12 17:44:57.852  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-12 17:44:57.852  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 17:44:57.862  6687  6687 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-12 17:44:57.862  6687  6726 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 17:44:57.862  6687  6726 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-12 17:44:57.862  6687  6726 D OpenGLRenderer: Enabling debug mode 0
,07-12 17:44:57.882  1017  3968 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-12 17:44:57.892  1176  1176 I StatusBar: Icon Only
,07-12 17:44:57.892  1176  1176 D PanelView: There is/are notification(s) 
,07-12 17:44:57.892  1017  6728 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 17:44:57.902  1017  1048 I ActivityManager: Displayed Component not be shown by security: +657ms (total +35s733ms)
07-12 17:44:57.902  1017  1048 W ActivityManager: mDVFSHelper.release()
07-12 17:44:57.902  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c5e1aaf u0 com.test.thalitest/.MainActivity t9} time:149968
07-12 17:44:57.912  6687  6687 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-12 17:44:57.912  6687  6687 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e457083 time:149974
07-12 17:44:57.912   259   449 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-12 17:44:57.912   259  1161 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,07-12 17:44:57.922  1862  1862 I SamsungIME: getCurrentCandidateView
,07-12 17:44:58.012  6687  6687 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6687
,07-12 17:44:58.032  1862  1862 D SamsungIME: Dismiss ExpandCandiate
,07-12 17:44:58.142  6687  6687 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 17:44:58.192  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,07-12 17:44:58.312  1862  1862 I SamsungIME: getDebugLevel  : 0x4f4c
,07-12 17:44:58.322  1862  1862 I SamsungIME: KeybaordView init() : load resources
,07-12 17:44:58.342  6687  6731 D jxcore_app_log: JniHelper::setJavaVM(0xb8c962f0), pthread_self() = -1189144792
07-12 17:44:58.342  1862  1862 I SamsungIME: getCurrentKeyboard
07-12 17:44:58.342  1862  1862 I SamsungIME: getTextKeyboard
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-12 17:44:58.352  6687  6731 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1306f3a9 added. We now have 1 listener(s)
,07-12 17:44:58.362  6687  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-12 17:44:58.362  6687  6731 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-12 17:44:58.362  6687  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 17:44:58.362  6687  6731 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 17:44:58.372  1862  1862 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 17:44:58.372  6687  6731 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f638a5c added. We now have 1 listener(s)
,07-12 17:44:58.372  6687  6731 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 17:44:58.382  6687  6731 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 17:44:58.382  6687  6731 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 17:44:58.392  6687  6731 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-12 17:44:58.392  6687  6731 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 17:44:58.392  6687  6731 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 17:44:58.392  6687  6731 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 17:44:58.392  6687  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:44:58.402  6687  6687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 17:44:58.432  6687  6687 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:44:58.982  6687  6736 W jxcore-log: Initializing JXcore engine
07-12 17:44:58.982  6687  6736 W jxcore-log: JXcore engine is ready
,07-12 17:44:59.042  2013  2013 E audit   : type=1400 msg=audit(1468338299.042:205): avc:  denied  { ioctl } for  pid=6736 comm="Thread-1203" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-12 17:44:59.042  2013  2013 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:59.042  2013  2013 E audit   : type=1300 msg=audit(1468338299.042:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ea008f8 items=0 ppid=308 ppcomm=main pid=6736 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1203" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-12 17:44:59.042  2013  2013 E audit   : type=1320 msg=audit(1468338299.042:205): 
,07-12 17:44:59.052  6687  6736 W jxcore-log: Starting JXcore engine
,07-12 17:44:59.152  6687  6736 W jxcore-log: Platform android,
07-12 17:44:59.152  6687  6736 W jxcore-log: 
07-12 17:44:59.152  6687  6736 W jxcore-log: Process ARCH arm
07-12 17:44:59.152  6687  6736 W jxcore-log: 
,07-12 17:44:59.352  6687  6736 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:44:59.352  6687  6736 I jxcore-log: 
,07-12 17:44:59.352  6687  6736 W jxcore-log: JXcore engine is started
07-12 17:44:59.362  6687  6731 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-12 17:44:59.362  6687  6687 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-12 17:44:59.372  6687  6736 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 17:44:59.372  6687  6736 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
07-12 17:44:59.382  6687  6687 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 17:44:59.382  6687  6687 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-12 17:44:59.382  1017  1490 D FocusedStackFrame: Set to : 0
07-12 17:44:59.382  1017  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-12 17:44:59.382  1017  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-12 17:44:59.382  1017  1490 D InputDispatcher: Focused application set to: xxxx
07-12 17:44:59.382  1017  1490 D InputDispatcher: Focus left window: 6687
07-12 17:44:59.392  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:44:59.392  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
07-12 17:44:59.392  1017  1490 I ActivityManager: Killing 6283:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-12 17:44:59.402  6687  6731 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
07-12 17:44:59.402  6687  6687 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-12 17:44:59.402  6687  6687 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-12 17:44:59.412  6687  6687 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 17:44:59.412  6687  6687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:44:59.412  6687  6687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-12 17:44:59.412  6687  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:44:59.412  6687  6687 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1306f3a9 removed from the list
07-12 17:44:59.412  6687  6687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:44:59.412  6687  6687 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f638a5c removed from the list
07-12 17:44:59.412  6687  6687 D io.jxcore.node.ConnectivityMonitor: stop
07-12 17:44:59.412  6687  6687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-12 17:44:59.412  6687  6687 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:44:59.422   259  1161 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-12 17:44:59.422   259  1039 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-12 17:44:59.432  1017  1479 W ActivityManager: mDVFSHelper.acquire()
,07-12 17:44:59.432  1017  1479 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-12 17:44:59.452  1481  1481 D Launcher: onRestart, Launcher: 851017090
,07-12 17:44:59.452  1481  1481 D Launcher: onStart, Launcher: 851017090
07-12 17:44:59.452  1481  1481 D Launcher.HomeView: onStart
,07-12 17:44:59.452  1481  1481 D Launcher: onResume, Launcher: 851017090
07-12 17:44:59.462  1017  1490 D SettingsProvider: name = kids_home_mode
07-12 17:44:59.462  1017  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 17:44:59.462  1017  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 17:44:59.462  1017  1490 D SettingsProvider: selectionArgs: false
07-12 17:44:59.462  1017  1490 D SettingsProvider: selectionArgs: 10006
07-12 17:44:59.462  1017  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-12 17:44:59.462  1017  1490 D SettingsProvider: ret = -1
07-12 17:44:59.462  1481  1481 D Launcher.HomeView: onResume
,07-12 17:44:59.462  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-12 17:44:59.472  1481  1481 D MenuAppsGridFragment: onResume
,07-12 17:44:59.472  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-12 17:44:59.472  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-12 17:44:59.472  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,07-12 17:44:59.482  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.482  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-12 17:44:59.482  1017  3967 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-12 17:44:59.482  1017  3967 W ActivityManager: userId = 0, bbcId = -10000,
07-12 17:44:59.482  1017  3967 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
07-12 17:44:59.482  1017  3967 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.482  1017  3967 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast,
07-12 17:44:59.482  1017  3967 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
07-12 17:44:59.482  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.482  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.482  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.482  1017  3967 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.502  6740  6740 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.502  6740  6740 E Zygote  : v2
07-12 17:44:59.502  6740  6740 I libpersona: KNOX_SDCARD checking this for 10039
07-12 17:44:59.502  6740  6740 I libpersona: KNOX_SDCARD not a persona
,07-12 17:44:59.502  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-12 17:44:59.502  1017  3967 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6740 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
07-12 17:44:59.502  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:44:59.512  1017  1490 D ActivityManager: handle home activity for 0,
07-12 17:44:59.512  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
07-12 17:44:59.512  1017  1490 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-12 17:44:59.512  1017  1490 D KnoxTimeoutHandler: post home show event for user 0
07-12 17:44:59.512  1017  1490 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-12 17:44:59.512  1017  1490 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 17:44:59.512  1017  1490 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-12 17:44:59.512  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,07-12 17:44:59.512  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-12 17:44:59.512  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 17:44:59.512  1481  1481 D Launcher.HomeView: onPause
,07-12 17:44:59.512  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-12 17:44:59.512  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-12 17:44:59.512  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:44:59.512  1017  1043 W ActivityManager: userId = 0, bbcId = -10000,
07-12 17:44:59.512  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.512  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-12 17:44:59.512  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.522  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.512  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.522  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.512  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-12 17:44:59.522  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.522  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.542  6756  6756 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.542  6756  6756 I libpersona: KNOX_SDCARD checking this for 10089
07-12 17:44:59.542  6756  6756 E Zygote  : v2
07-12 17:44:59.542  6756  6756 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:59.542  6756  6756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:44:59.542  6756  6756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:44:59.542  6756  6756 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-12 17:44:59.542  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6756 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-12 17:44:59.542  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:44:59.542  6740  6740 D ActivityThread: Added TimaKeyStore provider
,07-12 17:44:59.552  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.552  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.552  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-12 17:44:59.552  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,07-12 17:44:59.552  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.552  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.552  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.552  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.562  6770  6770 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.562  6770  6770 E Zygote  : v2
07-12 17:44:59.562  6770  6770 I libpersona: KNOX_SDCARD checking this for 10139
,07-12 17:44:59.562  6770  6770 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:59.572  6770  6770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:44:59.572  6756  6756 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:59.572  6756  6756 D ActivityThread: Added TimaKeyStore provider
,07-12 17:44:59.572  1017  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6770 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
07-12 17:44:59.572  6770  6770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
07-12 17:44:59.572  6770  6770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:44:59.592  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.592  1017  1555 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-12 17:44:59.592  1017  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.592  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-12 17:44:59.602   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
07-12 17:44:59.602  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.602  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.602  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
07-12 17:44:59.602  6770  6770 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:44:59.602  6770  6770 D ActivityThread: Added TimaKeyStore provider
,07-12 17:44:59.602  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-12 17:44:59.602  2622  2622 D Recents_RecreateReceiver: onReceive by home
,07-12 17:44:59.602  1017  3967 D InputDispatcher: Focus entered window: 1481
07-12 17:44:59.602  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-12 17:44:59.602  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.602  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.602  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
07-12 17:44:59.602  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,07-12 17:44:59.612  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-12 17:44:59.612  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-12 17:44:59.612  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-12 17:44:59.612  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.612  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.612  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.612  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-12 17:44:59.612  6740  6740 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-12 17:44:59.622  6756  6756 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 17:44:59.622  6756  6756 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-12 17:44:59.622  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{58ce8de token=android.os.BinderProxy@23b3b83c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-12 17:44:59.622  1481  1481 D Launcher.HomeView: onStop
07-12 17:44:59.622  6787  6787 E Zygote  : MountEmulatedStorage()
,07-12 17:44:59.622  6787  6787 E Zygote  : v2
07-12 17:44:59.622  1017  1136 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-12 17:44:59.622  6787  6787 I libpersona: KNOX_SDCARD checking this for 10084
07-12 17:44:59.622  6787  6787 I libpersona: KNOX_SDCARD not a persona
07-12 17:44:59.632  6787  6787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:44:59.632  1017  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 17:44:59.632  6787  6787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:44:59.632  6787  6787 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-12 17:44:59.632  1017  1030 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6787 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-12 17:44:59.632  1862  1862 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-12 17:44:59.642  6687  6687 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-12 17:44:59.662  1176  1176 I StatusBar: Icon Only
07-12 17:44:59.662  1176  1176 D PanelView: There is/are notification(s) 
,07-12 17:44:59.672  6770  6770 V TaskCloserActivity: TaskCloserActivity enter()
07-12 17:44:59.682  6787  6787 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:44:59.682  6787  6787 D ActivityThread: Added TimaKeyStore provider
07-12 17:44:59.682  6738  6738 D AndroidRuntime: 
07-12 17:44:59.682  6738  6738 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-12 17:44:59.682  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@23b3b83c time:151744
07-12 17:44:59.682  6738  6738 D AndroidRuntime: CheckJNI is OFF
07-12 17:44:59.682  6738  6738 D AndroidRuntime: readGMSProperty: start
07-12 17:44:59.682  6738  6738 D AndroidRuntime: readGMSProperty: already setted!!
07-12 17:44:59.682  6738  6738 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-12 17:44:59.682  6738  6738 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-12 17:44:59.682  6738  6738 D AndroidRuntime: readGMSProperty: end
07-12 17:44:59.682  6738  6738 D AndroidRuntime: addProductProperty: start
,07-12 17:44:59.702  6770  6770 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-12 17:44:59.702  6787  6787 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 17:44:59.702  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.702  1017  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.702  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,07-12 17:44:59.702  1017  1472 I ActivityManager: Killing 6312:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-12 17:44:59.712  1017  1048 W ActivityManager: mDVFSHelper.release()
,07-12 17:44:59.712  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f2cd2f9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:151771
,07-12 17:44:59.712  1017  1448 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:44:59.712  1017  1448 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:44:59.712  1017  1448 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-12 17:44:59.712  1017  1448 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,07-12 17:44:59.712  1017  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.712  1017  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.712  1017  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:44:59.712  1017  1448 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:44:59.732  6808  6808 E Zygote  : MountEmulatedStorage()
07-12 17:44:59.732  6808  6808 I libpersona: KNOX_SDCARD checking this for 10135
07-12 17:44:59.732  6808  6808 E Zygote  : v2
07-12 17:44:59.732  6808  6808 I libpersona: KNOX_SDCARD not a persona
,07-12 17:44:59.732   289   289 E SMD     : DCD OFF
07-12 17:44:59.732  1017  1448 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6808 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
07-12 17:44:59.732  6808  6808 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:44:59.732  1017  1448 I ActivityManager: Killing 6342:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
07-12 17:44:59.732  6808  6808 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:44:59.732  6808  6808 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 17:44:59.742  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,07-12 17:44:59.742  1017  1448 I ActivityManager: Killing 6299:com.osp.app.signin/u0a36 (adj 15): empty #21
,07-12 17:44:59.762  6808  6808 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:44:59.762  6808  6808 D ActivityThread: Added TimaKeyStore provider
,07-12 17:44:59.772  1017  1497 D PersonaManager: isKioskContainerExistOnDevice
,07-12 17:44:59.782  6808  6808 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-12 17:44:59.782  6808  6808 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 17:44:59.782  6808  6808 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-12 17:44:59.782  6808  6808 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-12 17:44:59.782  6808  6808 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-12 17:44:59.822  1017  1136 I ActivityManager: Killing 6178:com.android.mms/u0a41 (adj 15): empty #21
,07-12 17:44:59.822  6738  6738 E AffinityControl: AffinityControl: registerfunction enter
,07-12 17:44:59.852  6738  6738 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-12 17:44:59.862  1017  1479 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-12 17:44:59.862  1017  1479 D PackageManager: START PACKAGE DELETE: observer{767250325}
07-12 17:44:59.862  1017  1479 D PackageManager: pkg{<packageName>}
07-12 17:44:59.862  1017  1479 D PackageManager: user{0}
07-12 17:44:59.862  1017  1479 D PackageManager: caller{2000}
07-12 17:44:59.862  1017  1479 D PackageManager: flags{2}
07-12 17:44:59.862  1017  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-12 17:44:59.862  1017  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-12 17:44:59.862  1017  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 17:44:59.862  1017  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-12 17:44:59.862  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-12 17:44:59.862  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,07-12 17:44:59.862  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-12 17:44:59.862  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
07-12 17:44:59.862  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-12 17:44:59.862  6740  6740 D NearbySource: Nearby Source Create!,
07-12 17:44:59.862  6740  6740 D NearbyContext: Nearby Context Create!
,07-12 17:44:59.862  1017  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,07-12 17:44:59.872  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-12 17:44:59.872  1017  1043 I ActivityManager: Killing 6687:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-12 17:44:59.882  1017  1472 D CountryDetector: No listener is left
,07-12 17:44:59.902   258   521 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-12 17:44:59.902   258   521 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 17:44:59.902  6740  6740 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,07-12 17:44:59.902  6740  6740 D SLinkSource: Samsung link source created
,07-12 17:44:59.952  1017  1058 W PackageSettings: Skipping PackageSetting{1eeb9e51 com.example.hello/10168} due to missing metadata
,07-12 17:44:59.992  1017  1096 V AlarmManager: waitForAlarm result :8
,07-12 17:45:00.022  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-12 17:45:00.042  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-12 17:45:00.062  1017  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 17:45:00.092  2752  2752 I art     : Explicit concurrent mark sweep GC freed 23438(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 797us total 43.229ms
,07-12 17:45:00.102  1862  1862 E SamsungIME: mOCRHelper is null
,07-12 17:45:00.102  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 17:45:00.112  6451  6451 I art     : Explicit concurrent mark sweep GC freed 612(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 709us total 78.271ms
,07-12 17:45:00.122  2030  2207 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 17:45:00.152  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-12 17:45:00.152  1438  1438 D RegisteredServicesCache: empty dynamic service
,07-12 17:45:00.162  4689  4689 I art     : Explicit concurrent mark sweep GC freed 20623(1287KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 12MB/16MB, paused 3.745ms total 125.571ms
,07-12 17:45:00.162  1017  1123 V NetworkStats: removeUidsLocked() for UIDs [10170]
07-12 17:45:00.162  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 17:45:00.162  1017  1123 V NetworkStats: performPollLocked(flags=0x3)
,07-12 17:45:00.162  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,07-12 17:45:00.172  1017  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-12 17:45:00.172  1017  1448 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 17:45:00.182  6740  6740 D GalleryCacheReady: Receive : home resume
,07-12 17:45:00.182  1017  1218 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.182  1017  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:00.182  1017  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-12 17:45:00.182  1017  1218 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-12 17:45:00.192  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.192  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.192  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.192  1017  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:00.192  1017  1123 V NetworkStats: performPollLocked() took 28ms
,07-12 17:45:00.192  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 17:45:00.192  6740  6833 D ContactProvider: getAllContactInfoList Start
,07-12 17:45:00.202  6835  6835 E Zygote  : MountEmulatedStorage()
07-12 17:45:00.202  6835  6835 E Zygote  : v2
07-12 17:45:00.202  6835  6835 I libpersona: KNOX_SDCARD checking this for 10041
07-12 17:45:00.202  6835  6835 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:00.202  6835  6835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-12 17:45:00.202  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
07-12 17:45:00.202  1017  1042 W TextServicesManagerService: no available spell checker services found
07-12 17:45:00.202  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-12 17:45:00.212  6835  6835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:00.212  6835  6835 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-12 17:45:00.212  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.212  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.222  1017  1218 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=6835 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-12 17:45:00.232  6835  6835 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 17:45:00.232  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
07-12 17:45:00.232  6835  6835 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:00.252  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,07-12 17:45:00.252  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.262  1017  1017 I art     : Explicit concurrent mark sweep GC freed 49126(3MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 4.564ms total 221.774ms
,07-12 17:45:00.262  1017  1058 I art     : WaitForGcToComplete blocked for 106.411ms for cause Explicit
,07-12 17:45:00.272  6835  6835 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
07-12 17:45:00.272  6835  6835 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 17:45:00.272  6835  6835 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 17:45:00.272  6835  6835 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-12 17:45:00.272  6835  6835 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-12 17:45:00.282  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 17:45:00.282  1017  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 17:45:00.292  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.292  6740  6833 D ContactProvider: getAllContactInfoList End
,07-12 17:45:00.302  6740  6833 I syncContacts: thread: 1188, sync time = 275
,07-12 17:45:00.312  1017  1490 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-12 17:45:00.312  1017  1490 D SecContentProvider2: mCursor = null
,07-12 17:45:00.312  6835  6835 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-12 17:45:00.342  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,07-12 17:45:00.342  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-12 17:45:00.342  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-12 17:45:00.342  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-12 17:45:00.342  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-12 17:45:00.342  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,07-12 17:45:00.352  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-12 17:45:00.422  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-12 17:45:00.422  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.432  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.442  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.452  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-12 17:45:00.452  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 17:45:00.452  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 17:45:00.452  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.472  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.482  6835  6835 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 125.412ms
,07-12 17:45:00.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:00.482  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-12 17:45:00.502  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-12 17:45:00.502  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-12 17:45:00.502  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-12 17:45:00.512  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-12 17:45:00.512  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicy: uID is 10170
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-12 17:45:00.512  1017  3451 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,07-12 17:45:00.512  1017  1058 I art     : Explicit concurrent mark sweep GC freed 18732(1091KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.506ms total 239.631ms
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-12 17:45:00.512  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
,07-12 17:45:00.512  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-12 17:45:00.522  1017  1017 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,07-12 17:45:00.522  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:00.522  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-12 17:45:00.532  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 17:45:00.532  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-12 17:45:00.542  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 17:45:00.542  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-12 17:45:00.542  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-12 17:45:00.542  1017  1058 D PackageManager: delete codoeFile: 
,07-12 17:45:00.552  1017  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-12 17:45:00.552  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-12 17:45:00.552  1017  1058 D PackageManager: result of delete: 1{767250325}
,07-12 17:45:00.562  6738  6738 D AndroidRuntime: Shutting down VM
,07-12 17:45:00.562  6835  6850 D Mms/ArtClassLoader: init before art
,07-12 17:45:00.562  6835  6835 D Mms/TelephonyPermission: start operation mode monitor
,07-12 17:45:00.582  6835  6835 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 17:45:00.582  6835  6835 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
07-12 17:45:00.582  6835  6835 D Mms/TelephonyPermission: isDefault true
,07-12 17:45:00.582  6835  6835 D Mms/MmsApp: onCreate() com.android.mms
,07-12 17:45:00.612  6835  6835 D Mms/MmsApp: [start]    initCountryIso consume time = 302.403333
,07-12 17:45:00.612  1017  1555 D CountryDetector: The first listener is added
,07-12 17:45:00.622  6835  6835 D Mms/MmsApp: [end]    initCountryIso consume time = 6.592448
07-12 17:45:00.622  6835  6835 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.136042
,07-12 17:45:00.622  6835  6835 D Mms/MmsConfig: before partial update
,07-12 17:45:00.642  6835  6835 D Mms/MmsConfig: Load Resize quality : 80
,07-12 17:45:00.642  6835  6835 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,07-12 17:45:00.642  6835  6835 D EasySignUpManager_1.0.1: isAuth is false
,07-12 17:45:00.652  6835  6835 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,07-12 17:45:00.652  1454  1474 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6835
,07-12 17:45:00.652  1454  1474 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.736 ms
,07-12 17:45:00.662  6835  6835 D EasySignUpManager_1.0.1: isAuth is false
,07-12 17:45:00.662  6835  6835 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,07-12 17:45:00.662  6835  6835 E CscParser: mps_code.dat does not exist
,07-12 17:45:00.662  6835  6835 E CscParser: customer_path =/system/csc/customer.xml
,07-12 17:45:00.662  6835  6835 E CscParser: fileName + /system/csc/customer.xml
,07-12 17:45:00.672  6835  6835 E CscParser: mps_code.dat does not exist
,07-12 17:45:00.672  6835  6835 E CscParser: customer_path =/system/csc/customer.xml
,07-12 17:45:00.692  6835  6835 E CscParser: fileName + /system/csc/customer.xml
,07-12 17:45:00.692  6835  6835 D CscParser: getInstance fileName =/system/csc/customer.xml
,07-12 17:45:00.692  6835  6835 D Mms/MmsConfig:  enable multiwindow = false
,07-12 17:45:00.702  6835  6835 E Mms/MessageUtils: setCountryDetector : update country detector info 
,07-12 17:45:00.702  6835  6835 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-12 17:45:00.712  6835  6835 D Mms/MmsConfig: [end]    init() consume time = 89.171197
,07-12 17:45:00.712  6835  6835 D Mms/Contact: [start]    init() consume time = 0.924532
,07-12 17:45:00.712  1454  5345 D TP/MmsSmsProvider: query,matched:13, calling pid = 6835
,07-12 17:45:00.712  1454  5345 D TP/MmsSmsProvider: match 13:Elapsed time : 1.086 ms
,07-12 17:45:00.722  6835  6835 D Mms/Contact: [end]    init consume time = 11.885625
,07-12 17:45:00.732  6835  6857 D Mms/DraftCache: [start]    rebuildCache consume time = 10.018645
,07-12 17:45:00.732  1454  1471 D TP/MmsSmsProvider: query,matched:12, calling pid = 6835
,07-12 17:45:00.742  1454  1471 D TP/MmsSmsProvider: match 12:Elapsed time : 1.765 ms
,07-12 17:45:00.742  6835  6835 D Mms/MethodReflector: getSubId is called
07-12 17:45:00.742  6835  6835 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,07-12 17:45:00.742  6835  6835 D Mms/MethodReflector: getTelephonyProperty is called
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: auto download without roaming -> true
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-12 17:45:00.742  6835  6835 D Mms/MethodReflector: getSubId is called
,07-12 17:45:00.742  6835  6835 D Mms/MethodReflector: getDefaultSmsSubId is called
07-12 17:45:00.742  6835  6857 D Mms/DraftCache: [end]    rebuildCache consume time = 12.667709
07-12 17:45:00.742  6835  6835 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-12 17:45:00.742  6835  6835 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
07-12 17:45:00.742  6835  6835 D Mms/MethodReflector: getTelephonyProperty is called
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: auto download without roaming -> true
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: auto download during roaming secondary -> false
07-12 17:45:00.742  6835  6835 D Mms/DownloadManager: mAutoDownload ------> true
,07-12 17:45:00.762  6738  6738 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,07-12 17:45:00.782  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-12 17:45:00.782  1017  1058 D PackageManager: userId{-1}
07-12 17:45:00.782  1017  1058 D PackageManager: andCode{true}
,07-12 17:45:00.782  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,07-12 17:45:00.802  6835  6835 D ComposerPerformance: 1468338300810 ms / [DONE] Composer constructor
,07-12 17:45:00.802  6835  6835 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,07-12 17:45:00.802  6835  6835 I Mms/ReservationManager: ReservationManager()
07-12 17:45:00.802  6835  6835 I Mms/ReservationManager: resetAfterConnected()
,07-12 17:45:00.802  1454  1471 D TP/MmsSmsProvider: query,matched:7, calling pid = 6835
,07-12 17:45:00.802  1454  1471 D TP/MmsSmsProvider: match 7:Elapsed time : 1.957 ms
,07-12 17:45:00.812  6835  6835 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,07-12 17:45:00.812  6835  6859 D Mms/Conversation: [start]    init() consume time = 67.345937
,07-12 17:45:00.812  6835  6835 D Mms/MmsApp: [end]    onCreate() consume time = 2.118229
,07-12 17:45:00.812  1454  1474 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
07-12 17:45:00.812  6835  6835 D Mms/UIEventReceiver: ui event
,07-12 17:45:00.812  1017  1030 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-12 17:45:00.812  6835  6835 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,07-12 17:45:00.812  6835  6835 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,07-12 17:45:00.822  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.822  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:00.822  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-12 17:45:00.822  1454  1474 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,07-12 17:45:00.822  6835  6835 D Mms/MethodReflector: getSubId is called
07-12 17:45:00.822  6835  6835 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
07-12 17:45:00.822  1454  1474 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,07-12 17:45:00.822  6835  6835 D Mms/MethodReflector: getTelephonyProperty is called
07-12 17:45:00.822  6835  6835 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-12 17:45:00.822  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-12 17:45:00.822  6835  6835 D Mms/DownloadManager: auto download without roaming -> true
07-12 17:45:00.822  6835  6835 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
07-12 17:45:00.822  6835  6835 D Mms/DownloadManager: mAutoDownload ------> true
,07-12 17:45:00.822  6770  6770 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
07-12 17:45:00.822  1454  1474 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,07-12 17:45:00.832  1017  1497 I ActivityManager: Killing 6384:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,07-12 17:45:00.832  1454  1474 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,07-12 17:45:00.832  1454  1474 D TP/MmsSmsProvider: need read changed broadcast:false
07-12 17:45:00.832  6835  6859 D Mms/Conversation: [end]    init consume time = 21.29474
,07-12 17:45:00.842  6835  6859 D Mms/MessagingNotification: [start]    init() consume time = 5.62526,
,07-12 17:45:00.842  2703  2703 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 12 17:45:00 GMT+02:00 2016
07-12 17:45:00.842  1017  3451 D SSRM:n  : SIOP:: AP = 320
,07-12 17:45:00.852  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
07-12 17:45:00.852  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-12 17:45:00.852  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:00.852  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:00.852  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-12 17:45:00.862  6835  6859 D Mms/MessagingNotification: [end]    init consume time = 16.008803
,07-12 17:45:00.862  2703  2703 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
07-12 17:45:00.862  6835  6861 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.333072
07-12 17:45:00.862  1017  1479 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,07-12 17:45:00.862  1017  1479 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-12 17:45:00.862  1017  1479 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-12 17:45:00.862  2703  2703 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,07-12 17:45:00.862  6835  6863 D Mms/Synchronizer: [start]    doSync consume time = 5.39448
,07-12 17:45:00.872  1017  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.872  2703  2703 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-12 17:45:00.872  1017  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.872  1017  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.872  1017  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.872  2703  2703 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-12 17:45:00.872  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-12 17:45:00.872  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-12 17:45:00.882  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-12 17:45:00.882  6864  6864 E Zygote  : MountEmulatedStorage()
,07-12 17:45:00.882  6864  6864 E Zygote  : v2
07-12 17:45:00.882  6864  6864 I libpersona: KNOX_SDCARD checking this for 10090
07-12 17:45:00.882  6864  6864 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:00.882  6864  6864 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-12 17:45:00.892  1017  1479 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6864 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
07-12 17:45:00.892  6864  6864 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:00.892  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest,
,07-12 17:45:00.892  1454  1471 D TP/MmsSmsProvider: update, matched:300, calling pid = 6835
07-12 17:45:00.892  1454  1471 V TP/MmsSmsProvider: syncDBData start
07-12 17:45:00.892  1454  1471 V TP/MmsSmsProvider: syncDBData sms end
07-12 17:45:00.892  1454  1471 V TP/MmsSmsProvider: syncDBData mms end
07-12 17:45:00.892  1454  1471 V TP/MmsSmsProvider: syncDBData end
,07-12 17:45:00.902  6864  6864 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:00.902  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,07-12 17:45:00.902  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:00.902  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.902  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.902  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:00.912   308   308 I art     : Explicit concurrent mark sweep GC freed 8675(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 625us total 26.826ms,
,07-12 17:45:00.912  6835  6835 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,07-12 17:45:00.922  6835  6850 D Mms/ArtClassLoader: init [DONE] art
,07-12 17:45:00.932   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 565us total 16.520ms,
,07-12 17:45:00.942  6864  6864 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-12 17:45:00.942  6864  6864 D ActivityThread: Added TimaKeyStore provider
,07-12 17:45:00.952   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 16.401ms
,07-12 17:45:00.962  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-12 17:45:00.972  6879  6879 E Zygote  : MountEmulatedStorage()
07-12 17:45:00.972  6879  6879 E Zygote  : v2
07-12 17:45:00.972  6879  6879 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:00.972  6879  6879 I libpersona: KNOX_SDCARD not a persona
,07-12 17:45:00.972  6879  6879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:00.972  2703  6862 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,07-12 17:45:00.972  6879  6879 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-12 17:45:00.972  1017  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6879 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-12 17:45:00.972  6879  6879 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:00.972  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,07-12 17:45:00.972  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.972  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 17:45:00.972  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
07-12 17:45:00.972  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 17:45:00.982  2703  6862 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
,07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:00.982  2703  6862 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528),
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-12 17:45:00.982  2703  6862 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 17:45:00.982  2703  6862 W SQLiteOpenHelper: Opened klms.db in read-only mode
07-12 17:45:00.982  2703  6862 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-12 17:45:00.982  2703  6862 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
07-12 17:45:00.992  6894  6894 E Zygote  : MountEmulatedStorage()
07-12 17:45:00.992  6894  6894 E Zygote  : v2
07-12 17:45:00.992  6894  6894 I libpersona: KNOX_SDCARD checking this for 1000
07-12 17:45:00.992  6894  6894 I libpersona: KNOX_SDCARD not a persona
07-12 17:45:00.992  6894  6894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-12 17:45:01.002  6879  6879 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 17:45:01.002  1017  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6894 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-12 17:45:01.002  6879  6879 D ActivityThread: Added TimaKeyStore provider
07-12 17:45:01.002  6894  6894 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-12 17:45:01.002  6894  6894 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 17:45:01.002  1017  1472 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-12 17:45:01.002  1017  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
07-12 17:45:01.002  1017  1472 W ActivityManager: userId = 0, bbcId = -10000
07-12 17:45:01.002  1017  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-12 17:45:01.002  1017  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms

```
