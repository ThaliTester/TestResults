#### Test 84265062d118465_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-12 18:13:24.796   322   322 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-12 18:13:24.796   322   322 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 18:13:25.786   288   288 E SMD     : DCD OFF
09-12 18:13:25.836  6194  6194 D AndroidRuntime: 
09-12 18:13:25.836  6194  6194 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 18:13:25.836  6194  6194 D AndroidRuntime: CheckJNI is OFF
09-12 18:13:25.846  6194  6194 D AndroidRuntime: readGMSProperty: start
09-12 18:13:25.846  6194  6194 D AndroidRuntime: readGMSProperty: already setted!!
09-12 18:13:25.846  6194  6194 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 18:13:25.846  6194  6194 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 18:13:25.846  6194  6194 D AndroidRuntime: readGMSProperty: end
09-12 18:13:25.846  6194  6194 D AndroidRuntime: addProductProperty: start
09-12 18:13:25.986  6194  6194 E AffinityControl: AffinityControl: registerfunction enter
09-12 18:13:26.016  6194  6194 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 18:13:26.026  1014  1559 E PersonaManagerService: inState():  stateMachine is null !!
09-12 18:13:26.026  1014  1559 I PersonaManagerService: PersonaId don't exist
09-12 18:13:26.026  1014  1559 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 18:13:26.026  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-12 18:13:26.036  1014  1559 W ActivityManager: mDVFSHelper.acquire()
09-12 18:13:26.046  1014  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 18:13:26.046  1014  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 18:13:26.056  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.056  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.056  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.056  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:26.066  6205  6205 E Zygote  : MountEmulatedStorage()
09-12 18:13:26.066  6205  6205 E Zygote  : v2
09-12 18:13:26.066  6205  6205 I libpersona: KNOX_SDCARD checking this for 10155
09-12 18:13:26.066  6205  6205 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:26.066  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 18:13:26.066  1014  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 18:13:26.066   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-12 18:13:26.076  1014  1559 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6205 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 18:13:26.076  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-12 18:13:26.076  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 18:13:26.076  6205  6205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:26.076  6205  6205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:26.076  1014  1559 D InputDispatcher: Focused application set to: xxxx
09-12 18:13:26.076  1014  1559 D InputDispatcher: Focus left window: 3208
09-12 18:13:26.076  6205  6205 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 18:13:26.076  6194  6194 D AndroidRuntime: Shutting down VM
09-12 18:13:26.086  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:26.086  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 18:13:26.096   309   309 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 23.799ms
09-12 18:13:26.106  6205  6205 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:26.106  6205  6205 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:26.116  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 18:13:26.116   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.625ms
09-12 18:13:26.116  1014  1014 V ActivityManager: Display changed displayId=0
09-12 18:13:26.126  1014  1485 D PersonaManager: isKioskContainerExistOnDevice
09-12 18:13:26.136   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 18.202ms
09-12 18:13:26.166   258   444 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-12 18:13:26.166   258  1036 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-12 18:13:26.166  3208  3208 V ActivityThread: updateVisibility : ActivityRecord{3894d25 token=android.os.BinderProxy@33c62da0 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-12 18:13:26.236  6205  6205 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-12 18:13:26.246  6205  6205 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 186-187)
09-12 18:13:26.246  6205  6205 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:13:26.276  6205  6205 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26acadf1}
09-12 18:13:26.276  6205  6205 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 18:13:26.276  6205  6205 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 18:13:26.286  6194  6194 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 18:13:26.316  6205  6205 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-12 18:13:26.326  6205  6205 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-12 18:13:26.326  6205  6205 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-12 18:13:26.346  6205  6205 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 18:13:26.346  6205  6205 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-12 18:13:26.346  6205  6205 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-12 18:13:26.356  6205  6205 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:26.356  6205  6205 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:26.356  6205  6205 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:26.356  6205  6205 I Adreno-EGL: Local Branch: 
09-12 18:13:26.356  6205  6205 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:26.356  6205  6205 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:26.356  6205  6205 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:26.466  6205  6231 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-12 18:13:26.506  6205  6205 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:26.526  6205  6205 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 18:13:26.536  6205  6205 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-12 18:13:26.536  6205  6205 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-12 18:13:26.536  6205  6205 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-12 18:13:26.546  6205  6205 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:26.546  6205  6205 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:26.586  6205  6244 D OpenGLRenderer: Render dirty regions requested: true
,09-12 18:13:26.596  1014  3307 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 18:13:26.596  1014  3307 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-12 18:13:26.596  1014  3307 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 18:13:26.596  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-12 18:13:26.596  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 18:13:26.606  6205  6205 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-12 18:13:26.606  6205  6205 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-12 18:13:26.616   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-12 18:13:26.626  1014  1555 D InputDispatcher: Focus entered window: 6205
,09-12 18:13:26.626  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:26.626  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:26.626  6205  6205 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 18:13:26.626  6205  6244 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 18:13:26.636  6205  6244 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-12 18:13:26.636  6205  6244 D OpenGLRenderer: Enabling debug mode 0
,09-12 18:13:26.666  6205  6205 V ActivityThread: updateVisibility : ActivityRecord{2494a0e0 token=android.os.BinderProxy@2e505712 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 18:13:26.686  1014  3307 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 18:13:26.696  1177  1177 D PanelView: There is/are notification(s) 
,09-12 18:13:26.696  1014  6247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:26.706  6205  6205 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-12 18:13:26.706  6205  6205 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e505712 time:110645
,09-12 18:13:26.706  1787  1787 I SamsungIME: getCurrentCandidateView
,09-12 18:13:26.706  1014  1046 I ActivityManager: Displayed Component not be shown by security: +574ms (total +660ms)
,09-12 18:13:26.716  1014  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16d2a0c0 u0 com.test.thalitest/.MainActivity t128} time:110652,
09-12 18:13:26.716  1014  1046 W ActivityManager: mDVFSHelper.release(),
,09-12 18:13:26.716   258  1037 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-12 18:13:26.716   258  1036 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-12 18:13:26.776  6205  6205 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6205
,09-12 18:13:26.786  1787  1787 D SamsungIME: Dismiss ExpandCandiate
,09-12 18:13:26.886  6205  6205 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 18:13:26.916  1787  1787 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 18:13:26.956  1787  1787 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 18:13:26.966  1787  1787 I SamsungIME: KeybaordView init() : load resources
,09-12 18:13:26.986  1787  1787 I SamsungIME: getCurrentKeyboard
09-12 18:13:26.996  1787  1787 I SamsungIME: getTextKeyboard
,09-12 18:13:27.006  1787  1787 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 18:13:27.006  6205  6249 D jxcore_app_log: JniHelper::setJavaVM(0xb7a99328), pthread_self() = -1207943256
,09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-12 18:13:27.016  6205  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e020210 added. We now have 1 listener(s)
,09-12 18:13:27.026  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-12 18:13:27.026  6205  6249 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 18:13:27.026  6205  6249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:13:27.026  6205  6249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 18:13:27.036  6205  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c35d2f added. We now have 1 listener(s)
,09-12 18:13:27.036  6205  6249 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:27.046  6205  6249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-12 18:13:27.056  6205  6249 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:27.056  6205  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:27.056  6205  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 18:13:27.056  6205  6249 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:27.066  6205  6249 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:13:27.066  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:27.066  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:27.096  6205  6205 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 18:13:27.526  1787  6252 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 18:13:27.576  6205  6257 W jxcore-log: Initializing JXcore engine
09-12 18:13:27.576  6205  6257 W jxcore-log: JXcore engine is ready
,09-12 18:13:27.636  1871  1871 E audit   : type=1400 msg=audit(1473696807.636:205): avc:  denied  { ioctl } for  pid=6257 comm="Thread-1073" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 18:13:27.636  1871  1871 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:27.636  1871  1871 E audit   : type=1300 msg=audit(1473696807.636:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9da008f8 items=0 ppid=309 ppcomm=main pid=6257 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1073" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 18:13:27.636  1871  1871 E audit   : type=1320 msg=audit(1473696807.636:205): 
,09-12 18:13:27.646  6205  6257 W jxcore-log: Starting JXcore engine
,09-12 18:13:27.766  6205  6257 W jxcore-log: Platform android
09-12 18:13:27.766  6205  6257 W jxcore-log: 
09-12 18:13:27.766  6205  6257 W jxcore-log: Process ARCH arm
09-12 18:13:27.766  6205  6257 W jxcore-log: 
,09-12 18:13:27.976  6205  6257 I jxcore-log: JXcore Cordova bridge is ready!
09-12 18:13:27.976  6205  6257 I jxcore-log: 
,09-12 18:13:27.976  6205  6257 W jxcore-log: JXcore engine is started
,09-12 18:13:27.976  6205  6249 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 18:13:27.986  6205  6205 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 18:13:28.786   288   288 E SMD     : DCD OFF
,09-12 18:13:29.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:29.976  5435  5435 D FactoryTest: Not factory mode
,09-12 18:13:29.976  5435  5435 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 18:13:29.976  5435  5435 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-12 18:13:29.986  5435  5435 D MTPRx   : still no open session command from host, so toast
,09-12 18:13:29.986  5435  5435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-12 18:13:29.986  5435  5435 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-12 18:13:29.986  5435  5435 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113921
,09-12 18:13:29.986  1014  1559 E PersonaManagerService: inState():  stateMachine is null !!
,09-12 18:13:29.986  1014  1559 I PersonaManagerService: PersonaId don't exist
09-12 18:13:29.986  1014  1559 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 18:13:29.986  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 18:13:29.986  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:29.986  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:29.986  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-12 18:13:29.996  1014  1559 W ActivityManager: mDVFSHelper.acquire()
,09-12 18:13:30.006  1014  1559 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:13:30.006  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 18:13:30.006  1014  1559 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 18:13:30.006  1014  1559 D InputDispatcher: Focused application set to: xxxx
,09-12 18:13:30.006  1014  1559 D InputDispatcher: Focus left window: 6205
,09-12 18:13:30.006  5435  5435 E MTPRx   : started activity for popup
,09-12 18:13:30.016  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:13:30.016  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:30.046  5435  5435 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:13:30.066  5435  5435 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 18:13:30.066  1014  3305 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-12 18:13:30.066  1014  3305 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 18:13:30.066  1014  3305 D InputDispatcher: Focused application set to: xxxx
09-12 18:13:30.066  1014  3305 D InputDispatcher: Focus entered window: 6205
,09-12 18:13:30.066  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 18:13:30.076  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:13:30.076  1014  3304 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-12 18:13:30.076  1014  3304 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@20d5e613 attribute=null, token = android.os.BinderProxy@1a2d2e23
,09-12 18:13:30.106  5435  5435 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-12 18:13:30.116  5435  5435 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-12 18:13:30.116  5435  5435 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 18:13:30.136  6205  6205 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 18:13:30.136  6205  6205 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-12 18:13:30.136  6205  6205 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 18:13:30.136  6205  6205 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 18:13:30.136  1014  1555 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 18:13:30.136  1014  1555 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-12 18:13:30.136  1014  1555 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 18:13:30.136  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 18:13:30.146  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 18:13:30.156  6205  6205 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:13:30.156  6205  6205 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 18:13:30.156  6205  6205 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e505712 time:114093
,09-12 18:13:30.156  6205  6205 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2773f561 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3cb72e29, 16908290=android.view.AbsSavedState$1@3cb72e29}, android:focusedViewId=100}]}]
09-12 18:13:30.156  6205  6205 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 18:13:30.156  6205  6205 V ActivityThread: updateVisibility : ActivityRecord{2494a0e0 token=android.os.BinderProxy@2e505712 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 18:13:30.156  6205  6205 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 18:13:30.156  6205  6205 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-12 18:13:30.166  1014  1561 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:13:30.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:31.786   288   288 E SMD     : DCD OFF
,09-12 18:13:31.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:32.146  1014  3308 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:32.146  1014  3308 D BatteryService: level:81, scale:100, status:2, health:2, present:true, voltage: 4077, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 18:13:32.146  1014  3308 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 18:13:32.146  1014  3308 D BatteryService: stay LED for charging
,09-12 18:13:32.146  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:32.146  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:32.146  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:32.146  1014  1014 I MotionRecognitionService: Plugged
,09-12 18:13:32.156  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:32.156  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 18:13:32.156  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 81
,09-12 18:13:32.166  2653  2653 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:32.166  2653  2769 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:32.176  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:32.176  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:32.176  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:32.566  1014  2780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-12 18:13:32.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:32.996  1014  1041 W ActivityManager: mDVFSHelper.release(),
,09-12 18:13:33.486  1014  2749 D SSRM:n  : SIOP:: AP = 340
,09-12 18:13:33.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:34.786   288   288 E SMD     : DCD OFF,
,09-12 18:13:34.796   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-12 18:13:36.066  1014  1094 V AlarmManager: waitForAlarm result :4,
,09-12 18:13:36.066  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.086  1904  1904 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-12 18:13:36.096  1014  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-12 18:13:36.186  1904  1904 I art     : Explicit concurrent mark sweep GC freed 51625(2MB) AllocSpace objects, 17(608KB) LOS objects, 40% free, 13MB/22MB, paused 1.340ms total 69.909ms
,09-12 18:13:36.196  3842  3842 D ConnectivityManager: CallingUid : 10012, CallingPid : 3842
,09-12 18:13:36.196  1014  1217 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 18:13:36.196  1014  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-12 18:13:36.196  1014  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,09-12 18:13:36.206  1014  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-12 18:13:36.206  3842  6266 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 18:13:36.206  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:36.206  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.216  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.216  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.216  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.286  3842  6267 W DriveInitializer: Background init thread started
,09-12 18:13:36.316   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-12 18:13:36.316   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:36.316  3842  6267 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-12 18:13:36.336  1014  1312 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:36.336  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.346  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:36.346  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.346  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.376  1014  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:36.376  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.376  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.376  1014  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:36.376  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.386  1014  3305 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-12 18:13:36.386  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.416  3842  6267 W DriveInitializer: Background init thread ended
09-12 18:13:36.416  3842  6275 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-12 18:13:36.416  3842  6275 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-12 18:13:36.426  1904  1904 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 18:13:36.456  1014  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.456  1014  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.456  1014  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.566  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:36.566  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.566  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.566  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:36.566  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.596  1014  3308 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:36.596  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.596  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.596  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:36.596  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.646  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:36.646  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.646  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.646  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.666  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:36.676  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.676  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.676  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.736  1014  1312 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:36.736  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.736  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.736  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.736  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-12 18:13:36.736  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:36.736  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:36.736  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:36.766  6280  6280 E Zygote  : MountEmulatedStorage(),
09-12 18:13:36.766  6280  6280 I libpersona: KNOX_SDCARD checking this for 10012
09-12 18:13:36.766  6280  6280 E Zygote  : v2
09-12 18:13:36.766  6280  6280 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:36.766  6280  6280 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:36.776  6280  6280 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:36.776  6280  6280 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
09-12 18:13:36.776  1014  1312 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6280 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-12 18:13:36.796  6280  6280 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:36.796  6280  6280 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:36.816  6280  6280 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-12 18:13:36.816  6280  6280 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 18:13:36.856  6280  6280 I MultiDex: VM with version 2.1.0 has multidex support
09-12 18:13:36.856  6280  6280 I MultiDex: install
09-12 18:13:36.856  6280  6280 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-12 18:13:36.886  6280  6280 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-12 18:13:36.936  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-12 18:13:36.936  1014  3307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:36.946  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.946  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:36.946  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.956  1014  3304 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:36.956  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.956  1014  3304 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.956  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:36.956  6280  6280 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 18:13:36.956  6280  6280 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cb0c672: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-12 18:13:36.956  6280  6280 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 18:13:36.986  6280  6280 D ChimeraCfgMgr: Reading stored module config
,09-12 18:13:36.996  1014  3304 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-12 18:13:36.996  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 18:13:36.996  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:36.996  1014  3304 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:36.996  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.006  1904  1904 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=81d9a2cc-9ece-49b4-be77-98f39cfc6c63
,09-12 18:13:37.026  1904  1904 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 18:13:37.026  1904  1904 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 18:13:37.046  1014  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:37.056  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:37.056  1014  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:37.056  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.076  6280  6294 I art     : Background sticky concurrent mark sweep GC freed 20678(1031KB) AllocSpace objects, 3(133KB) LOS objects, 6% free, 10MB/11MB, paused 16.495ms total 71.385ms
,09-12 18:13:37.096  6280  6280 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-12 18:13:37.096  6280  6280 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-12 18:13:37.106  6280  6299 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-12 18:13:37.196   283   688 D WVCdm   : Instantiating CDM.
,09-12 18:13:37.206   283   681 I WVCdm   : CdmEngine::OpenSession
09-12 18:13:37.206   283   681 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-12 18:13:37.216   283   681 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-12 18:13:37.246   283   681 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-12 18:13:37.246   283   681 D DrmWidevineDash: Service_Initialize: starts!
09-12 18:13:37.246   283   681 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-12 18:13:37.246   283   681 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 18:13:37.246   283   681 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-12 18:13:37.246   283   681 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-12 18:13:37.246   283   681 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-12 18:13:37.246   283   681 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 18:13:37.246   283   681 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-12 18:13:37.246   283   681 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-12 18:13:37.246   283   681 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-12 18:13:37.256   283   681 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 18:13:37.276   283   681 D QSEECOMAPI: : Loaded image: APP id = 11
,09-12 18:13:37.276   283   681 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-12 18:13:37.276   283   681 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
,09-12 18:13:37.276   283   681 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-12 18:13:37.276   283   681 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16ee000
09-12 18:13:37.276   283   681 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16ee000
09-12 18:13:37.276   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.276   425   432 D DrmLibTime: got the req here! ret=0
09-12 18:13:37.276   425   432 D DrmLibTime: command id, time_cmd_id = 770
09-12 18:13:37.276   425   432 D DrmLibTime: time_getutcsec starts!
,09-12 18:13:37.276   425   432 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-12 18:13:37.276   425   432 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-12 18:13:37.276   425   432 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-12 18:13:37.276   425   432 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-12 18:13:37.286   425   432 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
09-12 18:13:37.286   425   432 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-12 18:13:37.286   425   432 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,09-12 18:13:37.286   425   432 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-12 18:13:37.286   325   553 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-12 18:13:37.286   325  6303 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-12 18:13:37.286   325  6303 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-12 18:13:37.286   325  6303 D QC-time-services: offset is: 0 for base: 0
,09-12 18:13:37.286   425   432 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-12 18:13:37.286   425   432 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-12 18:13:37.286   425   432 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473696817
09-12 18:13:37.286   425   432 D DrmLibTime: time_getutcsec returns 0, sec = 1473696817; nsec = 0
09-12 18:13:37.286   425   432 D DrmLibTime: time_getutcsec finished! 
,09-12 18:13:37.286   425   432 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-12 18:13:37.286   425   432 D DrmLibTime: before calling ioctl to read the next time_cmd
09-12 18:13:37.286   325   553 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
09-12 18:13:37.286   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-12 18:13:37.296   283   681 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-12 18:13:37.296   283   681 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-12 18:13:37.296   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.296   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.296   283   681 D DrmWidevineDash: hlos api version =  9
09-12 18:13:37.296   283   681 D DrmWidevineDash: tz api version =  9
09-12 18:13:37.296   283   681 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-12 18:13:37.296   283   681 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-12 18:13:37.296   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.296  1621  1649 I art     : Explicit concurrent mark sweep GC freed 1439(49KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 811us total 33.605ms
,09-12 18:13:37.306   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-12 18:13:37.306   283   681 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1921960
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-12 18:13:37.306   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 18:13:37.306   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb89dd130, dataLength=8
09-12 18:13:37.306   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.306   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.306   283   681 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-12 18:13:37.316   283   681 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb89db5c0, wrapped_rsa_key_length=1280
,09-12 18:13:37.316   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.316   283   681 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.316   283   681 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-12 18:13:37.316   283   681 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-12 18:13:37.316   283   688 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-12 18:13:37.316   283   688 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-12 18:13:37.316   283   688 I WVCdm   : CdmEngine::GenerateKeyRequest
09-12 18:13:37.316   283   688 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8962890, idLength=0xb1823730
09-12 18:13:37.316   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1823746, maximum = 0xb1823747
09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.336   283   688 D DrmWidevineDash: hlos api version =  9
09-12 18:13:37.336   283   688 D DrmWidevineDash: tz api version =  9
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18237b4
09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-12 18:13:37.336   283   688 D WVCdm   : PrepareKeyRequest: nonce=2970696077
09-12 18:13:37.336   283   688 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb896bf68
09-12 18:13:37.336   283   688 D DrmWidevineDash: message_length=1599, signature=0xb89cc5f0, signature_length=0xb1823714
,09-12 18:13:37.336   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.346  6280  6289 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-12 18:13:37.346  6280  6289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:37.346  6280  6289 I System.out: (HTTPLog)-Static: isShipBuild true
09-12 18:13:37.346  6280  6289 I System.out: (HTTPLog)-Thread-1050-399885335: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-12 18:13:37.346  6280  6289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:37.356   278  1009 D EnterpriseController: uids 10012
09-12 18:13:37.356   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:13:37.356   278  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 18:13:37.366  1904  2092 W GCoreFlp: No location to return for getLastLocation()
,09-12 18:13:37.396  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:37.396  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:37.396  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:37.396  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.396  6280  6289 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:13:37.406  6280  6289 I qtaguid : Tagging socket 27 with tag 1000180300000000{268441603,0} for uid -1, pid: 6280, getuid(): 10012
,09-12 18:13:37.406  1014  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:37.406  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:37.406  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:37.406  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.416  1014  3307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:37.416  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:37.416  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:37.416  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.426  3842  6276 D UdcContextInitService: registered all accounts: true
,09-12 18:13:37.426  1904  2100 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 18:13:37.446  1904  2112 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-12 18:13:37.496   283   688 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.496   283   688 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-12 18:13:37.506   283   283 I WVCdm   : CdmEngine::CloseSession,
09-12 18:13:37.506   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-12 18:13:37.506   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 18:13:37.506   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.506   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-12 18:13:37.506   283   283 I WVCdm   : L3 Terminate.
,09-12 18:13:37.506   283   283 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-12 18:13:37.506   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 18:13:37.506   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 18:13:37.506   283   283 D DrmWidevineDash: Service_Uninitialize: starts!
09-12 18:13:37.506   283   283 D QSEECOMAPI: : QSEECom_dealloc_memory 
,09-12 18:13:37.506   283   283 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
09-12 18:13:37.506   283   283 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-12 18:13:37.506   283   283 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-12 18:13:37.546  6280  6294 I art     : Background partial concurrent mark sweep GC freed 6787(500KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 5.399ms total 46.043ms
,09-12 18:13:37.726  6280  6289 I qtaguid : Untagging socket 27
,09-12 18:13:37.766  1014  3307 I art     : Explicit concurrent mark sweep GC freed 34633(1877KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 27MB/41MB, paused 2.478ms total 152.552ms
09-12 18:13:37.766  1014  3307 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-12 18:13:37.766  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 18:13:37.766  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:37.766  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:37.766  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:37.786   288   288 E SMD     : DCD OFF
,09-12 18:13:38.076  6311  6311 I dex2oat : ----------------------------------------------------
09-12 18:13:38.076  6311  6311 I dex2oat : <SS>: S T A R T I N G . . .
09-12 18:13:38.076  6311  6311 I dex2oat : <SS>: Zip is absent. Canceled.
,09-12 18:13:38.076  6311  6311 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-12 18:13:38.106  6311  6311 I dex2oat : dex2oat took 30.108ms (threads: 4)
,09-12 18:13:38.116  6280  6289 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:38.116  6280  6289 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:38.116  6280  6289 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:38.116  6280  6289 I Adreno-EGL: Local Branch: 
09-12 18:13:38.116  6280  6289 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:38.116  6280  6289 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:38.116  6280  6289 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:38.196  6280  6289 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:38.196  6280  6289 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:38.196  6280  6289 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:38.196  6280  6289 I Adreno-EGL: Local Branch: 
09-12 18:13:38.196  6280  6289 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:38.196  6280  6289 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:38.196  6280  6289 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:38.296  6280  6289 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:38.296  6280  6289 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:38.296  6280  6289 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:38.296  6280  6289 I Adreno-EGL: Local Branch: 
09-12 18:13:38.296  6280  6289 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:38.296  6280  6289 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:38.296  6280  6289 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:38.656  1014  1326 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-12 18:13:38.656  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-12 18:13:38.656  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:38.656  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:38.656  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:38.666  1904  6278 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:38.666   278  1009 D EnterpriseController: uids 10012
09-12 18:13:38.666   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:13:38.666   278  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 18:13:38.676  1904  6278 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:13:38.676  1904  6278 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1904, getuid(): 10012
,09-12 18:13:38.716  1904  6278 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1904, getuid(): 10012
,09-12 18:13:38.876  1904  2112 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 18:13:38.876  1904  2112 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-12 18:13:38.886  1904  2112 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-12 18:13:37.514+0200, stopTime=2016-09-12 18:13:38.892+0200, duration=1378ms
,09-12 18:13:38.886  1904  6321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:38.896   278  1009 D EnterpriseController: uids 10012
09-12 18:13:38.896   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:13:38.896   278  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 18:13:38.896  1904  6321 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:13:38.896  1904  6321 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1904, getuid(): 10012
,09-12 18:13:38.936  1904  6321 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1904, getuid(): 10012
,09-12 18:13:38.976  1904  2112 I art     : Explicit concurrent mark sweep GC freed 51805(3MB) AllocSpace objects, 10(302KB) LOS objects, 40% free, 14MB/23MB, paused 1.581ms total 71.817ms
,09-12 18:13:39.006  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-12 18:13:39.316  1904  6321 I qtaguid : Untagging socket 71
,09-12 18:13:39.336  1014  3308 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:39.336  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-12 18:13:39.336  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.336  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.336  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.366  1904  2112 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-12 18:13:39.426  1014  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.426  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.426  1014  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.426  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.456  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.456  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.456  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.456  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.496  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.496  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.496  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.496  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.496  1904  6328 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 18:13:39.496  1904  6326 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 18:13:39.496  1014  3304 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.496  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.496  1014  3304 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:39.506  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.526  1014  1326 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.526  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.526  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.526  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.526  1904  6328 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 18:13:39.526  1904  6326 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 18:13:39.526  1014  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.526  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.526  1014  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:39.526  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.556  1014  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:39.556  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:39.556  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:39.556  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:39.556  1904  6328 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 18:13:39.556  1904  6326 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 18:13:39.556  1904  6326 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-12 18:13:39.566  1904  6326 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 18:13:39.606  1014  1561 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 18:13:39.636  1904  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:39.646   278  1009 D EnterpriseController: uids 10012
09-12 18:13:39.646   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:13:39.646   278  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 18:13:39.646  1904  6326 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:13:39.646  1904  6326 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:39.676  1904  6326 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:39.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:39.946  1014  1555 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 18:13:39.956  1904  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:39.956  1904  6326 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:40.096  1014  1492 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 18:13:40.096  1904  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:40.096  1904  6326 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:40.236  1014  1312 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 18:13:40.246  1904  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:40.246  1904  6326 I qtaguid : Tagging socket 81 with tag 1106541400000000{285627412,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:40.396  1014  3308 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 18:13:40.396  1904  6326 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:40.396  1904  6326 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:13:40.576  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 18:13:40.576  6205  6257 I jxcore-log: 
,09-12 18:13:40.576  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 18:13:40.576  6205  6257 I jxcore-log: 
,09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:40.586  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:40.586  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:40.586  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 18:13:40.586  6205  6257 I jxcore-log: 
09-12 18:13:40.586  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 18:13:40.586  6205  6257 I jxcore-log: 
,09-12 18:13:40.796   288   288 E SMD     : DCD OFF
,09-12 18:13:40.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:41.076  1904  6322 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:41.076  1904  6322 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1904, getuid(): 10012
,09-12 18:13:41.236  6205  6257 D executeNativeTests: Running unit tests
,09-12 18:13:41.306  1904  6322 I qtaguid : Untagging socket 71
,09-12 18:13:41.316  1904  2112 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-12 18:13:41.326  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:13:41.326  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e added. We now have 2 listener(s)
,09-12 18:13:41.326  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:13:41.326  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:13:41.326  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:13:41.326  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:41.326  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f added. We now have 2 listener(s)
09-12 18:13:41.326  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:41.326  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:13:41.326  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.336  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.336  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.336  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:41.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 18:13:41.336  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.336  6205  6257 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 18:13:41.336  6205  6257 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:41.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 18:13:41.336  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.336  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.336  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.336  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.336  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:41.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e removed from the list
09-12 18:13:41.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f removed from the list
,09-12 18:13:41.346  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:41.346  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.346  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.346  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.346  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.346  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.346  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.346  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.346  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.356  6205  6257 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 18:13:41.356  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.356  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.356  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.356  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.356  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.356  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.356  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.356  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.356  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.356  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.356  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.356  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.356  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.356  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.356  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.356  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.356  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.356  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.356  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:41.366  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.366  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.366  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.366  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.366  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.366  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.366  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.366  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.366  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.366  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.366  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.366  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.366  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.366  6205  6257 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:13:41.366  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.376  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 18:13:41.376  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.376  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:41.376  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:41.376  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:41.376  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:41.386  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:41.386  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:13:41.386  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.386  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:13:41.386  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 18:13:41.396  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 18:13:41.396  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 18:13:41.396  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 18:13:41.406  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 18:13:41.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 18:13:41.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:41.406  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 18:13:41.416  2653  2667 D BtGatt.GattService: registerClient() - UUID=6f248eab-60a9-4c8a-8331-89ab9d3b9f8c
,09-12 18:13:41.466  2653  2745 D BtGatt.GattService: onClientRegistered() - UUID=6f248eab-60a9-4c8a-8331-89ab9d3b9f8c, clientIf=6,
09-12 18:13:41.466  6205  6213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 18:13:41.466  2653  2665 D BtGatt.GattService: start scan with filters
,09-12 18:13:41.486  2653  2765 D BtGatt.ScanManager: handling starting scan
09-12 18:13:41.486  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:13:41.486  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:41.486  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:41.486  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:41.486  2653  2765 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:41.486  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:13:41.486  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:13:41.486  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:41.486  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:41.496  6205  6257 I io.jxcore.node.ConnectionHelper: start: OK,
09-12 18:13:41.496  2653  2745 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:13:41.496  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-12 18:13:41.496  2653  2765 D BtGatt.ScanManager: allow scan with filters
09-12 18:13:41.496  2653  2765 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 18:13:41.496  2653  2765 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 18:13:41.496  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.496  6205  6257 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:13:41.496  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,09-12 18:13:41.496  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 18:13:41.496  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.496  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:13:41.496  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 18:13:41.496  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:13:41.496  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:13:41.496  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:41.496  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:13:41.496  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.496  2653  2765 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:41.496  2653  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
09-12 18:13:41.506  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:41.506  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:41.506  2653  2745 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:13:41.506  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.506  2653  2973 D BtGatt.GattService: stopScan() - queue size =1
09-12 18:13:41.506  2653  2667 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:41.506  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 18:13:41.506  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.506  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:41.506  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 18:13:41.506  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:41.506  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:41.506  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:41.516  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:41.516  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-12 18:13:41.516  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-12 18:13:41.516  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:41.516  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.516  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:41.516  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.516  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.516  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.516  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:41.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.516  6205  6257 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 18:13:41.516  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.526  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.526  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.526  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:13:41.526  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:13:41.526  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:41.526  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:13:41.526  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.526  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:13:41.536  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.536  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.536  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:41.536  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:41.546  2653  2765 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 62
09-12 18:13:41.546  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:41.546  2653  2765 D BtGatt.ScanManager: filter size is 1
09-12 18:13:41.546  2653  2765 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 18:13:41.546  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 18:13:41.546  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.546  2653  2765 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:41.546  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:41.546  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:13:41.546  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:41.556  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 18:13:41.556  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.556  2653  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:13:41.556  2653  2745 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:13:41.556  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.556  2653  2667 D BtGatt.GattService: registerClient() - UUID=35ff7b2c-6ec2-44bf-a5fe-5492c9e2c1ed
,09-12 18:13:41.606  2653  2745 D BtGatt.GattService: onClientRegistered() - UUID=35ff7b2c-6ec2-44bf-a5fe-5492c9e2c1ed, clientIf=6
,09-12 18:13:41.606  6205  6213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:13:41.606  2653  2665 D BtGatt.GattService: start scan with filters
,09-12 18:13:41.606  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: handling starting scan
09-12 18:13:41.606  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:41.606  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:41.606  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:41.606  2653  2745 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:13:41.606  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: allow scan with filters
09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-12 18:13:41.606  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:13:41.606  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:41.606  2653  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 18:13:41.606  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:41.606  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:13:41.606  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:13:41.606  2653  2745 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:13:41.606  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:41.616  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 18:13:41.616  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.626  6205  6257 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:41.636  2653  2765 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 63
,09-12 18:13:41.636  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.636  6205  6257 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 18:13:41.636  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:41.636  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 18:13:41.636  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 18:13:41.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:41.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:13:41.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:41.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:13:41.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:13:41.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:41.646  2653  2667 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:41.646  2653  2765 D BtGatt.ScanManager: filter size is 1
09-12 18:13:41.646  2653  2765 D BtGatt.ScanManager: delete FilterIndex - 4
,09-12 18:13:41.646  2653  2665 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:13:41.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:41.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:41.646  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:41.646  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.646  2653  2765 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:41.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:41.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:41.646  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:13:41.646  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:41.646  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:41.646  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:41.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.656  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.656  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:41.656  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.656  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.656  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.656  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.656  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.656  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.656  2653  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 18:13:41.656  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.656  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.656  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.656  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.656  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.656  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.656  6205  6257 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 18:13:41.656  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.656  2653  2745 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 18:13:41.656  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.666  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.666  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.666  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:41.666  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.666  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.666  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:13:41.666  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:13:41.666  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 18:13:41.666  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:13:41.666  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:13:41.676  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:13:41.676  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:13:41.676  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:13:41.686  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:13:41.686  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:13:41.686  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:13:41.686  2653  2973 D BtGatt.GattService: registerClient() - UUID=b8b11e9d-a2fa-4165-ab92-54167b9534ee
,09-12 18:13:41.736  2653  2745 D BtGatt.GattService: onClientRegistered() - UUID=b8b11e9d-a2fa-4165-ab92-54167b9534ee, clientIf=6
,09-12 18:13:41.736  6205  6216 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:13:41.736  2653  2974 D BtGatt.GattService: start scan with filters
09-12 18:13:41.736  2653  2765 D BtGatt.ScanManager: handling starting scan
09-12 18:13:41.736  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:13:41.736  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:13:41.736  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:13:41.736  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 18:13:41.736  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:41.736  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:13:41.736  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:13:41.736  2653  2745 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:13:41.736  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.736  2653  2765 D BtGatt.ScanManager: allow scan with filters
09-12 18:13:41.736  2653  2765 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:13:41.736  2653  2765 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 18:13:41.736  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:13:41.746  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:13:41.746  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.746  2653  2765 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:13:41.746  2653  2765 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:13:41.746  6205  6257 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 18:13:41.746  2653  2745 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 18:13:41.746  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.746  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.746  6205  6257 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:41.746  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:41.746  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:13:41.746  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:41.746  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:13:41.746  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:41.746  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:13:41.746  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:41.756  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:41.756  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:13:41.756  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:13:41.756  2653  2973 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:13:41.756  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 18:13:41.756  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.766  2653  2974 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:13:41.766  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:13:41.766  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:13:41.766  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:13:41.766  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:13:41.766  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:41.766  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:41.766  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:13:41.776  2653  2765 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 64
,09-12 18:13:41.776  2653  2765 D BtGatt.ScanManager: filter size is 1
09-12 18:13:41.776  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.776  6205  6257 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:13:41.776  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.776  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.776  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.776  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.776  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.776  2653  2765 D BtGatt.ScanManager: delete FilterIndex - 5
,09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.776  6205  6257 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 18:13:41.776  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.776  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.776  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 18:13:41.776  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.776  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.776  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.776  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.776  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.776  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.776  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.776  2653  2745 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:13:41.776  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.776  2653  2765 D BtGatt.ScanManager: stopping BLe Batch
09-12 18:13:41.786  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 18:13:41.786  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.786  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.786  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.786  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.786  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.786  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:41.786  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.786  6205  6257 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 18:13:41.786  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.786  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.786  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.786  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.786  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.786  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.786  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.786  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.786  2653  2745 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:13:41.786  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:13:41.786  2653  2765 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:13:41.786  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:41.796  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.796  2653  2745 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:13:41.796  2653  2745 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:13:41.796  6205  6257 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 18:13:41.796  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.796  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.796  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.796  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.796  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.796  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.796  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.796  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.796  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.796  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.796  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.796  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.796  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 18:13:41.796   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:41.796  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:41.796  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 18:13:41.796  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 18:13:41.796  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.796  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.796  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.796  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.796  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.796  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.806  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.806  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.806  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.806  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.806  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.806  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.806  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.806  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:13:41.806  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.806  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.806  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.806  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 18:13:41.806  6205  6257 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:41.806  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:41.806  6205  6257 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 18:13:41.806  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 18:13:41.806  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 18:13:41.806  6205  6257 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:41.806  6205  6257 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 18:13:41.806  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:41.806  6205  6257 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:41.806  6205  6257 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 18:13:41.806  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-12 18:13:41.806  6205  6257 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 18:13:41.806  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
,09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,09-12 18:13:41.816  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 18:13:41.816  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 18:13:41.816  6205  6257 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 18:13:41.816  6205  6257 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 18:13:41.816  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-12 18:13:41.816  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.816  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.816  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 18:13:41.816  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.816  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 18:13:41.816  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.816  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.816  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:41.816  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.816  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.816  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.816  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.816  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.816  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.816  6205  6257 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-12 18:13:41.826  6205  6338 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1137
,09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1137)
09-12 18:13:41.826  6205  6337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1137)
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 18:13:41.826  6205  6257 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:41.826  6205  6257 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 18:13:41.826  6205  6257 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:41.826  6205  6257 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.826  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.826  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.826  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.826  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.826  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.826  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.826  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:13:41.836  6205  6205 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:13:41.836  6205  6205 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:13:41.836  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.836  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:13:41.836  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:13:41.836  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.836  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.836  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:13:41.836  6205  6339 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 18:13:41.836  6205  6339 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 18:13:41.836  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.836  6205  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 18:13:41.836  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.836  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.836  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.836  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.836  6205  6257 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 18:13:41.836  6205  6257 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 18:13:41.836  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 18:13:41.836  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:13:41.836  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.836  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.836  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.836  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.836  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.836  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.846  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.846  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.846  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.846  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.846  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.846  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:13:41.846  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:13:41.846  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3788865e not in the list
09-12 18:13:41.846  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:13:41.846  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
09-12 18:13:41.846  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:13:41.846  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:13:41.846  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:41.856  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:13:41.856  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:13:41.856  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:13:41.856  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c60a3f not in the list
,09-12 18:13:41.856  6205  6257 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:41.856  6205  6257 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 18:13:41.856  6205  6257 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 18:13:41.856  6205  6257 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:41.856  6205  6257 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 18:13:41.856  6205  6257 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 18:13:41.856  6205  6257 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 18:13:41.856  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:41.856  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a72f509 added. We now have 2 listener(s)
09-12 18:13:41.856  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:41.856  6205  6257 D BluetoothAdapter: enable()
,09-12 18:13:41.856  6205  6257 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 18:13:41.856  1014  1485 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:13:41.866  1014  1485 D WifiService: setWifiEnabled: true pid=6205, uid=10155
09-12 18:13:41.856  1014  1485 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:41.866  1014  1485 W ActivityManager: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:41.856  1014  1485 D SecContentProvider2: mCursor = null
09-12 18:13:41.866  1014  1485 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:13:41.866  1014  1485 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:41.866  1014  1485 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 18:13:41.866  1014  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:13:41.866  1014  1485 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:13:41.866  1014  1485 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:13:41.866  1014  1485 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 18:13:41.866  1014  1485 D SettingsProvider: name = wifi_on
,09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1791430e added. We now have 3 listener(s)
09-12 18:13:41.866  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@361c012f added. We now have 4 listener(s)
09-12 18:13:41.866  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:41.866  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ba3033c added. We now have 5 listener(s)
09-12 18:13:41.866  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:41.876  1014  3307 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:13:41.876  1014  3307 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:41.876  1014  3307 D SecContentProvider2: mCursor = null
,09-12 18:13:41.876  1014  3307 D WifiService: setWifiEnabled: false pid=6205, uid=10155
09-12 18:13:41.876  1014  3307 D SettingsProvider: name = wifi_on
,09-12 18:13:41.876  1014  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 18:13:41.876  6205  6257 D BluetoothAdapter: disable()
,09-12 18:13:41.876  2146  2146 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:13:41.876  2146  2146 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 18:13:41.886  1014  1312 D SettingsProvider: name = bluetooth_on
,09-12 18:13:41.886  2146  2146 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-12 18:13:41.886  2146  2146 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:13:41.886  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:13:41.886  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:13:41.896  2653  2736 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 18:13:41.896  2653  2736 D BluetoothAdapterProperties: Setting state to 13
09-12 18:13:41.896  2653  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:13:41.896  1014  1126 E WifiNative-wlan0: do suspend true
,09-12 18:13:41.896  2653  2736 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:41.896  2653  2736 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 18:13:41.896  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:41.896  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:41.896  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.896  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.896  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:41.896  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:41.896  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:41.896  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.896  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.896  2653  2653 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-12 18:13:41.896  2653  2736 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:41.896  2653  2736 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 18:13:41.896  2653  2736 D BluetoothAdapterService: terminating service from this receiver
09-12 18:13:41.896  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:13:41.896  2653  2653 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9496f3b, channel: 19, state: LISTENING
09-12 18:13:41.896  2653  2653 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9496f3b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e20f40, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16ca8658mSocket: android.net.LocalSocket@293a33b1 impl:android.net.LocalSocketImpl@356e2096 fd:FileDescriptor[76]
09-12 18:13:41.896  2653  2653 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@293a33b1 impl:android.net.LocalSocketImpl@356e2096 fd:FileDescriptor[76]
,09-12 18:13:41.896  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:41.896  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-12 18:13:41.906  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.906  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:41.906  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.906  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.906  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:41.906  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:41.906  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-12 18:13:41.906  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.906  1787  1787 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:13:41.916  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:41.916  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:41.916  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-12 18:13:41.916  1014  3308 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:41.916  1014  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:41.916  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:41.926  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:41.926  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:13:41.926  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:41.926  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:41.926  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:41.926  2653  2736 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:13:41.926  2653  2736 D BluetoothAdapterProperties: mDiscovering is false
,09-12 18:13:41.926  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 18:13:41.926  1014  3308 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:41.926  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:13:41.926  2653  2736 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 18:13:41.926  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:41.926  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:41.926  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:41.936  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:13:41.936  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:41.936  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 18:13:41.936  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:13:41.936  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.946  1014  1561 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 18:13:41.946  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:41.946  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:41.946  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:41.946  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:41.946  2653  2745 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:41.946  2653  2745 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:13:41.946  1299  1299 D BluetoothPbap: Proxy object disconnected
,09-12 18:13:41.946  2653  2736 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-12 18:13:41.956  2653  2736 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 18:13:41.956  1299  1299 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:13:41.956  2653  2736 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-12 18:13:41.956  2653  2736 E bt-btif : BTM_SEC_CLR[17]: id 57
09-12 18:13:41.956  2653  5010 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 18:13:41.956  2653  2840 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-12 18:13:41.956  2653  2840 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 18:13:41.956  2653  2736 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 18:13:41.956  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.956  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:41.956  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:41.956  2653  2840 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:13:41.966  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:41.966  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:41.966  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:41.966  2653  2653 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17d5c417, channel: 5, state: LISTENING
09-12 18:13:41.966  2653  2653 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17d5c417, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11e76ac3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@88db004mSocket: android.net.LocalSocket@370d59ed impl:android.net.LocalSocketImpl@3c63b022 fd:FileDescriptor[74]
09-12 18:13:41.966  2653  2653 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@370d59ed impl:android.net.LocalSocketImpl@3c63b022 fd:FileDescriptor[74]
09-12 18:13:41.966  2653  2653 I BtOppRfcommListener: stopping Accept Thread
09-12 18:13:41.966  2653  2653 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32688ab3, channel: 12, state: LISTENING
09-12 18:13:41.966  2653  2653 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32688ab3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b2eb1ca, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a37c870mSocket: android.net.LocalSocket@f72a7e9 impl:android.net.LocalSocketImpl@a30ac6e fd:FileDescriptor[79]
09-12 18:13:41.966  2653  2653 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f72a7e9 impl:android.net.LocalSocketImpl@a30ac6e fd:FileDescriptor[79]
,09-12 18:13:41.966  2653  5010 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 18:13:41.976  2653  2653 V BluetoothOppManager: cleanUp...
,09-12 18:13:41.976  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:41.976  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 18:13:41.976  1014  1138 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-12 18:13:41.976  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:41.976  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:41.976  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:41.976  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:41.996  6345  6345 E Zygote  : MountEmulatedStorage()
09-12 18:13:41.996  6345  6345 I libpersona: KNOX_SDCARD checking this for 10003
09-12 18:13:41.996  6345  6345 E Zygote  : v2
,09-12 18:13:41.996  6345  6345 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:41.996  6345  6345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:41.996  1014  1138 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6345 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-12 18:13:41.996  6345  6345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:41.996  6345  6345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:42.036  6345  6345 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:42.036  6345  6345 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:42.066  6345  6345 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 18:13:42.096  6345  6345 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-12 18:13:42.096  6345  6345 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,09-12 18:13:42.096  6345  6345 D UserAnalysis: Create SecureDbHelper
,09-12 18:13:42.106  6345  6345 D IntelligenceServiceApplication: onCreate()
,09-12 18:13:42.106  1014  1561 I ActivityManager: Killing 5365:com.google.android.talk/u0a104 (adj 15): empty #31
,09-12 18:13:42.116  1014  1561 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-12 18:13:42.116  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.116  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.116  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.116  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.116  6345  6345 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-12 18:13:42.136  6363  6363 E Zygote  : MountEmulatedStorage()
,09-12 18:13:42.146  6363  6363 E Zygote  : v2
09-12 18:13:42.146  6363  6363 I libpersona: KNOX_SDCARD checking this for 10107
09-12 18:13:42.146  6363  6363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:42.146  6363  6363 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:42.146  6345  6345 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-12 18:13:42.146  1014  1561 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6363 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-12 18:13:42.146  6363  6363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:42.146  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-12 18:13:42.146  6363  6363 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:42.156  2653  2840 W bt-l2cap: btif_mce_execute_service enable:0
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:42.156  2653  2840 W bt-btif : ag scb idx 1 not allocated
09-12 18:13:42.156  2653  2840 W bt-btif : ag scb idx 2 not allocated
09-12 18:13:42.156  2653  2840 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 18:13:42.156  2653  2932 I bt_userial_mct: exiting userial_read_thread
09-12 18:13:42.156  2653  2932 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 18:13:42.156  2653  2745 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 18:13:42.156  2653  2842 I bt_vendor: hw_epilog_process
09-12 18:13:42.156  2653  2745 D bt_userial_mct: userial_close
09-12 18:13:42.156  2653  2745 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 18:13:42.156  6345  6345 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 18:13:42.176  6363  6363 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:42.176  6363  6363 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:42.206  1014  3308 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:42.206  1014  3308 D BatteryService: level:81, scale:100, status:2, health:2, present:true, voltage: 4070, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-12 18:13:42.206  1014  3308 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 18:13:42.206  1014  3308 D BatteryService: stay LED for charging
09-12 18:13:42.206  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:42.216  1014  1014 I MotionRecognitionService: Plugged
,09-12 18:13:42.216  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:42.216  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:42.216  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:42.216  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 18:13:42.216  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 81
,09-12 18:13:42.226  2653  2653 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:42.226  2653  2769 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:42.246  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
09-12 18:13:42.246  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
09-12 18:13:42.246  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:42.336  6205  6205 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:13:42.416  1014  3305 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-12 18:13:42.416  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 18:13:42.416  1014  3305 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.416  1014  3305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.416  1014  3305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:42.426  2653  2745 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 18:13:42.426  2653  2745 I bt_vendor: bluetooth satus is on
09-12 18:13:42.426  2653  2745 I bt_vendor: bt-vendor : resetting BT status
09-12 18:13:42.426  2653  2745 I bt_vendor: Starting hciattach daemon
09-12 18:13:42.426  2653  2745 I bt_vendor: try to set false
,09-12 18:13:42.436  2653  2745 I bt_vendor: Starting hciattach daemon
09-12 18:13:42.436  2653  2745 I bt_vendor: try to set false
,09-12 18:13:42.446  2653  2745 I bt_vendor: cleanup
,09-12 18:13:42.446  2653  2840 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-12 18:13:42.446  2653  2745 I GKI_LINUX: GKI_exit_task 0 done
09-12 18:13:42.446  2653  2745 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-12 18:13:42.446  2653  2736 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 18:13:42.446  2653  2736 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:13:42.446  2653  2736 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 18:13:42.446  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 18:13:42.446  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 18:13:42.456  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-12 18:13:42.456  1014  3308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:42.456  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-12 18:13:42.466  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.466  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.466  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.466  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:13:42.466  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:42.466  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-12 18:13:42.466  2653  2653 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:13:42.466  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:42.466  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 18:13:42.466  2653  2653 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 18:13:42.466  2653  2653 D BtGatt.GattService: stop()
09-12 18:13:42.466  2653  2653 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 18:13:42.466  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.466  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.466  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.476  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:42.476  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:13:42.476  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:13:42.476  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:42.476  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.476  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.476  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.476  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.476  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.476  2653  2653 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:13:42.476  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 18:13:42.476  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 18:13:42.486  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:42.486  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.486  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.486  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.486  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.486  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.486  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.486  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-12 18:13:42.496  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 18:13:42.496  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 18:13:42.496  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:13:42.496  1014  1312 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.496  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-12 18:13:42.496  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.496  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.496  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.496  1299  1299 D HeadsetProfile: Bluetooth service disconnected
,09-12 18:13:42.496  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-12 18:13:42.496  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:42.496  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:13:42.496  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.496  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.496  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.496  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.496  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.496  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.496  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.496  2653  2736 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:42.506  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.506  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.506  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.506  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.506  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:13:42.506  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:13:42.506  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:42.506  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.506  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.506  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.506  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:42.506  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:42.506  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.506  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:42.506  2653  2736 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:42.506  2653  2736 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-12 18:13:42.506  2653  2736 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 18:13:42.506  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-12 18:13:42.506  2653  2653 D A2dpService: Received stop request...Stopping profile...
09-12 18:13:42.506  2653  2779 D A2dpStateMachine: Exit Disconnected: -1
,09-12 18:13:42.516  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:13:42.516  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.516  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 18:13:42.516  2906  2906 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.516  1299  1299 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.516  1299  1299 D A2dpProfile: Bluetooth service disconnected
09-12 18:13:42.516  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-12 18:13:42.516  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:42.516  2653  2653 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 18:13:42.516  2653  2653 D HidService: Received stop request...Stopping profile...
09-12 18:13:42.516  2653  2653 D HidService: Stopping Bluetooth HidService
,09-12 18:13:42.516  2653  2653 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=261 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-12 18:13:42.516  6363  6363 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=254 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$Me,thodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:42.516  6363  6363 D ,StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.526  1014  1026 I ActivityManager: Killing 5047:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-12 18:13:42.516  2653  2653 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  2653  2653 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.k.c(PG:583)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  6363  6363 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 18:13:42.516  6363  6363 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:13:42.516  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.536  1299  1299 D BluetoothInputDevice: Proxy object disconnected
09-12 18:13:42.536  1299  1299 D HidProfile: Bluetooth service disconnected
09-12 18:13:42.536  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-12 18:13:42.546  2653  2653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 18:13:42.546  2653  2653 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 18:13:42.546  2653  2653 D HealthService: Received stop request...Stopping profile...
09-12 18:13:42.546  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.546  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-12 18:13:42.546  2653  2653 D PanService: Received stop request...Stopping profile...
09-12 18:13:42.546  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.546  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:42.546  2653  2653 D BluetoothMapService: Received stop request...Stopping profile...
09-12 18:13:42.546  1299  1299 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:42.546  1299  1299 D PanProfile: Bluetooth service disconnected
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.556  2653  2653 D SapService: Received stop request...Stopping profile...
09-12 18:13:42.556  1299  1299 D BluetoothMap: Proxy object disconnected
09-12 18:13:42.556  1299  1299 D MapProfile: Bluetooth service disconnected
09-12 18:13:42.556  2653  2653 D SapService: Stopping Bluetooth SapService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:13:42.556  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 18:13:42.556  1299  1299 D SapProfile: Bluetooth service disconnected
09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 18:13:42.556  2653  2653 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 18:13:42.556  2653  2782 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 18:13:42.556  2653  2653 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:13:42.556  2653  2653 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.556  2653  2653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:13:42.556  2653  2653 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.556  2653  2653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:13:42.556  2653  2653 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:42.556  2653  2653 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 18:13:42.556  2653  2653 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 18:13:42.556  2653  2653 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 18:13:42.556  2653  2653 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-12 18:13:42.566  2653  2736 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 18:13:42.566  2653  2736 D BluetoothAdapterProperties: Setting state to 10
09-12 18:13:42.566  2653  2736 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 18:13:42.566  2653  2736 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:42.566  2653  2736 D BluetoothAdapterService: updateAdapterState state is 10
09-12 18:13:42.566  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:42.566  1904  2097 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.566  1904  2097 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.566  2653  2736 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:42.566  2653  2736 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 18:13:42.566  2653  2736 I BluetoothAdapterState: Entering OffState
09-12 18:13:42.566  1177  2714 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.566  1177  2714 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.566  1299  1311 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:13:42.566  1299  1308 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  1299  1308 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  2653  2974 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  2653  2974 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  1437  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  1450  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  1450  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  1299  1311 D BluetoothMap: onBluetoothStateChange: up=false
09-12 18:13:42.576  1299  1308 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 18:13:42.576  1299  1308 D Bluetoothsap: Unbinding service...
09-12 18:13:42.576  1424  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  1424  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  1014  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  2906  2915 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.576  2906  2915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.576  2906  2920 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:42.576  2653  2667 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:42.586  1299  1308 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 18:13:42.586  6205  6213 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:42.586  6205  6213 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:42.586  6205  6213 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 18:13:42.586  6205  6213 D BluetoothLeAdvertiser: Exit stop advertising
09-12 18:13:42.586  6205  6213 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 18:13:42.586  6205  6213 D BluetoothLeScanner: Exiting stopAllScan
09-12 18:13:42.586  1299  1311 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 18:13:42.586  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-12 18:13:42.586  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-12 18:13:42.596  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.596  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-12 18:13:42.596  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-12 18:13:42.596  6363  6385 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 18:13:42.596  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:42.596  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:42.606  1177  1721 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
09-12 18:13:42.606  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:42.606  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-12 18:13:42.606  1177  1721 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
09-12 18:13:42.606  1787  1787 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:13:42.606  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
09-12 18:13:42.606  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:42.606  1014  1312 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:42.606  1904  2108 D BluetoothAdapter: 137638572: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:42.606  1904  2108 D BluetoothAdapter: 137638572: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:42.606  1014  1555 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:42.606  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:42.616  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:42.616  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.616  1014  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:42.616  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-12 18:13:42.616  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:42.616  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.616  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.616  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:13:42.616  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:42.616  1014  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:42.616  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.616  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 18:13:42.616  1014  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:42.616  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 18:13:42.616  1014  1555 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 18:13:42.626  2653  2745 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 18:13:42.616  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-12 18:13:42.626  2653  2653 I GKI_LINUX: GKI_exit_task 1 done
09-12 18:13:42.626  2653  2653 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 18:13:42.626  2653  2653 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 18:13:42.626  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.626  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.626  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:42.626  2653  2653 I art     : System.exit called, status: 0
09-12 18:13:42.626  2653  2653 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 18:13:42.646  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:42.646  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:42.646  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:42.646  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 18:13:42.646  1014  1312 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 18:13:42.656  1014  1312 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 18:13:42.656  1014  1312 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-12 18:13:42.656  1014  1312 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-12 18:13:42.656  1014  1312 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:13:42.656  1014  1312 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-12 18:13:42.656  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.656  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.656  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.656  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.676  6397  6397 E Zygote  : MountEmulatedStorage()
,09-12 18:13:42.676  6397  6397 E Zygote  : v2
09-12 18:13:42.676  6397  6397 I libpersona: KNOX_SDCARD checking this for 1002
09-12 18:13:42.676  6397  6397 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:42.676  6397  6397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:42.676  1014  1312 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6397 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-12 18:13:42.676  6397  6397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:42.676  6397  6397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:42.696  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
09-12 18:13:42.696  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-12 18:13:42.696   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:42.696  1904  4561 V NativeCrypto: Read error: ssl=0xb7fb3310: I/O error during system call, Connection timed out
,09-12 18:13:42.706  1904  4561 V NativeCrypto: SSL shutdown failed: ssl=0xb7fb3310: I/O error during system call, Broken pipe
09-12 18:13:42.706  6397  6397 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:42.706  6397  6397 D ActivityThread: Added TimaKeyStore provider
09-12 18:13:42.706  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.706  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:13:42.706  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:13:42.706  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-12 18:13:42.706  1014  1128 E ConnectivityService: updateNetworkInfo()
09-12 18:13:42.706  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.706  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.706  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.706  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.706  1014  1128 E ConnectivityService: updateNetworkInfo()
09-12 18:13:42.706  1904  4561 E GCM     : Wifi connection closed with errorCode 20
09-12 18:13:42.706  1014  1138 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-12 18:13:42.706  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:42.706  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.706  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:13:42.706  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 18:13:42.706  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.706  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-12 18:13:42.706  1014  2277 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 18:13:42.706  1014  2277 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
09-12 18:13:42.716  1014  2277 I qtaguid : Untagging socket 360
09-12 18:13:42.716  1014  2277 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:13:42.716  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:42.716  1014  1125 D WifiP2pService: InactiveState{ what=131204 }
09-12 18:13:42.716  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:42.716  1014  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 18:13:42.716  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.716  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.716  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.716  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:42.716  1014  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 18:13:42.726  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 18:13:42.726  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1,
09-12 18:13:42.726  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:42.726  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-12 18:13:42.726  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:42.726  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:42.726  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
,09-12 18:13:42.736  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:13:42.736  1014  1125 D WifiP2pService: P2pDisablingState
,09-12 18:13:42.736  1014  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 18:13:42.736  1014  1125 D WifiP2pService: p2p socket connection lost
09-12 18:13:42.736  1014  1125 D WifiP2pService: P2pDisabledState
,09-12 18:13:42.736  1014  1126 E WifiNative-wlan0: do suspend true
09-12 18:13:42.736  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:42.736  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:42.736  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 18:13:42.736  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 18:13:42.736  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:42.736  1014  1046 D WifiDisplayController: disconnect
09-12 18:13:42.736  1014  1046 D WifiDisplayController: updateConnection
09-12 18:13:42.736  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:42.736  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:13:42.736  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:42.736  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:42.736  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 18:13:42.736  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:42.746  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:13:42.746  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:42.746  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 18:13:42.746  6397  6397 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 18:13:42.746  6397  6397 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:13:42.776  6397  6397 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink,
,09-12 18:13:42.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding GattService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding HeadsetService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding A2dpService
,09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding HidService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding HealthService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding PanService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding SapService,
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding SapClientService
,09-12 18:13:42.806  6397  6397 D BtSettings.ProfileConfig: Adding HidDevService
09-12 18:13:42.806  6397  6397 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 18:13:42.806  1014  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-12 18:13:42.806  1014  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.806  1014  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:13:42.806  1014  1217 D SettingsProvider: selectionArgs: false
09-12 18:13:42.806  1014  1217 D SettingsProvider: selectionArgs: 1002
,09-12 18:13:42.806  1014  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.806  1014  1217 D SettingsProvider: ret = -1
,09-12 18:13:42.806  1014  3308 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
09-12 18:13:42.806  1014  3308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.806  1014  3308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.806  1014  3308 D SettingsProvider: selectionArgs: false
09-12 18:13:42.806  1014  3308 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.806  1014  3308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.806  1014  3308 D SettingsProvider: ret = -1
,09-12 18:13:42.806  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-12 18:13:42.806  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.806  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.806  1014  1026 D SettingsProvider: selectionArgs: false
09-12 18:13:42.806  1014  1026 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.806  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.806  1014  1026 D SettingsProvider: ret = -1
,09-12 18:13:42.816  1014  3305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-12 18:13:42.816  1014  3305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  3305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  3305 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  3305 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  3305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:13:42.816  1014  3305 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  1326 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-12 18:13:42.816  1014  1326 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1326 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-12 18:13:42.816  1014  1326 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1326 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  1326 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  1326 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  1485 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-12 18:13:42.816  1014  1485 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1485 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  1485 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1485 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  1485 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:13:42.816  1014  1485 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-12 18:13:42.816  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  1492 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1492 D SettingsProvider: selectionArgs: 1002,
09-12 18:13:42.816  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  1492 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  1561 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-12 18:13:42.816  1014  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-12 18:13:42.816  1014  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  1561 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1561 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  1561 D SettingsProvider: ret = -1
,09-12 18:13:42.816  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:42.816  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  1027 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1027 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:13:42.816  1014  1027 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  1312 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:42.816  1014  1312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:13:42.816  1014  1312 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1312 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  1312 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  1312 D SettingsProvider: ret = -1
,09-12 18:13:42.816  1014  1559 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-12 18:13:42.816  1014  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:42.816  1014  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  1559 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  1559 D SettingsProvider: selectionArgs: 1002
,09-12 18:13:42.816  1014  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  1559 D SettingsProvider: ret = -1
09-12 18:13:42.816  1014  3304 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-12 18:13:42.816  1014  3304 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 18:13:42.816  1014  3304 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:13:42.816  1014  3304 D SettingsProvider: selectionArgs: false
09-12 18:13:42.816  1014  3304 D SettingsProvider: selectionArgs: 1002
09-12 18:13:42.816  1014  3304 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:42.816  1014  3304 D SettingsProvider: ret = -1
,09-12 18:13:42.826  1014  1555 I ActivityManager: Killing 5497:com.google.android.partnersetup/u0a15 (adj 15): empty #31
09-12 18:13:42.826  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:42.826  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:42.836  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:42.836  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.836  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.836  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:42.846  1904  6417 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 18:13:42.846  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:13:42.846  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:42.846  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:42.846  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.846  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:42.846  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:42.846  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:42.856  3742  3742 I Hs20UtilService: Starting #8
,09-12 18:13:42.856  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:42.856  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.856  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:42.856  3742  3757 I Hs20UtilService: Message received 5007
,09-12 18:13:42.866  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:13:42.866  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:42.866  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:42.866  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
09-12 18:13:42.866  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:42.866  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:42.876  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:42.876  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.876  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.876  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-12 18:13:42.876  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-12 18:13:42.876  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.876  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.876  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:42.876  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:42.896  6419  6419 E Zygote  : MountEmulatedStorage()
,09-12 18:13:42.896  6419  6419 E Zygote  : v2
09-12 18:13:42.896  6419  6419 I libpersona: KNOX_SDCARD checking this for 10104
09-12 18:13:42.896  6419  6419 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:42.896  6419  6419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:42.896  1014  1026 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6419 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-12 18:13:42.896  1014  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:42.906  6419  6419 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:42.906  6419  6419 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:42.906  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:42.906  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:42.906  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:42.916  1904  6417 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false,
,09-12 18:13:42.926  6419  6419 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:42.926  6419  6419 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:42.936  6419  6419 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 18:13:43.126  6419  6442 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-12 18:13:43.126  6419  6442 I Babel   : MmsConfig.loadMmsSettings
,09-12 18:13:43.126  6419  6442 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-12 18:13:43.126  6419  6442 I Babel   : MmsConfig.loadFromDatabase
,09-12 18:13:43.136  6419  6442 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-12 18:13:43.146  6419  6442 I Babel   : MmsConfig.loadFromResources
,09-12 18:13:43.146  6419  6442 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 18:13:43.146  6419  6442 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-12 18:13:43.146  1014  1559 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-12 18:13:43.146  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 18:13:43.156  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.156  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:43.156  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 18:13:43.156  6419  6419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:43.196  6419  6419 I Babel_StickerModule: App launched.
,09-12 18:13:43.196  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:13:43.206  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:43.206  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:43.206  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,09-12 18:13:43.206  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:43.206  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:43.206  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:43.206  1014  3308 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 18:13:43.206  1014  3308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.206  1014  3308 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.206  1014  3308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.206  1014  3308 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.226   283   681 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-12 18:13:43.226   283   681 W QCamera2Factory: getCameraInfo: X
,09-12 18:13:43.226  6444  6444 E Zygote  : MountEmulatedStorage()
,09-12 18:13:43.226  6444  6444 E Zygote  : v2
09-12 18:13:43.226  6444  6444 I libpersona: KNOX_SDCARD checking this for 10068
09-12 18:13:43.226  6444  6444 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:43.226  6444  6444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 18:13:43.236  1014  3308 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6444 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:43.236   283   688 W QCamera2Factory: getCameraInfo: E, camera_id = 1,
09-12 18:13:43.236   283   688 W QCamera2Factory: getCameraInfo: X
,09-12 18:13:43.236  6444  6444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 18:13:43.246  6444  6444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:43.256  6419  6419 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 18:13:43.266  6419  6419 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 18:13:43.266  6419  6419 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 18:13:43.266  6444  6444 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.266  6444  6444 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.276  6419  6419 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-12 18:13:43.276  6419  6419 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 18:13:43.286  6419  6419 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 18:13:43.286  6419  6419 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 18:13:43.286  6419  6419 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 18:13:43.286  6419  6419 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 18:13:43.286  6444  6444 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:13:43.306  6419  6419 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 18:13:43.306  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:43.306  6419  6419 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 18:13:43.306  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:13:43.316  6419  6419 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-12 18:13:43.316  6419  6419 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 18:13:43.316  6419  6419 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 18:13:43.316  6419  6419 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 18:13:43.326  6419  6419 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 18:13:43.326  6419  6419 W VideoCapabilities: Unsupported mime video/mp43
,09-12 18:13:43.326  6419  6419 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 18:13:43.336  6419  6419 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 18:13:43.346  6444  6444 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:43.346  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 18:13:43.346  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.346  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.346  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.346  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.356  6419  6419 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
09-12 18:13:43.356  6459  6459 I libpersona: KNOX_SDCARD checking this for 10069
09-12 18:13:43.356  6459  6459 E Zygote  : MountEmulatedStorage()
09-12 18:13:43.356  6459  6459 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:43.356  6459  6459 E Zygote  : v2
,09-12 18:13:43.356  6459  6459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:43.356  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6459 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:43.366  6459  6459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:43.366  6459  6459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 18:13:43.376  1014  1048 I PowerManagerService: [PWL] Off : 50s ago
,09-12 18:13:43.376  6459  6459 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.386  6459  6459 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.396  1014  3308 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-12 18:13:43.396  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-12 18:13:43.396  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.396  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:43.396  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 18:13:43.406  1014  1555 I ActivityManager: Killing 5585:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-12 18:13:43.406  6459  6459 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:43.416  1014  1492 I ActivityManager: Killing 5801:com.sec.pcw.device/1000 (adj 15): empty #31
,09-12 18:13:43.506  1014  2749 D SSRM:n  : SIOP:: AP = 350
,09-12 18:13:43.536  1014  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 18:13:43.536  1014  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-12 18:13:43.546  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:13:43.546  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:43.546  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.546  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.546  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.546  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:43.556   278  1009 D EnterpriseController: uids 1000,
09-12 18:13:43.556   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:13:43.556   278  1009 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-12 18:13:43.556  3842  6266 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
09-12 18:13:43.556  1014  1128 E NetdConnector: NDC Command {53 network destroy 502} took too long (848ms)
09-12 18:13:43.556  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 18:13:43.556  1014  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
09-12 18:13:43.556  1450  1450 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:13:43.556  1014  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-12 18:13:43.556  1177  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 18:13:43.556  1014  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 18:13:43.556  1014  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-12 18:13:43.556  1014  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 18:13:43.556  1014  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 18:13:43.566  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 18:13:43.556  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 18:13:43.566   278  1013 D CommandListener: Clearing all IP addresses on wlan0
09-12 18:13:43.566  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-12 18:13:43.566  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 18:13:43.566  1014  2277 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:43.566  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 18:13:43.566  1014  1129 D Tethering: MasterInitialState.processMessage what=3
09-12 18:13:43.566  1014  1128 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 18:13:43.566  1014  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-12 18:13:43.566  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:43.566  1014  1123 V NetworkStats: updateIfacesLocked()
09-12 18:13:43.566  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.566  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:13:43.576  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:13:43.576  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:43.576  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:43.576  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-12 18:13:43.576  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
09-12 18:13:43.576  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
09-12 18:13:43.576  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 18:13:43.576  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 18:13:43.576  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,09-12 18:13:43.576  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 18:13:43.576  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 18:13:43.586  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.586  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:13:43.586  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 18:13:43.586  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.586  1014  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 18:13:43.586  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.586  1014  1123 V NetworkStats: performPollLocked() took 13ms
09-12 18:13:43.586  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:43.586  2146  2146 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:43.596  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 18:13:43.596  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:43.606  1014  3308 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-12 18:13:43.606  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:43.606  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.606  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.606  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:13:43.606  3742  3742 I Hs20UtilService: Starting #9
09-12 18:13:43.606  3742  3757 I Hs20UtilService: Message received 5007
09-12 18:13:43.606  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.606  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:43.616  1014  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 18:13:43.616  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:43.616  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:43.616  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.616  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.616  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:43.616  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:43.616  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:43.616  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 18:13:43.616  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:43.616  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:43.616  1014  1126 D SecContentProvider2: mCursor = null
09-12 18:13:43.616  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:43.616  1177  1177 D HotspotTile: onReceive : 0, 0
09-12 18:13:43.616  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:43.616  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:43.616  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:43.616  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:43.616  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:43.626  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:43.626  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:43.626  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:43.626  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:43.626  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:13:43.626  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:43.626  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:43.636  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:43.636  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:43.636  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:43.636  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:43.656  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.656  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.656  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.666  1014  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:43.666  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:43.666  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.666  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.666  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:43.666  1014  1138 I ActivityManager: Killing 5515:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-12 18:13:43.676  3742  3742 I Hs20UtilService: Starting #10
,09-12 18:13:43.676  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:13:43.676  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-12 18:13:43.676  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.676  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.676  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:43.676  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:43.696  6477  6477 E Zygote  : MountEmulatedStorage()
,09-12 18:13:43.696  6477  6477 E Zygote  : v2
09-12 18:13:43.696  6477  6477 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:43.696  6477  6477 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:43.696  6477  6477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:43.696  6477  6477 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:43.696  1014  1041 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 18:13:43.696  6477  6477 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:43.726  2146  2146 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:43.726  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.736  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.736  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.736  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.736  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.746  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-12 18:13:43.746  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-12 18:13:43.746  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:43.746  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.746  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.746  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.746  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.746  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.756  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.756  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.756  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.756  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.756  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.756  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.766  6477  6477 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:43.766  6477  6477 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:43.766  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.766  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.766  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.766  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,09-12 18:13:43.776  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:43.776  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.776  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-12 18:13:43.776  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.776  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 18:13:43.776  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 18:13:43.786  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,09-12 18:13:43.796   288   288 E SMD     : DCD OFF
,09-12 18:13:43.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:43.806  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:43.806  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 18:13:43.806  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:13:43.806  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:43.816  1014  3304 I ActivityManager: Killing 5817:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-12 18:13:43.826  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.826  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.826  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.826  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.826  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.826  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.826  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.826  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.826  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.836  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.836  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.836  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.836  2146  2146 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-12 18:13:43.836  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.836  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:43.836  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:13:43.836  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:43.846  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.846  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.846  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.846  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.856  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.856  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.856  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.856  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.866  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.866  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.866  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.866  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:43.866  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:43.866  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 18:13:43.866  2146  2146 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-12 18:13:43.876  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:13:43.876  2146  2146 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 18:13:43.876  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:43.876  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:13:43.876  2146  2146 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-12 18:13:43.876  2146  2146 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 18:13:43.876  2146  2146 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 18:13:43.876  1014  1129 D Tethering: InitialState.processMessage what=4
09-12 18:13:43.876  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:43.876  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:43.876  1014  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-12 18:13:43.876  1014  1129 E Tethering: No numeric data
09-12 18:13:43.876  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:43.876  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:43.876  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:13:43.876  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:43.876  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:13:43.876  1014  1129 D Tethering: clearTetheredNotification()
09-12 18:13:43.876  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:43.876  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:13:43.876  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:13:43.876  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:13:43.876  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-12 18:13:43.876  1177  1177 D HotspotTile: updateTetherState():false, false
,09-12 18:13:43.886  1014  1123 V NetworkStats: performPollLocked() took 6ms
,09-12 18:13:43.886  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:43.886  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:43.886  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:43.936   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb745d7c8
09-12 18:13:43.936   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-12 18:13:43.936   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-12 18:13:43.936   273   330 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220159352)
,09-12 18:13:43.966   273   330 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
09-12 18:13:43.966   273   330 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,09-12 18:13:43.966   273   330 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220159352) wakelock released: 1, error no: 0
09-12 18:13:43.966   273   330 I rmt_storage: 
09-12 18:13:43.966   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb745d7c8
,09-12 18:13:44.066  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-12 18:13:44.066  1014  1014 I ApplicationPolicy: updateDataUsageMap
09-12 18:13:44.076  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:44.086  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:44.086  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:44.086  3208  3208 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-12 18:13:44.096  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 18:13:44.096  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.096  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.096  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.096  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.096  3208  3208 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-12 18:13:44.126  6508  6508 E Zygote  : MountEmulatedStorage(),
,09-12 18:13:44.126  6508  6508 E Zygote  : v2
09-12 18:13:44.126  6508  6508 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:44.126  6508  6508 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.126  1014  1041 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6508 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 18:13:44.126  6508  6508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:44.126  6508  6508 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 18:13:44.136  6508  6508 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.156  6508  6508 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.156  6508  6508 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.176  2146  2146 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:44.176  6508  6508 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 18:13:44.176  6508  6508 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 18:13:44.176  6508  6508 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 18:13:44.186  6508  6508 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 18:13:44.186  6508  6508 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 18:13:44.186  6508  6508 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 18:13:44.186  6508  6508 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:44.186  1014  1217 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-12 18:13:44.186  1014  1217 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-12 18:13:44.186  1014  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-12 18:13:44.196  6508  6523 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 18:13:44.196  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.196  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.196  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.196  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.206  6525  6525 E Zygote  : MountEmulatedStorage(),
09-12 18:13:44.206  6525  6525 E Zygote  : v2
09-12 18:13:44.206  6525  6525 I libpersona: KNOX_SDCARD checking this for 10111
09-12 18:13:44.206  6525  6525 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:44.206  6525  6525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-12 18:13:44.206  1014  1217 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6525 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.206  6525  6525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 18:13:44.206  6525  6525 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 18:13:44.206  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
09-12 18:13:44.206  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.206  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.206  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.206  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.226  6540  6540 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.226  6540  6540 E Zygote  : v2
09-12 18:13:44.226  6540  6540 I libpersona: KNOX_SDCARD checking this for 10009
09-12 18:13:44.226  6540  6540 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.236  6540  6540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:44.236  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.236  6525  6525 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.236  6540  6540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:44.236  6540  6540 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.236  1014  1041 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6540 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.236  1014  1217 I ActivityManager: Killing 4177:com.sec.spp.push/u0a35 (adj 15): empty #31
,09-12 18:13:44.246  2146  2146 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 18:13:44.256   309   309 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 22.973ms
09-12 18:13:44.256  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:44.256  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:44.256  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:44.266  6540  6540 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.266  6540  6540 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.266  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
09-12 18:13:44.266  1725  1725 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:44.276  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.276  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.276  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.276  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.276   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 17.171ms
,09-12 18:13:44.296   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.893ms
,09-12 18:13:44.326  6555  6555 E Zygote  : MountEmulatedStorage(),
,09-12 18:13:44.326  6555  6555 E Zygote  : v2,
,09-12 18:13:44.326  6555  6555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:44.326  1014  1041 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6555 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-12 18:13:44.326  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-12 18:13:44.326  6555  6555 I libpersona: KNOX_SDCARD checking this for 10145
09-12 18:13:44.326  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 18:13:44.326  6555  6555 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.336  1014  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 18:13:44.336  6555  6555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:44.336  6419  6419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:44.336  6555  6555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.336  1725  1725 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-12 18:13:44.336  1725  1725 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-12 18:13:44.336  1725  1725 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-12 18:13:44.336  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:44.336  1725  1725 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:44.346  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:44.346  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:44.346  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:44.346  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:13:44.346  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:44.346  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:44.346  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:44.346  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:44.346  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-12 18:13:44.346  1177  1177 D HotspotTile: onReceive : 1, 0
09-12 18:13:44.346  1904  2108 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:13:44.346  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:44.346  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:44.346  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:44.356  1320  1333 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,09-12 18:13:44.356  1725  1725 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:13:44.356  1725  1725 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-12 18:13:44.366  1014  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 18:13:44.366  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.366  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.366  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.366  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.376  6525  6525 I MusicStore: Database version: 108
,09-12 18:13:44.376  6555  6555 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 18:13:44.376  6555  6555 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.386  6574  6574 E Zygote  : MountEmulatedStorage()
09-12 18:13:44.386  1014  1492 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6574 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 18:13:44.386  6574  6574 E Zygote  : v2
09-12 18:13:44.386  6574  6574 I libpersona: KNOX_SDCARD checking this for 10081
09-12 18:13:44.386  6574  6574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:44.386  6574  6574 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.386  6574  6574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:44.386  6574  6574 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.396  1725  1725 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-12 18:13:44.416  6574  6574 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.416  1014  1326 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 18:13:44.416  6574  6574 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.416  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 18:13:44.416  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.416  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.416  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:44.426  6555  6555 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-12 18:13:44.426  6555  6555 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:13:44.426  6555  6555 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 18:13:44.426  6555  6555 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:13:44.426  6555  6555 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 18:13:44.436  1014  1559 I ActivityManager: Killing 5128:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-12 18:13:44.436  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 18:13:44 GMT+02:00 2016
,09-12 18:13:44.436  1014  1561 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 18:13:44.446  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.446  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.446  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:44.446  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 18:13:44.446  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 18:13:44.456  1014  1138 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 18:13:44.456  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.456  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.456  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.456  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.466  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 18:13:44.466  3761  3761 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 18:13:44.466  3761  3761 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 18:13:44.466  1014  1138 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6592 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-12 18:13:44.476  6592  6592 E Zygote  : MountEmulatedStorage()
09-12 18:13:44.476  6592  6592 I libpersona: KNOX_SDCARD checking this for 10034
09-12 18:13:44.476  6592  6592 E Zygote  : v2
09-12 18:13:44.476  6592  6592 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.476  6592  6592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:44.476  3761  6591 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 18:13:44.476  3761  6591 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-12 18:13:44.476  6592  6592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:44.476  6592  6592 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.486  3761  6591 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-12 18:13:44.486  3761  6591 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-12 18:13:44.486  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 18:13:44.496  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.496  6592  6592 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.496  1014  1217 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.526  1014  1217 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.526  6525  6525 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-12 18:13:44.526  6525  6525 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 18:13:44.546  6592  6592 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 18:13:44.556  1014  1312 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 18:13:44.556  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.556  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.556  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.556  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.566  3324  6611 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 18:13:44.576  6612  6612 E Zygote  : MountEmulatedStorage()
,09-12 18:13:44.576  6612  6612 E Zygote  : v2
09-12 18:13:44.576  6612  6612 I libpersona: KNOX_SDCARD checking this for 10035
09-12 18:13:44.576  6612  6612 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.576  1014  1312 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6612 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.586  3324  6611 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-12 18:13:44.586  3324  6611 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-12 18:13:44.586  3324  6611 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-12 18:13:44.586  3324  6611 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 18:13:44.586  6612  6612 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:44.586  6612  6612 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:44.596  6612  6612 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
09-12 18:13:44.596  1014  1561 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.606  1014  3308 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.616  1014  3304 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 18:13:44.616  6525  6525 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-12 18:13:44.616  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.616  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:44.616  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.616  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.626  6612  6612 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.626  6612  6612 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.636  6626  6626 E Zygote  : MountEmulatedStorage(),
09-12 18:13:44.636  6626  6626 E Zygote  : v2
,09-12 18:13:44.636  6626  6626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:44.636  6626  6626 I libpersona: KNOX_SDCARD checking this for 10113
09-12 18:13:44.636  6626  6626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:44.636  6626  6626 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.636  6626  6626 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:44.646  1014  3304 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6626 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-12 18:13:44.646  1014  3304 I ActivityManager: Killing 5849:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-12 18:13:44.656  6626  6626 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.656  6626  6626 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.696  6525  6525 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 18:13:44.696  6525  6525 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a123935: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-12 18:13:44.706  6525  6525 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-12 18:13:44.706  6525  6525 D AndroidMusic: GMSCore installation verified
,09-12 18:13:44.706  6612  6647 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 18:13:44.706  6612  6647 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 18:13:44.716  5965  5980 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-12 18:13:44.726  6612  6612 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 18:13:44.726  1014  1561 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.726  5985  5985 I SA      : [DM] init START
,09-12 18:13:44.726  1014  1026 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-12 18:13:44.726  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.726  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:44.726  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 18:13:44.726  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-12 18:13:44.736  6612  6647 D SPPClientService: PushLog.txt file is not deleted.
,09-12 18:13:44.736  6612  6647 D SPPClientService: PushLog.txt file is not deleted.
09-12 18:13:44.736  6612  6647 D SPPClientService: ============PushLog. stop!
,09-12 18:13:44.736  5985  5985 I SA      : [DM] This device is not a Vodafone
,09-12 18:13:44.736  1014  1561 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.736  5965  5980 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-12 18:13:44.736  5965  5980 D BadgeProvider: sendNotify, [notify] : null
09-12 18:13:44.736  5965  5980 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 18:13:44.736  5965  5980 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 18:13:44.736  5965  5980 D BadgeProvider: update, [UpdateCount] : 1
,09-12 18:13:44.746  1476  1476 D Launcher.Model: reloadBadges entered.
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-12 18:13:44.746  5985  5985 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-12 18:13:44.756  5985  5985 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-12 18:13:44.766  1014  1555 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 18:13:44.766  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-12 18:13:44.766  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.766  1014  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.766  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:44.766  6612  6651 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-12 18:13:44.776  1014  1561 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.776  6525  6525 I ConfigStore: Config Database version: 1
,09-12 18:13:44.786  1014  1559 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:13:44.786  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:44.796  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 18:13:44.796  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:13:44.796  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:44.796  1014  1217 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-12 18:13:44.796  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.796  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.796  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.796  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:44.806   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-12 18:13:44.806  5985  5985 I SA      : [SCU] isHaveSA() - false
,09-12 18:13:44.806  5985  5985 I SA      : support phone number id : false
09-12 18:13:44.806  5985  5985 I SA      : [DM] Supports Ref Jpn : true
09-12 18:13:44.806  5985  5985 I SA      : [DM] init END
09-12 18:13:44.806  5985  5985 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
09-12 18:13:44.806  5985  5985 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-12 18:13:44.806  5985  5985 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-12 18:13:44.816  1014  1043 D Tethering: interfaceRemoved wlan0
09-12 18:13:44.816  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 18:13:44.816  5985  5985 I SA      : [SLFUCHKMGR] constructor called
,09-12 18:13:44.816  6656  6656 E Zygote  : MountEmulatedStorage(),
09-12 18:13:44.816  6656  6656 E Zygote  : v2
09-12 18:13:44.816  6656  6656 I libpersona: KNOX_SDCARD checking this for 10159
09-12 18:13:44.816  6656  6656 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:44.826  1014  1217 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6656 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:44.826  6656  6656 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:44.826  6656  6656 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:44.836  5985  5985 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-12 18:13:44.836  5985  5985 I SA      : [OR] == isSIMCardReady false ==
,09-12 18:13:44.836  5985  5985 I SA      : [SCU] == networkStateCheck == false
09-12 18:13:44.836  5985  5985 I SA      : [OR] onReceive END
,09-12 18:13:44.836  6656  6656 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-12 18:13:44.836  1014  3307 I ActivityManager: Killing 5865:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-12 18:13:44.836  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:44.856  6656  6656 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:44.856  6656  6656 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:44.896  1014  1555 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:13:44.896  1014  1555 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:44.896  1014  1555 D SecContentProvider2: mCursor = null
,09-12 18:13:44.906  1014  1555 D WifiService: setWifiEnabled: true pid=6205, uid=10155
,09-12 18:13:44.906  1014  3305 I ActivityManager: Killing 5552:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-12 18:13:44.906  1014  1555 W ActivityManager: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:13:44.906  1014  1555 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:13:44.906  1014  1555 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:44.906  1014  1555 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 18:13:44.906  1014  1555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:13:44.906  1014  1555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:13:44.906  1014  1555 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:13:44.906  1014  1555 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:13:44.916  1014  1555 D SettingsProvider: name = wifi_on
,09-12 18:13:44.916   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 18:13:44.916   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:44.916  1014  3307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:44.916  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.926  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.926  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.926  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:44.936  6525  6525 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 18:13:44.936  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 18:13:44.936   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 18:13:44.936   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:44.946  3842  4593 I iu.UploadsManager: num queued entries: 0
,09-12 18:13:44.946  3842  4593 I iu.UploadsManager: num updated entries: 0
,09-12 18:13:44.946  3842  4593 I iu.SyncManager: NEXT; no task
09-12 18:13:44.946  1014  1043 D Tethering: interfaceRemoved p2p0
09-12 18:13:44.946  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 18:13:44.946  1014  1026 I art     : Explicit concurrent mark sweep GC freed 52626(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 4.784ms total 197.286ms
,09-12 18:13:44.946  6525  6525 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 18:13:44.956   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 18:13:44.956   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:44.956  6525  6525 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 18:13:44.966  1014  3307 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 18:13:44.966  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-12 18:13:44.976  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.976  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.976  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:44.976  1014  1485 I ActivityManager: Killing 5782:com.android.mms/u0a46 (adj 15): empty #31
,09-12 18:13:44.986  1014  3308 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:44.986  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-12 18:13:44.996  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:44.996  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:44.996  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:45.016  1014  3304 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:45.016  1014  3305 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:45.026  1014  1138 I AudioService: getStreamVolume 3 index 0
,09-12 18:13:45.026  6525  6525 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-12 18:13:45.036   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 18:13:45.036   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.036  6525  6525 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-12 18:13:45.036  6626  6676 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 18:13:45.046  1014  1026 D CountryDetector: No listener is left
,09-12 18:13:45.046   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 18:13:45.046   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.046  6626  6676 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 18:13:45.056  1014  1559 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:45.056  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 18:13:45.056  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:45.056  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:45.056  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:45.066  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:45.066  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.066  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:45.066  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:45.066  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:45.066  1014  1326 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:45.076  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.076  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:45.076  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:45.076  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:45.076  1014  1485 I ActivityManager: Killing 5950:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-12 18:13:45.086  1014  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:45.086   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 18:13:45.086   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 18:13:45.096  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 18:13:45.096  6626  6681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 18:13:45.096  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.096  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.096  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.096  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.096   257   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,09-12 18:13:45.096   257   530 W Vold    : Returning OperationFailed - no handler for errno 0
09-12 18:13:45.096  6626  6681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 18:13:45.106  6685  6685 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.106  6685  6685 E Zygote  : v2
09-12 18:13:45.106  6685  6685 I libpersona: KNOX_SDCARD checking this for 10002
09-12 18:13:45.106  6685  6685 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:45.106  6685  6685 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:45.116  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6685 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:45.116  6685  6685 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:45.116  6685  6685 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:45.136  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-12 18:13:45.136  1014  3307 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 18:13:45.136  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.136  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.146  6685  6685 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.146  6685  6685 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.146  1014  1492 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-12 18:13:45.146  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-12 18:13:45.146  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:45.156  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:45.156  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-12 18:13:45.156  6525  6525 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-12 18:13:45.156  1014  1559 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:45.156  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 18:13:45.156  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:45.156  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:45.156  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:45.186  1014  1026 I ActivityManager: Killing 5833:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-12 18:13:45.216  1014  1555 I ActivityManager: Killing 6026:com.wsomacp/u0a25 (adj 15): empty #31
,09-12 18:13:45.226  1014  1326 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 18:13:45.226  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.226  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.226  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.226  1014  1326 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.246  1014  1326 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6717 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 18:13:45.246  6717  6717 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.246  6717  6717 E Zygote  : v2
09-12 18:13:45.246  6717  6717 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:45.246  6717  6717 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:45.246  6717  6717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:13:45.256  6717  6717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:45.256  6717  6717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:45.276  6717  6717 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.276  1014  1561 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:45.276  6717  6717 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.286  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:45.286  1014  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:45.286  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 18:13:45.306  6626  6626 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-12 18:13:45.326  6626  6626 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9259-9260)
09-12 18:13:45.326  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:13:45.326  6626  6626 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c63b022}
,09-12 18:13:45.326  6626  6626 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 18:13:45.326  6626  6626 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 18:13:45.336  6717  6717 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 18:13:45.356  6626  6626 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 18:13:45.356  6626  6626 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 18:13:45.356  6626  6626 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 18:13:45.376  6626  6626 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 18:13:45.376  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-12 18:13:45.376  6626  6626 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-12 18:13:45.386  6626  6626 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 18:13:45.386  6626  6626 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 18:13:45.386  6626  6626 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 18:13:45.386  6626  6626 I Adreno-EGL: Local Branch: 
09-12 18:13:45.386  6626  6626 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 18:13:45.386  6626  6626 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 18:13:45.386  6626  6626 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 18:13:45.446  6626  6745 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 18:13:45.446  6626  6626 I NSApplication: Starting up...
,09-12 18:13:45.456  1014  1559 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 18:13:45.456  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.456  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.456  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.456  1014  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.456  6717  6717 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 18:13:45.466  6717  6717 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
09-12 18:13:45.476  6750  6750 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.476  6750  6750 I libpersona: KNOX_SDCARD checking this for 10120
09-12 18:13:45.476  6750  6750 E Zygote  : v2
09-12 18:13:45.476  6750  6750 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:45.476  6717  6717 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
09-12 18:13:45.476  6750  6750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:45.476  6717  6717 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 18:13:45.476  6717  6717 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-12 18:13:45.476  6717  6717 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
09-12 18:13:45.476  6750  6750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:13:45.476  6750  6750 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 18:13:45.476  1014  1559 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6750 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 18:13:45.476  1014  1559 I ActivityManager: Killing 6010:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-12 18:13:45.486  1014  1559 I ActivityManager: Killing 5884:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-12 18:13:45.496  6750  6750 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.496  6750  6750 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.516  6750  6750 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:13:45.716  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 18:13:45.716  1014  1126 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 18:13:45.836  1014  3304 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-12 18:13:45.846  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.846  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:45.846  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.846  1014  3304 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:45.856  6771  6771 E Zygote  : MountEmulatedStorage()
09-12 18:13:45.856  6771  6771 E Zygote  : v2
09-12 18:13:45.856  6771  6771 I libpersona: KNOX_SDCARD checking this for 10125
09-12 18:13:45.856  6771  6771 I libpersona: KNOX_SDCARD not a persona
09-12 18:13:45.856  6771  6771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:13:45.856  1014  3304 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6771 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,09-12 18:13:45.856  1014  3304 I ActivityManager: Killing 6069:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-12 18:13:45.856  6771  6771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:13:45.866  6771  6771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:13:45.876  6771  6771 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:45.876  6771  6771 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:45.896  6771  6771 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 18:13:45.896  6771  6771 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:13:45.896  6771  6771 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 18:13:45.906  6771  6771 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:13:45.916  6771  6771 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 18:13:45.916  6771  6771 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 18:13:45.916  1014  1485 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-12 18:13:45.926  1014  1485 I ActivityManager: Killing 6094:com.samsung.helphub/1000 (adj 15): empty #31
,09-12 18:13:45.926  1014  3308 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:45.926  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:45.926  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:45.926  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:45.926  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:45.926  3742  3742 I Hs20UtilService: Starting #11
,09-12 18:13:45.926  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:13:45.936  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:45.936  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:45.936  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:45.936  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:46.086  1014  1043 D Tethering: interfaceAdded wlan0
,09-12 18:13:46.086  1014  1129 E Tethering: No numeric data
,09-12 18:13:46.096  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-12 18:13:46.096  1014  1129 D Tethering: clearTetheredNotification()
,09-12 18:13:46.106  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:13:46.106  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:46.106  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:46.106  1014  1129 D Tethering: InitialState.processMessage what=4
09-12 18:13:46.106  1014  1129 E Tethering: No numeric data
,09-12 18:13:46.106  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-12 18:13:46.106  1014  1129 D Tethering: clearTetheredNotification(),
09-12 18:13:46.106  1014  1043 D Tethering: interfaceAdded p2p0
09-12 18:13:46.116  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring,
,09-12 18:13:46.116  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:46.116  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:13:46.116  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.116   278  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-12 18:13:46.126   278  1013 D SoftapController: Softap fwReload - Ok
,09-12 18:13:46.126   278  1013 D CommandListener: Setting iface cfg
09-12 18:13:46.126   278  1013 D CommandListener: Trying to bring down wlan0
,09-12 18:13:46.126   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:46.126  1014  1126 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 18:13:46.136  1014  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-12 18:13:46.136  1014  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-12 18:13:46.176  6794  6794 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 18:13:46.176  6794  6794 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 18:13:46.176  6794  6794 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 18:13:46.186  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:46.186  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-12 18:13:46.186  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 18:13:46.186  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
,09-12 18:13:46.186  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:46.186  1014  1123 V NetworkStats: performPollLocked() took 5ms
,09-12 18:13:46.186  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:13:46.186  1177  1177 D HotspotTile: updateTetherState():false, false
,09-12 18:13:46.186  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:46.186  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:46.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:46.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:46.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:46.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:46.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:46.196  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:46.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-12 18:13:46.196  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:13:46.196  1177  1177 D HotspotTile: onReceive : 2, 0
,09-12 18:13:46.196  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-12 18:13:46.196  6794  6794 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-12 18:13:46.196  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:46.206  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:46.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6794
09-12 18:13:46.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 18:13:46.206  6794  6794 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 18:13:46.206  6794  6794 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.206  6794  6794 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-12 18:13:46.206  6794  6794 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 18:13:46.206  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:13:46.206  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:13:46.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6794
09-12 18:13:46.206  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:13:46.206   365   365 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
09-12 18:13:46.206  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 18:13:46.206  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:46.206  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:46.206  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:46.206  3742  3742 I Hs20UtilService: Starting #12
09-12 18:13:46.206  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:13:46.216  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:13:46.216  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:46.216  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:46.216  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:46.356   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-12 18:13:46.366  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-12 18:13:46.426  6794  6794 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 18:13:46.426  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:13:46.436  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 18:13:46.436   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6794
09-12 18:13:46.436   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:13:46.436  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 18:13:46.436  6794  6794 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.436  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 18:13:46.436  6794  6794 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.436  6794  6794 E wpa_supplicant: SIM READ ERROR
09-12 18:13:46.436  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.436  6794  6794 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.436  6794  6794 E wpa_supplicant: SIM READ ERROR
,09-12 18:13:46.436  6794  6794 I wpa_supplicant: Blacklist: Clear (all) 
09-12 18:13:46.436  6794  6794 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:13:46.436  6794  6794 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:13:46.436  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.436  6794  6794 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 18:13:46.436  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 18:13:46.436  6794  6794 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 18:13:46.446  6794  6794 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:13:46.446  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:13:46.446  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:46.446  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:46.536  6794  6794 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 18:13:46.786  6794  6794 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:46.786  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:13:46.796   288   288 E SMD     : DCD OFF
,09-12 18:13:46.796  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 18:13:46.806   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6794
,09-12 18:13:46.806   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:13:46.806  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 18:13:46.806  6794  6794 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.806  6794  6794 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 18:13:46.806  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 18:13:46.816  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-12 18:13:46.816   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6794
,09-12 18:13:46.816   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:13:46.816  6794  6794 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 18:13:46.816  6794  6794 I wpa_supplicant: ssSupport state is = 1
09-12 18:13:46.816  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:46.816  6794  6794 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:46.816  6794  6794 E wpa_supplicant: SIM READ ERROR
09-12 18:13:46.816  6794  6794 I wpa_supplicant: wpa_default_ap_write_once
,09-12 18:13:46.816  6794  6794 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:13:46.816  6794  6794 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:13:46.826  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:46.826  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:46.826  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.826  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-12 18:13:46.826  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:13:46.826  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:46.866  6794  6794 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,09-12 18:13:46.866  6794  6794 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 18:13:46.956  6794  6794 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-12 18:13:46.956  6794  6794 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-12 18:13:46.956  6794  6794 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 18:13:47.096  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:47.096  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:13:47.096  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:13:47.136  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-12 18:13:47.146  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-12 18:13:47.146  6794  6794 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 18:13:47.146  6794  6794 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:13:47.146  6794  6794 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:13:47.146  6794  6794 E wpa_supplicant: SIM READ ERROR
09-12 18:13:47.146  6794  6794 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:47.176  6794  6794 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-12 18:13:47.186  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
09-12 18:13:47.186  6794  6794 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 18:13:47.186  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:47.186  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:13:47.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.186  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.186  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:47.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 18:13:47.196  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:47.196  1014  1126 D WifiConfigStore: Loading config and enabling all networks 
09-12 18:13:47.196  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:47.196  1177  1177 D HotspotTile: onReceive : 3, 0
,09-12 18:13:47.196  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:47.206  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:47.206  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:47.206  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:47.206  1014  1126 E WifiConfigStore: Not a HS20
,09-12 18:13:47.206  1014  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 18:13:47.206  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:47.206  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:47.206  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:47.206  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:47.216  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 18:13:47.216  1014  3307 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:47.216  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:47.216  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 18:13:47.216  6794  6794 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 18:13:47.216  6794  6794 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 18:13:47.216  6794  6794 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:13:47.216  6794  6794 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-12 18:13:47.216  6794  6794 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 18:13:47.216  6794  6794 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 18:13:47.216  6794  6794 I wpa_supplicant: First Scan Start
09-12 18:13:47.216  6794  6794 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:13:47.216  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:47.216  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:47.216  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:13:47.226  1014  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-12 18:13:47.226  1014  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:13:47.226  1014  1126 I WifiNative-HAL: startHal
09-12 18:13:47.226  1014  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9e25488c
09-12 18:13:47.226  1014  1126 I WifiNative-HAL: Could not start hal
,09-12 18:13:47.226  3742  3742 I Hs20UtilService: Starting #13
,09-12 18:13:47.226  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:13:47.226  1014  1126 E WifiNative-wlan0: do suspend true
,09-12 18:13:47.226  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 18:13:47.226  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:13:47.226  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:47.226  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:47.226  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:47.226  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 18:13:47.236  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:47.236  1014  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
09-12 18:13:47.236  1014  1149 I WifiNative-HAL: startHal
,09-12 18:13:47.236  1014  1014 D RttService: SCAN_AVAILABLE : 3
,09-12 18:13:47.236  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9ccd99bc
09-12 18:13:47.236  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:47.236  1014  1149 I WifiNative-HAL: Could not start hal
09-12 18:13:47.236  1014  1149 E WifiScanningService: could not start HAL
,09-12 18:13:47.236   278  1013 D CommandListener: Setting iface cfg
09-12 18:13:47.236   278  1013 D CommandListener: Trying to bring up p2p0
09-12 18:13:47.236  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:13:47.236  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:13:47.236  1014  1126 E WifiNative-wlan0: invaild command id : 215
,09-12 18:13:47.236  1014  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 18:13:47.236  1014  1125 D WifiP2pService: P2pEnablingState
,09-12 18:13:47.236  1014  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-12 18:13:47.236  6419  6419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 18:13:47.246  1014  1125 D WifiP2pService: P2p socket connection successful
,09-12 18:13:47.246  6794  6794 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 18:13:47.246  1014  1125 D WifiP2pService: P2pEnabledState
,09-12 18:13:47.246  6794  6794 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:13:47.246  6794  6794 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-12 18:13:47.246  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-12 18:13:47.246  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 18:13:47.246  1014  1126 D SecContentProvider2: mCursor = null
09-12 18:13:47.246  1014  1128 E ConnectivityService: updateNetworkInfo(),
09-12 18:13:47.246  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:47.246  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 18:13:47.246  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.246  1014  1046 D WifiDisplayController: disconnect
09-12 18:13:47.246  1014  1046 D WifiDisplayController: updateConnection
09-12 18:13:47.246  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.246  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:47.256  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:13:47.256  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:13:47.256  1014  1126 E WifiNative-wlan0: invaild command id : 215
09-12 18:13:47.256  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:13:47.256  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:13:47.256  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:13:47.256  1014  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 18:13:47.256  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 18:13:47.256  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:47.256  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:47.256  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:47.256  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:13:47.266  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 18:13:47.266  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-12 18:13:47.266  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 18:13:47.266  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:47.266  1014  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-12 18:13:47.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 18:13:47.266  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  secondary type: null
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  wps: 0
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  grpcapab: 0
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  devcapab: 0
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  status: 3
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  wfdInfo: null
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  groupownerAddress: null
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  GOdeviceName: null
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  interfaceAddress: 
09-12 18:13:47.266  1014  1046 D WifiDisplayController:  SConnectInfo : null
,09-12 18:13:47.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:13:47.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 18:13:47.266  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:47.266  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:47.276  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:47.276  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 18:13:47.276  6444  6444 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:47.276  6459  6459 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:47.286  1014  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 18:13:47.286  1014  1125 D WifiP2pService: InactiveState
,09-12 18:13:47.286  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-12 18:13:47.286  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:13:47.286  6794  6794 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-12 18:13:47.286  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
09-12 18:13:47.286  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:13:47.926  1014  1138 I ActivityManager: Killing 5767:com.samsung.android.sm/1000 (adj 15): empty #31
,09-12 18:13:47.926  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:13:47.936  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 18:13:47.936  1014  1027 D SecContentProvider2: mCursor = null
,09-12 18:13:47.936  1014  1027 D WifiService: setWifiEnabled: false pid=6205, uid=10155
,09-12 18:13:47.936  1014  1027 D SettingsProvider: name = wifi_on
,09-12 18:13:47.946  1014  1125 D WifiP2pService: InactiveState{ what=131204 }
,09-12 18:13:47.946  1014  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-12 18:13:47.946  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 18:13:47.946  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:47.946  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 18:13:47.946  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:13:47.956  1014  1014 D RttService: SCAN_AVAILABLE : 1
,09-12 18:13:47.956  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 18:13:47.956  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:13:47.956  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:47.956  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:47.956  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:13:47.956  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:13:47.956  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:13:47.956  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 18:13:47.956  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 18:13:47.956  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:13:47.966  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:47.966  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-12 18:13:47.966  1014  1125 D WifiP2pService: P2pDisablingState
09-12 18:13:47.966  1014  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 18:13:47.966  1014  1125 D WifiP2pService: p2p socket connection lost
09-12 18:13:47.966  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.966  1014  1125 D WifiP2pService: P2pDisabledState
,09-12 18:13:47.966  1014  1046 D WifiDisplayController: disconnect
09-12 18:13:47.966  1014  1046 D WifiDisplayController: updateConnection
09-12 18:13:47.966  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:13:47.966  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:47.966   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:13:47.966  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:47.966  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:47.966  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:13:47.966  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:47.966  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 18:13:47.966  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:13:47.966  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:13:47.966  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:13:47.976  6794  6794 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:13:47.976  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:13:47.976  1014  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:13:47.976  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 18:13:47.976  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 18:13:47.986  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:13:47.986  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 18:13:47.996  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.996  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.996  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:47.996  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:47.996  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:47.996  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 18:13:47.996  6444  6444 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:48.006  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.006  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:48.006  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.006  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.006  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.006  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.006  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:48.006  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 18:13:48.006  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:48.006  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:48.006  1177  1177 D HotspotTile: onReceive : 0, 0
,09-12 18:13:48.006  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:13:48.006  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:48.006  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:48.006  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.006  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:48.016  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:48.016  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 18:13:48.016  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:48.016  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:48.016  6459  6459 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:48.026  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:13:48.026  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:13:48.026  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:48.026  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:13:48.026  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.026  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:48.026  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.036  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:48.036  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:13:48.036  6444  6444 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:13:48.036  6459  6459 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:13:48.046  1014  1555 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:48.046  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.046  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:48.046  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.046  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.046  3742  3742 I Hs20UtilService: Starting #14
,09-12 18:13:48.056  3742  3757 I Hs20UtilService: Message received 5007
,09-12 18:13:48.056  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:13:48.056  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 18:13:48.056  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:13:48.056  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:13:48.056  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:13:48.056  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:13:48.056  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:13:48.056  1014  1561 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:48.066  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.066  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:48.066  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:48.066  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.066  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:48.066  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:48.066  3742  3742 I Hs20UtilService: Starting #15
,09-12 18:13:48.066  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:48.066  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-12 18:13:48.066  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:13:48.096  6794  6794 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:48.196  6794  6794 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
09-12 18:13:48.196  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:13:48.196  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:13:48.196  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:13:48.196  6794  6794 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
,09-12 18:13:48.196  6794  6794 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 18:13:48.416  6794  6794 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:13:48.476  6794  6794 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-12 18:13:48.486  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 18:13:48.486  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:13:48.486  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:13:48.586  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-12 18:13:48.586  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 18:13:48.586  1014  1126 E WifiConfigStore: setLastSelectedConfiguration -1
09-12 18:13:48.586  6419  6419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-12 18:13:48.586  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:13:48.586  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 18:13:48.586  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.586  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.586  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:13:48.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:13:48.596  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:13:48.596  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-12 18:13:48.596  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 18:13:48.596  1904  2108 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-12 18:13:48.596  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,09-12 18:13:48.606  1177  1177 D HotspotTile: onReceive : 1, 0
,09-12 18:13:48.606  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.606  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:48.606  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-12 18:13:48.616  1014  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:13:48.616  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:13:48.616  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:48.616  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:48.616  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:13:48.616  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 18:13:48.626  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:13:48.626  3742  3742 I Hs20UtilService: Starting #16
,09-12 18:13:48.626  3742  3757 I Hs20UtilService: Message received 5011
09-12 18:13:48.626  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:13:48.626  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:13:49.336  1014  1043 D Tethering: interfaceRemoved wlan0
09-12 18:13:49.336  1014  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 18:13:49.566  1014  1043 D Tethering: interfaceRemoved p2p0
,09-12 18:13:49.566  1014  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 18:13:49.796   288   288 E SMD     : DCD OFF
,09-12 18:13:50.026  1014  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.026  1014  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:50.026  1014  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.036  1014  1138 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-12 18:13:50.036  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-12 18:13:50.036  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:50.036  1014  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.036  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.036  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-12 18:13:50.036  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-12 18:13:50.046  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.046  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.046  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 18:13:50.046  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.046  1014  1326 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.046  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.056  6626  6677 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 18:13:50.056  1014  1559 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:50.056  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 18:13:50.056  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:50.056  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.056  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.066  1014  3308 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:50.066  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-12 18:13:50.066  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:50.066  1014  3308 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.066  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-12 18:13:50.066  1014  1492 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 18:13:50.066  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
09-12 18:13:50.066  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:50.066  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.066  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.086  1014  1312 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 18:13:50.086  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-12 18:13:50.086  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:50.086  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.086  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.106  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:50.106  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.106  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:50.106  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-12 18:13:50.116  1904  1904 D WearableService: callingUid 10012, callindPid: 1904
,09-12 18:13:50.126  1014  1485 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 18:13:50.126  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 18:13:50.126  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:50.136  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:50.136  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 18:13:50.146  6525  6807 I MusicLeanback: Conditions not met for autocaching.
,09-12 18:13:50.146  6525  6807 I MusicLeanback: Stop autocaching.
,09-12 18:13:50.186  6525  6525 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 18:13:50.186  6525  6813 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 18:13:50.316  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 18:13:50.956  6205  6257 D BluetoothAdapter: enable()
,09-12 18:13:50.956  1014  1492 W ActivityManager: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:13:50.956  1014  1492 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 18:13:50.956  1014  1492 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:13:50.956  1014  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:50.956  1014  1492 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:50.956  1014  1492 D SettingsProvider: name = bluetooth_on
,09-12 18:13:50.966  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:50.966  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:50.966  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-12 18:13:50.966  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 18:13:51.026  6397  6397 D BluetoothAdapterState: make
,09-12 18:13:51.026  6397  6397 I bluedroid: init
,09-12 18:13:51.036  6397  6815 I BluetoothAdapterState: Entering OffState,
,09-12 18:13:51.036  6397  6397 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:13:51.036  6397  6397 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 18:13:51.036  6397  6397 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 18:13:51.036  6397  6397 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 18:13:51.036  6397  6397 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-12 18:13:51.036  6397  6397 I bluedroid: get_profile_interface socket
09-12 18:13:51.036  6397  6397 I bluedroid: get_profile_interface map_client
,09-12 18:13:51.046  6397  6818 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-12 18:13:51.046  6397  6397 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-12 18:13:51.046  6397  6818 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 18:13:51.046  6397  6818 E BluetoothServiceJni: populateRssiValuesNative
09-12 18:13:51.046  6397  6818 I bluedroid: getModelRssiValues
09-12 18:13:51.046  6397  6818 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 18:13:51.046  6397  6818 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:13:51.046  1014  1014 D SettingsProvider: name = bluetooth_name
,09-12 18:13:51.046  6397  6818 D BluetoothAdapterProperties: Name is: A5-1
,09-12 18:13:51.056  6397  6397 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.056  1014  1555 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:51.056  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.056  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.056  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.056  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.056  6397  6405 I bluedroid: config_hci_snoop_log
,09-12 18:13:51.056  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 18:13:51.056  1014  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-12 18:13:51.056  1014  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 18:13:51.056  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 18:13:51.056  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:13:51.066  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:51.066  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:13:51.066  6397  6397 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-12 18:13:51.066  1014  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 18:13:51.076  6397  6815 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 18:13:51.076  6397  6815 D BluetoothAdapterProperties: Setting state to 11
,09-12 18:13:51.076  6397  6815 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 18:13:51.076  6397  6815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:51.076  6397  6815 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 18:13:51.076  6397  6815 D BluetoothAdapterService: Autoconnection is available 
,09-12 18:13:51.076  6397  6815 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 18:13:51.076  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.076  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-12 18:13:51.076  6397  6815 D BluetoothSecureManager: getInstant: null
09-12 18:13:51.076  6397  6815 D BluetoothSecureManager: calling getMethod for getService
09-12 18:13:51.076  6397  6815 D BluetoothSecureManager: calling getService
,09-12 18:13:51.076  6397  6815 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2b3712dc
09-12 18:13:51.076  1014  1027 D BluetoothSecureManagerService: isSecureModeEnabled
09-12 18:13:51.076  1014  1027 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-12 18:13:51.076  6397  6815 D BtConfig.SecureMode: isSecureModeOn:false
09-12 18:13:51.076  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:51.086  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 18:13:51.086  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 18:13:51.086  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:51.086  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.086  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:13:51.096  1787  1787 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:13:51.096  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:51.096  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:13:51.096  6397  6815 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 18:13:51.096  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:51.096  6397  6815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.096  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 18:13:51.096  6397  6815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.096  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 18:13:51.096  6397  6815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.096  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 18:13:51.096  6397  6815 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 18:13:51.096  1014  3307 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:51.096  1014  1559 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 18:13:51.096  6397  6815 D BluetoothBondStateMachine: make
09-12 18:13:51.096  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:51.096  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:51.106  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.106  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:51.106  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.106  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:13:51.106  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 18:13:51.106  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.106  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:51.106  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:51.106  6397  6819 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 18:13:51.106  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 18:13:51.106  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 18:13:51.106  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 18:13:51.106  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.106  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.106  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:51.106  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.116  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.116  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.116  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.116  6397  6397 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 18:13:51.116  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:13:51.116  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:51.116  6397  6397 D BtGatt.GattService: Received start request. Starting profile...
09-12 18:13:51.116  6397  6397 D BtGatt.GattService: start()
09-12 18:13:51.116  6397  6397 D BtGatt.GattService: start()
09-12 18:13:51.116  6397  6397 I bluedroid: get_profile_interface gatt
,09-12 18:13:51.116  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
09-12 18:13:51.116  6397  6397 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:13:51.116  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:51.116  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 18:13:51.116  1014  3304 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.116  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.126  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.126  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:51.126  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.126  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:51.126  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:51.126  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:51.136  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.136  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.136  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.136  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.136  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.136  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 18:13:51.136  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:51.136  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:51.136  6397  6397 D BtGatt.GattService: mStartError = false
,09-12 18:13:51.136  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.146  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.146  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.146  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.146  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.146  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.146  6397  6397 D HeadsetService: Received start request. Starting profile...
09-12 18:13:51.146  6397  6397 D HeadsetService: start()
,09-12 18:13:51.146  6397  6397 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 18:13:51.146  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 18:13:51.146  6397  6397 D HeadsetStateMachine: make
,09-12 18:13:51.146  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:13:51.146  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:13:51.146  1014  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.146  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.146  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.146  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.146  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.156  6397  6397 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 18:13:51.156  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService,
09-12 18:13:51.156  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:51.156  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:13:51.156  1014  3305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.156  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.166  1014  3305 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.166  1014  3305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.166  1014  3305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.166  1014  3304 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 18:13:51.166  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.166  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.166  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.166  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:13:51.166  1014  3308 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-12 18:13:51.166  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.166  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.166  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.166  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:51.166  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:51.166  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.166  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:13:51.176  6397  6397 I bluedroid: get_profile_interface handsfree
09-12 18:13:51.176  1014  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.176  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.176  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.176  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.176  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.176  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 18:13:51.176  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:51.176  6397  6815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:13:51.176  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.176  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.176  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.176  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.176  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:51.186  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.186  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.186  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:51.186  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:51.186  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:13:51.186  6397  6815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 18:13:51.196  6397  6397 I DualScoManager: Instantiating Dual Sco Manager
09-12 18:13:51.196  6397  6397 I DualScoManager: Set HeadsetServiceHelper
,09-12 18:13:51.196  6397  6397 D BluetoothAtMessage: createCMTIContentObservers
,09-12 18:13:51.196  1014  1217 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 18:13:51.196  1014  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:13:51.196  1014  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:13:51.196  1014  1217 D SettingsProvider: selectionArgs: false
09-12 18:13:51.196  1014  1217 D SettingsProvider: selectionArgs: 1002
09-12 18:13:51.196  1014  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:13:51.196  1014  1217 D SettingsProvider: ret = -1
,09-12 18:13:51.196  6397  6823 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 18:13:51.196  6397  6397 D HeadsetService: mStartError = false
09-12 18:13:51.196  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.206  6397  6397 D A2dpService: Received start request. Starting profile...
,09-12 18:13:51.206  6397  6397 D A2dpService: start()
,09-12 18:13:51.206  6397  6397 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 18:13:51.206  6397  6397 I bluedroid: get_profile_interface avrcp
,09-12 18:13:51.206  6397  6823 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-12 18:13:51.206  6397  6823 D HeadsetStateMachine: map size, before remove : 0
,09-12 18:13:51.206  6397  6823 D HeadsetStateMachine: map size, after remove: 0
,09-12 18:13:51.216  6397  6397 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:13:51.226  6397  6397 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 18:13:51.236  6397  6829 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 18:13:51.236  6397  6397 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 18:13:51.236  6397  6397 D A2dpStateMachine: make
,09-12 18:13:51.236  6397  6397 I bluedroid: get_profile_interface a2dp
,09-12 18:13:51.236  6397  6831 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-12 18:13:51.236  6397  6397 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 18:13:51.236  6397  6397 D A2dpService: mStartError = false
,09-12 18:13:51.236  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.236  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-12 18:13:51.236  6397  6830 D A2dpStateMachine: Enter Disconnected: -2
,09-12 18:13:51.236  6397  6397 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:13:51.246  6397  6397 D HidService: Received start request. Starting profile...,
09-12 18:13:51.246  6397  6397 D HidService: start()
09-12 18:13:51.246  6397  6397 I bluedroid: get_profile_interface hidhost
09-12 18:13:51.246  6397  6397 D HidService: setHidService(): set to: null
09-12 18:13:51.246  6397  6397 D HidService: mStartError = false
09-12 18:13:51.246  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
09-12 18:13:51.246  6397  6397 I BluetoothHealthServiceJni: classInitNative: succeeds,
,09-12 18:13:51.246  6397  6397 D HealthService: Received start request. Starting profile...
09-12 18:13:51.246  6397  6397 D HealthService: start()
,09-12 18:13:51.246  6397  6397 I bluedroid: get_profile_interface health
,09-12 18:13:51.246  6397  6397 D HealthService: mStartError = false
09-12 18:13:51.246  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.246  6397  6397 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:13:51.246  6397  6397 D PanService: Received start request. Starting profile...
09-12 18:13:51.246  6397  6397 D PanService: start()
09-12 18:13:51.246  6397  6397 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:13:51.246  6397  6397 I bluedroid: get_profile_interface pan
,09-12 18:13:51.256  6397  6397 D PanService: mStartError = false
09-12 18:13:51.256  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.256  6397  6397 D HeadsetStateMachine: Try to query the phonestate on bind,
09-12 18:13:51.256  1424  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 18:13:51.256  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-12 18:13:51.256  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 18:13:51.256  1424  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 18:13:51.256  6397  6397 D HeadsetStateMachine: Proxy object connected
,09-12 18:13:51.256  6397  6397 D BluetoothMapService: Received start request. Starting profile...
09-12 18:13:51.256  6397  6397 D BluetoothMapService: start()
,09-12 18:13:51.266  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:51.266  6397  6829 D BluetoothMediaBrowser: no now playing list
09-12 18:13:51.266  6397  6829 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 18:13:51.266  6397  6397 D BluetoothMapService: mStartError = false
09-12 18:13:51.266  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:51.266  6397  6397 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 18:13:51.266  6397  6823 D HeadsetStateMachine: Disconnected process message: 11
,09-12 18:13:51.266  6397  6397 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-12 18:13:51.266  6397  6397 D SapService: Received start request. Starting profile...
09-12 18:13:51.266  6397  6397 D SapService: start()
09-12 18:13:51.266  6397  6397 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 18:13:51.266  6397  6397 I bluedroid: get_profile_interface sap
09-12 18:13:51.266  6397  6397 D SapService: mStartError = false
09-12 18:13:51.266  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
09-12 18:13:51.266  6397  6397 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-12 18:13:51.266  6397  6397 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-12 18:13:51.266  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 18:13:51.266  6397  6823 D HeadsetStateMachine: Disconnected process message: 18
09-12 18:13:51.266  6397  6397 D BluetoothA2dp: Proxy object connected
09-12 18:13:51.266  6397  6397 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-12 18:13:51.266  6397  6397 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 18:13:51.266  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 18:13:51.266  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 18:13:51.266  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 18:13:51.266  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-12 18:13:51.276  6397  6823 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:51.276  6397  6823 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-12 18:13:51.276  6397  6823 D HeadsetStateMachine: Disconnected process message: 11
09-12 18:13:51.276  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:13:51.296  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 18:13:51.296  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 18:13:51.306  6397  6815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 18:13:51.306  6397  6815 I bluedroid: enable
,09-12 18:13:51.306  6397  6815 I bt_hci_bdroid: init
,09-12 18:13:51.306  6397  6836 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 18:13:51.306  6397  6815 I bt_vendor: bt-vendor : init
09-12 18:13:51.306  6397  6815 I bt_vendor: bt-vendor : get_bt_soc_type
,09-12 18:13:51.306  6397  6815 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 18:13:51.306  6397  6815 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,09-12 18:13:51.306  6397  6815 D bt_userial_mct: userial_init
09-12 18:13:51.306  6397  6815 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 18:13:51.306  6397  6815 I bt_vendor: Starting hciattach daemon
,09-12 18:13:51.306  6397  6815 I bt_vendor: try to set false
,09-12 18:13:51.306  6397  6815 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-12 18:13:51.306  6397  6815 I bt_vendor: Starting hciattach daemon
09-12 18:13:51.306  6397  6815 I bt_vendor: try to set true
,09-12 18:13:51.326  6840  6840 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 18:13:51.376  6846  6846 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-12 18:13:51.386  6847  6847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 18:13:51.396  6849  6849 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 18:13:51.406  6850  6850 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 18:13:51.416  6851  6851 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 18:13:51.426  6852  6852 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 18:13:51.666  6855  6855 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 18:13:51.676  6856  6856 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 18:13:51.726  6397  6815 I bt_vendor: bluetooth satus is on,
09-12 18:13:51.726  6397  6838 D bt_userial_mct: userial_open(port:0)
09-12 18:13:51.726  6397  6838 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 18:13:51.726  6397  6838 I bt_vendor: Done intiailizing UART,
,09-12 18:13:51.726  6397  6838 I bt_vendor: Done intiailizing UART,
09-12 18:13:51.726  6397  6838 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 18:13:51.726  6397  6838 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-12 18:13:51.726  6397  6858 D bt_userial_mct: Entering userial_read_thread(),
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_HCI,
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_AVDT,
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_BNEP,
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_SAP
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_SMP,
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 18:13:51.726  6397  6836 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-12 18:13:51.826  6397  6836 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 18:13:51.836  6397  6836 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f706e9 
,09-12 18:13:51.836  6397  6836 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f706e9 
,09-12 18:13:51.856  6397  6818 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 18:13:51.856  6397  6818 E bt-btif : Calling BTA_HhEnable
,09-12 18:13:51.856  6397  6818 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 18:13:51.866  6397  6818 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 18:13:51.866  6397  6818 E BluetoothServiceJni: populateRssiValuesNative
,09-12 18:13:51.866  6397  6818 I bluedroid: getModelRssiValues
09-12 18:13:51.866  6397  6818 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 18:13:51.866  6397  6818 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:13:51.866  1014  1014 D SettingsProvider: name = bluetooth_name
,09-12 18:13:51.866  6397  6818 D BluetoothAdapterProperties: Name is: A5-1
,09-12 18:13:51.876  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.876  6397  6818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:51.876  6397  6818 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:13:51.876  6397  6818 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:13:51.876  6397  6818 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-12 18:13:51.876  6397  6818 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-12 18:13:51.876  6397  6818 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-12 18:13:51.876  6397  6818 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 18:13:51.876  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:51.876  6397  6818 E bt-btif : btif_sock_init: !vhci_init
09-12 18:13:51.876  6397  6818 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-12 18:13:51.876  6397  6818 D IOP_DB_BT: db_open: db_open : handle 3028193296l, read 13894 bytes onto local cache
09-12 18:13:51.876  6397  6818 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-12 18:13:51.876  6397  6818 D IOP_DB_BT: db_query: result 1
,09-12 18:13:51.876  6397  6818 I         : iop_db_open: iop_db_open status 0
,09-12 18:13:51.876  6397  6858 E bt_mct  : hci lib postload completed
,09-12 18:13:51.886  6397  6818 D bte_conf: Device ID record 1 : primary
,09-12 18:13:51.886  6397  6818 D bte_conf:   vendorId            = 0075
,09-12 18:13:51.886  6397  6818 D bte_conf:   vendorIdSource      = 0001
09-12 18:13:51.886  6397  6818 D bte_conf:   product             = 0100
,09-12 18:13:51.886  6397  6818 D bte_conf:   version             = 0200
09-12 18:13:51.886  6397  6818 D bte_conf:   clientExecutableURL = 
,09-12 18:13:51.886  6397  6818 D bte_conf:   serviceDescription  = 
09-12 18:13:51.886  6397  6818 D bte_conf:   documentationURL    = 
,09-12 18:13:51.886  6397  6818 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 18:13:51.896  6397  6818 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:13:51.896  6397  6815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 18:13:51.896  6397  6815 D BluetoothAdapterProperties: ScanMode =  20
,09-12 18:13:51.896  6397  6815 D BluetoothAdapterProperties: State =  11
,09-12 18:13:51.896  1014  1312 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 18:13:51.896  6397  6815 D BluetoothAdapterProperties: Setting state to 12
09-12 18:13:51.896  6397  6815 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:13:51.906  6397  6818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:51.906  6397  6818 D BluetoothAdapterProperties: Scan Mode:21
09-12 18:13:51.906  6397  6818 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:13:51.906  1014  3304 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-12 18:13:51.906  1014  3304 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 18:13:51.906  1014  3304 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:13:51.906  1014  3304 D SettingsProvider: selectionArgs: false
09-12 18:13:51.906  1014  3304 D SettingsProvider: selectionArgs: 1002
,09-12 18:13:51.906  1014  3304 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:13:51.906  1014  3304 D SettingsProvider: ret = -1
,09-12 18:13:51.906  6397  6815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-12 18:13:51.906  6397  6815 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 18:13:51.916  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:51.916  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.916  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.916  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.916  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.916  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:51.916  6397  6815 D BluetoothAdapterService: Autoconnection is available 
,09-12 18:13:51.916  1014  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 18:13:51.916  6397  6815 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 18:13:51.916  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:51.916  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.926  6397  6815 D BluetoothAdapterService: starting service from this receiver
,09-12 18:13:51.926  1014  1014 D BluetoothA2dp: Proxy object connected
09-12 18:13:51.926  1014  3308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:51.926  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.926  1904  1918 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:51.926  1904  1918 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.936  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:51.936  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.936  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:51.936  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:51.936  6397  6815 I BluetoothAdapterState: Entering On State from state = 11
,09-12 18:13:51.936  1299  1308 D BluetoothPan: Binding service...
,09-12 18:13:51.946  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 18:13:51.946  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.946  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:51.946  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.946  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.946  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.946  1177  1642 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:51.946  1177  1642 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.946  1014  1045 D BluetoothPan: Binding service...
,09-12 18:13:51.956  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 18:13:51.956  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.956  6397  6397 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 18:13:51.956  1299  1311 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:51.956  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:51.956  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 18:13:51.956  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.956  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.956  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.956  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.956  1424  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.956  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.956  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.956  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:51.956  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.956  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.956  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.966  1424  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.966  1299  1308 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:51.966  1299  1308 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.966  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.966  1437  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.966  1450  1785 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.966  1450  1785 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.966  6397  6405 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:51.966  1299  1311 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:13:51.966  6397  6397 I BluetoothPbapService: Handler(): got msg=1
,09-12 18:13:51.966  1014  1555 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:13:51.966  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 18:13:51.976  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 18:13:51.976  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.976  1299  1299 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:13:51.976  1299  1299 D PanProfile: Bluetooth service connected
,09-12 18:13:51.976  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.976  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.976  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.976  1014  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 18:13:51.976  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.976  1014  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:13:51.976  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.976  6363  6379 D BluetoothAdapter: onBluetoothStateChange: up=true,
09-12 18:13:51.976  6363  6379 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:51.976  1299  1308 D Bluetoothsap: onBluetoothStateChange: up=true
,09-12 18:13:51.976  1299  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
09-12 18:13:51.976  1299  1308 D Bluetoothsap: Binding service...
,09-12 18:13:51.976  6397  6863 V BluetoothPbapService: PBAP Service initSocket try: 0
09-12 18:13:51.986  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 18:13:51.986  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:51.986  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.986  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.986  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.986  1299  1308 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 18:13:51.986  1299  1299 D BluetoothPbap: Proxy object connected
,09-12 18:13:51.986  1299  1299 D PbapServerProfile: Bluetooth service connected
,09-12 18:13:51.986  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 18:13:51.986  1299  1308 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.986  1299  1299 D SapProfile: Bluetooth service connected
09-12 18:13:51.986  1299  1299 D Bluetoothsap: getConnectedDevices()
,09-12 18:13:51.986  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.986  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.996  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.996  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.996  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.996  6397  6863 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 18:13:51.996  6397  6863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:51.996  1299  1308 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.996  1424  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:51.996  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:13:51.996  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:51.996  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:51.996  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:51.996  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:51.996  1424  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:51.996  6397  6863 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-12 18:13:51.996  6397  6863 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:51.996  6397  6863 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:51.996  6397  6863 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e20f40
09-12 18:13:51.996  6397  6863 D BluetoothSocket: channel: 19
09-12 18:13:51.996  6397  6863 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 18:13:51.996  1424  1443 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.996  1424  1443 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.996  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.996  1014  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.996  1299  1299 D BluetoothMap: Proxy object connected
09-12 18:13:51.996  1299  1299 D MapProfile: Bluetooth service connected
,09-12 18:13:51.996  2906  2920 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:13:51.996  2906  2920 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:51.996  2906  2920 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:51.996  1299  1299 D BluetoothMap: getConnectedDevices()
,09-12 18:13:52.006  2906  2920 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:52.006  1014  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:52.006  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.006  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:52.006  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.006  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.006  6397  6405 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:52.006  6397  6405 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:13:52.006  1299  1299 D HeadsetProfile: Bluetooth service connected
,09-12 18:13:52.006  2906  2906 D BluetoothA2dp: Proxy object connected
09-12 18:13:52.006  1299  6864 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:13:52.006  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 18:13:52.006  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.006  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.016  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.016  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.016  1424  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:52.016  1299  1299 D BluetoothInputDevice: Proxy object connected
,09-12 18:13:52.016  1299  1299 D HidProfile: Bluetooth service connected
09-12 18:13:52.016  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:52.016  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:52.016  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.016  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:52.016  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.016  1424  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:52.026  2906  2920 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:52.026  1014  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:52.026  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:52.026  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.026  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.026  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.026  2906  2920 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:52.026  1450  1461 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:52.026  1014  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:13:52.026  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:13:52.036  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.036  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.036  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.036  1450  1461 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:13:52.036  6205  6213 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:13:52.036  6205  6213 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:13:52.036  1299  6862 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:13:52.036  1299  6862 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:13:52.046  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:13:52.046  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.046  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:52.046  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.046  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.046  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 18:13:52.046  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:13:52.046  1299  1299 D BluetoothA2dp: Proxy object connected
,09-12 18:13:52.046  1299  1299 D A2dpProfile: Bluetooth service connected
,09-12 18:13:52.046  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:52.046  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-12 18:13:52.046  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 18:13:52.046  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:52.056  1424  1424 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@29c35d2f, true
,09-12 18:13:52.056  1787  1787 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:52.056  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 18:13:52.056  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:52.056  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-12 18:13:52.056  1424  1424 D BluetoothHeadset: registerMessageListener
,09-12 18:13:52.056  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null,
,09-12 18:13:52.056  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:52.066  6397  6406 D HeadsetService: registerMessageListener
,09-12 18:13:52.066  1014  3304 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:52.066  6397  6406 D HeadsetService: registerMessageListener
09-12 18:13:52.066  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-12 18:13:52.066  6397  6823 D HeadsetStateMachine: Disconnected process message: 70
09-12 18:13:52.066  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:52.066  6397  6823 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@37662e79
09-12 18:13:52.066  1014  1326 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 18:13:52.066  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:13:52.066  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:52.066  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:52.066  1014  3304 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:52.066  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:52.066  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:52.066  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 18:13:52.066  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 18:13:52.076  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:52.076  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:52.076  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 18:13:52.076  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-12 18:13:52.076  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 18:13:52.076  1299  1299 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-12 18:13:52.076  1299  1299 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 18:13:52.076  1299  1299 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 18:13:52.076  1299  1299 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 18:13:52.076  6397  6868 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 18:13:52.076  6397  6823 D HeadsetStateMachine: Disconnected process message: 9
,09-12 18:13:52.076  6397  6823 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 18:13:52.086  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:52.086  6397  6868 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 18:13:52.086  6397  6868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 18:13:52.086  1014  1492 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:52.086  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.086  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.096  6397  6868 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-12 18:13:52.096  6397  6868 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:52.096  6397  6868 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:52.096  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.096  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-12 18:13:52.096  6397  6868 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2340d7be
09-12 18:13:52.096   283   681 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 18:13:52.096   283   681 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 18:13:52.096   283   681 V voice   : voice_set_parameters: exit with code(-2)
09-12 18:13:52.096   283   681 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 18:13:52.096   283   681 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 18:13:52.096   283   681 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 18:13:52.096   283   681 V audio_hw_primary: adev_set_parameters: exit
09-12 18:13:52.096  6397  6868 D BluetoothSocket: channel: 5
09-12 18:13:52.096  6397  6823 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 18:13:52.106  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:52.106  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:52.106  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:52.106  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 18:13:52.116  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:52.116  6397  6397 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:13:52.126  1014  1555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:52.126  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.126  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.126  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:52.126  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:52.136  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:52.136  1014  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:52.136  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:52.146  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.146  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:52.146  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:52.146  1904  6874 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 18:13:52.146  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:13:52.146  1014  3305 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:13:52.166  6397  6878 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:13:52.166  6397  6878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:13:52.176  6397  6878 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-12 18:13:52.176  6397  6878 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:13:52.176  6397  6878 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:13:52.176  6397  6878 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b2eb1ca
,09-12 18:13:52.176  6397  6878 D BluetoothSocket: channel: 12
09-12 18:13:52.176  6397  6878 I BtOppRfcommListener: Accept thread started.
,09-12 18:13:52.266  1014  1326 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:13:52.266  1014  1326 D BatteryService: level:81, scale:100, status:2, health:2, present:true, voltage: 4063, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 18:13:52.266  1014  1326 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 18:13:52.266  1014  1326 D BatteryService: stay LED for charging
,09-12 18:13:52.266  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:13:52.266  1014  1014 I MotionRecognitionService: Plugged
,09-12 18:13:52.266  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:13:52.276  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 18:13:52.276  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 18:13:52.276  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 81
,09-12 18:13:52.276  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:13:52.286  6397  6397 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:13:52.286  6397  6823 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:13:52.296  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:52.296  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:52.296  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:13:52.306  1014  1312 I art     : Explicit concurrent mark sweep GC freed 45126(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.611ms total 149.035ms
,09-12 18:13:52.306  1014  1312 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:52.306  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:52.306  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:52.306  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:52.316  1014  3307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:52.316  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:52.316  1014  3307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:52.316  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:52.326  1904  6874 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-12 18:13:52.566  1014  2780 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:13:52.796   288   288 E SMD     : DCD OFF,
,09-12 18:13:53.526  1014  2749 D SSRM:n  : SIOP:: AP = 350
,09-12 18:13:53.976  6205  6257 D BluetoothAdapter: disable()
,09-12 18:13:53.976  1014  3305 D SettingsProvider: name = bluetooth_on
,09-12 18:13:53.986  6397  6815 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 18:13:53.986  6397  6815 D BluetoothAdapterProperties: Setting state to 13
09-12 18:13:53.986  6397  6815 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 18:13:53.986  6397  6815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:53.986  6397  6815 D BluetoothAdapterService: updateAdapterState state is 13
09-12 18:13:53.986  1014  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:53.986  1014  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:13:53.986  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:53.986  1014  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:53.986  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:53.996  6397  6815 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:53.996  6397  6815 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 18:13:53.996  6397  6815 D BluetoothAdapterService: terminating service from this receiver
,09-12 18:13:53.996  6397  6397 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-12 18:13:53.996  6397  6397 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@9496f3b, channel: 19, state: LISTENING
09-12 18:13:53.996  1014  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:13:53.996  1014  1555 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:53.996  1014  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:53.996  1014  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:53.996  6397  6397 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@9496f3b, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e20f40, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16ca8658mSocket: android.net.LocalSocket@293a33b1 impl:android.net.LocalSocketImpl@356e2096 fd:FileDescriptor[75]
09-12 18:13:53.996  6397  6397 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@293a33b1 impl:android.net.LocalSocketImpl@356e2096 fd:FileDescriptor[75]
09-12 18:13:54.006  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:53.996  6397  6815 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 18:13:54.006  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
09-12 18:13:53.996  6397  6815 D BluetoothAdapterProperties: mDiscovering is false
09-12 18:13:53.996  1014  1138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 18:13:53.996  6397  6815 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 18:13:54.006  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:13:54.016  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 18:13:54.016  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:54.016  1177  1177 D BluetoothTile:  getBluetoothState : 13
,09-12 18:13:54.016  1787  1787 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:54.016  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:54.016  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.016  1014  3308 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:54.026  1014  1138 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:54.026  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:54.026  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:13:54.026  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:54.026  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:54.036  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:13:54.036  1014  3305 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:54.036  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.036  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:54.036  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:13:54.036  1014  3305 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:54.036  1014  3305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:54.036  6397  6818 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:13:54.036  6397  6818 D BluetoothAdapterProperties: Scan Mode:20
,09-12 18:13:54.036  1014  3305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:54.036  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:13:54.036  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:13:54.046  6205  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 18:13:54.046  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:13:54.046  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:54.046  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 18:13:54.046  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:54.046  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:54.046  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:54.046  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:54.046  6397  6815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-12 18:13:54.056  6397  6815 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-12 18:13:54.056  6397  6815 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-12 18:13:54.056  6397  6815 E bt-btif : cmd socket is not created
,09-12 18:13:54.056  6397  6878 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 18:13:54.056  6397  6815 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 18:13:54.056  1299  1299 D BluetoothPbap: Proxy object disconnected
,09-12 18:13:54.056  1299  1299 D PbapServerProfile: Bluetooth service disconnected
,09-12 18:13:54.056  6397  6836 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-12 18:13:54.056  6397  6836 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 18:13:54.056  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:54.056  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.056  6397  6836 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 18:13:54.056  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.066  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:54.066  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:54.076  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
09-12 18:13:54.076  6397  6397 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17d5c417, channel: 5, state: LISTENING
09-12 18:13:54.076  6397  6397 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17d5c417, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2340d7be, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@88db004mSocket: android.net.LocalSocket@370d59ed impl:android.net.LocalSocketImpl@3c63b022 fd:FileDescriptor[77]
09-12 18:13:54.076  6397  6397 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@370d59ed impl:android.net.LocalSocketImpl@3c63b022 fd:FileDescriptor[77]
,09-12 18:13:54.076  6397  6397 I BtOppRfcommListener: stopping Accept Thread
,09-12 18:13:54.076  6397  6397 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32688ab3, channel: 12, state: LISTENING
09-12 18:13:54.076  6397  6397 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32688ab3, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b2eb1ca, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a37c870mSocket: android.net.LocalSocket@f72a7e9 impl:android.net.LocalSocketImpl@a30ac6e fd:FileDescriptor[79]
09-12 18:13:54.076  6397  6397 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f72a7e9 impl:android.net.LocalSocketImpl@a30ac6e fd:FileDescriptor[79]
,09-12 18:13:54.076  6397  6878 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 18:13:54.076  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:54.076  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 18:13:54.086  6397  6397 V BluetoothOppManager: cleanUp...
,09-12 18:13:54.106  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:54.106  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:13:54.176  1014  1309 E Watchdog: !@Sync 4
,09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 18:13:54.256  6397  6836 W bt-btif : ag scb idx 1 not allocated
09-12 18:13:54.256  6397  6836 W bt-btif : ag scb idx 2 not allocated
09-12 18:13:54.256  6397  6836 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 18:13:54.256  6397  6858 I bt_userial_mct: exiting userial_read_thread
09-12 18:13:54.256  6397  6858 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 18:13:54.256  6397  6818 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 18:13:54.256  6397  6838 I bt_vendor: hw_epilog_process
,09-12 18:13:54.256  6397  6818 D bt_userial_mct: userial_close
,09-12 18:13:54.256  6397  6818 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 18:13:54.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:55.416  6397  6818 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 18:13:55.416  6397  6818 I bt_vendor: bluetooth satus is on
09-12 18:13:55.416  6397  6818 I bt_vendor: bt-vendor : resetting BT status
,09-12 18:13:55.416  6397  6818 I bt_vendor: Starting hciattach daemon
09-12 18:13:55.416  6397  6818 I bt_vendor: try to set false
,09-12 18:13:55.416  6397  6818 I bt_vendor: Starting hciattach daemon
,09-12 18:13:55.416  6397  6818 I bt_vendor: try to set false
,09-12 18:13:55.416  6397  6818 I bt_vendor: cleanup,
,09-12 18:13:55.416  6397  6836 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,09-12 18:13:55.416  6397  6818 I GKI_LINUX: GKI_exit_task 0 done
,09-12 18:13:55.416  6397  6818 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-12 18:13:55.426  6397  6815 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
09-12 18:13:55.426  6397  6815 D BtConfig.SecureMode: isSecureModeOn:false,
,09-12 18:13:55.426  6397  6815 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 18:13:55.426  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-12 18:13:55.426  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 18:13:55.426  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 18:13:55.426  1014  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:55.426  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.426  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.426  1014  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:55.426  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:55.426  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:13:55.426  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:13:55.426  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:13:55.436  6397  6397 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:13:55.436  1014  3304 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.436  6397  6397 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 18:13:55.436  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 18:13:55.436  6397  6397 D BtGatt.GattService: stop()
09-12 18:13:55.436  6397  6397 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 18:13:55.436  1014  3304 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:13:55.436  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.436  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-12 18:13:55.436  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 18:13:55.436  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:55.436  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.436  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:13:55.436  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 18:13:55.436  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.436  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.436  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.436  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:55.436  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-12 18:13:55.436  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:55.436  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:13:55.446  1014  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.446  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.446  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.446  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.446  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:13:55.446  6397  6397 D HeadsetService: Received stop request...Stopping profile...
,09-12 18:13:55.446  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 18:13:55.446  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:13:55.446  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:13:55.446  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.446  1014  3308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.446  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.446  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.446  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.446  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:55.446  1299  1299 D HeadsetProfile: Bluetooth service disconnected
,09-12 18:13:55.446  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 18:13:55.446  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 18:13:55.456  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:13:55.456  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:13:55.456  1014  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:13:55.456  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.456  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:55.456  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.456  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:55.456  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.456  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.456  6397  6815 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:55.456  1014  3304 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.456  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.456  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.456  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.456  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:55.456  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 18:13:55.456  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:55.456  6397  6815 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:13:55.456  1014  3305 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:13:55.456  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.466  1014  3305 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:55.466  1014  3305 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:13:55.466  1014  3305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:55.466  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:55.466  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:13:55.466  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:13:55.466  6397  6815 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:13:55.466  6397  6815 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:13:55.466  6397  6815 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 18:13:55.466  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-12 18:13:55.466  6397  6397 D A2dpService: Received stop request...Stopping profile...
,09-12 18:13:55.466  6397  6830 D A2dpStateMachine: Exit Disconnected: -1
,09-12 18:13:55.476  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.476  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:55.476  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 18:13:55.476  6397  6397 D HidService: Received stop request...Stopping profile...
,09-12 18:13:55.476  1299  1299 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:55.476  6397  6397 D HidService: Stopping Bluetooth HidService
09-12 18:13:55.476  6397  6397 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 18:13:55.476  6397  6397 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 18:13:55.476  6397  6397 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 18:13:55.476  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
09-12 18:13:55.476  1299  1299 D A2dpProfile: Bluetooth service disconnected
,09-12 18:13:55.476  2906  2906 D BluetoothA2dp: Proxy object disconnected
,09-12 18:13:55.476  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 18:13:55.476  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:55.476  6397  6397 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 18:13:55.476  1299  1299 D BluetoothInputDevice: Proxy object disconnected
09-12 18:13:55.476  1299  1299 D HidProfile: Bluetooth service disconnected
09-12 18:13:55.476  6397  6397 D HealthService: Received stop request...Stopping profile...
09-12 18:13:55.476  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.486  6397  6397 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-12 18:13:55.486  6397  6397 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 18:13:55.486  6397  6397 D PanService: Received stop request...Stopping profile...
,09-12 18:13:55.486  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.486  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 18:13:55.486  6397  6397 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 18:13:55.496  1299  1299 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 18:13:55.496  1299  1299 D PanProfile: Bluetooth service disconnected
,09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
,09-12 18:13:55.496  6397  6397 D SapService: Received stop request...Stopping profile...
09-12 18:13:55.496  6397  6397 D SapService: Stopping Bluetooth SapService
09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5d46857
09-12 18:13:55.496  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 18:13:55.496  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 18:13:55.496  6397  6397 D BluetoothA2dp: Proxy object disconnected
09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-12 18:13:55.496  6397  6831 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 18:13:55.496  6397  6397 I GKI_LINUX: GKI_exit_task 2 done
09-12 18:13:55.496  6397  6397 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 18:13:55.496  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 18:13:55.496  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.496  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 18:13:55.496  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.496  6397  6397 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 18:13:55.496  1299  1299 D BluetoothMap: Proxy object disconnected
09-12 18:13:55.496  6397  6397 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 18:13:55.496  1299  1299 D MapProfile: Bluetooth service disconnected
09-12 18:13:55.496  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,09-12 18:13:55.496  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.496  6397  6397 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 18:13:55.496  6397  6397 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 18:13:55.496  6397  6397 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 18:13:55.496  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 18:13:55.496  1299  1299 D SapProfile: Bluetooth service disconnected
,09-12 18:13:55.506  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 18:13:55.506  6397  6397 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:13:55.506  6397  6397 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 18:13:55.506  6397  6397 E BluetoothAdapterService(97806423): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 18:13:55.506  6397  6397 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 18:13:55.506  6397  6397 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 18:13:55.506  6397  6815 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-12 18:13:55.506  6397  6815 D BluetoothAdapterProperties: Setting state to 10
,09-12 18:13:55.506  6397  6815 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-12 18:13:55.506  6397  6815 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:13:55.506  6397  6815 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 18:13:55.506  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:55.506  6397  6815 D BluetoothAdapterService: Autoconnection is available 
09-12 18:13:55.506  6397  6815 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 18:13:55.506  6397  6815 I BluetoothAdapterState: Entering OffState
09-12 18:13:55.506  1904  1918 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:55.506  1904  1918 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:55.506  1177  1978 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:55.506  1177  1978 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:55.506  1299  1311 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 18:13:55.506  1299  6864 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:55.506  1299  6864 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:55.506  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:55.506  1437  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:55.516  1450  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.516  1450  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 18:13:55.516  6397  6406 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:55.516  1299  6862 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 18:13:55.516  6363  6379 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.516  6363  6379 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.516  1299  1308 D Bluetoothsap: onBluetoothStateChange: up=false
,09-12 18:13:55.516  1299  1308 D Bluetoothsap: Unbinding service...
,09-12 18:13:55.516  1424  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.516  1424  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.516  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 18:13:55.516  1014  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.516  2906  2915 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.516  2906  2915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.516  2906  2920 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:55.526  6397  6824 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.526  6397  6824 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.526  1299  6864 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 18:13:55.526  6205  6213 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 18:13:55.526  6205  6213 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 18:13:55.526  6205  6213 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-12 18:13:55.526  6205  6213 D BluetoothLeAdvertiser: Exit stop advertising
09-12 18:13:55.526  6205  6213 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 18:13:55.526  6205  6213 D BluetoothLeScanner: Exiting stopAllScan
,09-12 18:13:55.526  1299  6862 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 18:13:55.526  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-12 18:13:55.536  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 18:13:55.546  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:55.546  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-12 18:13:55.546  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 18:13:55.546  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:55.546  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:13:55.546  1177  1721 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:55.546  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:55.546  1177  1177 D BluetoothTile:  getBluetoothState : 10
,09-12 18:13:55.546  1177  1721 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:55.556  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
09-12 18:13:55.556  1177  1177 D BluetoothAdapter: 517624438: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:55.556  1014  3305 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:55.556  1014  1559 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 18:13:55.556  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:13:55.556  1787  1787 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:13:55.556  1904  2108 D BluetoothAdapter: 137638572: getState() :  mService = null. Returning STATE_OFF
09-12 18:13:55.556  1904  2108 D BluetoothAdapter: 137638572: getState() :  mService = null. Returning STATE_OFF
,09-12 18:13:55.556  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:13:55.556  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:55.556  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:13:55.556  1014  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:13:55.556  6397  6818 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 18:13:55.556  6397  6397 I GKI_LINUX: GKI_exit_task 1 done
09-12 18:13:55.556  6397  6397 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-12 18:13:55.556  6397  6397 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 18:13:55.556  1014  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.566  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:13:55.566  1014  1485 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:13:55.566  1014  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:55.566  1014  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:55.566  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:13:55.566  6397  6397 I art     : System.exit called, status: 0
09-12 18:13:55.566  6397  6397 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 18:13:55.566  1014  1561 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 18:13:55.566  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.566  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:55.566  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:13:55.566  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 18:13:55.576  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:13:55.576  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:13:55.586  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:13:55.586  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 18:13:55.726  1014  1217 I ActivityManager: Process com.android.bluetooth (pid 6397)(adj 0) has died(62,1082)
,09-12 18:13:55.746  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:13:55.746  1014  3305 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:13:55.746  1014  3305 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 18:13:55.746  1014  3305 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:55.746  1014  3305 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:13:55.746  1014  3305 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:55.756  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:13:55.756  1904  6895 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 18:13:55.766  1014  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:13:55.766  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:13:55.766  1014  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:13:55.776  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:13:55.776  1904  6895 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-12 18:13:55.796   288   288 E SMD     : DCD OFF
,09-12 18:13:55.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:56.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:56.996  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 18:13:56.996  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:13:57.816   322   322 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 18:13:58.206  1014  1960 V SAMP_SPCM_test: CSC File load.. ,
,09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings,
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall,
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-12 18:13:58.216  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time,
,09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 18:13:58.256  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-12 18:13:58.266  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-12 18:13:58.276  1014  1960 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
,09-12 18:13:58.276  1014  1960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-12 18:13:58.276  1014  1960 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-12 18:13:58.276  1014  1960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,09-12 18:13:58.276  1014  1960 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction,
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 18:13:58.276  1014  1960 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-12 18:13:58.306  6898  6898 E Zygote  : MountEmulatedStorage()
,09-12 18:13:58.306  6898  6898 E Zygote  : v2
09-12 18:13:58.306  1014  1960 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6898 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 18:13:58.306  6898  6898 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:13:58.306  6898  6898 I libpersona: KNOX_SDCARD not a persona
,09-12 18:13:58.306  6898  6898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 18:13:58.306  6898  6898 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 18:13:58.316  6898  6898 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 18:13:58.326   309   309 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 722us total 28.240ms
,09-12 18:13:58.346  6898  6898 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:13:58.346  6898  6898 D ActivityThread: Added TimaKeyStore provider
,09-12 18:13:58.356   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 815us total 20.840ms
,09-12 18:13:58.366  6898  6898 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:13:58.376   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 753us total 20.686ms
,09-12 18:13:58.406  1014  1960 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-12 18:13:58.806   288   288 E SMD     : DCD OFF
,09-12 18:13:58.806   322   322 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 18:13:59.806   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-12 18:13:59.996  1014  1094 V AlarmManager: waitForAlarm result :8,
,09-12 18:13:59.996  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:59.996  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da2821a added. We now have 6 listener(s)
,09-12 18:13:59.996  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:59.996  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:13:59.996  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf1814b added. We now have 7 listener(s)
,09-12 18:13:59.996  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:13:59.996  6205  6257 I System.out: IsBluetoothEnabled
,09-12 18:13:59.996  6205  6257 D BluetoothAdapter: disable()
,09-12 18:13:59.996  1014  1326 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-12 18:14:00.006  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:00.006  6205  6257 D BluetoothAdapter: enable()
,09-12 18:14:00.006  1014  1138 W ActivityManager: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:14:00.006  1014  1138 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 18:14:00.006  1014  1138 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:14:00.006  1014  1138 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.006  1014  1138 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.006  1014  1138 D SettingsProvider: name = bluetooth_on
,09-12 18:14:00.016  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 18:14:00.016  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.026  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-12 18:14:00.026  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 18:14:00.026  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:00.026  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:00.026  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:00.026  1014  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:00.046  1014  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6917 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-12 18:14:00.046  6917  6917 E Zygote  : MountEmulatedStorage()
09-12 18:14:00.046  6917  6917 E Zygote  : v2
09-12 18:14:00.046  6917  6917 I libpersona: KNOX_SDCARD checking this for 1002,
09-12 18:14:00.046  6917  6917 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:00.046  6917  6917 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:14:00.046  6917  6917 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:14:00.056  6917  6917 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:00.076  6917  6917 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:00.076  6917  6917 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:00.096  6917  6917 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-12 18:14:00.096  6917  6917 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
,09-12 18:14:00.126  6917  6917 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-12 18:14:00.166  6917  6917 D BtSettings.ProfileConfig: Adding GattService
,09-12 18:14:00.166  6917  6917 D BtSettings.ProfileConfig: Adding HeadsetService
,09-12 18:14:00.166  6917  6917 D BtSettings.ProfileConfig: Adding A2dpService
,09-12 18:14:00.166  6917  6917 D BtSettings.ProfileConfig: Adding HidService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding HealthService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding PanService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding SapService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding SapClientService
,09-12 18:14:00.176  6917  6917 D BtSettings.ProfileConfig: Adding HidDevService
,09-12 18:14:00.176  6917  6917 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 18:14:00.176  1014  3305 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-12 18:14:00.176  1014  3305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.176  1014  3305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.186  1014  3305 D SettingsProvider: selectionArgs: false
09-12 18:14:00.186  1014  3305 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.186  1014  3305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:14:00.186  1014  3305 D SettingsProvider: ret = -1
,09-12 18:14:00.186  1014  1561 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-12 18:14:00.186  1014  1561 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.186  1014  1561 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.186  1014  1561 D SettingsProvider: selectionArgs: false
09-12 18:14:00.186  1014  1561 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.186  1014  1561 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:14:00.186  1014  1561 D SettingsProvider: ret = -1
,09-12 18:14:00.186  1014  3304 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
09-12 18:14:00.186  1014  3304 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.186  1014  3304 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.186  1014  3304 D SettingsProvider: selectionArgs: false
,09-12 18:14:00.186  1014  3304 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.186  1014  3304 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.186  1014  3304 D SettingsProvider: ret = -1
,09-12 18:14:00.186  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-12 18:14:00.186  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.186  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.186  1014  1492 D SettingsProvider: selectionArgs: false
09-12 18:14:00.186  1014  1492 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.186  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:14:00.186  1014  1492 D SettingsProvider: ret = -1
,09-12 18:14:00.196  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.196  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.196  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.196  1014  1027 D SettingsProvider: selectionArgs: false
09-12 18:14:00.196  1014  1027 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.196  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.196  1014  1027 D SettingsProvider: ret = -1
,09-12 18:14:00.196  1014  1555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-12 18:14:00.196  1014  1555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.196  1014  1555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.196  1014  1555 D SettingsProvider: selectionArgs: false
09-12 18:14:00.196  1014  1555 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.196  1014  1555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.196  1014  1555 D SettingsProvider: ret = -1
,09-12 18:14:00.196  1014  1312 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.196  1014  1312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.196  1014  1312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.196  1014  1312 D SettingsProvider: selectionArgs: false
,09-12 18:14:00.196  1014  1312 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.196  1014  1312 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:14:00.196  1014  1312 D SettingsProvider: ret = -1
,09-12 18:14:00.196  1014  3307 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-12 18:14:00.196  1014  3307 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.196  1014  3307 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.196  1014  3307 D SettingsProvider: selectionArgs: false
,09-12 18:14:00.196  1014  3307 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.196  1014  3307 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.196  1014  3307 D SettingsProvider: ret = -1
09-12 18:14:00.206  1014  3308 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.206  1014  3308 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.206  1014  3308 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.206  1014  3308 D SettingsProvider: selectionArgs: false
,09-12 18:14:00.206  1014  3308 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.206  1014  3308 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.206  1014  3308 D SettingsProvider: ret = -1
09-12 18:14:00.206  1014  1326 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.206  1014  1326 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.206  1014  1326 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.206  1014  1326 D SettingsProvider: selectionArgs: false,
09-12 18:14:00.206  1014  1326 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.206  1014  1326 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 18:14:00.206  1014  1326 D SettingsProvider: ret = -1
09-12 18:14:00.206  1014  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.206  1014  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.206  1014  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.206  1014  1217 D SettingsProvider: selectionArgs: false,
09-12 18:14:00.206  1014  1217 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.206  1014  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.206  1014  1217 D SettingsProvider: ret = -1
09-12 18:14:00.206  1014  1559 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-12 18:14:00.206  1014  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 18:14:00.206  1014  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:00.206  1014  1559 D SettingsProvider: selectionArgs: false
09-12 18:14:00.206  1014  1559 D SettingsProvider: selectionArgs: 1002
09-12 18:14:00.206  1014  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.206  1014  1559 D SettingsProvider: ret = -1
,09-12 18:14:00.216  6917  6917 D BluetoothAdapterState: make
,09-12 18:14:00.226  6917  6917 I bluedroid: init
,09-12 18:14:00.226  6917  6932 I BluetoothAdapterState: Entering OffState
,09-12 18:14:00.226  6917  6917 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 18:14:00.226  6917  6917 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 18:14:00.226  6917  6917 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 18:14:00.226  6917  6917 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 18:14:00.226  6917  6917 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-12 18:14:00.226  6917  6917 I bluedroid: get_profile_interface socket
09-12 18:14:00.226  6917  6917 I bluedroid: get_profile_interface map_client
,09-12 18:14:00.226  6917  6935 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-12 18:14:00.226  6917  6917 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-12 18:14:00.226  6917  6935 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 18:14:00.226  6917  6935 E BluetoothServiceJni: populateRssiValuesNative
09-12 18:14:00.226  6917  6935 I bluedroid: getModelRssiValues
09-12 18:14:00.226  6917  6935 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 18:14:00.226  6917  6935 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:14:00.236  6917  6935 D BluetoothAdapterProperties: Name is: A5-1
,09-12 18:14:00.236  1014  1014 D SettingsProvider: name = bluetooth_name
,09-12 18:14:00.236  6917  6917 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:00.236  1014  3308 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:00.236  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.236  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.236  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.236  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.246  6917  6926 I bluedroid: config_hci_snoop_log
,09-12 18:14:00.246  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 18:14:00.246  1014  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-12 18:14:00.246  1014  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 18:14:00.246  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-12 18:14:00.246  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:14:00.256  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.256  6917  6917 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-12 18:14:00.256  1014  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 18:14:00.256  1014  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 18:14:00.256  1014  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 18:14:00.256  6917  6932 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 18:14:00.256  6917  6932 D BluetoothAdapterProperties: Setting state to 11
,09-12 18:14:00.256  6917  6932 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 18:14:00.256  6917  6932 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:14:00.256  6917  6932 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 18:14:00.266  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:00.266  1014  1014 I InputMethodManagerService: [BT Setting State] State =11,
,09-12 18:14:00.266  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:14:00.276  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.276  6917  6932 D BluetoothAdapterService: Autoconnection is available 
09-12 18:14:00.276  6917  6932 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 18:14:00.276  1177  1177 D BluetoothTile:  getBluetoothState : 11
,09-12 18:14:00.276  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:00.276  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 18:14:00.276  6917  6932 D BluetoothSecureManager: getInstant: null
,09-12 18:14:00.276  6917  6932 D BluetoothSecureManager: calling getMethod for getService
09-12 18:14:00.276  6917  6932 D BluetoothSecureManager: calling getService
09-12 18:14:00.276  6917  6932 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@7e0b4f
,09-12 18:14:00.276  1014  1492 D BluetoothSecureManagerService: isSecureModeEnabled
09-12 18:14:00.276  1014  1492 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-12 18:14:00.276  6917  6932 D BtConfig.SecureMode: isSecureModeOn:false
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 18:14:00.276  6917  6932 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 18:14:00.276  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 18:14:00.286  1014  3304 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:14:00.286  6917  6932 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.286  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 18:14:00.286  6917  6932 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.286  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.286  1787  1787 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-12 18:14:00.286  6917  6932 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.286  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 18:14:00.286  6917  6932 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 18:14:00.296  1014  1559 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
09-12 18:14:00.296  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.296  6917  6932 D BluetoothBondStateMachine: make
,09-12 18:14:00.296  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 18:14:00.296  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:00.296  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 18:14:00.296  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:14:00.296  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 18:14:00.296  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 18:14:00.296  6917  6937 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 18:14:00.296  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.296  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.296  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:00.296  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:00.306  1014  3304 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.306  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.306  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.306  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:00.306  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:14:00.306  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
09-12 18:14:00.306  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.306  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 18:14:00.306  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 18:14:00.306  1014  3304 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.306  6917  6917 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 18:14:00.306  1014  3304 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.316  6917  6917 D BtGatt.GattService: Received start request. Starting profile...
09-12 18:14:00.316  6917  6917 D BtGatt.GattService: start()
09-12 18:14:00.316  6917  6917 D BtGatt.GattService: start()
09-12 18:14:00.316  6917  6917 I bluedroid: get_profile_interface gatt
,09-12 18:14:00.316  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.316  1014  3304 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.316  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 18:14:00.316  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:14:00.316  6917  6917 D BtGatt.AdvertiseManager: advertise manager created
,09-12 18:14:00.316  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 18:14:00.316  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 18:14:00.316  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 18:14:00.316  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:00.316  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 18:14:00.316  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.316  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.326  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.326  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.326  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.326  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-12 18:14:00.326  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 18:14:00.326  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 18:14:00.326  6917  6917 D BtGatt.GattService: mStartError = false
09-12 18:14:00.326  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.336  6917  6917 D HeadsetService: Received start request. Starting profile...
09-12 18:14:00.336  6917  6917 D HeadsetService: start()
,09-12 18:14:00.336  6917  6917 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 18:14:00.336  6917  6917 D HeadsetStateMachine: make
,09-12 18:14:00.336  1014  3308 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.336  1014  3308 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.336  1014  3308 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.336  1014  3308 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.336  1014  3308 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.346  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.346  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 18:14:00.346  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 18:14:00.346  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.346  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.346  6917  6917 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 18:14:00.346  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.346  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.346  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.346  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 18:14:00.356  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 18:14:00.356  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 18:14:00.356  1014  1326 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-12 18:14:00.356  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.356  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.356  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.356  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:14:00.356  1014  1312 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.356  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.356  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.356  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.356  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.366  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.366  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 18:14:00.366  6917  6932 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 18:14:00.366  1014  1138 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 18:14:00.366  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.366  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.366  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:00.366  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 18:14:00.366  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:00.376  6917  6917 I bluedroid: get_profile_interface handsfree
,09-12 18:14:00.376  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.376  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:00.376  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.376  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 18:14:00.386  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 18:14:00.386  1014  1561 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 18:14:00.386  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:14:00.386  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:00.386  1014  1561 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:00.386  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.386  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.386  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.386  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 18:14:00.386  6917  6932 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 18:14:00.386  6917  6932 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 18:14:00.386  6917  6932 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 18:14:00.396  6917  6917 I DualScoManager: Instantiating Dual Sco Manager
,09-12 18:14:00.396  6917  6917 I DualScoManager: Set HeadsetServiceHelper
,09-12 18:14:00.406  6917  6917 D BluetoothAtMessage: createCMTIContentObservers
,09-12 18:14:00.406  1014  3305 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 18:14:00.406  1014  3305 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:00.406  1014  3305 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 18:14:00.406  1014  3305 D SettingsProvider: selectionArgs: false
09-12 18:14:00.406  1014  3305 D SettingsProvider: selectionArgs: 1002
,09-12 18:14:00.406  1014  3305 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:00.406  1014  3305 D SettingsProvider: ret = -1
,09-12 18:14:00.406  6917  6941 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 18:14:00.406  6917  6917 D HeadsetService: mStartError = false
09-12 18:14:00.406  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.406  6917  6941 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 18:14:00.406  6917  6941 D HeadsetStateMachine: map size, before remove : 0
09-12 18:14:00.406  6917  6941 D HeadsetStateMachine: map size, after remove: 0
,09-12 18:14:00.416  6917  6917 D A2dpService: Received start request. Starting profile...
,09-12 18:14:00.416  6917  6917 D A2dpService: start()
,09-12 18:14:00.416  6917  6917 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 18:14:00.416  6917  6917 I bluedroid: get_profile_interface avrcp
,09-12 18:14:00.426  6917  6917 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 18:14:00.436  6917  6917 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 18:14:00.436  6917  6945 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 18:14:00.436  6917  6917 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-12 18:14:00.436  6917  6917 D A2dpStateMachine: make
,09-12 18:14:00.446  6917  6917 I bluedroid: get_profile_interface a2dp
,09-12 18:14:00.446  6917  6947 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 18:14:00.446  6917  6917 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 18:14:00.446  6917  6917 D A2dpService: mStartError = false
09-12 18:14:00.446  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.446  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-12 18:14:00.446  6917  6917 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 18:14:00.446  6917  6946 D A2dpStateMachine: Enter Disconnected: -2
,09-12 18:14:00.446  6917  6917 D HidService: Received start request. Starting profile...
09-12 18:14:00.446  6917  6917 D HidService: start()
09-12 18:14:00.446  6917  6917 I bluedroid: get_profile_interface hidhost
09-12 18:14:00.446  6917  6917 D HidService: setHidService(): set to: null
09-12 18:14:00.446  6917  6917 D HidService: mStartError = false
09-12 18:14:00.446  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.446  6917  6917 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 18:14:00.446  6917  6917 D HealthService: Received start request. Starting profile...
09-12 18:14:00.446  6917  6917 D HealthService: start()
,09-12 18:14:00.456  6917  6917 I bluedroid: get_profile_interface health
09-12 18:14:00.456  6917  6917 D HealthService: mStartError = false
09-12 18:14:00.456  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.456  6917  6917 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 18:14:00.456  1424  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 18:14:00.456  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 18:14:00.456  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 18:14:00.456  1424  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 18:14:00.456  6917  6917 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 18:14:00.456  6917  6917 D PanService: Received start request. Starting profile...
09-12 18:14:00.456  6917  6917 D PanService: start()
09-12 18:14:00.456  6917  6917 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 18:14:00.456  6917  6917 I bluedroid: get_profile_interface pan
,09-12 18:14:00.466  6917  6917 D PanService: mStartError = false
09-12 18:14:00.466  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:14:00.466  6917  6917 D HeadsetStateMachine: Proxy object connected
,09-12 18:14:00.466  6917  6917 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 18:14:00.466  6917  6941 D HeadsetStateMachine: Disconnected process message: 11
,09-12 18:14:00.466  6917  6917 D BluetoothMapService: Received start request. Starting profile...
09-12 18:14:00.466  6917  6917 D BluetoothMapService: start()
,09-12 18:14:00.466  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:00.476  6917  6945 D BluetoothMediaBrowser: no now playing list
09-12 18:14:00.476  6917  6945 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 18:14:00.476  6917  6917 D BluetoothMapService: mStartError = false
09-12 18:14:00.476  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:00.476  6917  6917 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-12 18:14:00.476  6917  6917 D SapService: Received start request. Starting profile...
09-12 18:14:00.476  6917  6917 D SapService: start()
09-12 18:14:00.476  6917  6917 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 18:14:00.476  6917  6917 I bluedroid: get_profile_interface sap
09-12 18:14:00.476  6917  6917 D SapService: mStartError = false
09-12 18:14:00.476  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
09-12 18:14:00.476  6917  6917 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 18:14:00.476  6917  6917 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-12 18:14:00.476  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 18:14:00.476  6917  6917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 18:14:00.476  6917  6917 D BluetoothA2dp: Proxy object connected
09-12 18:14:00.476  6917  6917 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 18:14:00.476  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 18:14:00.476  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 18:14:00.476  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 18:14:00.476  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 18:14:00.476  6917  6941 D HeadsetStateMachine: Disconnected process message: 18
09-12 18:14:00.476  6917  6941 D HeadsetStateMachine: Disconnected process message: 10
09-12 18:14:00.476  6917  6941 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-12 18:14:00.476  6917  6941 D HeadsetStateMachine: Disconnected process message: 11
,09-12 18:14:00.476  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:14:00.506  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 18:14:00.506  6917  6917 E BluetoothAdapterService(648850929): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 18:14:00.516  6917  6932 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 18:14:00.516  6917  6932 I bluedroid: enable
,09-12 18:14:00.516  6917  6932 I bt_hci_bdroid: init
,09-12 18:14:00.516  6917  6951 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 18:14:00.516  6917  6932 I bt_vendor: bt-vendor : init
,09-12 18:14:00.516  6917  6932 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 18:14:00.516  6917  6932 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 18:14:00.516  6917  6932 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-12 18:14:00.516  6917  6932 D bt_userial_mct: userial_init
09-12 18:14:00.516  6917  6932 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 18:14:00.516  6917  6932 I bt_vendor: Starting hciattach daemon
09-12 18:14:00.516  6917  6932 I bt_vendor: try to set false
,09-12 18:14:00.516  6917  6932 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-12 18:14:00.516  6917  6932 I bt_vendor: Starting hciattach daemon
09-12 18:14:00.516  6917  6932 I bt_vendor: try to set true
,09-12 18:14:00.536  6955  6955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 18:14:00.596  6961  6961 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-12 18:14:00.606  6962  6962 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 18:14:00.626  6964  6964 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 18:14:00.636  6965  6965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 18:14:00.646  6966  6966 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 18:14:00.656  6967  6967 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 18:14:00.906  6970  6970 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 18:14:00.916  6971  6971 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 18:14:00.976  6917  6932 I bt_vendor: bluetooth satus is on
,09-12 18:14:00.976  6917  6953 D bt_userial_mct: userial_open(port:0)
09-12 18:14:00.976  6917  6953 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 18:14:00.976  6917  6953 I bt_vendor: Done intiailizing UART,
,09-12 18:14:00.976  6917  6953 I bt_vendor: Done intiailizing UART,
09-12 18:14:00.976  6917  6953 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-12 18:14:00.976  6917  6953 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 18:14:00.986  6917  6973 D bt_userial_mct: Entering userial_read_thread()
,09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_PAN,
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_SAP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_GATT
,09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-12 18:14:00.986  6917  6951 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-12 18:14:01.086  6917  6951 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 18:14:01.096  6917  6951 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f706e9 
,09-12 18:14:01.096  6917  6951 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f706e9 
,09-12 18:14:01.106  6917  6935 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 18:14:01.116  6917  6935 E bt-btif : Calling BTA_HhEnable
,09-12 18:14:01.116  6917  6935 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 18:14:01.116  6917  6935 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 18:14:01.116  6917  6935 E BluetoothServiceJni: populateRssiValuesNative
09-12 18:14:01.116  6917  6935 I bluedroid: getModelRssiValues
,09-12 18:14:01.116  6917  6935 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 18:14:01.116  6917  6935 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 18:14:01.116  1014  1014 D SettingsProvider: name = bluetooth_name
,09-12 18:14:01.116  6917  6935 D BluetoothAdapterProperties: Name is: A5-1
,09-12 18:14:01.126  6917  6935 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 18:14:01.126  6917  6935 D BluetoothAdapterProperties: Scan Mode:20
09-12 18:14:01.126  6917  6935 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:14:01.126  6917  6935 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-12 18:14:01.126  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:01.126  6917  6935 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-12 18:14:01.126  6917  6935 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-12 18:14:01.126  6917  6935 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 18:14:01.126  6917  6935 E bt-btif : btif_sock_init: !vhci_init
,09-12 18:14:01.126  6917  6935 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-12 18:14:01.126  6917  6935 D IOP_DB_BT: db_open: db_open : handle 3023818768l, read 13894 bytes onto local cache
09-12 18:14:01.126  6917  6935 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-12 18:14:01.126  6917  6935 D IOP_DB_BT: db_query: result 1
09-12 18:14:01.126  6917  6935 I         : iop_db_open: iop_db_open status 0
09-12 18:14:01.126  6917  6935 D bte_conf: Device ID record 1 : primary
09-12 18:14:01.126  6917  6935 D bte_conf:   vendorId            = 0075
09-12 18:14:01.126  6917  6935 D bte_conf:   vendorIdSource      = 0001
09-12 18:14:01.126  6917  6935 D bte_conf:   product             = 0100
09-12 18:14:01.126  6917  6935 D bte_conf:   version             = 0200
09-12 18:14:01.126  6917  6935 D bte_conf:   clientExecutableURL = 
09-12 18:14:01.126  6917  6935 D bte_conf:   serviceDescription  = 
09-12 18:14:01.126  6917  6935 D bte_conf:   documentationURL    = 
09-12 18:14:01.126  6917  6935 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 18:14:01.136  6917  6932 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-12 18:14:01.136  6917  6932 D BluetoothAdapterProperties: ScanMode =  20
09-12 18:14:01.136  6917  6932 D BluetoothAdapterProperties: State =  11
,09-12 18:14:01.136  6917  6935 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 18:14:01.136  1014  1326 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 18:14:01.136  6917  6932 D BluetoothAdapterProperties: Setting state to 12
,09-12 18:14:01.136  6917  6932 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 18:14:01.136  6917  6973 E bt_mct  : hci lib postload completed
,09-12 18:14:01.136  6917  6935 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 18:14:01.136  6917  6935 D BluetoothAdapterProperties: Scan Mode:21
,09-12 18:14:01.136  1014  1138 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 18:14:01.136  1014  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 18:14:01.136  1014  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 18:14:01.136  1014  1138 D SettingsProvider: selectionArgs: false
09-12 18:14:01.136  1014  1138 D SettingsProvider: selectionArgs: 1002
09-12 18:14:01.136  1014  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 18:14:01.136  1014  1138 D SettingsProvider: ret = -1
,09-12 18:14:01.136  6917  6932 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 18:14:01.136  6917  6932 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 18:14:01.146  6917  6935 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 18:14:01.146  1014  1312 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:01.146  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.146  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.146  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.146  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.156  1014  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:01.156  1014  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 18:14:01.156  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:01.156  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.156  6917  6932 D BluetoothAdapterService: Autoconnection is available 
09-12 18:14:01.156  6917  6932 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 18:14:01.156  6917  6932 D BluetoothAdapterService: starting service from this receiver
,09-12 18:14:01.156  1014  1014 D BluetoothA2dp: Proxy object connected
,09-12 18:14:01.156  1014  1326 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:01.156  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.156  1904  1918 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.156  1904  1918 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.156  1014  1326 W ActivityManager: userId = 0, bbcId = -10000,
09-12 18:14:01.156  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.156  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.166  1299  1308 D BluetoothPan: Binding service...
,09-12 18:14:01.166  6917  6932 I BluetoothAdapterState: Entering On State from state = 11
,09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:01.166  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:01.166  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 18:14:01.176  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.176  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.176  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.176  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.176  1177  1197 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.176  1177  1197 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.176  1014  1045 D BluetoothPan: Binding service...
,09-12 18:14:01.176  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 18:14:01.176  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.176  1299  1311 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 18:14:01.186  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-12 18:14:01.186  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:14:01.186  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.186  6917  6917 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 18:14:01.186  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.186  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.186  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.196  1424  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.196  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:14:01.196  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.196  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.196  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.196  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.196  1424  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.196  1299  6864 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.196  1299  6864 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.196  6917  6936 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.196  6917  6936 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.206  1437  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.206  1437  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.206  1450  1461 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.206  1450  1461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.206  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:14:01.206  6917  6917 I BluetoothPbapService: Handler(): got msg=1
,09-12 18:14:01.206  1299  1299 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 18:14:01.206  1299  1299 D PanProfile: Bluetooth service connected
,09-12 18:14:01.206  1014  1138 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:14:01.206  1299  1308 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 18:14:01.216  1299  1299 D BluetoothPbap: Proxy object connected
09-12 18:14:01.216  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-12 18:14:01.216  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.216  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.216  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.216  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.216  6917  6978 V BluetoothPbapService: PBAP Service initSocket try: 0
09-12 18:14:01.216  1014  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.216  1299  1299 D PbapServerProfile: Bluetooth service connected
09-12 18:14:01.216  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.216  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 18:14:01.216  1299  1299 D BluetoothMap: Proxy object connected
,09-12 18:14:01.216  1299  1299 D MapProfile: Bluetooth service connected
09-12 18:14:01.216  1014  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:14:01.216  1299  1299 D BluetoothMap: getConnectedDevices()
,09-12 18:14:01.216  6363  6376 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.216  6363  6376 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.216  1299  6862 D Bluetoothsap: onBluetoothStateChange: up=true
,09-12 18:14:01.216  1299  6862 D Bluetoothsap: Binding service...
,09-12 18:14:01.226  1299  6862 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 18:14:01.226  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 18:14:01.226  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.226  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.226  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.226  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.226  1299  6862 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 18:14:01.226  1299  1299 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-12 18:14:01.226  1299  1299 D SapProfile: Bluetooth service connected
09-12 18:14:01.226  1299  1299 D Bluetoothsap: getConnectedDevices()
09-12 18:14:01.226  1299  1311 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.226  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.226  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.226  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.226  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.226  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.226  1299  1311 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 18:14:01.226  6917  6978 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:14:01.226  6917  6978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:01.236  1424  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.236  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.236  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.236  1299  1299 D HeadsetProfile: Bluetooth service connected
,09-12 18:14:01.236  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.236  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.236  6917  6978 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-12 18:14:01.236  6917  6978 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:01.236  6917  6978 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:01.236  6917  6978 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb0c672
,09-12 18:14:01.236  6917  6978 D BluetoothSocket: channel: 19
09-12 18:14:01.236  6917  6978 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 18:14:01.236  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.236  1424  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.236  1424  6865 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 18:14:01.236  1424  6865 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.236  1014  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.236  1014  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.236  2906  6866 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.236  2906  6866 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 18:14:01.236  2906  2915 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:01.246  2906  2915 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.246  1014  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 18:14:01.246  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.246  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.246  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.246  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.246  2906  2906 D BluetoothA2dp: Proxy object connected
,09-12 18:14:01.246  1299  6862 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 18:14:01.246  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-12 18:14:01.246  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.246  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.256  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.256  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.256  1299  1299 D BluetoothInputDevice: Proxy object connected
09-12 18:14:01.256  1299  1299 D HidProfile: Bluetooth service connected
,09-12 18:14:01.256  1424  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.256  1014  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.256  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 18:14:01.256  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.256  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.256  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.256  1424  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.256  6917  6926 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:01.256  2906  6866 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.256  1014  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 18:14:01.266  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.266  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.266  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.266  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.266  2906  6866 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.266  1450  1785 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.266  1014  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 18:14:01.266  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 18:14:01.266  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.266  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.266  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-12 18:14:01.266  1450  1785 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 18:14:01.266  6205  6216 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 18:14:01.266  6205  6216 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 18:14:01.266  1299  1311 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 18:14:01.266  1299  1311 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 18:14:01.276  1014  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 18:14:01.276  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.276  1014  1045 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.276  1014  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:01.276  1014  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.276  1014  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 18:14:01.276  1014  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 18:14:01.276  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.276  1299  1299 D BluetoothA2dp: Proxy object connected
09-12 18:14:01.276  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-12 18:14:01.276  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-12 18:14:01.276  1299  1299 D A2dpProfile: Bluetooth service connected
,09-12 18:14:01.276  1424  1424 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@fed2f3c, true
,09-12 18:14:01.276  1424  1424 D BluetoothHeadset: registerMessageListener
,09-12 18:14:01.286  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,09-12 18:14:01.286  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 18:14:01.286  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.286  1177  1177 D BluetoothTile:  getBluetoothState : 12
,09-12 18:14:01.286  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.286  1787  1787 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 18:14:01.296  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.296  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:01.296  1014  1561 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:14:01.296  1014  1561 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.296  1014  1561 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.296  1014  1561 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:01.296  1014  1561 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 18:14:01.296  6917  6936 D HeadsetService: registerMessageListener
,09-12 18:14:01.296  6917  6936 D HeadsetService: registerMessageListener
,09-12 18:14:01.296  1299  1299 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 18:14:01.296  6917  6941 D HeadsetStateMachine: Disconnected process message: 70
09-12 18:14:01.296  6917  6941 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@11e76ac3
09-12 18:14:01.296  1424  1424 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-12 18:14:01.296  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 18:14:01.306  1299  1299 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 18:14:01.306  1299  1299 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 18:14:01.306  1299  1299 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 18:14:01.306  1299  1299 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 18:14:01.306  1014  1217 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 18:14:01.306  6917  6980 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 18:14:01.306  1014  1492 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 18:14:01.306  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 18:14:01.306  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-12 18:14:01.306  1424  1424 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 18:14:01.306  1424  1424 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 18:14:01.306  1177  1721 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 18:14:01.306  6917  6941 D HeadsetStateMachine: Disconnected process message: 9
,09-12 18:14:01.306  6917  6941 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 18:14:01.306  1299  1299 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 18:14:01.316  1014  3307 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 18:14:01.316  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.316  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.316  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.316  6917  6980 D BluetoothSocket: bindListen(): myUserId = 0
09-12 18:14:01.316  6917  6980 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:01.316  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings,
09-12 18:14:01.316   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.316   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.316   283   283 V voice   : voice_set_parameters: exit with code(-2)
09-12 18:14:01.316   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 18:14:01.316   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-12 18:14:01.316   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 18:14:01.316   283   283 V audio_hw_primary: adev_set_parameters: exit
09-12 18:14:01.316  6917  6941 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 18:14:01.326  6917  6980 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-12 18:14:01.326  6917  6980 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:01.326  6917  6980 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:01.326  6917  6980 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e20f40
,09-12 18:14:01.326  6917  6980 D BluetoothSocket: channel: 5
,09-12 18:14:01.326  1299  1299 D DockEventReceiver: finishStartingService: stopping service
,09-12 18:14:01.336  1299  1299 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 18:14:01.336  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 18:14:01.336  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 18:14:01.346  6917  6917 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1
,09-12 18:14:01.346  6917  6917 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 18:14:01.346  1014  3307 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 18:14:01.346  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.346  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:01.346  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:01.346  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 18:14:01.376  1904  1904 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 18:14:01.376  1014  1138 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 18:14:01.376  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 18:14:01.376  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.376  1014  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:14:01.376  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:01.386  1904  6988 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 18:14:01.386  1014  1555 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 18:14:01.386  1904  1904 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 18:14:01.386  1014  1312 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:14:01.396  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.396  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:14:01.396  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:01.396  6917  6991 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 18:14:01.396  6917  6991 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 18:14:01.406  6917  6991 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,09-12 18:14:01.406  6917  6991 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 18:14:01.406  6917  6991 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 18:14:01.406  6917  6991 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b2eb1ca
09-12 18:14:01.406  6917  6991 D BluetoothSocket: channel: 12
09-12 18:14:01.406  6917  6991 I BtOppRfcommListener: Accept thread started.
,09-12 18:14:01.406  1014  3304 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 18:14:01.406  1014  3304 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:01.406  1014  3304 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 18:14:01.406  1014  3304 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:01.416  1904  6988 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-12 18:14:01.806   288   288 E SMD     : DCD OFF
,09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:02.026  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:02.036  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:02.036  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:02.036  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@363b1728 added. We now have 8 listener(s)
,09-12 18:14:02.036  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:02.036  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 18:14:02.036  1014  1026 D WifiService: setWifiEnabled: false pid=6205, uid=10155
09-12 18:14:02.036  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 18:14:02.036  1014  1026 D SecContentProvider2: mCursor = null
09-12 18:14:02.036  1014  1026 D SettingsProvider: name = wifi_on
,09-12 18:14:02.046  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:02.046  1014  1312 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 18:14:02.046  1014  1312 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-12 18:14:02.046  1014  1312 D SecContentProvider2: mCursor = null
,09-12 18:14:02.046  1014  1312 D WifiService: setWifiEnabled: true pid=6205, uid=10155
,09-12 18:14:02.046  1014  1312 W ActivityManager: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 18:14:02.056  1014  1312 W WifiService: Failed getting userId using ActivityManagerNative
09-12 18:14:02.056  1014  1312 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6205, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 18:14:02.056  1014  1312 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 18:14:02.056  1014  1312 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 18:14:02.056  1014  1312 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 18:14:02.056  1014  1312 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 18:14:02.056  1014  1312 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 18:14:02.056  1014  1312 D SettingsProvider: name = wifi_on
,09-12 18:14:02.066  1014  1126 E WifiHW  : ##################### set firmware type 0 #####################,
,09-12 18:14:02.326  1014  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 18:14:02.326  1014  1217 D BatteryService: level:81, scale:100, status:2, health:2, present:true, voltage: 4078, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 18:14:02.326  1014  1217 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 18:14:02.326  1014  1217 D BatteryService: stay LED for charging
09-12 18:14:02.326  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 18:14:02.326  1014  1014 I MotionRecognitionService: Plugged
,09-12 18:14:02.326  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 18:14:02.326  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-12 18:14:02.326  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 18:14:02.326  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 18:14:02.326  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 81
,09-12 18:14:02.346  6917  6917 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 18:14:02.346  6917  6941 D HeadsetStateMachine: Disconnected process message: 10
,09-12 18:14:02.356  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:14:02.356  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:14:02.356  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:81 status:2 health:2
,09-12 18:14:02.436  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 18:14:02.436  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 18:14:02.436  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:14:02.436  1014  1043 D Tethering: interfaceAdded wlan0
,09-12 18:14:02.436  1014  1129 E Tethering: No numeric data,
09-12 18:14:02.436  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 18:14:02.436  1014  1129 D Tethering: clearTetheredNotification()
,09-12 18:14:02.446  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:02.446  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:02.446  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-12 18:14:02.446  1177  1177 D HotspotTile: updateTetherState():false, false
,09-12 18:14:02.446  1014  1043 D Tethering: interfaceAdded p2p0
,09-12 18:14:02.456  1014  1043 D Tethering: p2p0 is not a tetherable iface, ignoring,
09-12 18:14:02.456  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-12 18:14:02.456  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.456  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:02.456  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
09-12 18:14:02.456  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:02.456  1014  1123 V NetworkStats: performPollLocked() took 13ms
,09-12 18:14:02.466  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.466  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.466  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.476   278  1013 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 18:14:02.476   278  1013 D SoftapController: Softap fwReload - Ok
,09-12 18:14:02.476   278  1013 D CommandListener: Setting iface cfg
,09-12 18:14:02.476   278  1013 D CommandListener: Trying to bring down wlan0
09-12 18:14:02.476   278  1013 D CommandListener: Clearing all IP addresses on wlan0
,09-12 18:14:02.486  1014  1126 E WifiHW  : supplicant_name : p2p_supplicant,
,09-12 18:14:02.486  1014  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-12 18:14:02.496  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:02.496  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-12 18:14:02.496  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.496  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.496  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.496  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:14:02.496  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:02.496  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.496  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:02.496  1177  1177 D HotspotTile: onReceive : 2, 0
09-12 18:14:02.496  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 18:14:02.496  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:14:02.506  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:02.506  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-12 18:14:02.506  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:02.506  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 18:14:02.506  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:02.506  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 18:14:02.506  3742  3742 I Hs20UtilService: Starting #17
09-12 18:14:02.506  3742  3757 I Hs20UtilService: Message received 5011
09-12 18:14:02.506  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:14:02.506  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:14:02.506  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:14:02.506  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-12 18:14:02.536  7005  7005 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 18:14:02.536  7005  7005 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 18:14:02.536  7005  7005 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
09-12 18:14:02.556  7005  7005 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-12 18:14:02.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7005
09-12 18:14:02.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 18:14:02.556  7005  7005 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 18:14:02.556  7005  7005 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.556  7005  7005 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 18:14:02.556  7005  7005 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 18:14:02.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7005
09-12 18:14:02.556   365   365 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-12 18:14:02.686   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-12 18:14:02.696  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,09-12 18:14:02.766  7005  7005 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 18:14:02.766  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 18:14:02.776  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-12 18:14:02.776   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7005
09-12 18:14:02.776   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-12 18:14:02.776  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 18:14:02.776  7005  7005 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.776  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:14:02.776  7005  7005 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:02.776  7005  7005 E wpa_supplicant: SIM READ ERROR
09-12 18:14:02.776  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:14:02.776  7005  7005 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:02.776  7005  7005 E wpa_supplicant: SIM READ ERROR
09-12 18:14:02.776  7005  7005 I wpa_supplicant: Blacklist: Clear (all) 
09-12 18:14:02.776  7005  7005 I wpa_supplicant: wpa_default_ap_write_once,
09-12 18:14:02.776  7005  7005 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:14:02.776  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.776  7005  7005 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-12 18:14:02.776  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:02.776  7005  7005 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 18:14:02.776  7005  7005 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:14:02.776  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:14:02.776  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-12 18:14:02.786  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:14:02.786  1014  1129 D Tethering: InitialState.processMessage what=4
,09-12 18:14:02.786  1014  1129 E Tethering: No numeric data
09-12 18:14:02.786  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 18:14:02.786  1014  1129 D Tethering: clearTetheredNotification()
,09-12 18:14:02.786  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.786  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:14:02.786  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:02.786  1177  1177 D HotspotTile: updateTetherState():false, false
,09-12 18:14:02.786  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:14:02.786  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:02.786  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:02.786  1014  1123 V NetworkStats: performPollLocked() took 5ms
,09-12 18:14:02.796  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:02.796  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:02.826  7005  7005 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-12 18:14:02.986  7005  7005 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 18:14:02.986  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 18:14:02.996  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,09-12 18:14:02.996   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7005
09-12 18:14:02.996   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-12 18:14:02.996  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 18:14:02.996  7005  7005 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:02.996  7005  7005 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 18:14:03.006  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 18:14:03.016  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
09-12 18:14:03.016   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7005
09-12 18:14:03.016   365   365 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-12 18:14:03.016  7005  7005 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 18:14:03.016  7005  7005 I wpa_supplicant: ssSupport state is = 1
09-12 18:14:03.016  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 18:14:03.016  7005  7005 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 18:14:03.016  7005  7005 E wpa_supplicant: SIM READ ERROR
09-12 18:14:03.016  7005  7005 I wpa_supplicant: wpa_default_ap_write_once
09-12 18:14:03.016  7005  7005 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 18:14:03.016  7005  7005 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-12 18:14:03.016  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:03.016  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:14:03.016  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-12 18:14:03.016  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:03.016  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 18:14:03.016  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:14:03.066  7005  7005 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 18:14:03.066  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 18:14:03.146  7005  7005 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 18:14:03.146  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-12 18:14:03.146  7005  7005 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-12 18:14:03.156  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-12 18:14:03.156  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 18:14:03.156  7005  7005 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-12 18:14:03.156  7005  7005 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 18:14:03.156  7005  7005 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 18:14:03.156  7005  7005 E wpa_supplicant: SIM READ ERROR
,09-12 18:14:03.156  7005  7005 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 18:14:03.186  7005  7005 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 18:14:03.196  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-12 18:14:03.196  7005  7005 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 18:14:03.196  1014  1126 D WifiConfigStore: Loading config and enabling all networks 
,09-12 18:14:03.196  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:14:03.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-12 18:14:03.196  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:03.196  1177  1721 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 18:14:03.196  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:03.206  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:14:03.196  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:03.206  1177  1177 D HotspotTile: onReceive : 3, 0
,09-12 18:14:03.196  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:03.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 18:14:03.196  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-12 18:14:03.206  1299  1299 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 18:14:03.206  1014  1126 E WifiConfigStore: Not a HS20
,09-12 18:14:03.206  1014  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:03.216  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:03.216  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-12 18:14:03.216  1014  3307 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:14:03.216  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 18:14:03.216  7005  7005 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 18:14:03.216  7005  7005 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 18:14:03.216  7005  7005 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 18:14:03.216  7005  7005 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 18:14:03.216  7005  7005 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 18:14:03.216  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 18:14:03.216  7005  7005 I wpa_supplicant: First Scan Start
09-12 18:14:03.216  7005  7005 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 18:14:03.216  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:03.216  1014  3307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:03.216  1014  3307 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:03.216  1014  3307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:03.216  1014  3307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:03.226  1014  1126 D WifiNative-wlan0: Setting external_sim to 1
,09-12 18:14:03.226  1014  1126 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 18:14:03.226  1014  1126 I WifiNative-HAL: startHal
09-12 18:14:03.226  1014  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9e25488c
09-12 18:14:03.226  1014  1126 I WifiNative-HAL: Could not start hal
,09-12 18:14:03.226  6419  6419 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 18:14:03.226  3742  3742 I Hs20UtilService: Starting #18
,09-12 18:14:03.226  3742  3757 I Hs20UtilService: Message received 5011
,09-12 18:14:03.226  1014  1126 E WifiNative-wlan0: do suspend true
,09-12 18:14:03.226  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:14:03.226  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:14:03.226  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
09-12 18:14:03.226  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:14:03.226  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 18:14:03.226  1014  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-12 18:14:03.226   278  1013 D CommandListener: Setting iface cfg
09-12 18:14:03.226   278  1013 D CommandListener: Trying to bring up p2p0
,09-12 18:14:03.226  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-12 18:14:03.236  1014  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 18:14:03.236  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:14:03.236  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:14:03.236  1014  1126 E WifiNative-wlan0: invaild command id : 215
,09-12 18:14:03.236  1014  1149 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:03.236  1014  1149 I WifiNative-HAL: startHal
09-12 18:14:03.236  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9ccd99bc
09-12 18:14:03.236  1014  1149 I WifiNative-HAL: Could not start hal
09-12 18:14:03.236  1014  1149 E WifiScanningService: could not start HAL
,09-12 18:14:03.236  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-12 18:14:03.236  1014  1125 D WifiP2pService: P2pEnablingState
,09-12 18:14:03.236  1014  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-12 18:14:03.236  1014  1150 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:03.236  1014  1125 D WifiP2pService: P2p socket connection successful
09-12 18:14:03.236  7005  7005 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 18:14:03.236  1014  1125 D WifiP2pService: P2pEnabledState
,09-12 18:14:03.236  7005  7005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 18:14:03.236  7005  7005 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-12 18:14:03.246  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 18:14:03.246  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:14:03.246  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 18:14:03.246  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 18:14:03.246  1014  1126 E WifiNative-wlan0: invaild command id : 215
,09-12 18:14:03.246  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-12 18:14:03.246  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:03.246  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:03.246  1014  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,09-12 18:14:03.246  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-12 18:14:03.246  1014  1046 D WifiDisplayController: disconnect
09-12 18:14:03.246  1014  1046 D WifiDisplayController: updateConnection
09-12 18:14:03.246  1014  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 18:14:03.246  1014  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:14:03.246  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 18:14:03.246  1014  3304 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 18:14:03.246  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 18:14:03.246  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:03.246  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:03.256  1014  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 18:14:03.256  1014  1046 D WifiDisplayAdapter: onP2pDisconnected
09-12 18:14:03.256  1014  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 18:14:03.256  1014  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 18:14:03.256  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,09-12 18:14:03.256  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-12 18:14:03.256  1014  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-12 18:14:03.256  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 18:14:03.256  1014  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  secondary type: null
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  wps: 0
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  grpcapab: 0
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  devcapab: 0
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  status: 3
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  wfdInfo: null
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  groupownerAddress: null
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  GOdeviceName: null
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  interfaceAddress: 
09-12 18:14:03.256  1014  1046 D WifiDisplayController:  SConnectInfo : null
,09-12 18:14:03.256  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:14:03.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 18:14:03.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 18:14:03.266  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 18:14:03.266  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 18:14:03.266  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:14:03.266  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:14:03.266  6444  6444 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 18:14:03.266  6444  6444 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 18:14:03.276  6459  6459 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 18:14:03.286  1014  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 18:14:03.286  1014  1125 D WifiP2pService: InactiveState
,09-12 18:14:03.286  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-12 18:14:03.286  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:14:03.286  7005  7005 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-12 18:14:03.286  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
,09-12 18:14:03.286  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 18:14:03.426  1014  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 18:14:03.426  1014  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-12 18:14:03.426  1014  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 18:14:03.536  1014  2749 D SSRM:n  : SIOP:: AP = 340
,09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:04.076  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:04.076  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:04.076  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 18:14:04.086  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 18:14:04.086  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2773f561 Bundle[{}]
,09-12 18:14:04.086  6205  6257 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 18:14:04.086  6205  6257 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 18:14:04.086  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 18:14:04.086  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 18:14:04.086  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 18:14:04.096  6205  6257 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 18:14:04.096  6205  6257 I System.out: Running OutgoingSocketThread
,09-12 18:14:04.096  6205  7012 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1167)
,09-12 18:14:04.106  6205  7012 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39999
,09-12 18:14:04.106  6205  7012 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 18:14:04.446  7005  7005 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
09-12 18:14:04.446  7005  7005 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 18:14:04.446  7005  7005 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-12 18:14:04.446  7005  7005 I wpa_supplicant: Trying to associate with  'G700'
,09-12 18:14:04.446  7005  7005 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-12 18:14:04.446  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
09-12 18:14:04.446  1014  7010 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-12 18:14:04.466  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.466  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:04.566  7005  7005 E wpa_supplicant: Cmd 35605 not handled
,09-12 18:14:04.566  7005  7005 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 18:14:04.566  7005  7005 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-12 18:14:04.566  7005  7005 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-12 18:14:04.566  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 18:14:04.566  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:14:04.566  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 18:14:04.566  7005  7005 I wpa_supplicant: Associated with F4.99.3E
09-12 18:14:04.566  7005  7005 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 18:14:04.566  7005  7005 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 18:14:04.566  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:14:04.566  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-12 18:14:04.576  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 18:14:04.576  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:14:04.576  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 18:14:04.576  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 18:14:04.576  1014  1043 D Tethering: interfaceStatusChanged wlan0, false
09-12 18:14:04.576  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-12 18:14:04.576  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,09-12 18:14:04.576  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-12 18:14:04.576  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 18:14:04.576  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.576  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:04.586  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 18:14:04.586  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:04.586  1014  1129 E Tethering: No numeric data
,09-12 18:14:04.586  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 18:14:04.586  1014  1129 D Tethering: clearTetheredNotification()
,09-12 18:14:04.586  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:04.586  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 18:14:04.586  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 18:14:04.586  1177  1177 D HotspotTile: updateTetherState():false, false
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 18:14:04.586  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 18:14:04.586  7005  7005 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 18:14:04.586  7005  7005 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 18:14:04.586  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 18:14:04.596  7005  7005 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 18:14:04.596  7005  7005 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 18:14:04.596  1014  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 18:14:04.596  1014  1043 D Tethering: interfaceStatusChanged wlan0, true
09-12 18:14:04.596  1014  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 18:14:04.596  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-12 18:14:04.596  1014  1123 V NetworkStats: performPollLocked() took 10ms
,09-12 18:14:04.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 18:14:04.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:04.596  1014  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 18:14:04.596  1014  1126 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-12 18:14:04.606  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:04.606  1014  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 18:14:04.606  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:04.606  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:14:04.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:04.606  1014  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 18:14:04.606  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:14:04.616  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:04.616  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:04.616  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:04.616  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:04.616  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:04.616  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:04.616  3742  3742 I Hs20UtilService: Starting #19,
,09-12 18:14:04.616  3742  3757 I Hs20UtilService: Message received 5007
09-12 18:14:04.616  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 18:14:04.616  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:14:04.626  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:14:04.626  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-12 18:14:04.626  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:14:04.626  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 18:14:04.626  1299  1299 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 18:14:04.626  1299  3121 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 18:14:04.636   278  1013 D CommandListener: Setting iface cfg
,09-12 18:14:04.636  1014  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,09-12 18:14:04.636  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:14:04.636  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:04.646  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:14:04.646  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 18:14:04.646  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.646  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.646  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.646  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:04.656  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 18:14:04.656  1014  1126 D SecContentProvider2: mCursor = null
,09-12 18:14:04.656  1014  1126 E WifiNative-wlan0: do suspend false
,09-12 18:14:04.666  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-12 18:14:04.666  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:14:04.806   288   288 E SMD     : DCD OFF,
,09-12 18:14:04.876  7015  7015 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 18:14:04.886  7015  7015 I dhcpcd  : version 5.5.6 starting
,09-12 18:14:04.886  7015  7015 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-12 18:14:04.936  7015  7015 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-12 18:14:04.936  7015  7015 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 18:14:04.936  7015  7015 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
09-12 18:14:04.936  7015  7015 I dhcpcd  : bssid match
09-12 18:14:04.936  7015  7015 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
,09-12 18:14:05.006  7015  7015 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-12 18:14:05.086  7015  7015 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-12 18:14:05.096  6205  6257 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1168)
09-12 18:14:05.096  6205  6257 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1168)
,09-12 18:14:05.106  6205  6257 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1173)
,09-12 18:14:05.106  6205  6257 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 18:14:05.106  6205  6257 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1174)
,09-12 18:14:05.106  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-12 18:14:05.106  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29273c41 added. We now have 2 listener(s),
,09-12 18:14:05.116  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 18:14:05.116  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.116  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.116  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:05.116  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1556a5e6 added. We now have 9 listener(s)
09-12 18:14:05.116  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.116  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:05.116  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,09-12 18:14:05.126  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:05.126  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:14:05.126  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-12 18:14:05.126  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.126  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbe7dd4 added. We now have 3 listener(s)
09-12 18:14:05.126  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.136  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a5b7d added. We now have 10 listener(s)
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.136  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:05.136  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 18:14:05.136  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.136  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29273c41 removed from the list
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1556a5e6 removed from the list
09-12 18:14:05.136  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.136  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:05.136  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1556a5e6 not in the list
09-12 18:14:05.136  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@206a5b7d removed from the list,
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 18:14:05.136  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.136  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.136  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 18:14:05.136  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bbe7dd4 removed from the list
09-12 18:14:05.146  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.146  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d73a72 added. We now have 2 listener(s)
09-12 18:14:05.146  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.146  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.146  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.146  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.146  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399ecec3 added. We now have 9 listener(s),
09-12 18:14:05.146  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.146  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
09-12 18:14:05.146  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:05.156  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false,
,09-12 18:14:05.156  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 18:14:05.156  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:14:05.156  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.156  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc63279 added. We now have 3 listener(s)
,09-12 18:14:05.156  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.156  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.156  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.156  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.156  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.156  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395a8bbe added. We now have 10 listener(s)
09-12 18:14:05.156  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.156  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.156  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:05.156  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:14:05.156  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.156  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 18:14:05.156  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.166  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:05.166  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-12 18:14:05.166  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-12 18:14:05.176  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 18:14:05.176  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:14:05.176  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:05.186  6917  6981 D BtGatt.GattService: registerClient() - UUID=49bde6aa-935b-4cc4-8443-ec9ad5d1808e,
,09-12 18:14:05.226  6917  6935 D BtGatt.GattService: onClientRegistered() - UUID=49bde6aa-935b-4cc4-8443-ec9ad5d1808e, clientIf=6
,09-12 18:14:05.226  6205  6216 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 18:14:05.226  6917  6979 D BtGatt.GattService: start scan with filters
,09-12 18:14:05.226  6917  6940 D BtGatt.ScanManager: handling starting scan
09-12 18:14:05.226  6917  6940 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@26acadf1,
09-12 18:14:05.226  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:14:05.226  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:05.226  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-12 18:14:05.226  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:14:05.236  6917  6935 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:14:05.236  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-12 18:14:05.236  6917  6940 D BtGatt.ScanManager: allow scan with filters
09-12 18:14:05.236  6917  6940 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:14:05.236  6917  6940 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-12 18:14:05.236  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-12 18:14:05.236  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.236  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:05.236  6917  6940 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:05.236  6917  6940 D BtGatt.ScanManager: configuring batch scan storage, appIf 6,
,09-12 18:14:05.236  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 18:14:05.236  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:05.236  6917  6935 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:14:05.236  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.246  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:05.246  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,09-12 18:14:05.246  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.246  6205  6257 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 18:14:05.246  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.246  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 18:14:05.246  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 18:14:05.246  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:05.246  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 18:14:05.246  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:05.246  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:14:05.246  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:14:05.246  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:14:05.246  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:14:05.256  6917  6926 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:05.256  6917  6976 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:05.256  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:05.256  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:05.256  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:05.256  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.266  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 18:14:05.266  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.266  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:05.266  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 18:14:05.266  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.266  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.266  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.266  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.266  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34d73a72 removed from the list
,09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.266  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399ecec3 removed from the list
09-12 18:14:05.266  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.266  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.266  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.266  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.266  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.266  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399ecec3 not in the list
,09-12 18:14:05.266  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.266  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.276  6917  6940 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 65,
09-12 18:14:05.276  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:05.276  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.276  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.276  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@395a8bbe removed from the list,
09-12 18:14:05.276  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.276  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.276  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.276  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.276  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1bc63279 removed from the list
,09-12 18:14:05.276  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.276  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2fa5ca added. We now have 2 listener(s)
,09-12 18:14:05.286  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.286  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.286  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.286  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:05.286  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c09533b added. We now have 9 listener(s)
09-12 18:14:05.286  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.286  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:05.286  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.296  6917  6940 D BtGatt.ScanManager: filter size is 1,
09-12 18:14:05.296  6917  6940 D BtGatt.ScanManager: delete FilterIndex - 3,
09-12 18:14:05.296  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 18:14:05.296  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.296  6917  6940 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:14:05.296  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:14:05.296  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.296  6917  6940 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:14:05.296  6917  6935 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-12 18:14:05.296  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:05.306  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:05.306  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:05.306  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 18:14:05.306  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.306  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3116b7b1 added. We now have 3 listener(s)
,09-12 18:14:05.306  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.316  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 18:14:05.316  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.316  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:14:05.316  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.316  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@168a5496 added. We now have 10 listener(s)
09-12 18:14:05.316  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.316  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.316  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:05.316  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.316  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:05.316  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:14:05.316  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.316  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:05.316  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:05.326  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:05.326  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:05.336  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-12 18:14:05.336  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 18:14:05.336  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:05.336  6917  6925 D BtGatt.GattService: registerClient() - UUID=adba1e6d-8675-4cf6-b762-9b720abe8839
,09-12 18:14:05.356  1014  1041 W ProcessCpuTracker: Skipping unknown process pid 7022
,09-12 18:14:05.356  1014  1041 W ProcessCpuTracker: Skipping unknown process pid 7041
,09-12 18:14:05.376  6917  6935 D BtGatt.GattService: onClientRegistered() - UUID=adba1e6d-8675-4cf6-b762-9b720abe8839, clientIf=6
09-12 18:14:05.376  6205  6216 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:14:05.376  6917  6976 D BtGatt.GattService: start scan with filters
,09-12 18:14:05.376  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 18:14:05.376  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:05.376  6917  6940 D BtGatt.ScanManager: handling starting scan
09-12 18:14:05.376  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 18:14:05.376  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:14:05.386  6917  6935 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-12 18:14:05.386  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.386  6917  6940 D BtGatt.ScanManager: allow scan with filters
09-12 18:14:05.386  6917  6940 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:14:05.386  6917  6940 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
09-12 18:14:05.386  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:14:05.386  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.386  6917  6940 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:05.386  6917  6940 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 18:14:05.386  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:05.386  6917  6935 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:14:05.386  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.386  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 18:14:05.386  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:05.386  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 18:14:05.386  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.396  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 18:14:05.396  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:14:05.396  6205  6257 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 18:14:05.406  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:05.406  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.406  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.406  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.406  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b2fa5ca removed from the list
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.406  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c09533b removed from the list
09-12 18:14:05.406  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.406  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 18:14:05.406  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.406  6917  6940 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 66
,09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 18:14:05.406  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c09533b not in the list
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 18:14:05.406  6917  6979 D BtGatt.GattService: stopScan() - queue size =1
,09-12 18:14:05.406  6917  6926 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:05.406  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 18:14:05.406  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:05.406  6917  6940 D BtGatt.ScanManager: filter size is 1
,09-12 18:14:05.406  6917  6940 D BtGatt.ScanManager: delete FilterIndex - 4
,09-12 18:14:05.416  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 18:14:05.416  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.416  6917  6940 D BtGatt.ScanManager: stopping BLe Batch
,09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.416  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.416  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.416  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@168a5496 removed from the list
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.416  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.416  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3116b7b1 removed from the list
,09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250f2422 added. We now have 2 listener(s)
,09-12 18:14:05.416  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:14:05.416  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.416  6917  6940 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 18:14:05.416  6917  6935 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 18:14:05.416  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.416  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0eeb3 added. We now have 9 listener(s)
09-12 18:14:05.416  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 18:14:05.426  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 18:14:05.426  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 18:14:05.426  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 18:14:05.426  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 18:14:05.426  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:05.426  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.426  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ddbabe9 added. We now have 3 listener(s)
,09-12 18:14:05.426  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.436  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-12 18:14:05.436  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 18:14:05.436  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 18:14:05.436  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.436  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 18:14:05.436  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41f606e added. We now have 10 listener(s)
09-12 18:14:05.436  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.436  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 18:14:05.436  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 18:14:05.436  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 18:14:05.436  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 18:14:05.436  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 18:14:05.436  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 18:14:05.446  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 18:14:05.446  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 18:14:05.446  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 18:14:05.446  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 18:14:05.446  6205  6257 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 18:14:05.446  6917  6976 D BtGatt.GattService: registerClient() - UUID=c24a990d-b5c3-4839-9af8-daaf3e075905
,09-12 18:14:05.476  1014  1126 E WifiNative-wlan0: do suspend true
,09-12 18:14:05.486  6917  6935 D BtGatt.GattService: onClientRegistered() - UUID=c24a990d-b5c3-4839-9af8-daaf3e075905, clientIf=6
,09-12 18:14:05.486  6205  6213 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 18:14:05.496  6917  6925 D BtGatt.GattService: start scan with filters
,09-12 18:14:05.496  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 18:14:05.496  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 18:14:05.496  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 18:14:05.496  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 18:14:05.496  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-12 18:14:05.496  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 18:14:05.496  6917  6940 D BtGatt.ScanManager: handling starting scan
,09-12 18:14:05.496  1014  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 18:14:05.496  1014  1126 E WifiStateMachine: VerifyingLinkState enter
,09-12 18:14:05.496  6917  6935 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 18:14:05.496  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.496  6917  6940 D BtGatt.ScanManager: allow scan with filters
,09-12 18:14:05.496  6917  6940 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 18:14:05.496  6917  6940 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 18:14:05.506  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:14:05.506  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 18:14:05.506  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 18:14:05.506  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.506  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.506  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-12 18:14:05.506  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:05.506  1014  1128 D ConnectivityService: Adding iface wlan0 to network 503
09-12 18:14:05.506  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
09-12 18:14:05.506  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 18:14:05.506  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 18:14:05.506  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.506  6917  6940 D BtGatt.ScanManager: Starting BLE batch scan
09-12 18:14:05.506  6917  6940 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 18:14:05.506  1014  1128 E ConnectivityService: updateNetworkInfo()
09-12 18:14:05.506  1014  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-12 18:14:05.516  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 18:14:05.526  1014  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-12 18:14:05.526  1014  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 18:14:05.526  1014  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 18:14:05.526  1014  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 18:14:05.526  1014  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 18:14:05.526  6917  6935 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 18:14:05.526  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.536  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 18:14:05.536  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 18:14:05.536  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.536  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.536  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.536  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.536  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.536  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.536  1014  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,09-12 18:14:05.536  1014  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,09-12 18:14:05.546  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 18:14:05.546  1014  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-12 18:14:05.546  1014  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,09-12 18:14:05.546  1014  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 18:14:05.546  1014  1128 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,09-12 18:14:05.546  1014  1128 D ConnectivityService: LTETest block dns file not exists
,09-12 18:14:05.546  1014  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,09-12 18:14:05.556  1014  1128 E ConnectivityService: updateNetworkInfo()
,09-12 18:14:05.556  6917  6940 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 67
,09-12 18:14:05.556  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:05.566  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:05.566  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.566  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.566  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:05.566  3742  3742 I Hs20UtilService: Starting #20
,09-12 18:14:05.566  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 18:14:05.566  3742  3757 I Hs20UtilService: Message received 5007
,09-12 18:14:05.566  1014  1128 E ConnectivityService: updateNetworkInfo()
09-12 18:14:05.566  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 18:14:05.566  1014  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,09-12 18:14:05.566  1014  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,09-12 18:14:05.566  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:05.566  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 18:14:05.566  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 18:14:05.566  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-12 18:14:05.566  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:05.566  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.566  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.566  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.566  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.566  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 18:14:05.566  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.566  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@250f2422 removed from the list
09-12 18:14:05.566  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.566  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0eeb3 removed from the list
09-12 18:14:05.566  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.566  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 18:14:05.566  1014  7013 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 18:14:05.566   278  1009 D EnterpriseController: uids 1000
09-12 18:14:05.566   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:14:05.566   278  1009 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,09-12 18:14:05.576  1014  1128 D ConnectivityService:    accepting network in place of null
,09-12 18:14:05.576  1014  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 18:14:05.576  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-12 18:14:05.576  1014  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 18:14:05.576  1014  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
09-12 18:14:05.576  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 18:14:05.576  1450  1450 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 18:14:05.576  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.576  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.576  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.576  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.576  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.576  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.576  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:14:05.576  1014  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-12 18:14:05.586  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 18:14:05.586  1014  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-12 18:14:05.586  1014  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-12 18:14:05.586  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 18:14:05.586  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:05.586  1014  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-12 18:14:05.586  1177  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 18:14:05.586  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 18:14:05.586  1014  1129 D Tethering: MasterInitialState.processMessage what=3
,09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 18:14:05.586  1014  1123 V NetworkStats: updateIfacesLocked()
09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.586  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
09-12 18:14:05.586  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c0eeb3 not in the list
09-12 18:14:05.586  3842  6266 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 18:14:05.586  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.586  6917  6936 D BtGatt.GattService: stopScan() - queue size =1
09-12 18:14:05.586  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:05.586  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:05.586  6917  6940 D BtGatt.ScanManager: filter size is 1
09-12 18:14:05.586  6917  6940 D BtGatt.ScanManager: delete FilterIndex - 5
09-12 18:14:05.586  6917  6926 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 18:14:05.586  6917  6935 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
09-12 18:14:05.586  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 18:14:05.586  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 18:14:05.586  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 18:14:05.586  6917  6940 D BtGatt.ScanManager: stopping BLe Batch,
09-12 18:14:05.596  1014  1123 V NetworkStats: performPollLocked() took 7ms
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,09-12 18:14:05.596  1014  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 18:14:05.596  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0,
09-12 18:14:05.596  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.596  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 18:14:05.596  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 18:14:05.596  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
09-12 18:14:05.596  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-12 18:14:05.596  6917  6935 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 18:14:05.596  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.596  6917  6940 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 18:14:05.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 18:14:05.596  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.596  6917  6935 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 18:14:05.596  6917  6935 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 18:14:05.596  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:05.596  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 18:14:05.596  6205  6257 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 18:14:05.596  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:14:05.596  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.596  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.606  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 18:14:05.606  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 18:14:05.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.606  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.616  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@41f606e removed from the list
09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.616  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.616  6205  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.616  6205  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ddbabe9 removed from the list
,09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33e5157a added. We now have 2 listener(s)
09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.616  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b71812b added. We now have 9 listener(s)
09-12 18:14:05.616  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.616  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 18:14:05.616  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:05.616  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:05.626  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:05.626  6205  6257 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:05.626  6205  6257 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 18:14:05.626  6205  6257 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 18:14:05.626  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 18:14:05.626  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1053ef21 added. We now have 3 listener(s)
,09-12 18:14:05.636  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 18:14:05.636  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 18:14:05.636  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1f0f46 added. We now have 10 listener(s)
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 18:14:05.636  6205  6257 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 18:14:05.636  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 18:14:05.636  6205  6257 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.636  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.636  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33e5157a removed from the list
09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.636  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b71812b removed from the list
,09-12 18:14:05.636  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 18:14:05.636  6205  6257 D io.jxcore.node.ConnectivityMonitor: stop
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.636  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.636  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.636  6205  6257 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b71812b not in the list
09-12 18:14:05.636  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.636  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 18:14:05.636  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 18:14:05.636  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:05.646  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 18:14:05.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 18:14:05.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 18:14:05.646  6205  6257 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1f0f46 removed from the list
09-12 18:14:05.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 18:14:05.646  6205  6257 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 18:14:05.646  6205  6257 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 18:14:05.646  6205  6257 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 18:14:05.646  6205  6257 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1053ef21 removed from the list
,09-12 18:14:05.646  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 18:14:05.646  6205  6257 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything,
,09-12 18:14:05.646  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:05.646  3742  3742 I Hs20UtilService: Starting #21
,09-12 18:14:05.646  3742  3757 I Hs20UtilService: Message received 5007
,09-12 18:14:05.646  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 18:14:05.646  1299  1299 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 18:14:05.646  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,09-12 18:14:05.656  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 18:14:05.656  1299  1299 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-12 18:14:05.656  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 18:14:05.656  6205  7053 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1181, name: My test thread name)
,09-12 18:14:05.656  6205  7053 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1181, thread name: My test thread name)
09-12 18:14:05.656  6205  7053 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1181, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 18:14:05.656  6205  7054 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1183, name: My test thread name)
,09-12 18:14:05.666  6205  7054 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1183, thread name: My test thread name)
09-12 18:14:05.666  6205  7054 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 18:14:05.666  1014  1326 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 18:14:05.666  1014  1326 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 18:14:05.666  1014  1326 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:05.666  1014  1326 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:05.666  1014  1326 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 18:14:05.666  3742  3742 I Hs20UtilService: Starting #22
09-12 18:14:05.666  6205  6257 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 18:14:05.666  6205  6257 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 18:14:05.666  6205  6257 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 18:14:05.666  6205  6257 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 18:14:05.666  6205  6257 D com.test.thalitest.ThaliTestRunner: Total duration: 24346 ms
,09-12 18:14:05.666  3742  3757 I Hs20UtilService: Message received 5007
,09-12 18:14:05.666  6205  6257 I jxcore-log: *Native tests were executed*
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.666  6205  6257 I jxcore-log: Total number of executed tests:  80
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.666  6205  6257 I jxcore-log: Number of passed tests:  80
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.666  6205  6257 I jxcore-log: Number of failed tests:  0
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.666  6205  6257 I jxcore-log: Number of ignored tests:  0
09-12 18:14:05.666  6205  6257 I jxcore-log: 
,09-12 18:14:05.666  6205  6257 I jxcore-log: Total duration:  24346
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.666  6205  6257 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 18:14:05.666  6205  6257 I jxcore-log: 
,09-12 18:14:05.666  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.666  6205  6257 I jxcore-log: 
09-12 18:14:05.676  1299  1299 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 18:14:05.676  1299  1299 I NearbySettings: MountReceiver.onReceive - Keep current state
09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
,09-12 18:14:05.676  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.676  6205  6257 I jxcore-log: 
09-12 18:14:05.676  6205  6205 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-12 18:14:05.686  1014  3307 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  1014  3304 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-12 18:14:05.686  1014  3304 D SecContentProvider2: mCursor = null
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  1014  1312 D SecContentProvider2: uri = 15 selection = getToastGravity
09-12 18:14:05.686  1014  1312 D SecContentProvider2: mCursor = null
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  1014  1559 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-12 18:14:05.686  1014  1559 D SecContentProvider2: mCursor = null
,09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
09-12 18:14:05.686  1014  1485 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
,09-12 18:14:05.686  1014  1485 D SecContentProvider2: mCursor = null
09-12 18:14:05.686  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.686  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
09-12 18:14:05.696  1014  1555 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-12 18:14:05.696  1014  1555 D SecContentProvider2: mCursor = null
09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
09-12 18:14:05.696  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:05.696  6205  6257 I jxcore-log: 
,09-12 18:14:05.696  1014  1326 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-12 18:14:05.696  1014  1326 D SecContentProvider2: mCursor = null
,09-12 18:14:05.726   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-12 18:14:05.736  1014  1492 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-12 18:14:05.756  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 18:14:05.766  6205  6205 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 18:14:05.766  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.766  6205  6257 I jxcore-log: 
,09-12 18:14:05.776  1014  7013 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 18:14:05.866  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 16:14:05 GMT], X-Android-Received-Millis=[1473696845879], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473696845810]}
09-12 18:14:05.866  1014  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
09-12 18:14:05.866  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-12 18:14:05.866  1014  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
09-12 18:14:05.866  1014  7013 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 18:14:05.866  1014  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
09-12 18:14:05.866  1177  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:14:05.866  1014  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
09-12 18:14:05.866  3842  6266 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 18:14:05.866  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: updateDataNetType()
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,09-12 18:14:05.876  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 18:14:05.876  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.876  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 18:14:05.916  6205  6205 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-12 18:14:05.916  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:05.916  6205  6257 I jxcore-log: 
,09-12 18:14:05.926  7055  7055 D AndroidRuntime: ,
09-12 18:14:05.926  7055  7055 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 18:14:05.926  7055  7055 D AndroidRuntime: CheckJNI is OFF
,09-12 18:14:05.926  7055  7055 D AndroidRuntime: readGMSProperty: start,
09-12 18:14:05.926  7055  7055 D AndroidRuntime: readGMSProperty: already setted!!
09-12 18:14:05.926  7055  7055 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 18:14:05.926  7055  7055 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,09-12 18:14:05.926  7055  7055 D AndroidRuntime: readGMSProperty: end
09-12 18:14:05.926  7055  7055 D AndroidRuntime: addProductProperty: start
,09-12 18:14:06.076  7055  7055 E AffinityControl: AffinityControl: registerfunction enter
,09-12 18:14:06.076  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:06.096  1014  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:06.106  3208  3208 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-12 18:14:06.106  7055  7055 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 18:14:06.116  6525  6525 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 18:14:06.126  6205  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 18:14:06.126  6508  6508 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-12 18:14:06.126  6508  6508 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 18:14:06.126  6508  6508 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 18:14:06.126  6508  6508 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:06.126  1014  1485 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-12 18:14:06.136  6205  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 18:14:06.126  1014  1485 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-12 18:14:06.136  6205  6205 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 18:14:06.136  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 18:14:06.136  6205  6257 I jxcore-log: 
,09-12 18:14:06.136  6205  6257 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 18:14:06.136  6205  6257 I jxcore-log: 
09-12 18:14:06.136  6525  6525 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-12 18:14:06.136  1014  1027 D PackageManager: START PACKAGE DELETE: observer{963356659}
09-12 18:14:06.136  1014  1027 D PackageManager: pkg{<packageName>}
09-12 18:14:06.136  1014  1027 D PackageManager: user{0}
09-12 18:14:06.136  1014  1027 D PackageManager: caller{2000}
09-12 18:14:06.136  1014  1027 D PackageManager: flags{2}
09-12 18:14:06.136  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-12 18:14:06.136  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-12 18:14:06.136  1014  1027 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-12 18:14:06.136  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 18:14:06.136  1014  1027 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-12 18:14:06.146  1014  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-12 18:14:06.146  1014  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-12 18:14:06.146  1014  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-12 18:14:06.146  1014  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-12 18:14:06.146  1014  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-12 18:14:06.146  1725  1725 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:14:06.146  1014  1056 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-12 18:14:06.146  1014  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-12 18:14:06.146  1014  1041 I ActivityManager: Killing 6205:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
09-12 18:14:06.156  1014  1041 I ActivityManager:   Force finishing activity ActivityRecord{16d2a0c0 u0 com.test.thalitest/.MainActivity t128}
,09-12 18:14:06.156  6540  6540 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-12 18:14:06.156  1014  1492 D RCPManagerService: exchangeData() failure , invalid userId
09-12 18:14:06.156  1014  1041 W ActivityManager: mDVFSHelper.acquire()
,09-12 18:14:06.156  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 18:14:06.256  1014  1217 I WindowState: WIN DEATH: Window{3b5d7f20 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 18:14:06.256   258  1037 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,09-12 18:14:06.256   258  1036 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-12 18:14:06.266  1014  1217 D InputDispatcher: Focus left window: 6205
09-12 18:14:06.266   258  1036 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-12 18:14:06.276  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 18:14:06.276  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:14:06.276  3208  3208 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-12 18:14:06.276  1725  1725 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-12 18:14:06.276  1725  1725 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-12 18:14:06.276  1725  1725 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-12 18:14:06.276  1725  1725 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 18:14:06.286  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 18:14:06.286  6540  6540 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-12 18:14:06.296  6540  6540 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-12 18:14:06.296  1014  1041 D InputDispatcher: Focused application released
,09-12 18:14:06.296  6540  6540 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-12 18:14:06.306  1014  1056 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-12 18:14:06.306  1320  1749 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,09-12 18:14:06.306  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-12 18:14:06.316  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-12 18:14:06.316  3208  3208 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-12 18:14:06.336  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-12 18:14:06.336  1014  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 18:14:06.346  3208  3208 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-12 18:14:06.346  3208  3208 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-12 18:14:06.356  5684  5684 I art     : Explicit concurrent mark sweep GC freed 16604(953KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 6MB/11MB, paused 772us total 36.665ms
,09-12 18:14:06.376  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 18:14:06.396  5475  5475 I art     : Explicit concurrent mark sweep GC freed 389(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 744us total 72.005ms
,09-12 18:14:06.396  3842  3842 I art     : Explicit concurrent mark sweep GC freed 23739(1428KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.969ms total 90.909ms
,09-12 18:14:06.396  1787  1787 E SamsungIME: mOCRHelper is null
,09-12 18:14:06.416  1725  1725 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-12 18:14:06.426  1437  1437 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.436  1014  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-12 18:14:06.436  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:06.436  1014  1123 V NetworkStats: performPollLocked(flags=0x3)
09-12 18:14:06.436  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-12 18:14:06.436  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 18:14:06.436  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 18:14:06.436  1014  1123 V NetworkStats: performPollLocked() took 4ms
09-12 18:14:06.436  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:06.446  1437  1437 D RegisteredServicesCache: empty dynamic service
,09-12 18:14:06.476  1437  1437 D RegisteredComponentCache: Collect Tech packages for Knox
,09-12 18:14:06.476  1014  3304 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-12 18:14:06.476  1014  3304 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-12 18:14:06.486  1437  1437 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.486  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 18:14:06.486  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-12 18:14:06.496  3208  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-12 18:14:06.496  3208  3208 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-12 18:14:06.496  3208  3208 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-12 18:14:06.496  1014  3307 I art     : Explicit concurrent mark sweep GC freed 84681(4MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 28MB/43MB, paused 4.280ms total 217.567ms
,09-12 18:14:06.496  1014  3307 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-12 18:14:06.496  1014  3307 D SecContentProvider2: mCursor = null
09-12 18:14:06.506  1014  1014 I art     : WaitForGcToComplete blocked for 163.473ms for cause Explicit
,09-12 18:14:06.506  3208  3208 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-12 18:14:06.506  1904  2100 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 18:14:06.506  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 18:14:06.506  6477  6477 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 18:14:06.506  6477  6477 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 18:14:06.516  1014  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
09-12 18:14:06.516  1014  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-12 18:14:06.516  1014  1040 W TextServicesManagerService: no available spell checker services found
,09-12 18:14:06.516  6477  6477 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 18:14:06.526  1725  1725 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 18:14:06.526  1725  1725 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-12 18:14:06.536  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 18:14:06.536  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 18:14:06.536  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.536  1014  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 18:14:06.536  1014  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 18:14:06.536  1014  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 18:14:06.546  3208  3208 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-12 18:14:06.556   258   258 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-12 18:14:06.556  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 18:14:06 GMT+02:00 2016
,09-12 18:14:06.566  1014  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-12 18:14:06.566  1014  1138 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 18:14:06.566  1014  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.566  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.566  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.576  1014  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:06.576  1014  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:06.576  1014  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 18:14:06.576  1014  3308 D InputDispatcher: Focus entered window: 3208
,09-12 18:14:06.576  3208  3208 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 18:14:06.576  1014  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 18:14:06.576  1014  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 18:14:06.586  1014  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 18:14:06.586  3208  3208 V ActivityThread: updateVisibility : ActivityRecord{3894d25 token=android.os.BinderProxy@33c62da0 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-12 18:14:06.596  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 18:14:06.606  1014  1026 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 18:14:06.616  1014  1026 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6205 uid 10155
,09-12 18:14:06.616  6717  6717 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:06.616  6717  6717 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-12 18:14:06.616  6717  6717 I DIAGMON_AGENT: ./extraInfo: "NG700"
09-12 18:14:06.616  6717  6717 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-12 18:14:06.626  1014  7070 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 18:14:06.626  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 18:14:06.626  3208  3208 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33c62da0 time:150567
,09-12 18:14:06.636  1014  1046 W ActivityManager: mDVFSHelper.release()
09-12 18:14:06.636  1014  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{eb9f357 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:150571
,09-12 18:14:06.636  1787  1787 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-12 18:14:06.636  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-12 18:14:06.636  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.646  3761  3761 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 18:14:06.646  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:06.646  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:06.646  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-12 18:14:06.666  3761  3761 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 18:14:06.666  3761  7069 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 18:14:06.666  3761  7069 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-12 18:14:06.676  1014  1014 I art     : Explicit concurrent mark sweep GC freed 11976(1127KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 3.237ms total 178.708ms
,09-12 18:14:06.686  1014  1056 I art     : WaitForGcToComplete blocked for 253.298ms for cause Explicit
,09-12 18:14:06.696  1014  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 18:14:06.696  3761  7069 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-12 18:14:06.696  3761  7069 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-12 18:14:06.696  3761  7069 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-12 18:14:06.706  1014  1312 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 18:14:06.706  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 18:14:06.706  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.706  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.706  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 18:14:06.706  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 18:14:06.716  1014  3305 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-12 18:14:06.726  1014  3305 D SecContentProvider2: mCursor = null
,09-12 18:14:06.726  3761  7069 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-12 18:14:06.726  3761  7069 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-12 18:14:06.726   278  1009 D EnterpriseController: uids 10012
09-12 18:14:06.726   278  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 18:14:06.726   278  1009 D Netd    : getNetworkForDns: using netid 503 for uid 10012
,09-12 18:14:06.736  3842  3842 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 18:14:06.736  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 18:14:06.746  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.766  3842  4593 I iu.UploadsManager: num queued entries: 0
,09-12 18:14:06.766  3842  4593 I iu.UploadsManager: num updated entries: 0
,09-12 18:14:06.766  3842  4593 I iu.SyncManager: NEXT; no task
,09-12 18:14:06.786  5923  5923 D WaitQueueForNetworkActivate: notifyNetworkActivated
,09-12 18:14:06.796  6771  6771 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 18:14:06.796  3324  7081 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-12 18:14:06.796  3324  7081 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-12 18:14:06.796  3324  7081 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-12 18:14:06.806  6771  6771 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-12 18:14:06.806  6771  6771 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-12 18:14:06.806  6612  6612 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-12 18:14:06.826  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.826  5985  5985 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-12 18:14:06.836  5985  5985 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-12 18:14:06.836  5985  5985 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 18:14:06.846  5985  5985 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-12 18:14:06.846  5985  5985 I SA      : [OR] == isSIMCardReady false ==
,09-12 18:14:06.846  5985  5985 I SA      : [SCU] == networkStateCheck == true
,09-12 18:14:06.846  5985  5985 I SA      : [DM] getCountryCodeFromCSC : PL
09-12 18:14:06.846  5985  5985 I SA      : isChinaCountryCode : false
09-12 18:14:06.846  5985  5985 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-12 18:14:06.846  5985  5985 I SA      : [OR] == networkStateCheck true ==
,09-12 18:14:06.856  5985  5985 I SA      : [OR] GetMyCountryZoneTask
09-12 18:14:06.856  5985  5985 I SA      : [OR] onReceive END
09-12 18:14:06.856  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
09-12 18:14:06.856  1014  1217 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-12 18:14:06.856  1014  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
09-12 18:14:06.866  5985  7086 I SA      : [SRS] prepareGetMyCountryZone
,09-12 18:14:06.866  1014  1217 W ActivityManager: userId = 0, bbcId = -10000
09-12 18:14:06.866  1014  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:06.866  1014  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-12 18:14:06.876  3324  7081 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-12 18:14:06.876  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-12 18:14:06.876  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-12 18:14:06.876  1014  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 18:14:06.876  1014  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:14:06.876  1014  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 18:14:06.876  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-12 18:14:06.886  1904  7077 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} for uid -1, pid: 1904, getuid(): 10012
,09-12 18:14:06.886  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-12 18:14:06.886  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-12 18:14:06.886  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-12 18:14:06.886  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.896  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-12 18:14:06.896  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,09-12 18:14:06.896  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-12 18:14:06.896  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
09-12 18:14:06.896  3324  7081 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
09-12 18:14:06.896  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-12 18:14:06.896  1014  1485 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-12 18:14:06.896  1014  1485 D SecContentProvider2: mCursor = null
,09-12 18:14:06.906  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-12 18:14:06.906  5985  7086 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-12 18:14:06.906  5985  7086 I SA      : [SSP] query invoked
,09-12 18:14:06.906  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
09-12 18:14:06.906  3324  7081 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-12 18:14:06.906  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-12 18:14:06.906  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 18:14:06.906  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 18:14:06.906  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 18:14:06.906  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 18:14:06.916  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 18:14:06.916  1014  2749 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-12 18:14:06.916  3324  7081 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
09-12 18:14:06.916  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-12 18:14:06.916  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 18:14:06.916  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 18:14:06.926  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-12 18:14:06.926  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-12 18:14:06.926  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-12 18:14:06.936  1177  1177 D PanelView: There is/are notification(s) 
,09-12 18:14:06.936  3324  7081 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-12 18:14:06.936  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.946  5985  7086 I SA      : [TPMU] GetMccFromDB : null
09-12 18:14:06.946  5985  7086 I SA      : [SCU] getMccFromPreferece mcc = 260
09-12 18:14:06.946  5985  7086 I SA      : [LBE] isSupportCheckDomainRegion : false
09-12 18:14:06.946  5985  7086 I SA      : [TPM] isNoProxy(default) : true
,09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.946  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.956  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 18:14:06.956  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 18:14:06.956  1014  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 18:14:06.956  1014  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-12 18:14:06.956  1014  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-12 18:14:06.966  5985  7086 E File    : fail readDirectory() errno=2
,09-12 18:14:06.976  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-12 18:14:06.976  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.976  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.976  1177  1177 D PanelView: There is/are notification(s) 
,09-12 18:14:06.976  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 18:14:06.986  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:06.986  1177  1177 D PanelView: There is/are notification(s) 
,09-12 18:14:06.986  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 18:14:07.006  1014  1056 I art     : Explicit concurrent mark sweep GC freed 11896(702KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 3.290ms total 322.201ms
,09-12 18:14:07.036  1014  1056 D PackageManager: delete codoeFile: 
,09-12 18:14:07.056  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-12 18:14:07.056  1014  1056 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-12 18:14:07.056  1014  1312 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
09-12 18:14:07.056  1014  1056 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-12 18:14:07.056  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-12 18:14:07.056  1014  1056 D PackageManager: result of delete: 1{963356659}
,09-12 18:14:07.056  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:07.056  1014  1312 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 18:14:07.066  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-12 18:14:07.066  1014  1041 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-12 18:14:07.076  5923  5923 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
09-12 18:14:07.076  7055  7055 D AndroidRuntime: Shutting down VM
,09-12 18:14:07.076  5923  5923 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: exit::IDLE
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-12 18:14:07.076  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 18:14:07 GMT+02:00 2016
,09-12 18:14:07.076  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-12 18:14:07.076  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-12 18:14:07.076  5923  5923 D InitializeManagerStateMachine: entry::SUCCESS
09-12 18:14:07.076  5923  5923 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-12 18:14:07.076  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:07.076  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:07.076  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 18:14:07.086  3761  3761 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 18:14:07.086  1014  1138 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-12 18:14:07.086  1014  1138 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 18:14:07.086  1014  1138 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 18:14:07.086  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.086  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.086  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.086  1014  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.096  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 18:14:07.096  3761  3761 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 18:14:07.106  3761  3761 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-12 18:14:07.106  7093  7093 E Zygote  : MountEmulatedStorage()
09-12 18:14:07.106  7093  7093 E Zygote  : v2
09-12 18:14:07.106  7093  7093 I libpersona: KNOX_SDCARD checking this for 10094
09-12 18:14:07.106  7093  7093 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:07.106  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 18:14:07.106  7093  7093 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:14:07.116  1014  1138 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7093 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,09-12 18:14:07.116  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
09-12 18:14:07.116  7093  7093 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:14:07.116  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-12 18:14:07.116  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.116  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.116  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.116  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.116  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
09-12 18:14:07.116  7093  7093 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:07.126  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-12 18:14:07.136  6917  6933 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 18:14:07.146  7102  7102 E Zygote  : MountEmulatedStorage()
09-12 18:14:07.146  7102  7102 E Zygote  : v2
09-12 18:14:07.146  7102  7102 I libpersona: KNOX_SDCARD checking this for 10044
09-12 18:14:07.146  7102  7102 I libpersona: KNOX_SDCARD not a persona
09-12 18:14:07.146  7102  7102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:14:07.146  1014  1041 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7102 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-12 18:14:07.146  7102  7102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 18:14:07.146  7102  7102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 18:14:07.146  1014  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-12 18:14:07.146  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.146  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.146  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.146  1014  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.156  7093  7093 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.156  7093  7093 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:07.176  7123  7123 E Zygote  : MountEmulatedStorage()
09-12 18:14:07.176  7123  7123 E Zygote  : v2
09-12 18:14:07.176  7123  7123 I libpersona: KNOX_SDCARD checking this for 10149
09-12 18:14:07.176  7123  7123 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:07.176  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:14:07.176  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:14:07.176  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:07.186  1014  1041 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7123 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 18:14:07.186  7102  7102 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.186  7102  7102 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:07.186  5923  5923 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-12 18:14:07.186  5923  5923 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-12 18:14:07.196  5923  5923 D InitializeManagerStateMachine: exit::SUCCESS
,09-12 18:14:07.196  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.196  7123  7123 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:07.216  5923  5923 D InitializeManagerStateMachine: entry::IDLE
,09-12 18:14:07.236  7102  7102 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 18:14:07.246  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 18:14:07.246  6898  7116 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 18:14:07.246  7102  7102 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 18:14:07.246  7093  7093 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-12 18:14:07.256  7093  7093 D elm:15183: ELMEngine.ELMEngine( context ).
,09-12 18:14:07.256  3761  7092 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 18:14:07.256  7093  7093 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-12 18:14:07.256  3761  7092 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 18:14:07.256  1014  1492 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-12 18:14:07.256  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-12 18:14:07.256  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:07.256  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 18:14:07.256  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 18:14:07.266  3761  3761 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 18:14:07.276  7123  7123 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-12 18:14:07.276  7123  7123 D ThemeInfoUtil: isCurrentFestival = false
,09-12 18:14:07.276  7093  7093 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 18:14:07.276  1014  1561 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-12 18:14:07.286  7055  7055 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-12 18:14:07.286  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.286  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.286  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.286  1014  1561 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.286  6898  6898 I art     : Explicit concurrent mark sweep GC freed 767(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 726us total 52.620ms
,09-12 18:14:07.296  7093  7093 D elm:15183: ElmAgentService : onCreate()
,09-12 18:14:07.296  7093  7139 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-12 18:14:07.296  7093  7139 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-12 18:14:07.296  7093  7139 D elm:15183: MDMBridge.getInstance()
09-12 18:14:07.296  7093  7139 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 18:14:07.296  7140  7140 E Zygote  : MountEmulatedStorage(),
09-12 18:14:07.296  7140  7140 E Zygote  : v2
09-12 18:14:07.296  7140  7140 I libpersona: KNOX_SDCARD checking this for 10152
09-12 18:14:07.296  7140  7140 I libpersona: KNOX_SDCARD not a persona,
,09-12 18:14:07.306  1014  1561 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7140 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-12 18:14:07.306  7093  7139 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK(),
,09-12 18:14:07.306  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-12 18:14:07.306  3459  3459 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
09-12 18:14:07.306  3459  3459 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-12 18:14:07.306  3459  3459 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,09-12 18:14:07.306  3459  3459 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-12 18:14:07.306  3459  3459 W System.err: ,	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 18:14:07.306  3459  3459 W System.err: ,	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
,09-12 18:14:07.306  3459  3459 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 18:14:07.306  3459  3459 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 18:14:07.306  3459  3459 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-12 18:14:07.306  3459  3459 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 18:14:07.306  3459  3459 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-12 18:14:07.306  3459  3459 W System.err: ,	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 18:14:07.306  3459  3459 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399),
09-12 18:14:07.316  1014  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-12 18:14:07.316  1014  1056 D PackageManager: userId{-1}
09-12 18:14:07.316  1014  1056 D PackageManager: andCode{true}
,09-12 18:14:07.306  3459  3459 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 18:14:07.316  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:14:07.316  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:07.326  1014  1217 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-12 18:14:07.326  5965  5978 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-12 18:14:07.326  5965  5978 D BadgeProvider: sendNotify, [notify] : null
,09-12 18:14:07.326  5965  5978 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-12 18:14:07.326  5965  5978 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 18:14:07.326  5965  5978 D BadgeProvider: update, [UpdateCount] : 1
,09-12 18:14:07.336  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.336  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.336  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-12 18:14:07.336  1014  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.336  1476  1476 D Launcher.Model: reloadBadges entered.
,09-12 18:14:07.336  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.346  7140  7140 D ActivityThread: Added TimaKeyStore provider,
,09-12 18:14:07.356  7160  7160 E Zygote  : MountEmulatedStorage()
09-12 18:14:07.366  7160  7160 E Zygote  : v2
09-12 18:14:07.366  1014  1217 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7160 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 18:14:07.366  7160  7160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 18:14:07.366  1014  1217 I ActivityManager: Killing 5475:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
09-12 18:14:07.366  7160  7160 I libpersona: KNOX_SDCARD checking this for 1000
09-12 18:14:07.366  7160  7160 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:07.366  7160  7160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 18:14:07.366  7093  7093 D elm:15183: ElmAgentService : onDestroy().
09-12 18:14:07.366  1014  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-12 18:14:07.366  7160  7160 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:07.396  6508  6508 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-12 18:14:07.396  6508  6508 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 18:14:07.396  6508  6508 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 18:14:07.396  6508  6508 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-12 18:14:07.406  7160  7160 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.406  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-12 18:14:07.406  7160  7160 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:07.406  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.406  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.406  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.406  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 18:14:07.426  1014  1027 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7178 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
,09-12 18:14:07.426  7178  7178 E Zygote  : MountEmulatedStorage()
09-12 18:14:07.426  7178  7178 E Zygote  : v2
,09-12 18:14:07.426  7178  7178 I libpersona: KNOX_SDCARD checking this for 10032
09-12 18:14:07.426  7178  7178 I libpersona: KNOX_SDCARD not a persona
,09-12 18:14:07.436  7178  7178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 18:14:07.436  7178  7178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 18:14:07.436  7178  7178 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 18:14:07.446  1014  1027 I ActivityManager: Killing 6143:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-12 18:14:07.456  7178  7178 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 18:14:07.456  7178  7178 D ActivityThread: Added TimaKeyStore provider
,09-12 18:14:07.476  1014  1138 D PersonaManager: isKioskContainerExistOnDevice
,09-12 18:14:07.496  7160  7160 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-12 18:14:07.496  1014  1559 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-12 18:14:07.496  1014  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-12 18:14:07.496  1014  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-12 18:14:07.496  1014  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 18:14:07.496  1014  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu,
,09-12 18:14:07.506  1014  1555 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-12 18:14:07.506  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.506  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.506  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 18:14:07.506  1014  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
