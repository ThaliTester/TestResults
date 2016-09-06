#### Test 828946820542738_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
,09-06 19:09:23.731  1014  1319 E Watchdog: !@Sync 3
--------- beginning of main
09-06 19:09:24.001  6153  6153 D AndroidRuntime: 
09-06 19:09:24.001  6153  6153 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 19:09:24.001  6153  6153 D AndroidRuntime: CheckJNI is OFF
09-06 19:09:24.001  6153  6153 D AndroidRuntime: readGMSProperty: start
09-06 19:09:24.001  6153  6153 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:09:24.001  6153  6153 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:09:24.001  6153  6153 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:09:24.001  6153  6153 D AndroidRuntime: readGMSProperty: end
09-06 19:09:24.001  6153  6153 D AndroidRuntime: addProductProperty: start
09-06 19:09:24.131  6153  6153 E AffinityControl: AffinityControl: registerfunction enter
09-06 19:09:24.161  6153  6153 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 19:09:24.171  1014  1471 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:24.171  1014  1471 I PersonaManagerService: PersonaId don't exist
09-06 19:09:24.171  1014  1471 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 19:09:24.171  1014  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:24.181  1014  1471 W ActivityManager: mDVFSHelper.acquire()
09-06 19:09:24.191  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:09:24.191  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 19:09:24.201  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.201  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.201  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.201  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:24.211  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:24.211  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:09:24.211   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-06 19:09:24.211  6164  6164 E Zygote  : MountEmulatedStorage()
09-06 19:09:24.211  6164  6164 I libpersona: KNOX_SDCARD checking this for 10155
09-06 19:09:24.211  6164  6164 E Zygote  : v2
09-06 19:09:24.211  6164  6164 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:24.211  1014  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-06 19:09:24.211  1014  1471 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6164 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:09:24.221  1014  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:24.221  6164  6164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 19:09:24.231  6164  6164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:09:24.231  1014  1471 D InputDispatcher: Focused application set to: xxxx
09-06 19:09:24.231  6164  6164 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 19:09:24.231  1014  1471 D InputDispatcher: Focus left window: 3147
09-06 19:09:24.231  6153  6153 D AndroidRuntime: Shutting down VM
09-06 19:09:24.231  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:24.231  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:24.251  6164  6164 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:24.251  6164  6164 D ActivityThread: Added TimaKeyStore provider
09-06 19:09:24.261   310   310 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 19:09:24.261   310   310 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-06 19:09:24.261  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 19:09:24.261  1014  1014 V ActivityManager: Display changed displayId=0
09-06 19:09:24.281  1014  3243 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:09:24.311   257  4502 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-06 19:09:24.321   257   437 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-06 19:09:24.321  3147  3147 V ActivityThread: updateVisibility : ActivityRecord{2b564e45 token=android.os.BinderProxy@8c40d40 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-06 19:09:24.391  6164  6164 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-06 19:09:24.411  6164  6164 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8900-8901)
09-06 19:09:24.411  6164  6164 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 19:09:24.441  6153  6153 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 19:09:24.441  6164  6164 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c673911}
09-06 19:09:24.441  6164  6164 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:09:24.441  6164  6164 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-06 19:09:24.471  6164  6164 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-06 19:09:24.481  6164  6164 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:24.481  6164  6164 E SysUtils: ApplicationContext is null in ApplicationStatus
09-06 19:09:24.501  6164  6164 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
09-06 19:09:24.501  6164  6164 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
09-06 19:09:24.501  6164  6164 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
09-06 19:09:24.511  6164  6164 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:24.511  6164  6164 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:24.511  6164  6164 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:24.511  6164  6164 I Adreno-EGL: Local Branch: 
09-06 19:09:24.511  6164  6164 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:24.511  6164  6164 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:24.511  6164  6164 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
09-06 19:09:24.631  6164  6190 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
09-06 19:09:24.681  6164  6164 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:24.691  6164  6164 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-06 19:09:24.701  6164  6164 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 19:09:24.701  6164  6164 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-06 19:09:24.701  6164  6164 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-06 19:09:24.711  6164  6164 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:24.711  6164  6164 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-06 19:09:24.751  6164  6203 D OpenGLRenderer: Render dirty regions requested: true
09-06 19:09:24.761  1014  1485 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:09:24.761  1014  1485 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:09:24.761  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 19:09:24.761  1014  1485 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 19:09:24.761  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:09:24.771  6164  6164 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 19:09:24.771  6164  6164 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 19:09:24.781   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
09-06 19:09:24.791  1014  1369 D InputDispatcher: Focus entered window: 6164
09-06 19:09:24.791  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:24.801  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:24.801  6164  6164 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:09:24.801  6164  6203 I OpenGLRenderer: Initialized EGL, version 1.4
09-06 19:09:24.801  6164  6203 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-06 19:09:24.801  6164  6203 D OpenGLRenderer: Enabling debug mode 0
09-06 19:09:24.841  6164  6164 V ActivityThread: updateVisibility : ActivityRecord{3279e080 token=android.os.BinderProxy@3b2b65b2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:09:24.871  1014  3243 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 19:09:24.871  1014  6206 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-06 19:09:24.871  1171  1171 D PanelView: There is/are notification(s) 
09-06 19:09:24.881  1014  1045 I ActivityManager: Displayed Component not be shown by security: +596ms (total +689ms)
09-06 19:09:24.881  1014  1045 W ActivityManager: mDVFSHelper.release()
09-06 19:09:24.891  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20e01cfb u0 com.test.thalitest/.MainActivity t128} time:109380
09-06 19:09:24.891  1792  1792 I SamsungIME: getCurrentCandidateView
09-06 19:09:24.891   257   445 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
09-06 19:09:24.891  6164  6164 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 19:09:24.891  6164  6164 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b2b65b2 time:109387
09-06 19:09:24.891   257   437 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
09-06 19:09:24.941  6164  6164 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6164
09-06 19:09:24.981  1792  1792 D SamsungIME: Dismiss ExpandCandiate
09-06 19:09:25.081  6164  6164 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-06 19:09:25.121  1792  1792 I SamsungIME: getDebugLevel  : 0x4f4c
09-06 19:09:25.161  1792  1792 I SamsungIME: getDebugLevel  : 0x4f4c
09-06 19:09:25.171  1792  1792 I SamsungIME: KeybaordView init() : load resources
09-06 19:09:25.171  6164  6209 D jxcore_app_log: JniHelper::setJavaVM(0xb76e1328), pthread_self() = -1211856912
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 19:09:25.181  6164  6209 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@140669b0 added. We now have 1 listener(s)
,09-06 19:09:25.191  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-06 19:09:25.191  6164  6209 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
,09-06 19:09:25.191  6164  6209 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-06 19:09:25.191  6164  6209 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:09:25.201  1792  1792 I SamsungIME: getCurrentKeyboard
09-06 19:09:25.201  1792  1792 I SamsungIME: getTextKeyboard
,09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-06 19:09:25.201  6164  6209 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@201a214f added. We now have 1 listener(s)
09-06 19:09:25.201  6164  6209 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:25.211  1792  1792 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:09:25.211  6164  6209 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB,
,09-06 19:09:25.221  6164  6209 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:25.221  6164  6209 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:25.221  6164  6209 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 19:09:25.221  6164  6209 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:25.221  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:25.231  6164  6209 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:09:25.231  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:25.261  6164  6164 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 19:09:25.281   287   287 E SMD     : DCD OFF
,09-06 19:09:25.741  1792  6214 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 19:09:25.781  6164  6217 W jxcore-log: Initializing JXcore engine
09-06 19:09:25.781  6164  6217 W jxcore-log: JXcore engine is ready
,09-06 19:09:25.841  1924  1924 E audit   : type=1400 msg=audit(1473181765.841:205): avc:  denied  { ioctl } for  pid=6217 comm="Thread-1069" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 19:09:25.841  1924  1924 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:09:25.841  1924  1924 E audit   : type=1300 msg=audit(1473181765.841:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e6008f8 items=0 ppid=302 ppcomm=main pid=6217 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1069" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 19:09:25.841  1924  1924 E audit   : type=1320 msg=audit(1473181765.841:205): 
,09-06 19:09:25.851  6164  6217 W jxcore-log: Starting JXcore engine
,09-06 19:09:25.961  6164  6217 W jxcore-log: Platform android
09-06 19:09:25.961  6164  6217 W jxcore-log: 
09-06 19:09:25.961  6164  6217 W jxcore-log: Process ARCH arm
09-06 19:09:25.961  6164  6217 W jxcore-log: 
,09-06 19:09:26.161  6164  6217 I jxcore-log: JXcore Cordova bridge is ready!
09-06 19:09:26.161  6164  6217 I jxcore-log: 
,09-06 19:09:26.161  6164  6217 W jxcore-log: JXcore engine is started
,09-06 19:09:26.171  6164  6209 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 19:09:26.171  6164  6164 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 19:09:28.281   287   287 E SMD     : DCD OFF,
,09-06 19:09:29.241  5376  5376 D FactoryTest: Not factory mode
,09-06 19:09:29.241  5376  5376 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 19:09:29.251  5376  5376 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-06 19:09:29.251  5376  5376 D MTPRx   : still no open session command from host, so toast
09-06 19:09:29.251  5376  5376 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113741
09-06 19:09:29.251  5376  5376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-06 19:09:29.251  1014  3245 E PersonaManagerService: inState():  stateMachine is null !!
09-06 19:09:29.251  5376  5376 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-06 19:09:29.251  1014  3245 I PersonaManagerService: PersonaId don't exist
09-06 19:09:29.251  1014  3245 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-06 19:09:29.251  1014  3245 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:29.251  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:29.251  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:29.251  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
09-06 19:09:29.261  1014  3245 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:09:29.261   310   310 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:29.271  1014  3245 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:09:29.281  1014  3245 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 19:09:29.281  1014  3245 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-06 19:09:29.281  1014  3245 D InputDispatcher: Focused application set to: xxxx
09-06 19:09:29.281  1014  3245 D InputDispatcher: Focus left window: 6164
09-06 19:09:29.281  5376  5376 E MTPRx   : started activity for popup
09-06 19:09:29.291  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:29.291  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:09:29.311  5376  5376 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:29.331  5376  5376 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 19:09:29.331  1014  1369 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 19:09:29.331  1014  1369 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:09:29.331  1014  1369 D InputDispatcher: Focused application set to: xxxx
09-06 19:09:29.331  1014  1369 D InputDispatcher: Focus entered window: 6164
09-06 19:09:29.331  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:09:29.331  1014  1546 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 19:09:29.341  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 19:09:29.341  1014  1546 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@34a0c19a attribute=null, token = android.os.BinderProxy@3fa09ea
,09-06 19:09:29.371  5376  5376 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 19:09:29.381  5376  5376 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-06 19:09:29.381  5376  5376 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 19:09:29.401  6164  6164 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:09:29.401  6164  6164 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 19:09:29.401  6164  6164 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-06 19:09:29.401  6164  6164 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 19:09:29.401  1014  3243 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 19:09:29.401  1014  3243 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-06 19:09:29.401  1014  3243 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:09:29.411  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:09:29.411  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:09:29.421  6164  6164 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:09:29.421  6164  6164 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 19:09:29.421  6164  6164 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@10f78881 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3f61fd49, 16908290=android.view.AbsSavedState$1@3f61fd49}, android:focusedViewId=100}]}]
09-06 19:09:29.421  6164  6164 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 19:09:29.421  6164  6164 V ActivityThread: updateVisibility : ActivityRecord{3279e080 token=android.os.BinderProxy@3b2b65b2 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 19:09:29.421  6164  6164 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 19:09:29.421  6164  6164 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-06 19:09:29.421  6164  6164 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b2b65b2 time:113919
,09-06 19:09:29.431  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:09:30.261   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:31.261   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:31.281   287   287 E SMD     : DCD OFF,
,09-06 19:09:31.551  1014  3245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:31.551  1014  3245 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4235, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-06 19:09:31.551  1014  3245 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-06 19:09:31.551  1014  3245 D BatteryService: stay LED for charging
09-06 19:09:31.551  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:31.561  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:09:31.561  1014  1014 I MotionRecognitionService: Plugged
09-06 19:09:31.561  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:09:31.561  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:31.561  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:09:31.561  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:31.571  2651  2651 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:31.571  2651  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:31.581  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:31.581  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:31.581  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:32.031  1014  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:32.261  1014  1040 W ActivityManager: mDVFSHelper.release()
,09-06 19:09:32.261   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:32.861  1014  2724 D SSRM:n  : SIOP:: AP = 340,
,09-06 19:09:33.261   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:34.241  1014  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-06 19:09:34.261   310   310 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-06 19:09:34.281   287   287 E SMD     : DCD OFF
,09-06 19:09:35.511  1014  1093 V AlarmManager: waitForAlarm result :4,
,09-06 19:09:35.511  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.531  1934  1934 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-06 19:09:35.561  1014  3243 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:35.561  1014  3243 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.561  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:35.561  1014  3243 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:35.561  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:35.631  3771  3771 D ConnectivityManager: CallingUid : 10012, CallingPid : 3771
,09-06 19:09:35.631  1014  1137 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:09:35.631  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-06 19:09:35.631  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-06 19:09:35.631  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 19:09:35.631  3771  6226 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:09:35.681  3771  6227 W DriveInitializer: Background init thread started
,09-06 19:09:35.701   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 19:09:35.701   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:35.701  3771  6227 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-06 19:09:35.751  1014  1315 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:35.751  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.751  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:35.751  1014  1315 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:35.751  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:35.771  1014  1369 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-06 19:09:35.771  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.791  1014  1374 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:35.791  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.791  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:35.791  1014  1374 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:35.791  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:35.821  3771  6234 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-06 19:09:35.821  3771  6234 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-06 19:09:35.831  3771  6227 W DriveInitializer: Background init thread ended
,09-06 19:09:35.831  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:35.871  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:35.871  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:35.871  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:35.971  1014  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:35.971  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-06 19:09:35.971  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:35.971  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:35.971  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.001  1014  1369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:36.001  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 19:09:36.011  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:36.011  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.011  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.051  1014  1546 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.061  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.061  1014  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.061  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.071  1014  3244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.071  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.071  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.071  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.121  1014  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.121  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.121  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:36.121  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.131  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:36.131  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:36.131  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:36.131  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:36.141  6240  6240 E Zygote  : MountEmulatedStorage(),
,09-06 19:09:36.141  6240  6240 E Zygote  : v2
09-06 19:09:36.141  6240  6240 I libpersona: KNOX_SDCARD checking this for 10012
09-06 19:09:36.141  6240  6240 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:36.141  1014  1369 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6240 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-06 19:09:36.151  6240  6240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:36.151  6240  6240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:36.151  6240  6240 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:36.171   302   302 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 24.872ms
,09-06 19:09:36.181   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.971ms
,09-06 19:09:36.191  6240  6240 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:36.191  6240  6240 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:36.201   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.230ms
,09-06 19:09:36.201  6240  6240 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 19:09:36.211  6240  6240 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:09:36.251  6240  6240 I MultiDex: VM with version 2.1.0 has multidex support
09-06 19:09:36.251  6240  6240 I MultiDex: install
09-06 19:09:36.251  6240  6240 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 19:09:36.281  6240  6240 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 19:09:36.351  6240  6240 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:09:36.351  6240  6240 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4f7a512: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:09:36.351  6240  6240 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 19:09:36.371  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 19:09:36.381  1014  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.381  6240  6240 D ChimeraCfgMgr: Reading stored module config
,09-06 19:09:36.381  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.381  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.381  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.411  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.411  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.411  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:36.411  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.451  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:36.451  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:09:36.451  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:36.451  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:36.451  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.471  1934  1934 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=a98db153-3425-4190-8f02-51107f0416d3
,09-06 19:09:36.481  6240  6254 I art     : Background sticky concurrent mark sweep GC freed 28623(1348KB) AllocSpace objects, 2(32KB) LOS objects, 4% free, 10MB/11MB, paused 17.936ms total 79.974ms
,09-06 19:09:36.481  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:36.481  1934  1934 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 19:09:36.501  6240  6240 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:09:36.501  6240  6240 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 19:09:36.511  6240  6258 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-06 19:09:36.511  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.511  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.511  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.511  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.611  1934  1934 I art     : Explicit concurrent mark sweep GC freed 60390(3MB) AllocSpace objects, 12(432KB) LOS objects, 40% free, 14MB/23MB, paused 3.149ms total 82.825ms
,09-06 19:09:36.681  1934  2108 W GCoreFlp: No location to return for getLastLocation()
,09-06 19:09:36.681  1638  1719 I art     : Explicit concurrent mark sweep GC freed 1409(48KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 749us total 26.564ms
,09-06 19:09:36.691   282  1138 D WVCdm   : Instantiating CDM.
,09-06 19:09:36.701   282   282 I WVCdm   : CdmEngine::OpenSession
,09-06 19:09:36.701   282   282 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-06 19:09:36.721   282   282 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-06 19:09:36.741  1934  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:09:36.741  3771  6236 D UdcContextInitService: registered all accounts: true
,09-06 19:09:36.741   282   282 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-06 19:09:36.741   282   282 D DrmWidevineDash: Service_Initialize: starts!
09-06 19:09:36.741   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-06 19:09:36.741   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,09-06 19:09:36.751   282   282 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-06 19:09:36.751   282   282 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-06 19:09:36.751   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-06 19:09:36.751   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,09-06 19:09:36.751   282   282 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-06 19:09:36.751   282   282 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-06 19:09:36.751   282   282 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-06 19:09:36.751   282   282 D QSEECOMAPI: : App is not loaded in QSEE
,09-06 19:09:36.751  1014  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.751  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:36.751  1014  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:36.751  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.761  1014  1546 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.761  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.761  1014  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:36.761  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.761  1014  3245 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:36.761  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:36.761  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:36.761  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:36.771  1934  2116 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 19:09:36.781   282   282 D QSEECOMAPI: : Loaded image: APP id = 11
,09-06 19:09:36.781   282   282 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-06 19:09:36.781   282   282 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-06 19:09:36.781   282   282 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-06 19:09:36.781   282   282 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1388000
,09-06 19:09:36.781   282   282 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1388000
09-06 19:09:36.781   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.801   428   439 D DrmLibTime: got the req here! ret=0
09-06 19:09:36.801   428   439 D DrmLibTime: command id, time_cmd_id = 770
09-06 19:09:36.801   428   439 D DrmLibTime: time_getutcsec starts!
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-06 19:09:36.801   428   439 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
09-06 19:09:36.801   428   439 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-06 19:09:36.801   428   439 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-06 19:09:36.801   428   439 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-06 19:09:36.801   313   557 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-06 19:09:36.801   313  6265 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-06 19:09:36.801   313  6265 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-06 19:09:36.801   313  6265 D QC-time-services: offset is: 0 for base: 0
09-06 19:09:36.801   428   439 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-06 19:09:36.801   428   439 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473181776
09-06 19:09:36.801   428   439 D DrmLibTime: time_getutcsec returns 0, sec = 1473181776; nsec = 0
09-06 19:09:36.801   428   439 D DrmLibTime: time_getutcsec finished! 
09-06 19:09:36.801   428   439 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-06 19:09:36.801   428   439 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-06 19:09:36.801   313   557 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection,
,09-06 19:09:36.801   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 19:09:36.831   282   282 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-06 19:09:36.831   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-06 19:09:36.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.831   282   282 D DrmWidevineDash: hlos api version =  9
09-06 19:09:36.831   282   282 D DrmWidevineDash: tz api version =  9
09-06 19:09:36.831   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-06 19:09:36.831   282   282 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-06 19:09:36.831   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.831  6240  6250 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-06 19:09:36.841  6240  6250 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:36.841  6240  6250 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 19:09:36.841  6240  6250 I System.out: (HTTPLog)-Thread-1048-942093367: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-06 19:09:36.841  6240  6250 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:36.841   277  1008 D EnterpriseController: uids 10012
09-06 19:09:36.841   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:36.841   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 19:09:36.851   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-06 19:09:36.851   282   282 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbef221b0
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-06 19:09:36.851   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.851   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-06 19:09:36.851   282   282 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7af1f50, dataLength=8
09-06 19:09:36.851   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.861   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.861   282   282 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-06 19:09:36.861   282   282 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7a7bf40, wrapped_rsa_key_length=1280
,09-06 19:09:36.861   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.861   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 19:09:36.861   282   282 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-06 19:09:36.861   282   282 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-06 19:09:36.861   282   690 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-06 19:09:36.861   282   690 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-06 19:09:36.861   282   690 I WVCdm   : CdmEngine::GenerateKeyRequest
09-06 19:09:36.861   282   690 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7a80a90, idLength=0xb18b7730
09-06 19:09:36.861   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb18b7746, maximum = 0xb18b7747
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: hlos api version =  9
09-06 19:09:36.881   282   690 D DrmWidevineDash: tz api version =  9
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18b77b4
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-06 19:09:36.881   282   690 D WVCdm   : PrepareKeyRequest: nonce=2831666154
09-06 19:09:36.881   282   690 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7a98e68
09-06 19:09:36.881   282   690 D DrmWidevineDash: message_length=1599, signature=0xb7ae03a0, signature_length=0xb18b7714
09-06 19:09:36.881   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:36.891  6240  6250 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 19:09:36.891  6240  6250 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6240, getuid(): 10012
,09-06 19:09:37.031   282   690 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:37.031   282   690 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-06 19:09:37.031   282  1138 I WVCdm   : CdmEngine::CloseSession
,09-06 19:09:37.031   282  1138 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-06 19:09:37.031   282  1138 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 19:09:37.031   282  1138 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 19:09:37.031   282  1138 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-06 19:09:37.041   282  1138 I WVCdm   : L3 Terminate.
09-06 19:09:37.041   282  1138 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-06 19:09:37.041   282  1138 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-06 19:09:37.041   282  1138 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 19:09:37.041   282  1138 D DrmWidevineDash: Service_Uninitialize: starts!
09-06 19:09:37.041   282  1138 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-06 19:09:37.041   282  1138 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-06 19:09:37.041   282  1138 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-06 19:09:37.041   282  1138 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-06 19:09:37.101  1014  1544 I art     : Explicit concurrent mark sweep GC freed 36642(2035KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 27MB/41MB, paused 2.454ms total 150.073ms
,09-06 19:09:37.131  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 19:09:37.131  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:09:37.131  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:37.131  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:37.131  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:37.201  6240  6250 I qtaguid : Untagging socket 30
,09-06 19:09:37.281   287   287 E SMD     : DCD OFF
,09-06 19:09:37.541  6269  6269 I dex2oat : ----------------------------------------------------
09-06 19:09:37.541  6269  6269 I dex2oat : <SS>: S T A R T I N G . . .
09-06 19:09:37.541  6269  6269 I dex2oat : <SS>: Zip is absent. Canceled.
,09-06 19:09:37.541  6269  6269 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 19:09:37.571  6269  6269 I dex2oat : dex2oat took 22.475ms (threads: 4)
,09-06 19:09:37.581  6240  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:37.581  6240  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:37.581  6240  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:37.581  6240  6250 I Adreno-EGL: Local Branch: 
09-06 19:09:37.581  6240  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:37.581  6240  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:37.581  6240  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:37.661  6240  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:37.661  6240  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:37.661  6240  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:37.661  6240  6250 I Adreno-EGL: Local Branch: 
09-06 19:09:37.661  6240  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:37.661  6240  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:37.661  6240  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:38.041  6240  6250 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:38.041  6240  6250 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:38.041  6240  6250 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:38.041  6240  6250 I Adreno-EGL: Local Branch: 
09-06 19:09:38.041  6240  6250 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:38.041  6240  6250 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:38.041  6240  6250 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:38.131  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:38.131  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.131  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.131  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:38.131  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.141  1934  6238 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:38.141   277  1008 D EnterpriseController: uids 10012
09-06 19:09:38.141   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:38.141   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 19:09:38.141  1934  6238 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:38.141  1934  6238 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1934, getuid(): 10012
,09-06 19:09:38.191  1934  6238 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1934, getuid(): 10012
,09-06 19:09:38.461  1934  2116 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:09:38.461  1934  2116 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-06 19:09:38.461  1934  2116 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-06 19:09:36.877+0200, stopTime=2016-09-06 19:09:38.471+0200, duration=1594ms
,09-06 19:09:38.481  1934  6280 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:38.481   277  1008 D EnterpriseController: uids 10012
09-06 19:09:38.481   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:38.481   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 19:09:38.481  1934  6280 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:38.481  1934  6280 I qtaguid : Tagging socket 70 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1934, getuid(): 10012
,09-06 19:09:38.511  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.531  1934  6280 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1934, getuid(): 10012
,09-06 19:09:38.621  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-06 19:09:38.621  6164  6217 I jxcore-log: 
,09-06 19:09:38.621  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-06 19:09:38.621  6164  6217 I jxcore-log: 
,09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:38.631  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:38.631  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:38.631  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 19:09:38.631  6164  6217 I jxcore-log: 
,09-06 19:09:38.631  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 19:09:38.631  6164  6217 I jxcore-log: 
,09-06 19:09:38.751  1934  6280 I qtaguid : Untagging socket 70
,09-06 19:09:38.791  1014  3245 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:38.791  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-06 19:09:38.791  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.791  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.791  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.821  1934  2116 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-06 19:09:38.871  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.881  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.881  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.881  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.901  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.911  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.911  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.911  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.951  1014  3245 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.951  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.951  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.951  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.951  1934  6288 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:09:38.951  1934  6286 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:38.951  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.951  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.951  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:38.961  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.981  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.981  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:38.981  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.981  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:38.981  1934  6288 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:09:38.981  1934  6286 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:38.981  1014  3244 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:38.981  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:38.981  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:38.981  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.011  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:39.011  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:39.011  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:39.011  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:39.011  1934  6288 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 19:09:39.011  1934  6286 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 19:09:39.011  1934  6286 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-06 19:09:39.021  1934  6286 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 19:09:39.071  1014  1026 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.101  1934  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.101   277  1008 D EnterpriseController: uids 10012
09-06 19:09:39.101   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:39.101   277  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 19:09:39.111  1934  6286 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 19:09:39.111  1934  6286 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:09:39.161  1934  6286 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:09:39.271   310   310 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:39.311  6164  6217 D executeNativeTests: Running unit tests,
,09-06 19:09:39.371  1014  3244 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.371  1934  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.371  1934  6286 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:09:39.401  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:09:39.401  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe added. We now have 2 listener(s)
,09-06 19:09:39.401  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 19:09:39.401  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:39.401  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:09:39.401  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:39.401  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f added. We now have 2 listener(s)
09-06 19:09:39.401  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:39.401  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:09:39.401  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.411  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:39.411  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.411  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:39.411  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.411  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:39.411  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:39.411  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:39.421  6164  6217 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-06 19:09:39.421  6164  6217 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:39.421  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:39.421  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:39.421  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.421  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.421  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.421  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:09:39.421  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe removed from the list
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.421  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f removed from the list
09-06 19:09:39.421  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.421  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.421  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.421  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.421  6164  6217 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-06 19:09:39.421  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.421  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.421  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.421  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.421  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.421  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.421  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.421  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.421  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.431  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.431  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.431  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.431  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:39.431  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:39.441  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.441  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.441  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.441  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.441  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.441  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.441  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.441  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.441  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.441  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.441  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.441  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.441  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.441  6164  6217 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 19:09:39.441  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.451  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 19:09:39.451  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.451  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:09:39.451  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:39.451  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:39.451  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:39.451  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:39.451  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:09:39.451  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.451  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.451  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:09:39.461  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:09:39.461  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:09:39.461  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:39.471  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 19:09:39.471  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:09:39.471  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:39.471  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:09:39.481  2651  2928 D BtGatt.GattService: registerClient() - UUID=52009f3d-91a1-470a-a031-3e285314f7b7
,09-06 19:09:39.521  1014  3245 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 19:09:39.521  2651  2718 D BtGatt.GattService: onClientRegistered() - UUID=52009f3d-91a1-470a-a031-3e285314f7b7, clientIf=6
,09-06 19:09:39.531  6164  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:39.531  2651  2662 D BtGatt.GattService: start scan with filters
,09-06 19:09:39.531  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:39.531  2651  2723 D BtGatt.ScanManager: handling starting scan
09-06 19:09:39.531  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:09:39.531  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:09:39.531  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:39.531  2651  2723 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:39.531  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-06 19:09:39.541  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-06 19:09:39.541  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:39.541  1934  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:39.541  1934  6286 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:09:39.541  2651  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:09:39.541  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.541  2651  2723 D BtGatt.ScanManager: allow scan with filters
09-06 19:09:39.541  2651  2723 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:09:39.541  2651  2723 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:09:39.541  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:39.541  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:09:39.541  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.541  2651  2723 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:39.541  2651  2723 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:39.551  6164  6217 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:39.551  2651  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:09:39.551  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.551  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:39.551  6164  6217 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:39.551  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.551  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:39.551  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.551  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:39.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:39.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:39.551  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:39.551  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:09:39.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:39.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:39.561  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:09:39.561  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.561  2651  2928 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:39.561  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:39.561  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 19:09:39.561  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:39.561  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,09-06 19:09:39.561  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:39.561  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:39.561  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:39.571  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:09:39.571  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:39.571  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:39.571  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:39.571  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.571  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.571  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.571  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:39.571  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.571  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.571  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.571  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.571  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.571  6164  6217 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:09:39.571  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.571  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:39.571  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.581  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.581  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:39.581  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:39.581  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.591  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:09:39.591  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:09:39.591  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:09:39.591  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:39.591  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:39.591  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.591  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:39.601  2651  2723 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 18
,09-06 19:09:39.601  2651  2723 D BtGatt.ScanManager: filter size is 1,
09-06 19:09:39.601  2651  2723 D BtGatt.ScanManager: delete FilterIndex - 3
09-06 19:09:39.601  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:39.601  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:39.601  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.601  2651  2723 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:39.601  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:39.611  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:09:39.611  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.611  2651  2723 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:39.611  2651  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:39.611  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:09:39.611  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.611  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:09:39.611  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:39.611  2651  2662 D BtGatt.GattService: registerClient() - UUID=b7460e38-cc49-488d-ad8a-ae4f7bc1b6e8
,09-06 19:09:39.651  2651  2718 D BtGatt.GattService: onClientRegistered() - UUID=b7460e38-cc49-488d-ad8a-ae4f7bc1b6e8, clientIf=6
,09-06 19:09:39.651  6164  6177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:39.651  2651  2661 D BtGatt.GattService: start scan with filters
,09-06 19:09:39.661  2651  2723 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:39.661  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:39.661  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:09:39.661  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:09:39.661  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:09:39.661  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:39.661  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:39.671  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:09:39.671  2651  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:09:39.671  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.671  2651  2723 D BtGatt.ScanManager: allow scan with filters
09-06 19:09:39.671  2651  2723 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:09:39.671  2651  2723 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:09:39.671  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:09:39.671  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.671  2651  2723 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:39.671  2651  2723 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:09:39.671  2651  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:09:39.671  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.671  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:39.681  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:39.681  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.681  6164  6217 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 19:09:39.681  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.681  6164  6217 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:39.681  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.681  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:39.681  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.681  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:39.681  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:39.681  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:39.681  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:39.681  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:39.681  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:39.681  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:39.691  2651  2928 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:39.691  2651  2662 D BtGatt.GattService: unregisterClient() - clientIf=6,
09-06 19:09:39.691  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-06 19:09:39.691  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:39.691  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 19:09:39.691  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:39.691  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:39.701  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:39.701  2651  2723 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 19
,09-06 19:09:39.701  1014  1546 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:39.701  2651  2723 D BtGatt.ScanManager: filter size is 1
,09-06 19:09:39.701  2651  2723 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 19:09:39.701  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.701  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:39.701  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.701  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.701  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.701  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.701  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.701  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.701  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:09:39.701  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.701  2651  2723 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:39.711  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.711  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.711  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.711  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.711  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.711  6164  6217 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-06 19:09:39.711  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.711  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:39.711  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:39.711  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:09:39.711  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.711  2651  2723 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:09:39.711  2651  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:39.711  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.721  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.721  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:39.721  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:39.721  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:09:39.721  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:09:39.721  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:09:39.731  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.731  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:39.731  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:09:39.731  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.731  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:09:39.731  1934  6286 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:09:39.731  1934  6286 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:09:39.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:09:39.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:09:39.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:09:39.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 19:09:39.741  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:09:39.741  2651  2661 D BtGatt.GattService: registerClient() - UUID=ec3a2860-00a5-4415-bac9-56bdbff3e270
,09-06 19:09:39.781  2651  2718 D BtGatt.GattService: onClientRegistered() - UUID=ec3a2860-00a5-4415-bac9-56bdbff3e270, clientIf=6
,09-06 19:09:39.781  6164  6177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:09:39.791  2651  2929 D BtGatt.GattService: start scan with filters
,09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: handling starting scan
,09-06 19:09:39.791  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:09:39.791  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 19:09:39.791  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:09:39.791  2651  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:09:39.791  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.791  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: allow scan with filters
,09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:09:39.791  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:09:39.791  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:09:39.791  2651  2723 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-06 19:09:39.791  2651  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:09:39.791  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.791  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:09:39.791  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 19:09:39.791  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:09:39.801  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:09:39.801  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:09:39.801  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:09:39.811  2651  2723 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 20
,09-06 19:09:39.811  6164  6217 I io.jxcore.node.ConnectionHelper: start: OK,
09-06 19:09:39.811  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.811  6164  6217 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 19:09:39.811  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.811  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:09:39.811  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:09:39.811  2651  2661 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:09:39.811  2651  2929 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:09:39.811  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:09:39.811  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:09:39.821  2651  2723 D BtGatt.ScanManager: filter size is 1
09-06 19:09:39.821  2651  2723 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 19:09:39.821  2651  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:09:39.821  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.821  2651  2723 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:09:39.821  2651  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-06 19:09:39.821  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.821  2651  2723 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 19:09:39.821  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.821  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.821  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:39.821  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 19:09:39.821  6164  6217 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:09:39.821  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.821  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:39.821  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:09:39.821  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
,09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.821  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.821  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.821  2651  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:09:39.821  2651  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:09:39.821  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.821  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.821  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.821  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:39.831  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
09-06 19:09:39.831  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 19:09:39.831  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 19:09:39.831  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.831  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.831  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.831  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.831  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.831  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.831  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.841  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.841  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:39.841  6164  6217 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:39.841  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:09:39.841  6164  6217 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710],
,09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910],
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 19:09:39.841  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 19:09:39.841  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-06 19:09:39.841  6164  6217 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:39.841  6164  6217 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 19:09:39.841  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:39.841  6164  6217 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:39.841  6164  6217 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 19:09:39.841  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-06 19:09:39.841  6164  6217 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 19:09:39.841  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 19:09:39.851  6164  6217 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.851  6164  6297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1133)
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.851  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.851  6164  6298 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1133
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.851  6164  6217 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.851  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 19:09:39.851  6164  6297 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,09-06 19:09:39.851  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.851  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.851  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.851  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.851  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.851  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.851  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 19:09:39.861  6164  6217 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:39.861  6164  6217 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 19:09:39.861  6164  6217 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:39.861  6164  6217 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-06 19:09:39.861  6164  6217 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 19:09:39.861  6164  6217 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 19:09:39.861  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.861  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.861  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6297 D BluetoothSocket: connect(): myUserId = 0
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6297 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.861  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.861  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:39.861  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.861  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.861  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.861  6164  6217 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 19:09:39.861  2651  2661 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:09:39.861  6164  6297 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-06 19:09:39.861  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:09:39.871  6164  6164 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6164 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.871  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:09:39.871  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.871  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.871  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.871  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.871  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6299 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 19:09:39.871  6164  6299 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.871  6164  6217 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-06 19:09:39.871  6164  6217 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 19:09:39.871  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 19:09:39.871  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.871  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:09:39.871  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.871  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.871  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:09:39.871  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.871  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.871  6164  6164 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-06 19:09:39.881  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.881  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.881  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.881  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.881  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:09:39.881  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:09:39.881  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a4bdefe not in the list
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
09-06 19:09:39.881  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:09:39.881  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:09:39.881  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:09:39.881  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:09:39.881  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b3865f not in the list
,09-06 19:09:39.881  6164  6217 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 19:09:39.881  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:39.881  6164  6217 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 19:09:39.881  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 19:09:39.881  6164  6217 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 19:09:39.881  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-06 19:09:39.891  6164  6217 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:39.891  6164  6217 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 19:09:39.891  6164  6217 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 19:09:39.891  6164  6217 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 19:09:39.891  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:39.891  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2273d429 added. We now have 2 listener(s)
,09-06 19:09:39.891  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:39.891  6164  6217 D BluetoothAdapter: enable()
,09-06 19:09:39.891  6164  6217 D BluetoothAdapter: enable(): BT is already enabled..!
,09-06 19:09:39.901  1014  1369 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:39.901  1014  1369 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
09-06 19:09:39.901  1014  1369 D SecContentProvider2: mCursor = null
,09-06 19:09:39.901  1014  1369 D WifiService: setWifiEnabled: true pid=6164, uid=10155
09-06 19:09:39.901  1014  1369 W ActivityManager: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:39.901  1014  1369 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:39.901  1014  1369 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:39.901  1014  1369 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 19:09:39.901  1014  1369 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:39.901  1014  1369 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:39.901  1014  1369 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:39.901  1014  1369 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:39.901  1014  1369 D SettingsProvider: name = wifi_on
,09-06 19:09:39.901  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:39.901  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36ac03ae added. We now have 3 listener(s)
09-06 19:09:39.901  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:39.901  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:39.901  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@36f0c54f added. We now have 4 listener(s)
,09-06 19:09:39.901  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:39.911  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:39.911  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2abc44dc added. We now have 5 listener(s)
09-06 19:09:39.911  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:09:39.911  1014  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-06 19:09:39.911  1014  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-06 19:09:39.911  1014  1485 D SecContentProvider2: mCursor = null
,09-06 19:09:39.911  1014  1485 D SettingsProvider: name = wifi_on
09-06 19:09:39.911  1014  1485 D WifiService: setWifiEnabled: false pid=6164, uid=10155
,09-06 19:09:39.921  6164  6217 D BluetoothAdapter: disable()
,09-06 19:09:39.921  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 19:09:39.921  1014  1026 D SettingsProvider: name = bluetooth_on
09-06 19:09:39.921  2100  2100 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:09:39.921  2100  2100 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:09:39.921  2100  2100 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-06 19:09:39.931  2100  2100 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:09:39.931  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:09:39.931  2651  2715 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-06 19:09:39.931  2651  2715 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:39.931  2651  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:39.931  2651  2715 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:39.931  1014  1369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:39.931  2651  2715 D BluetoothAdapterService: updateAdapterState state is 13
09-06 19:09:39.931  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:39.931  1014  1369 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:39.941  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:39.941  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:39.941  2651  2651 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-06 19:09:39.941  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:09:39.941  2651  2715 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:39.941  2651  2715 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:39.941  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@342e1d5b, channel: 19, state: LISTENING
09-06 19:09:39.941  2651  2715 D BluetoothAdapterService: terminating service from this receiver
09-06 19:09:39.941  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@342e1d5b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4f7a512, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13f669f8mSocket: android.net.LocalSocket@204ded1 impl:android.net.LocalSocketImpl@3e9cbd36 fd:FileDescriptor[74]
09-06 19:09:39.941  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@204ded1 impl:android.net.LocalSocketImpl@3e9cbd36 fd:FileDescriptor[74]
,09-06 19:09:39.941  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:39.941  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:39.941  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:39.951  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:39.951  1364  1364 D BluetoothPbap: Proxy object disconnected
09-06 19:09:39.951  2651  2715 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:39.951  2651  2715 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:09:39.951  1014  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:09:39.951  2651  2715 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 19:09:39.951  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:09:39.951  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:39.951  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:39.951  1014  1125 E WifiNative-wlan0: do suspend true
09-06 19:09:39.951  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.951  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.961  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:39.961  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.961  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:09:39.961  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.961  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:39.961  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:39.961  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:39.961  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:39.961  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:39.961  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:39.971  1792  1792 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:39.971  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:09:39.971  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:09:39.971  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:09:39.971  1014  1315 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:09:39.971  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:39.971  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:39.971  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:09:39.971  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:09:39.981  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:39.981  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:09:39.981  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:39.981  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.981  2651  2718 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:09:39.991  2651  2718 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:39.991  2651  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:09:39.991  2651  2715 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:09:39.991  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:39.991  2651  2715 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-06 19:09:39.991  1014  3244 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:39.991  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:39.991  2651  2715 E bt-btif : cmd socket is not created
09-06 19:09:39.991  2651  2715 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-06 19:09:39.991  2651  4930 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:09:39.991  2651  2800 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:09:39.991  2651  2800 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-06 19:09:39.991  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:39.991  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:39.991  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:39.991  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:40.001  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:40.001  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:40.001  2651  2800 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:40.001  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.011  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34242da4, channel: 5, state: LISTENING
,09-06 19:09:40.011  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34242da4, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@301f9ee0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a27970dmSocket: android.net.LocalSocket@23ef76c2 impl:android.net.LocalSocketImpl@1f30dcd3 fd:FileDescriptor[76]
09-06 19:09:40.011  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23ef76c2 impl:android.net.LocalSocketImpl@1f30dcd3 fd:FileDescriptor[76]
09-06 19:09:40.011  6164  6297 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27b8acba, channel: -1, state: INIT
09-06 19:09:40.011  6164  6297 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@27b8acba, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e676b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3836d2c8mSocket: android.net.LocalSocket@3240df61 impl:android.net.LocalSocketImpl@fb4da86 fd:FileDescriptor[109]
09-06 19:09:40.011  2651  2651 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:40.011  2651  2651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9488010, channel: 12, state: LISTENING
09-06 19:09:40.011  2651  2651 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9488010, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385ec46a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@27439709mSocket: android.net.LocalSocket@29c23d0e impl:android.net.LocalSocketImpl@3d22732f fd:FileDescriptor[79]
09-06 19:09:40.011  2651  2651 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29c23d0e impl:android.net.LocalSocketImpl@3d22732f fd:FileDescriptor[79]
09-06 19:09:40.011  6164  6297 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3240df61 impl:android.net.LocalSocketImpl@fb4da86 fd:FileDescriptor[109]
09-06 19:09:40.011  6164  6297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1133)
09-06 19:09:40.011  2651  4930 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:40.011  1364  1364 D DockEventReceiver: finishStartingService: stopping service
09-06 19:09:40.011  2651  2651 V BluetoothOppManager: cleanUp...
,09-06 19:09:40.011  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:40.021  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:40.021  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:40.021  1014  3244 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 19:09:40.021  1014  3244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.021  1014  3244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.021  1014  3244 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.021  1014  3244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.031  6304  6304 E Zygote  : MountEmulatedStorage()
,09-06 19:09:40.031  6304  6304 E Zygote  : v2
09-06 19:09:40.031  6304  6304 I libpersona: KNOX_SDCARD checking this for 10003
09-06 19:09:40.031  6304  6304 I libpersona: KNOX_SDCARD not a persona,
,09-06 19:09:40.031  1014  3244 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6304 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-06 19:09:40.041  6304  6304 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:40.041  6304  6304 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 19:09:40.041  6304  6304 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:40.061  1014  1374 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:40.061  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:40.061  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:40.061  1014  1374 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:40.061  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.071  6304  6304 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:40.071  6304  6304 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:40.111  6304  6304 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 19:09:40.151  6304  6304 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
09-06 19:09:40.151  6304  6304 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 19:09:40.151  6304  6304 D UserAnalysis: Create SecureDbHelper
,09-06 19:09:40.161  6304  6304 D IntelligenceServiceApplication: onCreate()
,09-06 19:09:40.161  1014  3245 I ActivityManager: Killing 5304:com.google.android.talk/u0a104 (adj 15): empty #31
,09-06 19:09:40.171  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 19:09:40.171  6304  6304 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 19:09:40.171  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.171  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.171  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.171  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.191  6323  6323 E Zygote  : MountEmulatedStorage()
,09-06 19:09:40.191  6323  6323 E Zygote  : v2
09-06 19:09:40.191  6323  6323 I libpersona: KNOX_SDCARD checking this for 10107
09-06 19:09:40.191  6323  6323 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:40.191  6323  6323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:40.191  6323  6323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:09:40.191  1014  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6323 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 19:09:40.191  6323  6323 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:40.191  2651  2800 W bt-btif : ag scb idx 1 not allocated
,09-06 19:09:40.191  2651  2800 W bt-btif : ag scb idx 2 not allocated
09-06 19:09:40.191  2651  2800 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:09:40.191  2651  2880 I bt_userial_mct: exiting userial_read_thread
09-06 19:09:40.191  2651  2880 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 19:09:40.191  2651  2718 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:09:40.191  2651  2802 I bt_vendor: hw_epilog_process
09-06 19:09:40.201  2651  2718 D bt_userial_mct: userial_close
09-06 19:09:40.201  2651  2718 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:09:40.201  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 19:09:40.201  6304  6304 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,09-06 19:09:40.211  6304  6304 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 19:09:40.211  6323  6323 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:40.211  6323  6323 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:40.271   310   310 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:40.281   287   287 E SMD     : DCD OFF,
,09-06 19:09:40.371  6164  6164 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:09:40.391  1014  1471 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:40.391  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 19:09:40.391  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.391  1014  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:40.391  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.k.c(PG:583)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.441  6323  6323 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 19:09:40.441  6323  6323 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 19:09:40.451  1014  3244 I ActivityManager: Killing 4988:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-06 19:09:40.451  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 19:09:40.461  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 19:09:40.471  2651  2718 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:09:40.471  2651  2718 I bt_vendor: bluetooth satus is on
09-06 19:09:40.471  2651  2718 I bt_vendor: bt-vendor : resetting BT status
09-06 19:09:40.471  2651  2718 I bt_vendor: Starting hciattach daemon
09-06 19:09:40.471  2651  2718 I bt_vendor: try to set false
09-06 19:09:40.471  2651  2718 I bt_vendor: Starting hciattach daemon
09-06 19:09:40.471  2651  2718 I bt_vendor: try to set false
09-06 19:09:40.471  2651  2718 I bt_vendor: cleanup
09-06 19:09:40.471  2651  2800 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:09:40.471  2651  2718 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:09:40.471  2651  2718 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:09:40.471  2651  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:09:40.471  2651  2715 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:40.471  2651  2715 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:09:40.471  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:40.471  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:40.471  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:09:40.471  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.471  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:09:40.471  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.471  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.471  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:40.481  2651  2651 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:09:40.481  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:40.481  2651  2651 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:40.481  2651  2651 D BtGatt.GattService: stop()
09-06 19:09:40.481  2651  2651 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:09:40.481  1014  3244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.481  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:09:40.481  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.481  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.481  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.481  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:40.481  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-06 19:09:40.481  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.481  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:09:40.481  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.481  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.481  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:40.481  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:40.481  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 19:09:40.481  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.481  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:09:40.491  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.491  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.491  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:40.491  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:09:40.491  1014  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.491  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-06 19:09:40.491  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.491  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.491  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:40.491  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-06 19:09:40.491  1014  1374 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.491  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:40.491  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.491  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.491  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.491  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.491  2651  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.491  1014  1369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.491  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 19:09:40.501  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.501  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.501  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:40.501  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:09:40.501  1014  3245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:40.501  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-06 19:09:40.501  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.501  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.501  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:40.501  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:40.501  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:40.501  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:40.501  2651  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:40.501  2651  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:40.511  2651  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:40.511  2651  2715 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 19:09:40.511  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 19:09:40.511  2651  2651 D HeadsetService: Received stop request...Stopping profile...
09-06 19:09:40.511  6323  6342 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-06 19:09:40.511  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:40.511  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 19:09:40.511  2651  2651 D A2dpService: Received stop request...Stopping profile...
09-06 19:09:40.511  2651  2730 D A2dpStateMachine: Exit Disconnected: -1
09-06 19:09:40.511  1364  1364 D HeadsetProfile: Bluetooth service disconnected
09-06 19:09:40.511  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:40.521  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:40.521  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 19:09:40.521  2857  2857 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:40.521  2651  2651 D HidService: Received stop request...Stopping profile...
09-06 19:09:40.521  2651  2651 D HidService: Stopping Bluetooth HidService
09-06 19:09:40.521  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 19:09:40.521  2651  2651 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:09:40.521  2651  2651 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 19:09:40.521  1364  1364 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:40.521  1364  1364 D A2dpProfile: Bluetooth service disconnected
09-06 19:09:40.521  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:40.521  2651  2651 D HealthService: Received stop request...Stopping profile...
,09-06 19:09:40.521  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:40.521  2651  2651 D PanService: Received stop request...Stopping profile...
09-06 19:09:40.521  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:40.531  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:40.531  2651  2651 D BluetoothMapService: Received stop request...Stopping profile...
09-06 19:09:40.531  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:40.531  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:40.531  1364  1364 D HidProfile: Bluetooth service disconnected
,09-06 19:09:40.531  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.531  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:40.531  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-06 19:09:40.531  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:40.531  1364  1364 D PanProfile: Bluetooth service disconnected
,09-06 19:09:40.531  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:40.531  2651  2651 D SapService: Received stop request...Stopping profile...
09-06 19:09:40.531  1364  1364 D BluetoothMap: Proxy object disconnected
,09-06 19:09:40.531  1364  1364 D MapProfile: Bluetooth service disconnected
,09-06 19:09:40.541  2651  2651 D SapService: Stopping Bluetooth SapService
09-06 19:09:40.541  2651  2651 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:40.541  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:40.541  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:40.541  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:09:40.541  1364  1364 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:40.541  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 19:09:40.541  2651  2651 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:40.541  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 19:09:40.541  1364  1364 D SapProfile: Bluetooth service disconnected
09-06 19:09:40.541  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:40.541  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:40.541  2651  2651 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:40.541  2651  2651 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:09:40.541  2651  2733 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 19:09:40.541  2651  2651 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:40.541  2651  2651 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-06 19:09:40.551  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true,
09-06 19:09:40.551  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.551  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.551  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:09:40.551  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.551  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.551  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:40.551  2651  2651 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:40.551  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:09:40.551  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:40.551  2651  2651 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:40.551  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 19:09:40.551  2651  2651 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:40.551  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 19:09:40.551  2651  2651 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:40.551  2651  2651 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:09:40.551  2651  2651 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 19:09:40.551  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:40.551  2651  2651 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 19:09:40.551  2651  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:09:40.561  2651  2715 D BluetoothAdapterProperties: Setting state to 10
09-06 19:09:40.561  2651  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 19:09:40.561  2651  2715 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:40.561  2651  2715 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:09:40.561  2651  2715 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:40.561  2651  2715 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:40.561  2651  2715 I BluetoothAdapterState: Entering OffState
,09-06 19:09:40.561  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:40.561  1429  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.561  1364  1378 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.561  1364  1378 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.561  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.561  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:40.561  1458  1749 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.561  1458  1749 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.561  1364  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:40.571  6164  6178 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:40.571  6164  6178 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:40.571  6164  6178 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:09:40.571  6164  6178 D BluetoothLeAdvertiser: Exit stop advertising
09-06 19:09:40.571  6164  6178 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:09:40.571  6164  6178 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:09:40.571  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:40.571  2857  2878 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:40.571  1171  1188 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.571  1171  1188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.571  6323  6339 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:40.571  6323  6339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.581  1364  1380 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:09:40.581  1439  1456 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.581  1439  1456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.581  2651  2662 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:40.581  2651  2929 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:40.581  2651  2929 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.581  1934  1944 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:40.581  1934  1944 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.581  2857  2876 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:40.581  2857  2876 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:40.581  1364  1380 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:09:40.581  1364  1380 D Bluetoothsap: Unbinding service...
,09-06 19:09:40.581  1364  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:40.591  1364  1380 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:09:40.591  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-06 19:09:40.591  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:40.601  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:40.601  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:40.601  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:40.601  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:40.601  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:40.601  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:40.601  1171  1171 D BluetoothTile:  getBluetoothState : 10
09-06 19:09:40.601  1171  1743 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:40.601  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:40.601  1171  1743 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:40.601  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:40.601  1792  1792 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:40.601  1014  1315 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 19:09:40.601  1934  2122 D BluetoothAdapter: 1039818314: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:40.601  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:40.601  1934  2122 D BluetoothAdapter: 1039818314: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:40.611  1014  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:40.611  1014  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:40.611  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:40.611  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:40.611  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:40.611  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:40.611  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:40.611  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.611  2651  2718 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:09:40.611  1934  6282 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:40.611  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:40.611  1934  6282 I qtaguid : Tagging socket 70 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1934, getuid(): 10012
,09-06 19:09:40.621  2651  2651 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:09:40.621  2651  2651 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-06 19:09:40.621  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:40.621  2651  2651 I BluetoothServiceJni: cleanupNative: return from cleanup
09-06 19:09:40.621  1014  1546 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:40.621  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:40.621  2651  2651 I art     : System.exit called, status: 0
09-06 19:09:40.621  2651  2651 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:40.621  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.621  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.621  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:40.631  1364  1364 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:40.631  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:40.631  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:40.631  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:40.731  1014  1546 I ActivityManager: Process com.android.bluetooth (pid 2651)(adj 0) has died(49,1086)
,09-06 19:09:40.741  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:40.741  1014  3245 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:40.741  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:40.741  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:40.741  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:40.741  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.751  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-06 19:09:40.751  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:09:40.761   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:40.771  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:40.771  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 19:09:40.771  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.771  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.771  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.771  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:40.771  1934  4358 V NativeCrypto: Read error: ssl=0xb7c4d108: I/O error during system call, Connection timed out
09-06 19:09:40.771  1934  6282 I qtaguid : Untagging socket 70
,09-06 19:09:40.771  1934  6355 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-06 19:09:40.781  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:40.771  1934  6282 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:40.781  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-06 19:09:40.781  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:09:40.781  1934  4358 V NativeCrypto: SSL shutdown failed: ssl=0xb7c4d108: I/O error during system call, Broken pipe
09-06 19:09:40.781  1014  1127 E ConnectivityService: updateNetworkInfo(),
09-06 19:09:40.781  1014  1369 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-06 19:09:40.781  1934  4358 E GCM     : Wifi connection closed with errorCode 20
09-06 19:09:40.791  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:40.791  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:40.791  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,09-06 19:09:40.791  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:40.791  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 19:09:40.791  1014  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:40.791  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:09:40.791  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:40.791  1014  2216 I qtaguid : Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,09-06 19:09:40.801  1014  2216 I qtaguid : Untagging socket 351
09-06 19:09:40.801  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:40.801  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:40.801  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.801  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:09:40.801  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.801  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 19:09:40.801  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:40.801  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:40.801  1014  2216 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 19:09:40.801  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,09-06 19:09:40.801  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:40.801  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-06 19:09:40.801  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-06 19:09:40.801  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 19:09:40.801  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:40.811  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:09:40.811  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,09-06 19:09:40.811  1014  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:40.811  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.811  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:40.811  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.821  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:40.821  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:40.821  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:40.831  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:40.831  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-06 19:09:40.831  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:40.831  1014  1045 D WifiDisplayController: disconnect
09-06 19:09:40.831  1014  1045 D WifiDisplayController: updateConnection
09-06 19:09:40.831  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:40.831  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:40.831  1014  1125 E WifiNative-wlan0: do suspend true
09-06 19:09:40.831  1014  1124 D WifiP2pService: P2pDisablingState
09-06 19:09:40.831  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:09:40.831  1014  1124 D WifiP2pService: p2p socket connection lost
09-06 19:09:40.831  1014  1124 D WifiP2pService: P2pDisabledState
,09-06 19:09:40.831  1014  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:40.831  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:40.841  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:40.841  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:40.841  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:40.841  3680  3680 I Hs20UtilService: Starting #8
,09-06 19:09:40.841  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:09:40.841  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:40.841  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:40.841  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:40.841  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:40.851  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-06 19:09:40.851  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:40.851  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:40.851  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:40.851  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:40.851  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:40.851  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:40.851  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:40.851  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:40.851  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:40.851  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:40.851  1934  6355 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
09-06 19:09:40.851  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 19:09:40.851  1014  1137 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:40.851  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:09:40.861  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:09:40.861  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:40.861  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:40.861  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-06 19:09:40.861  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:40.861  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:40.861  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:40.861  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-06 19:09:40.861  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.861  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.861  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.861  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.881  6360  6360 E Zygote  : MountEmulatedStorage(),
09-06 19:09:40.881  6360  6360 E Zygote  : v2
09-06 19:09:40.881  6360  6360 I libpersona: KNOX_SDCARD checking this for 10068,
09-06 19:09:40.881  6360  6360 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:40.881  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6360 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:40.881  6360  6360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 19:09:40.881  6360  6360 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:40.881  6360  6360 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:40.901  6360  6360 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:40.901  6360  6360 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:40.921  6360  6360 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 19:09:40.931  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:40.931  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:40.961  6360  6360 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:40.961  1014  1543 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-06 19:09:40.961  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.961  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.961  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:40.961  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:40.971  6375  6375 E Zygote  : MountEmulatedStorage(),
09-06 19:09:40.971  6375  6375 E Zygote  : v2
09-06 19:09:40.971  6375  6375 I libpersona: KNOX_SDCARD checking this for 10069
09-06 19:09:40.971  6375  6375 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:40.971  6375  6375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:40.971  1014  1543 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6375 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:40.981  6375  6375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:40.981  6375  6375 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:40.991  6375  6375 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:40.991  6375  6375 D ActivityThread: Added TimaKeyStore provider,
,09-06 19:09:41.021  6375  6375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:41.021  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.021  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.021  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-06 19:09:41.021  1014  1137 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 19:09:41.031  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.031  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.031  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.031  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.051  6391  6391 E Zygote  : MountEmulatedStorage(),
,09-06 19:09:41.051  6391  6391 E Zygote  : v2,
09-06 19:09:41.051  6391  6391 I libpersona: KNOX_SDCARD checking this for 10104
,09-06 19:09:41.051  6391  6391 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:41.051  6391  6391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 19:09:41.061  1014  1137 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6391 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-06 19:09:41.061  1014  1137 I ActivityManager: Killing 5435:com.google.android.partnersetup/u0a15 (adj 15): empty #31
09-06 19:09:41.061  6391  6391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:41.061  6391  6391 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.091  6391  6391 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:41.091  6391  6391 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:41.111  6391  6391 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 19:09:41.271   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:41.291  6391  6414 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-06 19:09:41.291  6391  6414 I Babel   : MmsConfig.loadMmsSettings
,09-06 19:09:41.291  6391  6414 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-06 19:09:41.291  6391  6414 I Babel   : MmsConfig.loadFromDatabase
,09-06 19:09:41.301  6391  6414 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-06 19:09:41.301  6391  6414 I Babel   : MmsConfig.loadFromResources
,09-06 19:09:41.311  6391  6414 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 19:09:41.311  6391  6414 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-06 19:09:41.311  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-06 19:09:41.311  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.311  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.311  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.311  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:41.321  6391  6391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:41.361  6391  6391 I Babel_StickerModule: App launched.
,09-06 19:09:41.381   282  1138 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-06 19:09:41.381   282  1138 W QCamera2Factory: getCameraInfo: X
,09-06 19:09:41.381   282   691 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,09-06 19:09:41.381   282   691 W QCamera2Factory: getCameraInfo: X
,09-06 19:09:41.401  6391  6391 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 19:09:41.401  6391  6391 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:41.401  6391  6391 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 19:09:41.411  6391  6391 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 19:09:41.431  6391  6391 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:41.431  6391  6391 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:41.431  6391  6391 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 19:09:41.441  6391  6391 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 19:09:41.441  6391  6391 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 19:09:41.441  6391  6391 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 19:09:41.441  6391  6391 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 19:09:41.451  6391  6391 W VideoCapabilities: Unsupported mime video/mp43
,09-06 19:09:41.451  6391  6391 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 19:09:41.451  6391  6391 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 19:09:41.471  6391  6391 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 19:09:41.491  1014  3244 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-06 19:09:41.491  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-06 19:09:41.491  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.491  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:41.491  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 19:09:41.501  1014  1374 I ActivityManager: Killing 5745:com.sec.pcw.device/1000 (adj 15): empty #31
,09-06 19:09:41.611  1014  1369 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:41.611  1014  1369 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4212, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-06 19:09:41.611  1014  1369 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-06 19:09:41.611  1014  1369 D BatteryService: stay LED for charging
09-06 19:09:41.611  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:09:41.611  1014  1014 I MotionRecognitionService: Plugged
09-06 19:09:41.611  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:41.611  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:09:41.611  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:09:41.611  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:09:41.611  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:09:41.631  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 19:09:41.631  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-06 19:09:41.641  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.641  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:41.641  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.641  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2,
09-06 19:09:41.641  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.641  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:41.641  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.641  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.641  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:41.651   277  1008 D EnterpriseController: uids 10012,
09-06 19:09:41.651  1014  1127 E NetdConnector: NDC Command {53 network destroy 502} took too long (868ms)
09-06 19:09:41.651   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:41.651  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-06 19:09:41.651   277  1008 D Netd    : getNetworkForDns: using netid 0 for uid 10012
09-06 19:09:41.651  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-06 19:09:41.651   277  1008 D EnterpriseController: uids 1000
09-06 19:09:41.651  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:09:41.651   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:09:41.651  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 19:09:41.651   277  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-06 19:09:41.651  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-06 19:09:41.651   277  1012 D CommandListener: Clearing all IP addresses on wlan0
09-06 19:09:41.651  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:09:41.651  1171  1737 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:09:41.651  3771  6226 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 19:09:41.651  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:09:41.651  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.651  1458  1458 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-06 19:09:41.661  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:09:41.661  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 19:09:41.661  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 19:09:41.661  1014  2216 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:41.661  1934  1934 E ctxmgr  : [BaseServerTask]Server task (WriteInterestRecordTask) got error response.
,09-06 19:09:41.661  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 19:09:41.671  2100  2100 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:41.671  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
,09-06 19:09:41.671  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:09:41.671  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 19:09:41.671  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:09:41.671  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:41.671  1934  2116 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
,09-06 19:09:41.681  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:09:41.681  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:09:41.681  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.681  1014  1128 D Tethering: MasterInitialState.processMessage what=3
09-06 19:09:41.681  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:41.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 19:09:41.681  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.681  1014  1122 V NetworkStats: updateIfacesLocked()
,09-06 19:09:41.681  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:41.691  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:41.691  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:09:41.691  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:09:41.691  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:09:41.691  1171  1171 D StatusBar.NetworkController: updateDataNetType()
,09-06 19:09:41.691  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:09:41.691  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-06 19:09:41.691  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:41.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.691  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-06 19:09:41.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.691  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.691  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 19:09:41.691  1014  1122 V NetworkStats: performPollLocked() took 11ms
09-06 19:09:41.691  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:09:41.701  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:41.701  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:09:41.701  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:41.701  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:41.701  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 19:09:41.711  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.711  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:41.711  1171  1171 D HotspotTile: onReceive : 0, 0
,09-06 19:09:41.711  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:41.711  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.711  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:41.711  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:41.711  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:41.711  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:41.711  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:41.711  1014  1485 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:41.711  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:41.711  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.711  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.721  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:41.721  3680  3680 I Hs20UtilService: Starting #9
09-06 19:09:41.721  3680  3696 I Hs20UtilService: Message received 5007
09-06 19:09:41.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.731  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:41.741  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:41.741  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:41.741  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:41.741  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:41.741  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:41.741  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 19:09:41.761  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:41.761  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:41.761  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.761  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.761  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:41.771  3680  3680 I Hs20UtilService: Starting #10
09-06 19:09:41.771  3680  3696 I Hs20UtilService: Message received 5011
09-06 19:09:41.771  1014  1369 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
09-06 19:09:41.771  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.771  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.771  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:41.771  1014  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:41.781  6421  6421 E Zygote  : MountEmulatedStorage(),
,09-06 19:09:41.791  6421  6421 E Zygote  : v2,
09-06 19:09:41.791  6421  6421 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:41.791  6421  6421 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:41.791  1014  1369 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6421 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-06 19:09:41.791  6421  6421 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 19:09:41.791  6421  6421 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-06 19:09:41.801  2100  2100 I wpa_supplicant: Blacklist: Clear (all) ,
09-06 19:09:41.801  6421  6421 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:41.821  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.831  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.831  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.831  6421  6421 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 19:09:41.831  6421  6421 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:41.831  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.841  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.841  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.841  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.841  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-06 19:09:41.841  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.841  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.841  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.841  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.841  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.851  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.851  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.851  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.851  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.851  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.851  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.851  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.861  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.861  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.861  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.861  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 19:09:41.861  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.861  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.861  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.861  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.861  1458  1458 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 19:09:41.861  1458  1458 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 19:09:41.871  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:41.871  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:41.871  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:41.881  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:41.881  1014  3244 I ActivityManager: Killing 5525:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-06 19:09:41.881  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:41.881  2100  2100 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 19:09:41.881  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:41.881  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:41.881  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.881  1014  3243 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.881  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.891  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.891  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.891  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.891  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.891  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:41.891  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.901  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.901  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.901  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.901  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.901  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:41.901  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-06 19:09:41.901  2100  2100 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 19:09:41.911  2100  2100 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 19:09:41.911  2100  2100 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 19:09:41.911  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.911  2100  2100 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 19:09:41.911  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.911  2100  2100 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-06 19:09:41.911  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.911  1014  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:09:41.911  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-06 19:09:41.911  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.911  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:41.911  1014  1128 E Tethering: No numeric data
,09-06 19:09:41.911  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.911  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.911  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.911  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,09-06 19:09:41.911  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:41.911  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:41.911  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-06 19:09:41.911  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:41.911  1014  1128 D Tethering: clearTetheredNotification()
,09-06 19:09:41.911  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.911  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:09:41.921  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:09:41.921  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:09:41.921  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:41.921  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:09:41.921  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:41.921  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.921  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.921  1014  1122 V NetworkStats: performPollLocked() took 5ms,
09-06 19:09:41.921  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.921  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:41.921  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:41.921  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.921  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.921  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.931  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.931  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.931  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:41.931  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.941  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.941  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.941  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.941  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.951  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:41.951  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:41.951  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 19:09:41.961   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb85137c8
09-06 19:09:41.961   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-06 19:09:41.961   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 19:09:41.961   272   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1202637512)
,09-06 19:09:42.001   272   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
09-06 19:09:42.001   272   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 19:09:42.001   272   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1202637512) wakelock released: 1, error no: 0
09-06 19:09:42.001   272   346 I rmt_storage: 
09-06 19:09:42.001   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb85137c8
,09-06 19:09:42.121  2100  2100 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:09:42.161  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.171  1014  1014 I ApplicationPolicy: updateDataUsageMap,
,09-06 19:09:42.181  3147  3147 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-06 19:09:42.181  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.191  3147  3147 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
09-06 19:09:42.191  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 19:09:42.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.191  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.191  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.191  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.191  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.221  6453  6453 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.221  6453  6453 E Zygote  : v2
09-06 19:09:42.221  6453  6453 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:42.221  6453  6453 I libpersona: KNOX_SDCARD not a persona,
,09-06 19:09:42.221  1014  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
09-06 19:09:42.221  6453  6453 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 19:09:42.231  6453  6453 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.231  6453  6453 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.241  6453  6453 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-06 19:09:42.251  6453  6453 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.271  2100  2100 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 19:09:42.271  6453  6453 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-06 19:09:42.281  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:42.271  6453  6453 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-06 19:09:42.271  6453  6453 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
09-06 19:09:42.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
09-06 19:09:42.281  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 19:09:42.281  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:42.291  6453  6453 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
09-06 19:09:42.291  6453  6453 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:09:42.291  6453  6453 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:09:42.291  6453  6453 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.291  1014  1374 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-06 19:09:42.291  1014  1374 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:09:42.291  1014  1374 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-06 19:09:42.291  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.291  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.291  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.291  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.301  6453  6468 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-06 19:09:42.311  6470  6470 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.311  6470  6470 E Zygote  : v2
09-06 19:09:42.311  6470  6470 I libpersona: KNOX_SDCARD checking this for 10111
09-06 19:09:42.311  6470  6470 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.311  6470  6470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:42.311  6470  6470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.321  6470  6470 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:09:42.321  1014  1374 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6470 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:42.321  1014  1374 I ActivityManager: Killing 5458:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-06 19:09:42.321  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 19:09:42.321  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.321  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.321  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.321  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.341  6482  6482 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.341  1014  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6482 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:09:42.341  6482  6482 E Zygote  : v2
09-06 19:09:42.341  6482  6482 I libpersona: KNOX_SDCARD checking this for 10009
09-06 19:09:42.341  6482  6482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 19:09:42.341  6482  6482 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:42.351  1720  1720 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:09:42.351  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 19:09:42.351  6482  6482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.351  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.351  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.351  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.351  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.351  6482  6482 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.351  6470  6470 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.351  6470  6470 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.361  6494  6494 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.361  6494  6494 E Zygote  : v2
09-06 19:09:42.361  6494  6494 I libpersona: KNOX_SDCARD checking this for 10145
09-06 19:09:42.361  6494  6494 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.371  6494  6494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:42.371  6494  6494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.371  1014  1040 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6494 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-06 19:09:42.371  6482  6482 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.371  6494  6494 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:42.371  6482  6482 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.381  1720  1720 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-06 19:09:42.381  1720  1720 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-06 19:09:42.381  1720  1720 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-06 19:09:42.381  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 19:09:42.381  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 19:09:42.381  1720  1720 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
09-06 19:09:42.381  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:09:42.391  1295  1307 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
09-06 19:09:42.391  6391  6391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:42.391  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:42.391  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:42.391  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.391  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.391  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:42.391  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:42.401  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:42.401  1720  1720 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-06 19:09:42.401  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 19:09:42.401  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:42.401  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:42.401  1934  2122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:42.401  1171  1171 D HotspotTile: onReceive : 1, 0
,09-06 19:09:42.401  1720  1720 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-06 19:09:42.411  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:42.411  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.411  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:42.411  1014  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 19:09:42.411  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.411  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.411  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.411  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.431  6515  6515 E Zygote  : MountEmulatedStorage()
,09-06 19:09:42.431  6515  6515 E Zygote  : v2
09-06 19:09:42.431  6515  6515 I libpersona: KNOX_SDCARD checking this for 10081
09-06 19:09:42.431  6515  6515 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.431  6515  6515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:42.431  1014  1485 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6515 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 19:09:42.431  6515  6515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.431  6515  6515 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.431  6494  6494 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.431  6494  6494 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.451   302   302 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 23.065ms
09-06 19:09:42.451  1720  1720 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-06 19:09:42.461  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 19:09:42.461  6515  6515 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.471   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 965us total 18.174ms
,09-06 19:09:42.471  6494  6494 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 19:09:42.481  6494  6494 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:42.481  6494  6494 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-06 19:09:42.481  6494  6494 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 19:09:42.481  6494  6494 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 19:09:42.491   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 18.657ms
,09-06 19:09:42.521  1014  3244 I ActivityManager: Killing 5070:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-06 19:09:42.521  6470  6470 I MusicStore: Database version: 108
,09-06 19:09:42.531  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:09:42 GMT+02:00 2016
,09-06 19:09:42.531  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:09:42.531  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.531  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.531  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:42.531  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:09:42.531  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:09:42.541  1014  1374 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 19:09:42.541  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.541  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.541  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.541  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.551  3699  3699 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 19:09:42.551  3699  3699 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:09:42.551  3699  3699 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:09:42.551  3699  6535 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:09:42.551  6536  6536 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.551  6536  6536 E Zygote  : v2
09-06 19:09:42.551  6536  6536 I libpersona: KNOX_SDCARD checking this for 10034
09-06 19:09:42.551  6536  6536 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.561  6536  6536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:42.561  6536  6536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-06 19:09:42.561  1014  1546 D RCPManagerService: exchangeData() failure , invalid userId
09-06 19:09:42.561  1014  1374 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6536 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
09-06 19:09:42.561  3699  6535 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:09:42.571  6536  6536 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.571  3699  6535 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 19:09:42.571  3699  6535 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-06 19:09:42.571  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:42.581  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 19:09:42.581  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.581  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.581  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:42.591  6536  6536 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.591  6536  6536 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.591  1014  3243 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.601  3699  3699 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-06 19:09:42.631  6536  6536 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 19:09:42.651  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 19:09:42.651  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.651  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.651  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.651  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.661  6557  6557 E Zygote  : MountEmulatedStorage(),
09-06 19:09:42.661  6557  6557 E Zygote  : v2
09-06 19:09:42.661  6557  6557 I libpersona: KNOX_SDCARD checking this for 10113
09-06 19:09:42.661  6557  6557 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.661  6557  6557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:42.661  1014  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6557 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:42.671  1014  1027 I ActivityManager: Killing 4107:com.sec.spp.push/u0a35 (adj 15): empty #31
,09-06 19:09:42.671  6557  6557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:42.671  6557  6557 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.671  6470  6470 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 19:09:42.671  6470  6470 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 19:09:42.671  3248  6564 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-06 19:09:42.681  3248  6564 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 19:09:42.681  3248  6564 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 19:09:42.681  3248  6564 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 19:09:42.681  3248  6564 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:09:42.691  1014  1137 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.691  6557  6557 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.691  6557  6557 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.701  1014  1369 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.711  5990  5990 I SA      : [DM] init START
,09-06 19:09:42.721  5990  5990 I SA      : [DM] This device is not a Vodafone
,09-06 19:09:42.721  6470  6470 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 19:09:42.721  5990  5990 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-06 19:09:42.741  5990  5990 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75),
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: No package identifier when getting value for resource number 0x00000000,
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75),
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-06 19:09:42.751  5990  5990 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75),
09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-06 19:09:42.771  5990  5990 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-06 19:09:42.781  5882  5890 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 19:09:42.791  1014  3243 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.791  5990  5990 I SA      : [SCU] isHaveSA() - false
,09-06 19:09:42.791  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
09-06 19:09:42.791  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-06 19:09:42.791  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-06 19:09:42.791  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=1123)
,09-06 19:09:42.791  1014  1546 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.791  6470  6470 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 19:09:42.791  6470  6470 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@34c27255: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 19:09:42.791  6470  6470 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-06 19:09:42.791  6470  6470 D AndroidMusic: GMSCore installation verified
,09-06 19:09:42.801  5990  5990 I SA      : support phone number id : false
,09-06 19:09:42.801  5990  5990 I SA      : [DM] Supports Ref Jpn : true
,09-06 19:09:42.801  5990  5990 I SA      : [DM] init END
,09-06 19:09:42.801  5990  5990 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-06 19:09:42.801  5990  5990 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-06 19:09:42.801  5990  5990 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:09:42.811  5990  5990 I SA      : [SLFUCHKMGR] constructor called
,09-06 19:09:42.811  5990  5990 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 19:09:42.821  5990  5990 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:09:42.821  5990  5990 I SA      : [SCU] == networkStateCheck == false
09-06 19:09:42.821  5990  5990 I SA      : [OR] onReceive END
,09-06 19:09:42.821  1476  1476 D Launcher.Model: reloadBadges entered.
,09-06 19:09:42.821  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
09-06 19:09:42.821  5882  5890 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-06 19:09:42.821  5882  5890 D BadgeProvider: sendNotify, [notify] : null
09-06 19:09:42.821  5882  5890 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 19:09:42.821  5882  5890 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 19:09:42.821  5882  5890 D BadgeProvider: update, [UpdateCount] : 1
,09-06 19:09:42.831  1014  3243 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:42.831  1014  3243 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-06 19:09:42.831  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.831  1014  3243 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.831  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:42.831  1014  3244 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:09:42.831  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:42.851  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:42.851  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:42.851  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:42.851  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:42.851  1014  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-06 19:09:42.851  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.851  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.861  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:42.861  1014  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:42.871  1014  1485 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6583 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:42.881  6470  6470 I ConfigStore: Config Database version: 1,
09-06 19:09:42.881  6583  6583 E Zygote  : MountEmulatedStorage()
09-06 19:09:42.881  6583  6583 I libpersona: KNOX_SDCARD checking this for 10159
09-06 19:09:42.881  6583  6583 E Zygote  : v2
09-06 19:09:42.881  6583  6583 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:42.881  6583  6583 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 19:09:42.881  6583  6583 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:09:42.881  6583  6583 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-06 19:09:42.901  1014  2724 D SSRM:n  : SIOP:: AP = 350,
,09-06 19:09:42.921  1014  1042 D Tethering: interfaceRemoved wlan0
09-06 19:09:42.921  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:42.931  6583  6583 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:42.931  6583  6583 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:42.961  1014  1137 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 19:09:42.961  1014  1137 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:42.961  1014  1137 D SecContentProvider2: mCursor = null
,09-06 19:09:42.961  1014  1137 D WifiService: setWifiEnabled: true pid=6164, uid=10155
09-06 19:09:42.961  1014  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:42.961  1014  1137 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:09:42.961  1014  1137 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:42.961  1014  1137 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 19:09:42.961  1014  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:09:42.961  1014  1137 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:09:42.961  1014  1137 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:09:42.961  1014  1137 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:09:42.961  1014  1137 D SettingsProvider: name = wifi_on
,09-06 19:09:42.991  1014  1543 I ActivityManager: Killing 5778:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-06 19:09:42.991  1014  1315 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:42.991  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:09:42.991  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:42.991  1014  1315 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:42.991  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.001  3771  3771 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 19:09:43.011  1014  3245 I art     : Explicit concurrent mark sweep GC freed 52251(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.893ms total 180.370ms
,09-06 19:09:43.021  3771  4526 I iu.UploadsManager: num queued entries: 0
,09-06 19:09:43.021  3771  4526 I iu.UploadsManager: num updated entries: 0
09-06 19:09:43.021  3771  4526 I iu.SyncManager: NEXT; no task
,09-06 19:09:43.041  1014  1546 I ActivityManager: Killing 5792:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-06 19:09:43.061   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 19:09:43.061   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.061  6470  6470 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 19:09:43.061   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 19:09:43.061   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.061  6470  6470 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 19:09:43.061   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 19:09:43.061   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.061  6470  6470 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 19:09:43.071  1014  1042 D Tethering: interfaceRemoved p2p0
09-06 19:09:43.071  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:43.071  1014  1471 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-06 19:09:43.071  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.071  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.071  1014  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:43.071  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.081   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:09:43.081   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.081  6557  6604 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:43.081   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:43.081   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.091  6557  6604 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:09:43.091  1014  3244 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 19:09:43.091  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-06 19:09:43.091  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.091  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.091  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.101   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 19:09:43.101   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.101  6557  6609 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 19:09:43.111   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 19:09:43.111   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 19:09:43.111  6557  6609 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 19:09:43.111  1014  1315 I ActivityManager: Killing 5494:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-06 19:09:43.131  1014  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:43.141  1014  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:43.141  1014  1315 I AudioService: getStreamVolume 3 index 0
,09-06 19:09:43.151  6470  6470 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-06 19:09:43.151  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-06 19:09:43.151  1014  1485 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 19:09:43.151  6470  6470 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-06 19:09:43.151  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.161  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.171  1014  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:43.171  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 19:09:43.171  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:43.171  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.171  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.181  1014  1369 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:43.181  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.181  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.181  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.181  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.181  1014  3245 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 19:09:43.181  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.181  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:43.181  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.181  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.191  1014  1471 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:43.201  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 19:09:43.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.201  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.211  6625  6625 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.211  6625  6625 I libpersona: KNOX_SDCARD checking this for 10002
09-06 19:09:43.211  6625  6625 E Zygote  : v2
09-06 19:09:43.211  6625  6625 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.221  6625  6625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:43.221  6625  6625 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:43.221  6625  6625 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 19:09:43.221  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6625 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 19:09:43.241  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-06 19:09:43.241  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 19:09:43.241  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.241  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.241  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.251  6625  6625 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.251  6625  6625 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.251  1014  3243 I ActivityManager: Killing 5828:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-06 19:09:43.261  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:43.261  6470  6470 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-06 19:09:43.261  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:43.261  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.261  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:09:43.271  1014  1374 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:43.271  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 19:09:43.271  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.271  1014  1374 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:43.271  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:43.281  6557  6557 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-06 19:09:43.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:43.281   287   287 E SMD     : DCD OFF
,09-06 19:09:43.291  6557  6557 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7785-7787)
,09-06 19:09:43.291  6557  6557 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:09:43.301  6557  6557 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23ef76c2}
,09-06 19:09:43.301  6557  6557 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 19:09:43.301  6557  6557 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 19:09:43.321  6557  6557 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 19:09:43.321  6557  6557 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 19:09:43.321  6557  6557 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 19:09:43.321  1014  1543 I ActivityManager: Killing 5761:com.android.mms/u0a46 (adj 15): empty #31
,09-06 19:09:43.331  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 19:09:43.331  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.331  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.331  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.331  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.341  6646  6646 E Zygote  : MountEmulatedStorage()
09-06 19:09:43.341  6646  6646 E Zygote  : v2
09-06 19:09:43.341  6646  6646 I libpersona: KNOX_SDCARD checking this for 1000
09-06 19:09:43.341  6646  6646 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.341  6646  6646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:43.351  6646  6646 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:43.351  1014  1027 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6646 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-06 19:09:43.351  6646  6646 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.351  6557  6557 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-06 19:09:43.361  6557  6557 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-06 19:09:43.361  6557  6557 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-06 19:09:43.361  6557  6557 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 19:09:43.361  6557  6557 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 19:09:43.361  6557  6557 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 19:09:43.361  6557  6557 I Adreno-EGL: Local Branch: 
09-06 19:09:43.361  6557  6557 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 19:09:43.361  6557  6557 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 19:09:43.361  6557  6557 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 19:09:43.361  6646  6646 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.371  6646  6646 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.401  6646  6646 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 19:09:43.421  6557  6672 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 19:09:43.421  6557  6557 I NSApplication: Starting up...
,09-06 19:09:43.441  1014  1471 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 19:09:43.441  1014  3245 D CountryDetector: No listener is left
,09-06 19:09:43.451  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.451  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.451  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.451  1014  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.461  6677  6677 E Zygote  : MountEmulatedStorage(),
09-06 19:09:43.461  6677  6677 I libpersona: KNOX_SDCARD checking this for 10120
09-06 19:09:43.461  6677  6677 E Zygote  : v2
09-06 19:09:43.461  6677  6677 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:43.461  6677  6677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:43.461  6677  6677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-06 19:09:43.461  6677  6677 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 19:09:43.461  1014  1471 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6677 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-06 19:09:43.461  1014  1471 I ActivityManager: Killing 5943:com.wsomacp/u0a25 (adj 15): empty #31
,09-06 19:09:43.471  1014  1471 I ActivityManager: Killing 5906:com.sec.android.app.myfiles/u0a47 (adj 15): empty #32
,09-06 19:09:43.481  6677  6677 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.481  6677  6677 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.501  6677  6677 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:43.541  6646  6646 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-06 19:09:43.551  6646  6646 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 19:09:43.551  6646  6646 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.551  6646  6646 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:09:43.551  6646  6646 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 19:09:43.551  6646  6646 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 19:09:43.561  1014  1369 I ActivityManager: Killing 5808:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-06 19:09:43.771  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:09:43.771  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:09:43.781  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 19:09:43.791  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.791  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.791  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:43.791  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:43.811  6698  6698 E Zygote  : MountEmulatedStorage()
,09-06 19:09:43.811  6698  6698 E Zygote  : v2
09-06 19:09:43.811  6698  6698 I libpersona: KNOX_SDCARD checking this for 10125
09-06 19:09:43.811  6698  6698 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:43.821  6698  6698 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 19:09:43.821  1014  1026 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6698 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-06 19:09:43.821  1014  1026 I ActivityManager: Killing 5969:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-06 19:09:43.821  6698  6698 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:09:43.821  6698  6698 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 19:09:43.841  6698  6698 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:43.841  6698  6698 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:43.851  6698  6698 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 19:09:43.861  6698  6698 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 19:09:43.861  6698  6698 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:43.871  6698  6698 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:09:43.871  6698  6698 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:09:43.871  6698  6698 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:09:43.871  1014  1374 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 19:09:43.881  1014  1374 I ActivityManager: Killing 5843:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-06 19:09:43.881  1014  3245 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:43.881  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:43.881  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:43.881  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:43.881  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:43.891  3680  3680 I Hs20UtilService: Starting #11
,09-06 19:09:43.891  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:09:43.891  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:43.891  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:43.891  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:09:43.891  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:44.151  1014  1042 D Tethering: interfaceAdded wlan0
,09-06 19:09:44.151  1014  1128 E Tethering: No numeric data
,09-06 19:09:44.151  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:44.161  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:09:44.161  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.161  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:44.161  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:44.161  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:09:44.161  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:09:44.161  1014  1128 D Tethering: clearTetheredNotification()
,09-06 19:09:44.161  1014  1122 V NetworkStats: performPollLocked() took 7ms
,09-06 19:09:44.161  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.171  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.171  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.171  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:44.171  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:09:44.171  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:09:44.171  1014  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:09:44.171  1014  1128 E Tethering: No numeric data
09-06 19:09:44.171  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:09:44.171  1014  1128 D Tethering: clearTetheredNotification()
09-06 19:09:44.181  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:09:44.181  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:09:44.181  1014  1042 D Tethering: interfaceAdded p2p0
09-06 19:09:44.181  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:09:44.181  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:09:44.181  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:09:44.181  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:09:44.181  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:09:44.191  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 19:09:44.191  1014  1042 D Tethering: interfaceStatusChanged p2p0, false,
,09-06 19:09:44.191  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.191  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.191  1014  1122 V NetworkStats: performPollLocked() took 13ms
09-06 19:09:44.191  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.191  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:09:44.191   277  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:09:44.191   277  1012 D SoftapController: Softap fwReload - Ok
,09-06 19:09:44.201   277  1012 D CommandListener: Setting iface cfg
09-06 19:09:44.201   277  1012 D CommandListener: Trying to bring down wlan0
,09-06 19:09:44.201   277  1012 D CommandListener: Clearing all IP addresses on wlan0,
,09-06 19:09:44.201  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant,
,09-06 19:09:44.211  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 19:09:44.211  1014  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-06 19:09:44.221  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:44.221  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:44.221  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:44.221  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:44.221  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:44.221  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.221  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:44.221  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:44.221  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:44.221  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 19:09:44.221  1171  1171 D HotspotTile: onReceive : 2, 0
,09-06 19:09:44.221  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:44.231  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:44.231  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:44.241  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:44.241  1014  1369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:44.241  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:44.241  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:09:44.241  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:44.241  3680  3680 I Hs20UtilService: Starting #12
,09-06 19:09:44.241  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:09:44.251  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:44.251  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:44.251  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:44.251  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:44.281  6720  6720 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-06 19:09:44.281  6720  6720 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 19:09:44.281   310   310 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 19:09:44.281  6720  6720 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,09-06 19:09:44.291  6720  6720 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-06 19:09:44.301   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6720,
09-06 19:09:44.301   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 19:09:44.301  6720  6720 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 19:09:44.301  6720  6720 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:44.301  6720  6720 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:09:44.301  6720  6720 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-06 19:09:44.301   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6720
09-06 19:09:44.301   349   349 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 19:09:44.471   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 19:09:44.481  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-06 19:09:44.541  6720  6720 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:09:44.541  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:09:44.551  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-06 19:09:44.551   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6720
09-06 19:09:44.561   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:09:44.561  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-06 19:09:44.561  6720  6720 I wpa_supplicant: ssSupport state is = 1,
09-06 19:09:44.561  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 19:09:44.561  6720  6720 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:09:44.561  6720  6720 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.561  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.561  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.561  6720  6720 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.561  6720  6720 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.561  6720  6720 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:09:44.561  6720  6720 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:44.561  6720  6720 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:09:44.561  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.561  6720  6720 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:09:44.561  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.561  6720  6720 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:44.561  6720  6720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:09:44.561  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:09:44.561  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:44.641  6720  6720 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:09:44.831  6720  6720 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:44.831  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:09:44.841  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:09:44.841   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6720
,09-06 19:09:44.841   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-06 19:09:44.841  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:09:44.841  6720  6720 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:44.841  6720  6720 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:09:44.841  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 19:09:44.861  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 19:09:44.861   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6720
09-06 19:09:44.861   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-06 19:09:44.861  6720  6720 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 19:09:44.861  6720  6720 I wpa_supplicant: ssSupport state is = 1
09-06 19:09:44.861  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:44.861  6720  6720 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-06 19:09:44.861  6720  6720 E wpa_supplicant: SIM READ ERROR
09-06 19:09:44.861  6720  6720 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:09:44.861  6720  6720 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-06 19:09:44.861  6720  6720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-06 19:09:44.861  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.861  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.861  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:44.861  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:09:44.861  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-06 19:09:44.861  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:44.971  6720  6720 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 19:09:44.971  6720  6720 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:09:45.011  6720  6720 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-06 19:09:45.011  6720  6720 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-06 19:09:45.011  6720  6720 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:09:45.171  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:09:45.171  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:45.171  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:45.211  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:09:45.211  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:45.221  6720  6720 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:09:45.221  6720  6720 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:09:45.221  6720  6720 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:09:45.221  6720  6720 E wpa_supplicant: SIM READ ERROR
09-06 19:09:45.221  6720  6720 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:45.241  6720  6720 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 19:09:45.251  6720  6720 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:09:45.251  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-06 19:09:45.251  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:09:45.251  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:09:45.251  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:45.261  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.261  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:45.261  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:45.261  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:45.261  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-06 19:09:45.261  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:45.261  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:09:45.261  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:45.261  1171  1171 D HotspotTile: onReceive : 3, 0
,09-06 19:09:45.261  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:09:45.271  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:45.271  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.271  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:45.271  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:45.271  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:45.271  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:45.271  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:45.271  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:45.271  1014  3245 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:09:45.271  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:45.271  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:45.271  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:09:45.271  1014  1125 E WifiConfigStore: Not a HS20
,09-06 19:09:45.281  3680  3680 I Hs20UtilService: Starting #13
09-06 19:09:45.281  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:09:45.281  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:09:45.281  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:45.281  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
09-06 19:09:45.281  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:45.281  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:45.281  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:45.281  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:09:45.281  6720  6720 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:09:45.281  6720  6720 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:09:45.281  6720  6720 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:09:45.281  6720  6720 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:09:45.281  6720  6720 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:09:45.281  6720  6720 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:09:45.281  6720  6720 I wpa_supplicant: First Scan Start
,09-06 19:09:45.291  6720  6720 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:09:45.291  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:09:45.291  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:09:45.291  1014  1125 I WifiNative-HAL: startHal
09-06 19:09:45.291  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9cb8a88c
09-06 19:09:45.291  1014  1125 I WifiNative-HAL: Could not start hal
,09-06 19:09:45.291  6391  6391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:09:45.291  1014  1125 E WifiNative-wlan0: do suspend true
,09-06 19:09:45.291  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 19:09:45.291  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 19:09:45.301  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:09:45.301  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-06 19:09:45.301  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:09:45.301  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.301  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-06 19:09:45.301  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:45.301  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-06 19:09:45.301  1014  1149 I WifiNative-HAL: startHal
09-06 19:09:45.301  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9def19bc
09-06 19:09:45.301  1014  1149 I WifiNative-HAL: Could not start hal
09-06 19:09:45.301  1014  1149 E WifiScanningService: could not start HAL
,09-06 19:09:45.301  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:09:45.301  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:09:45.301  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-06 19:09:45.301   277  1012 D CommandListener: Setting iface cfg
,09-06 19:09:45.301   277  1012 D CommandListener: Trying to bring up p2p0
09-06 19:09:45.301  6720  6720 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:09:45.301  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 19:09:45.301  1014  1124 D WifiP2pService: P2pEnablingState
09-06 19:09:45.301  6720  6720 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:09:45.301  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 19:09:45.301  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:09:45.301  1014  1124 D WifiP2pService: P2p socket connection successful
09-06 19:09:45.301  6720  6720 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-06 19:09:45.301  1014  1124 D WifiP2pService: P2pEnabledState
09-06 19:09:45.301  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:09:45.301  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:45.301  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-06 19:09:45.311  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.311  1014  1045 D WifiDisplayController: disconnect
,09-06 19:09:45.311  1014  1045 D WifiDisplayController: updateConnection
09-06 19:09:45.311  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:09:45.311  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:09:45.311  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:45.311  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:09:45.311  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:09:45.311  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:45.311  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:45.311  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:45.311  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:09:45.311  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:09:45.311  1014  1369 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:45.311  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:09:45.311  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:09:45.311  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:09:45.311  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:45.321  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 19:09:45.321  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-06 19:09:45.321  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:45.321  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-06 19:09:45.321  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  secondary type: null
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  wps: 0
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  grpcapab: 0
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  devcapab: 0
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  status: 3
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  wfdInfo: null
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  groupownerAddress: null
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  GOdeviceName: null
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  interfaceAddress: 
09-06 19:09:45.321  1014  1045 D WifiDisplayController:  SConnectInfo : null
,09-06 19:09:45.321  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:09:45.321  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:45.321  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:45.321  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:45.331  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.331  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:09:45.331  6360  6360 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:45.331  6375  6375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:45.341  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:09:45.341  1014  1124 D WifiP2pService: InactiveState
,09-06 19:09:45.341  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-06 19:09:45.341  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.341  6720  6720 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-06 19:09:45.341  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:09:45.341  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:09:45.861  1014  3245 I ActivityManager: Killing 6020:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-06 19:09:45.971  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-06 19:09:45.971  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:09:45.971  1014  1027 D SecContentProvider2: mCursor = null,
,09-06 19:09:45.971  1014  1027 D WifiService: setWifiEnabled: false pid=6164, uid=10155
09-06 19:09:45.971  1014  1027 D SettingsProvider: name = wifi_on
,09-06 19:09:45.981  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-06 19:09:45.981  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-06 19:09:45.981  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,09-06 19:09:45.981  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-06 19:09:45.981  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 19:09:45.981  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:45.981  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:09:45.981  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-06 19:09:45.991  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-06 19:09:45.991  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:45.991  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:45.991  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 19:09:45.991  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:09:45.991  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 19:09:45.991  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:09:45.991  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 19:09:45.991  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-06 19:09:45.991  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.991  1014  1045 D WifiDisplayController: disconnect
09-06 19:09:45.991  1014  1045 D WifiDisplayController: updateConnection
09-06 19:09:45.991  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:09:45.991  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:09:45.991  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:09:46.001  1014  1124 D WifiP2pService: P2pDisablingState
,09-06 19:09:46.001  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 19:09:46.001  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 19:09:46.001  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:09:46.001  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:09:46.001  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:09:46.001  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 19:09:46.001  1014  1124 D WifiP2pService: p2p socket connection lost
,09-06 19:09:46.001  1014  1124 D WifiP2pService: P2pDisabledState
,09-06 19:09:46.001  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:46.001  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:46.001  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:46.001  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 19:09:46.001  1014  1369 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:09:46.001  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 19:09:46.001  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:46.001   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:09:46.011  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:46.011  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:09:46.011  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 19:09:46.011  6360  6360 D FileShare-Client: Outbound.stopDelayTimer - 
09-06 19:09:46.011  6720  6720 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 19:09:46.011  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:46.011  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:09:46.011  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.011  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.011  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.011  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:46.021  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:46.021  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:46.021  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.021  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.021  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.021  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:09:46.021  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:46.021  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 19:09:46.021  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 19:09:46.021  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:46.031  1171  1171 D HotspotTile: onReceive : 0, 0
09-06 19:09:46.031  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:46.031  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
,09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:46.031  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:46.031  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:46.031  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:46.031  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:46.031  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 19:09:46.031  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:46.031  6375  6375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:46.041  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:09:46.041  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:46.041  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:46.041  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:46.041  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:46.041  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:09:46.041  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:46.051  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:46.051  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:09:46.051  6360  6360 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:09:46.051  6375  6375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:09:46.061  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:46.061  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:46.061  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:46.061  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:46.061  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:46.061  3680  3680 I Hs20UtilService: Starting #14
,09-06 19:09:46.071  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:09:46.071  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:09:46.071  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:09:46.071  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:09:46.071  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:09:46.071  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:09:46.071  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:09:46.071  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:09:46.081  1014  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:46.081  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:46.081  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:46.081  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:46.081  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:46.081  3680  3680 I Hs20UtilService: Starting #15
,09-06 19:09:46.081  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:09:46.081  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:09:46.081  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:46.081  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:46.081  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:46.151  6720  6720 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:09:46.291   287   287 E SMD     : DCD OFF,
,09-06 19:09:46.311  6720  6720 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-06 19:09:46.311  6720  6720 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
09-06 19:09:46.311  6720  6720 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
,09-06 19:09:46.311  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:09:46.311  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:09:46.311  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:09:46.621  6720  6720 I wpa_supplicant: Blacklist: Clear (all) ,
,09-06 19:09:46.701  6720  6720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-06 19:09:46.701  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:09:46.701  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:09:46.701  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:09:46.811  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 19:09:46.811  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 19:09:46.811  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:09:46.811  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:09:46.811  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:09:46.811  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 19:09:46.811  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.811  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.821  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:09:46.811  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:09:46.821  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:09:46.821  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 19:09:46.821  6391  6391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 19:09:46.821  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:09:46.821  1171  1171 D HotspotTile: onReceive : 1, 0
,09-06 19:09:46.821  1934  2122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-06 19:09:46.821  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.831  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
09-06 19:09:46.831  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:46.831  1014  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:09:46.831  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:09:46.831  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:46.831  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:46.831  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:09:46.841  3680  3680 I Hs20UtilService: Starting #16
,09-06 19:09:46.841  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:09:46.851  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:09:46.851  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:09:46.861  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:09:46.861  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:09:47.461  1014  1042 D Tethering: interfaceRemoved wlan0
09-06 19:09:47.461  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 19:09:47.591  1014  1042 D Tethering: interfaceRemoved p2p0
,09-06 19:09:47.591  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 19:09:48.071  1014  3245 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-06 19:09:48.071  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-06 19:09:48.071  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.071  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.071  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 19:09:48.081  6557  6605 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-06 19:09:48.131  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:48.131  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.131  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.131  1014  1543 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-06 19:09:48.141  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-06 19:09:48.141  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:48.141  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:48.141  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.151  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:48.151  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:48.151  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.161  1014  1485 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:48.161  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-06 19:09:48.161  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:48.161  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:48.161  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.171  1014  1369 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:48.171  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-06 19:09:48.171  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:48.171  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:48.171  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.181  1014  1137 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:48.181  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 19:09:48.181  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.181  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.181  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.191  1014  3244 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-06 19:09:48.191  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-06 19:09:48.191  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.191  1014  3244 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.191  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.211  1014  1315 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:48.211  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.211  1014  1315 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.211  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-06 19:09:48.221  1934  1934 D WearableService: callingUid 10012, callindPid: 1934
,09-06 19:09:48.231  1014  1471 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 19:09:48.231  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 19:09:48.231  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:48.231  1014  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:48.231  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 19:09:48.251  6470  6734 I MusicLeanback: Conditions not met for autocaching.
,09-06 19:09:48.251  6470  6734 I MusicLeanback: Stop autocaching.
,09-06 19:09:48.271  6470  6470 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-06 19:09:48.281  6470  6739 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-06 19:09:48.311  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 19:09:48.981  6164  6217 D BluetoothAdapter: enable()
,09-06 19:09:48.981  1014  1546 W ActivityManager: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:09:48.981  1014  1546 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-06 19:09:48.981  1014  1546 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:48.981  1014  1546 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:48.981  1014  1546 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:48.991  1014  1546 D SettingsProvider: name = bluetooth_on,
,09-06 19:09:48.991  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:48.991  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:49.001  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
,09-06 19:09:49.001  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-06 19:09:49.001  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:49.001  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:49.001  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:49.001  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:49.021  6741  6741 E Zygote  : MountEmulatedStorage()
,09-06 19:09:49.021  6741  6741 E Zygote  : v2
09-06 19:09:49.021  6741  6741 I libpersona: KNOX_SDCARD checking this for 1002,
09-06 19:09:49.021  6741  6741 I libpersona: KNOX_SDCARD not a persona
,09-06 19:09:49.021  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:49.021  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6741 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:09:49.031  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:49.031  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:09:49.061  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:49.061  6741  6741 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:49.071  6741  6741 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:09:49.071  6741  6741 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:49.101  6741  6741 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding HidService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding PanService
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding SapService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 19:09:49.141  6741  6741 D BtSettings.ProfileConfig: Adding HidDevService
09-06 19:09:49.141  6741  6741 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:09:49.151  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:09:49.151  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.151  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.151  1014  1137 D SettingsProvider: selectionArgs: false
09-06 19:09:49.151  1014  1137 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.151  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.151  1014  1137 D SettingsProvider: ret = -1
,09-06 19:09:49.151  1014  1315 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:49.151  1014  1315 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.151  1014  1315 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.151  1014  1315 D SettingsProvider: selectionArgs: false
09-06 19:09:49.151  1014  1315 D SettingsProvider: selectionArgs: 1002
09-06 19:09:49.151  1014  1315 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.151  1014  1315 D SettingsProvider: ret = -1
,09-06 19:09:49.151  1014  1544 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:49.151  1014  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.151  1014  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.151  1014  1544 D SettingsProvider: selectionArgs: false
09-06 19:09:49.151  1014  1544 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.151  1014  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.151  1014  1544 D SettingsProvider: ret = -1
,09-06 19:09:49.161  1014  3243 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 19:09:49.161  1014  3243 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.161  1014  3243 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.161  1014  3243 D SettingsProvider: selectionArgs: false
09-06 19:09:49.161  1014  3243 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.161  1014  3243 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.161  1014  3243 D SettingsProvider: ret = -1
,09-06 19:09:49.161  1014  1374 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-06 19:09:49.161  1014  1374 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.161  1014  1374 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.161  1014  1374 D SettingsProvider: selectionArgs: false
09-06 19:09:49.161  1014  1374 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.161  1014  1374 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.161  1014  1374 D SettingsProvider: ret = -1
,09-06 19:09:49.161  1014  3245 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-06 19:09:49.161  1014  3245 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.161  1014  3245 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.161  1014  3245 D SettingsProvider: selectionArgs: false
09-06 19:09:49.161  1014  3245 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.161  1014  3245 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.161  1014  3245 D SettingsProvider: ret = -1
,09-06 19:09:49.171  1014  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:49.171  1014  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.171  1014  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.171  1014  1471 D SettingsProvider: selectionArgs: false
09-06 19:09:49.171  1014  1471 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.171  1014  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.171  1014  1471 D SettingsProvider: ret = -1
,09-06 19:09:49.171  1014  1543 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-06 19:09:49.171  1014  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.171  1014  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.171  1014  1543 D SettingsProvider: selectionArgs: false
09-06 19:09:49.171  1014  1543 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.171  1014  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.171  1014  1543 D SettingsProvider: ret = -1
,09-06 19:09:49.171  1014  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:49.171  1014  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.171  1014  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.171  1014  1485 D SettingsProvider: selectionArgs: false
09-06 19:09:49.171  1014  1485 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.171  1014  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.171  1014  1485 D SettingsProvider: ret = -1
,09-06 19:09:49.181  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:49.181  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.181  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.181  1014  1026 D SettingsProvider: selectionArgs: false
09-06 19:09:49.181  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.181  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:49.181  1014  1026 D SettingsProvider: ret = -1
,09-06 19:09:49.181  1014  3244 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:49.181  1014  3244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.181  1014  3244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:49.181  1014  3244 D SettingsProvider: selectionArgs: false
09-06 19:09:49.181  1014  3244 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:49.181  1014  3244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.181  1014  3244 D SettingsProvider: ret = -1
,09-06 19:09:49.181  1014  1546 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
09-06 19:09:49.181  1014  1546 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.181  1014  1546 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:49.181  1014  1546 D SettingsProvider: selectionArgs: false
,09-06 19:09:49.181  1014  1546 D SettingsProvider: selectionArgs: 1002
09-06 19:09:49.181  1014  1546 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.181  1014  1546 D SettingsProvider: ret = -1
,09-06 19:09:49.201  6741  6741 D BluetoothAdapterState: make
,09-06 19:09:49.201  6741  6741 I bluedroid: init,
09-06 19:09:49.211  6741  6756 I BluetoothAdapterState: Entering OffState
,09-06 19:09:49.211  6741  6741 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:09:49.211  6741  6741 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 19:09:49.211  6741  6741 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 19:09:49.211  6741  6741 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:09:49.211  6741  6741 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-06 19:09:49.211  6741  6741 I bluedroid: get_profile_interface socket,
09-06 19:09:49.211  6741  6741 I bluedroid: get_profile_interface map_client
09-06 19:09:49.211  6741  6759 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:09:49.221  6741  6759 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-06 19:09:49.221  6741  6759 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:49.221  6741  6759 I bluedroid: getModelRssiValues
09-06 19:09:49.221  6741  6759 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:49.221  6741  6759 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:49.221  6741  6741 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:09:49.221  6741  6759 D BluetoothAdapterProperties: Name is: A5-1
,09-06 19:09:49.221  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 19:09:49.231  6741  6741 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:49.231  1014  1485 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:49.231  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.231  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.231  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.231  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.241  6741  6755 I bluedroid: config_hci_snoop_log
,09-06 19:09:49.241  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-06 19:09:49.241  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:09:49.241  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 19:09:49.241  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 19:09:49.241  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:49.251  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:49.251  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:49.251  6741  6741 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:09:49.251  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:49.251  6741  6756 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:09:49.251  6741  6756 D BluetoothAdapterProperties: Setting state to 11
09-06 19:09:49.251  6741  6756 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 19:09:49.251  6741  6756 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:49.251  6741  6756 D BluetoothAdapterService: updateAdapterState state is 11
09-06 19:09:49.261  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:49.261  6741  6756 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:49.261  6741  6756 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:09:49.261  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:49.261  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:49.271  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:49.271  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:49.271  1171  1171 D BluetoothTile:  getBluetoothState : 11
,09-06 19:09:49.271  1792  1792 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:49.271  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:49.271  6741  6756 D BluetoothSecureManager: getInstant: null
,09-06 19:09:49.271  6741  6756 D BluetoothSecureManager: calling getMethod for getService
09-06 19:09:49.271  6741  6756 D BluetoothSecureManager: calling getService
,09-06 19:09:49.271  1014  3245 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:49.271  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.281  6741  6756 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@37e83f6f
,09-06 19:09:49.281  1014  1546 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:09:49.281  1014  1546 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 19:09:49.281  6741  6756 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:49.281  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.281  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:49.281  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:49.281  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:49.281  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:49.281  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:09:49.281  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:49.281  1014  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:49.281  1014  3243 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 19:09:49.281  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:09:49.281  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:49.281  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:49.281  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:09:49.281  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:49.281  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:49.291  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:49.291  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:49.291   287   287 E SMD     : DCD OFF
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:49.291  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 19:09:49.291  6741  6756 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:09:49.291  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:49.291  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:49.301  6741  6756 D BluetoothBondStateMachine: make
,09-06 19:09:49.301  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:49.301  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:49.301  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 19:09:49.311  6741  6762 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:09:49.311  1014  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:49.311  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.311  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.311  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.311  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.311  6741  6741 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:49.311  6741  6741 D BtGatt.GattService: Received start request. Starting profile...
,09-06 19:09:49.311  6741  6741 D BtGatt.GattService: start()
09-06 19:09:49.311  6741  6741 D BtGatt.GattService: start()
,09-06 19:09:49.311  6741  6741 I bluedroid: get_profile_interface gatt
,09-06 19:09:49.311  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:49.311  6741  6741 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:09:49.321  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:49.321  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:49.321  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:49.321  1014  1369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.321  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.321  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.321  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.321  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.321  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:49.321  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:49.321  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:49.331  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.331  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.331  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.331  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.331  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.331  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:49.331  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:49.331  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:49.331  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.331  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.331  6741  6741 D BtGatt.GattService: mStartError = false
09-06 19:09:49.331  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:49.331  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.331  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.331  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.331  6741  6741 D HeadsetService: Received start request. Starting profile...
09-06 19:09:49.331  6741  6741 D HeadsetService: start()
,09-06 19:09:49.341  6741  6741 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:09:49.341  6741  6741 D HeadsetStateMachine: make
,09-06 19:09:49.341  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:49.341  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:49.341  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:49.341  1014  1369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.341  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.341  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.341  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.341  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.341  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:09:49.351  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:49.351  6741  6741 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:09:49.351  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:49.351  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:49.351  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 19:09:49.351  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.351  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:49.351  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.351  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.361  1014  1544 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 19:09:49.361  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-06 19:09:49.361  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:49.361  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:49.361  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:49.361  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.361  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.361  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:49.361  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.361  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.361  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.361  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:49.361  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.361  1014  1374 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-06 19:09:49.361  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.361  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:49.361  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:49.361  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-06 19:09:49.371  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:49.371  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:09:49.371  6741  6756 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:49.371  6741  6741 I bluedroid: get_profile_interface handsfree,
09-06 19:09:49.371  1014  1315 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:49.371  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:49.371  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:49.371  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:49.371  1014  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:49.371  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:49.391  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:49.391  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:49.391  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:49.391  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:49.391  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:49.391  6741  6756 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:09:49.391  6741  6741 I DualScoManager: Instantiating Dual Sco Manager
09-06 19:09:49.391  6741  6741 I DualScoManager: Set HeadsetServiceHelper
09-06 19:09:49.391  6741  6741 D BluetoothAtMessage: createCMTIContentObservers
09-06 19:09:49.391  1014  3244 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 19:09:49.391  1014  3244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:49.391  1014  3244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:49.391  1014  3244 D SettingsProvider: selectionArgs: false
09-06 19:09:49.391  1014  3244 D SettingsProvider: selectionArgs: 1002
09-06 19:09:49.391  1014  3244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:49.391  1014  3244 D SettingsProvider: ret = -1
09-06 19:09:49.391  6741  6768 D HeadsetStateMachine: Enter Disconnected: -2
09-06 19:09:49.391  6741  6741 D HeadsetService: mStartError = false
09-06 19:09:49.391  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.391  6741  6768 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:49.391  6741  6768 D HeadsetStateMachine: map size, before remove : 0
09-06 19:09:49.391  6741  6768 D HeadsetStateMachine: map size, after remove: 0
09-06 19:09:49.401  6741  6741 D A2dpService: Received start request. Starting profile...
09-06 19:09:49.401  6741  6741 D A2dpService: start()
09-06 19:09:49.401  6741  6741 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-06 19:09:49.401  6741  6741 I bluedroid: get_profile_interface avrcp
09-06 19:09:49.401  6741  6741 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-06 19:09:49.421  6741  6741 I Avrcp   :  Updating now playing list upon AVRCP Start
09-06 19:09:49.421  6741  6769 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-06 19:09:49.421  6741  6741 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 19:09:49.421  6741  6741 D A2dpStateMachine: make
,09-06 19:09:49.421  6741  6741 I bluedroid: get_profile_interface a2dp
09-06 19:09:49.421  6741  6771 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:09:49.421  6741  6741 E bt-btif : warning : media task started media_task_refcnt 1 
09-06 19:09:49.431  6741  6741 D A2dpService: mStartError = false
09-06 19:09:49.431  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.431  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-06 19:09:49.431  6741  6741 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:09:49.431  6741  6770 D A2dpStateMachine: Enter Disconnected: -2
09-06 19:09:49.431  6741  6741 D HidService: Received start request. Starting profile...
09-06 19:09:49.431  6741  6741 D HidService: start()
09-06 19:09:49.431  6741  6741 I bluedroid: get_profile_interface hidhost
09-06 19:09:49.431  6741  6741 D HidService: setHidService(): set to: null
09-06 19:09:49.431  6741  6741 D HidService: mStartError = false
09-06 19:09:49.431  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.431  6741  6741 I BluetoothHealthServiceJni: classInitNative: succeeds
09-06 19:09:49.431  6741  6741 D HealthService: Received start request. Starting profile...
09-06 19:09:49.431  6741  6741 D HealthService: start()
09-06 19:09:49.431  6741  6741 I bluedroid: get_profile_interface health
09-06 19:09:49.431  6741  6741 D HealthService: mStartError = false
09-06 19:09:49.431  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.431  6741  6741 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-06 19:09:49.441  6741  6741 D PanService: Received start request. Starting profile...
09-06 19:09:49.441  6741  6741 D PanService: start()
09-06 19:09:49.441  6741  6741 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:49.441  6741  6741 I bluedroid: get_profile_interface pan
09-06 19:09:49.441  6741  6769 D BluetoothMediaBrowser: no now playing list
09-06 19:09:49.441  6741  6769 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-06 19:09:49.441  6741  6741 D PanService: mStartError = false
09-06 19:09:49.441  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.441  6741  6741 D HeadsetStateMachine: Try to query the phonestate on bind
09-06 19:09:49.441  1429  1437 I Telecom : BluetoothPhoneService: queryPhoneState
09-06 19:09:49.441  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 19:09:49.441  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:09:49.441  1429  1437 I Telecom : BluetoothPhoneService: Result of Message : true
09-06 19:09:49.451  6741  6741 D BluetoothMapService: Received start request. Starting profile...
09-06 19:09:49.451  6741  6741 D BluetoothMapService: start()
09-06 19:09:49.451  6741  6741 D BluetoothMapService: mStartError = false
09-06 19:09:49.451  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.451  6741  6741 D HeadsetStateMachine: Proxy object connected
09-06 19:09:49.451  6741  6741 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 19:09:49.451  6741  6768 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:49.451  6741  6741 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
09-06 19:09:49.451  6741  6741 D SapService: Received start request. Starting profile...
09-06 19:09:49.451  6741  6741 D SapService: start()
09-06 19:09:49.451  6741  6741 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:09:49.451  6741  6741 I bluedroid: get_profile_interface sap
09-06 19:09:49.451  6741  6741 D SapService: mStartError = false
09-06 19:09:49.451  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:49.451  6741  6741 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 19:09:49.451  6741  6741 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:09:49.451  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:49.451  6741  6741 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:49.451  6741  6741 D BluetoothA2dp: Proxy object connected
09-06 19:09:49.451  6741  6741 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:09:49.451  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:49.451  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 19:09:49.451  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:09:49.451  6741  6768 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:09:49.451  6741  6768 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:09:49.451  6741  6768 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:49.451  6741  6768 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:49.461  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:49.481  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-06 19:09:49.481  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
09-06 19:09:49.481  6741  6756 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-06 19:09:49.481  6741  6756 I bluedroid: enable
09-06 19:09:49.481  6741  6775 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:09:49.481  6741  6756 I bt_hci_bdroid: init
09-06 19:09:49.491  6741  6756 I bt_vendor: bt-vendor : init
09-06 19:09:49.491  6741  6756 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:09:49.491  6741  6756 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:09:49.491  6741  6756 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-06 19:09:49.491  6741  6756 D bt_userial_mct: userial_init
09-06 19:09:49.491  6741  6756 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:09:49.491  6741  6756 I bt_vendor: Starting hciattach daemon
09-06 19:09:49.491  6741  6756 I bt_vendor: try to set false
09-06 19:09:49.491  6741  6756 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:09:49.491  6741  6756 I bt_vendor: Starting hciattach daemon
09-06 19:09:49.491  6741  6756 I bt_vendor: try to set true
,09-06 19:09:49.511  6779  6779 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:09:49.551  6785  6785 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 19:09:49.561  6786  6786 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:09:49.571  6788  6788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 19:09:49.581  6789  6789 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:09:49.591  6790  6790 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:49.601  6791  6791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:09:49.861  6794  6794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-06 19:09:49.871  6795  6795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:09:49.901  6741  6756 I bt_vendor: bluetooth satus is on,
09-06 19:09:49.901  6741  6777 D bt_userial_mct: userial_open(port:0)
09-06 19:09:49.901  6741  6777 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:09:49.901  6741  6777 I bt_vendor: Done intiailizing UART,
,09-06 19:09:49.901  6741  6777 I bt_vendor: Done intiailizing UART,
09-06 19:09:49.901  6741  6777 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-06 19:09:49.901  6741  6777 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:09:49.911  6741  6797 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_HCI,
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_A2D
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_GAP,
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_SDP,
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_GATT
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:09:49.911  6741  6775 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,09-06 19:09:50.021  6741  6775 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:09:50.021  6741  6775 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa409a6e9 
,09-06 19:09:50.021  6741  6775 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa409a6e9 
,09-06 19:09:50.041  6741  6759 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:09:50.041  6741  6759 E bt-btif : Calling BTA_HhEnable
,09-06 19:09:50.041  6741  6759 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:09:50.041  6741  6759 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-06 19:09:50.051  6741  6759 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:50.051  6741  6759 I bluedroid: getModelRssiValues
09-06 19:09:50.051  6741  6759 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:50.051  6741  6759 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:50.051  6741  6759 D BluetoothAdapterProperties: Name is: A5-1
,09-06 19:09:50.051  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 19:09:50.051  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.051  6741  6759 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:50.051  6741  6759 D BluetoothAdapterProperties: Scan Mode:20
09-06 19:09:50.051  6741  6759 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:50.061  6741  6759 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-06 19:09:50.061  6741  6759 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 19:09:50.061  6741  6759 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:09:50.061  6741  6759 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 19:09:50.061  6741  6759 E bt-btif : btif_sock_init: !vhci_init
09-06 19:09:50.061  6741  6759 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 19:09:50.061  6741  6759 D IOP_DB_BT: db_open: db_open : handle 3028422672l, read 13894 bytes onto local cache
09-06 19:09:50.061  6741  6759 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 19:09:50.061  6741  6759 D IOP_DB_BT: db_query: result 1
09-06 19:09:50.061  6741  6759 I         : iop_db_open: iop_db_open status 0
09-06 19:09:50.061  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.061  6741  6759 D bte_conf: Device ID record 1 : primary
,09-06 19:09:50.061  6741  6759 D bte_conf:   vendorId            = 0075
09-06 19:09:50.061  6741  6759 D bte_conf:   vendorIdSource      = 0001
,09-06 19:09:50.061  6741  6759 D bte_conf:   product             = 0100
09-06 19:09:50.061  6741  6759 D bte_conf:   version             = 0200,
09-06 19:09:50.061  6741  6759 D bte_conf:   clientExecutableURL = 
,09-06 19:09:50.061  6741  6759 D bte_conf:   serviceDescription  = 
,09-06 19:09:50.061  6741  6759 D bte_conf:   documentationURL    = 
,09-06 19:09:50.061  6741  6759 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:09:50.071  6741  6759 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 19:09:50.071  6741  6756 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-06 19:09:50.071  6741  6756 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:09:50.071  6741  6756 D BluetoothAdapterProperties: State =  11
,09-06 19:09:50.071  1014  1543 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 19:09:50.071  6741  6756 D BluetoothAdapterProperties: Setting state to 12
09-06 19:09:50.071  6741  6756 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
09-06 19:09:50.071  6741  6797 E bt_mct  : hci lib postload completed
,09-06 19:09:50.071  6741  6759 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:50.071  6741  6759 D BluetoothAdapterProperties: Scan Mode:21
09-06 19:09:50.071  6741  6759 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:50.081  1014  1137 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 19:09:50.081  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 19:09:50.081  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:50.081  1014  1137 D SettingsProvider: selectionArgs: false
09-06 19:09:50.081  1014  1137 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:50.081  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:50.081  1014  1137 D SettingsProvider: ret = -1
,09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:50.081  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:50.091  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:50.091  6741  6756 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 19:09:50.091  6741  6756 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:09:50.091  1014  3245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.091  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.091  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.091  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.091  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.101  6741  6756 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:50.101  6741  6756 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:09:50.101  6741  6756 D BluetoothAdapterService: starting service from this receiver
09-06 19:09:50.101  1014  3243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:50.101  1429  1441 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.101  1014  3243 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 19:09:50.101  1429  1441 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.101  1429  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.101  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.101  1014  3243 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.101  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:50.101  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:50.111  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.111  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.111  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.111  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.111  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.111  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:50.111  6741  6756 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:09:50.111  1429  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.111  1364  6602 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.111  1364  6602 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.121  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.121  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.121  1458  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.121  1458  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.121  6741  6755 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:50.121  1364  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:09:50.121  6741  6741 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:09:50.131  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 19:09:50.131  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.131  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.131  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.131  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.131  6164  6177 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.131  6164  6177 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.141  1364  1380 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.141  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:50.141  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.141  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.141  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.141  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.141  1364  1380 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.141  6741  6741 I BluetoothPbapService: Handler(): got msg=1
,09-06 19:09:50.151  1364  1364 D HeadsetProfile: Bluetooth service connected
09-06 19:09:50.151  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.151  1014  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-06 19:09:50.151  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.151  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.151  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.151  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.151  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.151  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.161  2857  2876 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:50.161  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.161  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.161  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.161  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.161  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.161  2857  2876 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.161  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:50.161  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:50.161  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.161  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.161  1014  1014 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.161  2857  2876 D BluetoothA2dp: onBluetoothStateChange: up=true
09-06 19:09:50.161  1364  1364 D BluetoothInputDevice: Proxy object connected
,09-06 19:09:50.161  1364  1364 D HidProfile: Bluetooth service connected
09-06 19:09:50.161  2857  2876 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.161  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:50.161  6741  6800 V BluetoothPbapService: PBAP Service initSocket try: 0
09-06 19:09:50.161  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.161  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.161  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.161  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.161  1171  1932 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.161  2857  2857 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.161  1171  1932 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.171  6323  6339 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.171  6323  6339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.171  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:50.171  6741  6800 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:50.171  6741  6800 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:50.171  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.171  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:09:50.171  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:50.171  1364  6602 D BluetoothPbap: onBluetoothStateChange: up=true
09-06 19:09:50.171  6741  6800 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-06 19:09:50.171  6741  6800 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.171  6741  6800 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.171  6741  6800 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4f7a512
09-06 19:09:50.171  6741  6800 D BluetoothSocket: channel: 19
09-06 19:09:50.171  6741  6800 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 19:09:50.171  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:09:50.171  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.181  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.181  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.181  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.181  1439  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.181  1439  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.181  1364  1364 D BluetoothPbap: Proxy object connected
09-06 19:09:50.181  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-06 19:09:50.181  1458  1692 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.181  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:50.181  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.181  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.181  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.181  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.181  1458  1692 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.191  6741  6755 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.191  6741  6755 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.191  1934  4454 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:50.191  1934  4454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:50.191  1364  1380 D BluetoothPan: Binding service...
,09-06 19:09:50.191  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:09:50.191  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.191  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.191  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.191  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.191  2857  2878 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:50.191  2857  2878 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:50.191  1364  1380 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:09:50.191  1364  1380 D Bluetoothsap: Binding service...
09-06 19:09:50.191  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:50.191  1364  1364 D PanProfile: Bluetooth service connected
09-06 19:09:50.191  1364  1380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:09:50.201  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 19:09:50.201  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.201  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:09:50.201  1364  1380 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:09:50.201  1364  1378 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:50.201  1364  1378 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.201  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:09:50.201  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.201  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.201  1364  1364 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:09:50.201  1364  1364 D SapProfile: Bluetooth service connected
09-06 19:09:50.201  1364  1364 D Bluetoothsap: getConnectedDevices()
,09-06 19:09:50.201  1429  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:50.201  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:50.201  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:50.201  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.201  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.201  1429  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:50.201  1364  1364 D BluetoothA2dp: Proxy object connected
09-06 19:09:50.201  1364  1364 D A2dpProfile: Bluetooth service connected
,09-06 19:09:50.211  1014  1044 D BluetoothPan: Binding service...
,09-06 19:09:50.211  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:09:50.211  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.211  1364  1380 D BluetoothMap: onBluetoothStateChange: up=true
09-06 19:09:50.211  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 19:09:50.211  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:09:50.211  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.211  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.211  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:50.211  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.211  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:50.211  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:50.211  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:50.211  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:09:50.211  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-06 19:09:50.211  1364  1364 D BluetoothMap: Proxy object connected
09-06 19:09:50.211  1364  1364 D MapProfile: Bluetooth service connected
09-06 19:09:50.211  1364  1364 D BluetoothMap: getConnectedDevices()
,09-06 19:09:50.221  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:50.221  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@201a214f, true
,09-06 19:09:50.221  1429  1429 D BluetoothHeadset: registerMessageListener
,09-06 19:09:50.221  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:50.221  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.221  1171  1171 D BluetoothTile:  getBluetoothState : 12
,09-06 19:09:50.221  1792  1792 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:50.231  1014  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.231  1014  1369 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:09:50.231  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:50.231  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.231  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:50.241  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.241  1014  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:50.241  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.241  6741  6755 D HeadsetService: registerMessageListener
,09-06 19:09:50.241  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.241  6741  6755 D HeadsetService: registerMessageListener
09-06 19:09:50.241  6741  6768 D HeadsetStateMachine: Disconnected process message: 70
09-06 19:09:50.241  6741  6768 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@fa8f4e3
,09-06 19:09:50.241  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.241  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:09:50.241  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-06 19:09:50.241  1014  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:50.241  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:50.251  1364  1364 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 19:09:50.251  1364  1364 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:09:50.251  1364  1364 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:09:50.251  1364  1364 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:09:50.251  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-06 19:09:50.251  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:09:50.251  6741  6804 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:09:50.251  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:09:50.251  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.251  6741  6768 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:09:50.261  6741  6768 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 19:09:50.261  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:50.261  6741  6804 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:50.261  6741  6804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:50.261   282   690 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.261   282   690 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.261   282   690 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:09:50.261   282   690 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:09:50.261   282   690 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:09:50.261   282   690 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:09:50.261   282   690 V audio_hw_primary: adev_set_parameters: exit
09-06 19:09:50.271  6741  6768 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:09:50.271  6741  6804 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-06 19:09:50.271  6741  6804 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.271  6741  6804 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.271  6741  6804 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@301f9ee0
09-06 19:09:50.271  6741  6804 D BluetoothSocket: channel: 5
,09-06 19:09:50.271  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:50.271  1014  1485 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:50.271  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.281  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.281  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.281  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:50.291  1364  1364 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:50.291  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:50.291  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:50.291  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:09:50.301  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:50.301  6741  6741 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:50.301  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:50.301  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.301  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.301  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:50.301  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:50.321  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:50.321  1014  3245 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:50.321  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:50.321  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.321  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:50.321  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:50.331  1934  6810 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-06 19:09:50.331  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:50.341  1014  1485 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:50.351  6741  6814 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:09:50.351  6741  6814 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:50.351  6741  6814 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,09-06 19:09:50.351  6741  6814 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:50.351  6741  6814 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:50.351  6741  6814 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385ec46a
09-06 19:09:50.351  6741  6814 D BluetoothSocket: channel: 12
09-06 19:09:50.351  6741  6814 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:50.421  1934  2106 I art     : Explicit concurrent mark sweep GC freed 48737(2MB) AllocSpace objects, 54(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.509ms total 79.904ms
,09-06 19:09:50.591  1014  1543 I art     : Explicit concurrent mark sweep GC freed 46504(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.393ms total 165.558ms
09-06 19:09:50.591  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:50.591  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:50.591  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:50.591  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:50.601  1014  3245 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:50.601  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:50.601  1014  3245 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:50.601  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:50.611  1934  6810 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:09:51.671  1014  1374 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:09:51.671  1014  1374 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4255, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-06 19:09:51.671  1014  1374 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 19:09:51.671  1014  1374 D BatteryService: stay LED for charging
09-06 19:09:51.671  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-06 19:09:51.681  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 19:09:51.681  1014  1014 I MotionRecognitionService: Plugged,
,09-06 19:09:51.681  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
09-06 19:09:51.681  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:09:51.681  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 19:09:51.681  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98,
,09-06 19:09:51.701  6741  6741 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:09:51.701  6741  6768 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:09:51.711  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:51.711  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
09-06 19:09:51.711  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:09:52.001  6164  6217 D BluetoothAdapter: disable()
,09-06 19:09:52.001  1014  1369 D SettingsProvider: name = bluetooth_on
,09-06 19:09:52.011  6741  6756 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 19:09:52.011  6741  6756 D BluetoothAdapterProperties: Setting state to 13
09-06 19:09:52.011  6741  6756 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 19:09:52.011  6741  6756 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:52.011  6741  6756 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 19:09:52.011  1014  1374 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 19:09:52.011  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 19:09:52.011  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:52.011  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:52.011  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:52.021  6741  6741 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 19:09:52.021  6741  6756 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:52.021  6741  6756 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 19:09:52.021  6741  6756 D BluetoothAdapterService: terminating service from this receiver
,09-06 19:09:52.021  6741  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@342e1d5b, channel: 19, state: LISTENING
09-06 19:09:52.021  6741  6741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@342e1d5b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@4f7a512, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13f669f8mSocket: android.net.LocalSocket@204ded1 impl:android.net.LocalSocketImpl@3e9cbd36 fd:FileDescriptor[74]
09-06 19:09:52.021  6741  6741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@204ded1 impl:android.net.LocalSocketImpl@3e9cbd36 fd:FileDescriptor[74]
,09-06 19:09:52.021  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:52.021  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-06 19:09:52.031  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:52.031  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:52.031  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:52.031  1014  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:09:52.031  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:52.031  1171  1171 D BluetoothTile:  getBluetoothState : 13
,09-06 19:09:52.041  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:52.041  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:52.041  1792  1792 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:52.041  1014  1543 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:52.041  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:52.041  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:52.051  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:52.051  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:52.051  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:52.051  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:52.051  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:52.051  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:52.051  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:52.051  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:52.051  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:52.051  6741  6756 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 19:09:52.051  6741  6756 D BluetoothAdapterProperties: mDiscovering is false
,09-06 19:09:52.061  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 19:09:52.061  1014  3244 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:09:52.061  1014  1374 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:52.061  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:09:52.061  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 19:09:52.061  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:52.061  1014  1374 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:52.061  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:52.061  6164  6164 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 19:09:52.061  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:09:52.061  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:52.061  6741  6756 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 19:09:52.071  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:52.071  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:52.071  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:52.071  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:52.071  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:52.081  1364  1364 D BluetoothPbap: Proxy object disconnected
,09-06 19:09:52.081  6741  6759 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:52.081  6741  6759 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:52.081  1364  1364 D PbapServerProfile: Bluetooth service disconnected
,09-06 19:09:52.091  6741  6756 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 19:09:52.091  6741  6756 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 19:09:52.091  6741  6756 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 19:09:52.091  6741  6756 E bt-btif : cmd socket is not created
09-06 19:09:52.091  6741  6814 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 19:09:52.091  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:52.091  6741  6756 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:09:52.091  6741  6775 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 19:09:52.091  6741  6775 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 19:09:52.091  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:52.091  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:52.091  6741  6775 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 19:09:52.101  6741  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38273437, channel: 5, state: LISTENING
09-06 19:09:52.101  6741  6741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38273437, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@301f9ee0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@34242da4mSocket: android.net.LocalSocket@2a27970d impl:android.net.LocalSocketImpl@23ef76c2 fd:FileDescriptor[76]
09-06 19:09:52.101  6741  6741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a27970d impl:android.net.LocalSocketImpl@23ef76c2 fd:FileDescriptor[76]
,09-06 19:09:52.101  6741  6741 I BtOppRfcommListener: stopping Accept Thread
09-06 19:09:52.101  6741  6741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f30dcd3, channel: 12, state: LISTENING
09-06 19:09:52.101  6741  6741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f30dcd3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385ec46a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9488010mSocket: android.net.LocalSocket@27439709 impl:android.net.LocalSocketImpl@29c23d0e fd:FileDescriptor[81]
09-06 19:09:52.101  6741  6741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27439709 impl:android.net.LocalSocketImpl@29c23d0e fd:FileDescriptor[81]
,09-06 19:09:52.101  1364  1364 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:52.101  6741  6814 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 19:09:52.101  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:52.101  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:52.111  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:52.111  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 19:09:52.121  6741  6741 V BluetoothOppManager: cleanUp...
,09-06 19:09:52.141  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:52.151  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:52.291   287   287 E SMD     : DCD OFF
,09-06 19:09:52.291  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:52.301  6741  6797 I bt_userial_mct: exiting userial_read_thread
09-06 19:09:52.301  6741  6797 D bt_userial_mct: Leaving userial_evt_read_thread()
,09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 19:09:52.301  6741  6775 W bt-btif : ag scb idx 1 not allocated
09-06 19:09:52.301  6741  6775 W bt-btif : ag scb idx 2 not allocated
09-06 19:09:52.301  6741  6775 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 19:09:52.301  6741  6759 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 19:09:52.301  6741  6777 I bt_vendor: hw_epilog_process
09-06 19:09:52.301  6741  6759 D bt_userial_mct: userial_close
09-06 19:09:52.301  6741  6759 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 19:09:52.921  1014  2724 D SSRM:n  : SIOP:: AP = 340
,09-06 19:09:53.031  6741  6759 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
,09-06 19:09:53.031  1014  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.031  6741  6759 I bt_vendor: bluetooth satus is on
,09-06 19:09:53.031  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 19:09:53.031  6741  6759 I bt_vendor: bt-vendor : resetting BT status,
,09-06 19:09:53.031  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-06 19:09:53.031  6741  6759 I bt_vendor: Starting hciattach daemon
,09-06 19:09:53.031  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 19:09:53.031  6741  6759 I bt_vendor: try to set false
09-06 19:09:53.031  6741  6759 I bt_vendor: Starting hciattach daemon
09-06 19:09:53.031  6741  6759 I bt_vendor: try to set false
09-06 19:09:53.031  6741  6759 I bt_vendor: cleanup
09-06 19:09:53.031  6741  6775 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-06 19:09:53.041  1014  1374 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.031  6741  6759 I GKI_LINUX: GKI_exit_task 0 done
09-06 19:09:53.041  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 19:09:53.031  6741  6759 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-06 19:09:53.031  6741  6756 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 19:09:53.031  6741  6756 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:53.031  6741  6756 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 19:09:53.031  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:53.031  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:53.031  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:09:53.031  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.031  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.031  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.031  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:53.031  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:53.031  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-06 19:09:53.031  6741  6741 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 19:09:53.041  6741  6741 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 19:09:53.041  6741  6741 D BtGatt.GattService: stop()
09-06 19:09:53.041  1014  1374 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.041  6741  6741 D BtGatt.AdvertiseManager: advertise clients cleared
09-06 19:09:53.041  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 19:09:53.041  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.041  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.041  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.041  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 19:09:53.041  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:53.041  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:53.041  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.041  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.041  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.041  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:53.041  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.041  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:53.051  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
09-06 19:09:53.051  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.051  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.051  1014  3244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.051  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 19:09:53.051  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.051  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:53.051  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:53.051  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 19:09:53.051  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.051  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.051  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.051  6741  6741 D HeadsetService: Received stop request...Stopping profile...
,09-06 19:09:53.051  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 19:09:53.051  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:53.051  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:53.051  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:53.051  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.061  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.061  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.061  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.061  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.061  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.061  6741  6756 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.061  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.061  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.061  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.061  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.061  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:53.061  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.061  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:53.061  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.061  6741  6756 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 19:09:53.061  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 19:09:53.071  1364  1364 D HeadsetProfile: Bluetooth service disconnected
,09-06 19:09:53.071  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:53.071  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.071  6741  6741 D A2dpService: Received stop request...Stopping profile...
,09-06 19:09:53.071  6741  6770 D A2dpStateMachine: Exit Disconnected: -1
,09-06 19:09:53.071  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.071  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.071  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.081  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.081  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.081  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 19:09:53.081  6741  6756 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:53.081  6741  6756 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 19:09:53.081  6741  6756 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 19:09:53.081  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.081  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 19:09:53.081  6741  6741 D HidService: Received stop request...Stopping profile...
,09-06 19:09:53.081  6741  6741 D HidService: Stopping Bluetooth HidService
09-06 19:09:53.081  6741  6741 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-06 19:09:53.081  6741  6741 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 19:09:53.081  6741  6741 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-06 19:09:53.081  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.091  2857  2857 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.091  1364  1364 D BluetoothA2dp: Proxy object disconnected
,09-06 19:09:53.091  1364  1364 D A2dpProfile: Bluetooth service disconnected
09-06 19:09:53.091  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.091  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 19:09:53.091  1364  1364 D BluetoothInputDevice: Proxy object disconnected
09-06 19:09:53.091  1364  1364 D HidProfile: Bluetooth service disconnected
,09-06 19:09:53.091  6741  6741 D HealthService: Received stop request...Stopping profile...
,09-06 19:09:53.091  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.091  6741  6741 D PanService: Received stop request...Stopping profile...,
09-06 19:09:53.091  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.091  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 19:09:53.091  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 19:09:53.091  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.091  6741  6741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 19:09:53.091  6741  6741 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 19:09:53.101  1364  1364 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 19:09:53.101  1364  1364 D PanProfile: Bluetooth service disconnected
,09-06 19:09:53.101  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.101  6741  6741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 19:09:53.101  6741  6741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 19:09:53.101  6741  6741 D SapService: Received stop request...Stopping profile...
09-06 19:09:53.101  6741  6741 D SapService: Stopping Bluetooth SapService
09-06 19:09:53.101  6741  6741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c673911
,09-06 19:09:53.101  1364  1364 D BluetoothMap: Proxy object disconnected
09-06 19:09:53.101  1364  1364 D MapProfile: Bluetooth service disconnected
,09-06 19:09:53.101  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-06 19:09:53.111  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 19:09:53.111  1364  1364 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 19:09:53.111  6741  6741 D BluetoothA2dp: Proxy object disconnected
09-06 19:09:53.111  1364  1364 D SapProfile: Bluetooth service disconnected
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 19:09:53.111  6741  6771 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-06 19:09:53.111  6741  6741 I GKI_LINUX: GKI_exit_task 2 done
09-06 19:09:53.111  6741  6741 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 19:09:53.111  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 19:09:53.111  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:53.111  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 19:09:53.111  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.111  6741  6741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 19:09:53.111  6741  6741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 19:09:53.111  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 19:09:53.111  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.111  6741  6741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-06 19:09:53.111  6741  6741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 19:09:53.111  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 19:09:53.111  6741  6741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:53.111  6741  6741 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 19:09:53.111  6741  6741 E BluetoothAdapterService(1013397777): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 19:09:53.111  6741  6756 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 19:09:53.111  6741  6756 D BluetoothAdapterProperties: Setting state to 10
09-06 19:09:53.111  6741  6756 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-06 19:09:53.111  6741  6756 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:53.111  6741  6756 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 19:09:53.111  6741  6741 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 19:09:53.111  6741  6741 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 19:09:53.111  6741  6756 D BluetoothAdapterService: Autoconnection is available 
09-06 19:09:53.121  6741  6756 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 19:09:53.121  6741  6756 I BluetoothAdapterState: Entering OffState
09-06 19:09:53.121  1429  1441 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.121  1429  1441 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.121  1364  1378 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.121  1364  1378 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.121  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.121  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.121  1458  1749 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.121  1458  1749 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.121  6741  6818 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.121  1364  1380 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 19:09:53.121  6164  6207 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.121  6164  6207 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 19:09:53.121  6164  6207 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 19:09:53.121  6164  6207 D BluetoothLeAdvertiser: Exit stop advertising
,09-06 19:09:53.121  6164  6207 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 19:09:53.121  6164  6207 D BluetoothLeScanner: Exiting stopAllScan
,09-06 19:09:53.121  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.121  2857  2878 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.121  1171  3572 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.121  1171  3572 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  6323  6337 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.131  6323  6337 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  1364  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 19:09:53.131  1439  1456 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.131  1439  1456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  6741  6803 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.131  6741  6803 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  1934  2115 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 19:09:53.131  1934  2115 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  2857  2876 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 19:09:53.131  2857  2876 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 19:09:53.131  1364  6602 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 19:09:53.131  1364  6602 D Bluetoothsap: Unbinding service...
,09-06 19:09:53.131  1364  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 19:09:53.141  1364  1380 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 19:09:53.141  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-06 19:09:53.141  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:53.151  6741  6759 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 19:09:53.151  6741  6741 I GKI_LINUX: GKI_exit_task 1 done
09-06 19:09:53.151  6741  6741 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-06 19:09:53.151  6741  6741 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 19:09:53.171  6741  6741 I art     : System.exit called, status: 0
09-06 19:09:53.171  6741  6741 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 19:09:53.191  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.191  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-06 19:09:53.191  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:53.191  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:53.191  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:53.191  1171  1743 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.191  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.191  1171  1171 D BluetoothTile:  getBluetoothState : 10
,09-06 19:09:53.191  1171  1743 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.191  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:53.201  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:53.201  1171  1171 D BluetoothAdapter: 218464022: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.201  1792  1792 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:53.201  1014  1485 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:53.201  1934  2122 D BluetoothAdapter: 1039818314: getState() :  mService = null. Returning STATE_OFF
09-06 19:09:53.201  1934  2122 D BluetoothAdapter: 1039818314: getState() :  mService = null. Returning STATE_OFF
,09-06 19:09:53.201  1014  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:53.201  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.201  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.201  1014  3244 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:53.201  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:53.201  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.201  1014  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:53.201  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:53.211  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 19:09:53.211  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:53.211  1014  1374 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 19:09:53.211  1014  1374 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.211  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:53.211  1014  1374 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:53.211  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:53.231  1364  1364 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:53.231  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:53.231  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:53.231  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 19:09:53.241  1014  1137 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:09:53.241  1014  1137 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:09:53.251  1014  1137 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-06 19:09:53.251  1014  1137 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-06 19:09:53.251  1014  1137 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:09:53.251  1014  1137 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 19:09:53.251  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:53.251  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:09:53.251  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:53.251  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:09:53.271  6833  6833 E Zygote  : MountEmulatedStorage()
,09-06 19:09:53.271  6833  6833 E Zygote  : v2
09-06 19:09:53.271  6833  6833 I libpersona: KNOX_SDCARD checking this for 1002
09-06 19:09:53.271  6833  6833 I libpersona: KNOX_SDCARD not a persona
09-06 19:09:53.271  6833  6833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:09:53.271  1014  1137 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6833 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 19:09:53.271  6833  6833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:09:53.281  6833  6833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 19:09:53.301  6833  6833 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:09:53.301  6833  6833 D ActivityThread: Added TimaKeyStore provider
,09-06 19:09:53.311  6833  6833 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 19:09:53.311  6833  6833 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 19:09:53.331  6833  6833 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 19:09:53.361  6833  6833 D BtSettings.ProfileConfig: Adding GattService
,09-06 19:09:53.361  6833  6833 D BtSettings.ProfileConfig: Adding HeadsetService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding A2dpService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding HidService
,09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding HealthService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding PanService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding SapService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding SapClientService
09-06 19:09:53.371  6833  6833 D BtSettings.ProfileConfig: Adding HidDevService
,09-06 19:09:53.371  6833  6833 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 19:09:53.371  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 19:09:53.371  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.371  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:53.371  1014  1026 D SettingsProvider: selectionArgs: false
09-06 19:09:53.371  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:53.371  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.371  1014  1026 D SettingsProvider: ret = -1
,09-06 19:09:53.371  1014  1315 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:53.371  1014  1315 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.371  1014  1315 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.371  1014  1315 D SettingsProvider: selectionArgs: false
09-06 19:09:53.371  1014  1315 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.371  1014  1315 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.371  1014  1315 D SettingsProvider: ret = -1
09-06 19:09:53.371  1014  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:53.371  1014  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.371  1014  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.371  1014  1485 D SettingsProvider: selectionArgs: false
09-06 19:09:53.371  1014  1485 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.371  1014  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.371  1014  1485 D SettingsProvider: ret = -1
,09-06 19:09:53.371  1014  1543 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-06 19:09:53.371  1014  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.371  1014  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.371  1014  1543 D SettingsProvider: selectionArgs: false
09-06 19:09:53.371  1014  1543 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.371  1014  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.371  1014  1543 D SettingsProvider: ret = -1
,09-06 19:09:53.371  1014  1369 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 19:09:53.371  1014  1369 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.371  1014  1369 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.371  1014  1369 D SettingsProvider: selectionArgs: false
09-06 19:09:53.371  1014  1369 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:53.371  1014  1369 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.371  1014  1369 D SettingsProvider: ret = -1
09-06 19:09:53.381  1014  1374 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
09-06 19:09:53.381  1014  1374 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  1374 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 19:09:53.381  1014  1374 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  1374 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.381  1014  1374 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.381  1014  1374 D SettingsProvider: ret = -1
,09-06 19:09:53.381  1014  3244 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 19:09:53.381  1014  3244 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  3244 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  3244 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  3244 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.381  1014  3244 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.381  1014  3244 D SettingsProvider: ret = -1
09-06 19:09:53.381  1014  3245 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-06 19:09:53.381  1014  3245 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  3245 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  3245 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  3245 D SettingsProvider: selectionArgs: 1002,
,09-06 19:09:53.381  1014  3245 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:53.381  1014  3245 D SettingsProvider: ret = -1
,09-06 19:09:53.381  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:53.381  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  1137 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  1137 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.381  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 19:09:53.381  1014  1137 D SettingsProvider: ret = -1
09-06 19:09:53.381  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:53.381  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  1027 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  1027 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:53.381  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.381  1014  1027 D SettingsProvider: ret = -1
09-06 19:09:53.381  1014  1544 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 19:09:53.381  1014  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  1544 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  1544 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.381  1014  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.381  1014  1544 D SettingsProvider: ret = -1
09-06 19:09:53.381  1014  3243 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-06 19:09:53.381  1014  3243 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:53.381  1014  3243 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:53.381  1014  3243 D SettingsProvider: selectionArgs: false
09-06 19:09:53.381  1014  3243 D SettingsProvider: selectionArgs: 1002
09-06 19:09:53.381  1014  3243 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:53.381  1014  3243 D SettingsProvider: ret = -1
,09-06 19:09:53.401  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:53.401  1014  1369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:53.401  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:53.401  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.401  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:53.401  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:53.411  1934  6849 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:09:53.411  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:53.411  1014  1315 I ActivityManager: Killing 6044:com.samsung.helphub/1000 (adj 15): empty #31
,09-06 19:09:53.421  1014  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:53.421  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:53.421  1014  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:53.421  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:53.431  1934  6849 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 19:09:53.731  1014  1319 E Watchdog: !@Sync 4
,09-06 19:09:54.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 19:09:55.021  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:09:55.021  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:09:55.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:55.291   287   287 E SMD     : DCD OFF,
,09-06 19:09:56.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:57.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:58.021  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-06 19:09:58.021  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@143a0f47 added. We now have 6 listener(s)
09-06 19:09:58.021  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:58.021  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:09:58.021  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@254a5374 added. We now have 7 listener(s)
09-06 19:09:58.021  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:09:58.021  6164  6217 I System.out: IsBluetoothEnabled
,09-06 19:09:58.021  6164  6217 D BluetoothAdapter: disable()
09-06 19:09:58.021  1014  3245 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
09-06 19:09:58.021  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.031  6164  6217 D BluetoothAdapter: enable()
,09-06 19:09:58.031  1014  1137 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-06 19:09:58.031  1014  1137 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 19:09:58.031  1014  1137 W ActivityManager: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:09:58.031  1014  1977 V SAMP_SPCM_test: CSC File load.. 
09-06 19:09:58.031  1014  1137 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:58.031  1014  1137 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:58.041  1014  1137 D SettingsProvider: name = bluetooth_on
,09-06 19:09:58.041  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-06 19:09:58.041  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,09-06 19:09:58.041  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-06 19:09:58.051  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:09:58.081  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-06 19:09:58.091  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-06 19:09:58.091  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-06 19:09:58.091  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,09-06 19:09:58.091  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security,
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location,
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 19:09:58.091  1014  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-06 19:09:58.111  1014  1977 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 19:09:58.121  6833  6833 D BluetoothAdapterState: make
,09-06 19:09:58.131  6833  6833 I bluedroid: init
09-06 19:09:58.131  6833  6855 I BluetoothAdapterState: Entering OffState
,09-06 19:09:58.131  6833  6833 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 19:09:58.131  6833  6833 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 19:09:58.131  6833  6833 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-06 19:09:58.131  6833  6833 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 19:09:58.131  6833  6833 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 19:09:58.131  6833  6833 I bluedroid: get_profile_interface socket
09-06 19:09:58.131  6833  6833 I bluedroid: get_profile_interface map_client
,09-06 19:09:58.131  6833  6858 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 19:09:58.141  6833  6833 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 19:09:58.141  6833  6858 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-06 19:09:58.141  6833  6858 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:58.141  6833  6858 I bluedroid: getModelRssiValues
09-06 19:09:58.141  6833  6858 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 19:09:58.141  6833  6858 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:58.141  6833  6858 D BluetoothAdapterProperties: Name is: A5-1
09-06 19:09:58.141  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 19:09:58.141  6833  6833 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:58.151  1014  1369 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:58.151  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.151  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:58.151  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.151  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.151  6833  6841 I bluedroid: config_hci_snoop_log
,09-06 19:09:58.151  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-06 19:09:58.151  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,09-06 19:09:58.161  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
09-06 19:09:58.161  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:58.161  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:58.161  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 19:09:58.161  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 19:09:58.161  6833  6833 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 19:09:58.161  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 19:09:58.171  6833  6855 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 19:09:58.171  6833  6855 D BluetoothAdapterProperties: Setting state to 11
09-06 19:09:58.171  6833  6855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 19:09:58.171  6833  6855 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:58.171  6833  6855 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 19:09:58.171  6833  6855 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:58.171  6833  6855 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 19:09:58.171  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:58.171  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-06 19:09:58.181  6833  6855 D BluetoothSecureManager: getInstant: null
09-06 19:09:58.181  6833  6855 D BluetoothSecureManager: calling getMethod for getService
09-06 19:09:58.181  6833  6855 D BluetoothSecureManager: calling getService
,09-06 19:09:58.181  6833  6855 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@37e83f6f
,09-06 19:09:58.181  1014  1546 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 19:09:58.181  1014  1546 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 19:09:58.181  6833  6855 D BtConfig.SecureMode: isSecureModeOn:false
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 19:09:58.181  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 19:09:58.181  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:58.181  1171  1171 D BluetoothTile:  getBluetoothState : 11
09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:58.181  1792  1792 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:58.181  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 19:09:58.181  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 19:09:58.191  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:58.191  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:58.191  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 19:09:58.191  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:58.191  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:58.191  1014  1544 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 19:09:58.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:58.191  6833  6855 D BluetoothBondStateMachine: make
,09-06 19:09:58.191  1014  1315 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 19:09:58.191  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:58.191  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 19:09:58.191  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 19:09:58.191  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 19:09:58.191  1014  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:58.191  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 19:09:58.191  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 19:09:58.191  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-06 19:09:58.201  6833  6859 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 19:09:58.201  1014  1543 W ActivityManager: userId = 0, bbcId = -10000,
09-06 19:09:58.201  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:58.201  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:58.201  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:58.201  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.201  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:58.211  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.211  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.211  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 19:09:58.211  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 19:09:58.211  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 19:09:58.211  6833  6833 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 19:09:58.211  6833  6833 D BtGatt.GattService: Received start request. Starting profile...
09-06 19:09:58.211  6833  6833 D BtGatt.GattService: start()
09-06 19:09:58.211  6833  6833 D BtGatt.GattService: start()
09-06 19:09:58.211  6833  6833 I bluedroid: get_profile_interface gatt
,09-06 19:09:58.211  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
09-06 19:09:58.211  6833  6833 D BtGatt.AdvertiseManager: advertise manager created
,09-06 19:09:58.211  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:58.211  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.211  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.211  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.211  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.211  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:58.221  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:58.221  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 19:09:58.221  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 19:09:58.221  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:58.221  1014  3244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:58.221  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 19:09:58.221  1014  3244 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.221  1014  3244 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:58.221  1014  3244 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:58.221  1014  3244 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.231  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 19:09:58.231  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 19:09:58.231  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 19:09:58.231  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:58.231  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.241  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.241  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.241  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.241  6833  6833 D BtGatt.GattService: mStartError = false
,09-06 19:09:58.241  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.241  6833  6833 D HeadsetService: Received start request. Starting profile...
09-06 19:09:58.241  6833  6833 D HeadsetService: start()
,09-06 19:09:58.241  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 19:09:58.241  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 19:09:58.241  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 19:09:58.241  6833  6833 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 19:09:58.241  6833  6833 D HeadsetStateMachine: make
,09-06 19:09:58.251  6833  6833 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 19:09:58.251  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 19:09:58.251  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.251  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.251  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.251  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.251  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 19:09:58.251  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 19:09:58.251  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 19:09:58.251  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:58.251  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.251  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.251  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.251  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.261  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 19:09:58.261  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.261  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 19:09:58.261  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 19:09:58.261  6833  6855 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 19:09:58.261  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.261  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.261  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:58.261  1014  1546 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:58.261  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.261  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.261  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.261  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.271  1014  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 19:09:58.271  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 19:09:58.271  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 19:09:58.271  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:58.271  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.271  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 19:09:58.271  6833  6833 I bluedroid: get_profile_interface handsfree
,09-06 19:09:58.271  1014  1369 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:58.271  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:58.271  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:58.271  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:58.271  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:58.271  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:58.271  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 19:09:58.271  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:58.271  6833  6855 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-06 19:09:58.281  6833  6855 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-06 19:09:58.281  6833  6855 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 19:09:58.281  6833  6855 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-06 19:09:58.281  6833  6855 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 19:09:58.281   310   310 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 19:09:58.291  6833  6833 I DualScoManager: Instantiating Dual Sco Manager
,09-06 19:09:58.291  6833  6833 I DualScoManager: Set HeadsetServiceHelper
,09-06 19:09:58.291  6833  6833 D BluetoothAtMessage: createCMTIContentObservers
,09-06 19:09:58.291  1014  3243 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 19:09:58.291  1014  3243 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:58.291  1014  3243 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:58.291  1014  3243 D SettingsProvider: selectionArgs: false
09-06 19:09:58.291  1014  3243 D SettingsProvider: selectionArgs: 1002
,09-06 19:09:58.291  1014  3243 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:58.291  1014  3243 D SettingsProvider: ret = -1
,09-06 19:09:58.291   287   287 E SMD     : DCD OFF
09-06 19:09:58.291  6833  6863 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 19:09:58.291  6833  6863 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 19:09:58.291  6833  6833 D HeadsetService: mStartError = false
09-06 19:09:58.291  6833  6863 D HeadsetStateMachine: map size, before remove : 0
09-06 19:09:58.291  6833  6863 D HeadsetStateMachine: map size, after remove: 0
,09-06 19:09:58.291  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.301  6833  6833 D A2dpService: Received start request. Starting profile...
09-06 19:09:58.301  6833  6833 D A2dpService: start()
,09-06 19:09:58.301  6833  6833 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 19:09:58.301  6833  6833 I bluedroid: get_profile_interface avrcp
,09-06 19:09:58.311  6833  6833 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 19:09:58.321  6833  6833 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 19:09:58.321  6833  6868 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
09-06 19:09:58.321  6833  6833 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-06 19:09:58.321  6833  6833 D A2dpStateMachine: make
,09-06 19:09:58.331  6833  6833 I bluedroid: get_profile_interface a2dp
09-06 19:09:58.331  6833  6870 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 19:09:58.331  6833  6833 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 19:09:58.331  6833  6833 D A2dpService: mStartError = false
09-06 19:09:58.331  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.331  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 19:09:58.331  6833  6833 I BluetoothHidServiceJni: classInitNative: succeeds
09-06 19:09:58.331  6833  6869 D A2dpStateMachine: Enter Disconnected: -2
,09-06 19:09:58.331  6833  6833 D HidService: Received start request. Starting profile...
09-06 19:09:58.331  6833  6833 D HidService: start()
09-06 19:09:58.331  6833  6833 I bluedroid: get_profile_interface hidhost
09-06 19:09:58.331  6833  6833 D HidService: setHidService(): set to: null
09-06 19:09:58.331  6833  6833 D HidService: mStartError = false
09-06 19:09:58.331  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.331  6833  6833 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 19:09:58.331  6833  6833 D HealthService: Received start request. Starting profile...
09-06 19:09:58.341  6833  6833 D HealthService: start()
09-06 19:09:58.341  6833  6868 D BluetoothMediaBrowser: no now playing list
09-06 19:09:58.341  6833  6868 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 19:09:58.341  6833  6833 I bluedroid: get_profile_interface health
,09-06 19:09:58.341  6833  6833 D HealthService: mStartError = false
09-06 19:09:58.341  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.341  6833  6833 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 19:09:58.341  6833  6833 D PanService: Received start request. Starting profile...
09-06 19:09:58.341  6833  6833 D PanService: start()
09-06 19:09:58.341  6833  6833 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 19:09:58.341  6833  6833 I bluedroid: get_profile_interface pan
,09-06 19:09:58.341  6833  6833 D PanService: mStartError = false
09-06 19:09:58.341  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.341  6833  6833 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 19:09:58.341  1429  2725 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 19:09:58.351  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 19:09:58.351  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:58.351  1429  2725 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 19:09:58.351  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:58.351  6833  6833 D BluetoothMapService: Received start request. Starting profile...
09-06 19:09:58.351  6833  6833 D BluetoothMapService: start()
,09-06 19:09:58.351  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:58.361  6833  6833 D BluetoothMapService: mStartError = false
09-06 19:09:58.361  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:58.361  6833  6833 D HeadsetStateMachine: Proxy object connected
,09-06 19:09:58.361  6833  6833 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 19:09:58.361  6833  6833 D SapService: Received start request. Starting profile...
09-06 19:09:58.361  6833  6833 D SapService: start()
09-06 19:09:58.361  6833  6833 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 19:09:58.361  6833  6833 I bluedroid: get_profile_interface sap
09-06 19:09:58.361  6833  6833 D SapService: mStartError = false
09-06 19:09:58.361  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
09-06 19:09:58.361  6833  6833 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 19:09:58.361  6833  6833 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-06 19:09:58.361  6833  6833 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 19:09:58.361  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 19:09:58.361  6833  6833 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 19:09:58.361  6833  6833 D BluetoothA2dp: Proxy object connected
09-06 19:09:58.361  6833  6833 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 19:09:58.361  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 19:09:58.361  6833  6863 D HeadsetStateMachine: Disconnected process message: 11
09-06 19:09:58.361  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-06 19:09:58.361  6833  6863 D HeadsetStateMachine: Disconnected process message: 18
09-06 19:09:58.361  6833  6863 D HeadsetStateMachine: Disconnected process message: 10
09-06 19:09:58.361  6833  6863 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 19:09:58.361  6833  6863 D HeadsetStateMachine: Disconnected process message: 11
,09-06 19:09:58.361  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 19:09:58.371  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 19:09:58.391  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 19:09:58.391  6833  6833 E BluetoothAdapterService(826849399): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 19:09:58.391  6833  6855 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 19:09:58.391  6833  6855 I bluedroid: enable
09-06 19:09:58.391  6833  6855 I bt_hci_bdroid: init
,09-06 19:09:58.391  6833  6855 I bt_vendor: bt-vendor : init
09-06 19:09:58.391  6833  6855 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 19:09:58.391  6833  6855 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 19:09:58.391  6833  6855 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-06 19:09:58.391  6833  6855 D bt_userial_mct: userial_init
09-06 19:09:58.391  6833  6874 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-06 19:09:58.391  6833  6855 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 19:09:58.391  6833  6855 I bt_vendor: Starting hciattach daemon
09-06 19:09:58.391  6833  6855 I bt_vendor: try to set false
,09-06 19:09:58.391  6833  6855 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-06 19:09:58.391  6833  6855 I bt_vendor: Starting hciattach daemon
09-06 19:09:58.391  6833  6855 I bt_vendor: try to set true
,09-06 19:09:58.411  6878  6878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 19:09:58.471  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 19:09:58.481  6885  6885 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-06 19:09:58.501  6887  6887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:58.511  6888  6888 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 19:09:58.521  6889  6889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 19:09:58.531  6890  6890 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 19:09:58.951  6893  6893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-06 19:09:58.961  6894  6894 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 19:09:59.001  6833  6855 I bt_vendor: bluetooth satus is on,
09-06 19:09:59.001  6833  6876 D bt_userial_mct: userial_open(port:0)
09-06 19:09:59.001  6833  6876 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 19:09:59.001  6833  6876 I bt_vendor: Done intiailizing UART,
,09-06 19:09:59.001  6833  6876 I bt_vendor: Done intiailizing UART
09-06 19:09:59.001  6833  6876 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 19:09:59.001  6833  6876 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 19:09:59.011  6833  6896 D bt_userial_mct: Entering userial_read_thread()
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_BTM
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_GAP
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_SAP
,09-06 19:09:59.011  6833  6874 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 19:09:59.021  6833  6874 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 19:09:59.021  6833  6874 I         : BTE_InitTraceLevels -- TRC_SMP
09-06 19:09:59.021  6833  6874 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-06 19:09:59.021  6833  6874 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 19:09:59.021  6833  6874 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 19:09:59.111  6833  6874 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 19:09:59.121  6833  6874 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40946e9 
,09-06 19:09:59.121  6833  6874 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40946e9 
,09-06 19:09:59.141  6833  6858 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 19:09:59.141  6833  6858 E bt-btif : Calling BTA_HhEnable
,09-06 19:09:59.141  6833  6858 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 19:09:59.151  6833  6858 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-06 19:09:59.151  6833  6858 E BluetoothServiceJni: populateRssiValuesNative
09-06 19:09:59.151  6833  6858 I bluedroid: getModelRssiValues
09-06 19:09:59.151  6833  6858 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 19:09:59.151  6833  6858 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 19:09:59.151  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 19:09:59.151  6833  6858 D BluetoothAdapterProperties: Name is: A5-1
,09-06 19:09:59.151  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:09:59.161  6833  6858 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 19:09:59.161  6833  6858 D BluetoothAdapterProperties: Scan Mode:20
,09-06 19:09:59.161  6833  6858 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:59.161  6833  6858 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-06 19:09:59.161  6833  6858 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-06 19:09:59.161  6833  6858 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 19:09:59.161  6833  6858 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 19:09:59.171  6833  6858 E bt-btif : btif_sock_init: !vhci_init
,09-06 19:09:59.171  6833  6858 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-06 19:09:59.171  6833  6896 E bt_mct  : hci lib postload completed
09-06 19:09:59.171  6833  6858 D IOP_DB_BT: db_open: db_open : handle 3023953936l, read 13894 bytes onto local cache
09-06 19:09:59.171  6833  6858 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 19:09:59.171  6833  6858 D IOP_DB_BT: db_query: result 1
09-06 19:09:59.171  6833  6858 I         : iop_db_open: iop_db_open status 0
09-06 19:09:59.171  6833  6858 D bte_conf: Device ID record 1 : primary
09-06 19:09:59.171  6833  6858 D bte_conf:   vendorId            = 0075
09-06 19:09:59.171  6833  6858 D bte_conf:   vendorIdSource      = 0001
09-06 19:09:59.171  6833  6858 D bte_conf:   product             = 0100
09-06 19:09:59.171  6833  6858 D bte_conf:   version             = 0200
09-06 19:09:59.171  6833  6858 D bte_conf:   clientExecutableURL = 
09-06 19:09:59.171  6833  6858 D bte_conf:   serviceDescription  = 
09-06 19:09:59.171  6833  6858 D bte_conf:   documentationURL    = 
09-06 19:09:59.171  6833  6858 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 19:09:59.171  6833  6855 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 19:09:59.171  6833  6855 D BluetoothAdapterProperties: ScanMode =  20
09-06 19:09:59.171  6833  6855 D BluetoothAdapterProperties: State =  11
,09-06 19:09:59.171  6833  6858 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 19:09:59.171  1014  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 19:09:59.171  6833  6855 D BluetoothAdapterProperties: Setting state to 12
09-06 19:09:59.171  6833  6855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 19:09:59.181  6833  6858 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 19:09:59.181  6833  6858 D BluetoothAdapterProperties: Scan Mode:21
,09-06 19:09:59.181  6833  6858 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 19:09:59.181  1014  3243 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-06 19:09:59.181  1014  3243 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 19:09:59.181  1014  3243 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 19:09:59.181  1014  3243 D SettingsProvider: selectionArgs: false
09-06 19:09:59.181  1014  3243 D SettingsProvider: selectionArgs: 1002
09-06 19:09:59.181  1014  3243 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 19:09:59.181  1014  3243 D SettingsProvider: ret = -1
,09-06 19:09:59.181  6833  6855 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 19:09:59.181  6833  6855 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 19:09:59.181  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 19:09:59.181  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.191  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.191  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.191  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.191  6833  6855 D BluetoothAdapterService: Autoconnection is available 
,09-06 19:09:59.191  6833  6855 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 19:09:59.191  6833  6855 D BluetoothAdapterService: starting service from this receiver
,09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:09:59.191  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:09:59.191  1429  1441 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.191  1429  1441 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.191  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.191  1014  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.191  1014  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.201  1014  1471 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.201  1014  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.201  1014  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.201  6833  6855 I BluetoothAdapterState: Entering On State from state = 11
,09-06 19:09:59.201  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:09:59.201  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.201  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.201  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.201  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.201  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.201  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.201  1364  1380 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:59.211  1364  1380 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.211  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.211  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.211  1458  1692 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.211  1458  1692 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.211  6833  6864 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:59.211  6833  6841 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.211  6833  6841 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.211  1364  6602 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 19:09:59.211  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 19:09:59.211  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.211  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.211  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.211  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.211  6833  6833 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 19:09:59.221  6164  6178 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:59.221  6164  6178 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.221  1364  1378 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.221  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:59.221  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.221  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.221  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.221  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:09:59.221  1364  1378 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.221  1429  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.231  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:59.231  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.231  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.231  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.231  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.231  1429  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.231  2857  2876 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.231  6833  6833 I BluetoothPbapService: Handler(): got msg=1
09-06 19:09:59.231  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.231  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.231  1364  1364 D HeadsetProfile: Bluetooth service connected
09-06 19:09:59.231  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.231  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.231  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.231  1014  1315 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:59.241  2857  2876 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.241  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:59.241  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:59.241  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:59.241  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.241  1014  1014 D BluetoothA2dp: Proxy object connected
,09-06 19:09:59.241  6833  6900 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 19:09:59.241  2857  2878 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:59.251  2857  2878 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.251  1014  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 19:09:59.251  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.251  1364  1364 D BluetoothInputDevice: Proxy object connected
09-06 19:09:59.251  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.251  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.251  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.251  6833  6900 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:59.251  2857  2857 D BluetoothA2dp: Proxy object connected
,09-06 19:09:59.251  6833  6900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:59.251  1364  1364 D HidProfile: Bluetooth service connected
,09-06 19:09:59.251  6833  6900 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,09-06 19:09:59.251  6833  6900 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.251  6833  6900 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.251  6833  6900 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@301f9ee0
09-06 19:09:59.251  6833  6900 D BluetoothSocket: channel: 19
09-06 19:09:59.251  6833  6900 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 19:09:59.251  1171  1932 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.251  1171  1932 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.251  6323  6339 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.251  6323  6339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.251  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-06 19:09:59.251  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.251  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-06 19:09:59.251  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.251  1364  6602 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 19:09:59.261  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 19:09:59.261  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.261  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.261  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.261  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.261  1364  1364 D BluetoothPbap: Proxy object connected
,09-06 19:09:59.261  1439  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.261  1439  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.261  1364  1364 D PbapServerProfile: Bluetooth service connected
,09-06 19:09:59.261  1458  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.261  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 19:09:59.271  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.271  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.271  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.271  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.271  1458  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 19:09:59.271  1934  1943 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 19:09:59.271  1934  1943 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 19:09:59.271  1364  1380 D BluetoothPan: Binding service...
,09-06 19:09:59.271  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-06 19:09:59.271  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.271  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.271  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.271  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.271  2857  2876 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 19:09:59.281  2857  2876 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 19:09:59.281  1364  1378 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 19:09:59.281  1364  1378 D Bluetoothsap: Binding service...
09-06 19:09:59.281  1364  1364 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:09:59.281  1364  1364 D PanProfile: Bluetooth service connected
,09-06 19:09:59.281  1364  1378 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 19:09:59.281  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 19:09:59.281  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.281  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.281  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.281  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.281  1364  1378 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 19:09:59.281  1364  1380 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 19:09:59.281  1364  1380 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.281  1364  1364 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 19:09:59.281  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 19:09:59.281  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.281  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.281  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.281  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 19:09:59.281   310   310 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
09-06 19:09:59.281  1364  1364 D SapProfile: Bluetooth service connected
09-06 19:09:59.281  1364  1364 D Bluetoothsap: getConnectedDevices()
,09-06 19:09:59.281  1429  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 19:09:59.291  1364  1364 D BluetoothA2dp: Proxy object connected
09-06 19:09:59.291  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 19:09:59.291  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 19:09:59.291  1364  1364 D A2dpProfile: Bluetooth service connected
09-06 19:09:59.291  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.291  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.291  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-06 19:09:59.291  1429  2725 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 19:09:59.291  1014  1044 D BluetoothPan: Binding service...
,09-06 19:09:59.291  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 19:09:59.291  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 19:09:59.291  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 19:09:59.291  1364  6602 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 19:09:59.291  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 19:09:59.291  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.291  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.291  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:09:59.291  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.291  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 19:09:59.291  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 19:09:59.291  1364  1364 D BluetoothMap: Proxy object connected
09-06 19:09:59.291  1364  1364 D MapProfile: Bluetooth service connected
09-06 19:09:59.291  1364  1364 D BluetoothMap: getConnectedDevices()
,09-06 19:09:59.291  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.291  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-06 19:09:59.291  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 19:09:59.301  1171  1171 D BluetoothTile:  onBluetoothStateChange:
,09-06 19:09:59.301  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@336070dc, true
,09-06 19:09:59.301  1171  1171 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 19:09:59.301  1171  1171 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 19:09:59.301  1171  1171 D BluetoothTile:  getBluetoothState : 12
,09-06 19:09:59.301  1792  1792 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 19:09:59.311  1429  1429 D BluetoothHeadset: registerMessageListener
09-06 19:09:59.311  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:59.311  1014  1137 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.311  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:09:59.311  1014  3243 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 19:09:59.311  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 19:09:59.311  1171  1171 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 19:09:59.311  1014  1315 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:09:59.311  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.311  1364  1364 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.311  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.311  6833  6864 D HeadsetService: registerMessageListener
09-06 19:09:59.311  1014  1315 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 19:09:59.311  1171  1743 D BluetoothTile:  handleUpdatestate:false name:null
09-06 19:09:59.311  6833  6864 D HeadsetService: registerMessageListener
09-06 19:09:59.321  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 19:09:59.321  6833  6863 D HeadsetStateMachine: Disconnected process message: 70
,09-06 19:09:59.321  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 19:09:59.321  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 19:09:59.321  6833  6863 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@211f1599
,09-06 19:09:59.321  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-06 19:09:59.321  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 19:09:59.321  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 19:09:59.321  1364  1364 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-06 19:09:59.321  6833  6863 D HeadsetStateMachine: Disconnected process message: 9
,09-06 19:09:59.331  6833  6863 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-06 19:09:59.331  1364  1364 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 19:09:59.331  1364  1364 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 19:09:59.331  1364  1364 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 19:09:59.331  6833  6903 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 19:09:59.341   282  1138 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-06 19:09:59.341   282  1138 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 19:09:59.341   282  1138 V voice   : voice_set_parameters: exit with code(-2)
09-06 19:09:59.341   282  1138 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 19:09:59.341   282  1138 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 19:09:59.341   282  1138 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 19:09:59.341   282  1138 V audio_hw_primary: adev_set_parameters: exit
,09-06 19:09:59.341  1364  1364 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 19:09:59.341  6833  6903 D BluetoothSocket: bindListen(): myUserId = 0
09-06 19:09:59.341  6833  6903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 19:09:59.341  6833  6863 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 19:09:59.341  1014  1369 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 19:09:59.341  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.341  6833  6903 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 19:09:59.341  6833  6903 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.341  6833  6903 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.341  6833  6903 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2027005e
,09-06 19:09:59.341  6833  6903 D BluetoothSocket: channel: 5
09-06 19:09:59.341  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.341  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.341  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 19:09:59.351  1364  1364 D DockEventReceiver: finishStartingService: stopping service
,09-06 19:09:59.361  1364  1364 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 19:09:59.361  1171  1171 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 19:09:59.361  1171  1171 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 19:09:59.371  6833  6833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:09:59.371  6833  6833 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 19:09:59.371  1014  3245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 19:09:59.371  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.371  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.371  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:09:59.371  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 19:09:59.391  1934  1934 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 19:09:59.391  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 19:09:59.391  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 19:09:59.391  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.391  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:59.391  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:59.401  1014  1137 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 19:09:59.411  1934  6912 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 19:09:59.411  1934  1934 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 19:09:59.411  1014  1374 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 19:09:59.411  1014  1374 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:09:59.411  1014  1374 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:59.411  1014  1374 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:59.421  6833  6913 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 19:09:59.421  6833  6913 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 19:09:59.421  6833  6913 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-06 19:09:59.421  6833  6913 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 19:09:59.421  6833  6913 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 19:09:59.421  6833  6913 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@385ec46a
,09-06 19:09:59.431  6833  6913 D BluetoothSocket: channel: 12,
09-06 19:09:59.431  6833  6913 I BtOppRfcommListener: Accept thread started.
,09-06 19:09:59.431  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,09-06 19:09:59.431  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:09:59.431  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:09:59.431  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:09:59.441  1934  6912 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 19:09:59.991  1014  1093 V AlarmManager: waitForAlarm result :8
,09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:00.061  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:00.061  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:00.061  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:00.061  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5cb109d added. We now have 8 listener(s)
09-06 19:10:00.061  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:00.071  1014  3245 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:10:00.071  1014  3245 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:10:00.071  1014  3245 D SecContentProvider2: mCursor = null
,09-06 19:10:00.071  1014  3245 D WifiService: setWifiEnabled: false pid=6164, uid=10155
,09-06 19:10:00.071  1014  3245 D SettingsProvider: name = wifi_on
,09-06 19:10:00.081  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.081  1014  1546 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 19:10:00.081  1014  1546 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 19:10:00.081  1014  1546 D SecContentProvider2: mCursor = null
,09-06 19:10:00.081  1014  1546 D WifiService: setWifiEnabled: true pid=6164, uid=10155
,09-06 19:10:00.081  1014  1546 W ActivityManager: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 19:10:00.081  1014  1546 W WifiService: Failed getting userId using ActivityManagerNative
09-06 19:10:00.081  1014  1546 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6164, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 19:10:00.081  1014  1546 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 19:10:00.081  1014  1546 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 19:10:00.081  1014  1546 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 19:10:00.081  1014  1546 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 19:10:00.081  1014  1546 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 19:10:00.081  1014  1546 D SettingsProvider: name = wifi_on
,09-06 19:10:00.091  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 19:10:00.451  1014  1042 D Tethering: interfaceAdded wlan0
,09-06 19:10:00.461  1014  1128 E Tethering: No numeric data
,09-06 19:10:00.461  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:10:00.461  1014  1128 D Tethering: clearTetheredNotification()
,09-06 19:10:00.461  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.461  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:00.461  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:00.461  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:00.471  1014  1122 V NetworkStats: performPollLocked() took 6ms
,09-06 19:10:00.471  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.471  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 19:10:00.471  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:00.471  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:00.471  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:00.471  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:10:00.471  1014  1128 D Tethering: InitialState.processMessage what=4
,09-06 19:10:00.471  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.481  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.481  1014  1128 E Tethering: No numeric data
09-06 19:10:00.481  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 19:10:00.481  1014  1128 D Tethering: clearTetheredNotification()
09-06 19:10:00.481  1014  1042 D Tethering: interfaceAdded p2p0
,09-06 19:10:00.481  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 19:10:00.491  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 19:10:00.491  1171  1171 D HotspotTile: updateTetherState():false, false
09-06 19:10:00.491  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.491  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:00.491  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:00.491  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:00.491  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:10:00.491  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated,
,09-06 19:10:00.491  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 19:10:00.491   277  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 19:10:00.501   277  1012 D SoftapController: Softap fwReload - Ok
,09-06 19:10:00.501  1014  1122 V NetworkStats: performPollLocked() took 8ms
09-06 19:10:00.501  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.501   277  1012 D CommandListener: Setting iface cfg
09-06 19:10:00.501   277  1012 D CommandListener: Trying to bring down wlan0
,09-06 19:10:00.501  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:00.501  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:00.501   277  1012 D CommandListener: Clearing all IP addresses on wlan0
,09-06 19:10:00.511  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 19:10:00.511  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-06 19:10:00.521  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:00.521  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 19:10:00.521  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.521  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.521  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:00.521  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:00.531  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:00.531  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:00.531  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 19:10:00.531  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:10:00.531  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:00.531  1171  1171 D HotspotTile: onReceive : 2, 0
,09-06 19:10:00.531  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:00.531  1014  3243 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 19:10:00.531  1014  3243 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:00.541  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:00.541  1014  3243 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:00.541  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:00.541  3680  3680 I Hs20UtilService: Starting #17,
,09-06 19:10:00.541  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:10:00.541  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 19:10:00.541  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:10:00.541  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:10:00.541  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:10:00.571  6925  6925 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 19:10:00.571  6925  6925 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-06 19:10:00.571  6925  6925 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 19:10:00.591  6925  6925 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-06 19:10:00.591   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6925
09-06 19:10:00.591   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 19:10:00.591  6925  6925 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,09-06 19:10:00.591  6925  6925 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:00.591  6925  6925 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-06 19:10:00.591  6925  6925 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 19:10:00.591   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6925
09-06 19:10:00.591   349   349 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-06 19:10:00.751   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,09-06 19:10:00.761  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-06 19:10:00.821  6925  6925 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 19:10:00.821  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-06 19:10:00.831  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-06 19:10:00.831   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6925
09-06 19:10:00.831   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-06 19:10:00.831  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
09-06 19:10:00.831  6925  6925 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:00.831  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.831  6925  6925 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:00.831  6925  6925 E wpa_supplicant: SIM READ ERROR
09-06 19:10:00.831  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.831  6925  6925 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:00.831  6925  6925 E wpa_supplicant: SIM READ ERROR
09-06 19:10:00.831  6925  6925 I wpa_supplicant: Blacklist: Clear (all) 
09-06 19:10:00.831  6925  6925 I wpa_supplicant: wpa_default_ap_write_once,
09-06 19:10:00.831  6925  6925 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:00.831  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.831  6925  6925 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 19:10:00.831  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:00.831  6925  6925 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 19:10:00.841  6925  6925 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 19:10:00.841  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:00.841  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:00.841  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:00.981  6925  6925 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 19:10:01.111  6925  6925 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 19:10:01.111  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-06 19:10:01.121  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-06 19:10:01.121   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6925
09-06 19:10:01.121   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-06 19:10:01.121  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-06 19:10:01.121  6925  6925 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:01.121  6925  6925 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-06 19:10:01.121  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-06 19:10:01.141  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-06 19:10:01.141   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6925
09-06 19:10:01.141   349   349 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-06 19:10:01.141  6925  6925 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-06 19:10:01.141  6925  6925 I wpa_supplicant: ssSupport state is = 1
09-06 19:10:01.141  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 19:10:01.141  6925  6925 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.141  6925  6925 E wpa_supplicant: SIM READ ERROR
,09-06 19:10:01.141  6925  6925 I wpa_supplicant: wpa_default_ap_write_once
09-06 19:10:01.141  6925  6925 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 19:10:01.141  6925  6925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 19:10:01.141  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.151  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.141  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:10:01.151  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.151  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 19:10:01.151  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,09-06 19:10:01.201  6925  6925 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-06 19:10:01.201  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 19:10:01.241  6925  6925 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 19:10:01.241  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-06 19:10:01.241  6925  6925 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-06 19:10:01.251  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 19:10:01.251  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-06 19:10:01.251  6925  6925 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 19:10:01.251  6925  6925 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 19:10:01.251  6925  6925 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 19:10:01.251  6925  6925 E wpa_supplicant: SIM READ ERROR
,09-06 19:10:01.251  6925  6925 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 19:10:01.281  6925  6925 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 19:10:01.291  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
09-06 19:10:01.291  6925  6925 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 19:10:01.291  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-06 19:10:01.291  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:01.291  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:01.291  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.291  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.291  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.291  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:01.291  1171  1171 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 19:10:01.291  1171  1171 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 19:10:01.291   287   287 E SMD     : DCD OFF
09-06 19:10:01.291  1171  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 19:10:01.291  1171  1171 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.301  1171  1171 D HotspotTile: onReceive : 3, 0
,09-06 19:10:01.301  1364  1364 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 19:10:01.301  1014  1125 E WifiConfigStore: Not a HS20
,09-06 19:10:01.301  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 19:10:01.301  1014  1546 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:01.301  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 19:10:01.301  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 19:10:01.311  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:01.311  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:01.311  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 19:10:01.311  6925  6925 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 19:10:01.311  6925  6925 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 19:10:01.311  6925  6925 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 19:10:01.311  6925  6925 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 19:10:01.311  6925  6925 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 19:10:01.311  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 19:10:01.311  6925  6925 I wpa_supplicant: First Scan Start
09-06 19:10:01.311  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:01.311  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 19:10:01.311  6925  6925 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 19:10:01.311  3680  3680 I Hs20UtilService: Starting #18
,09-06 19:10:01.311  3680  3696 I Hs20UtilService: Message received 5011
,09-06 19:10:01.311  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-06 19:10:01.311  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 19:10:01.311  1014  1125 I WifiNative-HAL: startHal
09-06 19:10:01.311  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9cb8a88c
09-06 19:10:01.311  1014  1125 I WifiNative-HAL: Could not start hal
,09-06 19:10:01.321  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:01.321  6391  6391 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 19:10:01.321  1014  1125 E WifiNative-wlan0: do suspend true
,09-06 19:10:01.321  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 19:10:01.321  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-06 19:10:01.321   277  1012 D CommandListener: Setting iface cfg
09-06 19:10:01.321   277  1012 D CommandListener: Trying to bring up p2p0
,09-06 19:10:01.321  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 19:10:01.321  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 19:10:01.321  1014  1124 D WifiP2pService: P2pEnablingState
09-06 19:10:01.321  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-06 19:10:01.321  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 19:10:01.321  1014  1149 I WifiNative-HAL: startHal
09-06 19:10:01.321  1014  1124 D WifiP2pService: P2p socket connection successful
09-06 19:10:01.321  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9def19bc
,09-06 19:10:01.321  1014  1124 D WifiP2pService: P2pEnabledState
09-06 19:10:01.321  1014  1149 I WifiNative-HAL: Could not start hal
09-06 19:10:01.321  1014  1149 E WifiScanningService: could not start HAL,
09-06 19:10:01.331  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 19:10:01.331  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.331  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-06 19:10:01.331  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-06 19:10:01.331  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:10:01.331  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-06 19:10:01.331  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:01.331  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 19:10:01.331  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 19:10:01.331  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-06 19:10:01.331  6925  6925 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.331  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:10:01.331  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
09-06 19:10:01.331  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 19:10:01.331  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
09-06 19:10:01.331  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 19:10:01.331  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 19:10:01.331  1014  1045 D WifiDisplayController: disconnect
09-06 19:10:01.331  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-06 19:10:01.331  1014  1045 D WifiDisplayController: updateConnection
09-06 19:10:01.331  6925  6925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 19:10:01.331  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-06 19:10:01.331  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 19:10:01.331  6925  6925 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-06 19:10:01.331  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 19:10:01.341  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
09-06 19:10:01.341  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 19:10:01.341  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 19:10:01.341  1171  1171 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-06 19:10:01.341  1014  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 19:10:01.341  1171  1171 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 19:10:01.341  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.341  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:10:01.341  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-06 19:10:01.341  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-06 19:10:01.351  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:01.351  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:10:01.351  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 19:10:01.351  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  secondary type: null
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  wps: 0
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  grpcapab: 0
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  devcapab: 0
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  status: 3
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  wfdInfo: null
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  groupownerAddress: null
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  GOdeviceName: null
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  interfaceAddress: 
09-06 19:10:01.351  1014  1045 D WifiDisplayController:  SConnectInfo : null
09-06 19:10:01.351  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:01.351  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-06 19:10:01.351  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:10:01.351  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:10:01.351  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:10:01.351  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 19:10:01.351  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:01.361  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.361  6360  6360 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 19:10:01.361  6360  6360 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 19:10:01.371  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 19:10:01.371  1014  1124 D WifiP2pService: InactiveState
,09-06 19:10:01.371  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:10:01.371  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.371  6925  6925 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 19:10:01.371  6375  6375 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 19:10:01.381  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-06 19:10:01.381  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 19:10:01.471  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,09-06 19:10:01.471  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
09-06 19:10:01.471  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 19:10:01.731  1014  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 19:10:01.741  1014  1137 D BatteryService: level:98, scale:100, status:2, health:2, present:true, voltage: 4231, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-06 19:10:01.741  1014  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 19:10:01.741  1014  1137 D BatteryService: stay LED for charging
09-06 19:10:01.741  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 19:10:01.741  1014  1014 I MotionRecognitionService: Plugged
,09-06 19:10:01.741  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 19:10:01.741  1171  1171 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 19:10:01.741  1171  1171 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 19:10:01.751  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 19:10:01.751  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 98
,09-06 19:10:01.761  6833  6833 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 19:10:01.761  6833  6863 D HeadsetStateMachine: Disconnected process message: 10
,09-06 19:10:01.771  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:10:01.771  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:10:01.771  1171  1171 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:98 status:2 health:2
,09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:02.101  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:02.101  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:02.111  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 19:10:02.111  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 19:10:02.111  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@10f78881 Bundle[{}]
,09-06 19:10:02.111  6164  6217 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 19:10:02.121  6164  6217 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 19:10:02.121  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 19:10:02.121  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
,09-06 19:10:02.121  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-06 19:10:02.121  6164  6217 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 19:10:02.131  6164  6217 I System.out: Running OutgoingSocketThread
,09-06 19:10:02.131  6164  6933 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1163)
,09-06 19:10:02.131  6164  6933 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50501
,09-06 19:10:02.131  6164  6933 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-06 19:10:02.551  6925  6925 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
09-06 19:10:02.551  6925  6925 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 19:10:02.551  6925  6925 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 19:10:02.551  6925  6925 I wpa_supplicant: Trying to associate with  'G700'
09-06 19:10:02.551  6925  6925 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-06 19:10:02.551  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 19:10:02.551  1014  6930 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 19:10:02.571  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.571  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:10:02.691  6925  6925 E wpa_supplicant: Cmd 35605 not handled
,09-06 19:10:02.691  6925  6925 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:10:02.691  6925  6925 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-06 19:10:02.691  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.691  6925  6925 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 19:10:02.691  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 19:10:02.691  6925  6925 I wpa_supplicant: Associated with F4.99.3E
09-06 19:10:02.691  6925  6925 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:10:02.691  6925  6925 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 19:10:02.691  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-06 19:10:02.691  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.691  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:02.701  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.701  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.701  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,09-06 19:10:02.701  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 19:10:02.701  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
09-06 19:10:02.701  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 19:10:02.701  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.701  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:10:02.701  1014  1128 E Tethering: No numeric data
09-06 19:10:02.701  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.701  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 19:10:02.701  1014  1128 D Tethering: clearTetheredNotification()
09-06 19:10:02.711  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-06 19:10:02.711  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.711  1171  1171 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 19:10:02.711  1171  1171 D HotspotTile: updateTetherState():false, false
,09-06 19:10:02.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:02.711  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:02.711  1014  1122 V NetworkStats: performPollLocked() took 7ms
,09-06 19:10:02.711  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:02.721  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.721  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:10:02.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:02.721  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:02.721  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.721  1014  1125 D SecContentProvider2: mCursor = null
,09-06 19:10:02.721  6925  6925 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 19:10:02.721  6925  6925 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 19:10:02.731  6925  6925 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 19:10:02.731  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:10:02.731  6925  6925 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-06 19:10:02.731  6925  6925 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 19:10:02.731  6925  6925 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 19:10:02.731  6925  6925 I wpa_supplicant: Blacklist: Clear (temp) 
09-06 19:10:02.731  6925  6925 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 19:10:02.731  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.731  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 19:10:02.731  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
,09-06 19:10:02.731  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50],
,09-06 19:10:02.741  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 19:10:02.741  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 19:10:02.741  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 19:10:02.741  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:10:02.741  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 19:10:02.751  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:02.751  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:02.751  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.751  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.751  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.751  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 19:10:02.751  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:02.751  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:02.751  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:02.751  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:02.751  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:02.751  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:02.761  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 19:10:02.771  3680  3680 I Hs20UtilService: Starting #19
,09-06 19:10:02.771  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:10:02.771  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:10:02.771  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 19:10:02.771  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 19:10:02.771   277  1012 D CommandListener: Setting iface cfg
,09-06 19:10:02.771  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 19:10:02.771  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 19:10:02.771  1364  1364 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 19:10:02.781  1364  3061 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 19:10:02.781  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-06 19:10:02.781  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-06 19:10:02.781  1014  1125 D SecContentProvider2: mCursor = null,
,09-06 19:10:02.791  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:02.791  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:02.791  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.791  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.791  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:02.791  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:02.801  1014  1125 E WifiNative-wlan0: do suspend false
,09-06 19:10:02.801  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 19:10:02.801  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:10:02.801  1014  1125 D SecContentProvider2: mCursor = null
09-06 19:10:02.801  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:10:02.941  1014  2724 D SSRM:n  : SIOP:: AP = 330
,09-06 19:10:03.021  6938  6938 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 19:10:03.021  6938  6938 I dhcpcd  : version 5.5.6 starting
,09-06 19:10:03.021  6938  6938 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 19:10:03.071  6938  6938 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-06 19:10:03.071  6938  6938 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-06 19:10:03.081  6938  6938 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 19:10:03.081  6938  6938 I dhcpcd  : bssid match
09-06 19:10:03.081  6938  6938 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-06 19:10:03.131  6164  6217 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1164)
,09-06 19:10:03.131  6164  6217 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1164)
,09-06 19:10:03.131  6938  6938 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-06 19:10:03.131  6164  6217 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1169)
09-06 19:10:03.131  6164  6217 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-06 19:10:03.131  6164  6217 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1170)
,09-06 19:10:03.141  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.141  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf41912 added. We now have 2 listener(s)
,09-06 19:10:03.141  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.151  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.151  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.151  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.151  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197e58e3 added. We now have 9 listener(s)
09-06 19:10:03.151  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.151  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.151  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.161  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.161  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.161  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.161  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.161  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.161  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.161  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd1999 added. We now have 3 listener(s)
,09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.171  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.171  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d76b45e added. We now have 10 listener(s)
,09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.171  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.171  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.171  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,09-06 19:10:03.171  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:03.171  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.171  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 19:10:03.171  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf41912 removed from the list
09-06 19:10:03.171  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.171  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197e58e3 removed from the list
09-06 19:10:03.171  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 19:10:03.171  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.181  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.181  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@197e58e3 not in the list
09-06 19:10:03.181  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d76b45e removed from the list
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.181  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fcd1999 removed from the list
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1533a03f added. We now have 2 listener(s)
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.181  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31889d0c added. We now have 9 listener(s)
09-06 19:10:03.181  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 19:10:03.181  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.191  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 19:10:03.191  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.191  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 19:10:03.191  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.191  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf5b86a added. We now have 3 listener(s)
09-06 19:10:03.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.191  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 19:10:03.201  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 19:10:03.201  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.201  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.201  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.201  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecc015b added. We now have 10 listener(s)
09-06 19:10:03.201  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.201  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.201  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.201  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.201  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.201  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 19:10:03.201  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-06 19:10:03.211  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:10:03.211  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 19:10:03.211  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 19:10:03.211  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.211  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 19:10:03.211  6833  6841 D BtGatt.GattService: registerClient() - UUID=f52fe9aa-da44-4b20-920d-534b75fff8ce
09-06 19:10:03.231  6938  6938 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-06 19:10:03.261  6833  6858 D BtGatt.GattService: onClientRegistered() - UUID=f52fe9aa-da44-4b20-920d-534b75fff8ce, clientIf=6,
,09-06 19:10:03.261  6164  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.261  6833  6902 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.271  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.271  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.271  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.271  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.271  6833  6862 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:03.271  6833  6862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3148b877
,09-06 19:10:03.271  6833  6858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-06 19:10:03.271  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.271  6833  6862 D BtGatt.ScanManager: allow scan with filters
09-06 19:10:03.271  6833  6862 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:10:03.271  6833  6862 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 19:10:03.281  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:10:03.281  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.281  6833  6862 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.281  6833  6862 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.281  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.281  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.281  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.281  6833  6858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:10:03.281  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.291  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-06 19:10:03.291  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.291  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.301  6164  6217 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 19:10:03.301  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.301  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 19:10:03.301  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.301  6833  6841 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.301  6833  6902 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.301  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 19:10:03.301  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.311  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.311  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.311  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.311  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:03.311  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.311  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.311  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.311  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.311  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.311  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.311  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1533a03f removed from the list
09-06 19:10:03.311  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.311  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31889d0c removed from the list
09-06 19:10:03.311  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.311  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.311  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.311  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.321  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.321  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.321  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.321  6833  6862 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 21
09-06 19:10:03.321  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31889d0c not in the list
09-06 19:10:03.321  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.321  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.331  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.331  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:10:03.331  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ecc015b removed from the list
09-06 19:10:03.331  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.331  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.331  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.331  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf5b86a removed from the list
09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bf5837 added. We now have 2 listener(s)
,09-06 19:10:03.331  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.331  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 19:10:03.331  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.331  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e381a4 added. We now have 9 listener(s)
09-06 19:10:03.331  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.331  6833  6862 D BtGatt.ScanManager: filter size is 1
09-06 19:10:03.341  6833  6862 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 19:10:03.341  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.341  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-06 19:10:03.341  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 19:10:03.341  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.341  6833  6862 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.351  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.351  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.351  6833  6862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,09-06 19:10:03.351  6833  6858 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.351  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.351  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.361  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.361  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.361  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.361  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df0eac2 added. We now have 3 listener(s)
,09-06 19:10:03.361  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.361  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.371  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.371  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.371  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.371  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.371  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2740d3 added. We now have 10 listener(s)
09-06 19:10:03.371  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.371  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.371  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.371  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 19:10:03.371  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 19:10:03.371  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.371  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.381  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.401  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 19:10:03.401  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-06 19:10:03.421  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.421  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.421  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.431  6833  6841 D BtGatt.GattService: registerClient() - UUID=8005d224-64b0-4923-9e6a-25bd42761793
,09-06 19:10:03.471  6833  6858 D BtGatt.GattService: onClientRegistered() - UUID=8005d224-64b0-4923-9e6a-25bd42761793, clientIf=6
,09-06 19:10:03.471  6164  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 19:10:03.471  6833  6901 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.471  6833  6862 D BtGatt.ScanManager: handling starting scan
,09-06 19:10:03.471  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 19:10:03.471  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.471  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 19:10:03.471  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.471  6833  6858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 19:10:03.471  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.471  6833  6862 D BtGatt.ScanManager: allow scan with filters
,09-06 19:10:03.481  6833  6862 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 19:10:03.481  6833  6862 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 19:10:03.481  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 19:10:03.481  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.481  6833  6862 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.481  6833  6862 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.481  6833  6858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 19:10:03.481  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.481  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.481  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 19:10:03.481  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.481  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 19:10:03.481  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.491  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.501  6833  6862 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 22,
,09-06 19:10:03.501  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 19:10:03.501  6164  6217 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-06 19:10:03.501  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:03.501  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.501  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 19:10:03.501  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.501  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bf5837 removed from the list
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.501  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e381a4 removed from the list
,09-06 19:10:03.501  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.501  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:03.501  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.501  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37e381a4 not in the list
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.501  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.501  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.511  6833  6864 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.511  6833  6862 D BtGatt.ScanManager: filter size is 1
09-06 19:10:03.511  6833  6862 D BtGatt.ScanManager: delete FilterIndex - 4
09-06 19:10:03.511  6833  6841 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.511  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:10:03.511  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 19:10:03.511  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.511  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.511  6833  6862 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.511  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.511  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.511  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 19:10:03.521  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.521  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2740d3 removed from the list,
09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.521  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.521  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2df0eac2 removed from the list
09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1b172f added. We now have 2 listener(s),
,09-06 19:10:03.521  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 19:10:03.521  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.521  6833  6862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.521  6833  6858 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 19:10:03.521  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.521  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.521  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.521  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 19:10:03.521  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f3613c added. We now have 9 listener(s)
09-06 19:10:03.521  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.521  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.531  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.531  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.531  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 19:10:03.531  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.541  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.541  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.541  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 19:10:03.541  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d25101a added. We now have 3 listener(s)
,09-06 19:10:03.541  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.541  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.541  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 19:10:03.541  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.541  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbf74b added. We now have 10 listener(s)
09-06 19:10:03.541  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 19:10:03.541  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.541  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 19:10:03.541  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-06 19:10:03.541  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.541  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 19:10:03.551  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 19:10:03.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 19:10:03.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 19:10:03.551  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 19:10:03.551  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 19:10:03.551  6164  6217 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 19:10:03.561  6833  6901 D BtGatt.GattService: registerClient() - UUID=f81fc65d-302f-4540-9413-2a4ccb19193d
,09-06 19:10:03.601  6833  6858 D BtGatt.GattService: onClientRegistered() - UUID=f81fc65d-302f-4540-9413-2a4ccb19193d, clientIf=6
,09-06 19:10:03.601  6164  6178 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 19:10:03.601  6833  6844 D BtGatt.GattService: start scan with filters
,09-06 19:10:03.601  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 19:10:03.601  6833  6862 D BtGatt.ScanManager: handling starting scan
09-06 19:10:03.601  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 19:10:03.601  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 19:10:03.601  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 19:10:03.601  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 19:10:03.611  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-06 19:10:03.611  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 19:10:03.611  6833  6858 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 19:10:03.611  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.611  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 19:10:03.611  6833  6862 D BtGatt.ScanManager: allow scan with filters
,09-06 19:10:03.611  6833  6862 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
09-06 19:10:03.611  6833  6862 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 19:10:03.621  1014  1125 E WifiNative-wlan0: do suspend true,
,09-06 19:10:03.621  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 19:10:03.621  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.621  6833  6862 D BtGatt.ScanManager: Starting BLE batch scan
09-06 19:10:03.621  6833  6862 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 19:10:03.621  6833  6858 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 19:10:03.621  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.621  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 19:10:03.631  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.631  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.631  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 19:10:03.631  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.631  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.631  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.631  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 19:10:03.631  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.631  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1b172f removed from the list
09-06 19:10:03.631  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.631  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f3613c removed from the list
09-06 19:10:03.631  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop
09-06 19:10:03.631  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.631  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.631  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 19:10:03.631  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.631  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.641  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35f3613c not in the list
,09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 19:10:03.641  6833  6902 D BtGatt.GattService: stopScan() - queue size =1
,09-06 19:10:03.641  6833  6864 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 19:10:03.641  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 19:10:03.641  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.651  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
09-06 19:10:03.651  6833  6862 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
09-06 19:10:03.651  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 19:10:03.651  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 19:10:03.651  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.651  6164  6164 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 19:10:03.651  6164  6164 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 19:10:03.651  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 19:10:03.651  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.651  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cbf74b removed from the list
,09-06 19:10:03.651  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.651  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 19:10:03.651  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.651  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.651  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d25101a removed from the list
,09-06 19:10:03.651  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.651  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a60bd27 added. We now have 2 listener(s)
09-06 19:10:03.651  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,09-06 19:10:03.651  1014  1125 E WifiStateMachine: VerifyingLinkState enter
09-06 19:10:03.651  6833  6862 D BtGatt.ScanManager: filter size is 1
09-06 19:10:03.651  6833  6862 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 19:10:03.651  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-06 19:10:03.651  6833  6858 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 19:10:03.651  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:03.661  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.661  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.661  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.661  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.661  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.661  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.661  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.661  6833  6862 D BtGatt.ScanManager: stopping BLe Batch
,09-06 19:10:03.661  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-06 19:10:03.661  1014  1127 D ConnectivityService: Adding iface wlan0 to network 503
,09-06 19:10:03.661  6833  6858 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 19:10:03.661  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 19:10:03.661  6833  6862 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 19:10:03.671  6833  6858 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-06 19:10:03.671  6833  6858 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 19:10:03.671  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 19:10:03.671  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.671  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.671  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.671  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fc9bd4 added. We now have 9 listener(s)
09-06 19:10:03.671  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.671  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 19:10:03.681  1014  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-06 19:10:03.681  1014  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 19:10:03.681  1014  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.681  1014  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
09-06 19:10:03.681  1014  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 19:10:03.681  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 19:10:03.681  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.681  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503,
09-06 19:10:03.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.691  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
09-06 19:10:03.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.681  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.691  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-06 19:10:03.691  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 19:10:03.691  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 19:10:03.691  1014  1127 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
09-06 19:10:03.691  1014  1127 D ConnectivityService: LTETest block dns file not exists
,09-06 19:10:03.691  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-06 19:10:03.691  1014  3243 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.691  1014  3243 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.691  1014  3243 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.691  1014  3243 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.691  1014  3243 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.691  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-06 19:10:03.691  3680  3680 I Hs20UtilService: Starting #20
,09-06 19:10:03.701  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:10:03.701  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:10:03.701  1364  1364 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.701  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-06 19:10:03.711  1014  1127 E ConnectivityService: updateNetworkInfo()
09-06 19:10:03.711  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 19:10:03.711  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
09-06 19:10:03.711  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-06 19:10:03.711  1014  6936 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.711  1014  6936 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 19:10:03.711  1014  6936 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 19:10:03.711  1014  6936 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 19:10:03.711  1014  6936 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 19:10:03.711   277  1008 D EnterpriseController: uids 1000
09-06 19:10:03.711   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:10:03.711   277  1008 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-06 19:10:03.711  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 19:10:03.711  6164  6217 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 19:10:03.711  1014  1127 D ConnectivityService:    accepting network in place of null
,09-06 19:10:03.721  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 19:10:03.721  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 19:10:03.721  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-06 19:10:03.721  1458  1458 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:10:03.721  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 19:10:03.721  1458  1458 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 19:10:03.721  6164  6217 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 19:10:03.721  6164  6217 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 19:10:03.721  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 19:10:03.721  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45d8872 added. We now have 3 listener(s)
,09-06 19:10:03.721  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 19:10:03.721  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 19:10:03.721  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.731  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.731  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.731  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.731  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-06 19:10:03.731  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,09-06 19:10:03.731  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 19:10:03.731  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-06 19:10:03.731  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 19:10:03.731  1171  1737 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 19:10:03.741  3771  6226 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 19:10:03.741  1014  1122 V NetworkStats: updateIfacesLocked()
09-06 19:10:03.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.741  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-06 19:10:03.741  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 19:10:03.741  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:03.741  1014  1122 V NetworkStats: performPollLocked() took 3ms
09-06 19:10:03.741  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:03.741  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:03.741  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 19:10:03.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 19:10:03.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 19:10:03.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 19:10:03.741  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 19:10:03.741  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159204c3 added. We now have 10 listener(s)
09-06 19:10:03.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 19:10:03.741  6164  6217 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 19:10:03.741  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 19:10:03.741  6164  6217 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 19:10:03.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.741  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.741  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 19:10:03.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.741  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a60bd27 removed from the list
09-06 19:10:03.741  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.741  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fc9bd4 removed from the list
,09-06 19:10:03.751  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.751  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 19:10:03.751  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 19:10:03.751  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,09-06 19:10:03.751  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:03.751  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 19:10:03.751  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.751  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.751  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.751  1171  1171 D StatusBar.NetworkController: EthernetConnected: false
09-06 19:10:03.751  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 19:10:03.751  1171  1171 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 19:10:03.751  1171  1171 D StatusBar.NetworkController: updateDataNetType()
09-06 19:10:03.751  1171  1171 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 19:10:03.751  1171  1171 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 19:10:03.751  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 19:10:03.751  6164  6217 D io.jxcore.node.ConnectivityMonitor: stop,
09-06 19:10:03.751  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.751  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.761  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 19:10:03.761  1171  1171 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 19:10:03.761  1171  1171 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 19:10:03.771  1014  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.771  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:03.771  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.771  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.771  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.771  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:03.771  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 19:10:03.771  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.771  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.771  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:03.771  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.771  6164  6217 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fc9bd4 not in the list
,09-06 19:10:03.771  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.771  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 19:10:03.781  3680  3680 I Hs20UtilService: Starting #21
,09-06 19:10:03.781  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 19:10:03.781  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:10:03.781  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 19:10:03.781  6164  6217 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 19:10:03.781  6164  6217 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@159204c3 removed from the list
09-06 19:10:03.781  6164  6217 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 19:10:03.781  6164  6217 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 19:10:03.781  6164  6217 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 19:10:03.781  6164  6217 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 19:10:03.781  6164  6217 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45d8872 removed from the list
,09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-06 19:10:03.781  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-06 19:10:03.781  1364  1364 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 19:10:03.781  6164  6217 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 19:10:03.781  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-06 19:10:03.781  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 19:10:03.781  1364  1364 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-06 19:10:03.781  1364  1364 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.791  6164  6976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1177, name: My test thread name)
,09-06 19:10:03.791  6164  6976 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1177, thread name: My test thread name)
09-06 19:10:03.791  6164  6976 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1177, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.791  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 19:10:03.791  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 19:10:03.791  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:03.791  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:03.791  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 19:10:03.791  6164  6977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1179, name: My test thread name)
09-06 19:10:03.791  6164  6977 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1179, thread name: My test thread name)
09-06 19:10:03.791  6164  6977 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1179, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 19:10:03.791  3680  3680 I Hs20UtilService: Starting #22
,09-06 19:10:03.801  3680  3696 I Hs20UtilService: Message received 5007
,09-06 19:10:03.801  1364  1364 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 19:10:03.801  6164  6217 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 19:10:03.801  6164  6217 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 19:10:03.801  6164  6217 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 19:10:03.801  6164  6217 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 19:10:03.801  6164  6217 D com.test.thalitest.ThaliTestRunner: Total duration: 24400 ms
09-06 19:10:03.801  1364  1364 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 19:10:03.801  6164  6217 I jxcore-log: *Native tests were executed*
09-06 19:10:03.801  6164  6217 I jxcore-log: 
,09-06 19:10:03.801  6164  6217 I jxcore-log: Total number of executed tests:  80
09-06 19:10:03.801  6164  6217 I jxcore-log: 
09-06 19:10:03.801  6164  6217 I jxcore-log: Number of passed tests:  80
09-06 19:10:03.801  6164  6217 I jxcore-log: 
,09-06 19:10:03.801  6164  6217 I jxcore-log: Number of failed tests:  0
09-06 19:10:03.801  6164  6217 I jxcore-log: 
09-06 19:10:03.801  6164  6217 I jxcore-log: Number of ignored tests:  0
09-06 19:10:03.801  6164  6217 I jxcore-log: 
,09-06 19:10:03.801  6164  6217 I jxcore-log: Total duration:  24400
09-06 19:10:03.801  6164  6217 I jxcore-log: 
09-06 19:10:03.801  6164  6217 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 19:10:03.801  6164  6217 I jxcore-log: 
,09-06 19:10:03.801  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.801  6164  6217 I jxcore-log: 
09-06 19:10:03.811  6164  6164 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.811  1014  1374 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-06 19:10:03.811  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.811  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  1014  1369 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-06 19:10:03.821  1014  1369 D SecContentProvider2: mCursor = null
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
,09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
,09-06 19:10:03.821  1014  3245 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  1014  3245 D SecContentProvider2: mCursor = null
,09-06 19:10:03.821  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.821  6164  6217 I jxcore-log: 
09-06 19:10:03.821  6164  6164 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
09-06 19:10:03.831  1014  3243 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
09-06 19:10:03.831  1014  3243 D SecContentProvider2: mCursor = null
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
09-06 19:10:03.831  1014  1026 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 19:10:03.831  1014  1026 D SecContentProvider2: mCursor = null
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:03.831  6164  6217 I jxcore-log: 
,09-06 19:10:03.831  1014  1544 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
09-06 19:10:03.831  1014  1544 D SecContentProvider2: mCursor = null
,09-06 19:10:03.841  1014  1315 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-06 19:10:03.841  1014  1315 D SecContentProvider2: mCursor = null
,09-06 19:10:03.861   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-06 19:10:03.881  1014  1374 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-06 19:10:03.881  1171  1171 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 19:10:04.021  6164  6164 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 19:10:04.021  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.021  6164  6217 I jxcore-log: 
,09-06 19:10:04.091  6978  6978 D AndroidRuntime: 
09-06 19:10:04.091  6978  6978 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 19:10:04.101  6978  6978 D AndroidRuntime: CheckJNI is OFF
,09-06 19:10:04.101  6978  6978 D AndroidRuntime: readGMSProperty: start
09-06 19:10:04.101  6978  6978 D AndroidRuntime: readGMSProperty: already setted!!
09-06 19:10:04.101  6978  6978 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 19:10:04.101  6978  6978 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 19:10:04.101  6978  6978 D AndroidRuntime: readGMSProperty: end
09-06 19:10:04.101  6978  6978 D AndroidRuntime: addProductProperty: start
,09-06 19:10:04.151  6164  6164 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 19:10:04.151  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 19:10:04.151  6164  6217 I jxcore-log: 
,09-06 19:10:04.231  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.241  6978  6978 E AffinityControl: AffinityControl: registerfunction enter,
,09-06 19:10:04.241  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.261  3147  3147 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 19:10:04.281  6164  6164 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 19:10:04.291  6164  6164 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 19:10:04.291  6164  6217 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 19:10:04.291  6164  6217 I jxcore-log: 
,09-06 19:10:04.291  6978  6978 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 19:10:04.301   287   287 E SMD     : DCD OFF
,09-06 19:10:04.301  6453  6453 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-06 19:10:04.301  6453  6453 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 19:10:04.301  6453  6453 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-06 19:10:04.301  6453  6453 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.301  6470  6470 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-06 19:10:04.301  1014  3244 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-06 19:10:04.301  1014  3244 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 19:10:04.321  1014  1026 D PackageManager: START PACKAGE DELETE: observer{413153573}
09-06 19:10:04.321  1014  1026 D PackageManager: pkg{<packageName>}
09-06 19:10:04.321  1014  1026 D PackageManager: user{0}
09-06 19:10:04.321  1014  1026 D PackageManager: caller{2000}
09-06 19:10:04.321  1014  1026 D PackageManager: flags{2}
09-06 19:10:04.321  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-06 19:10:04.321  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-06 19:10:04.321  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-06 19:10:04.321  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:10:04.321  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 19:10:04.321  1720  1720 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:10:04.321  1014  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-06 19:10:04.321  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-06 19:10:04.321  1014  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 19:10:04.321  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
09-06 19:10:04.321  1014  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 19:10:04.331  1014  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-06 19:10:04.331  6470  6470 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-06 19:10:04.331  1014  1546 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:10:04.331  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 19:10:04.331  6482  6482 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-06 19:10:04.341  1720  1720 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-06 19:10:04.341  1720  1720 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-06 19:10:04.341  1720  1720 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-06 19:10:04.341  1720  1720 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 19:10:04.461  1295  1306 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-06 19:10:04.471  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-06 19:10:04.471  1014  1040 I ActivityManager: Killing 6164:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 19:10:04.481  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{20e01cfb u0 com.test.thalitest/.MainActivity t128}
,09-06 19:10:04.531  1014  1374 I art     : Explicit concurrent mark sweep GC freed 79405(4MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 27MB/41MB, paused 8.560ms total 186.036ms
,09-06 19:10:04.531  1014  1374 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 19:10:04.531  1014  1374 D SecContentProvider2: mCursor = null
09-06 19:10:04.531  1014  1040 W ActivityManager: mDVFSHelper.acquire()
,09-06 19:10:04.551  1720  1720 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-06 19:10:04.551  1720  1720 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 19:10:04.561  1720  1720 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-06 19:10:04.561  1014  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-06 19:10:04.561  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 19:10:04.561  6421  6421 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 19:10:04.561  6421  6421 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 19:10:04.561  6421  6421 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 19:10:04.561  1014  1055 I ActivityManager:   Force finishing activity ActivityRecord{20e01cfb u0 com.test.thalitest/.MainActivity t128 f}
09-06 19:10:04.561  1014  1055 W ActivityManager: Duplicate finish request for ActivityRecord{20e01cfb u0 com.test.thalitest/.MainActivity t128 f}
,09-06 19:10:04.601  1014  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 19:10:04.601  5625  5625 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.016ms total 22.503ms
,09-06 19:10:04.611  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:10:04.611  6482  6482 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-06 19:10:04.611  1014  1040 D InputDispatcher: Focus left window: 6164
,09-06 19:10:04.611  1014  1040 D InputDispatcher: Focused application released
,09-06 19:10:04.611  1014  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 19:10:04.611  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 19:10:04.611  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:10:04.611  5416  5416 I art     : Explicit concurrent mark sweep GC freed 388(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 968us total 35.856ms
,09-06 19:10:04.621  6482  6482 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-06 19:10:04.621  6482  6482 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.stepAnimationLocked:341 com.android.server.wm.WindowAnimator.updateWindowsLocked:292 com.android.server.wm.WindowAnimator.animateLocked:806 
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowAnimator.updateWindowsLocked:451 
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1319 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2059 
09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getDisplayId:1229 com.android.server.wm.WindowStateAnimator.computeShownFrameLocked:1555 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2059 
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:1933 
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1663 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 
09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1673 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 
,09-06 19:10:04.631  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1705 
09-06 19:10:04.641  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 com.android.server.wm.WindowAnimator.animateLocked:812 
,09-06 19:10:04.641  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1707 com.android.server.wm.WindowStateAnimator.setSurfaceBoundariesLocked:2032 com.android.server.wm.WindowStateAnimator.prepareSurfaceLocked:2061 com.android.server.wm.WindowAnimator.animateLocked:812 
,09-06 19:10:04.641  3771  3771 I art     : Explicit concurrent mark sweep GC freed 22636(1368KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 15MB/20MB, paused 1.323ms total 76.984ms
,09-06 19:10:04.641  1014  1045 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.isDefaultDisplay:1845 com.android.server.wm.WindowState.getMultiWindowStyleLw:2377 com.android.server.wm.WindowStateAnimator.updateSurfaceWindowCrop:1723 
,09-06 19:10:04.651  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 19:10:04.651  1014  1027 I WindowState: WIN DEATH: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 19:10:04.661   257  4502 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,09-06 19:10:04.661  1014  1027 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowState.getWindowList:1991 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3693 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 
,09-06 19:10:04.661  1014  1027 E WindowState: getStack: Window{3577b4db u0 com.test.thalitest/com.test.thalitest.MainActivity} couldn't find taskId=128 Callers=com.android.server.wm.WindowState.getDisplayContent:1224 com.android.server.wm.WindowManagerService.removeWindowInnerLocked:3698 com.android.server.wm.WindowManagerService.removeWindowLocked:3559 com.android.server.wm.WindowState$DeathRecipient.binderDied:1650 
,09-06 19:10:04.671  1792  1792 E SamsungIME: mOCRHelper is null
,09-06 19:10:04.671  3771  3789 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-06 19:10:04.671  1934  2114 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 19:10:04.691  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-06 19:10:04.691  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.691  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-06 19:10:04.691  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 19:10:04.701  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 19:10:04.701  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.701  1014  1122 V NetworkStats: performPollLocked() took 10ms
,09-06 19:10:04.711  1439  1439 D PersonaManager: isKioskContainerExistOnDevice,
,09-06 19:10:04.711  3147  3147 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-06 19:10:04.721  1439  1439 D RegisteredServicesCache: empty dynamic service
,09-06 19:10:04.721  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-06 19:10:04.731  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 19:10:04.731  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-06 19:10:04.751  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-06 19:10:04.751  3147  3147 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-06 19:10:04.761  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:10:04 GMT+02:00 2016
,09-06 19:10:04.771  6646  6646 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:04.771  6646  6646 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 19:10:04.771  6646  6646 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-06 19:10:04.771  6646  6646 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-06 19:10:04.771  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-06 19:10:04.781  1014  3245 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:10:04.781  1014  3245 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:10:04.781  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 19:10:04.781  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 19:10:04.781  1014  3245 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:04.781  1014  3245 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:04.781  1014  3245 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:10:04.791  3147  3147 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-06 19:10:04.791  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 19:10:04.791  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:10:04.791  3147  3147 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-06 19:10:04.811  3699  3699 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 19:10:04.811  1014  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-06 19:10:04.811  1014  1026 D SecContentProvider2: mCursor = null
,09-06 19:10:04.811  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:04.821  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-06 19:10:04.841  1014  3244 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-06 19:10:04.841  1014  3244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-06 19:10:04.841  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-06 19:10:04.851  1014  1546 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 19:10:04.851  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 19:10:04.851  3699  3699 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:10:04.851  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:04.851  1014  1546 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 19:10:04.851  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 19:10:04.851  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-06 19:10:04.861  3147  3147 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-06 19:10:04.861  3699  3699 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 19:10:04.861  3147  3147 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-06 19:10:04.861  3147  3147 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-06 19:10:04.861  1014  1055 I art     : Explicit concurrent mark sweep GC freed 19142(1583KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 6.325ms total 247.624ms
,09-06 19:10:04.871  3147  3147 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-06 19:10:04.871   277  1008 D EnterpriseController: uids 10012
09-06 19:10:04.871   277  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 19:10:04.871   277  1008 D Netd    : getNetworkForDns: using netid 503 for uid 10012
,09-06 19:10:04.871  3699  6991 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 19:10:04.881  3699  6991 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 19:10:04.881  3699  6991 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-06 19:10:04.891  1014  1546 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-06 19:10:04.891  1014  1546 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-06 19:10:04.891  1014  1546 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:04.891  1014  1546 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:04.891  1014  1546 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-06 19:10:04.891  3699  6991 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-06 19:10:04.891  1014  3244 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 19:10:04.891  1014  3244 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 19:10:04.891  1014  3244 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-06 19:10:04.891  3147  3147 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-06 19:10:04.891  3699  6991 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-06 19:10:04.901  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-06 19:10:04.901  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-06 19:10:04.911  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 19:10:04.911  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-06 19:10:04.911  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-06 19:10:04.911  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-06 19:10:04.921  3699  6991 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-06 19:10:04.921  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-06 19:10:04.921  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 19:10:04.921  3699  6991 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-06 19:10:04.921  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 19:10:04.921  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-06 19:10:04.921  1014  1055 D PackageManager: delete codoeFile: 
,09-06 19:10:04.931  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 19:10:04.931  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-06 19:10:04.931  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-06 19:10:04.931  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 19:10:04.931  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-06 19:10:04.931  1014  2724 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 19:10:04.931  1014  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-06 19:10:04.931  1014  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-06 19:10:04.931  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-06 19:10:04.931  1014  1039 W TextServicesManagerService: no available spell checker services found
09-06 19:10:04.941  3699  3699 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-06 19:10:04.941   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-06 19:10:04.941  1014  1055 D PackageManager: result of delete: 1{413153573}
,09-06 19:10:04.941  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 19:10:04.941  3771  3771 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 19:10:04.951  1014  1137 D InputDispatcher: Focus entered window: 3147
,09-06 19:10:04.951  3771  4526 I iu.UploadsManager: num queued entries: 0
09-06 19:10:04.951  3771  4526 I iu.UploadsManager: num updated entries: 0
,09-06 19:10:04.951  3771  4526 I iu.SyncManager: NEXT; no task
,09-06 19:10:04.951  3147  3147 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-06 19:10:04.951  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 19:10:04.951  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 19:10:04.951  6978  6978 D AndroidRuntime: Shutting down VM
,09-06 19:10:04.961  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.961  1014  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 19:10:04.961  1014  1055 D PackageManager: userId{-1}
09-06 19:10:04.961  1014  1055 D PackageManager: andCode{true}
,09-06 19:10:04.961  3147  3147 V ActivityThread: updateVisibility : ActivityRecord{2b564e45 token=android.os.BinderProxy@8c40d40 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-06 19:10:04.961  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.971  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:04.981  1014  3244 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 19:10:04.981  1014  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.001  1014  7002 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 19:10:05.001  1014  1374 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-06 19:10:05.001  3248  7004 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-06 19:10:05.001  3248  7004 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-06 19:10:05.001  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.001  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.001  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.001  1014  1374 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.011  3248  7004 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 19:10:05.011  1014  3244 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6164 uid 10155
,09-06 19:10:05.011  3147  3147 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8c40d40 time:149504
,09-06 19:10:05.011  1792  1792 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,09-06 19:10:05.021  7006  7006 E Zygote  : MountEmulatedStorage()
09-06 19:10:05.021  7006  7006 E Zygote  : v2
09-06 19:10:05.021  7006  7006 I libpersona: KNOX_SDCARD checking this for 10035
09-06 19:10:05.021  7006  7006 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:05.021  7006  7006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 19:10:05.021  1014  1374 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7006 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 19:10:05.031  7006  7006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 19:10:05.031  7006  7006 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-06 19:10:05.031  1014  1045 W ActivityManager: mDVFSHelper.release()
09-06 19:10:05.031  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1e1d6d19 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149523
09-06 19:10:05.031  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
09-06 19:10:05.031  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
09-06 19:10:05.031  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-06 19:10:05.031  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 19:10:05.031  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 19:10:05.051  1934  6993 I qtaguid : Tagging socket 61 with tag 1000040700000000{268436487,0} for uid -1, pid: 1934, getuid(): 10012
,09-06 19:10:05.061  6698  6698 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:05.071  1171  1171 D PanelView: There is/are notification(s) 
,09-06 19:10:05.081  7006  7006 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 19:10:05.081  7006  7006 D ActivityThread: Added TimaKeyStore provider
,09-06 19:10:05.081  1171  1171 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-06 19:10:05.081  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:10:05.081  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
09-06 19:10:05.081  1171  1171 D PanelView: There is/are notification(s) 
09-06 19:10:05.081  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-06 19:10:05.081  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 19:10:05.081  3248  7004 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-06 19:10:05.081  5922  5922 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-06 19:10:05.091  1171  1171 D PersonaManager: isKioskContainerExistOnDevice
,09-06 19:10:05.091  1171  1171 D PanelView: There is/are notification(s) 
09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
09-06 19:10:05.091  1171  1171 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-06 19:10:05.091  3248  7004 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
09-06 19:10:05.091  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.091  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.101  6698  6698 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 19:10:05.101  6698  6698 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 19:10:05.101  3248  7004 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-06 19:10:05.111  3248  7004 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-06 19:10:05.111  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.121  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 19:10:05.121  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 19:10:05.121  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-06 19:10:05.121  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.121  3248  7004 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-06 19:10:05.131  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.131  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.141  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:05.141  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:05.141  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.151  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:05.151  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:05.151  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 19:10:05.151  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 19:10:05.151  1171  1171 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-06 19:10:05.151  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 19:10:05.151  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-06 19:10:05.151  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
09-06 19:10:05.161  6978  6978 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 19:10:05.161  7006  7027 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-06 19:10:05.161  7006  7027 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-06 19:10:05.171  7006  7006 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-06 19:10:05.171  5990  5990 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-06 19:10:05.171  5990  5990 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-06 19:10:05.171  5990  5990 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 19:10:05.181  6833  6856 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 19:10:05.181  7006  7027 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:10:05.181  7006  7027 D SPPClientService: PushLog.txt file is not deleted.
09-06 19:10:05.181  7006  7027 D SPPClientService: ============PushLog. stop!
,09-06 19:10:05.191  5990  5990 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-06 19:10:05.191  5990  5990 I SA      : [OR] == isSIMCardReady false ==
,09-06 19:10:05.191  5990  5990 I SA      : [SCU] == networkStateCheck == true
,09-06 19:10:05.191  5990  5990 I SA      : [DM] getCountryCodeFromCSC : PL,
09-06 19:10:05.191  5990  5990 I SA      : isChinaCountryCode : false
09-06 19:10:05.191  5990  5990 I SA      : [SCU] is ChinestModel Data Restricted   : false,
09-06 19:10:05.191  5990  5990 I SA      : [OR] == networkStateCheck true ==
09-06 19:10:05.201  5990  5990 I SA      : [OR] GetMyCountryZoneTask
09-06 19:10:05.201  5990  5990 I SA      : [OR] onReceive END
,09-06 19:10:05.201  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 19:10:05.201  5990  7029 I SA      : [SRS] prepareGetMyCountryZone
,09-06 19:10:05.201  1014  1315 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,09-06 19:10:05.201  1014  1315 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
09-06 19:10:05.201  1014  1315 W ActivityManager: userId = 0, bbcId = -10000
09-06 19:10:05.201  1014  1315 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:05.201  1014  1315 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-06 19:10:05.211  5990  7029 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-06 19:10:05.211  5990  7029 I SA      : [SSP] query invoked
,09-06 19:10:05.221  5990  7029 I SA      : [TPMU] GetMccFromDB : null
,09-06 19:10:05.221  5990  7029 I SA      : [SCU] getMccFromPreferece mcc = 260
,09-06 19:10:05.221  5990  7029 I SA      : [LBE] isSupportCheckDomainRegion : false
09-06 19:10:05.221  5990  7029 I SA      : [TPM] isNoProxy(default) : true
,09-06 19:10:05.221  1014  1471 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-06 19:10:05.221  1014  1471 D SecContentProvider2: mCursor = null
,09-06 19:10:05.231  5990  7029 E File    : fail readDirectory() errno=2
,09-06 19:10:05.301  1014  1543 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-06 19:10:05.301  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.301  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:05.301  1014  1543 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 19:10:05.301  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-06 19:10:05.311  1014  1040 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 19:10:05.321  5922  5922 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-06 19:10:05.321  5922  5922 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-06 19:10:05.321  5922  5922 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-06 19:10:05.321  5922  5922 D InitializeManagerStateMachine: exit::IDLE
09-06 19:10:05.321  5922  5922 D InitializeManagerStateMachine: entry::NETWORK_CHECK
09-06 19:10:05.321  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 19:10:05 GMT+02:00 2016
,09-06 19:10:05.321  1014  1369 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 19:10:05.321  1014  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 19:10:05.321  1014  1369 W ActivityManager: userId = 0, bbcId = -10000
,09-06 19:10:05.321  1014  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 19:10:05.321  1014  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-06 19:10:05.331  5922  5922 D InitializeManagerStateMachine: entry::SUCCESS
09-06 19:10:05.331  5922  5922 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-06 19:10:05.331  3699  3699 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 19:10:05.331  1014  1026 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,09-06 19:10:05.331  1014  1026 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-06 19:10:05.331  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 19:10:05.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 19:10:05.331  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 19:10:05.341  3699  3699 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 19:10:05.341  3699  3699 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 19:10:05.351  7035  7035 E Zygote  : MountEmulatedStorage(),
09-06 19:10:05.351  7035  7035 E Zygote  : v2
,09-06 19:10:05.351  7035  7035 I libpersona: KNOX_SDCARD checking this for 10094
09-06 19:10:05.351  3699  3699 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-06 19:10:05.351  7035  7035 I libpersona: KNOX_SDCARD not a persona
,09-06 19:10:05.351  7035  7035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 19:10:05.351  7035  7035 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 19:10:05.361  1014  1026 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7035 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
09-06 19:10:05.351  7035  7035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
