#### Test 721454317367600_thali01_samsung-SM-A300FU Logs


```
--------- beginning of main
06-22 07:43:58.722   335   335 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-22 07:43:58.722   335   335 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-22 07:43:59.552  5941  5941 D AndroidRuntime: 
06-22 07:43:59.552  5941  5941 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-22 07:43:59.552  5941  5941 D AndroidRuntime: CheckJNI is OFF
06-22 07:43:59.552  5941  5941 D AndroidRuntime: readGMSProperty: start
06-22 07:43:59.552  5941  5941 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:43:59.552  5941  5941 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:43:59.552  5941  5941 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:43:59.552  5941  5941 D AndroidRuntime: readGMSProperty: end
06-22 07:43:59.552  5941  5941 D AndroidRuntime: addProductProperty: start
06-22 07:43:59.702  5941  5941 E AffinityControl: AffinityControl: registerfunction enter
06-22 07:43:59.722  5941  5941 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-22 07:43:59.732  1013  1495 E PersonaManagerService: inState():  stateMachine is null !!
06-22 07:43:59.732  1013  1495 I PersonaManagerService: PersonaId don't exist
06-22 07:43:59.732  1013  1495 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-22 07:43:59.742  1013  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:59.742   301   301 E SMD     : DCD OFF
--------- beginning of system
06-22 07:43:59.752  1013  1495 W ActivityManager: mDVFSHelper.acquire()
06-22 07:43:59.762  1013  1043 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-22 07:43:59.762  1013  1043 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-22 07:43:59.762  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:59.762  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:59.762  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:59.762  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:43:59.782  5952  5952 E Zygote  : MountEmulatedStorage()
06-22 07:43:59.782  5952  5952 E Zygote  : v2
06-22 07:43:59.782  5952  5952 I libpersona: KNOX_SDCARD checking this for 10151
06-22 07:43:59.782  5952  5952 I libpersona: KNOX_SDCARD not a persona
06-22 07:43:59.782  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-22 07:43:59.782  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-22 07:43:59.782   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
06-22 07:43:59.782  5952  5952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:43:59.782  5952  5952 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:43:59.782  5952  5952 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-22 07:43:59.792  1013  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
06-22 07:43:59.792  1013  1495 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5952 uid=10151 gids={50151, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-22 07:43:59.792  1013  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:43:59.792  1013  1495 D InputDispatcher: Focused application set to: xxxx
06-22 07:43:59.792  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:43:59.792  1013  1495 D InputDispatcher: Focus left window: 5145
06-22 07:43:59.802  5941  5941 D AndroidRuntime: Shutting down VM
06-22 07:43:59.812   321   321 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 26.133ms
06-22 07:43:59.822  5952  5952 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:43:59.822  5952  5952 D ActivityThread: Added TimaKeyStore provider
06-22 07:43:59.822  1013  1478 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-22 07:43:59.832  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:43:59.832  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
06-22 07:43:59.832  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-22 07:43:59.832   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 17.934ms
06-22 07:43:59.852   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.394ms
06-22 07:43:59.852  1013  1478 D PersonaManager: isKioskContainerExistOnDevice
06-22 07:43:59.862  5145  5145 V ActivityThread: updateVisibility : ActivityRecord{3f084880 token=android.os.BinderProxy@263b4f14 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : false
06-22 07:43:59.892   259   451 I SurfaceFlinger: id=9 Removed Mauncher (4/10)
06-22 07:43:59.892   259  1093 I SurfaceFlinger: id=9 Removed Mauncher (-2/10)
06-22 07:43:59.892   259   453 I SurfaceFlinger: id=11 Removed TettingsRec (5/9)
06-22 07:43:59.902   259   451 I SurfaceFlinger: id=11 Removed TettingsRec (-2/9)
06-22 07:43:59.902  1480  1480 D Launcher: onTrimMemory. Level: 20
06-22 07:43:59.902  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{32c99423 token=android.os.BinderProxy@32b8a771 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-22 07:43:59.952  5952  5952 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-22 07:43:59.962  5952  5952 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9886-9888)
06-22 07:43:59.962  5952  5952 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:59.982  5952  5952 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3bbe09a7}
06-22 07:43:59.982  5952  5952 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-22 07:43:59.982  5952  5952 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-22 07:43:59.992  1013  1091 V AlarmManager: waitForAlarm result :8
06-22 07:44:00.002  5941  5941 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-22 07:44:00.022  5952  5952 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-22 07:44:00.022  5952  5952 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:00.022  5952  5952 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-22 07:44:00.032  5952  5969 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-22 07:44:00.042  5952  5952 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-22 07:44:00.042  5952  5952 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,06-22 07:44:00.052  5952  5952 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,06-22 07:44:00.052  5952  5952 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-22 07:44:00.052  5952  5952 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-22 07:44:00.052  5952  5952 I Adreno-EGL: Build Date: 04/06/15 Mon
06-22 07:44:00.052  5952  5952 I Adreno-EGL: Local Branch: 
06-22 07:44:00.052  5952  5952 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-22 07:44:00.052  5952  5952 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-22 07:44:00.052  5952  5952 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,06-22 07:44:00.192  5952  5978 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,06-22 07:44:00.242  5952  5952 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:00.252  5952  5952 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,06-22 07:44:00.262  5952  5952 D PhoneWindow: *FMB* installDecor mIsFloating : false
,06-22 07:44:00.262  5952  5952 D PhoneWindow: *FMB* installDecor flags : -2139027200
,06-22 07:44:00.262  5952  5952 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,06-22 07:44:00.272  5952  5952 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:00.272  5952  5952 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-22 07:44:00.322  5952  5991 D OpenGLRenderer: Render dirty regions requested: true
,06-22 07:44:00.332  1013  1531 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-22 07:44:00.332  1013  1531 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:44:00.332  1013  1531 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:44:00.332  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-22 07:44:00.332  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,06-22 07:44:00.342  5952  5952 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-22 07:44:00.342  5952  5952 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,06-22 07:44:00.352   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,06-22 07:44:00.352  1013  1132 D InputDispatcher: Focus entered window: 5952
,06-22 07:44:00.362  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-22 07:44:00.362  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-22 07:44:00.362  5952  5952 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-22 07:44:00.362  5952  5991 I OpenGLRenderer: Initialized EGL, version 1.4
,06-22 07:44:00.372  5952  5991 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,06-22 07:44:00.372  5952  5991 D OpenGLRenderer: Enabling debug mode 0
,06-22 07:44:00.382  5952  5952 V ActivityThread: updateVisibility : ActivityRecord{17c0acee token=android.os.BinderProxy@f92b4f0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,06-22 07:44:00.412  1013  1530 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-22 07:44:00.422  5952  5952 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f92b4f0 time:110342
,06-22 07:44:00.422  1173  1173 I StatusBar: Icon Only
,06-22 07:44:00.422  1173  1173 D PanelView: There is/are notification(s) 
,06-22 07:44:00.422  1013  5994 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-22 07:44:00.422  5952  5952 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,06-22 07:44:00.472  1013  1043 I ActivityManager: Displayed Component not be shown by security: +615ms (total +711ms)
06-22 07:44:00.472  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{94b509c u0 com.test.thalitest/.MainActivity t81} time:110391
06-22 07:44:00.472  1013  1043 W ActivityManager: mDVFSHelper.release()
,06-22 07:44:00.472   259   451 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,06-22 07:44:00.472   259  1093 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,06-22 07:44:00.482  1920  1920 I SamsungIME: getCurrentCandidateView
,06-22 07:44:00.502  5952  5952 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5952
,06-22 07:44:00.582  1920  1920 D SamsungIME: Dismiss ExpandCandiate
,06-22 07:44:00.632  5952  5952 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,06-22 07:44:00.732  5952  5996 D jxcore_app_log: JniHelper::setJavaVM(0xb73b22f0), pthread_self() = -1215194168
,06-22 07:44:00.732  1920  1920 I SamsungIME: getDebugLevel  : 0x4f4c
,06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-22 07:44:00.752  5952  5996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a82d9e added. We now have 1 listener(s)
,06-22 07:44:00.752  5952  5996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,06-22 07:44:00.752  5952  5996 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,06-22 07:44:00.752  5952  5996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-22 07:44:00.762  5952  5996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-22 07:44:00.762  5952  5996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f927095 added. We now have 1 listener(s)
,06-22 07:44:00.762  5952  5996 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-22 07:44:00.772  5952  5996 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-22 07:44:00.772  5952  5996 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-22 07:44:00.772  5952  5996 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,06-22 07:44:00.782  5952  5996 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-22 07:44:00.782  5952  5996 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,06-22 07:44:00.782  5952  5996 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-22 07:44:00.782  5952  5996 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-22 07:44:00.782  1920  1920 I SamsungIME: getDebugLevel  : 0x4f4c
,06-22 07:44:00.782  5952  5996 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-22 07:44:00.792  1920  1920 I SamsungIME: KeybaordView init() : load resources
,06-22 07:44:00.812  5952  5952 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-22 07:44:00.822  1920  1920 I SamsungIME: getCurrentKeyboard
06-22 07:44:00.822  1920  1920 I SamsungIME: getTextKeyboard
,06-22 07:44:00.842  1920  1920 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-22 07:44:01.332  5952  6001 W jxcore-log: Initializing JXcore engine
06-22 07:44:01.332  5952  6001 W jxcore-log: JXcore engine is ready
,06-22 07:44:01.382  1919  1919 E audit   : type=1400 msg=audit(1466574241.382:203): avc:  denied  { ioctl } for  pid=6001 comm="Thread-1073" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-22 07:44:01.392  1919  1919 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:01.392  1919  1919 E audit   : type=1300 msg=audit(1466574241.382:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9f3008f8 items=0 ppid=321 ppcomm=main pid=6001 auid=4294967295 uid=10151 gid=10151 euid=10151 suid=10151 fsuid=10151 egid=10151 sgid=10151 fsgid=10151 ses=4294967295 tty=(none) comm="Thread-1073" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,06-22 07:44:01.392  1919  1919 E audit   : type=1320 msg=audit(1466574241.382:203): 
,06-22 07:44:01.402  5952  6001 W jxcore-log: Starting JXcore engine,
,06-22 07:44:01.502  5952  6001 W jxcore-log: Platform android
06-22 07:44:01.502  5952  6001 W jxcore-log: 
06-22 07:44:01.502  5952  6001 W jxcore-log: Process ARCH arm
06-22 07:44:01.502  5952  6001 W jxcore-log: 
,06-22 07:44:01.702  5952  6001 I jxcore-log: JXcore Cordova bridge is ready!
06-22 07:44:01.702  5952  6001 I jxcore-log: 
,06-22 07:44:01.702  5952  6001 W jxcore-log: JXcore engine is started
,06-22 07:44:01.702  5952  5996 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-22 07:44:01.712  5952  5952 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-22 07:44:01.722  5952  6001 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-22 07:44:01.722  5952  6001 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-22 07:44:01.722  5952  5952 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-22 07:44:01.722  5952  5952 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-22 07:44:01.722  1013  1530 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-22 07:44:01.732  1013  1530 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
06-22 07:44:01.732  1013  1530 D InputDispatcher: Focused application set to: xxxx
06-22 07:44:01.732  1013  1530 I ActivityManager: Killing 5554:com.google.android.partnersetup/u0a14 (adj 15): empty #21
06-22 07:44:01.742  5952  5952 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-22 07:44:01.742  5952  5952 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,06-22 07:44:01.742  5952  5952 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-22 07:44:01.742  5952  5952 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-22 07:44:01.742  5952  5952 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,06-22 07:44:01.742  5952  5952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-22 07:44:01.742  5952  5952 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32a82d9e removed from the list
06-22 07:44:01.742  5952  5952 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-22 07:44:01.742  5952  5952 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f927095 removed from the list
06-22 07:44:01.742  5952  5952 D io.jxcore.node.ConnectivityMonitor: stop
06-22 07:44:01.742  5952  5952 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-22 07:44:01.752  5952  5952 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-22 07:44:01.762   259   453 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,06-22 07:44:01.762   259  1093 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,06-22 07:44:01.762  1013  1477 D InputDispatcher: Focus left window: 5952,
,06-22 07:44:01.772  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-22 07:44:01.772  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-22 07:44:01.772  1013  1293 W ActivityManager: mDVFSHelper.acquire()
,06-22 07:44:01.782  5952  5952 E ViewRootImpl: sendUserActionEvent() mView == null
,06-22 07:44:01.802  1013  1026 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,06-22 07:44:01.812  1013  1495 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
06-22 07:44:01.812  1013  1495 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-22 07:44:01.812  1013  1495 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-22 07:44:01.812  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-22 07:44:01.812  1013  1013 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
06-22 07:44:01.812  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,06-22 07:44:01.812  1480  1480 D Launcher: onRestart, Launcher: 280467779
,06-22 07:44:01.812  1480  1480 D Launcher: onStart, Launcher: 280467779
,06-22 07:44:01.812  1480  1480 D Launcher.HomeView: onStart
,06-22 07:44:01.822  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{32c99423 token=android.os.BinderProxy@32b8a771 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,06-22 07:44:01.832   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,06-22 07:44:01.842  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-22 07:44:01.852  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-22 07:44:01.852   259   259 I SurfaceFlinger: id=15 createSurf (585x883),1 flag=4, TettingsRec
,06-22 07:44:01.852  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-22 07:44:01.852  1013  1477 D InputDispatcher: Focus entered window: 5145
,06-22 07:44:01.862  5145  5145 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-22 07:44:01.862  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-22 07:44:01.862  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-22 07:44:01.872  5145  5145 V ActivityThread: updateVisibility : ActivityRecord{3f084880 token=android.os.BinderProxy@263b4f14 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,06-22 07:44:01.892  5145  5145 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@263b4f14 time:111810
,06-22 07:44:01.892  1480  1480 D Launcher.HomeView: onStop
,06-22 07:44:01.912  1013  1043 W ActivityManager: mDVFSHelper.release()
,06-22 07:44:01.912  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{23ee6504 u0 com.android.settings/.SettingsReceiverActivity t80} time:111833
06-22 07:44:01.912  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{479eec7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t79} time:111833
,06-22 07:44:02.002  6004  6004 D AndroidRuntime: 
06-22 07:44:02.002  6004  6004 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,06-22 07:44:02.002  6004  6004 D AndroidRuntime: CheckJNI is OFF,
06-22 07:44:02.002  6004  6004 D AndroidRuntime: readGMSProperty: start
,06-22 07:44:02.002  6004  6004 D AndroidRuntime: readGMSProperty: already setted!!
06-22 07:44:02.002  6004  6004 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-22 07:44:02.002  6004  6004 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-22 07:44:02.002  6004  6004 D AndroidRuntime: readGMSProperty: end
06-22 07:44:02.002  6004  6004 D AndroidRuntime: addProductProperty: start,
,06-22 07:44:02.142  6004  6004 E AffinityControl: AffinityControl: registerfunction enter,
,06-22 07:44:02.172  6004  6004 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,06-22 07:44:02.182  1013  1495 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
06-22 07:44:02.182  1013  1495 D PackageManager: START PACKAGE DELETE: observer{694272256},
06-22 07:44:02.182  1013  1495 D PackageManager: pkg{<packageName>}
06-22 07:44:02.182  1013  1495 D PackageManager: user{0}
06-22 07:44:02.182  1013  1495 D PackageManager: caller{2000}
06-22 07:44:02.182  1013  1495 D PackageManager: flags{2}
06-22 07:44:02.182  1013  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-22 07:44:02.182  1013  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-22 07:44:02.182  1013  1495 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,06-22 07:44:02.182  1013  1053 D PackageManager: !@killApplicatoin: 10151, uninstall pkg
06-22 07:44:02.182  1013  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-22 07:44:02.182  1013  1495 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-22 07:44:02.182  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-22 07:44:02.182  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-22 07:44:02.182  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled,
06-22 07:44:02.182  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-22 07:44:02.182  1013  1038 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=-1: uninstall pkg
06-22 07:44:02.182  1013  1038 I ActivityManager: Killing 5952:com.test.thalitest/u0a151 (adj 9): stop com.test.thalitest cause uninstall pkg
,06-22 07:44:02.192  1013  1038 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:02.282  1013  1053 I ActivityManager: Force stopping com.test.thalitest appid=10151 user=0: pkg removed
,06-22 07:44:02.292  1013  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,06-22 07:44:02.332  5697  5697 I art     : Explicit concurrent mark sweep GC freed 22900(1192KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 783us total 38.234ms
,06-22 07:44:02.352  1013  1095 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-22 07:44:02.352  1920  1920 E SamsungIME: mOCRHelper is null
06-22 07:44:02.352  1515  1799 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-22 07:44:02.372  1013  1119 V NetworkStats: removeUidsLocked() for UIDs [10151]
06-22 07:44:02.372  1013  1119 V NetworkStats: performPollLocked(flags=0x3)
,06-22 07:44:02.372  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox updated
06-22 07:44:02.372  1013  1119 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,06-22 07:44:02.382  1013  1119 V NetworkStats: performPollLocked() took 15ms
,06-22 07:44:02.392  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:02.392  1440  1440 D RegisteredServicesCache: empty dynamic service
,06-22 07:44:02.402  3983  3983 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jun 22 07:44:02 GMT+02:00 2016
,06-22 07:44:02.402  1013  1495 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
06-22 07:44:02.402  1013  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.402  1013  1495 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.402  1013  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:02.402  1013  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-22 07:44:02.412  3983  3983 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,06-22 07:44:02.412  1013  1530 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
,06-22 07:44:02.422  1013  1530 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,06-22 07:44:02.422  1013  1530 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-22 07:44:02.422  1013  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.422  1013  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.422  1013  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.422  1013  1530 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.432  6020  6020 E Zygote  : MountEmulatedStorage(),
06-22 07:44:02.432  6020  6020 I libpersona: KNOX_SDCARD checking this for 10090
06-22 07:44:02.432  6020  6020 E Zygote  : v2
,06-22 07:44:02.432  6020  6020 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.432  6020  6020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:02.442  1013  1530 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6020 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,06-22 07:44:02.442  6020  6020 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:02.442  1013  1120 D NtpTrustedTime: forceRefresh() from cache miss
06-22 07:44:02.442  6020  6020 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.442   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:44:02.442   279  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-22 07:44:02.452  3983  3983 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,06-22 07:44:02.452   279  1008 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-22 07:44:02.452   279  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
06-22 07:44:02.452  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-22 07:44:02.452  1013  1120 D NtpTrustedTime: forceRefresh Fail.
,06-22 07:44:02.462  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.462  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.462  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.462  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.462  3983  3983 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-22 07:44:02.462  3983  3983 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,06-22 07:44:02.482  6036  6036 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.482  6036  6036 E Zygote  : v2
06-22 07:44:02.482  6036  6036 I libpersona: KNOX_SDCARD checking this for 10032
06-22 07:44:02.482  6036  6036 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.482  6036  6036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:02.482  6036  6036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:02.482  6036  6036 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.482  1013  1038 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=6036 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-22 07:44:02.482  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,06-22 07:44:02.492  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.492  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.492  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.492  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.502  6020  6020 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.502  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,06-22 07:44:02.502  6020  6020 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.502  6047  6047 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.502  6047  6047 E Zygote  : v2
06-22 07:44:02.502  6047  6047 I libpersona: KNOX_SDCARD checking this for 10052
06-22 07:44:02.502  6047  6047 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:02.502  1013  1038 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6047 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,06-22 07:44:02.502  6047  6047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:02.512  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,06-22 07:44:02.512  1013  1037 D EnterpriseDeviceManagerService: Package has changed for user 0
06-22 07:44:02.512  1013  1037 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-22 07:44:02.512  1013  1037 W TextServicesManagerService: no available spell checker services found
06-22 07:44:02.512  6047  6047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:02.512  6047  6047 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.512  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
06-22 07:44:02.522  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.522  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.522  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.522  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.522  1013  1013 I art     : Explicit concurrent mark sweep GC freed 45669(3MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 22MB/33MB, paused 2.982ms total 232.769ms
,06-22 07:44:02.532  6036  6036 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-22 07:44:02.532  6036  6036 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.532  6063  6063 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.532  6063  6063 I libpersona: KNOX_SDCARD checking this for 10098
06-22 07:44:02.532  6063  6063 E Zygote  : v2
06-22 07:44:02.532  6063  6063 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:02.532  1013  1053 I art     : WaitForGcToComplete blocked for 232.584ms for cause Explicit
06-22 07:44:02.532  6063  6063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:02.532  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START,
06-22 07:44:02.542  1013  1495 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-22 07:44:02.542  1013  1495 D SecContentProvider2: mCursor = null
,06-22 07:44:02.542  6063  6063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:02.542  6063  6063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.552  1013  1038 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6063 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,06-22 07:44:02.552  6047  6047 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:02.552  6047  6047 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.552  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,06-22 07:44:02.582  6063  6063 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.582  6063  6063 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.592  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,06-22 07:44:02.592  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:02.602  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,06-22 07:44:02.612  1013  1013 D RCPManagerService: PackageReceiver onReceive()
,06-22 07:44:02.622  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,06-22 07:44:02.622  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.622  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-22 07:44:02.622  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10151 container id = 0
,06-22 07:44:02.622  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,06-22 07:44:02.622  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
,06-22 07:44:02.642  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:02.652  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,06-22 07:44:02.652  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.652  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.652  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.652  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.652  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,06-22 07:44:02.672  6082  6082 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.672  6082  6082 E Zygote  : v2
06-22 07:44:02.672  6082  6082 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:02.672  6082  6082 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.672  6082  6082 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:02.672  1013  1478 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6082 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:44:02.672  6020  6020 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-22 07:44:02.672  6020  6020 D elm:15121: ELMEngine.ELMEngine( context ).
06-22 07:44:02.672  3983  6019 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,06-22 07:44:02.672  6082  6082 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:02.672  6020  6020 D elm:15121: MDMBridge.setEnterpriseBridge()
,06-22 07:44:02.672  6082  6082 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.682  3983  6019 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,06-22 07:44:02.692  1013  1495 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,06-22 07:44:02.692  1013  1495 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
06-22 07:44:02.692  1013  1495 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:02.692  1013  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,06-22 07:44:02.692  1013  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-22 07:44:02.702  1013  2721 D SSRM:n  : SIOP:: AP = 310
,06-22 07:44:02.702  6020  6020 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,06-22 07:44:02.712  6020  6020 D elm:15121: ElmAgentService : onCreate()
06-22 07:44:02.712  6082  6082 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.712  6020  6097 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-22 07:44:02.712  6020  6097 D elm:15121: MainReceiver.listeningToPackageRemoved()
06-22 07:44:02.712  6020  6097 D elm:15121: MDMBridge.getInstance()
06-22 07:44:02.712  6020  6097 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
06-22 07:44:02.712  6082  6082 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.712  6020  6097 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-22 07:44:02.722  3377  3377 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,06-22 07:44:02.722  3377  3377 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,06-22 07:44:02.722  3377  3377 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-22 07:44:02.722  3377  3377 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:02.722  3377  3377 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:02.722  3377  3377 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:02.722  3377  3377 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:02.722  3377  3377 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:02.722  3377  3377 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,06-22 07:44:02.732  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:02.732  6020  6020 D elm:15121: ElmAgentService : onDestroy().
,06-22 07:44:02.742  3983  3983 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,06-22 07:44:02.742   301   301 E SMD     : DCD OFF,
,06-22 07:44:02.762  1013  1132 I ActivityManager: Killing 5576:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,06-22 07:44:02.762  6036  6099 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-22 07:44:02.762  6036  6099 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,06-22 07:44:02.772  1013  1132 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,06-22 07:44:02.772  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.772  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.772  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.772  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.782  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.782  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicy: uID is 10151
06-22 07:44:02.782  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:44:02.782  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-22 07:44:02.792  6101  6101 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.792  6101  6101 E Zygote  : v2
06-22 07:44:02.792  6101  6101 I libpersona: KNOX_SDCARD checking this for 10032
06-22 07:44:02.792  6101  6101 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:02.792  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null,
06-22 07:44:02.792  6101  6101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:02.792  6036  6099 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.792  6036  6099 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.792  6036  6099 D SPPClientService: ============PushLog. stop!
,06-22 07:44:02.792  1013  1132 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6101 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:02.792  1013  1132 I ActivityManager: Killing 5605:com.sec.pcw.device/1000 (adj 15): empty #21
,06-22 07:44:02.802  6101  6101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:02.802  6101  6101 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.802  1013  1477 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-22 07:44:02.802  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.802  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.812  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.812  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,06-22 07:44:02.822  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicy: uID is 10151
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,06-22 07:44:02.822  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-22 07:44:02.822  1013  1013 V AlarmManagerEXT: com.test.thalitest(10151) is removed.
,06-22 07:44:02.822  1013  2721 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,06-22 07:44:02.832  1013  1053 I art     : Explicit concurrent mark sweep GC freed 16242(931KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/33MB, paused 6.549ms total 293.615ms
,06-22 07:44:02.832  6101  6101 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.832  6101  6101 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.842  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,06-22 07:44:02.842  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.842  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.842  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.842  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.852  6117  6117 E Zygote  : MountEmulatedStorage(),
,06-22 07:44:02.852  6117  6117 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:02.852  6117  6117 E Zygote  : v2
06-22 07:44:02.852  6117  6117 I libpersona: KNOX_SDCARD not a persona,
06-22 07:44:02.852  6117  6117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:02.862  1013  1478 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:44:02.862  1013  1478 I ActivityManager: Killing 5630:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
06-22 07:44:02.862  6117  6117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:02.872  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,06-22 07:44:02.872  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.872  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.872  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.872  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.872  6117  6117 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.882  6124  6124 E Zygote  : MountEmulatedStorage(),
06-22 07:44:02.882  6124  6124 I libpersona: KNOX_SDCARD checking this for 10055
06-22 07:44:02.882  6124  6124 E Zygote  : v2
06-22 07:44:02.882  6124  6124 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:02.882  6124  6124 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:02.892  1013  1026 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6124 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
06-22 07:44:02.892  6124  6124 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:02.892  6124  6124 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.892  1013  1158 D TaskPersister: removeObsoleteFile: deleting file=81_task.xml
06-22 07:44:02.892  1013  1158 D TaskPersister: removeObsoleteFile: deleting file=80_task.xml
,06-22 07:44:02.912  6117  6117 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.912  6124  6124 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:02.912  6124  6124 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.922  6047  6116 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-22 07:44:02.922  6117  6117 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:02.922  1588  1588 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
06-22 07:44:02.922  1588  1588 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,06-22 07:44:02.942  1013  1478 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,06-22 07:44:02.952  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.952  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.952  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:02.952  1013  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:02.952  6101  6148 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,06-22 07:44:02.952  6101  6148 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,06-22 07:44:02.962  1013  1478 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=6150 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-22 07:44:02.962  1013  1478 I ActivityManager: Killing 5655:com.android.mms/u0a41 (adj 15): empty #21
,06-22 07:44:02.962  1013  1132 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,06-22 07:44:02.962  1013  1037 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
06-22 07:44:02.962  1013  1132 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
,06-22 07:44:02.962  1013  1132 W ActivityManager: userId = 0, bbcId = -10000
,06-22 07:44:02.972  1013  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:02.972  6150  6150 E Zygote  : MountEmulatedStorage()
06-22 07:44:02.972  6150  6150 I libpersona: KNOX_SDCARD checking this for 10036,
06-22 07:44:02.972  6150  6150 E Zygote  : v2
06-22 07:44:02.972  6150  6150 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:02.972  6150  6150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:02.972  6124  6124 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
06-22 07:44:02.972  1013  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,06-22 07:44:02.972  6150  6150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:02.972  6150  6150 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-22 07:44:02.982  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:02.982  1013  1053 D PackageManager: delete codoeFile: 
06-22 07:44:02.992  1013  1053 D AASAuninstall: userId = 0, info.removedAppID = 10151, info.uid = 10151, packageName = com.test.thalitest
06-22 07:44:02.992  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:02.992  6101  6148 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.992  1013  1053 I AASA_removePackage: UID=10151 Target=com.test.thalitest
06-22 07:44:02.992  6101  6148 D SPPClientService: PushLog.txt file is not deleted.
06-22 07:44:02.992  6101  6148 D SPPClientService: ============PushLog. stop!
,06-22 07:44:03.002  1013  1053 D PackageManager: result of delete: 1{694272256}
,06-22 07:44:03.002  3258  3258 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
,06-22 07:44:03.002  3258  3258 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
06-22 07:44:03.002  3258  3258 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,06-22 07:44:03.002  3258  3258 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-22 07:44:03.002  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.002  3258  6158 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,06-22 07:44:03.002  6004  6004 D AndroidRuntime: Shutting down VM
,06-22 07:44:03.012  1013  1132 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-22 07:44:03.012  6150  6150 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:03.012  6150  6150 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:03.012  1013  1132 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.012  1013  1132 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.012  1013  1132 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.012  6117  6117 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,06-22 07:44:03.022  3258  6158 D AccountUtils: Clearing selected account for com.test.thalitest
,06-22 07:44:03.022  1013  1293 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
06-22 07:44:03.022  1013  1293 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,06-22 07:44:03.022  3258  3258 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
06-22 07:44:03.022  3258  3258 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
06-22 07:44:03.022  3258  3258 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
06-22 07:44:03.022  3258  3258 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,06-22 07:44:03.022  1013  1293 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.022  1013  1293 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:03.022  1013  1293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,06-22 07:44:03.022  1013  1037 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-22 07:44:03.022  1013  1037 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-22 07:44:03.022  1013  1037 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-22 07:44:03.022  1013  1479 D CountryDetector: No listener is left
,06-22 07:44:03.032  1013  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-22 07:44:03.032  1013  1053 D PackageManager: userId{-1}
06-22 07:44:03.032  1013  1053 D PackageManager: andCode{true}
,06-22 07:44:03.032  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.042  1013  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,06-22 07:44:03.042  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.052  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.052  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,06-22 07:44:03.052  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.052  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.052  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.052  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.052  6124  6124 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
06-22 07:44:03.052  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:03.052  6124  6124 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,06-22 07:44:03.052  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-22 07:44:03.052  6124  6124 D UserAnalysis: Create SecureDbHelper
06-22 07:44:03.062  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.062  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:03.062  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-22 07:44:03.062  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-22 07:44:03.062  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-22 07:44:03.062  6171  6171 E Zygote  : MountEmulatedStorage(),
06-22 07:44:03.062  6171  6171 E Zygote  : v2
,06-22 07:44:03.062  6171  6171 I libpersona: KNOX_SDCARD checking this for 1000
,06-22 07:44:03.072  6171  6171 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:03.072  6171  6171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:03.072  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-22 07:44:03.072  1013  1025 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6171 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:44:03.072  1013  1478 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-22 07:44:03.072  6171  6171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:03.072  1013  1478 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.072  1013  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.072  1013  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.072  6171  6171 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:44:03.072  1013  1037 D UsbSettingsManager: clearDefaults: com.test.thalitest
06-22 07:44:03.072  1013  1037 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,06-22 07:44:03.082  1013  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-22 07:44:03.092  6124  6124 D IntelligenceServiceApplication: onCreate()
,06-22 07:44:03.092  6124  6124 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,06-22 07:44:03.092  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.092  1013  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.092  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.102  6171  6171 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:03.102  6171  6171 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.102  1013  1530 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:03.102  1013  1530 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,06-22 07:44:03.102  1013  1530 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.102  1013  1530 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.102  1013  1530 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.112  1013  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,06-22 07:44:03.112  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.112  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.112  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.112  1013  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.112  6124  6124 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-22 07:44:03.122  6190  6190 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.122  6190  6190 E Zygote  : v2
06-22 07:44:03.122  6190  6190 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:03.122  6190  6190 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:03.122  6190  6190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:03.132  6150  6150 I SA      : [SSP] onCreated,
06-22 07:44:03.132  1013  1026 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6190 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:44:03.142  3258  6158 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest,
,06-22 07:44:03.142  6190  6190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-22 07:44:03.142  1013  1479 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
06-22 07:44:03.142  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,06-22 07:44:03.142  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.142  1013  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.142  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-22 07:44:03.142  6190  6190 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:03.142  1013  1531 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,06-22 07:44:03.152  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-22 07:44:03.162  3258  6188 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
06-22 07:44:03.162  3258  6188 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,06-22 07:44:03.162   321   321 I art     : Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 615us total 31.303ms,
,06-22 07:44:03.162  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-22 07:44:03.172  1013  1293 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-22 07:44:03.172  3258  6188 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
06-22 07:44:03.172  3258  6188 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,06-22 07:44:03.172  1013  1293 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.172  1013  1293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.172  1013  1293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.182   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 16.966ms
,06-22 07:44:03.182  1013  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:03.182  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
06-22 07:44:03.182  1013  1479 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.182  1013  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.182  1013  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.192  1013  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.192  1013  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.192  1013  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.192  1013  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.192  6150  6150 I SA      : [TPM] There is no property file
06-22 07:44:03.192  6171  6210 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,06-22 07:44:03.192  6171  6210 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,06-22 07:44:03.192  6190  6190 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:03.192  6190  6190 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.192  6150  6150 I SA      : [SCU] isHaveSA() - false
,06-22 07:44:03.202  6150  6150 I SA      : [TPM] getModelProperty : null
06-22 07:44:03.202  6150  6150 I SA      : [TPM] getCSCProperty : null
,06-22 07:44:03.202  6150  6150 I SA      : [DM] FLOATING AMOLED FEATURE: true
06-22 07:44:03.202  6150  6150 I SA      : [DM] PRODUCT AMOLED FEATURE: false
06-22 07:44:03.202  6150  6150 I SA      : [DM] TFT FEATURE: false
06-22 07:44:03.202   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 20.726ms
,06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
06-22 07:44:03.212  6004  6004 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
06-22 07:44:03.212  5914  5914 I art     : Explicit concurrent mark sweep GC freed 393(33KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 4MB/6MB, paused 690us total 52.251ms
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-22 07:44:03.212  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-22 07:44:03.222  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,06-22 07:44:03.222  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
06-22 07:44:03.222  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
06-22 07:44:03.222  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
06-22 07:44:03.222  6150  6150 I SA      : [DM] init START
06-22 07:44:03.222  6212  6212 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.222  6212  6212 E Zygote  : v2
06-22 07:44:03.222  6212  6212 I libpersona: KNOX_SDCARD checking this for 10011
06-22 07:44:03.222  6212  6212 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:03.222  5914  6189 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
06-22 07:44:03.222  6150  6150 I SA      : [DM] This device is not a Vodafone
06-22 07:44:03.222  6212  6212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:03.232  1013  1479 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6212 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
06-22 07:44:03.232  6212  6212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:03.232  1013  1495 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:44:03.232  6212  6212 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-22 07:44:03.232  1013  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
06-22 07:44:03.232  1013  1495 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.232  1013  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:03.232  1013  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
06-22 07:44:03.242  1013  1531 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
06-22 07:44:03.242  1013  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
06-22 07:44:03.242  6171  6171 D AcmsService: Enter Oncreate
06-22 07:44:03.242  6171  6171 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:03.242  6171  6171 D AcmsService: creating AcmsCore
06-22 07:44:03.242  6171  6171 D AcmsCore: AcmsCore.getAcmsCore() - Enter
06-22 07:44:03.242  6171  6171 D AcmsCore: AcmsCore
06-22 07:44:03.252  1013  1531 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.252  1013  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.252  1013  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
06-22 07:44:03.252  6124  6124 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
06-22 07:44:03.252  1013  1132 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
06-22 07:44:03.252  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.252  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.252  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.252  1013  1132 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.252  1013  1531 D LocationManagerService: getProviders()=[passive, gps]
06-22 07:44:03.262  6212  6212 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:03.262  6212  6212 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.262  6171  6171 D AcmsCore: init
06-22 07:44:03.262  6171  6171 D AcmsCore: Looper handler is not null
06-22 07:44:03.262  6171  6171 D AcmsCore: Post to AcmsCoreHandler
06-22 07:44:03.262  6171  6171 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:03.262  6171  6171 D AcmsServiceMonitor: Incrementing - Counter value: 1
06-22 07:44:03.262  6171  6171 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
06-22 07:44:03.262  6171  6171 D AcmsService: onStartCommand
06-22 07:44:03.262  6171  6171 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
06-22 07:44:03.262  6171  6171 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
06-22 07:44:03.262  6171  6171 D AcmsServiceMonitor: Incrementing - Counter value: 2
06-22 07:44:03.262  6171  6171 D AcmsService: Incremented Counter Value : onStartCommand
06-22 07:44:03.272  6171  6224 D AcmsCertificateMngr: AcmsCertificateMngr
06-22 07:44:03.272  6171  6224 D AcmsRevocationMngr: AcmsRevocationMngr
06-22 07:44:03.272  6234  6234 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.272  6234  6234 E Zygote  : v2
06-22 07:44:03.272  6234  6234 I libpersona: KNOX_SDCARD checking this for 10014
06-22 07:44:03.272  6234  6234 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:03.282  1013  1132 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6234 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
06-22 07:44:03.282  1013  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
06-22 07:44:03.282  1013  1293 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
06-22 07:44:03.282  6150  6150 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
06-22 07:44:03.292  6171  6171 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
06-22 07:44:03.292  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-22 07:44:03.292  6124  6124 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
06-22 07:44:03.292  5734  5747 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
06-22 07:44:03.292  5734  5747 D BadgeProvider: update, [BadgeCount] : badgecount=0
06-22 07:44:03.292  5734  5747 D BadgeProvider: update, [UpdateCount] : 0
06-22 07:44:03.292  6150  6150 W ResourceType: No package identifier when getting value for resource number 0x00000000
,06-22 07:44:03.302  6234  6234 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:03.302  6234  6234 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:03.302  6234  6234 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
06-22 07:44:03.302  1013  1495 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
06-22 07:44:03.302  1013  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
06-22 07:44:03.302  3258  6188 E SQLiteLog: (539) recovered 4 pages from /data/data/com.google.android.gms/databases/help_responses.db-journal
,06-22 07:44:03.302  1013  1495 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.302  1013  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.302  1013  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,06-22 07:44:03.302  3258  6188 W gH_HelpResponseDatabase: Upgrading database from version 15 to 17, which will destroy all old data
,06-22 07:44:03.312  6150  6150 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,06-22 07:44:03.312  1013  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,06-22 07:44:03.312  6150  6150 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,06-22 07:44:03.312  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0,
06-22 07:44:03.312  6150  6150 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
06-22 07:44:03.312  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.312  5734  5751 D BadgeProvider: insert, [uri] : content://com.sec.badge/apps [ContentValues] : package=com.samsung.android.sm badgecount=0 class=com.samsung.android.sm.app.dashboard.SmartManagerDashBoardActivity
06-22 07:44:03.312  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.312  5734  5751 D BadgeProvider: insert, [args] : com.sec.android.provider.badge.BadgeProvider$SqlArguments@2ed57bcb
06-22 07:44:03.312  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.322  6150  6150 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
06-22 07:44:03.322  6150  6150 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,06-22 07:44:03.322  6150  6150 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
06-22 07:44:03.322  6150  6150 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
06-22 07:44:03.322  6150  6150 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
06-22 07:44:03.332  6150  6150 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,06-22 07:44:03.332  6234  6234 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:03.342  6234  6234 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.342  6212  6212 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-22 07:44:03.342  6212  6212 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-22 07:44:03.342  6150  6150 I SA      : [SCU] isHaveSA() - false
06-22 07:44:03.342  6150  6150 I SA      : support phone number id : false
06-22 07:44:03.342  6150  6150 I SA      : [DM] Supports Ref Jpn : true
06-22 07:44:03.342  6150  6150 I SA      : [DM] init END
06-22 07:44:03.342  6150  6150 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOJ5 PSS = 4.497050696380942  ]
,06-22 07:44:03.342  6150  6150 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10151 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
06-22 07:44:03.342  1013  1495 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-22 07:44:03.342  6254  6254 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.342  6254  6254 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:03.342  6254  6254 E Zygote  : v2
06-22 07:44:03.342  6254  6254 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:03.342  6254  6254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-22 07:44:03.352  1013  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,06-22 07:44:03.352  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.352  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.352  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.352  1013  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.352  6254  6254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:03.352  5734  5751 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
06-22 07:44:03.352  5734  5751 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,06-22 07:44:03.352  6254  6254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:03.352  5734  5751 E SQLiteDatabase: Error inserting package=com.samsung.android.sm badgecount=0 class=com.samsung.android.sm.app.dashboard.SmartManagerDashBoardActivity
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at com.sec.android.provider.badge.BadgeProvider.insert(BadgeProvider.java:97)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:242)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:163)
06-22 07:44:03.352  5734  5751 E SQLiteDatabase: 	at android.os.Binder.execTransact(Binder.java:446)
06-22 07:44:03.352  5734  5751 D BadgeProvider: insert, [rowId] : -1
06-22 07:44:03.372  6264  6264 I libpersona: KNOX_SDCARD checking this for 1000
06-22 07:44:03.362  3258  6188 E SQLiteLog: (10) unixWrite() File Descriptor : 97 gets errno : 9
06-22 07:44:03.372  6264  6264 I libpersona: KNOX_SDCARD not a persona
06-22 07:44:03.362  3258  6188 E SQLiteLog: (10) unixWrite() File Descriptor : 97 gets errno : 9
06-22 07:44:03.362  3258  6188 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
06-22 07:44:03.362  3258  6188 E AndroidRuntime: Process: com.google.android.gms, PID: 3258
06-22 07:44:03.362  3258  6188 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:262)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.a(SourceFile:108)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:527)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:03.362  3258  6188 E AndroidRuntime,: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.362  3258  6188 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:44:03.372  6264  6264 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.372  6264  6264 E Zygote  : v2
06-22 07:44:03.372  6264  6264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:03.372  6264  6264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-22 07:44:03.372  6264  6264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-22 07:44:03.372  1013  1495 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6264 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-22 07:44:03.382  6124  6124 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,06-22 07:44:03.382  6124  6124 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,06-22 07:44:03.382  6124  6124 E SQLiteDatabase: Error inserting timestamp=1466574243126 message=Predictor: service is stopped by Application.onCreate
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:03.382  6124  6124 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-22 07:44:03.382  1013  1026 I ActivityManager: Killing 5714:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
06-22 07:44:03.382  6124  6124 E UserAnalysis: It failed to insert to dump_log table
06-22 07:44:03.382  6190  6190 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-22 07:44:03.382  6190  6190 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-22 07:44:03.382  6124  6124 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.382  6124  6124 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
06-22 07:44:03.382  6190  6190 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
06-22 07:44:03.382  1013  5420 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,06-22 07:44:03.392  6124  6124 E SQLiteDatabase: Error inserting timestamp=1466574243267 message=Predictor: service stopped by removePlaceCategories()
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:03.392  6124  6124 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-22 07:44:03.392  6124  6124 E UserAnalysis: It failed to insert to dump_log table
,06-22 07:44:03.392  6190  6190 E SQLiteLog: (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:03.392  6190  6190 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-22 07:44:03.392  6190  6190 D AndroidRuntime: Shutting down VM
06-22 07:44:03.392  6190  6190 E AndroidRuntime: FATAL EXCEPTION: main
06-22 07:44:03.392 , 6190  6190 E AndroidRuntime: Process: com.sec.pcw.device, PID: 6190
06-22 07:44:03.392  6190  6190 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.,java:5702)
06-22 07:44:03.392  6190  6190 E AndroidRuntime: 	... 11 more
06-22 07:44:03.402  1013  1477 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
06-22 07:44:03.402  1013  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
06-22 07:44:03.412  1013  1477 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.412  1013  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-22 07:44:03.412  1013  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
06-22 07:44:03.412  6254  6254 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:03.412  6254  6254 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.412  6264  6264 D TimaKeyStoreProvider: TimaSignature is unavailable
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: Can't write: system_app_crash
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop162.tmp: open failed: EROFS (Read-only file system)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-22 07:44:03.412  1013  6285 E DropBoxManagerService: 	... 5 more
06-22 07:44:03.412  6264  6264 D ActivityThread: Added TimaKeyStore provider
06-22 07:44:03.422  6171  6171 D AcmsService: Inside handle Intent
06-22 07:44:03.422  6171  6171 D AcmsService: App removed - package name: com.test.thalitest
06-22 07:44:03.422  6171  6171 D AcmsCore: Post to AcmsCoreHandler
06-22 07:44:03.422  6171  6171 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
06-22 07:44:03.422  6171  6171 D AcmsServiceMonitor: Incrementing - Counter value: 3
06-22 07:44:03.422  6171  6171 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
06-22 07:44:03.422  6171  6171 D AcmsService: Decremented Counter Value : handleStartIntent
06-22 07:44:03.422  6171  6171 D AcmsServiceMonitor: Decrementing - Counter value: 2
06-22 07:44:03.432  6212  6212 I MultiDex: VM with version 2.1.0 has multidex support
06-22 07:44:03.432  6212  6212 I MultiDex: install
06-22 07:44:03.432  6212  6212 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-22 07:44:03.432  1013  1495 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,06-22 07:44:03.442  1013  1531 I ActivityManager: Killing 5765:com.wsomacp/u0a23 (adj 15): empty #21
,06-22 07:44:03.442  3258  6188 I Process : Sending signal. PID: 3258 SIG: 9
,06-22 07:44:03.442  1013  6287 E DropBoxManagerService: Can't write: system_app_crash
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop163.tmp: open failed: EROFS (Read-only file system)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-22 07:44:03.442  1013  6287 E DropBoxManagerService: 	... 5 more
,06-22 07:44:03.462  1013  1530 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-22 07:44:03.462  1013  1530 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,06-22 07:44:03.462  6190  6190 I Process : Sending signal. PID: 6190 SIG: 9
,06-22 07:44:03.462  1013  1530 W ActivityManager: userId = 0, bbcId = -10000
06-22 07:44:03.462  1013  1530 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-22 07:44:03.462  1013  1530 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-22 07:44:03.462   256   256 E lowmemorykiller: Error writing /proc/3258/oom_score_adj; errno=22
,06-22 07:44:03.462  1013  1530 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,06-22 07:44:03.472  1013  1530 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigFetchService in 1000ms
06-22 07:44:03.472  6047  6116 E SQLiteLog: (28) failed to open "/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db" with flag (131138) and mode_t (0) due to error (30)
,06-22 07:44:03.472  6047  6116 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.w.getWritableDatabase(InternalIcingCorporaProvider.java:561)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:276)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.472  6047  6116 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:44:03.482  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-22 07:44:03.482  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b; callingUser = 0; userId(target) = 0
,06-22 07:44:03.482  1013  1025 W ActivityManager: Unable to start service Intent { cmp=com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b (has extras) } U=0: not found
,06-22 07:44:03.482  1013  1531 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,06-22 07:44:03.482  1013  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.482  1013  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.482  1013  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-22 07:44:03.482  1013  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-22 07:44:03.502  6293  6293 E Zygote  : MountEmulatedStorage()
06-22 07:44:03.502  6293  6293 E Zygote  : v2
06-22 07:44:03.502  6293  6293 I libpersona: KNOX_SDCARD checking this for 10039
06-22 07:44:03.502  6293  6293 I libpersona: KNOX_SDCARD not a persona
,06-22 07:44:03.502  6293  6293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-22 07:44:03.502  6293  6293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-22 07:44:03.512  6293  6293 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-22 07:44:03.522  6254  6254 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,06-22 07:44:03.522  6293  6293 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-22 07:44:03.522  6293  6293 D ActivityThread: Added TimaKeyStore provider
,06-22 07:44:03.532  1013  1531 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6293 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-22 07:44:03.532  1013  1293 I ActivityManager: Process com.google.android.gms (pid 3258)(adj 0) has died(56,770)
,06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10935ms
,06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10934ms
,06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10934ms
,06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20933ms
06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20933ms
,06-22 07:44:03.532  1013  1293 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20932ms
06-22 07:44:03.532  6047  6116 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,06-22 07:44:03.532  6047  6116 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
06-22 07:44:03.532  6047  6116 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6047
06-22 07:44:03.532  6047  6116 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.w.getWritableDatabase(InternalIcingCorporaProvider.java:561)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:276)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.532  6047  6116 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM usage_log WHERE strftime('%s','now', '-40 days')*1000 - start_time >= 0] disk I/O error
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM running_service_log WHERE strftime('%s','now', '-40 days')*1000 - captured_time >= 0] disk I/O error
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM noti_info WHERE strftime('%s','now', '-40 days')*1000 - posted_date >= 0] disk I/O error
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM screen_state_log WHERE strftime('%s','now', '-40 days')*1000 - time >= 0] disk I/O error
,06-22 07:44:03.542  1013  1132 I ActivityManager: Process com.sec.pcw.device (pid 6190)(adj 15) has died(56,770)
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 17: [DELETE FROM debug_log_info WHERE strftime('%s','now', '-20 days')*1000 - created_At >= 0] disk I/O error
,06-22 07:44:03.542  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.542  5914  6250 E SQLiteLog: (3850) statement aborts at 3: [DELETE FROM system_env_info] disk I/O error
,06-22 07:44:03.552  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.552  5914  6250 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,06-22 07:44:03.552  5914  6250 E SQLiteDatabase: Error inserting name=this value=SmartManager LowpowerContextEngine
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:204)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-22 07:44:03.552  5914  6250 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-22 07:44:03.552  6264  6264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
06-22 07:44:03.552  5914  6250 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,06-22 07:44:03.552  5914  6250 E SQLiteDatabase: Error inserting name=now value=Wed Jun 22 07:44:03 GMT+02:00 2016
,06-22 07:44:03.552  5914  6250 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:205)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
06-22 07:44:03.552  5914  6250 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
```
