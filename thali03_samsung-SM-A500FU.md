#### Test 81418577b7b45c2_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main,
08-16 14:22:59.532   327   327 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 14:22:59.532   327   327 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-16 14:22:59.802  6173  6173 D AndroidRuntime: 
08-16 14:22:59.802  6173  6173 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 14:22:59.802  6173  6173 D AndroidRuntime: CheckJNI is OFF
08-16 14:22:59.802  6173  6173 D AndroidRuntime: readGMSProperty: start
08-16 14:22:59.802  6173  6173 D AndroidRuntime: readGMSProperty: already setted!!
08-16 14:22:59.802  6173  6173 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 14:22:59.802  6173  6173 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 14:22:59.802  6173  6173 D AndroidRuntime: readGMSProperty: end
08-16 14:22:59.802  6173  6173 D AndroidRuntime: addProductProperty: start
08-16 14:22:59.942  6173  6173 E AffinityControl: AffinityControl: registerfunction enter
08-16 14:22:59.962  6173  6173 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 14:22:59.972  1014  3292 E PersonaManagerService: inState():  stateMachine is null !!
08-16 14:22:59.972  1014  3292 I PersonaManagerService: PersonaId don't exist
08-16 14:22:59.972  1014  3292 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 14:22:59.982  1014  3292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-16 14:22:59.992  1014  1092 V AlarmManager: waitForAlarm result :8
08-16 14:22:59.992  1014  3292 W ActivityManager: mDVFSHelper.acquire()
08-16 14:23:00.002  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 14:23:00.002  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 14:23:00.002  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:00.002  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:00.002  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:00.002  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:00.022  6184  6184 E Zygote  : MountEmulatedStorage()
08-16 14:23:00.022  6184  6184 E Zygote  : v2
08-16 14:23:00.022  6184  6184 I libpersona: KNOX_SDCARD checking this for 10155
08-16 14:23:00.022  6184  6184 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:00.022  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 14:23:00.022  1014  3292 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6184 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 14:23:00.022  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 14:23:00.022  1014  3292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 14:23:00.022  1014  3292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:23:00.022  1014  3292 D InputDispatcher: Focused application set to: xxxx
08-16 14:23:00.022  1014  3292 D InputDispatcher: Focus left window: 3039
08-16 14:23:00.022  6173  6173 D AndroidRuntime: Shutting down VM
08-16 14:23:00.022   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 14:23:00.032  6184  6184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:00.032  6184  6184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:00.032  6184  6184 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 14:23:00.042  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:23:00.042  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 14:23:00.062  6184  6184 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:23:00.062  6184  6184 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:00.072  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 14:23:00.072  1014  1014 V ActivityManager: Display changed displayId=0
08-16 14:23:00.092  1014  1486 D PersonaManager: isKioskContainerExistOnDevice
08-16 14:23:00.112   257   450 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-16 14:23:00.112   257  1159 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-16 14:23:00.122  3039  3039 V ActivityThread: updateVisibility : ActivityRecord{3f49d301 token=android.os.BinderProxy@170d0fac {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-16 14:23:00.202  6184  6184 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-16 14:23:00.222  6184  6184 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9369-9370)
08-16 14:23:00.222  6184  6184 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:23:00.232  6173  6173 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 14:23:00.252  6184  6184 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {77c628d}
08-16 14:23:00.252  6184  6184 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 14:23:00.252  6184  6184 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 14:23:00.282  6184  6184 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 14:23:00.282  6184  6184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:23:00.292  6184  6184 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 14:23:00.312  6184  6184 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-16 14:23:00.312  6184  6184 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-16 14:23:00.312  6184  6184 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-16 14:23:00.312  6184  6184 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:23:00.312  6184  6184 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:23:00.312  6184  6184 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:23:00.312  6184  6184 I Adreno-EGL: Local Branch: 
08-16 14:23:00.312  6184  6184 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:23:00.312  6184  6184 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:23:00.312  6184  6184 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 14:23:00.382  6184  6212 D BluetoothAdapter: 1044383420: getState() :  mService = null. Returning STATE_OFF
08-16 14:23:00.432  6184  6210 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-16 14:23:00.472  6184  6184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:23:00.492  6184  6184 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 14:23:00.502  6184  6184 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 14:23:00.502  6184  6184 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-16 14:23:00.502  6184  6184 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-16 14:23:00.512  6184  6184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:23:00.512  6184  6184 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 14:23:00.552  6184  6223 D OpenGLRenderer: Render dirty regions requested: true
08-16 14:23:00.562  1014  1492 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 14:23:00.562  1014  1492 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 14:23:00.562  1014  1492 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 14:23:00.562  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 14:23:00.562  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 14:23:00.572   293   293 E SMD     : DCD OFF
08-16 14:23:00.572  6184  6184 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 14:23:00.572  6184  6184 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 14:23:00.582   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-16 14:23:00.592  1014  3002 D InputDispatcher: Focus entered window: 6184
08-16 14:23:00.592  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:23:00.592  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 14:23:00.592  6184  6184 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 14:23:00.592  6184  6223 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 14:23:00.602  6184  6223 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-16 14:23:00.602  6184  6223 D OpenGLRenderer: Enabling debug mode 0
08-16 14:23:00.642  6184  6184 V ActivityThread: updateVisibility : ActivityRecord{15f45ab5 token=android.os.BinderProxy@3179d59f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 14:23:00.672  1014  1132 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 14:23:00.672  1178  1178 D PanelView: There is/are notification(s) 
08-16 14:23:00.682  1014  6226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 14:23:00.682  6184  6184 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-16 14:23:00.682  6184  6184 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3179d59f time:109837
08-16 14:23:00.682  1790  1790 I SamsungIME: getCurrentCandidateView
08-16 14:23:00.692  1014  1044 I ActivityManager: Displayed Component not be shown by security: +592ms (total +688ms)
08-16 14:23:00.692  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ddde6a5 u0 com.test.thalitest/.MainActivity t128} time:109840
08-16 14:23:00.692  1014  1044 W ActivityManager: mDVFSHelper.release()
08-16 14:23:00.692   257  1159 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-16 14:23:00.692   257   447 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-16 14:23:00.742  6184  6184 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6184
08-16 14:23:00.772  1790  1790 D SamsungIME: Dismiss ExpandCandiate
08-16 14:23:00.852  6184  6184 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-16 14:23:00.902  1790  1790 I SamsungIME: getDebugLevel  : 0x4f4c
08-16 14:23:00.942  1790  1790 I SamsungIME: getDebugLevel  : 0x4f4c
08-16 14:23:00.952  1790  1790 I SamsungIME: KeybaordView init() : load resources
08-16 14:23:00.952  6184  6227 D jxcore_app_log: JniHelper::setJavaVM(0xb8299328), pthread_self() = -1199581808
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 14:23:00.962  6184  6227 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13325b25 added. We now have 1 listener(s)
08-16 14:23:00.972  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
08-16 14:23:00.972  6184  6227 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:00.972  6184  6227 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:00.972  6184  6227 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 14:23:00.982  1790  1790 I SamsungIME: getCurrentKeyboard
08-16 14:23:00.982  6184  6227 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@359ec508 added. We now have 1 listener(s)
08-16 14:23:00.982  1790  1790 I SamsungIME: getTextKeyboard
08-16 14:23:00.982  6184  6227 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:00.992  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 14:23:00.992  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 14:23:00.992  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 14:23:00.992  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 14:23:00.992  6184  6227 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 14:23:01.002  1790  1790 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-16 14:23:01.002  6184  6227 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:01.002  6184  6227 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
08-16 14:23:01.002  6184  6227 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:01.012  6184  6227 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:01.012  6184  6227 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 14:23:01.012  6184  6227 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:01.012  6184  6227 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:23:01.012  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:01.012  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:01.042  6184  6184 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 14:23:01.532  6184  6234 W jxcore-log: Initializing JXcore engine
08-16 14:23:01.532  6184  6234 W jxcore-log: JXcore engine is ready
,08-16 14:23:01.542  1790  6233 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 14:23:01.592  1889  1889 E audit   : type=1400 msg=audit(1471350181.592:205): avc:  denied  { ioctl } for  pid=6234 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-16 14:23:01.592  1889  1889 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:01.592  1889  1889 E audit   : type=1300 msg=audit(1471350181.592:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9dd008f8 items=0 ppid=311 ppcomm=main pid=6234 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 14:23:01.592  1889  1889 E audit   : type=1320 msg=audit(1471350181.592:205): 
,08-16 14:23:01.602  6184  6234 W jxcore-log: Starting JXcore engine,
,08-16 14:23:01.712  6184  6234 W jxcore-log: Platform android
08-16 14:23:01.712  6184  6234 W jxcore-log: 
08-16 14:23:01.712  6184  6234 W jxcore-log: Process ARCH arm
08-16 14:23:01.712  6184  6234 W jxcore-log: 
,08-16 14:23:01.892  6184  6234 I jxcore-log: JXcore Cordova bridge is ready!,
08-16 14:23:01.892  6184  6234 I jxcore-log: 
08-16 14:23:01.892  6184  6234 W jxcore-log: JXcore engine is started
,08-16 14:23:01.892  6184  6227 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 14:23:01.902  6184  6184 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 14:23:03.572   293   293 E SMD     : DCD OFF
,08-16 14:23:04.132  5365  5365 D FactoryTest: Not factory mode
,08-16 14:23:04.132  5365  5365 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 14:23:04.132  5365  5365 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-16 14:23:04.142  5365  5365 D MTPRx   : still no open session command from host, so toast
,08-16 14:23:04.142  5365  5365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-16 14:23:04.142  5365  5365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-16 14:23:04.142  5365  5365 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113292
,08-16 14:23:04.142  1014  1027 E PersonaManagerService: inState():  stateMachine is null !!
,08-16 14:23:04.142  1014  1027 I PersonaManagerService: PersonaId don't exist
08-16 14:23:04.142  1014  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 14:23:04.142  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 14:23:04.142  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:04.142  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:04.142  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 14:23:04.152  1014  1027 W ActivityManager: mDVFSHelper.acquire(),
,08-16 14:23:04.162  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:04.172  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:23:04.172  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 14:23:04.172  1014  1027 D InputDispatcher: Focused application set to: xxxx
,08-16 14:23:04.172  1014  1027 D InputDispatcher: Focus left window: 6184
08-16 14:23:04.172  5365  5365 E MTPRx   : started activity for popup
,08-16 14:23:04.172  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:23:04.172  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 14:23:04.202  5365  5365 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-16 14:23:04.202  5365  5365 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-16 14:23:04.202  5365  5365 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 14:23:04.202  5365  5365 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:04.212  5365  5365 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 14:23:04.212  5365  5365 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:23:04.222  5365  5365 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 14:23:04.232  1014  3290 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-16 14:23:04.232  1014  3290 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 14:23:04.232  1014  3290 D InputDispatcher: Focused application set to: xxxx
,08-16 14:23:04.232  1014  3290 D InputDispatcher: Focus entered window: 6184
,08-16 14:23:04.232  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 14:23:04.232  1014  1492 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 14:23:04.232  1014  1492 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@471b92c attribute=null, token = android.os.BinderProxy@2e7818fc
,08-16 14:23:04.232  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 14:23:04.272  5365  5365 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-16 14:23:04.282  5365  5365 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 14:23:04.282  5365  5365 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 14:23:04.302  6184  6184 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 14:23:04.302  6184  6184 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-16 14:23:04.302  6184  6184 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 14:23:04.302  6184  6184 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 14:23:04.302  1014  1701 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 14:23:04.302  1014  1701 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 14:23:04.302  1014  1701 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 14:23:04.302  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 14:23:04.302  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 14:23:04.312  6184  6184 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 14:23:04.312  6184  6184 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 14:23:04.322  6184  6184 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3179d59f time:113471
,08-16 14:23:04.322  6184  6184 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@342719f2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3ad89c90, 16908290=android.view.AbsSavedState$1@3ad89c90}, android:focusedViewId=100}]}]
,08-16 14:23:04.322  6184  6184 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 14:23:04.322  6184  6184 V ActivityThread: updateVisibility : ActivityRecord{15f45ab5 token=android.os.BinderProxy@3179d59f {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 14:23:04.322  6184  6184 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:23:04.322  6184  6184 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 14:23:04.332  1014  1216 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:04.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:05.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:06.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:06.572   293   293 E SMD     : DCD OFF,
,08-16 14:23:06.932  1014  1132 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 14:23:06.932  1014  1132 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4260, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 14:23:06.932  1014  1132 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 14:23:06.932  1014  1132 D BatteryService: stay LED for charging
08-16 14:23:06.932  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 14:23:06.932  1014  1014 I MotionRecognitionService: Plugged
,08-16 14:23:06.932  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 14:23:06.932  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 14:23:06.932  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 14:23:06.942  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-16 14:23:06.942  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 14:23:06.962  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:06.962  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:06.962  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:07.152  1014  1039 W ActivityManager: mDVFSHelper.release()
,08-16 14:23:07.182  1014  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-16 14:23:07.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:08.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:08.802  1014  2718 D SSRM:n  : SIOP:: AP = 320
,08-16 14:23:09.542   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-16 14:23:09.572   293   293 E SMD     : DCD OFF,
,08-16 14:23:10.052  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-16 14:23:10.852  1014  1092 V AlarmManager: waitForAlarm result :4,
,08-16 14:23:10.852  1014  1092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-16 14:23:10.862  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-16 14:23:10.862  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>,
08-16 14:23:10.862  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-16 14:23:10.872  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-16 14:23:10.882  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 14:23:10.882  1924  1924 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 14:23:10.892  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 14:23:10.892  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 14:23:10.902  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 14:23:10.902  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-16 14:23:10.902  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-16 14:23:10.922  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:10.922  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-16 14:23:10.922  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:10.922  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:10.922  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:10.942  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 14:23:10.952  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 14:23:10.962  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 14:23:10.982  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 14:23:10.982  3815  3815 D ConnectivityManager: CallingUid : 10012, CallingPid : 3815
,08-16 14:23:10.982  1014  3002 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:23:10.982  1014  1124 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-16 14:23:10.982  1014  1124 D ConnectivityService: apparently satisfied.  currentScore=60
,08-16 14:23:10.982  1014  1124 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-16 14:23:10.992  3815  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 14:23:11.042  3815  6246 W DriveInitializer: Background init thread started
,08-16 14:23:11.062   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 14:23:11.062   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:11.062  3815  6246 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 14:23:11.102  1014  1132 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:11.102  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.112  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.112  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.112  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.142  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:11.142  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.142  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.142  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:11.142  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.162  1014  1026 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-16 14:23:11.162  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.172  3815  6246 W DriveInitializer: Background init thread ended
,08-16 14:23:11.172  3815  6254 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-16 14:23:11.182  3815  6254 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 14:23:11.192  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:23:11.222  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.222  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.222  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.222  1014  1092 V AlarmManager: waitForAlarm result :4
,08-16 14:23:11.332  1014  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:11.332  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.332  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:11.332  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.332  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-16 14:23:11.362  1014  3290 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:11.362  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.362  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.362  1014  3290 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:11.362  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.412  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.412  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.412  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:11.412  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.432  1014  3287 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.432  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:11.432  1014  3287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.432  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.482  1014  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.482  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.482  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:11.482  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.492  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:11.492  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:11.492  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:11.492  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:11.502  6259  6259 E Zygote  : MountEmulatedStorage(),
08-16 14:23:11.502  6259  6259 E Zygote  : v2
08-16 14:23:11.502  6259  6259 I libpersona: KNOX_SDCARD checking this for 10012
,08-16 14:23:11.502  6259  6259 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:11.502  1014  1486 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6259 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-16 14:23:11.512  6259  6259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 14:23:11.512  6259  6259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 14:23:11.522  6259  6259 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:11.522   311   311 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 20.629ms
,08-16 14:23:11.542   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 17.285ms
,08-16 14:23:11.562  6259  6259 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:11.562  6259  6259 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:11.562   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.134ms
,08-16 14:23:11.572  6259  6259 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 14:23:11.572  6259  6259 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 14:23:11.612  1924  2119 I art     : Explicit concurrent mark sweep GC freed 57398(3MB) AllocSpace objects, 19(736KB) LOS objects, 39% free, 13MB/23MB, paused 1.660ms total 89.385ms
,08-16 14:23:11.622  6259  6259 I MultiDex: VM with version 2.1.0 has multidex support
08-16 14:23:11.622  6259  6259 I MultiDex: install
08-16 14:23:11.622  6259  6259 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 14:23:11.662  6259  6259 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 14:23:11.722  6259  6259 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 14:23:11.732  6259  6259 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@240ad89e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 14:23:11.732  6259  6259 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 14:23:11.742  6259  6259 D ChimeraCfgMgr: Reading stored module config
,08-16 14:23:11.822  6259  6273 I art     : Background sticky concurrent mark sweep GC freed 28562(1344KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 5.029ms total 65.018ms
,08-16 14:23:11.852  6259  6259 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 14:23:11.852  6259  6259 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 14:23:11.852  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-16 14:23:11.862  1014  3244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.862  6259  6276 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 14:23:11.862  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.862  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.862  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.872  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.872  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.872  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.872  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.912  1924  1924 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=54538b84-db3f-4676-92a8-38642a2382fc
,08-16 14:23:11.912  1014  1486 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 14:23:11.912  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 14:23:11.912  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.912  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:11.912  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:11.922  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:23:11.922  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 14:23:11.932  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:11.942  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:11.942  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:11.942  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:12.002   287   706 D WVCdm   : Instantiating CDM.
,08-16 14:23:12.002   287   287 I WVCdm   : CdmEngine::OpenSession
08-16 14:23:12.002   287   287 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 14:23:12.022   287   287 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 14:23:12.042   287   287 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-16 14:23:12.042   287   287 D DrmWidevineDash: Service_Initialize: starts!
08-16 14:23:12.042   287   287 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 14:23:12.042   287   287 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 14:23:12.042   287   287 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-16 14:23:12.042   287   287 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 14:23:12.042   287   287 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 14:23:12.042   287   287 D QSEECOMAPI: : App is not loaded in QSEE
08-16 14:23:12.042   287   287 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-16 14:23:12.042   287   287 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 14:23:12.042   287   287 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 14:23:12.042   287   287 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 14:23:12.062   287   287 D QSEECOMAPI: : Loaded image: APP id = 11
,08-16 14:23:12.062   287   287 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-16 14:23:12.072   287   287 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-16 14:23:12.072   287   287 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-16 14:23:12.072   287   287 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1750000
08-16 14:23:12.072   287   287 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1750000
08-16 14:23:12.072   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.072   427   439 D DrmLibTime: got the req here! ret=0
08-16 14:23:12.072   427   439 D DrmLibTime: command id, time_cmd_id = 770
08-16 14:23:12.072   427   439 D DrmLibTime: time_getutcsec starts!
08-16 14:23:12.072   427   439 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-16 14:23:12.072   427   439 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-16 14:23:12.072   427   439 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-16 14:23:12.072   427   439 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-16 14:23:12.092   427   439 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-16 14:23:12.092   427   439 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-16 14:23:12.092   427   439 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-16 14:23:12.092  6259  6267 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-16 14:23:12.092  6259  6267 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 14:23:12.092  6259  6267 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 14:23:12.092  6259  6267 I System.out: (HTTPLog)-Thread-1046-154078227: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 14:23:12.092  6259  6267 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 14:23:12.092   427   439 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-16 14:23:12.092   331   421 D QC-time-services: Daemon: Connection accepted:time_genoff
08-16 14:23:12.092   331  6283 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
,08-16 14:23:12.092   331  6283 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-16 14:23:12.092   280   962 D EnterpriseController: uids 10012
08-16 14:23:12.092   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:12.092   280   962 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:23:12.092   331  6283 D QC-time-services: offset is: 0 for base: 0
08-16 14:23:12.092   427   439 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-16 14:23:12.092   427   439 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-16 14:23:12.092   427   439 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471350192
08-16 14:23:12.092   427   439 D DrmLibTime: time_getutcsec returns 0, sec = 1471350192; nsec = 0
08-16 14:23:12.092   427   439 D DrmLibTime: time_getutcsec finished! 
08-16 14:23:12.092   427   439 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-16 14:23:12.092   427   439 D DrmLibTime: before calling ioctl to read the next time_cmd
08-16 14:23:12.092   331   421 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-16 14:23:12.092   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:23:12.092  6259  6267 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:23:12.102  6259  6267 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6259, getuid(): 10012
,08-16 14:23:12.112   287   287 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-16 14:23:12.112   287   287 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 14:23:12.112   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.112   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.112   287   287 D DrmWidevineDash: hlos api version =  9
08-16 14:23:12.112   287   287 D DrmWidevineDash: tz api version =  9
08-16 14:23:12.112   287   287 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,08-16 14:23:12.112   287   287 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-16 14:23:12.112   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.122  1653  1721 I art     : Explicit concurrent mark sweep GC freed 1373(46KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 682us total 26.466ms
,08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-16 14:23:12.132   287   287 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbedda1b0
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7e2e050, dataLength=8
08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-16 14:23:12.132   287   287 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7e1d9d8, wrapped_rsa_key_length=1280
08-16 14:23:12.132   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.142   287   287 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:23:12.142   287   287 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-16 14:23:12.142   287   287 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 14:23:12.142   287   706 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-16 14:23:12.142   287   706 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-16 14:23:12.142   287   706 I WVCdm   : CdmEngine::GenerateKeyRequest
08-16 14:23:12.142   287   706 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7df1548, idLength=0xb18a4730
08-16 14:23:12.142   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb18a4746, maximum = 0xb18a4747
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.152   287   706 D DrmWidevineDash: hlos api version =  9
08-16 14:23:12.152   287   706 D DrmWidevineDash: tz api version =  9
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18a47b4
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-16 14:23:12.152   287   706 D WVCdm   : PrepareKeyRequest: nonce=3305205820
08-16 14:23:12.152   287   706 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7e21048
08-16 14:23:12.152   287   706 D DrmWidevineDash: message_length=1599, signature=0xb7de01b8, signature_length=0xb18a4714
08-16 14:23:12.152   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.232  1924  2107 W GCoreFlp: No location to return for getLastLocation()
,08-16 14:23:12.262  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:12.262  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:12.262  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:12.262  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:12.272  1014  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:12.272  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:12.272  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:12.272  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:12.272  1014  3244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:12.272  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:12.272  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:12.272  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:12.292  3815  6255 D UdcContextInitService: registered all accounts: true
,08-16 14:23:12.302  1924  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 14:23:12.312   287   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.312   287   706 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
08-16 14:23:12.312  1924  2126 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-16 14:23:12.312   287   694 I WVCdm   : CdmEngine::CloseSession
,08-16 14:23:12.312   287   694 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-16 14:23:12.312   287   694 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.312   287   694 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 14:23:12.312   287   694 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-16 14:23:12.312   287   694 I WVCdm   : L3 Terminate.
08-16 14:23:12.312   287   694 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-16 14:23:12.312   287   694 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 14:23:12.312   287   694 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 14:23:12.312   287   694 D DrmWidevineDash: Service_Uninitialize: starts!
08-16 14:23:12.312   287   694 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-16 14:23:12.312   287   694 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-16 14:23:12.312   287   694 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-16 14:23:12.312   287   694 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-16 14:23:12.342  6259  6267 I qtaguid : Untagging socket 30
,08-16 14:23:12.572   293   293 E SMD     : DCD OFF
,08-16 14:23:12.632  1014  3002 I art     : Explicit concurrent mark sweep GC freed 34924(1879KB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 27MB/41MB, paused 3.422ms total 154.430ms
,08-16 14:23:12.652  1014  1307 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 14:23:12.652  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 14:23:12.652  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:12.652  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:12.652  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:12.772  6288  6288 I dex2oat : ----------------------------------------------------
08-16 14:23:12.772  6288  6288 I dex2oat : <SS>: S T A R T I N G . . .
08-16 14:23:12.772  6288  6288 I dex2oat : <SS>: Zip is absent. Canceled.
,08-16 14:23:12.772  6288  6288 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 14:23:12.802  6288  6288 I dex2oat : dex2oat took 25.371ms (threads: 4)
,08-16 14:23:12.812  6259  6267 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-16 14:23:12.812  6259  6267 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:23:12.812  6259  6267 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:23:12.812  6259  6267 I Adreno-EGL: Local Branch: 
08-16 14:23:12.812  6259  6267 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:23:12.812  6259  6267 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:23:12.812  6259  6267 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:23:12.892  6259  6267 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:23:12.892  6259  6267 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:23:12.892  6259  6267 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:23:12.892  6259  6267 I Adreno-EGL: Local Branch: 
08-16 14:23:12.892  6259  6267 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:23:12.892  6259  6267 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:23:12.892  6259  6267 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:23:12.982  6259  6267 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-16 14:23:12.982  6259  6267 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:23:12.982  6259  6267 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:23:12.982  6259  6267 I Adreno-EGL: Local Branch: 
08-16 14:23:12.982  6259  6267 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:23:12.982  6259  6267 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:23:12.982  6259  6267 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:23:13.322  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 14:23:13.322  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 14:23:13.322  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.322  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.322  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.332  1924  6257 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:13.342   280   962 D EnterpriseController: uids 10012
08-16 14:23:13.342   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:13.342   280   962 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:23:13.342  1924  6257 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:23:13.342  1924  6257 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:13.382  1924  6257 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:13.532  1014  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:13.532  1924  2126 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 14:23:13.532  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-16 14:23:13.542  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.542  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.542  1924  2126 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-16 14:23:13.542  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.542  1924  2126 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-16 14:23:12.415+0200, stopTime=2016-08-16 14:23:13.552+0200, duration=1137ms
,08-16 14:23:13.552  1924  6300 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:13.552   280   962 D EnterpriseController: uids 10012
08-16 14:23:13.552   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:13.552   280   962 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:23:13.552  1924  6300 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 14:23:13.552  1924  6300 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:13.602  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-16 14:23:13.602  1924  6300 I qtaguid : Tagging socket 76 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:13.672  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.672  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.672  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.672  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.702  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.702  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.702  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.702  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.742  1014  3292 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.742  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.742  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.742  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.742  1924  6306 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:23:13.742  1924  6304 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 14:23:13.742  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.742  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.742  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.742  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.772  1014  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.772  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.772  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.772  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.772  1924  6306 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:23:13.772  1924  6304 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 14:23:13.772  1014  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.772  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.772  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.772  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.802  1014  3290 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:13.802  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.802  1014  3290 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.802  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.802  1924  6306 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 14:23:13.802  1924  6304 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 14:23:13.802  1924  6304 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-16 14:23:13.822  1924  6304 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 14:23:13.932  1924  6304 I art     : Explicit concurrent mark sweep GC freed 41780(2MB) AllocSpace objects, 16(469KB) LOS objects, 39% free, 14MB/24MB, paused 1.500ms total 73.675ms
,08-16 14:23:13.932  1924  6300 I qtaguid : Untagging socket 73
,08-16 14:23:13.952  1014  3288 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:13.962  1014  1345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:13.962  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.recovery.AccountRecoveryUpdaterService; callingUser = 0; userId(target) = 0
,08-16 14:23:13.962  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:13.962  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:13.962  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:13.992  1924  2126 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-16 14:23:14.002  1924  6308 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 14:23:14.012  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.012   280   962 D EnterpriseController: uids 10012
08-16 14:23:14.012   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:14.012   280   962 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 14:23:14.012  1924  6304 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:23:14.022  1924  6304 I qtaguid : Tagging socket 85 with tag 1106541400000000{285627412,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.042  1924  6308 I GLSUser : Method not found getActionBar
,08-16 14:23:14.042  1924  6308 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.042  1924  6308 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:23:14.052  1924  6308 I qtaguid : Tagging socket 86 with tag 40100000000{1025,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.052  1924  6304 I qtaguid : Tagging socket 89 with tag 1106541400000000{285627412,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.082  1924  6308 I qtaguid : Tagging socket 92 with tag 40100000000{1025,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.272  1014  1486 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:14.272  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.282  1924  6304 I qtaguid : Tagging socket 85 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.342  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:14.342  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:14.342  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:14.402  1014  1216 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:14.412  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.412  1924  6304 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:14.542  1014  3244 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:14.572  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.572  1924  6304 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 14:23:14.572  1924  6304 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:14.612  1924  6304 I qtaguid : Tagging socket 84 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:14.822  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:14.822  1924  6304 I qtaguid : Tagging socket 85 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:14.992  1014  3288 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:15.002  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:15.002  1924  6304 I qtaguid : Tagging socket 85 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:15.082  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 14:23:15.082  6184  6234 I jxcore-log: 
,08-16 14:23:15.082  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 14:23:15.082  6184  6234 I jxcore-log: 
,08-16 14:23:15.082  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:15.082  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:15.082  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.082  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 14:23:15.092  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 14:23:15.092  6184  6234 I jxcore-log: 
,08-16 14:23:15.092  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-16 14:23:15.092  6184  6234 I jxcore-log: 
,08-16 14:23:15.132  1014  3287 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:15.142  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:15.142  1924  6304 I qtaguid : Tagging socket 85 with tag 1106583100000000{285628465,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:15.282  1014  3292 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 14:23:15.302  1924  6304 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:15.302  1924  6304 I qtaguid : Tagging socket 85 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1924, getuid(): 10012
,08-16 14:23:15.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:15.552  6184  6234 D ExecuteNativeTests: Running unit tests
,08-16 14:23:15.572   293   293 E SMD     : DCD OFF
,08-16 14:23:15.652  1924  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:15.652  1924  6299 I qtaguid : Tagging socket 73 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1924, getuid(): 10012
,08-16 14:23:15.652  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:15.652  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 added. We now have 2 listener(s)
,08-16 14:23:15.652  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:15.652  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:15.652  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:15.662  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:15.662  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e added. We now have 2 listener(s)
08-16 14:23:15.662  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:15.662  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:15.662  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:15.662  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:15.662  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:15.662  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.662  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.662  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:15.662  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:15.662  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:15.662  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:23:15.662  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:23:15.662  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 14:23:15.672  6184  6234 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 14:23:15.672  6184  6234 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:23:15.672  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:15.672  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 14:23:15.672  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.672  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.672  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.672  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:15.672  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 removed from the list
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.672  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e removed from the list
08-16 14:23:15.672  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:15.672  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.672  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
,08-16 14:23:15.672  6184  6234 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 14:23:15.672  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.672  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.672  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.672  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.672  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.672  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.672  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.672  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.672  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.672  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.672  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.682  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
,08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:23:15.682  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.682  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.682  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.682  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.682  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.682  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.682  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.682  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.682  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.682  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.682  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.682  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.682  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.682  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.682  6184  6234 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:15.692  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:15.692  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:15.692  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.692  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.692  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:15.692  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:15.692  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:15.692  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:15.692  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-16 14:23:15.692  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-16 14:23:15.692  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:15.692  6184  6234 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:23:15.692  6184  6234 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:23:15.692  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-16 14:23:15.692  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.692  6184  6234 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-16 14:23:15.692  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.692  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.692  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:15.692  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.692  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:15.692  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:15.692  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:15.692  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:15.702  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:15.702  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.702  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.702  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.702  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:15.702  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.702  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.702  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.702  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.702  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.702  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.702  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.702  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.702  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.702  6184  6234 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:15.702  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:15.702  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:15.702  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.702  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.702  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:15.702  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:15.702  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:15.702  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 14:23:15.712  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:15.712  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-16 14:23:15.712  6184  6234 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: start: OK
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.712  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.712  6184  6234 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.712  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:15.712  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.712  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.712  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.712  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.712  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.712  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.712  6184  6234 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:23:15.722  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:23:15.722  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 14:23:15.722  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.722  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 14:23:15.722  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 14:23:15.722  6184  6234 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:23:15.722  6184  6234 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:23:15.722  6184  6234 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 14:23:15.722  6184  6234 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 14:23:15.722  6184  6234 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 14:23:15.722  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.722  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.722  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.722  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.722  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1132)
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6313 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1132
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.732  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 14:23:15.732  6184  6234 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:15.732  6184  6234 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 14:23:15.732  6184  6234 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 14:23:15.732  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:15.732  6184  6234 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 14:23:15.732  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.732  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.732  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.732  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.732  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-16 14:23:15.742  6184  6184 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6184 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.742  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:15.742  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.742  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 14:23:15.742  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 14:23:15.742  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.742  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.742  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.742  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.742  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.742  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.752  6184  6312 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.752  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.752  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thalipro,ject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:15.752  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:15.752  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115c16f9 not in the list
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:15.752  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:15.752  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:15.752  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30cbd63e not in the list
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:15.752  6184  6234 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 14:23:15.752  6184  6312 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 14:23:15.752  6184  6312 D BluetoothSocket: connect(): myUserId = 0
08-16 14:23:15.752  6184  6312 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:23:15.752  6184  6312 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@357990d8, channel: -1, state: INIT
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 14:23:15.752  6184  6312 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@357990d8, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:23:15.752  6184  6234 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 14:23:15.752  6184  6312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1132)
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 14:23:15.752  6184  6234 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 14:23:15.752  6184  6234 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 14:23:15.762  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:15.762  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2df4ac31 added. We now have 2 listener(s)
08-16 14:23:15.762  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:15.762  6184  6234 D BluetoothAdapter: enable()
,08-16 14:23:15.762  1014  1307 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 14:23:15.762  1014  1307 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:23:15.762  1014  1307 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.762  1014  1307 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.772  1014  1307 D SettingsProvider: name = bluetooth_on
08-16 14:23:15.772  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.772  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.772  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 14:23:15.772  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
08-16 14:23:15.772  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:15.772  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:15.772  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:15.772  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:15.782  1014  3286 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 14:23:15.782  1014  3286 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 14:23:15.782  1014  3286 D SecContentProvider2: mCursor = null
08-16 14:23:15.782  1014  3286 D WifiService: setWifiEnabled: true pid=6184, uid=10155
08-16 14:23:15.782  1014  3286 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.782  1014  3286 W WifiService: Failed getting userId using ActivityManagerNative
08-16 14:23:15.782  1014  3286 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.782  1014  3286 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:15.782  1014  3286 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 14:23:15.782  1014  3286 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 14:23:15.782  1014  3286 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 14:23:15.782  1014  3286 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:23:15.782  1014  3286 D SettingsProvider: name = wifi_on
08-16 14:23:15.782  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:15.782  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c8a6f16 added. We now have 3 listener(s)
08-16 14:23:15.782  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:15.792  6315  6315 E Zygote  : MountEmulatedStorage()
08-16 14:23:15.792  6315  6315 E Zygote  : v2
08-16 14:23:15.792  6315  6315 I libpersona: KNOX_SDCARD checking this for 1002
08-16 14:23:15.792  6315  6315 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:15.792  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.792  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.792  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:15.792  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35ce3097 added. We now have 4 listener(s)
08-16 14:23:15.792  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:15.792  6315  6315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:15.792  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:15.792  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2762e284 added. We now have 5 listener(s)
08-16 14:23:15.792  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:15.792  1014  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6315 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-16 14:23:15.792  6315  6315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:15.792  1014  1701 D WifiService: setWifiEnabled: false pid=6184, uid=10155
08-16 14:23:15.792  1014  1701 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 14:23:15.792  1014  1701 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 14:23:15.792  1014  1701 D SecContentProvider2: mCursor = null
08-16 14:23:15.792  1014  1701 D SettingsProvider: name = wifi_on
08-16 14:23:15.792  6315  6315 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:15.802  6184  6234 D BluetoothAdapter: enable()
08-16 14:23:15.802  1014  1122 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 14:23:15.802  2099  2099 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 14:23:15.802  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 14:23:15.802  2099  2099 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 14:23:15.802  2099  2099 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 14:23:15.802  1014  3288 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:23:15.802  1014  3288 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:15.802  1014  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 14:23:15.802  1014  3288 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:15.802  1014  3288 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.812  1014  3288 D SettingsProvider: name = bluetooth_on
,08-16 14:23:15.812  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:15.812  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.812  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.812  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
,08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 14:23:15.812  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:15.812  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:15.812  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 14:23:15.812  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:15.812  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:15.812  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:15.822  1014  1122 E WifiNative-wlan0: do suspend true
,08-16 14:23:15.832  6315  6315 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:15.832  6315  6315 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:15.842  6315  6315 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 14:23:15.852  6315  6315 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:23:15.892  6315  6315 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding GattService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding HidService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding HealthService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding PanService
08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 14:23:15.942  6315  6315 D BtSettings.ProfileConfig: Adding SapService
,08-16 14:23:15.952  6315  6315 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-16 14:23:15.952  6315  6315 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-16 14:23:15.952  6315  6315 D BtSettings.ProfileConfig: Adding SapClientService
,08-16 14:23:15.952  6315  6315 D BtSettings.ProfileConfig: Adding HidDevService
08-16 14:23:15.952  6315  6315 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 14:23:15.952  1014  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 14:23:15.952  1014  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:15.952  1014  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.952  1014  1216 D SettingsProvider: selectionArgs: false
,08-16 14:23:15.952  1014  1216 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.952  1014  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 14:23:15.952  1014  1216 D SettingsProvider: ret = -1
,08-16 14:23:15.952  1014  1216 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:15.962  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:15.962  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:15.962  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:15.962  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.962  1014  1492 D SettingsProvider: selectionArgs: false
,08-16 14:23:15.962  1014  1492 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.962  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:15.962  1014  1492 D SettingsProvider: ret = -1
,08-16 14:23:15.972  1014  1492 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:15.972  1014  3290 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:15.972  1014  3290 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:15.972  1014  3290 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.972  1014  3290 D SettingsProvider: selectionArgs: false
08-16 14:23:15.972  1014  3290 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.972  1014  3290 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:15.972  1014  3290 D SettingsProvider: ret = -1
,08-16 14:23:15.982  1014  3290 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:15.982  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-16 14:23:15.982  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:15.982  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.982  1014  1345 D SettingsProvider: selectionArgs: false
,08-16 14:23:15.982  1014  1345 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.982  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:15.982  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:15.982  1014  1345 D SettingsProvider: ret = -1
,08-16 14:23:15.992  1014  1345 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:15.992  1014  1307 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-16 14:23:15.992  1014  1307 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-16 14:23:15.992  1014  1307 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.992  1014  1307 D SettingsProvider: selectionArgs: false
08-16 14:23:15.992  1014  1307 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.992  1014  1307 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 14:23:15.992  1014  1307 D SettingsProvider: ret = -1
,08-16 14:23:15.992  1014  1307 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
08-16 14:23:15.992  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-16 14:23:15.992  1014  1701 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-16 14:23:15.992  1014  1701 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:15.992  1014  1701 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:15.992  1014  1701 D SettingsProvider: selectionArgs: false
,08-16 14:23:15.992  1014  1701 D SettingsProvider: selectionArgs: 1002
08-16 14:23:15.992  1014  1701 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 14:23:15.992  1014  1701 D SettingsProvider: ret = -1
,08-16 14:23:16.002  1014  1701 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.002  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.002  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.002  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.002  1014  1345 D SettingsProvider: selectionArgs: false
08-16 14:23:16.002  1014  1345 D SettingsProvider: selectionArgs: 1002
,08-16 14:23:16.002  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.002  1014  1345 D SettingsProvider: ret = -1
,08-16 14:23:16.002  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.002  1014  1345 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.012  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.012  1014  3286 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-16 14:23:16.012  1014  3286 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.012  1014  3286 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.012  1014  3286 D SettingsProvider: selectionArgs: false
08-16 14:23:16.012  1014  3286 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.012  1014  3286 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.012  1014  3286 D SettingsProvider: ret = -1
,08-16 14:23:16.012  1014  3286 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.012  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.012  1014  3290 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:16.012  1014  3290 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:16.012  1014  3290 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.012  1014  3290 D SettingsProvider: selectionArgs: false
08-16 14:23:16.012  1014  3290 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.012  1014  3290 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.012  1014  3290 D SettingsProvider: ret = -1
,08-16 14:23:16.022  1014  3290 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.022  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-16 14:23:16.022  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.022  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.022  1014  1492 D SettingsProvider: selectionArgs: false
08-16 14:23:16.022  1014  1492 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.022  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.022  1014  1492 D SettingsProvider: ret = -1
,08-16 14:23:16.022  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.032  1014  1492 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.032  1014  3292 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService,
08-16 14:23:16.032  1014  3292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.032  1014  3292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.032  1014  3292 D SettingsProvider: selectionArgs: false
08-16 14:23:16.032  1014  3292 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.032  1014  3292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.032  1014  3292 D SettingsProvider: ret = -1
,08-16 14:23:16.032  1014  3292 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.032  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.032  1014  1701 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 14:23:16.032  1014  1701 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.032  1014  1701 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.032  1014  1701 D SettingsProvider: selectionArgs: false
08-16 14:23:16.032  1014  1701 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.032  1014  1701 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.032  1014  1701 D SettingsProvider: ret = -1
,08-16 14:23:16.042  1014  1701 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.042  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.042  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.052  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.052  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.082  6315  6315 D BluetoothAdapterState: make
,08-16 14:23:16.082  6315  6315 I bluedroid: init
,08-16 14:23:16.082  6315  6331 I BluetoothAdapterState: Entering OffState
,08-16 14:23:16.092  6315  6315 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 14:23:16.092  6315  6315 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 14:23:16.092  6315  6315 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:23:16.092  6315  6315 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 14:23:16.102  6315  6315 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 14:23:16.102  6315  6315 I bluedroid: get_profile_interface socket
08-16 14:23:16.102  6315  6315 I bluedroid: get_profile_interface map_client
,08-16 14:23:16.102  6315  6315 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
08-16 14:23:16.102  6315  6334 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 14:23:16.102  6315  6334 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 14:23:16.102  6315  6334 E BluetoothServiceJni: populateRssiValuesNative
08-16 14:23:16.102  6315  6334 I bluedroid: getModelRssiValues
08-16 14:23:16.102  6315  6334 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 14:23:16.102  6315  6334 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-16 14:23:16.102  6315  6334 D BluetoothAdapterProperties: Name is: A5-1
,08-16 14:23:16.102  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 14:23:16.112  6315  6315 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:16.112  1014  1345 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp,
08-16 14:23:16.112  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:16.112  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 14:23:16.112  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.112  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.122  6315  6327 I bluedroid: config_hci_snoop_log
,08-16 14:23:16.122  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-16 14:23:16.122  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,08-16 14:23:16.122  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 14:23:16.122  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 14:23:16.122  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 14:23:16.122  6315  6315 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 14:23:16.132  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:16.132  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:16.142  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 14:23:16.142  6315  6331 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 14:23:16.142  6315  6331 D BluetoothAdapterProperties: Setting state to 11
,08-16 14:23:16.142  6315  6331 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 14:23:16.142  6315  6331 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:16.142  6315  6331 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 14:23:16.142  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 14:23:16.142  6315  6331 D BluetoothAdapterService: Autoconnection is available 
,08-16 14:23:16.142  6315  6331 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 14:23:16.152  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:16.152  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-16 14:23:16.152  6315  6331 D BluetoothSecureManager: getInstant: null
,08-16 14:23:16.152  6315  6331 D BluetoothSecureManager: calling getMethod for getService
08-16 14:23:16.152  6315  6331 D BluetoothSecureManager: calling getService
08-16 14:23:16.152  6315  6331 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1b23f19a
,08-16 14:23:16.152  1014  1492 D BluetoothSecureManagerService: isSecureModeEnabled
,08-16 14:23:16.152  1014  1492 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 14:23:16.162  6315  6331 D BtConfig.SecureMode: isSecureModeOn:false
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 14:23:16.162  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:16.162  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:16.162  1178  1178 D BluetoothTile:  getBluetoothState : 11
08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 14:23:16.162  1790  1790 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.162  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.162  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:16.172  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
08-16 14:23:16.172  6315  6331 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 14:23:16.172  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 14:23:16.172  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:16.172  6315  6331 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:16.172  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 14:23:16.172  6315  6331 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:16.172  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 14:23:16.172  6315  6331 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:16.172  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 14:23:16.172  6315  6331 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 14:23:16.172  1014  3292 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:16.172  1014  3287 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 14:23:16.172  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:16.172  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:16.172  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.182  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 14:23:16.182  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:16.182  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.182  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:16.182  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:16.182  6315  6331 D BluetoothBondStateMachine: make
,08-16 14:23:16.182  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 14:23:16.182  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 14:23:16.182  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 14:23:16.192  6315  6335 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:23:16.192  1014  3288 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:16.192  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.192  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.192  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:16.192  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:16.192  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:16.192  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 14:23:16.192  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:16.192  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:16.192  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:16.192  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.192  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.192  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.192  6315  6315 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:23:16.192  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.192  6315  6315 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:23:16.192  6315  6315 D BtGatt.GattService: start()
08-16 14:23:16.192  6315  6315 D BtGatt.GattService: start()
08-16 14:23:16.192  6315  6315 I bluedroid: get_profile_interface gatt
,08-16 14:23:16.192  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:16.192  6315  6315 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:23:16.202  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 14:23:16.202  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 14:23:16.202  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:16.202  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:16.202  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.202  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.202  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.202  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.202  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 14:23:16.202  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:16.202  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 14:23:16.212  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:16.212  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 14:23:16.212  1014  3290 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:16.212  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.212  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:16.212  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.212  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.222  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 14:23:16.222  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 14:23:16.222  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 14:23:16.222  6315  6315 D BtGatt.GattService: mStartError = false
08-16 14:23:16.222  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.222  1014  3002 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:16.222  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.222  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.222  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:16.222  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.232  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 14:23:16.232  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 14:23:16.232  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 14:23:16.232  6315  6315 D HeadsetService: Received start request. Starting profile...
08-16 14:23:16.232  6315  6315 D HeadsetService: start()
,08-16 14:23:16.232  1014  1701 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 14:23:16.232  6315  6315 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 14:23:16.232  6315  6315 D HeadsetStateMachine: make
,08-16 14:23:16.242  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 14:23:16.242  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:16.242  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.242  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.242  6315  6315 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 14:23:16.242  6184  6184 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-16 14:23:16.252  6340  6340 E Zygote  : MountEmulatedStorage()
,08-16 14:23:16.252  6340  6340 I libpersona: KNOX_SDCARD checking this for 10003
08-16 14:23:16.252  6340  6340 E Zygote  : v2
08-16 14:23:16.252  6340  6340 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:16.252  6340  6340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-16 14:23:16.252  1014  1701 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6340 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-16 14:23:16.252  1014  1132 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 14:23:16.252  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-16 14:23:16.252  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.252  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.252  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom,
08-16 14:23:16.252  1014  3286 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:16.252  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.252  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.252  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.252  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.262  6340  6340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:16.262  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.262  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.262  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 14:23:16.262  6340  6340 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:16.262  1014  1486 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 14:23:16.262  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.262  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.262  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.262  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-16 14:23:16.262  6315  6315 I bluedroid: get_profile_interface handsfree
,08-16 14:23:16.262  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:16.262  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.262  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:16.262  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.262  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.272  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 14:23:16.272  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 14:23:16.272  6315  6331 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 14:23:16.272  1014  3290 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:16.272  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.272  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.272  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:16.272  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:16.282  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:16.282  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 14:23:16.282  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 14:23:16.282  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 14:23:16.282  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 14:23:16.282  6315  6331 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:23:16.282  6315  6315 I DualScoManager: Instantiating Dual Sco Manager
08-16 14:23:16.282  6315  6315 I DualScoManager: Set HeadsetServiceHelper
08-16 14:23:16.292  6315  6315 D BluetoothAtMessage: createCMTIContentObservers
,08-16 14:23:16.292  1014  1486 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 14:23:16.292  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:16.292  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:16.292  1014  1486 D SettingsProvider: selectionArgs: false
08-16 14:23:16.292  1014  1486 D SettingsProvider: selectionArgs: 1002
08-16 14:23:16.292  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:16.292  1014  1486 D SettingsProvider: ret = -1
,08-16 14:23:16.292  1014  1486 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:16.302  6315  6339 D HeadsetStateMachine: Enter Disconnected: -2
08-16 14:23:16.302  6315  6315 D HeadsetService: mStartError = false
08-16 14:23:16.302  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.302  1014  1014 D BluetoothA2dp: Proxy object connected
,08-16 14:23:16.302  2823  2823 D BluetoothA2dp: Proxy object connected
08-16 14:23:16.302  6315  6339 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 14:23:16.302  6315  6339 D HeadsetStateMachine: map size, before remove : 0
08-16 14:23:16.302  6315  6339 D HeadsetStateMachine: map size, after remove: 0
,08-16 14:23:16.302  6315  6315 D A2dpService: Received start request. Starting profile...
08-16 14:23:16.302  6315  6315 D A2dpService: start()
08-16 14:23:16.312  6315  6315 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 14:23:16.312  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:16.312  6315  6315 I bluedroid: get_profile_interface avrcp
,08-16 14:23:16.312  6340  6340 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:16.312  6340  6340 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:16.322  6315  6315 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,08-16 14:23:16.342  6315  6315 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 14:23:16.342  6315  6356 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 14:23:16.342  6315  6315 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 14:23:16.342  6315  6315 D A2dpStateMachine: make
,08-16 14:23:16.342  6315  6315 I bluedroid: get_profile_interface a2dp
,08-16 14:23:16.342  6315  6360 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 14:23:16.342  6315  6315 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 14:23:16.342  6315  6315 D A2dpService: mStartError = false
08-16 14:23:16.342  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.352  6315  6315 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 14:23:16.352  6315  6359 D A2dpStateMachine: Enter Disconnected: -2
,08-16 14:23:16.352  6340  6340 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 14:23:16.352  6315  6315 D HidService: Received start request. Starting profile...
08-16 14:23:16.352  6315  6315 D HidService: start()
08-16 14:23:16.352  6315  6315 I bluedroid: get_profile_interface hidhost
08-16 14:23:16.352  6315  6315 D HidService: setHidService(): set to: null
08-16 14:23:16.352  6315  6315 D HidService: mStartError = false
08-16 14:23:16.352  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.352  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-16 14:23:16.352  6315  6315 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 14:23:16.352  6315  6315 D HealthService: Received start request. Starting profile...
08-16 14:23:16.352  6315  6315 D HealthService: start()
,08-16 14:23:16.362  6315  6315 I bluedroid: get_profile_interface health
,08-16 14:23:16.362  6315  6315 D HealthService: mStartError = false
08-16 14:23:16.362  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.362  6315  6315 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 14:23:16.362  6315  6356 D BluetoothMediaBrowser: no now playing list
,08-16 14:23:16.362  6315  6356 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 14:23:16.362  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 14:23:16.362  6315  6315 D PanService: Received start request. Starting profile...
08-16 14:23:16.362  6315  6315 D PanService: start()
08-16 14:23:16.362  6315  6315 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:23:16.362  6315  6315 I bluedroid: get_profile_interface pan
,08-16 14:23:16.362  6315  6315 D PanService: mStartError = false
08-16 14:23:16.362  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:16.362  6315  6315 D HeadsetStateMachine: Proxy object connected
,08-16 14:23:16.362  6315  6315 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 14:23:16.372  1431  1453 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 14:23:16.372  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-16 14:23:16.372  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 14:23:16.372  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 14:23:16.372  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 14:23:16.382  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 14:23:16.382  6340  6340 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-16 14:23:16.382  6340  6340 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 14:23:16.382  6340  6340 D UserAnalysis: Create SecureDbHelper
,08-16 14:23:16.392  1431  1431 W BluetoothHeadset: Proxy not attached to service
,08-16 14:23:16.392  1431  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 14:23:16.392  6315  6315 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 14:23:16.392  6315  6339 D HeadsetStateMachine: Disconnected process message: 11
,08-16 14:23:16.392  6340  6340 D IntelligenceServiceApplication: onCreate(),
,08-16 14:23:16.392  6315  6315 D BluetoothMapService: Received start request. Starting profile...
08-16 14:23:16.392  6315  6315 D BluetoothMapService: start()
,08-16 14:23:16.392  6315  6315 D BluetoothMapService: mStartError = false
08-16 14:23:16.392  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:16.392  6315  6315 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 14:23:16.402  6315  6315 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 14:23:16.402  6315  6339 D HeadsetStateMachine: Disconnected process message: 18
08-16 14:23:16.402  6315  6315 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-16 14:23:16.402  6315  6315 D SapService: Received start request. Starting profile...
08-16 14:23:16.402  6315  6315 D SapService: start()
08-16 14:23:16.402  6315  6315 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 14:23:16.402  6315  6315 I bluedroid: get_profile_interface sap
08-16 14:23:16.402  6315  6315 D SapService: mStartError = false
08-16 14:23:16.402  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:16.402  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 14:23:16.402  6315  6315 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 14:23:16.402  6315  6315 D BluetoothA2dp: Proxy object connected
08-16 14:23:16.402  6315  6315 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 14:23:16.402  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 14:23:16.402  6315  6339 D HeadsetStateMachine: Disconnected process message: 10
08-16 14:23:16.402  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 14:23:16.402  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 14:23:16.402  6315  6339 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:23:16.402  6315  6339 D HeadsetStateMachine: Disconnected process message: 11
,08-16 14:23:16.402  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 14:23:16.412  1014  3290 I ActivityManager: Killing 5274:com.google.android.talk/u0a104 (adj 15): empty #31
,08-16 14:23:16.422  6340  6340 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 14:23:16.422  1014  1345 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,08-16 14:23:16.422  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.422  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:16.422  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:16.422  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.432  6365  6365 E Zygote  : MountEmulatedStorage()
08-16 14:23:16.432  6365  6365 I libpersona: KNOX_SDCARD checking this for 10145
08-16 14:23:16.432  6365  6365 E Zygote  : v2
08-16 14:23:16.432  6365  6365 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:16.432  6365  6365 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:16.442  1014  1345 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6365 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-16 14:23:16.442  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 14:23:16.442  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 14:23:16.442  6365  6365 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:16.442  6365  6365 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 14:23:16.452  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 14:23:16.462  6365  6365 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:16.462  6365  6365 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:16.472  6365  6365 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-16 14:23:16.472  6365  6365 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:16.472  6365  6365 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 14:23:16.472  6365  6365 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:16.472  6365  6365 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 14:23:16.522  1014  1492 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 14:23:16.542  1014  3288 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 14:23:16.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:16.582  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 14:23:16.582  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,08-16 14:23:16.592  1014  1132 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 14:23:16.592  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.592  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
08-16 14:23:16.592  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:16.592  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:16.592  1014  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:16.602  6387  6387 E Zygote  : MountEmulatedStorage()
08-16 14:23:16.602  6387  6387 E Zygote  : v2
08-16 14:23:16.602  6387  6387 I libpersona: KNOX_SDCARD checking this for 10107
08-16 14:23:16.602  6387  6387 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:16.602  6387  6387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:16.602  6387  6387 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:16.602  1014  1132 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6387 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-16 14:23:16.612  6387  6387 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:16.612  1014  1701 I ActivityManager: Killing 4958:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-16 14:23:16.622  1014  1121 D WifiP2pService: InactiveState{ what=143375 }
,08-16 14:23:16.622  6315  6331 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 14:23:16.622  1014  1121 D WifiP2pService: P2pEnabledState{ what=143375 }
08-16 14:23:16.622  6315  6331 I bluedroid: enable
,08-16 14:23:16.622  6315  6331 I bt_hci_bdroid: init
,08-16 14:23:16.622   280   966 D CommandListener: Clearing all IP addresses on wlan0,
08-16 14:23:16.632  1924  4413 V NativeCrypto: Read error: ssl=0xb8780760: I/O error during system call, Connection timed out
08-16 14:23:16.632  5926  5931 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 14:23:16.632  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 14:23:16.632  6315  6331 I bt_vendor: bt-vendor : init
08-16 14:23:16.632  6315  6331 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:23:16.632  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 14:23:16.632  6315  6331 E bt_vendor: get_bt_soc_type: Failed to get soc type,
08-16 14:23:16.632  6315  6331 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 14:23:16.632  6315  6331 D bt_userial_mct: userial_init
08-16 14:23:16.632  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:16.632  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:16.632  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 14:23:16.632  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:16.632  6315  6331 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:23:16.632  6315  6331 I bt_vendor: Starting hciattach daemon
08-16 14:23:16.632  6315  6331 I bt_vendor: try to set false,
08-16 14:23:16.632  1924  6299 I qtaguid : Untagging socket 73
08-16 14:23:16.642  1014  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:23:16.632  6315  6331 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:23:16.642  1014  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-16 14:23:16.632  6315  6331 I bt_vendor: Starting hciattach daemon,
08-16 14:23:16.632  6315  6331 I bt_vendor: try to set true
08-16 14:23:16.642  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:16.642  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:16.642  6315  6396 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 14:23:16.642  6387  6387 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 14:23:16.642  6387  6387 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:16.642  1014  1121 D WifiP2pService: InactiveState{ what=131204 }
08-16 14:23:16.642  1014  1122 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 14:23:16.642  1014  1121 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 14:23:16.642  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: FAILED,
08-16 14:23:16.652  1924  4413 V NativeCrypto: SSL shutdown failed: ssl=0xb8780760: I/O error during system call, Broken pipe
,08-16 14:23:16.652  1924  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:16.652  1014  1132 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 14:23:16.652  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 14:23:16.652  1924  4413 E GCM     : Wifi connection closed with errorCode 20
,08-16 14:23:16.652  1014  1307 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-16 14:23:16.652  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:16.652  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:16.652  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 14:23:16.652  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:16.652  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-16 14:23:16.652  1014  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 14:23:16.652  1014  2216 I qtaguid : Tagging socket 362 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,08-16 14:23:16.662  1014  2216 I qtaguid : Untagging socket 362
08-16 14:23:16.662  1014  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:16.672  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:16.672  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:16.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:16.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:16.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:16.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:16.672  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:23:16.672  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:23:16.682  6409  6409 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:23:16.682  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-16 14:23:16.682  1014  1148 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:23:16.682  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:23:16.682  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,08-16 14:23:16.692  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
,08-16 14:23:16.692  1014  1121 D WifiP2pService: P2pDisablingState
08-16 14:23:16.692  1014  1121 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 14:23:16.692  1014  1121 D WifiP2pService: p2p socket connection lost
08-16 14:23:16.692  1014  1121 D WifiP2pService: P2pDisabledState
,08-16 14:23:16.692  1014  1122 E WifiNative-wlan0: do suspend true
,08-16 14:23:16.702  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 14:23:16.702  1014  1216 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 14:23:16.702  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 14:23:16.702  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 14:23:16.702  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 14:23:16.702  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:16.702  1014  1044 D WifiDisplayController: disconnect
08-16 14:23:16.702  1014  1044 D WifiDisplayController: updateConnection
08-16 14:23:16.702  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:16.702  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:16.702  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 14:23:16.712  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-16 14:23:16.712  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 14:23:16.712  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 14:23:16.712  5926  5931 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-16 14:23:16.712  5926  5931 D BadgeProvider: sendNotify, [notify] : null
08-16 14:23:16.712  5926  5931 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 14:23:16.712  5926  5931 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 14:23:16.712  5926  5931 D BadgeProvider: update, [UpdateCount] : 1
,08-16 14:23:16.712  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 14:23:16.712  1014  1486 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 14:23:16.712  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-16 14:23:16.712  1014  3002 D RCPManagerService: exchangeData() failure , invalid userId
08-16 14:23:16.712  1476  1476 D Launcher.Model: reloadBadges entered.
08-16 14:23:16.722  1014  1039 W BroadcastQueue: Failure sending broadcast Intent { act=android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED flg=0x40000010 (has extras) }
08-16 14:23:16.722  1014  1039 W BroadcastQueue: android.os.DeadObjectException
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1220)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:530)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:666)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:718)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 14:23:16.722  1014  1039 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 14:23:16.742  6418  6418 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 14:23:16.752  6419  6419 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 14:23:16.772  6421  6421 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 14:23:16.782  6422  6422 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 14:23:16.792  6423  6423 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 14:23:16.802  6424  6424 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 14:23:16.932  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-16 14:23:16.932  1014  3002 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 14:23:16.932  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.932  1014  1132 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,08-16 14:23:16.932  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 14:23:16.932  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:16.932  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:16.932  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 14:23:16.942  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.k.c(PG:583)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  6387  6387 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:16.982  6387  6387 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:16.982  1014  3287 I ActivityManager: Killing 5420:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-16 14:23:16.992  1014  1307 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-16 14:23:16.992  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 14:23:16.992  1014  1307 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4206, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 14:23:16.992  1014  1307 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 14:23:16.992  1014  1307 D BatteryService: stay LED for charging
08-16 14:23:16.992  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 14:23:17.002  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-16 14:23:17.002  1014  1014 I MotionRecognitionService: Plugged
08-16 14:23:17.002  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-16 14:23:17.002  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 14:23:17.002  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 14:23:17.012  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 14:23:17.012  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 14:23:17.022  6436  6436 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
08-16 14:23:17.022  6315  6315 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 14:23:17.022  6315  6339 D HeadsetStateMachine: Disconnected process message: 10
08-16 14:23:17.032  6438  6438 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 14:23:17.032  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 14:23:17.032  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 14:23:17.032  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 14:23:17.032  1014  3290 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:17.042  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 14:23:17.042  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.042  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.042  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 14:23:17.042  6315  6331 I bt_vendor: bluetooth satus is on
08-16 14:23:17.042  6315  6399 D bt_userial_mct: userial_open(port:0)
08-16 14:23:17.042  6315  6399 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-16 14:23:17.042  6387  6429 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-16 14:23:17.042  3614  3614 I Hs20UtilService: Starting #8
08-16 14:23:17.042  3614  3648 I Hs20UtilService: Message received 5007
08-16 14:23:17.042  6315  6399 I bt_vendor: Done intiailizing UART
08-16 14:23:17.052  6315  6399 I bt_vendor: Done intiailizing UART
08-16 14:23:17.052  6315  6399 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-16 14:23:17.052  6315  6399 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:23:17.052  6315  6442 D bt_userial_mct: Entering userial_read_thread()
08-16 14:23:17.052  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 14:23:17.052  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 14:23:17.052  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 14:23:17.052  6315  6396 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:23:17.052  6315  6396 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:23:17.062  6315  6396 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 14:23:17.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-16 14:23:17.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:17.062  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 14:23:17.062  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:17.062  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 14:23:17.062  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.062  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.062  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 14:23:17.072  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 14:23:17.072  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 14:23:17.072  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:17.072  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-16 14:23:17.072  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:17.072  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 14:23:17.072  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:17.072  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 14:23:17.082  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.082  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.082  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.082  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.092  6443  6443 E Zygote  : MountEmulatedStorage(),
08-16 14:23:17.092  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6443 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:23:17.092  6443  6443 E Zygote  : v2
08-16 14:23:17.092  6443  6443 I libpersona: KNOX_SDCARD checking this for 10068
08-16 14:23:17.092  6443  6443 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:17.092  6443  6443 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:17.092  6443  6443 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:17.102  6443  6443 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:17.112  6443  6443 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:17.112  6443  6443 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:17.132  6443  6443 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 14:23:17.142  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:17.142  6315  6396 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 14:23:17.142  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 14:23:17.142  6315  6396 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a16e9 
,08-16 14:23:17.142  6315  6396 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a16e9 
,08-16 14:23:17.152  6315  6334 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 14:23:17.152  6315  6334 E bt-btif : Calling BTA_HhEnable
,08-16 14:23:17.162  6315  6334 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 14:23:17.162  6315  6334 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-16 14:23:17.162  6315  6334 E BluetoothServiceJni: populateRssiValuesNative
,08-16 14:23:17.162  6315  6334 I bluedroid: getModelRssiValues
08-16 14:23:17.162  6315  6334 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 14:23:17.162  6315  6334 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 14:23:17.162  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 14:23:17.162  6315  6334 D BluetoothAdapterProperties: Name is: A5-1
,08-16 14:23:17.162  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.162  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:17.172  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:17.172  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.172  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.172  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:17.172  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:17.172  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.172  6315  6334 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 14:23:17.172  6315  6334 D BluetoothAdapterProperties: Scan Mode:20
08-16 14:23:17.172  6315  6334 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:17.172  6315  6334 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 14:23:17.172  6315  6334 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 14:23:17.172  6315  6334 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-16 14:23:17.172  6315  6334 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 14:23:17.172  6315  6334 E bt-btif : btif_sock_init: !vhci_init
08-16 14:23:17.172  6315  6334 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 14:23:17.182  6315  6442 E bt_mct  : hci lib postload completed
,08-16 14:23:17.182  6315  6334 D IOP_DB_BT: db_open: db_open : handle 3028394000l, read 13894 bytes onto local cache
08-16 14:23:17.182  6315  6334 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 14:23:17.182  6315  6334 D IOP_DB_BT: db_query: result 1
08-16 14:23:17.182  6315  6334 I         : iop_db_open: iop_db_open status 0
,08-16 14:23:17.182  6443  6443 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 14:23:17.182  6315  6334 D bte_conf: Device ID record 1 : primary
08-16 14:23:17.182  6315  6334 D bte_conf:   vendorId            = 0075
08-16 14:23:17.182  6315  6334 D bte_conf:   vendorIdSource      = 0001
08-16 14:23:17.182  6315  6334 D bte_conf:   product             = 0100
08-16 14:23:17.182  6315  6334 D bte_conf:   version             = 0200
08-16 14:23:17.182  6315  6334 D bte_conf:   clientExecutableURL = 
08-16 14:23:17.182  6315  6334 D bte_conf:   serviceDescription  = 
08-16 14:23:17.182  6315  6334 D bte_conf:   documentationURL    = 
08-16 14:23:17.182  6315  6334 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:23:17.182  6315  6334 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:23:17.182  1014  3292 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 14:23:17.182  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.182  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.182  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.182  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.202  6461  6461 E Zygote  : MountEmulatedStorage(),
,08-16 14:23:17.202  6461  6461 E Zygote  : v2
,08-16 14:23:17.202  6461  6461 I libpersona: KNOX_SDCARD checking this for 10069
08-16 14:23:17.202  6461  6461 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:17.202  1014  3292 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6461 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:17.202  6315  6331 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false,
08-16 14:23:17.202  6315  6331 D BluetoothAdapterProperties: ScanMode =  20
,08-16 14:23:17.202  6315  6331 D BluetoothAdapterProperties: State =  11
08-16 14:23:17.202  1014  3290 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 14:23:17.202  1014  3292 I ActivityManager: Killing 5023:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
08-16 14:23:17.202  6315  6331 D BluetoothAdapterProperties: Setting state to 12
08-16 14:23:17.202  6315  6331 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 14:23:17.202  6461  6461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:17.212  6461  6461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 14:23:17.212  6315  6334 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 14:23:17.212  6315  6334 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:23:17.212  6315  6334 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:17.212  6461  6461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:17.212  1014  1132 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 14:23:17.212  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:17.212  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:17.212  1014  1132 D SettingsProvider: selectionArgs: false
08-16 14:23:17.212  1014  1132 D SettingsProvider: selectionArgs: 1002
08-16 14:23:17.212  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:17.212  1014  1132 D SettingsProvider: ret = -1
,08-16 14:23:17.212  6184  6184 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 14:23:17.212  1014  1132 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-16 14:23:17.222  6315  6331 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:17.222  6315  6331 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 14:23:17.222  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:17.222  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.222  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:17.222  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.222  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.222  1178  1178 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-16 14:23:17.232  6184  6184 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 14:23:17.232  6315  6331 D BluetoothAdapterService: Autoconnection is available 
08-16 14:23:17.232  6184  6193 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.232  6184  6193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:17.232  6315  6331 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 14:23:17.232  6315  6349 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:17.232  6315  6331 D BluetoothAdapterService: starting service from this receiver
,08-16 14:23:17.232  6387  6395 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.232  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:17.232  6387  6395 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:17.232  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 14:23:17.232  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.232  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.232  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.232  6315  6331 I BluetoothAdapterState: Entering On State from state = 11
08-16 14:23:17.232  1455  1723 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.232  1455  1723 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:17.232  6184  6184 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 14:23:17.242  2823  2831 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:17.242  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:17.242  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.242  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:17.242  2823  2839 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.242  2823  2839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.242  6315  6327 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.242  6315  6327 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.242  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 14:23:17.242  1924  2114 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.242  1924  2114 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.242  6315  6315 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 14:23:17.252  1443  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.252  1443  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.252  1431  1442 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.252  1431  1442 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.252  1178  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:17.252  1178  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:17.252  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 14:23:17.252  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 14:23:17.252  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:17.252  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-16 14:23:17.252  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 14:23:17.252  6461  6461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:17.252  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.252  6461  6461 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:17.262  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@27d444fa, true,
08-16 14:23:17.262  1431  1431 D BluetoothHeadset: registerMessageListener
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.262  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 14:23:17.262  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-16 14:23:17.262  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 14:23:17.262  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:17.262  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-16 14:23:17.272  1790  1790 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:17.272  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.272  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:17.272  1014  1492 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:17.272  1014  1307 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 14:23:17.272  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:17.272  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:17.272  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:17.282  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:17.282  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:17.282  6315  6327 D HeadsetService: registerMessageListener
,08-16 14:23:17.282  6315  6327 D HeadsetService: registerMessageListener
,08-16 14:23:17.282  6315  6339 D HeadsetStateMachine: Disconnected process message: 70
,08-16 14:23:17.282  6315  6339 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2750d423
,08-16 14:23:17.282  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-16 14:23:17.282  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 14:23:17.292  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:17.292  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.292  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.292  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.292  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:17.292  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-16 14:23:17.292  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 14:23:17.292  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 14:23:17.302  6315  6339 D HeadsetStateMachine: Disconnected process message: 9
,08-16 14:23:17.302  6315  6339 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 14:23:17.302  6315  6315 I BluetoothPbapService: Handler(): got msg=1
,08-16 14:23:17.302  1014  3288 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 14:23:17.312   287   694 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-16 14:23:17.312   287   694 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 14:23:17.312   287   694 V voice   : voice_set_parameters: exit with code(-2)
08-16 14:23:17.312   287   694 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 14:23:17.312   287   694 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 14:23:17.312   287   694 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 14:23:17.312   287   694 V audio_hw_primary: adev_set_parameters: exit
,08-16 14:23:17.312  6315  6339 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 14:23:17.322  6315  6479 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 14:23:17.322  6315  6480 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 14:23:17.332  6461  6461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:17.332  6315  6479 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 14:23:17.332  6315  6479 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:23:17.332  6315  6479 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-16 14:23:17.332  6315  6479 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:17.332  6315  6479 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:17.332  6315  6479 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed28f7f
08-16 14:23:17.332  6315  6479 D BluetoothSocket: channel: 19
08-16 14:23:17.332  6315  6479 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-16 14:23:17.332  6315  6480 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 14:23:17.332  6315  6480 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:17.332  6315  6480 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-16 14:23:17.332  6315  6480 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:17.332  6315  6480 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:17.332  6315  6480 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3299fb4c
08-16 14:23:17.332  6315  6480 D BluetoothSocket: channel: 5
,08-16 14:23:17.332  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.332  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.332  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-16 14:23:17.332  1014  3292 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-16 14:23:17.342  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.342  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.342  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:17.342  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:17.352  6484  6484 E Zygote  : MountEmulatedStorage()
08-16 14:23:17.352  6484  6484 I libpersona: KNOX_SDCARD checking this for 10104
08-16 14:23:17.352  6484  6484 E Zygote  : v2
08-16 14:23:17.352  6484  6484 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:17.352  6484  6484 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:17.352  1014  3292 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6484 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 14:23:17.352  1014  3292 I ActivityManager: Killing 5510:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-16 14:23:17.352  6484  6484 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:17.352  6484  6484 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:17.372  6484  6484 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:17.372  6484  6484 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:17.382  6484  6484 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:23:17.502  1014  1121 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 14:23:17.502  1014  1121 D WifiP2pService: DefaultState{ what=143375 }
,08-16 14:23:17.502   280   962 D EnterpriseController: uids 10012
08-16 14:23:17.502   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:17.502   280   962 D Netd    : getNetworkForDns: using netid 0 for uid 10012
08-16 14:23:17.502   280   966 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:17.512   280   962 D EnterpriseController: uids 1000
08-16 14:23:17.512   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:17.512   280   962 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 14:23:17.512  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:17.512  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:17.512  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.512  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.512  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.512  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:17.512  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 14:23:17.512  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 14:23:17.512  1014  1124 E NetdConnector: NDC Command {53 network destroy 502} took too long (868ms)
,08-16 14:23:17.512  1014  1124 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 14:23:17.512  1014  1124 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-16 14:23:17.512  1014  1124 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:23:17.512  1178  1691 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:23:17.512  1014  1124 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 14:23:17.512  1014  1124 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 14:23:17.512  1014  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 14:23:17.512  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 14:23:17.512  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 14:23:17.512  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 14:23:17.512  2099  2099 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 14:23:17.512  1014  1121 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 14:23:17.522  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 14:23:17.522  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-6ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:17.522  3815  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 14:23:17.522  1924  1924 E ctxmgr  : [BaseServerTask]Server task (WriteInterestRecordTask) got error response.
,08-16 14:23:17.522  1924  2126 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
,08-16 14:23:17.532  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:17.532  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:17.532  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.532  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.532  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.532  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:17.532  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 14:23:17.532  1014  1127 D Tethering: MasterInitialState.processMessage what=3
08-16 14:23:17.532  1014  1124 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 14:23:17.532  1014  1124 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-16 14:23:17.532  1014  1124 E ConnectivityService: updateNetworkInfo()
,08-16 14:23:17.532  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:17.532  1014  1124 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:23:17.532  1014  1122 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 14:23:17.532  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 14:23:17.542  1014  1119 V NetworkStats: updateIfacesLocked()
08-16 14:23:17.542  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.542  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
,08-16 14:23:17.542  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:17.542  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:17.542  1178  1178 D StatusBar.NetworkController: EthernetConnected: false,
08-16 14:23:17.542  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-16 14:23:17.542  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 14:23:17.542  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-16 14:23:17.542  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 14:23:17.542  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 14:23:17.542  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:17.542  1014  1122 D SecContentProvider2: mCursor = null
08-16 14:23:17.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:17.552  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.552  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.552  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.552  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.552  1014  1120 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-16 14:23:17.552  1014  1119 V NetworkStats: performPollLocked() took 17ms
08-16 14:23:17.552  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:17.562  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:17.562  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.562  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:17.562  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:17.562  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 14:23:17.562  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:17.562  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:17.562  1178  1178 D HotspotTile: onReceive : 0, 0
,08-16 14:23:17.562  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.572  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:17.582  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.582  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.582  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.582  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:17.592  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:17.592  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:17.642  6484  6511 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 14:23:17.642  6484  6511 I Babel   : MmsConfig.loadMmsSettings
08-16 14:23:17.642  6484  6511 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-16 14:23:17.642  6484  6511 I Babel   : MmsConfig.loadFromDatabase
,08-16 14:23:17.642  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.652  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.652  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.652  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.652  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.652  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.652  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.652  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 14:23:17.652  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.662  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.662  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.662  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.662  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.662  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.662  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.662  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.662  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.672  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.672  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.672  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.672  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.672  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.672  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 14:23:17.672  2099  2099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 14:23:17.672  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.672  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 14:23:17.672  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:17.672  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-16 14:23:17.672  6484  6511 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 14:23:17.672  6484  6511 I Babel   : MmsConfig.loadFromResources
08-16 14:23:17.672  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 14:23:17.682  6484  6511 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 14:23:17.682  6484  6511 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-16 14:23:17.692  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.692  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.692  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.692  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 14:23:17.692  1014  3287 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-16 14:23:17.692  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 14:23:17.692  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.692  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.692  1014  3287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.692  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 14:23:17.692  2099  2099 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-16 14:23:17.702  2099  2099 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 14:23:17.702  2099  2099 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 14:23:17.702  2099  2099 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 14:23:17.702  2099  2099 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 14:23:17.702  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 14:23:17.702  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:17.702  1014  1122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-16 14:23:17.702  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:17.702  1014  1127 D Tethering: InitialState.processMessage what=4
,08-16 14:23:17.702  1014  1127 E Tethering: No numeric data
,08-16 14:23:17.702  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 14:23:17.702  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:17.712  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:23:17.712  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:17.712  1014  1127 D Tethering: clearTetheredNotification()
,08-16 14:23:17.712  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:17.712  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-16 14:23:17.712  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:17.712  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
,08-16 14:23:17.712  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:17.712  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 14:23:17.712  1178  1178 D HotspotTile: updateTetherState():false, false
,08-16 14:23:17.712  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:17.712  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:17.712  6484  6484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:17.722  1014  1119 V NetworkStats: performPollLocked() took 8ms
08-16 14:23:17.722  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.722  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.722  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:17.752   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8b1e7c8
08-16 14:23:17.752   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-16 14:23:17.752   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
,08-16 14:23:17.752   271   314 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1196301000)
,08-16 14:23:17.762  1014  1492 I art     : Explicit concurrent mark sweep GC freed 47643(2MB) AllocSpace objects, 2(80KB) LOS objects, 33% free, 27MB/41MB, paused 2.700ms total 187.163ms,
,08-16 14:23:17.762  1014  1024 I art     : WaitForGcToComplete blocked for 133.029ms for cause HeapTrim,
,08-16 14:23:17.782  6484  6484 I Babel_StickerModule: App launched.
,08-16 14:23:17.802  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:17.802  1014  1307 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 14:23:17.802  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.802  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.802  1014  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.802  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:17.802   287   706 W QCamera2Factory: getCameraInfo: E, camera_id = 0
08-16 14:23:17.802   287   706 W QCamera2Factory: getCameraInfo: X,
,08-16 14:23:17.802   287   694 W QCamera2Factory: getCameraInfo: E, camera_id = 1,
08-16 14:23:17.802   287   694 W QCamera2Factory: getCameraInfo: X
,08-16 14:23:17.812   271   314 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-16 14:23:17.812   271   314 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 14:23:17.812   271   314 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1196301000) wakelock released: 1, error no: 0
08-16 14:23:17.812   271   314 I rmt_storage: 
,08-16 14:23:17.812   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8b1e7c8
,08-16 14:23:17.832  6484  6484 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 14:23:17.832  6484  6484 W AudioCapabilities: Unsupported mime audio/evrc
08-16 14:23:17.832  1291  1291 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 14:23:17.842  6484  6484 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 14:23:17.842  1291  1291 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:17.842  1014  1345 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:17.842  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.842  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.842  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.842  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.842  1291  1291 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 14:23:17.842  6484  6484 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-16 14:23:17.842  6484  6484 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-16 14:23:17.842  1291  1291 E BluetoothHeadset: BTStateChangeCB is registed
08-16 14:23:17.842  1291  1291 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 14:23:17.842  1014  1307 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:17.842  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 14:23:17.842  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.852  1014  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.852  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-16 14:23:17.852  1291  1291 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:17.852  1291  1291 D BluetoothMap: Create BluetoothMap proxy object
,08-16 14:23:17.852  6484  6484 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 14:23:17.852  1014  3287 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 14:23:17.852  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 14:23:17.852  6484  6484 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 14:23:17.852  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.852  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.852  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.852  6484  6484 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 14:23:17.852  6484  6484 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 14:23:17.852  1014  3292 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 14:23:17.852  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.852  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.852  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.852  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.862  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-16 14:23:17.862  1014  1486 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 14:23:17.862  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.862  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.862  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.862  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.862  1291  1291 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 14:23:17.872  1014  3290 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 14:23:17.872  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.872  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:17.872  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.872  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.872  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.872  6484  6484 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 14:23:17.872  6484  6484 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 14:23:17.872  1014  1132 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 14:23:17.872  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:17.872  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.872  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.872  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:17.872  1291  1291 D LocalBluetoothProfileManager: PANU : true
08-16 14:23:17.872  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
08-16 14:23:17.872  1291  1291 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 14:23:17.882  6484  6484 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 14:23:17.882  1291  1291 D DockEventReceiver: finishStartingService: stopping service
08-16 14:23:17.882  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
08-16 14:23:17.882  1291  1291 D BluetoothA2dp: Proxy object connected
08-16 14:23:17.882  1291  1291 D A2dpProfile: Bluetooth service connected
,08-16 14:23:17.882  6484  6484 W VideoCapabilities: Unsupported mime video/wvc1,
08-16 14:23:17.892  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:17.892  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-16 14:23:17.892  6484  6484 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 14:23:17.892  1291  1291 D HeadsetProfile: Bluetooth service connected
08-16 14:23:17.892  6484  6484 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 14:23:17.892  6484  6484 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 14:23:17.892  6484  6484 W VideoCapabilities: Unsupported mime video/mp43
,08-16 14:23:17.902  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:17.902  6315  6315 D BtConfig.SecureMode: isSecureModeOn:false
08-16 14:23:17.902  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:17.902  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
08-16 14:23:17.902  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.902  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.902  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:17.902  6484  6484 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 14:23:17.912  6484  6484 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-16 14:23:17.912  1291  1291 D BluetoothMap: Proxy object connected
08-16 14:23:17.912  1291  1291 D MapProfile: Bluetooth service connected
08-16 14:23:17.912  1291  1291 D BluetoothMap: getConnectedDevices()
,08-16 14:23:17.922  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:17.922  1014  3002 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:17.922  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-16 14:23:17.922  1291  1291 D BluetoothPbap: Proxy object connected
08-16 14:23:17.922  1291  1291 D PbapServerProfile: Bluetooth service connected
,08-16 14:23:17.922  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 14:23:17.922  2099  2099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 14:23:17.922  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.922  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 14:23:17.922  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-16 14:23:17.922  1014  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.922  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:17.932  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 14:23:17.932  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 14:23:17.932  1014  1122 E WifiConfigStore: setLastSelectedConfiguration -1
08-16 14:23:17.932  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-16 14:23:17.932  1291  1291 D SapProfile: Bluetooth service connected
08-16 14:23:17.932  1291  1291 D Bluetoothsap: getConnectedDevices()
08-16 14:23:17.932  1924  6530 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 14:23:17.932  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:17.942  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:17.942  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 14:23:17.942  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.942  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.942  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:17.942  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:17.942  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:17.942  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 14:23:17.942  1291  1291 D BluetoothInputDevice: Proxy object connected
08-16 14:23:17.942  1291  1291 D HidProfile: Bluetooth service connected
08-16 14:23:17.942  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:17.942  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:17.942  1178  1178 D HotspotTile: onReceive : 1, 0
,08-16 14:23:17.942  1924  2127 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:17.952  6484  6484 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 14:23:17.952  1014  3002 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:17.952  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.952  1014  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.952  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 14:23:17.952  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:17.952  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:17.962  1014  3288 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 14:23:17.962  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:17.962  1291  1291 D PanProfile: Bluetooth service connected
,08-16 14:23:17.972  1014  1345 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:17.972  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:17.972  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:17.972  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:17.972  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:17.972  3614  3614 I Hs20UtilService: Starting #9
08-16 14:23:17.972  1014  1701 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-16 14:23:17.972  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:17.972  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:17.972  1014  1701 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:17.972  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:17.982  1924  6530 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 14:23:17.982  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:17.982  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 14:23:17.992  6315  6534 D BluetoothSocket: bindListen(): myUserId = 0
08-16 14:23:17.992  6315  6534 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:17.992  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:17.992  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:17.992  6315  6534 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-16 14:23:17.992  6315  6534 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:17.992  6315  6534 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:17.992  6315  6534 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@279b5d76
,08-16 14:23:17.992  6315  6534 D BluetoothSocket: channel: 12
08-16 14:23:17.992  6315  6534 I BtOppRfcommListener: Accept thread started.
08-16 14:23:17.992  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 14:23:17.992  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:17.992  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 14:23:17.992  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:18.002  1014  3287 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:18.002  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:18.002  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.002  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.002  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:18.002  3614  3614 I Hs20UtilService: Starting #10
,08-16 14:23:18.002  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:18.002  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-16 14:23:18.002  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.002  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.002  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.002  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.022  6535  6535 E Zygote  : MountEmulatedStorage()
08-16 14:23:18.022  1014  1486 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6535 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 14:23:18.022  6535  6535 E Zygote  : v2
08-16 14:23:18.022  6535  6535 I libpersona: KNOX_SDCARD checking this for 1000
08-16 14:23:18.022  6535  6535 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:18.022  6535  6535 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:18.022  1014  3288 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-16 14:23:18.022  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-16 14:23:18.022  6535  6535 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:18.022  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.022  1014  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:18.022  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 14:23:18.022  6535  6535 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.032  1014  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:18.032  6484  6484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:18.042  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-16 14:23:18.052  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:18.052  6535  6535 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:23:18.052  3039  3039 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
08-16 14:23:18.052  6535  6535 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:18.062  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:18.062  3039  3039 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-16 14:23:18.062  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:18.082  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 14:23:18.092  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 14:23:18.092  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 14:23:18.092  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:18.092  1014  3287 I ActivityManager: Killing 5765:com.sec.pcw.device/1000 (adj 15): empty #31
,08-16 14:23:18.102  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:18.102  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.102  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.312  1014  1027 I ActivityManager: Killing 5783:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-16 14:23:18.522  1014  1041 D Tethering: interfaceRemoved wlan0
,08-16 14:23:18.522  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 14:23:18.542   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:18.572   293   293 E SMD     : DCD OFF,
,08-16 14:23:18.632  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.632  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.632  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.632  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.642  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.642  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.642  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.642  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.642  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.652  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.652  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.652  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.652  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.662  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.662  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.662  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.662  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.662  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 14:23:18.672  1014  1307 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:18.672  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:18.672  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.672  1014  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.672  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:18.682  3614  3614 I Hs20UtilService: Starting #11
08-16 14:23:18.682  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:18.682  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 14:23:18.682  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 14:23:18.682  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:18.682  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:18.692  1014  1701 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 14:23:18.692  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.692  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.692  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.692  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.702  6552  6552 E Zygote  : MountEmulatedStorage()
08-16 14:23:18.702  6552  6552 I libpersona: KNOX_SDCARD checking this for 1000
08-16 14:23:18.702  6552  6552 E Zygote  : v2
08-16 14:23:18.702  6552  6552 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:18.702  6552  6552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:18.712  6552  6552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 14:23:18.712  1014  1701 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6552 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 14:23:18.712  6552  6552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.722  6552  6552 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 14:23:18.732  6552  6552 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:18.752  6552  6552 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 14:23:18.752  6552  6552 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 14:23:18.752  6552  6552 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 14:23:18.762  6552  6552 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 14:23:18.762  6552  6552 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 14:23:18.762  6552  6552 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 14:23:18.762  6552  6552 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:18.762  1014  1701 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-16 14:23:18.762  6552  6567 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-16 14:23:18.762  1014  1701 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 14:23:18.762  1014  1701 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-16 14:23:18.762  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.762  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.762  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.762  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.782  6569  6569 E Zygote  : MountEmulatedStorage()
08-16 14:23:18.782  6569  6569 E Zygote  : v2
08-16 14:23:18.782  6569  6569 I libpersona: KNOX_SDCARD checking this for 10111
08-16 14:23:18.782  6569  6569 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:18.782  6569  6569 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1,
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6315, ws=null) (elapsedTime=1726)
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1475),
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1474)
08-16 14:23:18.782  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=1249)
,08-16 14:23:18.782  6569  6569 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:18.782  1014  1041 D Tethering: interfaceRemoved p2p0
08-16 14:23:18.782  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 14:23:18.782  6569  6569 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.792  1014  1701 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6569 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:18.792  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-16 14:23:18.792  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.792  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.792  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.792  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.812  6580  6580 E Zygote  : MountEmulatedStorage()
,08-16 14:23:18.812  6580  6580 I libpersona: KNOX_SDCARD checking this for 10009
08-16 14:23:18.812  6580  6580 E Zygote  : v2
08-16 14:23:18.812  6580  6580 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:18.812  6580  6580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:18.812  6580  6580 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:18.812  6580  6580 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.812  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 14:23:18.822  1014  1026 D WifiService: setWifiEnabled: true pid=6184, uid=10155
08-16 14:23:18.812  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 14:23:18.822  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:18.812  1014  1026 D SecContentProvider2: mCursor = null
08-16 14:23:18.822  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
08-16 14:23:18.822  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:18.822  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:18.822  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 14:23:18.822  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 14:23:18.822  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 14:23:18.822  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 14:23:18.822  6569  6569 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:23:18.822  1014  1026 D SettingsProvider: name = wifi_on
08-16 14:23:18.822  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6580 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:18.822  1014  1039 I ActivityManager: Killing 5798:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-16 14:23:18.822  1014  2718 D SSRM:n  : SIOP:: AP = 340
,08-16 14:23:18.832  6569  6569 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:18.832  1724  1724 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 14:23:18.842  6580  6580 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:18.842  6580  6580 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:18.852   311   311 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 853us total 28.666ms
,08-16 14:23:18.862  1724  1724 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-16 14:23:18.862  1724  1724 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-16 14:23:18.862  1724  1724 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-16 14:23:18.862  1724  1724 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 14:23:18.872   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 800us total 22.153ms
,08-16 14:23:18.872  1724  1724 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 14:23:18.882  1724  1724 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-16 14:23:18.882  1310  1762 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,08-16 14:23:18.882  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 14:23:18.882  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.882  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.882  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.882  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.882  1014  3292 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 14:23:18.892  1014  3290 D RCPManagerService: exchangeData() failure , invalid userId
08-16 14:23:18.892   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 18.400ms
,08-16 14:23:18.912  6600  6600 E Zygote  : MountEmulatedStorage(),
08-16 14:23:18.912  6600  6600 E Zygote  : v2
08-16 14:23:18.912  6600  6600 I libpersona: KNOX_SDCARD checking this for 10081
08-16 14:23:18.912  6600  6600 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:18.912  6600  6600 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:18.912  6600  6600 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 14:23:18.912  6600  6600 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.922  1014  1026 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6600 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 14:23:18.932  1724  1724 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-16 14:23:18.932  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 14:23:18.932  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:18.932  6600  6600 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:18.942  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:18.942  6600  6600 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:18.942  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:18.952  1014  1307 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-16 14:23:18.952  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.952  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.952  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:18.952  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:18.952  6569  6569 I MusicStore: Database version: 108,
,08-16 14:23:18.962  6621  6621 E Zygote  : MountEmulatedStorage(),
08-16 14:23:18.962  6621  6621 I libpersona: KNOX_SDCARD checking this for 10159
08-16 14:23:18.962  6621  6621 E Zygote  : v2
08-16 14:23:18.962  6621  6621 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:18.962  6621  6621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:18.972  6621  6621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 14:23:18.972  1014  1307 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6621 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:23:18.972  6621  6621 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 14:23:18.982  1014  1307 I ActivityManager: Killing 5478:com.sec.knox.bridge/1000 (adj 15): empty #31
08-16 14:23:18.982  1014  1216 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 14:23:18.982  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 14:23:18.982  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.982  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:18.982  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:18.992  3649  3649 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 14:23:18 GMT+02:00 2016
,08-16 14:23:18.992  1014  3290 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 14:23:18.992  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 14:23:18.992  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:18.992  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:18.992  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 14:23:18.992  3649  3649 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 14:23:19.002  1014  1307 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 14:23:19.002  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.002  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.002  6621  6621 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:23:19.002  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.002  1014  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.012  6621  6621 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:19.012  3649  3649 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 14:23:19.012  3649  3649 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 14:23:19.022  3649  3649 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 14:23:19.022  3649  6637 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 14:23:19.022  6639  6639 E Zygote  : MountEmulatedStorage()
08-16 14:23:19.022  6639  6639 E Zygote  : v2
08-16 14:23:19.022  6639  6639 I libpersona: KNOX_SDCARD checking this for 10034
08-16 14:23:19.022  6639  6639 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:19.022  6639  6639 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:19.032  1014  1307 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6639 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
08-16 14:23:19.032  3649  6637 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 14:23:19.032  6639  6639 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:19.032  6639  6639 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:19.032  3649  6637 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 14:23:19.042  3649  6637 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-16 14:23:19.042  3649  3649 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 14:23:19.062  6639  6639 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:19.062  6639  6639 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:19.072  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 14:23:19.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.082  6569  6569 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
08-16 14:23:19.082  6569  6569 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 14:23:19.082  6655  6655 E Zygote  : MountEmulatedStorage()
,08-16 14:23:19.082  6655  6655 E Zygote  : v2
08-16 14:23:19.082  6655  6655 I libpersona: KNOX_SDCARD checking this for 10113
08-16 14:23:19.082  6655  6655 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:19.082  6655  6655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:19.082  1014  1486 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6655 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:19.092  6655  6655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:19.092  6655  6655 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:19.092  1014  1492 I ActivityManager: Killing 5444:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-16 14:23:19.102  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:19.102  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.102  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:19.102  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.102  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:19.112  3815  3815 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 14:23:19.112  3815  4583 I iu.UploadsManager: num queued entries: 0
,08-16 14:23:19.112  3815  4583 I iu.UploadsManager: num updated entries: 0
08-16 14:23:19.112  3815  4583 I iu.SyncManager: NEXT; no task
,08-16 14:23:19.122  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:19.122  6655  6655 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:19.142  6569  6569 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 14:23:19.142  6639  6639 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 14:23:19.142  1014  1492 I ActivityManager: Killing 5826:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-16 14:23:19.162  3076  6670 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-16 14:23:19.162  3076  6670 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 14:23:19.162  3076  6670 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 14:23:19.162  3076  6670 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-16 14:23:19.162  3076  6670 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 14:23:19.162  5846  5846 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 14:23:19.172  1014  3002 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-16 14:23:19.172  6011  6011 I SA      : [DM] init START
08-16 14:23:19.172  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.172  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:19.172  1014  3002 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 14:23:19.172  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 14:23:19.182  6011  6011 I SA      : [DM] This device is not a Vodafone
,08-16 14:23:19.192  6569  6569 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 14:23:19.192  6569  6569 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@39d4d811: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 14:23:19.192  6569  6569 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 14:23:19.192  6569  6569 D AndroidMusic: GMSCore installation verified
,08-16 14:23:19.202  5846  6671 E SPPClientService: [[SystemStateMonitorService]] No Active Internet,
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 14:23:19.212  6011  6011 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 14:23:19.222  1014  3290 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:19.222  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-16 14:23:19.222  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.222  1014  3290 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.222  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.222  6011  6011 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 14:23:19.222  6011  6011 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-16 14:23:19.222  6011  6011 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-16 14:23:19.222  6011  6011 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-16 14:23:19.232  6011  6011 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-16 14:23:19.232  6011  6011 I SA      : [SCU] isHaveSA() - false
08-16 14:23:19.232  6011  6011 I SA      : support phone number id : false
08-16 14:23:19.232  6011  6011 I SA      : [DM] Supports Ref Jpn : true
,08-16 14:23:19.232  6011  6011 I SA      : [DM] init END
08-16 14:23:19.232  6011  6011 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-16 14:23:19.242  6569  6569 I ConfigStore: Config Database version: 1
,08-16 14:23:19.242  6011  6011 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-16 14:23:19.242  6011  6011 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 14:23:19.242  6011  6011 I SA      : [SLFUCHKMGR] constructor called
,08-16 14:23:19.252  6011  6011 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-16 14:23:19.252  6011  6011 I SA      : [OR] == isSIMCardReady false ==
,08-16 14:23:19.252  6011  6011 I SA      : [SCU] == networkStateCheck == false
08-16 14:23:19.252  6011  6011 I SA      : [OR] onReceive END
,08-16 14:23:19.252  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:19.292   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 14:23:19.292   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.292  6569  6569 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 14:23:19.292   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 14:23:19.292   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.302  6569  6569 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,08-16 14:23:19.302   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 14:23:19.302   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.302  6569  6569 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 14:23:19.312  1014  3287 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 14:23:19.312  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.312  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.312  1014  3287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.312  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.322  1014  1307 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 14:23:19.322  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-16 14:23:19.322  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.332  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.332  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.342  1014  3244 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:19.352  1014  3002 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:19.352  1014  1132 I AudioService: getStreamVolume 3 index 0
,08-16 14:23:19.362  6569  6569 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-16 14:23:19.362  6569  6569 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-16 14:23:19.382  1014  3292 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:19.382  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 14:23:19.382  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:19.382  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.382  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.392  1014  1132 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 14:23:19.392  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.392  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.392  1014  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.392  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.392  1014  3286 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:19.392  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.392  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.392  1014  3286 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.392  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.402  1014  3244 I ActivityManager: Killing 5746:com.android.mms/u0a46 (adj 15): empty #31
,08-16 14:23:19.402  1014  3287 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:19.412  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 14:23:19.422  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.422  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.422  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.422  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.422   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 14:23:19.422   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.422  6655  6683 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 14:23:19.432   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 14:23:19.432   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.432  6655  6683 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 14:23:19.432  6685  6685 E Zygote  : MountEmulatedStorage()
08-16 14:23:19.432  6685  6685 I libpersona: KNOX_SDCARD checking this for 10002
08-16 14:23:19.432  6685  6685 E Zygote  : v2
08-16 14:23:19.432  6685  6685 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:19.432  6685  6685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:19.432  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6685 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:19.442  6685  6685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:19.442  6685  6685 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:19.452  1014  1486 D CountryDetector: No listener is left
,08-16 14:23:19.462   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 14:23:19.462   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.462  6655  6692 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 14:23:19.462   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 14:23:19.462   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:19.462  6655  6692 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 14:23:19.462  1014  1216 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-16 14:23:19.462  6685  6685 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 14:23:19.462  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 14:23:19.462  6685  6685 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:19.462  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:19.462  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.462  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 14:23:19.472  6569  6569 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-16 14:23:19.472  1014  3286 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:19.472  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 14:23:19.472  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:19.472  1014  3286 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.472  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:19.482  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 14:23:19.482  1014  1122 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 14:23:19.512  1014  1307 I ActivityManager: Killing 5926:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,08-16 14:23:19.512  1014  1307 I ActivityManager: Killing 5905:com.sec.android.app.myfiles/u0a47 (adj 15): empty #32
,08-16 14:23:19.532  1014  3292 I ActivityManager: Killing 5960:com.wsomacp/u0a25 (adj 15): empty #31
,08-16 14:23:19.542   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 14:23:19.552  1014  3002 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-16 14:23:19.552  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.552  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.552  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.552  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.562  6707  6707 E Zygote  : MountEmulatedStorage(),
,08-16 14:23:19.572  6707  6707 E Zygote  : v2
,08-16 14:23:19.572  6707  6707 I libpersona: KNOX_SDCARD checking this for 1000
08-16 14:23:19.572  6707  6707 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:19.572  6707  6707 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:19.572  1014  3002 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6707 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-16 14:23:19.572  6707  6707 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 14:23:19.572  6707  6707 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:19.592  6707  6707 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:19.592  6707  6707 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:19.632  6707  6707 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 14:23:19.662  1014  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:19.662  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:19.662  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:19.662  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 14:23:19.682  6655  6655 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-16 14:23:19.692  6655  6655 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8847-8848)
,08-16 14:23:19.692  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:23:19.702  6655  6655 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {176ca54e}
,08-16 14:23:19.702  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 14:23:19.702  6655  6655 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 14:23:19.722  6655  6655 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 14:23:19.722  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 14:23:19.732  6655  6655 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 14:23:19.742  6655  6655 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 14:23:19.742  6655  6655 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-16 14:23:19.742  6655  6655 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-16 14:23:19.752  6655  6655 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 14:23:19.752  6655  6655 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 14:23:19.752  6655  6655 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 14:23:19.752  6655  6655 I Adreno-EGL: Local Branch: 
08-16 14:23:19.752  6655  6655 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 14:23:19.752  6655  6655 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 14:23:19.752  6655  6655 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 14:23:19.772  6707  6707 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-16 14:23:19.782  6707  6707 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-16 14:23:19.782  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:19.782  6707  6707 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
08-16 14:23:19.782  6707  6707 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-16 14:23:19.782  6707  6707 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 14:23:19.812  6655  6655 I NSApplication: Starting up...
,08-16 14:23:19.812  6655  6753 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 14:23:19.822  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 14:23:19.822  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.822  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:19.822  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.822  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:19.832  6758  6758 E Zygote  : MountEmulatedStorage(),
08-16 14:23:19.832  6758  6758 I libpersona: KNOX_SDCARD checking this for 10120
08-16 14:23:19.832  6758  6758 E Zygote  : v2
08-16 14:23:19.832  6758  6758 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:19.832  6758  6758 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:19.832  1014  1486 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6758 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:19.842  6758  6758 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:19.842  6758  6758 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 14:23:19.842  1014  1486 I ActivityManager: Killing 5983:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-16 14:23:19.862  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:19.862  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:19.862  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:19.862  1014  1041 D Tethering: interfaceAdded wlan0
,08-16 14:23:19.872  6758  6758 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:19.872  1014  1041 D Tethering: interfaceAdded p2p0
,08-16 14:23:19.872   280   966 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 14:23:19.872  1014  1127 E Tethering: No numeric data
08-16 14:23:19.872   280   966 D SoftapController: Softap fwReload - Ok
,08-16 14:23:19.872  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:23:19.872  1014  1127 D Tethering: clearTetheredNotification()
08-16 14:23:19.872  6758  6758 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:19.872  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 14:23:19.882  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:19.882  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-16 14:23:19.882   280   966 D CommandListener: Setting iface cfg
08-16 14:23:19.882   280   966 D CommandListener: Trying to bring down wlan0
08-16 14:23:19.882  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 14:23:19.882   280   966 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:19.882  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
08-16 14:23:19.882  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:19.882  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:19.882  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:19.882  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 14:23:19.882  1178  1178 D HotspotTile: updateTetherState():false, false
,08-16 14:23:19.882  1014  1122 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 14:23:19.892  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:19.892  1014  1119 V NetworkStats: performPollLocked() took 7ms
08-16 14:23:19.892  1014  1122 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 14:23:19.892  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:19.902  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 14:23:19.902  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:19.902  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:19.902  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:19.902  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:19.902  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:19.902  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 14:23:19.902  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 14:23:19.902  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:19.902  1178  1178 D HotspotTile: onReceive : 2, 0
,08-16 14:23:19.902  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:19.912  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:19.912  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:19.912  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 14:23:19.912  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:19.912  6758  6758 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:23:19.942  6774  6774 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 14:23:19.942  6774  6774 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:23:19.942  6774  6774 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 14:23:19.952  6774  6774 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-16 14:23:19.952   397   397 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6774,
08-16 14:23:19.952   397   397 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-16 14:23:19.952  6774  6774 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 14:23:19.952  6774  6774 I wpa_supplicant: ssSupport state is = 1,
08-16 14:23:19.952  6774  6774 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 14:23:19.952  6774  6774 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 14:23:19.952   397   397 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6774
08-16 14:23:19.952   397   397 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106,
,08-16 14:23:20.122   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-16 14:23:20.132  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-16 14:23:20.192  6774  6774 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 14:23:20.192  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 14:23:20.202  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-16 14:23:20.212   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6774
08-16 14:23:20.212   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 14:23:20.212  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 14:23:20.212  6774  6774 I wpa_supplicant: ssSupport state is = 1
08-16 14:23:20.212  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 14:23:20.212  6774  6774 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:20.212  6774  6774 E wpa_supplicant: SIM READ ERROR
08-16 14:23:20.212  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:20.212  6774  6774 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:20.212  6774  6774 E wpa_supplicant: SIM READ ERROR
08-16 14:23:20.212  6774  6774 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:20.212  6774  6774 I wpa_supplicant: wpa_default_ap_write_once
08-16 14:23:20.212  6774  6774 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 14:23:20.212  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:20.212  6774  6774 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 14:23:20.212  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 14:23:20.212  6774  6774 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:20.212  6774  6774 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:23:20.212  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:20.212  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:20.212  1014  1127 D Tethering: InitialState.processMessage what=4
,08-16 14:23:20.212  1014  1127 E Tethering: No numeric data,
08-16 14:23:20.222  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:23:20.222  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:20.222  1014  1127 D Tethering: clearTetheredNotification()
08-16 14:23:20.222  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
08-16 14:23:20.222  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:20.222  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:20.222  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:20.222  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 14:23:20.222  1178  1178 D HotspotTile: updateTetherState():false, false
,08-16 14:23:20.222  1014  1119 V NetworkStats: performPollLocked() took 3ms
08-16 14:23:20.222  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:20.222  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:20.222  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:20.232  1014  1701 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 14:23:20.232  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:20.232  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:20.232  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:20.232  1014  1701 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:20.252  6783  6783 E Zygote  : MountEmulatedStorage(),
08-16 14:23:20.252  6783  6783 E Zygote  : v2
08-16 14:23:20.252  6783  6783 I libpersona: KNOX_SDCARD checking this for 10125,
08-16 14:23:20.252  6783  6783 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:20.252  6783  6783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 14:23:20.252  6783  6783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:20.252  6783  6783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:20.262  1014  1701 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6783 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 14:23:20.262  1014  1701 I ActivityManager: Killing 5868:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-16 14:23:20.282  6774  6774 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 14:23:20.282  6783  6783 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:20.282  6783  6783 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:20.302  6783  6783 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 14:23:20.302  6783  6783 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 14:23:20.302  6783  6783 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:23:20.312  6783  6783 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:20.312  6783  6783 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-16 14:23:20.322  6783  6783 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 14:23:20.322  1014  3244 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.,
08-16 14:23:20.322  1014  3244 I ActivityManager: Killing 5813:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-16 14:23:20.332  1014  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:20.332  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:20.332  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:20.332  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:20.332  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:20.332  3614  3614 I Hs20UtilService: Starting #12
,08-16 14:23:20.332  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:20.342  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 14:23:20.342  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 14:23:20.342  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:20.342  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:20.542  6774  6774 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 14:23:20.552  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 14:23:20.562  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 14:23:20.562   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6774
08-16 14:23:20.562   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 14:23:20.562  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 14:23:20.562  6774  6774 I wpa_supplicant: ssSupport state is = 1
08-16 14:23:20.562  6774  6774 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 14:23:20.562  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 14:23:20.582  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 14:23:20.582   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6774
08-16 14:23:20.582   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 14:23:20.582  6774  6774 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 14:23:20.582  6774  6774 I wpa_supplicant: ssSupport state is = 1
08-16 14:23:20.582  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:20.582  6774  6774 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:20.582  6774  6774 E wpa_supplicant: SIM READ ERROR
08-16 14:23:20.582  6774  6774 I wpa_supplicant: wpa_default_ap_write_once
08-16 14:23:20.582  6774  6774 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-16 14:23:20.582  6774  6774 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-16 14:23:20.582  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:20.582  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:20.582  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-16 14:23:20.582  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 14:23:20.582  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-16 14:23:20.582  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 14:23:20.722  6774  6774 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 14:23:20.722  6774  6774 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 14:23:20.822  6774  6774 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-16 14:23:20.822  6774  6774 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-16 14:23:20.822  6774  6774 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 14:23:20.832  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-16 14:23:20.832  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-16 14:23:20.832  6774  6774 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 14:23:20.832  6774  6774 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 14:23:20.832  6774  6774 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:20.832  6774  6774 E wpa_supplicant: SIM READ ERROR,
08-16 14:23:20.842  6774  6774 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 14:23:20.862  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 14:23:20.862  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:20.862  1014  1041 D Tethering: interfaceStatusChanged p2p0, false,
,08-16 14:23:20.862  6774  6774 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 14:23:20.872  1014  1122 D WifiNative-wlan0: callSECApiInt - ID [210],
08-16 14:23:20.872  6774  6774 I wpa_supplicant: Skip scan - bUseNetwork false
08-16 14:23:20.872  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:20.872  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-16 14:23:20.872  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:20.872  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:20.872  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:20.872  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:20.882  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:20.882  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 14:23:20.882  1014  1122 D WifiConfigStore: Loading config and enabling all networks 
08-16 14:23:20.882  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:20.882  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:20.882  1178  1178 D HotspotTile: onReceive : 3, 0
,08-16 14:23:20.882  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:20.892  1014  1132 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:20.892  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 14:23:20.892  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:20.892  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:20.892  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:20.892  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:20.892  1014  1122 E WifiConfigStore: Not a HS20
,08-16 14:23:20.892  1014  1122 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 14:23:20.892  1014  1122 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:20.892  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:20.902  3614  3614 I Hs20UtilService: Starting #13
,08-16 14:23:20.902  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 14:23:20.902  6774  6774 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 14:23:20.902  6774  6774 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 14:23:20.902  6774  6774 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 14:23:20.902  6774  6774 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 14:23:20.902  6774  6774 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 14:23:20.902  6774  6774 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 14:23:20.902  6774  6774 I wpa_supplicant: First Scan Start
,08-16 14:23:20.902  6774  6774 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 14:23:20.902  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:20.902  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:20.902  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 14:23:20.902  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:20.902  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:20.902  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:20.902  1014  1122 D WifiNative-wlan0: Setting external_sim to 1
,08-16 14:23:20.912  1014  1122 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:23:20.912  1014  1122 I WifiNative-HAL: startHal
08-16 14:23:20.912  1014  1122 E wifi    : getStaticLongField sWifiHalHandle 0x9cc9e88c
08-16 14:23:20.912  1014  1122 I WifiNative-HAL: Could not start hal
,08-16 14:23:20.912  6484  6484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:20.912  1014  1122 E WifiNative-wlan0: do suspend true
,08-16 14:23:20.912  1014  1121 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 14:23:20.912  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-16 14:23:20.922  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-16 14:23:20.922  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:20.922  1014  1147 I WifiNative-HAL: startHal
08-16 14:23:20.922  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9ddfd9bc
08-16 14:23:20.922   280   966 D CommandListener: Setting iface cfg
08-16 14:23:20.922   280   966 D CommandListener: Trying to bring up p2p0
,08-16 14:23:20.922  1014  1147 I WifiNative-HAL: Could not start hal
08-16 14:23:20.922  1014  1147 E WifiScanningService: could not start HAL
,08-16 14:23:20.922  1014  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 14:23:20.922  1014  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 14:23:20.922  1014  1122 E WifiNative-wlan0: invaild command id : 215
08-16 14:23:20.922  1014  1121 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 14:23:20.922  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-16 14:23:20.922  1014  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:20.922  1014  1121 D WifiP2pService: P2pEnablingState
08-16 14:23:20.922  1014  1121 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 14:23:20.922  1014  1121 D WifiP2pService: P2p socket connection successful
08-16 14:23:20.922  1014  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 14:23:20.922  1014  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 14:23:20.922  1014  1122 E WifiNative-wlan0: invaild command id : 215
08-16 14:23:20.922  1014  1121 D WifiP2pService: P2pEnabledState
,08-16 14:23:20.922  1014  1124 E ConnectivityService: updateNetworkInfo()
,08-16 14:23:20.922  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 14:23:20.922  6774  6774 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 14:23:20.922  6774  6774 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 14:23:20.932  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 14:23:20.932  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:20.932  1014  1044 D WifiDisplayController: disconnect
08-16 14:23:20.932  1014  1044 D WifiDisplayController: updateConnection
08-16 14:23:20.932  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:20.932  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:20.932  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 14:23:20.932  6774  6774 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-16 14:23:20.932  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-16 14:23:20.932  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:20.932  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 14:23:20.932  1014  3002 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 14:23:20.932  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 14:23:20.932  1014  1121 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 14:23:20.932  1014  1121 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-16 14:23:20.942  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 14:23:20.942  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-16 14:23:20.942  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 14:23:20.942  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 14:23:20.942  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 14:23:20.942  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 14:23:20.942  1014  1121 D WifiP2pService: DeviceAddress: 7e:96:ac
08-16 14:23:20.942  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:20.942  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:20.942  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  secondary type: null
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  wps: 0
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  grpcapab: 0
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  devcapab: 0
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  status: 3
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  wfdInfo: null
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-16 14:23:20.942  1014  1044 D WifiDisplayController:  SConnectInfo : null
,08-16 14:23:20.942  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:20.952  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 14:23:20.952  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:20.952  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 14:23:20.952  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:20.952  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:20.952  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 14:23:20.952  6443  6443 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 14:23:20.962  6461  6461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:20.962  1014  1121 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 14:23:20.962  1014  1121 D WifiP2pService: InactiveState
,08-16 14:23:20.962  1014  1121 D WifiP2pService: InactiveState{ what=143376 }
,08-16 14:23:20.962  1014  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 14:23:20.962  6774  6774 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 14:23:20.962  1014  1121 D WifiP2pService: InactiveState{ what=143376 },
08-16 14:23:20.962  1014  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 14:23:21.582   293   293 E SMD     : DCD OFF,
,08-16 14:23:21.852  1014  1701 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 14:23:21.852  1014  1701 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 14:23:21.852  1014  1701 D SecContentProvider2: mCursor = null
,08-16 14:23:21.852  1014  1701 D WifiService: setWifiEnabled: false pid=6184, uid=10155
,08-16 14:23:21.852  1014  1701 D SettingsProvider: name = wifi_on
,08-16 14:23:21.872  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 14:23:21.872  1014  1121 D WifiP2pService: InactiveState{ what=131204 }
08-16 14:23:21.872  1014  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:21.872  1014  1121 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 14:23:21.872  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-16 14:23:21.872  1014  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler },
08-16 14:23:21.882  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:21.882  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 14:23:21.882  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 14:23:21.882  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-16 14:23:21.882  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 14:23:21.882  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 14:23:21.882  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 14:23:21.882  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:21.882  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 14:23:21.902  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 14:23:21.882  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:21.902  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 14:23:21.882  1014  1044 D WifiDisplayController: disconnect
08-16 14:23:21.902  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 14:23:21.882  1014  1044 D WifiDisplayController: updateConnection
08-16 14:23:21.882  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:21.882  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 14:23:21.882  1014  1121 D WifiP2pService: P2pDisablingState
08-16 14:23:21.882  1014  1121 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 14:23:21.882  1014  1121 D WifiP2pService: p2p socket connection lost
08-16 14:23:21.882  1014  1121 D WifiP2pService: P2pDisabledState
,08-16 14:23:21.902   280   966 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:21.902  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:21.902  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-16 14:23:21.902  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,08-16 14:23:21.902  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 14:23:21.902  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 14:23:21.902  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 14:23:21.902  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:21.902  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 14:23:21.902  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 14:23:21.902  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:21.902  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 14:23:21.902  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 14:23:21.912  6774  6774 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 14:23:21.912  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 14:23:21.922  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 14:23:21.922  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:21.922  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:21.922  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:21.922  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:21.922  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:21.922  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 14:23:21.922  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 14:23:21.922  6443  6443 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 14:23:21.932  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:21.932  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 14:23:21.932  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:21.932  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:21.932  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:21.932  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:21.932  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:21.942  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 14:23:21.942  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:21.942  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:21.942  1178  1178 D HotspotTile: onReceive : 0, 0
,08-16 14:23:21.942  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:21.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:21.952  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:21.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:21.952  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:21.962  6461  6461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:21.962  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 14:23:21.962  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:21.962  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:21.972  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 14:23:21.972  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:21.972  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 14:23:21.972  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:21.972  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:21.972  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 14:23:21.972  6443  6443 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 14:23:21.982  6461  6461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:21.982  1014  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:21.992  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:21.992  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:21.992  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:21.992  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:21.992  3614  3614 I Hs20UtilService: Starting #14
,08-16 14:23:21.992  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:21.992  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 14:23:21.992  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:21.992  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:22.002  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-16 14:23:22.002  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:22.002  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 14:23:22.002  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:22.002  1014  3244 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:22.002  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:22.002  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:22.012  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:22.012  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:22.012  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 14:23:22.012  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:22.012  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 14:23:22.012  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:22.012  3614  3614 I Hs20UtilService: Starting #15
,08-16 14:23:22.012  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:22.062  6774  6774 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:22.142  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 14:23:22.142  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-16 14:23:22.142  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:22.142  6774  6774 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 14:23:22.142  6774  6774 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED,
08-16 14:23:22.142  6774  6774 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-16 14:23:22.402  6774  6774 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:22.462  6774  6774 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-16 14:23:22.462  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:22.462  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:22.472  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:22.572  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-16 14:23:22.572  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 14:23:22.572  1014  1122 E WifiConfigStore: setLastSelectedConfiguration -1
08-16 14:23:22.572  6484  6484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:22.572  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 14:23:22.572  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 14:23:22.582  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:22.582  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:22.582  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 14:23:22.582  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:22.582  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:22.582  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:22.582  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 14:23:22.582  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:22.582  1924  2127 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 14:23:22.582  1178  1178 D HotspotTile: onReceive : 1, 0
,08-16 14:23:22.582  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:22.582  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 14:23:22.592  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:22.592  1014  1039 I ActivityManager: Killing 6050:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-16 14:23:22.592  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:22.592  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:22.602  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:22.602  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:22.602  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:22.602  3614  3614 I Hs20UtilService: Starting #16
08-16 14:23:22.602  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:22.602  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 14:23:22.602  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:22.602  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:22.602  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:23.182  1014  1041 D Tethering: interfaceRemoved wlan0
,08-16 14:23:23.182  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 14:23:23.212  6315  6332 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 14:23:23.352  1014  1041 D Tethering: interfaceRemoved p2p0
,08-16 14:23:23.352  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 14:23:24.102  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 14:23:24.362  1014  1039 W ActivityManager: userId = 0, bbcId = -10000,
08-16 14:23:24.362  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.362  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.372  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music,
,08-16 14:23:24.372  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.372  1014  1216 W ActivityManager: userId = 0, bbcId = -10000,
08-16 14:23:24.372  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.372  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,08-16 14:23:24.382  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:24.382  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.382  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.392  1014  3292 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:24.392  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.402  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.402  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:24.402  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.402  1014  1486 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:24.402  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.402  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.412  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:24.412  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.412  1014  1701 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 14:23:24.412  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 14:23:24.412  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.412  1014  1701 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:24.412  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.582   293   293 E SMD     : DCD OFF
,08-16 14:23:24.592  1014  3287 I art     : Explicit concurrent mark sweep GC freed 50759(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.415ms total 159.988ms
,08-16 14:23:24.592  1014  3287 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-16 14:23:24.592  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.592  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:24.592  1014  3287 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.592  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 14:23:24.592  6569  6808 I MusicLeanback: Conditions not met for autocaching.
,08-16 14:23:24.592  6569  6808 I MusicLeanback: Stop autocaching.
,08-16 14:23:24.602  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-16 14:23:24.602  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.602  6655  6684 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 14:23:24.602  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:24.602  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.602  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.622  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:24.632  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.632  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.632  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 14:23:24.632  1924  1924 D WearableService: callingUid 10012, callindPid: 1924
,08-16 14:23:24.642  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 14:23:24.642  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 14:23:24.642  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.642  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.642  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 14:23:24.672  6569  6569 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 14:23:24.672  6569  6816 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 14:23:24.872  6184  6234 D BluetoothAdapter: disable()
,08-16 14:23:24.872  1014  3244 D SettingsProvider: name = bluetooth_on
,08-16 14:23:24.882  6315  6331 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 14:23:24.882  6315  6331 D BluetoothAdapterProperties: Setting state to 13
,08-16 14:23:24.882  6315  6331 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 14:23:24.882  6315  6331 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 14:23:24.882  6315  6331 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 14:23:24.892  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:24.892  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.892  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.892  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:24.892  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:24.892  6315  6331 D BluetoothAdapterService: Autoconnection is available 
,08-16 14:23:24.892  6315  6331 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 14:23:24.892  6315  6331 D BluetoothAdapterService: terminating service from this receiver
,08-16 14:23:24.892  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.892  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:24.892  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:24.902  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:24.902  6315  6315 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 14:23:24.902  6315  6331 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:23:24.902  6315  6331 D BluetoothAdapterProperties: mDiscovering is false
,08-16 14:23:24.902  1014  1026 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 14:23:24.902  6315  6331 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 14:23:24.912  6315  6315 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32e4ef77, channel: 19, state: LISTENING
,08-16 14:23:24.912  6315  6315 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32e4ef77, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ed28f7f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@197a67e4mSocket: android.net.LocalSocket@231de44d impl:android.net.LocalSocketImpl@2fd7db02 fd:FileDescriptor[74]
,08-16 14:23:24.912  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:24.912  6315  6315 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@231de44d impl:android.net.LocalSocketImpl@2fd7db02 fd:FileDescriptor[74],
,08-16 14:23:24.912  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-16 14:23:24.922  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-16 14:23:24.932  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:24.932  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 14:23:24.932  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-16 14:23:24.932  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:24.942  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:24.942  1790  1790 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:24.942  1014  1345 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:24.942  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:24.942  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:24.942  1014  3292 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:24.942  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:24.942  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
,08-16 14:23:24.952  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:24.952  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:24.952  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 14:23:24.952  1014  3244 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:24.952  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:24.952  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:24.952  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:24.952  6315  6334 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 14:23:24.952  6315  6334 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:24.952  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:24.952  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:24.952  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:24.952  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:24.952  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 14:23:24.962  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:24.962  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:24.962  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:24.962  6315  6331 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 14:23:24.962  6315  6331 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 14:23:24.962  6315  6331 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-16 14:23:24.962  1014  3292 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 14:23:24.962  6315  6331 E bt-btif : cmd socket is not created
08-16 14:23:24.962  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-16 14:23:24.962  6315  6331 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:23:24.962  6315  6534 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 14:23:24.962  6315  6396 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 14:23:24.962  6315  6396 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 14:23:24.962  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:24.962  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:24.962  6315  6396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 14:23:24.972  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:24.972  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:24.972  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:24.972  1291  1291 D BluetoothPbap: Proxy object disconnected
,08-16 14:23:24.972  1291  1291 D PbapServerProfile: Bluetooth service disconnected
,08-16 14:23:24.982  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:24.982  6315  6315 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@92f0c13, channel: 5, state: LISTENING
08-16 14:23:24.982  6315  6315 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@92f0c13, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3299fb4c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28681e50mSocket: android.net.LocalSocket@2f717849 impl:android.net.LocalSocketImpl@176ca54e fd:FileDescriptor[76]
08-16 14:23:24.982  6315  6315 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f717849 impl:android.net.LocalSocketImpl@176ca54e fd:FileDescriptor[76]
08-16 14:23:24.982  6315  6315 I BtOppRfcommListener: stopping Accept Thread
08-16 14:23:24.982  6315  6315 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bf4566f, channel: 12, state: LISTENING
08-16 14:23:24.982  6315  6315 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bf4566f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@279b5d76, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@238cf7cmSocket: android.net.LocalSocket@37505005 impl:android.net.LocalSocketImpl@2e71c85a fd:FileDescriptor[79]
08-16 14:23:24.982  6315  6315 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37505005 impl:android.net.LocalSocketImpl@2e71c85a fd:FileDescriptor[79]
,08-16 14:23:24.982  6315  6534 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 14:23:24.992  6315  6315 V BluetoothOppManager: cleanUp...
,08-16 14:23:24.992  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:24.992  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:24.992  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 14:23:25.012  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:25.022  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:25.162  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 14:23:25.162  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:25.162  6315  6396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:25.162  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:25.162  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:25.172  6315  6396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:25.172  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:25.172  6315  6396 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:25.172  6315  6396 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:25.172  6315  6396 W bt-btif : ag scb idx 1 not allocated
08-16 14:23:25.172  6315  6396 W bt-btif : ag scb idx 2 not allocated
08-16 14:23:25.172  6315  6396 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:23:25.172  6315  6442 I bt_userial_mct: exiting userial_read_thread
08-16 14:23:25.172  6315  6442 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 14:23:25.172  6315  6334 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:23:25.172  6315  6399 I bt_vendor: hw_epilog_process
08-16 14:23:25.172  6315  6334 D bt_userial_mct: userial_close
08-16 14:23:25.172  6315  6334 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 14:23:25.602  6315  6334 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 14:23:25.602  6315  6334 I bt_vendor: bluetooth satus is on
08-16 14:23:25.602  6315  6334 I bt_vendor: bt-vendor : resetting BT status
08-16 14:23:25.602  6315  6334 I bt_vendor: Starting hciattach daemon
08-16 14:23:25.602  6315  6334 I bt_vendor: try to set false
,08-16 14:23:25.602  6315  6334 I bt_vendor: Starting hciattach daemon
08-16 14:23:25.602  6315  6334 I bt_vendor: try to set false
,08-16 14:23:25.602  6315  6334 I bt_vendor: cleanup
,08-16 14:23:25.602  6315  6396 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 14:23:25.602  6315  6334 I GKI_LINUX: GKI_exit_task 0 done
08-16 14:23:25.602  6315  6334 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated,
,08-16 14:23:25.602  6315  6331 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
08-16 14:23:25.602  6315  6331 D BtConfig.SecureMode: isSecureModeOn:false
08-16 14:23:25.602  6315  6331 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
08-16 14:23:25.602  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-16 14:23:25.602  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
,08-16 14:23:25.602  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-16 14:23:25.612  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 14:23:25.612  1014  1486 W ActivityManager: userId = 0, bbcId = -10000,
08-16 14:23:25.612  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-16 14:23:25.612  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.612  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.612  6315  6315 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:23:25.612  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 14:23:25.612  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:25.612  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:25.612  1014  1701 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:25.612  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 14:23:25.612  6315  6315 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:23:25.612  6315  6315 D BtGatt.GattService: stop()
08-16 14:23:25.612  6315  6315 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 14:23:25.612  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.612  1014  1701 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:25.612  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:25.612  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 14:23:25.612  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:25.612  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 14:23:25.612  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:25.622  1014  3287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:25.622  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.622  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.622  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.622  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.622  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService,
08-16 14:23:25.622  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
,08-16 14:23:25.622  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 14:23:25.622  1014  3286 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:25.622  6315  6315 D HeadsetService: Received stop request...Stopping profile...,
08-16 14:23:25.622  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 14:23:25.622  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:25.622  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.622  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:25.622  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d,
08-16 14:23:25.622  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-16 14:23:25.622  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 14:23:25.632  1291  1291 D HeadsetProfile: Bluetooth service disconnected
,08-16 14:23:25.632  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1,
08-16 14:23:25.632  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 14:23:25.632  1014  1701 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:25.632  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.632  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.632  1014  1701 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.632  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.632  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 14:23:25.632  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 14:23:25.632  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 14:23:25.632  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:25.632  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.632  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.632  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.632  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.642  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 14:23:25.642  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:25.642  6315  6331 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:25.642  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:25.642  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.642  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.642  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.642  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.642  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 14:23:25.642  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:25.642  6315  6331 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 14:23:25.642  1014  3287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:25.642  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.652  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.652  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.652  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:25.652  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:25.652  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 14:23:25.652  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 14:23:25.652  6315  6331 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 14:23:25.652  6315  6331 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-16 14:23:25.652  6315  6331 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 14:23:25.652  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-16 14:23:25.652  6315  6315 D A2dpService: Received stop request...Stopping profile...
08-16 14:23:25.652  6315  6359 D A2dpStateMachine: Exit Disconnected: -1
,08-16 14:23:25.652  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.662  2823  2823 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.662  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.662  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 14:23:25.662  6315  6315 D HidService: Received stop request...Stopping profile...
,08-16 14:23:25.662  6315  6315 D HidService: Stopping Bluetooth HidService
,08-16 14:23:25.662  1291  1291 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.662  1291  1291 D A2dpProfile: Bluetooth service disconnected
08-16 14:23:25.662  6315  6315 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-16 14:23:25.662  6315  6315 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 14:23:25.662  6315  6315 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 14:23:25.662  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.662  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 14:23:25.662  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:25.662  6315  6315 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 14:23:25.662  6315  6315 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 14:23:25.662  6315  6315 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 14:23:25.672  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-16 14:23:25.672  1291  1291 D HidProfile: Bluetooth service disconnected
,08-16 14:23:25.672  6315  6315 D HealthService: Received stop request...Stopping profile...
08-16 14:23:25.672  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.672  6315  6315 D PanService: Received stop request...Stopping profile...
,08-16 14:23:25.672  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.672  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 14:23:25.672  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:23:25.672  6315  6315 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 14:23:25.672  1291  1291 D PanProfile: Bluetooth service disconnected
,08-16 14:23:25.682  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.682  6315  6315 D SapService: Received stop request...Stopping profile...
,08-16 14:23:25.682  6315  6315 D SapService: Stopping Bluetooth SapService
08-16 14:23:25.682  6315  6315 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:25.682  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-16 14:23:25.682  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 14:23:25.682  6315  6315 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 14:23:25.682  6315  6315 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:25.682  6315  6315 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 14:23:25.682  6315  6360 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 14:23:25.682  1291  1291 D BluetoothMap: Proxy object disconnected
08-16 14:23:25.682  1291  1291 D MapProfile: Bluetooth service disconnected
,08-16 14:23:25.682  6315  6315 I GKI_LINUX: GKI_exit_task 2 done
08-16 14:23:25.682  6315  6315 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:23:25.682  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 14:23:25.682  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 14:23:25.682  1291  1291 D SapProfile: Bluetooth service disconnected
,08-16 14:23:25.692  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:25.692  6315  6315 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:25.692  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 14:23:25.692  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:25.692  6315  6315 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:25.692  6315  6315 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-16 14:23:25.692  6315  6315 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 14:23:25.692  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,08-16 14:23:25.692  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:25.692  6315  6315 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:25.692  6315  6315 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:23:25.692  6315  6315 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 14:23:25.692  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-16 14:23:25.692  6315  6315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:25.692  6315  6315 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 14:23:25.692  6315  6315 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 14:23:25.692  6315  6331 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:23:25.692  6315  6331 D BluetoothAdapterProperties: Setting state to 10
08-16 14:23:25.692  6315  6331 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 14:23:25.692  6315  6331 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:25.692  6315  6331 D BluetoothAdapterService: updateAdapterState state is 10
08-16 14:23:25.692  6315  6315 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 14:23:25.692  6315  6315 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 14:23:25.692  1291  1300 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 14:23:25.692  6315  6331 D BluetoothAdapterService: Autoconnection is available 
08-16 14:23:25.692  6315  6331 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-16 14:23:25.692  6315  6331 I BluetoothAdapterState: Entering OffState
,08-16 14:23:25.702  6184  6193 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.702  6184  6193 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.702  6315  6349 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:23:25.702  6387  6398 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.702  6387  6398 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.702  1455  1473 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:25.702  1455  1473 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.702  2823  6825 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:23:25.702  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 14:23:25.702  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.702  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.702  1291  6811 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 14:23:25.702  2823  2831 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.702  2823  2831 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.712  1291  1308 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1291  6811 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:25.712  6315  6477 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:25.712  6315  6477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.712  1291  1300 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1291  1300 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:25.712  1924  1933 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1924  1933 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.712  1443  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1443  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.712  1431  1442 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:25.712  1431  1442 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:25.712  1178  1996 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1178  1996 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:25.712  1291  1308 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 14:23:25.712  1291  1308 D Bluetoothsap: Unbinding service...
,08-16 14:23:25.712  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-16 14:23:25.722  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 14:23:25.722  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:25.722  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,08-16 14:23:25.732  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 14:23:25.732  1178  1178 D BluetoothAdapter: 855079650: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.732  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:25.732  1178  1714 D BluetoothAdapter: 855079650: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.732  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:25.732  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-16 14:23:25.732  1178  1714 D BluetoothAdapter: 855079650: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.732  1178  1178 D BluetoothAdapter: 855079650: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.732  1178  1178 D BluetoothAdapter: 855079650: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.742  1790  1790 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0,
08-16 14:23:25.742  1014  3292 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 14:23:25.742  1014  3286 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 14:23:25.742  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 14:23:25.742  1924  2127 D BluetoothAdapter: 442996321: getState() :  mService = null. Returning STATE_OFF
08-16 14:23:25.742  1924  2127 D BluetoothAdapter: 442996321: getState() :  mService = null. Returning STATE_OFF
,08-16 14:23:25.742  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:25.742  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:25.742  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:25.742  1014  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:25.742  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.742  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:25.752  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:25.752  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:25.752  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:25.752  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 14:23:25.752  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.752  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:25.752  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:25.752  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:25.752  6315  6334 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 14:23:25.752  6315  6315 I GKI_LINUX: GKI_exit_task 1 done
,08-16 14:23:25.752  6315  6315 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 14:23:25.752  6315  6315 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 14:23:25.762  6315  6315 I art     : System.exit called, status: 0
,08-16 14:23:25.762  6315  6315 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 14:23:25.762  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:25.762  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:25.772  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:25.772  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 14:23:25.882  1014  1027 I ActivityManager: Process com.android.bluetooth (pid 6315)(adj 0) has died(73,1062)
,08-16 14:23:25.892  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:25.892  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:25.892  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 14:23:25.902  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:25.902  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:25.902  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:25.912  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
08-16 14:23:25.912  1924  6832 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 14:23:25.912  1014  3292 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:25.922  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:25.922  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:25.922  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:25.932  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:25.932  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:25.932  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:25.932  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:25.942  1924  6832 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 14:23:27.052  1014  3286 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 14:23:27.052  1014  3286 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4283, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 14:23:27.052  1014  3286 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-16 14:23:27.052  1014  3286 D BatteryService: stay LED for charging
08-16 14:23:27.062  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-16 14:23:27.052  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
08-16 14:23:27.062  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 14:23:27.052  1014  1014 I MotionRecognitionService: Plugged
08-16 14:23:27.052  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 14:23:27.062  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 14:23:27.062  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 14:23:27.082  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:27.082  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:27.082  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:27.192  1014  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 14:23:27.592   293   293 E SMD     : DCD OFF
,08-16 14:23:27.892  6184  6234 D BluetoothAdapter: enable()
,08-16 14:23:27.892  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 14:23:27.892  1014  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 14:23:27.892  1014  1026 W BluetoothManagerService: ,	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:23:27.892  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-16 14:23:27.892  1014  1026 D SettingsProvider: name = bluetooth_on
,08-16 14:23:27.892  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:27.902  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:27.902  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:27.902  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 14:23:27.902  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 14:23:27.912  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 14:23:27.912  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:27.912  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:27.912  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:27.922  6836  6836 E Zygote  : MountEmulatedStorage(),
,08-16 14:23:27.932  6836  6836 E Zygote  : v2
08-16 14:23:27.932  6836  6836 I libpersona: KNOX_SDCARD checking this for 1002
08-16 14:23:27.932  6836  6836 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:27.932  6836  6836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 14:23:27.942  6836  6836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:27.942  6836  6836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-16 14:23:27.942  1014  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6836 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 14:23:27.962  6836  6836 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:27.962  6836  6836 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:27.982  6836  6836 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 14:23:27.982  6836  6836 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:23:28.022  6836  6836 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding GattService
,08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding A2dpService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding HidService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding HealthService
,08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding PanService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding BluetoothMapService,
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding SapService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding SapClientService
08-16 14:23:28.062  6836  6836 D BtSettings.ProfileConfig: Adding HidDevService,
08-16 14:23:28.062  6836  6836 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 14:23:28.072  1014  3288 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 14:23:28.072  1014  3288 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:28.072  1014  3288 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  3288 D SettingsProvider: selectionArgs: false
,08-16 14:23:28.072  1014  3288 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.072  1014  3288 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 14:23:28.072  1014  3288 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  1486 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:28.072  1014  1486 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.072  1014  1486 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  1486 D SettingsProvider: selectionArgs: false
,08-16 14:23:28.072  1014  1486 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.072  1014  1486 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  1486 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  3287 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:28.072  1014  3287 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.072  1014  3287 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  3287 D SettingsProvider: selectionArgs: false
08-16 14:23:28.072  1014  3287 D SettingsProvider: selectionArgs: 1002
,08-16 14:23:28.072  1014  3287 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  3287 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  1307 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-16 14:23:28.072  1014  1307 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.072  1014  1307 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  1307 D SettingsProvider: selectionArgs: false
08-16 14:23:28.072  1014  1307 D SettingsProvider: selectionArgs: 1002
,08-16 14:23:28.072  1014  1307 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  1307 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-16 14:23:28.072  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:28.072  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  1027 D SettingsProvider: selectionArgs: false
,08-16 14:23:28.072  1014  1027 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.072  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  1027 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  3286 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 14:23:28.072  1014  3286 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.072  1014  3286 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  3286 D SettingsProvider: selectionArgs: false
08-16 14:23:28.072  1014  3286 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.072  1014  3286 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  3286 D SettingsProvider: ret = -1
08-16 14:23:28.072  1014  3002 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 14:23:28.072  1014  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.072  1014  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.072  1014  3002 D SettingsProvider: selectionArgs: false
08-16 14:23:28.072  1014  3002 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.072  1014  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.072  1014  3002 D SettingsProvider: ret = -1
08-16 14:23:28.082  1014  1132 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 14:23:28.082  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.082  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.082  1014  1132 D SettingsProvider: selectionArgs: false
08-16 14:23:28.082  1014  1132 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.082  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.082  1014  1132 D SettingsProvider: ret = -1
08-16 14:23:28.082  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:28.082  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.082  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.082  1014  1345 D SettingsProvider: selectionArgs: false
08-16 14:23:28.082  1014  1345 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.082  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.082  1014  1345 D SettingsProvider: ret = -1
08-16 14:23:28.082  1014  1701 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.082  1014  1701 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.082  1014  1701 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.082  1014  1701 D SettingsProvider: selectionArgs: false
08-16 14:23:28.082  1014  1701 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.082  1014  1701 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.082  1014  1701 D SettingsProvider: ret = -1
08-16 14:23:28.082  1014  3292 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.082  1014  3292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.082  1014  3292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.082  1014  3292 D SettingsProvider: selectionArgs: false
08-16 14:23:28.082  1014  3292 D SettingsProvider: selectionArgs: 1002
08-16 14:23:28.082  1014  3292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.082  1014  3292 D SettingsProvider: ret = -1
,08-16 14:23:28.082  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 14:23:28.082  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:28.082  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:28.082  1014  1492 D SettingsProvider: selectionArgs: false
08-16 14:23:28.082  1014  1492 D SettingsProvider: selectionArgs: 1002
,08-16 14:23:28.082  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.082  1014  1492 D SettingsProvider: ret = -1
,08-16 14:23:28.102  6836  6836 D BluetoothAdapterState: make,
,08-16 14:23:28.102  6836  6836 I bluedroid: init
,08-16 14:23:28.102  6836  6851 I BluetoothAdapterState: Entering OffState
,08-16 14:23:28.102  6836  6836 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 14:23:28.112  6836  6836 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 14:23:28.112  6836  6836 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 14:23:28.112  6836  6836 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 14:23:28.112  6836  6836 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-16 14:23:28.112  6836  6836 I bluedroid: get_profile_interface socket
08-16 14:23:28.112  6836  6836 I bluedroid: get_profile_interface map_client
08-16 14:23:28.112  6836  6854 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 14:23:28.112  6836  6836 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-16 14:23:28.112  6836  6854 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 14:23:28.122  6836  6854 E BluetoothServiceJni: populateRssiValuesNative
08-16 14:23:28.122  6836  6854 I bluedroid: getModelRssiValues
08-16 14:23:28.122  6836  6854 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 14:23:28.122  6836  6854 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 14:23:28.122  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 14:23:28.122  6836  6836 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:28.122  6836  6854 D BluetoothAdapterProperties: Name is: A5-1
08-16 14:23:28.122  1014  3002 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 14:23:28.122  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.122  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.122  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:28.122  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.122  6836  6848 I bluedroid: config_hci_snoop_log
,08-16 14:23:28.122  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 14:23:28.132  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,08-16 14:23:28.132  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 14:23:28.132  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 14:23:28.132  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 14:23:28.142  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:28.142  6836  6836 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 14:23:28.142  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:28.142  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled,
,08-16 14:23:28.142  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 14:23:28.152  6836  6851 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 14:23:28.152  6836  6851 D BluetoothAdapterProperties: Setting state to 11
,08-16 14:23:28.152  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 14:23:28.152  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:28.152  6836  6851 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 14:23:28.152  6836  6851 D BluetoothAdapterService: Autoconnection is available 
,08-16 14:23:28.152  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 14:23:28.152  6836  6851 D BluetoothSecureManager: getInstant: null
,08-16 14:23:28.162  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:28.162  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-16 14:23:28.162  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:28.172  6836  6851 D BluetoothSecureManager: calling getMethod for getService
08-16 14:23:28.172  6836  6851 D BluetoothSecureManager: calling getService
,08-16 14:23:28.172  6836  6851 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3906facb
,08-16 14:23:28.172  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:28.172  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-16 14:23:28.172  1014  3288 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 14:23:28.172  1014  3288 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 14:23:28.172  6836  6851 D BtConfig.SecureMode: isSecureModeOn:false
08-16 14:23:28.172  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 14:23:28.172  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-16 14:23:28.172  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:28.172  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 14:23:28.172  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:28.172  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 14:23:28.172  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 14:23:28.172  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
08-16 14:23:28.172  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 14:23:28.172  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 14:23:28.172  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 14:23:28.182  1014  3292 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:28.182  1790  1790 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:28.182  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:28.182  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:28.182  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
08-16 14:23:28.182  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 14:23:28.182  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.182  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.182  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.182  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.182  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:28.182  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:28.192  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.192  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 14:23:28.192  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:28.192  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 14:23:28.192  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:28.192  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:28.202  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:28.202  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 14:23:28.202  6836  6851 D BluetoothBondStateMachine: make
,08-16 14:23:28.202  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 14:23:28.202  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 14:23:28.202  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-16 14:23:28.202  6836  6857 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 14:23:28.212  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:28.212  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.212  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.212  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.212  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.212  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 14:23:28.212  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:28.212  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:28.212  6836  6836 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:23:28.212  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:28.222  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.222  6836  6836 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:23:28.222  6836  6836 D BtGatt.GattService: start()
08-16 14:23:28.222  6836  6836 D BtGatt.GattService: start()
08-16 14:23:28.222  6836  6836 I bluedroid: get_profile_interface gatt
08-16 14:23:28.222  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.222  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.222  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:28.222  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:28.222  6836  6836 D BtGatt.AdvertiseManager: advertise manager created
,08-16 14:23:28.222  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 14:23:28.222  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 14:23:28.222  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:28.222  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:28.222  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.232  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.232  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:28.232  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.232  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 14:23:28.232  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:28.232  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 14:23:28.232  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.232  1014  1701 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:28.232  1014  1701 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.232  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 14:23:28.232  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:28.232  6836  6836 D BtGatt.GattService: mStartError = false
08-16 14:23:28.232  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.242  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 14:23:28.242  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 14:23:28.242  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 14:23:28.242  1014  3290 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:28.242  6836  6836 D HeadsetService: Received start request. Starting profile...
08-16 14:23:28.242  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 14:23:28.242  6836  6836 D HeadsetService: start()
,08-16 14:23:28.242  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.242  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.242  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.242  6836  6836 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 14:23:28.242  6836  6836 D HeadsetStateMachine: make
,08-16 14:23:28.242  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 14:23:28.242  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 14:23:28.242  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 14:23:28.242  1014  3286 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:28.242  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.242  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.242  6836  6836 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 14:23:28.252  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.252  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.252  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:28.252  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:28.252  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:28.252  1014  3002 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:28.252  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.252  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.252  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.262  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.262  1014  3287 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 14:23:28.262  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.262  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:28.262  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.262  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 14:23:28.262  1014  3290 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 14:23:28.262  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.262  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-16 14:23:28.262  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.262  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 14:23:28.262  6836  6836 I bluedroid: get_profile_interface handsfree
08-16 14:23:28.262  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 14:23:28.262  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:28.262  6836  6851 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 14:23:28.262  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:28.262  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:28.272  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:28.272  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:28.272  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:28.272  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.272  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.272  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 14:23:28.272  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 14:23:28.272  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-16 14:23:28.272  6836  6851 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 14:23:28.282  6836  6836 I DualScoManager: Instantiating Dual Sco Manager
,08-16 14:23:28.282  6836  6836 I DualScoManager: Set HeadsetServiceHelper
,08-16 14:23:28.282  6836  6836 D BluetoothAtMessage: createCMTIContentObservers
,08-16 14:23:28.292  1014  1701 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 14:23:28.292  1014  1701 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:28.292  1014  1701 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 14:23:28.292  1014  1701 D SettingsProvider: selectionArgs: false
08-16 14:23:28.292  1014  1701 D SettingsProvider: selectionArgs: 1002
,08-16 14:23:28.292  1014  1701 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:28.292  1014  1701 D SettingsProvider: ret = -1
,08-16 14:23:28.292  6836  6860 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 14:23:28.292  6836  6836 D HeadsetService: mStartError = false
08-16 14:23:28.292  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.292  6836  6860 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 14:23:28.292  6836  6860 D HeadsetStateMachine: map size, before remove : 0
08-16 14:23:28.292  6836  6860 D HeadsetStateMachine: map size, after remove: 0
,08-16 14:23:28.302  6836  6836 D A2dpService: Received start request. Starting profile...
08-16 14:23:28.302  6836  6836 D A2dpService: start()
,08-16 14:23:28.302  6836  6836 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 14:23:28.302  6836  6836 I bluedroid: get_profile_interface avrcp
,08-16 14:23:28.302  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:28.312  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:28.312  6836  6836 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:23:28.322  6836  6836 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 14:23:28.332  6836  6864 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 14:23:28.332  6836  6836 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 14:23:28.332  6836  6836 D A2dpStateMachine: make
,08-16 14:23:28.332  6836  6836 I bluedroid: get_profile_interface a2dp
,08-16 14:23:28.332  6836  6866 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 14:23:28.332  6836  6836 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 14:23:28.342  6836  6836 D A2dpService: mStartError = false
08-16 14:23:28.342  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:28.342  6836  6865 D A2dpStateMachine: Enter Disconnected: -2
,08-16 14:23:28.342  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 14:23:28.342  6836  6836 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 14:23:28.342  6836  6836 D HidService: Received start request. Starting profile...
08-16 14:23:28.342  6836  6836 D HidService: start()
08-16 14:23:28.342  6836  6836 I bluedroid: get_profile_interface hidhost
08-16 14:23:28.342  6836  6836 D HidService: setHidService(): set to: null
08-16 14:23:28.342  6836  6836 D HidService: mStartError = false
08-16 14:23:28.342  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.342  6836  6836 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 14:23:28.342  6836  6836 D HealthService: Received start request. Starting profile...
08-16 14:23:28.342  6836  6836 D HealthService: start()
,08-16 14:23:28.342  6836  6836 I bluedroid: get_profile_interface health
,08-16 14:23:28.342  6836  6836 D HealthService: mStartError = false
08-16 14:23:28.342  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.342  6836  6836 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 14:23:28.352  6836  6836 D PanService: Received start request. Starting profile...
08-16 14:23:28.352  6836  6836 D PanService: start()
,08-16 14:23:28.352  6836  6836 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:23:28.352  6836  6836 I bluedroid: get_profile_interface pan
,08-16 14:23:28.352  6836  6836 D PanService: mStartError = false
08-16 14:23:28.352  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.352  6836  6864 D BluetoothMediaBrowser: no now playing list
,08-16 14:23:28.352  6836  6836 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 14:23:28.352  6836  6864 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 14:23:28.352  1431  1453 I Telecom : BluetoothPhoneService: queryPhoneState,
08-16 14:23:28.352  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-16 14:23:28.352  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 14:23:28.352  1431  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 14:23:28.362  6836  6836 D BluetoothMapService: Received start request. Starting profile...
,08-16 14:23:28.362  6836  6836 D BluetoothMapService: start()
,08-16 14:23:28.362  6836  6836 D BluetoothMapService: mStartError = false
,08-16 14:23:28.362  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.362  6836  6836 D HeadsetStateMachine: Proxy object connected
,08-16 14:23:28.362  6836  6836 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 14:23:28.362  6836  6836 D SapService: Received start request. Starting profile...
,08-16 14:23:28.362  6836  6836 D SapService: start()
,08-16 14:23:28.362  6836  6836 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 14:23:28.362  6836  6836 I bluedroid: get_profile_interface sap
08-16 14:23:28.362  6836  6836 D SapService: mStartError = false
,08-16 14:23:28.372  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:28.372  6836  6836 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 14:23:28.372  6836  6860 D HeadsetStateMachine: Disconnected process message: 11
08-16 14:23:28.372  6836  6836 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 14:23:28.372  6836  6860 D HeadsetStateMachine: Disconnected process message: 18
,08-16 14:23:28.372  6836  6836 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-16 14:23:28.372  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 14:23:28.372  6836  6836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 14:23:28.372  6836  6860 D HeadsetStateMachine: Disconnected process message: 10
08-16 14:23:28.372  6836  6836 D BluetoothA2dp: Proxy object connected
08-16 14:23:28.372  6836  6836 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-16 14:23:28.372  6836  6860 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:23:28.372  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 14:23:28.372  6836  6860 D HeadsetStateMachine: Disconnected process message: 11
08-16 14:23:28.372  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 14:23:28.372  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 14:23:28.372  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 14:23:28.402  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 14:23:28.402  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 14:23:28.402  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 14:23:28.402  6836  6851 I bluedroid: enable
,08-16 14:23:28.402  6836  6851 I bt_hci_bdroid: init
,08-16 14:23:28.402  6836  6871 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 14:23:28.402  6836  6851 I bt_vendor: bt-vendor : init
,08-16 14:23:28.402  6836  6851 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:23:28.402  6836  6851 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-16 14:23:28.402  6836  6851 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 14:23:28.402  6836  6851 D bt_userial_mct: userial_init
,08-16 14:23:28.412  6836  6851 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 14:23:28.412  6836  6851 I bt_vendor: Starting hciattach daemon
08-16 14:23:28.412  6836  6851 I bt_vendor: try to set false
,08-16 14:23:28.412  6836  6851 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 14:23:28.412  6836  6851 I bt_vendor: Starting hciattach daemon
08-16 14:23:28.412  6836  6851 I bt_vendor: try to set true
,08-16 14:23:28.432  6875  6875 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 14:23:28.482  6881  6881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 14:23:28.492  6882  6882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 14:23:28.512  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 14:23:28.512  6885  6885 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 14:23:28.522  6886  6886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 14:23:28.532  6887  6887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 14:23:28.812  6890  6890 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 14:23:28.822  6891  6891 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 14:23:28.862  6836  6851 I bt_vendor: bluetooth satus is on,
08-16 14:23:28.872  6836  6873 D bt_userial_mct: userial_open(port:0)
,08-16 14:23:28.872  6836  6873 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 14:23:28.872  6836  6873 I bt_vendor: Done intiailizing UART
,08-16 14:23:28.872  6836  6873 I bt_vendor: Done intiailizing UART
08-16 14:23:28.872  6836  6873 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-16 14:23:28.872  6836  6873 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-16 14:23:28.882  6836  6893 D bt_userial_mct: Entering userial_read_thread()
,08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:23:28.882  6836  6871 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 14:23:28.892  1014  2718 D SSRM:n  : SIOP:: AP = 330
,08-16 14:23:28.972  1014  1339 E Watchdog: !@Sync 4
,08-16 14:23:28.992  6836  6871 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 14:23:28.992  6836  6871 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a16e9 
,08-16 14:23:28.992  6836  6871 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a16e9 
,08-16 14:23:29.012  6836  6854 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 14:23:29.012  6836  6854 E bt-btif : Calling BTA_HhEnable
,08-16 14:23:29.012  6836  6854 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 14:23:29.012  6836  6854 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 14:23:29.022  6836  6854 E BluetoothServiceJni: populateRssiValuesNative,
08-16 14:23:29.022  6836  6854 I bluedroid: getModelRssiValues
08-16 14:23:29.022  6836  6854 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 14:23:29.022  6836  6854 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 14:23:29.022  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 14:23:29.022  6836  6854 D BluetoothAdapterProperties: Name is: A5-1
,08-16 14:23:29.022  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:29.032  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:29.032  6836  6854 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 14:23:29.032  6836  6854 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:29.032  6836  6854 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:29.032  6836  6854 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-16 14:23:29.032  6836  6854 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-16 14:23:29.042  6836  6854 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-16 14:23:29.042  6836  6854 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 14:23:29.042  6836  6854 E bt-btif : btif_sock_init: !vhci_init
08-16 14:23:29.042  6836  6854 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 14:23:29.042  6836  6854 D IOP_DB_BT: db_open: db_open : handle 3028467728l, read 13894 bytes onto local cache
,08-16 14:23:29.042  6836  6854 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-16 14:23:29.042  6836  6854 D IOP_DB_BT: db_query: result 1
08-16 14:23:29.042  6836  6854 I         : iop_db_open: iop_db_open status 0
,08-16 14:23:29.042  6836  6854 D bte_conf: Device ID record 1 : primary
08-16 14:23:29.042  6836  6854 D bte_conf:   vendorId            = 0075
08-16 14:23:29.042  6836  6854 D bte_conf:   vendorIdSource      = 0001
08-16 14:23:29.042  6836  6854 D bte_conf:   product             = 0100
08-16 14:23:29.042  6836  6854 D bte_conf:   version             = 0200
08-16 14:23:29.042  6836  6854 D bte_conf:   clientExecutableURL = 
08-16 14:23:29.042  6836  6854 D bte_conf:   serviceDescription  = 
08-16 14:23:29.042  6836  6854 D bte_conf:   documentationURL    = 
08-16 14:23:29.042  6836  6854 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 14:23:29.042  6836  6893 E bt_mct  : hci lib postload completed
,08-16 14:23:29.042  6836  6854 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:23:29.042  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 14:23:29.042  6836  6851 D BluetoothAdapterProperties: ScanMode =  20
08-16 14:23:29.042  6836  6851 D BluetoothAdapterProperties: State =  11
,08-16 14:23:29.042  1014  1492 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 14:23:29.042  6836  6851 D BluetoothAdapterProperties: Setting state to 12
,08-16 14:23:29.052  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 14:23:29.052  6836  6854 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 14:23:29.052  6836  6854 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:23:29.052  6836  6854 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:29.052  1014  3288 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-16 14:23:29.052  1014  3288 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 14:23:29.052  1014  3288 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:29.052  1014  3288 D SettingsProvider: selectionArgs: false
08-16 14:23:29.052  1014  3288 D SettingsProvider: selectionArgs: 1002
08-16 14:23:29.052  1014  3288 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:29.052  1014  3288 D SettingsProvider: ret = -1
,08-16 14:23:29.052  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 14:23:29.052  6836  6851 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 14:23:29.062  1014  3286 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:29.062  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.062  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:29.062  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:29.062  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.062  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.062  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:29.072  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.072  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.072  1291  1300 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 14:23:29.072  6836  6851 D BluetoothAdapterService: Autoconnection is available 
08-16 14:23:29.072  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 14:23:29.072  6836  6851 D BluetoothAdapterService: starting service from this receiver
,08-16 14:23:29.072  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:29.072  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 14:23:29.072  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.072  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.072  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.072  6836  6851 I BluetoothAdapterState: Entering On State from state = 11
,08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:29.082  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:29.082  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 14:23:29.082  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.082  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.082  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.082  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.092  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:29.092  6836  6836 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 14:23:29.102  1431  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.102  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:29.102  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.102  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:29.102  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.102  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:29.102  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 14:23:29.102  1431  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.102  6184  6192 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:29.102  6184  6192 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.102  6387  6395 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.102  6387  6395 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.102  1455  1475 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.102  1455  1475 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.112  1431  6897 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.112  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:29.112  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 14:23:29.112  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.112  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.112  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.112  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.112  6836  6836 I BluetoothPbapService: Handler(): got msg=1
08-16 14:23:29.112  1291  1291 D BluetoothPbap: Proxy object connected
08-16 14:23:29.112  1291  1291 D PbapServerProfile: Bluetooth service connected
08-16 14:23:29.112  1431  6897 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.112  2823  6825 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:29.112  1014  1345 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 14:23:29.112  2823  6825 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
08-16 14:23:29.112  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:29.112  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,08-16 14:23:29.122  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.122  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.122  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth,
,08-16 14:23:29.122  2823  2823 D BluetoothA2dp: Proxy object connected
,08-16 14:23:29.122  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:29.122  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 14:23:29.122  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 14:23:29.122  6836  6898 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 14:23:29.122  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.122  1014  1014 D BluetoothA2dp: Proxy object connected
,08-16 14:23:29.122  1291  1308 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.122  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 14:23:29.122  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.132  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.132  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.132  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.132  1291  1308 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.132  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.132  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:29.132  1291  6811 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:23:29.132  6836  6898 D BluetoothSocket: bindListen(): myUserId = 0
08-16 14:23:29.132  6836  6898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:29.132  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 14:23:29.132  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.132  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:29.132  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.132  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.132  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.132  6836  6898 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-16 14:23:29.132  6836  6898 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:29.132  6836  6898 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:29.132  6836  6898 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@240ad89e
08-16 14:23:29.132  6836  6898 D BluetoothSocket: channel: 19
08-16 14:23:29.132  6836  6898 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 14:23:29.132  2823  2839 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:29.132  2823  2839 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.132  1291  6811 D BluetoothPan: Binding service...
,08-16 14:23:29.142  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 14:23:29.142  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.142  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.142  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.142  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.142  6836  6846 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:29.142  6836  6846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:29.142  1291  1308 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 14:23:29.142  1291  1291 D BluetoothInputDevice: Proxy object connected
,08-16 14:23:29.142  1291  1291 D HidProfile: Bluetooth service connected
08-16 14:23:29.142  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 14:23:29.142  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.142  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.142  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.142  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.142  1014  1043 D BluetoothPan: Binding service...
,08-16 14:23:29.142  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 14:23:29.142  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.142  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:29.142  2823  2831 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.142  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:29.142  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.152  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.152  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:29.152  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-16 14:23:29.152  2823  2831 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.152  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:29.152  1291  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.152  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:29.152  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 14:23:29.152  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.152  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.152  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.152  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:29.152  1291  1291 D PanProfile: Bluetooth service connected
08-16 14:23:29.152  6836  6899 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:29.152  1291  6811 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.152  1291  6811 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:29.152  1924  2119 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:29.152  1924  2119 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.162  1455  1723 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.162  1291  1291 D BluetoothMap: Proxy object connected
08-16 14:23:29.162  1291  1291 D MapProfile: Bluetooth service connected
08-16 14:23:29.162  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:29.162  1291  1291 D BluetoothMap: getConnectedDevices()
08-16 14:23:29.162  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.162  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.162  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.162  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.162  1455  1723 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.162  1431  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:29.162  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:29.162  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:29.162  1291  1291 D BluetoothA2dp: Proxy object connected
08-16 14:23:29.162  1291  1291 D A2dpProfile: Bluetooth service connected
08-16 14:23:29.162  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.162  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.162  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.162  1431  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:29.162  1443  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.162  1443  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:29.162  1431  1442 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.162  1431  1442 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:29.162  1178  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:29.162  1178  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:29.162  1291  1300 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 14:23:29.162  1291  1300 D Bluetoothsap: Binding service...
,08-16 14:23:29.162  1291  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-16 14:23:29.162  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap,
08-16 14:23:29.162  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-16 14:23:29.172  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.172  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.172  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth,
08-16 14:23:29.172  1291  1300 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 14:23:29.172  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 14:23:29.172  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 14:23:29.172  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:29.172  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-16 14:23:29.172  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 14:23:29.172  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 14:23:29.172  1291  1291 D SapProfile: Bluetooth service connected
08-16 14:23:29.172  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-16 14:23:29.172  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@35c1baab, true
,08-16 14:23:29.182  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-16 14:23:29.182  1431  1431 D BluetoothHeadset: registerMessageListener
,08-16 14:23:29.182  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 14:23:29.182  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:29.182  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-16 14:23:29.182  1790  1790 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:29.182  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:29.192  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:29.192  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-16 14:23:29.192  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 14:23:29.192  6836  6899 D HeadsetService: registerMessageListener
08-16 14:23:29.192  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:29.192  1014  1132 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 14:23:29.192  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 14:23:29.192  6836  6899 D HeadsetService: registerMessageListener
,08-16 14:23:29.192  6836  6860 D HeadsetStateMachine: Disconnected process message: 70
08-16 14:23:29.192  6836  6860 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ed28f7f
,08-16 14:23:29.192  6836  6900 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 14:23:29.192  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:29.192  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 14:23:29.192  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 14:23:29.202  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.202  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:29.202  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:29.202  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:29.202  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:29.202  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-16 14:23:29.202  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 14:23:29.202  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.,
08-16 14:23:29.202  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-16 14:23:29.202  6836  6900 D BluetoothSocket: bindListen(): myUserId = 0
08-16 14:23:29.202  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
08-16 14:23:29.202  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-16 14:23:29.202  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 14:23:29.202  6836  6900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:23:29.202  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 14:23:29.202  6836  6900 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-16 14:23:29.202  6836  6900 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:29.202  6836  6900 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:29.202  6836  6900 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3299fb4c,
08-16 14:23:29.212  6836  6900 D BluetoothSocket: channel: 5
,08-16 14:23:29.212  6836  6860 D HeadsetStateMachine: Disconnected process message: 9
08-16 14:23:29.212  6836  6860 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 14:23:29.212   287   287 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-16 14:23:29.212   287   287 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 14:23:29.212   287   287 V voice   : voice_set_parameters: exit with code(-2)
08-16 14:23:29.212   287   287 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 14:23:29.212   287   287 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 14:23:29.212   287   287 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 14:23:29.212   287   287 V audio_hw_primary: adev_set_parameters: exit
08-16 14:23:29.212  6836  6860 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 14:23:29.222  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:29.222  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 14:23:29.222  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.232  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:29.232  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.232  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:29.232  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:29.232  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:29.242  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:29.242  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 14:23:29.252  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:29.252  6836  6836 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 14:23:29.252  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:29.252  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.252  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.252  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:29.252  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:29.262  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:29.262  1014  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:29.262  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 14:23:29.272  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:29.272  1014  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:29.272  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:29.282  1924  6906 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-16 14:23:29.282  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:29.282  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:29.292  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:29.292  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:29.292  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:29.292  1014  1701 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 14:23:29.302  1924  6906 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 14:23:29.302  6836  6910 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 14:23:29.302  6836  6910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:29.312  6836  6910 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 14:23:29.312  6836  6910 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:29.312  6836  6910 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:29.312  6836  6910 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@279b5d76
,08-16 14:23:29.312  6836  6910 D BluetoothSocket: channel: 12
,08-16 14:23:29.312  6836  6910 I BtOppRfcommListener: Accept thread started.
,08-16 14:23:29.552   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:30.552   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:30.592   293   293 E SMD     : DCD OFF
,08-16 14:23:30.912  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 14:23:30.912  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:31.552   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:32.552   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 14:23:33.022  1014  1966 V SAMP_SPCM_test: CSC File load.. 
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control,
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location,
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-16 14:23:33.022  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 14:23:33.062  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn,
08-16 14:23:33.072  1014  1966 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-16 14:23:33.092  1014  1966 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-16 14:23:33.562   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 14:23:33.592   293   293 E SMD     : DCD OFF
,08-16 14:23:33.912  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:33.912  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173666a2 added. We now have 6 listener(s)
,08-16 14:23:33.912  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:33.912  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:33.912  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38bb3f33 added. We now have 7 listener(s)
,08-16 14:23:33.912  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:33.912  6184  6234 I System.out: IsBluetoothEnabled
,08-16 14:23:33.912  6184  6234 D BluetoothAdapter: disable()
,08-16 14:23:33.922  1014  3292 D SettingsProvider: name = bluetooth_on
,08-16 14:23:33.932  6836  6851 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 14:23:33.932  6836  6851 D BluetoothAdapterProperties: Setting state to 13
08-16 14:23:33.932  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 14:23:33.932  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:33.932  6836  6851 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 14:23:33.932  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:33.932  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:33.932  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:33.932  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:33.932  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:33.942  6836  6836 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 14:23:33.942  6836  6851 D BluetoothAdapterService: Autoconnection is available 
,08-16 14:23:33.942  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-16 14:23:33.942  6836  6851 D BluetoothAdapterService: terminating service from this receiver
,08-16 14:23:33.942  6836  6836 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32e4ef77, channel: 19, state: LISTENING
,08-16 14:23:33.942  6836  6836 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32e4ef77, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@240ad89e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@197a67e4mSocket: android.net.LocalSocket@231de44d impl:android.net.LocalSocketImpl@2fd7db02 fd:FileDescriptor[74]
,08-16 14:23:33.942  6836  6836 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@231de44d impl:android.net.LocalSocketImpl@2fd7db02 fd:FileDescriptor[74]
,08-16 14:23:33.952  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:33.952  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-16 14:23:33.952  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:33.952  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:33.952  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 14:23:33.962  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:33.962  6184  6234 D BluetoothAdapter: enable()
,08-16 14:23:33.962  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-16 14:23:33.962  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:33.962  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:33.962  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:33.962  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-16 14:23:33.962  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:33.972  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 14:23:33.972  1790  1790 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:33.972  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:33.972  1014  3002 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:33.972  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:33.972  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:33.982  1014  3287 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 14:23:33.982  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 14:23:33.982  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:33.982  6184  6184 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 14:23:33.982  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:33.982  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:33.982  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 14:23:33.982  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:33.982  6836  6851 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 14:23:33.982  6836  6851 D BluetoothAdapterProperties: mDiscovering is false
,08-16 14:23:33.982  1014  1701 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 14:23:33.982  6836  6851 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 14:23:33.982  1014  3290 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 14:23:33.982  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:33.992  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:33.992  1014  3290 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:33.992  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:33.992  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:34.002  1014  3287 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 14:23:34.002  1014  3287 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 14:23:34.002  1014  3287 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:34.002  1014  3287 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:34.002  1014  3287 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:34.002  1014  3287 D SettingsProvider: name = bluetooth_on
,08-16 14:23:34.002  6836  6854 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 14:23:34.002  6836  6854 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:34.002  1014  1132 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 14:23:34.002  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.012  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.012  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:34.012  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.012  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:34.012  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 14:23:34.012  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 14:23:34.012  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 14:23:34.012  6836  6851 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 14:23:34.012  6836  6851 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 14:23:34.012  6836  6851 E bt-btif : cmd socket is not created
,08-16 14:23:34.012  6836  6910 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 14:23:34.012  6836  6871 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 14:23:34.012  6836  6871 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 14:23:34.012  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:34.012  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:34.012  6836  6871 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:34.012  1291  1291 D BluetoothPbap: Proxy object disconnected
08-16 14:23:34.012  6836  6851 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 14:23:34.012  1291  1291 D PbapServerProfile: Bluetooth service disconnected
,08-16 14:23:34.022  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 14:23:34.032  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:34.032  6836  6836 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@92f0c13, channel: 5, state: LISTENING
,08-16 14:23:34.032  6836  6836 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@92f0c13, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3299fb4c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28681e50mSocket: android.net.LocalSocket@2f717849 impl:android.net.LocalSocketImpl@176ca54e fd:FileDescriptor[76]
08-16 14:23:34.032  6836  6836 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f717849 impl:android.net.LocalSocketImpl@176ca54e fd:FileDescriptor[76]
08-16 14:23:34.032  6836  6836 I BtOppRfcommListener: stopping Accept Thread
08-16 14:23:34.032  6836  6836 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3bf4566f, channel: 12, state: LISTENING
08-16 14:23:34.032  6836  6836 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3bf4566f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@279b5d76, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@238cf7cmSocket: android.net.LocalSocket@37505005 impl:android.net.LocalSocketImpl@2e71c85a fd:FileDescriptor[80]
,08-16 14:23:34.032  6836  6836 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37505005 impl:android.net.LocalSocketImpl@2e71c85a fd:FileDescriptor[80]
08-16 14:23:34.032  6836  6910 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 14:23:34.032  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:34.042  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:34.042  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 14:23:34.042  6836  6836 V BluetoothOppManager: cleanUp...
,08-16 14:23:34.052  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = USER_TURN_ON, isTurningOn=false, isTurningOff=true
08-16 14:23:34.052  6836  6851 I BluetoothAdapterState: CURRENT_STATE=PENDING: Deferring request USER_TURN_ON
,08-16 14:23:34.062  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:34.062  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 14:23:34.222  6836  6871 W bt-btif : ag scb idx 1 not allocated
08-16 14:23:34.222  6836  6871 W bt-btif : ag scb idx 2 not allocated
08-16 14:23:34.222  6836  6871 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 14:23:34.222  6836  6893 I bt_userial_mct: exiting userial_read_thread
08-16 14:23:34.222  6836  6893 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 14:23:34.222  6836  6854 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 14:23:34.222  6836  6873 I bt_vendor: hw_epilog_process
08-16 14:23:34.222  6836  6854 D bt_userial_mct: userial_close
08-16 14:23:34.222  6836  6854 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 14:23:34.562   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-16 14:23:34.642  6836  6854 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 14:23:34.642  6836  6854 I bt_vendor: bluetooth satus is on
08-16 14:23:34.642  6836  6854 I bt_vendor: bt-vendor : resetting BT status
08-16 14:23:34.642  6836  6854 I bt_vendor: Starting hciattach daemon
08-16 14:23:34.642  6836  6854 I bt_vendor: try to set false
,08-16 14:23:34.642  6836  6854 I bt_vendor: Starting hciattach daemon
08-16 14:23:34.642  6836  6854 I bt_vendor: try to set false
,08-16 14:23:34.642  6836  6854 I bt_vendor: cleanup
08-16 14:23:34.642  6836  6871 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 14:23:34.642  6836  6854 I GKI_LINUX: GKI_exit_task 0 done
,08-16 14:23:34.642  6836  6854 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 14:23:34.642  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 14:23:34.642  6836  6851 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 14:23:34.642  6836  6851 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 14:23:34.642  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-16 14:23:34.642  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 14:23:34.642  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 14:23:34.652  1014  3288 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 14:23:34.652  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.652  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.652  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.652  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.652  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-16 14:23:34.652  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:34.652  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-16 14:23:34.652  6836  6836 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 14:23:34.652  1014  3286 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.652  6836  6836 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 14:23:34.652  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.652  6836  6836 D BtGatt.GattService: stop()
08-16 14:23:34.652  6836  6836 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 14:23:34.652  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.652  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:34.652  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.662  1014  3287 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.662  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 14:23:34.662  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 14:23:34.662  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:34.662  1014  3287 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.662  1014  3287 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.662  1014  3287 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:34.662  1014  3287 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.662  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 14:23:34.662  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.662  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:34.662  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 14:23:34.662  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.662  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.662  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.662  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.662  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.662  6836  6836 D HeadsetService: Received stop request...Stopping profile...
,08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 14:23:34.672  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 14:23:34.672  1014  3288 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.672  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.672  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.672  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.672  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 14:23:34.672  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.672  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 14:23:34.672  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 14:23:34.672  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:34.672  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.672  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-16 14:23:34.672  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.672  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.672  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:34.682  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.682  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 14:23:34.682  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.682  1291  1291 D HeadsetProfile: Bluetooth service disconnected,
08-16 14:23:34.682  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.682  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:34.682  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.682  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 14:23:34.682  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 14:23:34.682  6836  6851 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-16 14:23:34.682  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.692  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.692  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.692  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:34.692  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:34.692  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.692  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.692  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 14:23:34.692  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 14:23:34.692  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 14:23:34.692  6836  6851 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 14:23:34.692  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-16 14:23:34.692  6836  6836 D A2dpService: Received stop request...Stopping profile...
,08-16 14:23:34.692  6836  6865 D A2dpStateMachine: Exit Disconnected: -1
,08-16 14:23:34.702  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d,
,08-16 14:23:34.702  2823  2823 D BluetoothA2dp: Proxy object disconnected
,08-16 14:23:34.702  1291  1291 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:34.702  1291  1291 D A2dpProfile: Bluetooth service disconnected
08-16 14:23:34.702  6836  6836 D HidService: Received stop request...Stopping profile...
08-16 14:23:34.702  6836  6836 D HidService: Stopping Bluetooth HidService
,08-16 14:23:34.702  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-16 14:23:34.702  6836  6836 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 14:23:34.702  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 14:23:34.702  6836  6836 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-16 14:23:34.702  6836  6836 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 14:23:34.702  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.702  6836  6836 D HealthService: Received stop request...Stopping profile...
,08-16 14:23:34.702  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.702  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-16 14:23:34.702  1291  1291 D HidProfile: Bluetooth service disconnected
,08-16 14:23:34.712  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-16 14:23:34.712  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 14:23:34.712  6836  6836 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 14:23:34.712  6836  6836 D PanService: Received stop request...Stopping profile...
,08-16 14:23:34.712  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.712  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 14:23:34.712  6836  6836 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 14:23:34.712  6836  6836 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 14:23:34.722  6836  6836 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 14:23:34.722  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 14:23:34.722  1291  1291 D PanProfile: Bluetooth service disconnected
,08-16 14:23:34.722  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.722  6836  6836 D SapService: Received stop request...Stopping profile...
08-16 14:23:34.722  6836  6836 D SapService: Stopping Bluetooth SapService
08-16 14:23:34.722  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.722  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-16 14:23:34.732  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService,
08-16 14:23:34.732  6836  6866 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 14:23:34.732  6836  6836 I GKI_LINUX: GKI_exit_task 2 done,
08-16 14:23:34.732  6836  6836 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 14:23:34.732  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 14:23:34.732  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.732  6836  6836 D BluetoothA2dp: Proxy object disconnected,
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-16 14:23:34.732  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 14:23:34.732  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.732  6836  6836 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 14:23:34.732  1291  1291 D BluetoothMap: Proxy object disconnected
08-16 14:23:34.732  1291  1291 D MapProfile: Bluetooth service disconnected
08-16 14:23:34.732  6836  6836 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 14:23:34.732  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 14:23:34.732  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
08-16 14:23:34.732  6836  6836 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 14:23:34.732  6836  6836 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 14:23:34.732  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 14:23:34.732  6836  6836 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 14:23:34.732  6836  6836 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService,
08-16 14:23:34.732  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 14:23:34.732  1291  1291 D SapProfile: Bluetooth service disconnected
08-16 14:23:34.732  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-16 14:23:34.732  6836  6836 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 14:23:34.732  6836  6836 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-16 14:23:34.732  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 14:23:34.732  6836  6851 D BluetoothAdapterProperties: Setting state to 10
08-16 14:23:34.732  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 14:23:34.732  1291  6811 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: Autoconnection is available 
,08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 14:23:34.732  6836  6851 I BluetoothAdapterState: Entering OffState
08-16 14:23:34.732  6836  6851 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-16 14:23:34.732  6836  6851 D BluetoothAdapterProperties: Setting state to 11
08-16 14:23:34.732  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: updateAdapterState state is 11
08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: Autoconnection is available 
08-16 14:23:34.732  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-16 14:23:34.732  6836  6851 D BtConfig.SecureMode: isSecureModeOn:false
08-16 14:23:34.732  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 14:23:34.732  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 10
08-16 14:23:34.732  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:34.732  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
08-16 14:23:34.732  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 14:23:34.742  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.732  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
08-16 14:23:34.742  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-16 14:23:34.732  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
,08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
,08-16 14:23:34.742  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 14:23:34.742  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService,
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 14:23:34.742  6184  6192 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.742  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.742  6184  6192 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:34.742  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-16 14:23:34.742  6387  6398 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.742  6387  6398 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.742  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.742  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.742  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.742  6836  6836 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 14:23:34.742  6836  6836 D BtGatt.GattService: Received start request. Starting profile...
08-16 14:23:34.752  1014  1307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.742  6836  6836 D BtGatt.GattService: start()
08-16 14:23:34.752  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 14:23:34.742  6836  6836 D BtGatt.GattService: start()
08-16 14:23:34.742  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:34.742  6836  6836 D BtGatt.AdvertiseManager: advertise manager created
08-16 14:23:34.742  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.742  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:34.742  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 14:23:34.742  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 14:23:34.742  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 14:23:34.742  1455  1723 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.742  1455  1723 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:34.742  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.742  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.742  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.752  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 14:23:34.752  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 14:23:34.752  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 14:23:34.752  2823  6825 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:34.752  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.752  1014  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.752  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.752  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 14:23:34.752  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 14:23:34.752  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 14:23:34.752  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:34.752  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.752  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.752  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.752  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.752  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.762  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 14:23:34.762  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 14:23:34.762  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 14:23:34.762  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:34.762  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.762  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.762  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.762  1291  1300 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 14:23:34.762  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.762  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.762  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.762  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 14:23:34.762  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.762  6836  6851 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 14:23:34.762  1014  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.762  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.762  2823  2831 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.762  2823  2831 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:34.762  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.762  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.762  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:34.772  6836  6836 D BtGatt.GattService: mStartError = false
,08-16 14:23:34.772  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 14:23:34.772  6836  6836 D HeadsetService: Received start request. Starting profile...
08-16 14:23:34.772  6836  6836 D HeadsetService: start()
08-16 14:23:34.772  6836  6836 D HeadsetStateMachine: make
,08-16 14:23:34.772  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-16 14:23:34.772  6836  6899 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.772  1014  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 14:23:34.772  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.772  6836  6899 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.772  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.772  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.772  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 14:23:34.772  1291  1308 D BluetoothMap: onBluetoothStateChange: up=false
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:34.772  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-16 14:23:34.772  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.772  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 14:23:34.772  6836  6851 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 14:23:34.772  6836  6851 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 14:23:34.772  6836  6851 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 14:23:34.772  6836  6836 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 14:23:34.782  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:34.782  1014  1701 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 14:23:34.782  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.782  1014  1701 W ActivityManager: userId = 0, bbcId = -10000,
08-16 14:23:34.782  1014  1701 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.782  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 14:23:34.782  6836  6855 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 14:23:34.782  1014  1492 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 14:23:34.782  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-16 14:23:34.782  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.782  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.782  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 14:23:34.782  6836  6836 I bluedroid: get_profile_interface handsfree
,08-16 14:23:34.782  1291  6811 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.782  1291  6811 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.782  1924  2119 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.782  1924  2119 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.782  1443  1466 D BluetoothAdapter: onBluetoothStateChange: up=false,
,08-16 14:23:34.792  1443  1466 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 14:23:34.792  1431  6924 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.792  1431  6924 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:34.792  1178  2343 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 14:23:34.792  6836  6836 E DualScoManager: Dual Sco Manager already instantiated
08-16 14:23:34.792  6836  6836 I DualScoManager: Set HeadsetServiceHelper
08-16 14:23:34.792  6836  6836 D BluetoothAtMessage: createCMTIContentObservers
,08-16 14:23:34.792  1178  2343 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 14:23:34.792  1014  3244 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 14:23:34.792  1014  3244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:34.792  1014  3244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:34.792  1014  3244 D SettingsProvider: selectionArgs: false
08-16 14:23:34.792  1014  3244 D SettingsProvider: selectionArgs: 1002
08-16 14:23:34.792  1014  3244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:34.792  1014  3244 D SettingsProvider: ret = -1
,08-16 14:23:34.792  6836  6836 D HeadsetService: mStartError = false
08-16 14:23:34.792  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.792  6836  6836 D A2dpService: Received start request. Starting profile...
08-16 14:23:34.792  6836  6836 D A2dpService: start()
08-16 14:23:34.792  6836  6836 I bluedroid: get_profile_interface avrcp
08-16 14:23:34.792  6836  6927 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 14:23:34.792  1291  1308 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 14:23:34.792  1291  1308 D Bluetoothsap: Unbinding service...
,08-16 14:23:34.802  6836  6836 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 14:23:34.802  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:34.802  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-16 14:23:34.802  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 14:23:34.802  6836  6927 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 14:23:34.802  6836  6927 D HeadsetStateMachine: map size, before remove : 0
08-16 14:23:34.802  6836  6927 D HeadsetStateMachine: map size, after remove: 0
,08-16 14:23:34.802  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:34.802  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:34.802  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-16 14:23:34.812  1790  1790 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:34.812  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:34.812  1014  3288 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 14:23:34.812  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 14:23:34.812  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:34.812  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:34.812  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:34.812  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-16 14:23:34.812  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:34.822  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-16 14:23:34.822  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-16 14:23:34.822  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
08-16 14:23:34.822  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 14:23:34.822  1014  1132 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-16 14:23:34.822  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 14:23:34.822  1790  1790 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 14:23:34.822  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 14:23:34.822  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
08-16 14:23:34.822  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:34.822  1014  1701 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:34.822  1014  1701 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.832  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:34.832  6836  6836 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 14:23:34.832  6836  6928 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 14:23:34.832  6836  6836 D A2dpStateMachine: make
,08-16 14:23:34.832  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.832  1014  1701 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:34.832  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:34.842  6836  6836 I bluedroid: get_profile_interface a2dp
,08-16 14:23:34.842  6836  6930 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 14:23:34.842  6836  6836 E bt-btif : warning : media task started media_task_refcnt 1 
08-16 14:23:34.842  6836  6836 D A2dpService: mStartError = false
08-16 14:23:34.842  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.842  6836  6836 D HidService: Received start request. Starting profile...
08-16 14:23:34.842  6836  6836 D HidService: start()
08-16 14:23:34.842  6836  6836 I bluedroid: get_profile_interface hidhost
08-16 14:23:34.842  6836  6836 D HidService: setHidService(): set to: null
08-16 14:23:34.842  6836  6836 D HidService: mStartError = false
08-16 14:23:34.842  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:34.842  6836  6929 D A2dpStateMachine: Enter Disconnected: -2
08-16 14:23:34.842  6836  6836 D HealthService: Received start request. Starting profile...
08-16 14:23:34.842  6836  6836 D HealthService: start()
,08-16 14:23:34.842  1014  3288 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 14:23:34.842  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-16 14:23:34.842  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.842  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:34.842  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:34.852  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:34.852  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:34.852  6836  6836 I bluedroid: get_profile_interface health
08-16 14:23:34.852  6836  6836 D HealthService: mStartError = false
08-16 14:23:34.852  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.852  6836  6836 D PanService: Received start request. Starting profile...
08-16 14:23:34.852  6836  6836 D PanService: start()
08-16 14:23:34.852  6836  6836 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 14:23:34.852  6836  6836 I bluedroid: get_profile_interface pan
08-16 14:23:34.852  6836  6836 D PanService: mStartError = false
08-16 14:23:34.852  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:34.852  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-16 14:23:34.852  6836  6836 D BluetoothMapService: Received start request. Starting profile...
08-16 14:23:34.852  6836  6836 D BluetoothMapService: start()
,08-16 14:23:34.852  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:34.852  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:34.852  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:34.862  6836  6836 D BluetoothMapService: mStartError = false
08-16 14:23:34.862  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:34.862  6836  6836 D SapService: Received start request. Starting profile...
08-16 14:23:34.862  6836  6836 D SapService: start()
08-16 14:23:34.862  6836  6836 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 14:23:34.862  6836  6836 I bluedroid: get_profile_interface sap
08-16 14:23:34.862  6836  6836 D SapService: mStartError = false
08-16 14:23:34.862  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
08-16 14:23:34.862  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:34.862  6836  6836 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 14:23:34.862  1431  1453 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 14:23:34.862  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:34.862  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-16 14:23:34.862  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 14:23:34.862  1431  1453 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 14:23:34.862  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:34.872  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 14:23:34.872  6836  6836 D HeadsetStateMachine: Proxy object connected
08-16 14:23:34.872  6836  6836 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-16 14:23:34.872  6836  6836 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 14:23:34.872  6836  6836 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 14:23:34.872  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 14:23:34.872  6836  6836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 14:23:34.872  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 14:23:34.872  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 14:23:34.872  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-16 14:23:34.872  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-16 14:23:34.872  6836  6927 D HeadsetStateMachine: Disconnected process message: 11
08-16 14:23:34.872  6836  6927 D HeadsetStateMachine: Disconnected process message: 18
08-16 14:23:34.872  6836  6927 D HeadsetStateMachine: Disconnected process message: 10
08-16 14:23:34.872  6836  6927 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 14:23:34.872  6836  6927 D HeadsetStateMachine: Disconnected process message: 11
,08-16 14:23:34.872  6836  6928 D BluetoothMediaBrowser: no now playing list
,08-16 14:23:34.872  6836  6928 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 14:23:34.882  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-16 14:23:34.882  6836  6836 E BluetoothAdapterService(125592205): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 14:23:34.892  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 14:23:34.892  6836  6851 I bluedroid: enable
08-16 14:23:34.892  6836  6851 I bt_hci_bdroid: init
,08-16 14:23:34.892  6836  6851 I bt_vendor: bt-vendor : init
08-16 14:23:34.892  6836  6851 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 14:23:34.892  6836  6851 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 14:23:34.892  6836  6851 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 14:23:34.892  6836  6851 D bt_userial_mct: userial_init
08-16 14:23:34.892  6836  6936 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 14:23:34.892  6836  6851 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 14:23:34.892  6836  6851 I bt_vendor: Starting hciattach daemon
08-16 14:23:34.892  6836  6851 I bt_vendor: try to set false
,08-16 14:23:34.892  6836  6851 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 14:23:34.892  6836  6851 I bt_vendor: Starting hciattach daemon
08-16 14:23:34.892  6836  6851 I bt_vendor: try to set true
,08-16 14:23:34.912  6942  6942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 14:23:34.912  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:34.912  1014  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:34.912  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0,
,08-16 14:23:34.922  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:34.922  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:34.922  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:34.942  1924  6951 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 14:23:34.942  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
,08-16 14:23:34.962  6954  6954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 14:23:34.972  6955  6955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 14:23:34.982  6957  6957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 14:23:34.992  6958  6958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 14:23:35.002  6959  6959 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 14:23:35.012  6960  6960 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 14:23:35.092  1014  3288 I art     : Explicit concurrent mark sweep GC freed 31496(1813KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.328ms total 142.856ms
,08-16 14:23:35.092  1014  3288 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:35.092  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.092  1014  3288 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:35.092  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:35.102  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:35.102  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:35.112  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 14:23:35.112  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:35.112  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.112  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:35.112  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:35.122  1924  6951 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 14:23:35.132  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:35.132  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:35.312  6964  6964 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 14:23:35.322  6965  6965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 14:23:35.352  6836  6851 I bt_vendor: bluetooth satus is on,
08-16 14:23:35.352  6836  6938 D bt_userial_mct: userial_open(port:0)
08-16 14:23:35.352  6836  6938 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 14:23:35.352  6836  6938 I bt_vendor: Done intiailizing UART,
,08-16 14:23:35.352  6836  6938 I bt_vendor: Done intiailizing UART
08-16 14:23:35.352  6836  6938 I bt_userial_mct: CMD=73, EVT=73, ACL_Out=74, ACL_In=74
08-16 14:23:35.352  6836  6938 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 14:23:35.352  6836  6936 E bt-att  : DIS already initalized
08-16 14:23:35.362  6836  6967 D bt_userial_mct: Entering userial_read_thread()
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 14:23:35.362  6836  6936 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 14:23:35.462  6836  6936 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 14:23:35.462  6836  6936 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40a16e9 
,08-16 14:23:35.462  6836  6936 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40a16e9 
,08-16 14:23:35.482  6836  6854 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 14:23:35.482  6836  6854 E bt-btif : Calling BTA_HhEnable
,08-16 14:23:35.482  6836  6854 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 14:23:35.492  6836  6854 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-16 14:23:35.492  6836  6854 E BluetoothServiceJni: populateRssiValuesNative
08-16 14:23:35.492  6836  6854 I bluedroid: getModelRssiValues
08-16 14:23:35.492  6836  6854 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 14:23:35.492  6836  6854 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 14:23:35.492  6836  6854 D BluetoothAdapterProperties: Name is: A5-1
,08-16 14:23:35.492  1014  1014 D SettingsProvider: name = bluetooth_name
,08-16 14:23:35.492  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:35.492  6836  6854 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 14:23:35.492  6836  6854 D BluetoothAdapterProperties: Scan Mode:20
,08-16 14:23:35.492  6836  6854 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:35.502  6836  6854 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 14:23:35.502  6836  6854 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 14:23:35.502  6836  6854 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 14:23:35.502  6836  6854 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 14:23:35.502  6836  6854 E bt-btif : btif_sock_init: !vhci_init
,08-16 14:23:35.502  6836  6854 D bte_conf: Device ID record 1 : primary
,08-16 14:23:35.502  6836  6854 D bte_conf:   vendorId            = 0075
08-16 14:23:35.502  6836  6854 D bte_conf:   vendorIdSource      = 0001
08-16 14:23:35.502  6836  6854 D bte_conf:   product             = 0100
08-16 14:23:35.502  6836  6854 D bte_conf:   version             = 0200
08-16 14:23:35.502  6836  6854 D bte_conf:   clientExecutableURL = 
,08-16 14:23:35.502  6836  6854 D bte_conf:   serviceDescription  = 
08-16 14:23:35.502  6836  6854 D bte_conf:   documentationURL    = 
08-16 14:23:35.502  6836  6854 D bte_conf: bte_load_did_conf no section named DID2.
08-16 14:23:35.502  6836  6854 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 14:23:35.502  6836  6851 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 14:23:35.502  6836  6851 D BluetoothAdapterProperties: ScanMode =  20
,08-16 14:23:35.502  6836  6851 D BluetoothAdapterProperties: State =  11
,08-16 14:23:35.502  1014  1132 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 14:23:35.502  6836  6851 D BluetoothAdapterProperties: Setting state to 12
,08-16 14:23:35.512  6836  6851 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 14:23:35.512  6836  6967 E bt_mct  : hci lib postload completed
,08-16 14:23:35.522  6836  6854 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 14:23:35.522  6836  6854 D BluetoothAdapterProperties: Scan Mode:21
08-16 14:23:35.522  6836  6854 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 14:23:35.522  1014  1132 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 14:23:35.522  1014  1132 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 14:23:35.522  1014  1132 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 14:23:35.522  1014  1132 D SettingsProvider: selectionArgs: false
08-16 14:23:35.522  1014  1132 D SettingsProvider: selectionArgs: 1002
08-16 14:23:35.522  1014  1132 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 14:23:35.522  1014  1132 D SettingsProvider: ret = -1
,08-16 14:23:35.522  6836  6851 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 14:23:35.522  6836  6851 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:35.522  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:35.522  1014  1132 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:35.522  1014  1132 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.532  1014  1132 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.532  1014  1132 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:35.532  1014  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.532  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.532  6836  6851 D BluetoothAdapterService: Autoconnection is available 
08-16 14:23:35.532  6836  6851 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 14:23:35.532  6836  6851 D BluetoothAdapterService: starting service from this receiver
,08-16 14:23:35.532  1014  3244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:35.532  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 14:23:35.532  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.532  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.532  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.542  6836  6851 I BluetoothAdapterState: Entering On State from state = 11
,08-16 14:23:35.542  6836  6836 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-16 14:23:35.542  6836  6836 I BluetoothPbapService: Handler(): got msg=1
,08-16 14:23:35.542  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:35.542  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.542  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 14:23:35.542  1291  6811 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 14:23:35.542  1014  3288 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 14:23:35.542  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:35.552  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap,
08-16 14:23:35.552  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.552  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
08-16 14:23:35.552  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:35.552  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-16 14:23:35.552  6836  6970 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 14:23:35.552  6836  6970 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 14:23:35.552  1431  6924 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.562  6836  6970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:35.562  1291  1291 D BluetoothPbap: Proxy object connected
,08-16 14:23:35.562  1291  1291 D PbapServerProfile: Bluetooth service connected
08-16 14:23:35.562  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:35.562  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.562  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.562  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.562  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.562  1431  6924 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:35.562  6836  6970 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-16 14:23:35.562  6836  6970 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:35.562  6836  6970 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:35.562  6836  6970 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@988dbe3
,08-16 14:23:35.562  6184  6193 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.562  6184  6193 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.562  6836  6970 D BluetoothSocket: channel: 19
,08-16 14:23:35.562  6387  6398 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.562  6387  6398 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.562  6836  6970 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 14:23:35.562  1455  1681 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.562  1455  1681 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:35.562  1431  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.572  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 14:23:35.572  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.572  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.572  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.572  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.572  1431  1442 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 14:23:35.572  2823  2831 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:35.572  2823  2831 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.572  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 14:23:35.572  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.572  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.572  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.572  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.582  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:35.582  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 14:23:35.582  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:35.582  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.582  1014  1014 D BluetoothA2dp: Proxy object connected
,08-16 14:23:35.582  2823  2823 D BluetoothA2dp: Proxy object connected
08-16 14:23:35.582  1291  1308 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.582  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 14:23:35.582  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.582  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.582  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.582  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.582  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-16 14:23:35.582  1291  1308 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:35.582  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:35.582  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.592  1291  1300 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 14:23:35.592  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 14:23:35.592  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.592  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.592  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.592  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.592  2823  6825 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:35.592  2823  6825 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.592  1291  1291 D BluetoothInputDevice: Proxy object connected
08-16 14:23:35.592  1291  1291 D HidProfile: Bluetooth service connected
08-16 14:23:35.592  1291  1308 D BluetoothPan: Binding service...
,08-16 14:23:35.592  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 14:23:35.592  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.592  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.592  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.592  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.592  6836  6846 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.592  6836  6846 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.592  1291  6811 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 14:23:35.602  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 14:23:35.602  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.602  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 14:23:35.602  1291  1291 D PanProfile: Bluetooth service connected
08-16 14:23:35.602  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.602  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.602  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.602  1014  1043 D BluetoothPan: Binding service...
,08-16 14:23:35.602  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 14:23:35.602  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 14:23:35.602  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 14:23:35.602  2823  2831 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.602  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:35.602  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 14:23:35.602  1291  1291 D BluetoothMap: Proxy object connected
08-16 14:23:35.602  1291  1291 D MapProfile: Bluetooth service connected
08-16 14:23:35.602  1291  1291 D BluetoothMap: getConnectedDevices()
08-16 14:23:35.602  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.602  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.602  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.602  2823  2831 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 14:23:35.602  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 14:23:35.602  1291  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.602  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:35.602  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.612  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.612  6836  6846 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 14:23:35.612  1291  1291 D BluetoothA2dp: Proxy object connected
,08-16 14:23:35.612  6836  6846 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.612  1014  1043 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 14:23:35.612  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.612  1291  1291 D A2dpProfile: Bluetooth service connected
08-16 14:23:35.612  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.612  6836  6836 D BluetoothA2dp: Proxy object connected
08-16 14:23:35.612  6836  6836 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-16 14:23:35.612  1291  1308 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.612  1291  1308 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.612  1924  1933 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.612  1924  1933 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:35.612  1455  1475 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.612  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 14:23:35.612  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.612  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.612  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.612  1455  1475 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:35.622  1431  6924 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 14:23:35.622  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 14:23:35.622  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 14:23:35.622  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.622  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.622  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.622  1431  6924 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 14:23:35.622  1443  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 14:23:35.622  1443  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.622  1431  6897 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.622  1431  6897 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 14:23:35.622  1178  1206 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 14:23:35.622  1178  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 14:23:35.622  1291  1300 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 14:23:35.622  1291  1300 D Bluetoothsap: Binding service...
,08-16 14:23:35.622  1291  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 14:23:35.622  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-16 14:23:35.622  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.622  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.622  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.632  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.632  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 14:23:35.632  1291  1291 D SapProfile: Bluetooth service connected
08-16 14:23:35.632  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-16 14:23:35.632  1291  1300 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 14:23:35.632  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 14:23:35.632  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 14:23:35.632  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:35.632  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-16 14:23:35.632  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 14:23:35.642  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-16 14:23:35.642  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@359ec508, true
,08-16 14:23:35.642  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 14:23:35.642  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 14:23:35.642  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-16 14:23:35.642  1431  1431 D BluetoothHeadset: registerMessageListener
,08-16 14:23:35.642  1790  1790 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 14:23:35.642  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:35.642  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:35.652  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:35.652  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:35.652  1014  3288 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:35.652  1014  3292 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 14:23:35.652  1014  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:35.652  1014  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.652  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 14:23:35.652  6836  6972 D HeadsetService: registerMessageListener
,08-16 14:23:35.662  6836  6972 D HeadsetService: registerMessageListener,
,08-16 14:23:35.662  1178  1714 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 14:23:35.662  6836  6927 D HeadsetStateMachine: Disconnected process message: 70
08-16 14:23:35.662  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null,
,08-16 14:23:35.662  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.662  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 14:23:35.662  6836  6927 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@36d6f9e0
08-16 14:23:35.662  1014  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 14:23:35.662  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 14:23:35.662  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 14:23:35.662  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.,
08-16 14:23:35.662  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 14:23:35.662  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 14:23:35.662  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 14:23:35.662  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 14:23:35.662  6836  6973 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-16 14:23:35.662  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 14:23:35.662  6836  6927 D HeadsetStateMachine: Disconnected process message: 9
08-16 14:23:35.662  6836  6927 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 14:23:35.672   287   694 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-16 14:23:35.672  6836  6973 D BluetoothSocket: bindListen(): myUserId = 0
08-16 14:23:35.672  6836  6973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 14:23:35.672   287   694 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 14:23:35.672   287   694 V voice   : voice_set_parameters: exit with code(-2)
08-16 14:23:35.672   287   694 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 14:23:35.672   287   694 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 14:23:35.672   287   694 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 14:23:35.672   287   694 V audio_hw_primary: adev_set_parameters: exit
08-16 14:23:35.672  6836  6927 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 14:23:35.672  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 14:23:35.672  6836  6973 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[83]}
08-16 14:23:35.672  6836  6973 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:35.672  6836  6973 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:35.672  6836  6973 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3cead499
,08-16 14:23:35.672  6836  6973 D BluetoothSocket: channel: 5
,08-16 14:23:35.672  1014  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 14:23:35.672  1014  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.672  1014  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.672  1014  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:35.672  1014  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 14:23:35.692  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-16 14:23:35.692  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 14:23:35.692  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 14:23:35.692  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 14:23:35.702  6836  6836 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:35.702  6836  6836 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 14:23:35.702  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 14:23:35.702  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.702  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:35.702  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:35.702  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 14:23:35.722  1014  1132 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-16 14:23:35.722  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 14:23:35.722  1014  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 14:23:35.722  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 14:23:35.722  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.722  1014  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:35.722  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:35.732  1924  6983 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 14:23:35.732  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 14:23:35.732  6836  6982 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 14:23:35.732  6836  6982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 14:23:35.742  6836  6982 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
08-16 14:23:35.742  6836  6982 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 14:23:35.742  6836  6982 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 14:23:35.742  6836  6982 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b0b2155
08-16 14:23:35.742  6836  6982 D BluetoothSocket: channel: 12
08-16 14:23:35.742  6836  6982 I BtOppRfcommListener: Accept thread started.
,08-16 14:23:35.742  1014  3292 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 14:23:35.742  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:35.742  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 14:23:35.742  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 14:23:35.742  1924  6983 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:36.022  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:36.022  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
08-16 14:23:36.022  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:36.022  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96da2f0 added. We now have 8 listener(s)
,08-16 14:23:36.022  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:36.022  1014  1345 D SecContentProvider: uri = 18 selection = isWifiEnabled,
,08-16 14:23:36.022  1014  1345 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
,08-16 14:23:36.032  1014  1345 D SecContentProvider2: mCursor = null
,08-16 14:23:36.032  1014  1345 D WifiService: setWifiEnabled: false pid=6184, uid=10155,
,08-16 14:23:36.032  1014  1345 D SettingsProvider: name = wifi_on
,08-16 14:23:36.032  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:36.032  1014  1701 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 14:23:36.042  1014  1701 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 14:23:36.042  1014  1701 D SecContentProvider2: mCursor = null
,08-16 14:23:36.042  1014  1701 D WifiService: setWifiEnabled: true pid=6184, uid=10155
,08-16 14:23:36.042  1014  1701 W ActivityManager: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 14:23:36.042  1014  1701 W WifiService: Failed getting userId using ActivityManagerNative
08-16 14:23:36.042  1014  1701 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6184, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 14:23:36.042  1014  1701 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 14:23:36.042  1014  1701 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 14:23:36.042  1014  1701 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 14:23:36.042  1014  1701 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 14:23:36.042  1014  1701 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 14:23:36.042  1014  1701 D SettingsProvider: name = wifi_on
,08-16 14:23:36.052  1014  1122 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 14:23:36.392  1014  1041 D Tethering: interfaceAdded wlan0
,08-16 14:23:36.392  1014  1127 E Tethering: No numeric data
,08-16 14:23:36.392  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
,08-16 14:23:36.392  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.402  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:23:36.402  1014  1127 D Tethering: clearTetheredNotification()
08-16 14:23:36.402  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 14:23:36.402  1178  1178 D HotspotTile: updateTetherState():false, false
08-16 14:23:36.402  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:36.402  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 14:23:36.402  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 14:23:36.402  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 14:23:36.402  1014  1119 V NetworkStats: performPollLocked() took 10ms
08-16 14:23:36.402  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-16 14:23:36.402  1014  1127 D Tethering: InitialState.processMessage what=4
08-16 14:23:36.412  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.412  1014  1127 E Tethering: No numeric data
08-16 14:23:36.412  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 14:23:36.412  1014  1127 D Tethering: clearTetheredNotification()
08-16 14:23:36.412  1014  1041 D Tethering: interfaceAdded p2p0
08-16 14:23:36.412  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 14:23:36.412  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 14:23:36.412  1178  1178 D HotspotTile: updateTetherState():false, false
08-16 14:23:36.422  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:36.422  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-16 14:23:36.422   280   966 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 14:23:36.422   280   966 D SoftapController: Softap fwReload - Ok
08-16 14:23:36.422  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.422  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
08-16 14:23:36.422  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.432  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.432   280   966 D CommandListener: Setting iface cfg
08-16 14:23:36.432  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:36.432   280   966 D CommandListener: Trying to bring down wlan0
08-16 14:23:36.432  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:36.432  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 14:23:36.432   280   966 D CommandListener: Clearing all IP addresses on wlan0
08-16 14:23:36.432  1014  1119 V NetworkStats: performPollLocked() took 10ms
,08-16 14:23:36.442  1014  1122 E WifiHW  : supplicant_name : p2p_supplicant
08-16 14:23:36.442  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:36.442  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.442  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:36.442  1014  1122 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 14:23:36.442  1014  1122 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-16 14:23:36.452  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:36.452  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 14:23:36.452  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 14:23:36.452  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:36.452  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:36.452  1178  1178 D HotspotTile: onReceive : 2, 0
08-16 14:23:36.452  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:36.452  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 14:23:36.452  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:36.452  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:36.452  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 14:23:36.472  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:36.472  1014  1486 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:36.472  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:36.472  1014  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:36.472  1014  1486 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:36.472  1014  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:36.472  1014  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 14:23:36.482  3614  3614 I Hs20UtilService: Starting #17
08-16 14:23:36.482  3614  3648 I Hs20UtilService: Message received 5011
,08-16 14:23:36.482  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 14:23:36.482  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:36.482  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:36.482  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:36.502  6994  6994 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 14:23:36.502  6994  6994 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 14:23:36.502  6994  6994 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 14:23:36.512  6994  6994 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-16 14:23:36.512   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6994
08-16 14:23:36.512   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 14:23:36.512  6994  6994 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 14:23:36.512  6994  6994 I wpa_supplicant: ssSupport state is = 1,
08-16 14:23:36.512  6994  6994 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 14:23:36.512  6994  6994 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 14:23:36.512   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6994
,08-16 14:23:36.512   397   397 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-16 14:23:36.582   293   293 E SMD     : DCD OFF,
,08-16 14:23:36.672   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-16 14:23:36.682  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-16 14:23:36.742  6994  6994 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 14:23:36.742  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-16 14:23:36.752  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 14:23:36.752   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6994
08-16 14:23:36.752   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-16 14:23:36.752  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 14:23:36.752  6994  6994 I wpa_supplicant: ssSupport state is = 1
08-16 14:23:36.752  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:36.752  6994  6994 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:36.752  6994  6994 E wpa_supplicant: SIM READ ERROR
08-16 14:23:36.752  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:36.752  6994  6994 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:36.752  6994  6994 E wpa_supplicant: SIM READ ERROR
08-16 14:23:36.752  6994  6994 I wpa_supplicant: Blacklist: Clear (all) 
08-16 14:23:36.752  6994  6994 I wpa_supplicant: wpa_default_ap_write_once
08-16 14:23:36.752  6994  6994 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 14:23:36.752  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:36.752  6994  6994 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 14:23:36.752  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:36.752  6994  6994 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:36.762  6994  6994 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:23:36.762  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 14:23:36.762  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 14:23:36.762  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:36.852  6994  6994 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 14:23:37.052  6994  6994 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 14:23:37.052  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 14:23:37.062  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-16 14:23:37.062   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6994
08-16 14:23:37.062   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 14:23:37.062  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 14:23:37.062  6994  6994 I wpa_supplicant: ssSupport state is = 1
,08-16 14:23:37.062  6994  6994 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-16 14:23:37.072  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 14:23:37.082  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,08-16 14:23:37.082   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6994
08-16 14:23:37.082   397   397 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 14:23:37.082  6994  6994 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
08-16 14:23:37.082  6994  6994 I wpa_supplicant: ssSupport state is = 1
,08-16 14:23:37.082  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 14:23:37.082  6994  6994 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:37.082  6994  6994 E wpa_supplicant: SIM READ ERROR
08-16 14:23:37.082  6994  6994 I wpa_supplicant: wpa_default_ap_write_once
,08-16 14:23:37.082  6994  6994 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-16 14:23:37.082  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:37.082  6994  6994 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 14:23:37.082  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 14:23:37.082  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:37.082  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-16 14:23:37.082  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 14:23:37.082  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-16 14:23:37.122  1014  1026 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-16 14:23:37.122  1014  1026 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4280, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
,08-16 14:23:37.122  1014  1026 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
,08-16 14:23:37.122  1014  1026 D BatteryService: stay LED for charging,
,08-16 14:23:37.122  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,08-16 14:23:37.122  1014  1014 I MotionRecognitionService: Plugged
08-16 14:23:37.122  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 14:23:37.132  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 14:23:37.132  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 14:23:37.132  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 14:23:37.132  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-16 14:23:37.132  6994  6994 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-16 14:23:37.132  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 14:23:37.142  6836  6836 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 14:23:37.142  6836  6927 D HeadsetStateMachine: Disconnected process message: 10
,08-16 14:23:37.152  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:37.152  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-16 14:23:37.152  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-16 14:23:37.172  6994  6994 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-16 14:23:37.172  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 14:23:37.172  6994  6994 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 14:23:37.402  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 14:23:37.402  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-16 14:23:37.402  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 14:23:37.452  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,08-16 14:23:37.452  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-16 14:23:37.452  6994  6994 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 14:23:37.452  6994  6994 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 14:23:37.452  6994  6994 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 14:23:37.452  6994  6994 E wpa_supplicant: SIM READ ERROR,
08-16 14:23:37.452  6994  6994 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 14:23:37.482  6994  6994 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 14:23:37.492  1014  1122 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 14:23:37.492  6994  6994 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 14:23:37.492  1014  1122 D WifiConfigStore: Loading config and enabling all networks 
,08-16 14:23:37.502  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:37.502  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 14:23:37.502  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:37.502  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:37.502  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:37.502  1178  1714 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 14:23:37.502  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:37.502  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:37.502  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 14:23:37.502  1178  1178 D HotspotTile: onReceive : 3, 0
,08-16 14:23:37.502  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 14:23:37.502  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:37.512  6184  6184 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:37.512  1014  1122 E WifiConfigStore: Not a HS20
,08-16 14:23:37.512  1014  1122 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 14:23:37.512  1014  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:37.512  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:37.512  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:37.512  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:37.512  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:37.512  6184  6184 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:37.512  1014  1122 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 14:23:37.512  3614  3614 I Hs20UtilService: Starting #18
,08-16 14:23:37.522  1014  1122 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-16 14:23:37.522  3614  3648 I Hs20UtilService: Message received 5011
08-16 14:23:37.522  6994  6994 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON,
08-16 14:23:37.522  6994  6994 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
08-16 14:23:37.522  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 14:23:37.522  6535  6535 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 14:23:37.522  6535  6535 D SecurityLogAgent: StateMachine : Current State = 1
08-16 14:23:37.522  6535  6535 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 14:23:37.522  6994  6994 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-16 14:23:37.522  6994  6994 I wpa_supplicant: P2P: Current p2p state = IDLE,
08-16 14:23:37.522  6994  6994 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-16 14:23:37.522  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 14:23:37.522  6994  6994 I wpa_supplicant: First Scan Start
08-16 14:23:37.522  6994  6994 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 14:23:37.522  1014  1122 D WifiNative-wlan0: Setting external_sim to 1
08-16 14:23:37.522  1014  1122 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 14:23:37.522  1014  1122 I WifiNative-HAL: startHal
08-16 14:23:37.522  1014  1122 E wifi    : getStaticLongField sWifiHalHandle 0x9cc9e88c
08-16 14:23:37.522  1014  1122 I WifiNative-HAL: Could not start hal
,08-16 14:23:37.532  6484  6484 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 14:23:37.532  1014  1122 E WifiNative-wlan0: do suspend true
,08-16 14:23:37.532  1014  1121 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 14:23:37.532  1014  1122 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-16 14:23:37.532   280   966 D CommandListener: Setting iface cfg
,08-16 14:23:37.532  1014  1121 D WifiP2pService: P2pEnablingState
08-16 14:23:37.532   280   966 D CommandListener: Trying to bring up p2p0
08-16 14:23:37.532  1014  1121 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 14:23:37.532  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 14:23:37.532  1014  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 14:23:37.532  1014  1147 I WifiNative-HAL: startHal
08-16 14:23:37.532  1014  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9ddfd9bc
08-16 14:23:37.532  1014  1147 I WifiNative-HAL: Could not start hal
08-16 14:23:37.532  1014  1147 E WifiScanningService: could not start HAL
08-16 14:23:37.532  1014  1121 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 14:23:37.532  1014  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 14:23:37.542  1014  1121 D WifiP2pService: P2p socket connection successful
08-16 14:23:37.532  1014  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 14:23:37.532  1014  1122 E WifiNative-wlan0: invaild command id : 215
08-16 14:23:37.542  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-16 14:23:37.542  1014  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:37.542  1014  1122 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 14:23:37.542  1014  1122 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 14:23:37.542  1014  1122 E WifiNative-wlan0: invaild command id : 215
,08-16 14:23:37.542  1014  1121 D WifiP2pService: P2pEnabledState
,08-16 14:23:37.542  6994  6994 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 14:23:37.542  1014  1121 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 14:23:37.542  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 14:23:37.542  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:37.542  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 14:23:37.542  6994  6994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 14:23:37.542  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:37.542  6994  6994 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-16 14:23:37.542  1014  1044 D WifiDisplayController: disconnect
08-16 14:23:37.542  1014  1044 D WifiDisplayController: updateConnection
08-16 14:23:37.542  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 14:23:37.542  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:37.552  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 14:23:37.552  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 14:23:37.552  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 14:23:37.552  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:37.552  1014  1122 D SecContentProvider2: mCursor = null
08-16 14:23:37.552  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-16 14:23:37.552  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-16 14:23:37.552  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 14:23:37.552  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 14:23:37.552  1014  1121 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 14:23:37.552  1014  1121 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-16 14:23:37.552  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:37.552  1014  1122 D SecContentProvider2: mCursor = null
08-16 14:23:37.552  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 14:23:37.552  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 14:23:37.552  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:37.552  1014  1121 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 14:23:37.562  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  secondary type: null
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  wps: 0
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  grpcapab: 0
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  devcapab: 0
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  status: 3
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  wfdInfo: null
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-16 14:23:37.562  1014  1044 D WifiDisplayController:  SConnectInfo : null
,08-16 14:23:37.562  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 14:23:37.562  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:37.562  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 14:23:37.562  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:37.562  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:37.572  6443  6443 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 14:23:37.572  6443  6443 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 14:23:37.572  6461  6461 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 14:23:37.582  1014  1121 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 14:23:37.582  1014  1121 D WifiP2pService: InactiveState
,08-16 14:23:37.582  1014  1121 D WifiP2pService: InactiveState{ what=143376 }
08-16 14:23:37.582  1014  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 14:23:37.582  6994  6994 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 14:23:37.582  1014  1121 D WifiP2pService: InactiveState{ what=143376 }
,08-16 14:23:37.582  1014  1121 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:38.062  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:38.072  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@342719f2 Bundle[{}]
08-16 14:23:38.072  6184  6234 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 14:23:38.072  6184  6234 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 14:23:38.072  6184  6234 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 14:23:38.082  6184  6234 I System.out: Running OutgoingSocketThread
,08-16 14:23:38.082  6184  7004 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1161)
,08-16 14:23:38.092  6184  7004 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41526,
08-16 14:23:38.092  6184  7004 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,08-16 14:23:38.812  6994  6994 I wpa_supplicant: nl80211: Received scan results (32 BSSes),
08-16 14:23:38.812  6994  6994 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 14:23:38.812  6994  6994 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-16 14:23:38.812  6994  6994 I wpa_supplicant: Trying to associate with  'G700'
08-16 14:23:38.812  6994  6994 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-16 14:23:38.812  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 14:23:38.812  1014  7002 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-16 14:23:38.832  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:38.832  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:38.912  1014  2718 D SSRM:n  : SIOP:: AP = 320
,08-16 14:23:38.932  6994  6994 E wpa_supplicant: Cmd 35605 not handled
,08-16 14:23:38.932  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:38.932  6994  6994 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 14:23:38.932  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-16 14:23:38.932  6994  6994 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-16 14:23:38.932  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 14:23:38.932  6994  6994 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 14:23:38.932  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 14:23:38.932  6994  6994 I wpa_supplicant: Associated with F4.99.3E
08-16 14:23:38.932  6994  6994 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 14:23:38.932  6994  6994 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 14:23:38.932  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 14:23:38.932  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 14:23:38.932  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-16 14:23:38.932  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:38.932  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 14:23:38.932  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-16 14:23:38.942  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 14:23:38.942  6994  6994 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 14:23:38.942  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,08-16 14:23:38.942  6994  6994 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 14:23:38.942  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,08-16 14:23:38.942  6994  6994 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 14:23:38.942  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 14:23:38.942  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 14:23:38.942  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:38.942  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:38.942  6994  6994 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 14:23:38.942  6994  6994 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 14:23:38.942  6994  6994 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 14:23:38.942  6994  6994 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 14:23:38.942  6994  6994 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-16 14:23:38.942  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 14:23:38.942  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:38.952  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 14:23:38.952  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,08-16 14:23:38.952  1014  1127 E Tethering: No numeric data
08-16 14:23:38.952  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 14:23:38.952  1014  1127 D Tethering: clearTetheredNotification()
08-16 14:23:38.952  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 14:23:38.952  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 14:23:38.952  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
08-16 14:23:38.952  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 14:23:38.952  1178  1178 D HotspotTile: updateTetherState():false, false
08-16 14:23:38.962  1014  1122 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 14:23:38.962  1014  1122 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 14:23:38.962  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 14:23:38.962  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:38.962  1014  1122 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 14:23:38.962  1014  1124 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 14:23:38.962  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:38.972  1014  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 14:23:38.972  1014  1119 V NetworkStats: performPollLocked() took 14ms
08-16 14:23:38.972  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:38.972  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:38.972  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:38.972  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:38.972  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:38.972  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:38.972  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:38.982  1014  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-16 14:23:38.982  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:38.982  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:38.982  1014  3286 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:38.982  1014  3286 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:38.982  1014  3286 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:38.982  1014  3286 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:38.982  1014  3286 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:38.982  3614  3614 I Hs20UtilService: Starting #19
,08-16 14:23:38.992  1014  1122 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 14:23:38.992  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:38.992  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 14:23:38.992  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:38.992  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 14:23:39.002   280   966 D CommandListener: Setting iface cfg
,08-16 14:23:39.002  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 14:23:39.002  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 14:23:39.002  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 14:23:39.002  1291  3006 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 14:23:39.012  1014  1122 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 14:23:39.012  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 14:23:39.012  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:39.022  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:39.022  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 14:23:39.022  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.022  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.022  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.022  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.032  1014  1122 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 14:23:39.032  1014  1122 D SecContentProvider2: mCursor = null
,08-16 14:23:39.032  1014  1122 E WifiNative-wlan0: do suspend false
,08-16 14:23:39.032  1014  1121 D WifiP2pService: InactiveState{ what=143375 }
,08-16 14:23:39.032  1014  1121 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 14:23:39.082  6184  6234 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1162)
,08-16 14:23:39.082  6184  6234 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1162)
,08-16 14:23:39.082  6184  6234 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1167)
,08-16 14:23:39.082  6184  6234 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 14:23:39.082  6184  6234 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1168)
,08-16 14:23:39.092  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:39.092  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20f3b069 added. We now have 2 listener(s)
,08-16 14:23:39.092  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 14:23:39.092  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.092  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:39.092  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:39.092  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b84aee added. We now have 9 listener(s)
08-16 14:23:39.092  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:39.092  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:39.092  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:39.102  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:39.102  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:39.102  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:39.102  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.102  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.102  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 14:23:39.102  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c21fe1c added. We now have 3 listener(s)
,08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8dea25 added. We now have 10 listener(s)
,08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.112  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:39.112  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.112  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 14:23:39.112  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20f3b069 removed from the list
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b84aee removed from the list
08-16 14:23:39.112  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:39.112  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.112  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21b84aee not in the list
08-16 14:23:39.112  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b8dea25 removed from the list
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.112  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.112  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c21fe1c removed from the list
,08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.112  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66227fa added. We now have 2 listener(s)
,08-16 14:23:39.112  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-16 14:23:39.122  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.122  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.122  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.122  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55561ab added. We now have 9 listener(s)
,08-16 14:23:39.122  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.122  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:39.122  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:39.122  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:39.122  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 14:23:39.122  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:39.122  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.122  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d803a1 added. We now have 3 listener(s)
,08-16 14:23:39.122  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.132  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.132  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:39.132  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.132  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.132  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.132  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@109ac9c6 added. We now have 10 listener(s)
08-16 14:23:39.132  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.132  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.132  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:39.132  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:39.132  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:39.132  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:23:39.132  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:39.142  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:39.142  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:39.142  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:39.152  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 14:23:39.152  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:23:39.152  6836  6846 D BtGatt.GattService: registerClient() - UUID=10bf0661-5196-44ec-b97e-89cd36516b77
,08-16 14:23:39.202  6836  6854 D BtGatt.GattService: onClientRegistered() - UUID=10bf0661-5196-44ec-b97e-89cd36516b77, clientIf=5
,08-16 14:23:39.202  6184  6193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:23:39.202  6836  6855 D BtGatt.GattService: start scan with filters
,08-16 14:23:39.202  6836  6926 D BtGatt.ScanManager: handling starting scan
08-16 14:23:39.202  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:39.202  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 14:23:39.202  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:39.202  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-16 14:23:39.202  6836  6926 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@77c628d
,08-16 14:23:39.212  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-16 14:23:39.212  6836  6854 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-16 14:23:39.212  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.212  6836  6926 D BtGatt.ScanManager: allow scan with filters,
08-16 14:23:39.212  6836  6926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 14:23:39.212  6836  6926 D BtGatt.ScanManager: set filter index= 3 for clientIf= 5
08-16 14:23:39.212  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:39.212  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:39.212  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 14:23:39.212  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.222  6836  6926 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 14:23:39.222  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 14:23:39.222  6836  6926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:39.222  6836  6854 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 14:23:39.222  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.222  6184  6234 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 14:23:39.222  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.222  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 14:23:39.222  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.222  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:39.222  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 14:23:39.222  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:39.222  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:39.222  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:39.222  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:39.222  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:23:39.222  6836  6972 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:39.232  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:23:39.232  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.232  6836  6846 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:23:39.232  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:23:39.232  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:39.232  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:39.232  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:39.232  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:39.242  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 14:23:39.242  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.242  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.242  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.242  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66227fa removed from the list,
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.242  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55561ab removed from the list
08-16 14:23:39.242  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.242  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:39.242  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:39.242  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:39.242  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.242  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.242  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.252  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@55561ab not in the list
08-16 14:23:39.252  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@109ac9c6 removed from the list,
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.252  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d803a1 removed from the list
08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@969bc52 added. We now have 2 listener(s)
,08-16 14:23:39.252  7009  7009 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.252  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d25b23 added. We now have 9 listener(s)
08-16 14:23:39.252  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.252  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:39.262  7009  7009 I dhcpcd  : version 5.5.6 starting
,08-16 14:23:39.262  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:39.262  7009  7009 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:39.272  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:39.272  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 14:23:39.272  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:39.272  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.272  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291c85d9 added. We now have 3 listener(s)
08-16 14:23:39.272  6836  6926 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,08-16 14:23:39.272  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:39.282  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.282  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:39.282  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.282  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.282  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.282  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10c34b9e added. We now have 10 listener(s)
08-16 14:23:39.282  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.282  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.282  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.282  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:39.282  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:39.282  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:39.282  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:23:39.282  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:39.292  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-16 14:23:39.292  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:39.302  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.sec.android.app.samsungapps 4. Count : 1
,08-16 14:23:39.302  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.sec.spp.push 4. Count : 1
,08-16 14:23:39.302  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.302  1014  1039 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.302  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.302  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 14:23:39.302  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 14:23:39.302  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:23:39.312  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.android.bluetooth 4. Count : 4
,08-16 14:23:39.312  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.samsung.android.app.FileShareServer 4. Count : 11,
,08-16 14:23:39.312  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.312  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.312  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
08-16 14:23:39.312  6836  6899 D BtGatt.GattService: registerClient() - UUID=b0e5a53a-1bcd-4397-8695-9dc71a0b04de
,08-16 14:23:39.312  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.android.settings 4. Count : 2
,08-16 14:23:39.322  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.google.android.gms 4. Count : 12,
08-16 14:23:39.322  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.sec.android.app.launcher 4. Count : 31
,08-16 14:23:39.332  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.332  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.332  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.332  6836  6926 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,08-16 14:23:39.332  7009  7009 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 14:23:39.332  7009  7009 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 14:23:39.332  7009  7009 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 14:23:39.332  7009  7009 I dhcpcd  : bssid match
08-16 14:23:39.332  7009  7009 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-16 14:23:39.332  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.332  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:39.332  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.342  6836  6926 D BtGatt.ScanManager: filter size is 1
08-16 14:23:39.342  6836  6926 D BtGatt.ScanManager: delete FilterIndex - 3
08-16 14:23:39.342  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 14:23:39.342  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.342  6836  6926 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:39.342  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.342  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.342  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.342  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 14:23:39.342  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.342  6836  6926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:23:39.342  6836  6854 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:39.342  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.352  1014  1701 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:39.352  1014  1701 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.352  1014  1701 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.352  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.352  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.352  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,08-16 14:23:39.352  6836  6854 D BtGatt.GattService: onClientRegistered() - UUID=b0e5a53a-1bcd-4397-8695-9dc71a0b04de, clientIf=5
,08-16 14:23:39.352  6184  6193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 14:23:39.352  1014  1307 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:39.352  1014  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.352  1014  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
08-16 14:23:39.362  6836  6855 D BtGatt.GattService: start scan with filters
08-16 14:23:39.362  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:39.362  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 14:23:39.362  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 14:23:39.362  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: handling starting scan
,08-16 14:23:39.362  6836  6854 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 14:23:39.362  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: allow scan with filters
08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: set filter index= 4 for clientIf= 5
,08-16 14:23:39.362  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:39.362  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:39.362  6836  6926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 14:23:39.362  6836  6854 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:23:39.362  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.362  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:39.362  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 14:23:39.362  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 14:23:39.372  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 14:23:39.372  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.372  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.372  6184  6234 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 14:23:39.372  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:39.372  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.372  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.372  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.372  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@969bc52 removed from the list
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.372  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d25b23 removed from the list
08-16 14:23:39.372  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:39.372  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 14:23:39.372  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.372  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d25b23 not in the list
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:39.372  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:39.372  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:23:39.382  6836  6899 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:39.382  6836  6855 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-16 14:23:39.382  7009  7009 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 14:23:39.382  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 14:23:39.382  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:39.382  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.382  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10c34b9e removed from the list
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.382  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.382  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.382  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.382  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291c85d9 removed from the list
,08-16 14:23:39.382  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.382  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9483aa added. We now have 2 listener(s)
,08-16 14:23:39.392  6836  6926 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1,
08-16 14:23:39.392  6836  6926 D BtGatt.ScanManager: filter size is 1
08-16 14:23:39.392  6836  6926 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 14:23:39.392  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 14:23:39.392  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.392  6836  6926 D BtGatt.ScanManager: stopping BLe Batch
,08-16 14:23:39.392  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-16 14:23:39.392  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.392  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-16 14:23:39.392  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 14:23:39.392  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d60b9b added. We now have 9 listener(s)
08-16 14:23:39.392  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.392  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:39.392  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:39.392  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.392  6836  6926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:23:39.392  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:39.402  6836  6854 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 14:23:39.402  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 14:23:39.402  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:39.402  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 14:23:39.402  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 14:23:39.402  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.402  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b81711 added. We now have 3 listener(s)
,08-16 14:23:39.402  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.402  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.402  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:39.402  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.402  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.402  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.402  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f3076 added. We now have 10 listener(s)
08-16 14:23:39.402  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.402  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.402  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 14:23:39.402  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 14:23:39.402  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 14:23:39.402  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 14:23:39.412  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 14:23:39.412  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 14:23:39.412  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 14:23:39.422  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 14:23:39.422  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 14:23:39.422  6184  6234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 14:23:39.422  6836  6972 D BtGatt.GattService: registerClient() - UUID=880f637e-d029-4327-bcac-eaf6b95c7cc4
,08-16 14:23:39.432  7009  7009 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-16 14:23:39.462  6836  6854 D BtGatt.GattService: onClientRegistered() - UUID=880f637e-d029-4327-bcac-eaf6b95c7cc4, clientIf=5
,08-16 14:23:39.462  6184  6193 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 14:23:39.462  6836  6846 D BtGatt.GattService: start scan with filters
08-16 14:23:39.462  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 14:23:39.462  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 14:23:39.462  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 14:23:39.462  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 14:23:39.462  6836  6926 D BtGatt.ScanManager: handling starting scan
,08-16 14:23:39.472  6836  6854 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-16 14:23:39.472  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.472  6836  6926 D BtGatt.ScanManager: allow scan with filters
,08-16 14:23:39.472  6836  6926 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 14:23:39.472  6836  6926 D BtGatt.ScanManager: set filter index= 5 for clientIf= 5
,08-16 14:23:39.472  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-16 14:23:39.472  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 14:23:39.472  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.472  6836  6926 D BtGatt.ScanManager: Starting BLE batch scan
08-16 14:23:39.472  6836  6926 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
08-16 14:23:39.472  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 14:23:39.472  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 14:23:39.472  6836  6854 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 14:23:39.472  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.482  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 14:23:39.482  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.482  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-16 14:23:39.492  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-16 14:23:39.492  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.492  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.492  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.492  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f9483aa removed from the list
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.492  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d60b9b removed from the list
08-16 14:23:39.492  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:39.492  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-16 14:23:39.492  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.492  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11d60b9b not in the list
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 14:23:39.492  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 14:23:39.492  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 14:23:39.502  6836  6899 D BtGatt.GattService: stopScan() - queue size =1
,08-16 14:23:39.502  6836  6926 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 2,
08-16 14:23:39.502  6836  6926 D BtGatt.ScanManager: filter size is 1
08-16 14:23:39.502  6836  6926 D BtGatt.ScanManager: delete FilterIndex - 5
08-16 14:23:39.502  6836  6848 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 14:23:39.502  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 14:23:39.502  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 14:23:39.502  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 14:23:39.502  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 14:23:39.502  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 14:23:39.502  6836  6854 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-16 14:23:39.502  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.502  6836  6926 D BtGatt.ScanManager: stopping BLe Batch
08-16 14:23:39.502  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 14:23:39.512  6836  6854 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 14:23:39.512  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.512  6836  6926 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.512  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:39.512  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e8f3076 removed from the list
08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.512  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.512  6184  6184 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 14:23:39.512  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.512  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35b81711 removed from the list
08-16 14:23:39.512  6184  6184 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 14:23:39.512  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.512  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3db5de02 added. We now have 2 listener(s)
,08-16 14:23:39.512  6836  6854 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 14:23:39.512  6836  6854 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 14:23:39.512  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 14:23:39.512  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 14:23:39.522  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27a05313 added. We now have 9 listener(s)
08-16 14:23:39.522  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 14:23:39.522  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 14:23:39.522  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false,
08-16 14:23:39.532  6184  6234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 14:23:39.532  6184  6234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-16 14:23:39.532  6184  6234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 14:23:39.532  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 14:23:39.532  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9d9749 added. We now have 3 listener(s)
,08-16 14:23:39.532  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a7d84e added. We now have 10 listener(s)
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 14:23:39.542  6184  6234 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.542  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3db5de02 removed from the list
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27a05313 removed from the list
,08-16 14:23:39.542  6184  6184 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 14:23:39.542  6184  6234 D io.jxcore.node.ConnectivityMonitor: stop
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.542  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.542  6184  6234 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27a05313 not in the list
08-16 14:23:39.542  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a7d84e removed from the list
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 14:23:39.542  6184  6234 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 14:23:39.542  6184  6234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 14:23:39.542  6184  6234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 14:23:39.542  6184  6234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e9d9749 removed from the list
,08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 14:23:39.542  6184  6234 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 14:23:39.552  6184  7032 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1175, name: My test thread name)
08-16 14:23:39.552  6184  7032 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1175, thread name: My test thread name)
08-16 14:23:39.552  6184  7032 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1175, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 14:23:39.552  6184  7033 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1177, name: My test thread name)
,08-16 14:23:39.552  6184  7033 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1177, thread name: My test thread name)
08-16 14:23:39.552  6184  7033 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1177, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 14:23:39.552  6184  6234 E com.test.thalitest.ThaliTestRunner: DiscoveryManager1 isRunning should return true,
08-16 14:23:39.552  6184  6234 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
08-16 14:23:39.552  6184  6234 E com.test.thalitest.ThaliTestRunner:      but: was <false>
08-16 14:23:39.552  6184  6234 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 14:23:39.552  6184  6234 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 79
,08-16 14:23:39.552  6184  6234 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  1
08-16 14:23:39.552  6184  6234 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 14:23:39.552  6184  6234 D com.test.thalitest.ThaliTestRunner: Total duration: 23905 ms
08-16 14:23:39.562  6184  6234 I jxcore-log: Total number of executed tests:  80
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: Number of passed tests:  79
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: Number of failed tests:  1
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: Number of ignored tests:  0
08-16 14:23:39.562  6184  6234 I jxcore-log: 
,08-16 14:23:39.562  6184  6234 I jxcore-log: Total duration:  23905
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: Failed to execute UT.
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 14:23:39.562  6184  6234 I jxcore-log: 
,08-16 14:23:39.562  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.562  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:39.562  6184  6234 I jxcore-log: 
08-16 14:23:39.572  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:39.572  6184  6234 I jxcore-log: 
08-16 14:23:39.572  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:39.572  6184  6234 I jxcore-log: 
08-16 14:23:39.572  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 14:23:39.572  6184  6234 I jxcore-log: 
08-16 14:23:39.572  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:39.572  6184  6234 I jxcore-log: 
08-16 14:23:39.572  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.572  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6184 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
,08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.582  6184  6234 I jxcore-log: 
08-16 14:23:39.582   293   293 E SMD     : DCD OFF
,08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.592  6184  6234 I jxcore-log: 
,08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 14:23:39.592  6184  6234 I jxcore-log: 
,08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
08-16 14:23:39.592  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 14:23:39.592  6184  6234 I jxcore-log: 
,08-16 14:23:39.642  1014  1122 E WifiNative-wlan0: do suspend true,
,08-16 14:23:39.672  1014  1121 D WifiP2pService: InactiveState{ what=143375 },
08-16 14:23:39.672  1014  1121 D WifiP2pService: P2pEnabledState{ what=143375 },
08-16 14:23:39.672  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:39.672  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:39.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 14:23:39.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.672  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.672  1014  1122 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 14:23:39.672  1014  1122 E WifiStateMachine: VerifyingLinkState enter
,08-16 14:23:39.682  1014  1122 D WifiNative-wlan0: callSECApiInt - ID [210],
08-16 14:23:39.682  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:39.682  1014  1124 D ConnectivityService: Adding iface wlan0 to network 503
08-16 14:23:39.682  1014  1124 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-16 14:23:39.682  1014  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-16 14:23:39.682  1014  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 14:23:39.682  1014  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 14:23:39.682  1014  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 14:23:39.682  1014  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 14:23:39.692  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:39.692  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:39.692  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.692  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.692  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.692  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.702  1014  3244 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:39.702  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:39.702  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.702  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.702  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:39.702  1014  1122 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-16 14:23:39.702  3614  3614 I Hs20UtilService: Starting #20
08-16 14:23:39.702  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:39.702  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 14:23:39.702  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 14:23:39.712  1014  1122 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 14:23:39.712  1014  1122 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 14:23:39.712  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 14:23:39.722  1014  1124 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503,
,08-16 14:23:39.722  1014  1124 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,08-16 14:23:39.722  1014  1124 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
08-16 14:23:39.722  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:39.722  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 14:23:39.722  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.722  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.722  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.722  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.722  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-16 14:23:39.722  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
08-16 14:23:39.722  1014  1124 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 14:23:39.722  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
08-16 14:23:39.722  1014  1124 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-16 14:23:39.722  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-16 14:23:39.722  1014  1124 D ConnectivityService: LTETest block dns file not exists
,08-16 14:23:39.732  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:39.732  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 14:23:39.732  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.732  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:39.732  1014  1124 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.732  1014  1124 E ConnectivityService: updateNetworkInfo()
08-16 14:23:39.732  1014  1124 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 14:23:39.732  1014  1124 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.732  1014  1124 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,08-16 14:23:39.732  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:39.732  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 14:23:39.732  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 14:23:39.732  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-16 14:23:39.742  1014  7005 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 14:23:39.742   280   962 D EnterpriseController: uids 1000
08-16 14:23:39.742   280   962 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 14:23:39.742   280   962 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,08-16 14:23:39.742  1014  1124 D ConnectivityService:    accepting network in place of null
,08-16 14:23:39.742  1014  1121 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 14:23:39.742  1014  1122 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 14:23:39.742  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 14:23:39.742  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 14:23:39.742  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.742  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.742  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.742  6184  6184 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 14:23:39.752  1014  1124 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 14:23:39.752  1014  1124 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-16 14:23:39.752  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:39.752  6184  6234 I jxcore-log: 
08-16 14:23:39.752  1014  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 14:23:39.752  1014  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 14:23:39.752  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 14:23:39.752  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:39.752  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.752  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 14:23:39.752  3614  3614 I Hs20UtilService: Starting #21
,08-16 14:23:39.752  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:39.762  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 14:23:39.762  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 14:23:39.762  1014  1124 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-16 14:23:39.762  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 14:23:39.762  1014  1127 D Tethering: MasterInitialState.processMessage what=3
08-16 14:23:39.762  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.762  1014  1119 V NetworkStats: updateIfacesLocked()
08-16 14:23:39.762  1014  1119 V NetworkStats: performPollLocked(flags=0x1)
08-16 14:23:39.762  1014  1124 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.762  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 14:23:39.762  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:39.762  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:39.762  1178  1691 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 14:23:39.762  3815  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 14:23:39.762  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-16 14:23:39.762  1014  1119 V NetworkStats: performPollLocked() took 6ms
08-16 14:23:39.762  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1014  1120 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 14:23:39.762  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 14:23:39.772  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 14:23:39.772  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-16 14:23:39.772  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 14:23:39.772  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 14:23:39.772  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 14:23:39.772  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:39.772  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 14:23:39.772  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.772  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.782  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 14:23:39.782  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 14:23:39.782  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:39.782  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:39.782  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 14:23:39.782  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 14:23:39.782  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 14:23:39.792  3614  3614 I Hs20UtilService: Starting #22
,08-16 14:23:39.792  3614  3648 I Hs20UtilService: Message received 5007
,08-16 14:23:39.792  1014  1216 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-16 14:23:39.792  1014  1701 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 14:23:39.792  1014  1701 D SecContentProvider2: mCursor = null
,08-16 14:23:39.792  1014  1345 D SecContentProvider2: uri = 15 selection = getToastGravity
08-16 14:23:39.792  1014  1345 D SecContentProvider2: mCursor = null
,08-16 14:23:39.792  1014  1492 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 14:23:39.792  1014  1492 D SecContentProvider2: mCursor = null
,08-16 14:23:39.802  1014  3002 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-16 14:23:39.802  1014  3002 D SecContentProvider2: mCursor = null
,08-16 14:23:39.802  1014  1486 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 14:23:39.802  1014  1486 D SecContentProvider2: mCursor = null
,08-16 14:23:39.802  1014  3290 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-16 14:23:39.802  1014  3290 D SecContentProvider2: mCursor = null
,08-16 14:23:39.822   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-16 14:23:39.842  1014  1027 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-16 14:23:39.852  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 14:23:39.852  7042  7042 D AndroidRuntime: 
08-16 14:23:39.852  7042  7042 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 14:23:39.852  7042  7042 D AndroidRuntime: CheckJNI is OFF
,08-16 14:23:39.852  7042  7042 D AndroidRuntime: readGMSProperty: start
08-16 14:23:39.852  7042  7042 D AndroidRuntime: readGMSProperty: already setted!!
08-16 14:23:39.852  7042  7042 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 14:23:39.852  7042  7042 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 14:23:39.852  7042  7042 D AndroidRuntime: readGMSProperty: end
08-16 14:23:39.852  7042  7042 D AndroidRuntime: addProductProperty: start
,08-16 14:23:39.882  1014  7005 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 14:23:39.882  6184  6184 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-16 14:23:39.882  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 14:23:39.882  6184  6234 I jxcore-log: 
,08-16 14:23:39.952  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 12:23:39 GMT], X-Android-Received-Millis=[1471350219964], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471350219930]}
08-16 14:23:39.952  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 14:23:39.952  1014  7005 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-16 14:23:39.952  1014  1124 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.952  1014  1124 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.952  1014  1124 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-16 14:23:39.952  1014  1124 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
08-16 14:23:39.952  1014  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 14:23:39.952  1178  1691 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:23:39.952  3815  6245 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 14:23:39.962  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 14:23:39.962  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:39.962  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 14:23:40.012  6184  6184 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-16 14:23:40.012  7042  7042 E AffinityControl: AffinityControl: registerfunction enter
08-16 14:23:40.012  6184  6234 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,08-16 14:23:40.012  6184  6234 I jxcore-log: 
,08-16 14:23:40.032  7042  7042 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-16 14:23:40.052  1014  3292 D PackageManager: START PACKAGE DELETE: observer{901082960},
08-16 14:23:40.052  1014  3292 D PackageManager: pkg{<packageName>}
08-16 14:23:40.052  1014  3292 D PackageManager: user{0}
08-16 14:23:40.052  1014  3292 D PackageManager: caller{2000}
08-16 14:23:40.052  1014  3292 D PackageManager: flags{2}
,08-16 14:23:40.052  1014  3292 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-16 14:23:40.052  1014  3292 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 14:23:40.052  1014  3292 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 14:23:40.052  1014  3292 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-16 14:23:40.052  1014  3292 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 14:23:40.052  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 14:23:40.052  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 14:23:40.052  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 14:23:40.052  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 14:23:40.052  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 14:23:40.052  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg,
,08-16 14:23:40.062  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-16 14:23:40.062  1014  1039 I ActivityManager: Killing 6184:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
08-16 14:23:40.062  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{3ddde6a5 u0 com.test.thalitest/.MainActivity t128}
,08-16 14:23:40.072  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,08-16 14:23:40.192  1014  1345 I WindowState: WIN DEATH: Window{2fa79b85 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 14:23:40.192   257  1160 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-16 14:23:40.192   257  1160 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-16 14:23:40.202  1014  1345 D InputDispatcher: Focus left window: 6184
,08-16 14:23:40.202   257   447 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-16 14:23:40.222  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 14:23:40.222  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 14:23:40.222  1014  1039 D InputDispatcher: Focused application released
,08-16 14:23:40.222  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-16 14:23:40.242  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 14:23:40.252  5610  5610 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 706us total 22.698ms
,08-16 14:23:40.262  1014  1124 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 14:23:40.272  5402  5402 I art     : Explicit concurrent mark sweep GC freed 403(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 744us total 33.205ms
,08-16 14:23:40.272  1014  1095 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 14:23:40.282  1790  1790 E SamsungIME: mOCRHelper is null
,08-16 14:23:40.292  1924  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 14:23:40.312  3649  3649 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 14:23:40 GMT+02:00 2016
,08-16 14:23:40.332  3815  3815 I art     : Explicit concurrent mark sweep GC freed 23055(1391KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 16MB/26MB, paused 1.500ms total 101.463ms
,08-16 14:23:40.342  3039  3039 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-16 14:23:40.342  3815  3825 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-16 14:23:40.352  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 14:23:40.352  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 14:23:40.352  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 14:23:40.352  1014  1038 W TextServicesManagerService: no available spell checker services found
,08-16 14:23:40.362  6569  6569 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 14:23:40.362  1014  1492 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 14:23:40.362  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 14:23:40.362  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:40.362  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:40.362  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 14:23:40.372  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0,
08-16 14:23:40.372  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:40.372  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.372  1443  1443 D RegisteredServicesCache: empty dynamic service
,08-16 14:23:40.372  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 14:23:40.382  3039  3039 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3,
,08-16 14:23:40.382  3649  3649 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 14:23:40.382  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-16 14:23:40.402  1014  1119 V NetworkStats: removeUidsLocked() for UIDs [10155]
,08-16 14:23:40.402  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:40.402  1014  1119 V NetworkStats: performPollLocked(flags=0x3)
,08-16 14:23:40.402  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.402  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 14:23:40.402  1014  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 14:23:40.402  3649  3649 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 14:23:40.402  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.412  3649  3649 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 14:23:40.412  1014  1026 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-16 14:23:40.412  1014  1026 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 14:23:40.412  3649  3649 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-16 14:23:40.422  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 14:23:40.422  1014  1119 V NetworkStats: performPollLocked() took 25ms
08-16 14:23:40.422  1014  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 14:23:40.422  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 14:23:40.422  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.422  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.422  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.422  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.422  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 14:23:40.432  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-16 14:23:40.432  1014  1132 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 14:23:40.432  1014  1132 D SecContentProvider2: mCursor = null
,08-16 14:23:40.442  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest,
08-16 14:23:40.442  7060  7060 E Zygote  : MountEmulatedStorage()
08-16 14:23:40.442  7060  7060 I libpersona: KNOX_SDCARD checking this for 10094
08-16 14:23:40.442  7060  7060 E Zygote  : v2
08-16 14:23:40.442  7060  7060 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:40.442  7060  7060 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:40.442  7060  7060 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:40.442  1014  1026 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7060 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-16 14:23:40.452  7060  7060 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:40.452  1014  1014 I art     : Explicit concurrent mark sweep GC freed 67750(4MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/42MB, paused 6.709ms total 211.510ms
,08-16 14:23:40.452  1014  1054 I art     : WaitForGcToComplete blocked for 77.238ms for cause Explicit
,08-16 14:23:40.462  3039  3039 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-16 14:23:40.472  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-16 14:23:40.472  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.472  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.472  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.472  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.472  7060  7060 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.482  7060  7060 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:40.482  3039  3039 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-16 14:23:40.492  7075  7075 E Zygote  : MountEmulatedStorage(),
08-16 14:23:40.492  7075  7075 E Zygote  : v2
,08-16 14:23:40.492  7075  7075 I libpersona: KNOX_SDCARD checking this for 10044
08-16 14:23:40.492  7075  7075 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:40.492  7075  7075 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:40.492  7075  7075 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 14:23:40.492  7075  7075 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:40.502  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7075 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 14:23:40.502  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast,
,08-16 14:23:40.512  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.512  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.512  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.512  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.522  7075  7075 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.522   311   311 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.031ms total 25.455ms
,08-16 14:23:40.532  7075  7075 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:40.542  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 14:23:40.542   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 24.274ms
,08-16 14:23:40.552  5707  7090 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-16 14:23:40.562  3649  7059 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 14:23:40.562  3649  7059 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 14:23:40.562   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 17.053ms
,08-16 14:23:40.572  7091  7091 E Zygote  : MountEmulatedStorage(),
08-16 14:23:40.572  7091  7091 E Zygote  : v2,
08-16 14:23:40.572  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7091 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 14:23:40.572  7091  7091 I libpersona: KNOX_SDCARD checking this for 10149
,08-16 14:23:40.572  7091  7091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:40.572  7091  7091 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:40.582  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:40.582  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 14:23:40.582  7091  7091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:40.582  7091  7091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:40.582  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 14:23:40.592  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:40.592  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 14:23:40.612  1014  3287 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
08-16 14:23:40.612  1014  3287 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-16 14:23:40.622  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 14:23:40.632  7075  7075 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 14:23:40.642  7091  7091 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.642  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-16 14:23:40.652  7091  7091 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:40.652  3649  3649 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 14:23:40.652  3039  3039 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 14:23:40.652  3039  3039 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-16 14:23:40.652  3039  3039 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-16 14:23:40.652  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-16 14:23:40.652  3039  3039 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-16 14:23:40.652  7060  7060 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 14:23:40.652  1014  1486 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 14:23:40.652  1014  1486 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 14:23:40.652  1014  1486 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 14:23:40.662  3039  3039 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-16 14:23:40.662   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-16 14:23:40.662  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 14:23:40.672  7060  7060 D elm:15183: ELMEngine.ELMEngine( context ).
,08-16 14:23:40.672  1014  1027 D InputDispatcher: Focus entered window: 3039
,08-16 14:23:40.682  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 14:23:40.682  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 14:23:40.682  7060  7060 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-16 14:23:40.682  1014  3002 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 14:23:40.682  1014  3002 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 14:23:40.682  5707  7090 I art     : Explicit concurrent mark sweep GC freed 710(50KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 1.459ms total 118.567ms
,08-16 14:23:40.682  3039  3039 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 14:23:40.682  1014  3002 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:40.682  1014  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:40.682  1014  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 14:23:40.692  3039  3039 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-16 14:23:40.692  3039  3039 V ActivityThread: updateVisibility : ActivityRecord{3f49d301 token=android.os.BinderProxy@170d0fac {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-16 14:23:40.692  1014  3292 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 14:23:40.692  7060  7060 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 14:23:40.702  1014  7107 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 14:23:40.702  1014  3292 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6184 uid 10155
,08-16 14:23:40.722  1014  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.sm, calleePkgName: com.sec.android.provider.badge
,08-16 14:23:40.722  3039  3039 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@170d0fac time:149875
,08-16 14:23:40.732  1790  1790 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-16 14:23:40.732  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.732  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.732  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.732  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.742  7060  7060 D elm:15183: ElmAgentService : onCreate()
,08-16 14:23:40.742  7060  7108 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-16 14:23:40.742  7060  7108 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-16 14:23:40.742  7060  7108 D elm:15183: MDMBridge.getInstance()
08-16 14:23:40.742  7060  7108 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 14:23:40.742  7110  7110 E Zygote  : MountEmulatedStorage()
08-16 14:23:40.742  7110  7110 I libpersona: KNOX_SDCARD checking this for 10072
08-16 14:23:40.742  7110  7110 E Zygote  : v2
08-16 14:23:40.742  7110  7110 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:40.742  7110  7110 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:40.752  7110  7110 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:40.752  7110  7110 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-16 14:23:40.752  1014  1054 W art     : Suspending all threads took: 9.970ms
,08-16 14:23:40.762  1014  1027 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7110 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,08-16 14:23:40.772  7110  7110 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.772  7091  7091 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 14:23:40.772  7091  7091 D ThemeInfoUtil: isCurrentFestival = false
,08-16 14:23:40.772  7060  7108 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 14:23:40.782  7110  7110 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:40.782  3181  3181 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-16 14:23:40.782  1014  1124 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 14:23:40.782  3181  3181 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-16 14:23:40.782  3181  3181 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-16 14:23:40.782  3181  3181 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:40.782  3181  3181 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 14:23:40.782  3181  3181 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:40.782  3181  3181 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:40.782  3181  3181 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:40.782  3181  3181 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 14:23:40.792  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.792  1014  1044 W ActivityManager: mDVFSHelper.release()
08-16 14:23:40.792  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39a7ca07 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149946
,08-16 14:23:40.802  1014  1054 I art     : Explicit concurrent mark sweep GC freed 17869(2038KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 20.906ms total 343.973ms
,08-16 14:23:40.802  1014  3002 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-16 14:23:40.802  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.802  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.802  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.802  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.812  7127  7127 E Zygote  : MountEmulatedStorage(),
08-16 14:23:40.812  7127  7127 I libpersona: KNOX_SDCARD checking this for 1000
,08-16 14:23:40.812  7127  7127 E Zygote  : v2
,08-16 14:23:40.812  7127  7127 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:40.812  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:40.822  1014  3002 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7127 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 14:23:40.822  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:40.822  1014  1054 D PackageManager: delete codoeFile: 
08-16 14:23:40.822  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:40.832  1014  3002 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-16 14:23:40.832  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.832  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.832  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:40.832  1014  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:40.832  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,08-16 14:23:40.842  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-16 14:23:40.842  1014  1054 D PackageManager: result of delete: 1{901082960}
,08-16 14:23:40.842  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.842  7127  7127 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:40.852  7110  7110 D BadgeProvider: onCreate
,08-16 14:23:40.852  7110  7110 D BadgeProvider: DatabaseHelper
,08-16 14:23:40.852  7042  7042 D AndroidRuntime: Shutting down VM
08-16 14:23:40.852  1014  1014 D RCPManagerService: PackageReceiver onReceive()
08-16 14:23:40.852  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
08-16 14:23:40.852  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.862  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 14:23:40.862  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-16 14:23:40.862  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-16 14:23:40.862  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-16 14:23:40.862  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0,
08-16 14:23:40.872  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
08-16 14:23:40.872  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 14:23:40.872  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 14:23:40.872  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 14:23:40.872  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 14:23:40.872  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 14:23:40.872  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 14:23:40.872  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:40.872  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:40.872  1014  3002 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7143 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
08-16 14:23:40.872  7143  7143 E Zygote  : MountEmulatedStorage()
08-16 14:23:40.872  7143  7143 I libpersona: KNOX_SDCARD checking this for 10152
08-16 14:23:40.872  7143  7143 E Zygote  : v2
08-16 14:23:40.872  7143  7143 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:40.882  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.882  7143  7143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:40.882  1014  3002 I ActivityManager: Killing 6068:com.samsung.helphub/1000 (adj 15): empty #31
,08-16 14:23:40.882  7143  7143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:40.882  7143  7143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:40.892  7060  7060 D elm:15183: ElmAgentService : onDestroy().
,08-16 14:23:40.892  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 14:23:40.892  1014  2718 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 14:23:40.892  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
,08-16 14:23:40.902  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 14:23:40.902  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-16 14:23:40.902  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 14:23:40.902  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-16 14:23:40.912  1178  1178 D PanelView: There is/are notification(s) 
,08-16 14:23:40.912  7110  7119 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-16 14:23:40.912  7110  7119 D BadgeProvider: sendNotify, [notify] : null
08-16 14:23:40.912  7110  7119 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-16 14:23:40.912  7110  7119 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 14:23:40.912  7110  7119 D BadgeProvider: update, [UpdateCount] : 1
08-16 14:23:40.912  1014  1492 I ActivityManager: Killing 5402:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-16 14:23:40.912  1014  1307 I ActivityManager: Killing 6122:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-16 14:23:40.922  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.932  7143  7143 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:40.932  7143  7143 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:40.942  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-16 14:23:40.942  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-16 14:23:40.952  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.952  1014  1132 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:40.962  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.962  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 14:23:40.962  7075  7075 D NearbySource: Nearby Source Create!
,08-16 14:23:40.962  7075  7075 D NearbyContext: Nearby Context Create!
,08-16 14:23:40.972  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.972  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:23:40.972  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 14:23:40.982  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 14:23:40.982  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 14:23:40.982  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 14:23:40.982  7127  7127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-16 14:23:40.992  1014  3290 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-16 14:23:40.992  1014  3290 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-16 14:23:40.992  1014  3290 W ActivityManager: userId = 0, bbcId = -10000
,08-16 14:23:40.992  1014  3290 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 14:23:40.992  1014  3290 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-16 14:23:40.992  6552  6552 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 14:23:40.992  6552  6552 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 14:23:40.992  6552  6552 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 14:23:40.992  6552  6552 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-16 14:23:40.992  1178  1178 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-16 14:23:41.002  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
08-16 14:23:41.002  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:41.002  1178  1178 D PanelView: There is/are notification(s) 
08-16 14:23:41.002  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 14:23:41.002  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,08-16 14:23:41.002  1178  1178 D PanelView: There is/are notification(s) 
08-16 14:23:41.002  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 14:23:41.002  1014  1345 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-16 14:23:41.002  1014  1345 D SecContentProvider2: mCursor = null
,08-16 14:23:41.002  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-16 14:23:41.002  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-16 14:23:41.002  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-16 14:23:41.012  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 14:23:41.012  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.012  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.012  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.012  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.012  7143  7143 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-16 14:23:41.022  7159  7159 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.022  7159  7159 E Zygote  : v2
08-16 14:23:41.022  7159  7159 I libpersona: KNOX_SDCARD checking this for 10032
08-16 14:23:41.022  7159  7159 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:41.022  7159  7159 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:41.022  7159  7159 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:41.022  1014  1026 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7159 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-16 14:23:41.032  7159  7159 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:41.032  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-16 14:23:41.032  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.032  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.032  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.032  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:41.042   256   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-16 14:23:41.042   256   526 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 14:23:41.042  7075  7075 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-16 14:23:41.042  7075  7075 D SLinkSource: Samsung link source created
08-16 14:23:41.042  7167  7167 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.042  7167  7167 E Zygote  : v2
08-16 14:23:41.042  7167  7167 I libpersona: KNOX_SDCARD checking this for 1000
08-16 14:23:41.042  7167  7167 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:41.052  7167  7167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:41.052  7167  7167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:41.052  1014  1486 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7167 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 14:23:41.052  7167  7167 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 14:23:41.052  1014  3288 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-16 14:23:41.052  1014  3288 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-16 14:23:41.052  1014  3288 W ActivityManager: userId = 0, bbcId = -10000
08-16 14:23:41.052  1014  3288 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 14:23:41.052  1014  3288 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-16 14:23:41.062  1014  1486 I ActivityManager: Killing 5658:com.android.defcontainer/u0a4 (adj 15): empty #31
,08-16 14:23:41.062  1014  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-16 14:23:41.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.072  1014  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:41.072  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-16 14:23:41.072  7042  7042 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
08-16 14:23:41.082  7159  7159 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:41.082  7159  7159 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:41.082  7167  7167 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:41.092  7167  7167 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:41.092  7190  7190 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.092  7190  7190 I libpersona: KNOX_SDCARD checking this for 10156
08-16 14:23:41.092  7190  7190 E Zygote  : v2
08-16 14:23:41.092  7190  7190 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:41.092  7190  7190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:41.092  7190  7190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:41.092  1014  1486 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7190 uid=10156 gids={50156, 9997} abi=armeabi-v7a
08-16 14:23:41.092  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 14:23:41.092  1014  1054 D PackageManager: userId{-1}
08-16 14:23:41.092  1014  1054 D PackageManager: andCode{true}
,08-16 14:23:41.092  7190  7190 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 14:23:41.112  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 14:23:41.112  1014  1054 W ActivityManager: Application dead when creating service ServiceRecord{ca5bf6 u0 com.android.defcontainer/.DefaultContainerService}
,08-16 14:23:41.122  1014  1054 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 1000ms
,08-16 14:23:41.122  7190  7190 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:41.122  7190  7190 D ActivityThread: Added TimaKeyStore provider
,08-16 14:23:41.122  1014  1054 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 4000ms
,08-16 14:23:41.122  7167  7167 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 14:23:41.122  1014  3292 W ActivityManager: Spurious death for ProcessRecord{14724bf7 0:com.android.defcontainer/u0a4}, curProc for 5658: null
,08-16 14:23:41.122  1014  3290 I ActivityManager: Killing 5532:com.android.vending/u0a28 (adj 15): empty #31
,08-16 14:23:41.152  7190  7190 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-16 14:23:41.152  7190  7190 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-16 14:23:41.162  1014  1345 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 14:23:41.162  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.162  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.162  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.162  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:41.172  7190  7190 I TapandpayWidget:Utils: Clear T&P info.
,08-16 14:23:41.172  7167  7167 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-16 14:23:41.172  7159  7207 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-16 14:23:41.172  5846  5846 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
08-16 14:23:41.172  1014  1216 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 14:23:41.172  5846  5846 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
,08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 14:23:41.172  5846  5846 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 14:23:41.172  5846  5846 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,08-16 14:23:41.182  1014  3244 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0,
08-16 14:23:41.182  1014  3244 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-16 14:23:41.182  7190  7190 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-16 14:23:41.182  7210  7210 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.182  7210  7210 I libpersona: KNOX_SDCARD checking this for 10035
08-16 14:23:41.182  7210  7210 E Zygote  : v2
08-16 14:23:41.182  7210  7210 I libpersona: KNOX_SDCARD not a persona
,08-16 14:23:41.182  7210  7210 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:41.192  7210  7210 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:41.192  7210  7210 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 14:23:41.192  7159  7207 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-16 14:23:41.192  1014  1345 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7210 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:41.202  1014  1345 I ActivityManager: Killing 6259:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,08-16 14:23:41.202  1014  1345 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-16 14:23:41.202  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.202  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.202  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.202  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:41.202  7159  7207 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 14:23:41.222  5707  5707 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-16 14:23:41.222  7210  7210 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 14:23:41.222  7210  7210 D ActivityThread: Added TimaKeyStore provider
08-16 14:23:41.222  7226  7226 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.222  7226  7226 E Zygote  : v2,
08-16 14:23:41.222  7226  7226 I libpersona: KNOX_SDCARD checking this for 10091
,08-16 14:23:41.222  7226  7226 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:41.232  7226  7226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 14:23:41.232  1014  1345 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7226 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 14:23:41.232  1014  1345 I ActivityManager: Killing 6600:com.android.chrome/u0a81 (adj 15): empty #31,
08-16 14:23:41.232  1014  1345 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,08-16 14:23:41.232  7226  7226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 14:23:41.232  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.232  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 14:23:41.232  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 14:23:41.232  7226  7226 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 14:23:41.232  1014  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 14:23:41.232  7159  7207 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 14:23:41.232  7159  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:41.232  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 14:23:41.242  7159  7207 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 14:23:41.242  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:41.242  7159  7207 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 14:23:41.252  7239  7239 E Zygote  : MountEmulatedStorage()
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 14:23:41.252  7239  7239 E Zygote  : v2
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 14:23:41.252  7239  7239 I libpersona: KNOX_SDCARD checking this for 10160
08-16 14:23:41.252  7239  7239 I libpersona: KNOX_SDCARD not a persona
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 14:23:41.252  7239  7239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 14:23:41.252  7159  7207 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 14:23:41.262  7239  7239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 14:23:41.262  1014  1345 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7239 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
08-16 14:23:41.262  7239  7239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 14:23:41.262  1014  1345 I ActivityManager: Killing 6580:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,08-16 14:23:41.272  7110  7118 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 14:23:41.272  7110  7118 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
08-16 14:23:41.272  7159  7207 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 14:23:41.272  7159  7207 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 14:23:41.272  7159  7207 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 14:23:41.272  7110  7118 E DatabaseUtils: Writing exception to parcel
08-16 14:23:41.272  7110  7118 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-16 14:23:41.272  7110  7118 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 14:23:41.272  7226  7226 D TimaKeyStoreProvider: TimaSignature is unavailable

```
