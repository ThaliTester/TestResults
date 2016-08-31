#### Test 829140733a8c9ab_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-31 15:24:56.167   329   329 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 15:24:56.167   329   329 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-31 15:24:56.927  6175  6175 D AndroidRuntime: 
08-31 15:24:56.927  6175  6175 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 15:24:56.937  6175  6175 D AndroidRuntime: CheckJNI is OFF
08-31 15:24:56.937  6175  6175 D AndroidRuntime: readGMSProperty: start
08-31 15:24:56.937  6175  6175 D AndroidRuntime: readGMSProperty: already setted!!
08-31 15:24:56.937  6175  6175 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 15:24:56.937  6175  6175 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 15:24:56.937  6175  6175 D AndroidRuntime: readGMSProperty: end
08-31 15:24:56.937  6175  6175 D AndroidRuntime: addProductProperty: start
08-31 15:24:57.107  6175  6175 E AffinityControl: AffinityControl: registerfunction enter
08-31 15:24:57.127   287   287 E SMD     : DCD OFF
08-31 15:24:57.137  6175  6175 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 15:24:57.147  1014  1076 E PersonaManagerService: inState():  stateMachine is null !!
08-31 15:24:57.147  1014  1076 I PersonaManagerService: PersonaId don't exist
08-31 15:24:57.147  1014  1076 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 15:24:57.147  1014  1076 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-31 15:24:57.157  1014  1076 W ActivityManager: mDVFSHelper.acquire()
08-31 15:24:57.167  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 15:24:57.167  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 15:24:57.177  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:24:57.177  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:24:57.177  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:24:57.177  1014  1076 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:24:57.187  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 15:24:57.187  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 15:24:57.187  6186  6186 E Zygote  : MountEmulatedStorage()
08-31 15:24:57.187  6186  6186 I libpersona: KNOX_SDCARD checking this for 10155
08-31 15:24:57.187  6186  6186 E Zygote  : v2
08-31 15:24:57.187  6186  6186 I libpersona: KNOX_SDCARD not a persona
08-31 15:24:57.187   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-31 15:24:57.187  1014  1076 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6186 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 15:24:57.187  1014  1076 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-31 15:24:57.187  1014  1076 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 15:24:57.197  6186  6186 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:24:57.197  6186  6186 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:24:57.197  6186  6186 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 15:24:57.207   312   312 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 20.390ms
08-31 15:24:57.207  1014  1076 D InputDispatcher: Focused application set to: xxxx
08-31 15:24:57.207  1014  1076 D InputDispatcher: Focus left window: 3162
08-31 15:24:57.217  6175  6175 D AndroidRuntime: Shutting down VM
08-31 15:24:57.217  6186  6186 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 15:24:57.217  6186  6186 D ActivityThread: Added TimaKeyStore provider
08-31 15:24:57.227  1014  1014 V ActivityManager: Display changed displayId=0
08-31 15:24:57.227   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 611us total 16.982ms
08-31 15:24:57.247  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 15:24:57.247   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 17.446ms
08-31 15:24:57.257  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 15:24:57.257  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 15:24:57.257  1014  2928 D PersonaManager: isKioskContainerExistOnDevice
08-31 15:24:57.307   257  1779 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
08-31 15:24:57.307   257   445 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
08-31 15:24:57.307  3162  3162 V ActivityThread: updateVisibility : ActivityRecord{5464132 token=android.os.BinderProxy@2a37a9f1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-31 15:24:57.367  6186  6186 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-31 15:24:57.377  6186  6186 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 126-128)
08-31 15:24:57.377  6186  6186 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:24:57.407  6186  6186 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d72c58e}
08-31 15:24:57.407  6186  6186 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 15:24:57.407  6186  6186 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 15:24:57.417  6175  6175 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 15:24:57.447  6186  6186 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-31 15:24:57.447  6186  6186 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:24:57.447  6186  6186 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-31 15:24:57.467  6186  6186 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-31 15:24:57.467  6186  6186 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-31 15:24:57.467  6186  6186 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-31 15:24:57.477  6186  6186 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 15:24:57.477  6186  6186 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 15:24:57.477  6186  6186 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 15:24:57.477  6186  6186 I Adreno-EGL: Local Branch: 
08-31 15:24:57.477  6186  6186 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 15:24:57.477  6186  6186 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 15:24:57.477  6186  6186 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 15:24:57.597  6186  6212 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-31 15:24:57.637  6186  6186 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:24:57.657  6186  6186 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 15:24:57.667  6186  6186 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-31 15:24:57.667  6186  6186 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-31 15:24:57.667  6186  6186 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 15:24:57.677  6186  6186 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:24:57.677  6186  6186 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:24:57.717  6186  6225 D OpenGLRenderer: Render dirty regions requested: true
,08-31 15:24:57.727  1014  2928 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 15:24:57.727  1014  2928 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-31 15:24:57.727  1014  2928 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 15:24:57.727  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-31 15:24:57.727  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 15:24:57.737  6186  6186 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-31 15:24:57.737  6186  6186 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 15:24:57.747   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-31 15:24:57.757  1014  1480 D InputDispatcher: Focus entered window: 6186
,08-31 15:24:57.757  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 15:24:57.757  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 15:24:57.767  6186  6186 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 15:24:57.767  6186  6225 I OpenGLRenderer: Initialized EGL, version 1.4,
,08-31 15:24:57.767  6186  6225 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
08-31 15:24:57.767  6186  6225 D OpenGLRenderer: Enabling debug mode 0
,08-31 15:24:57.807  6186  6186 V ActivityThread: updateVisibility : ActivityRecord{c69e431 token=android.os.BinderProxy@14708bbb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 15:24:57.837  1014  1746 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 15:24:57.837  1178  1178 D PanelView: There is/are notification(s) ,
,08-31 15:24:57.847  1014  6228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 15:24:57.847  6186  6186 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-31 15:24:57.847  6186  6186 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14708bbb time:110599
,08-31 15:24:57.857  1785  1785 I SamsungIME: getCurrentCandidateView
,08-31 15:24:57.857  1014  1044 I ActivityManager: Displayed Component not be shown by security: +596ms (total +686ms)
08-31 15:24:57.857  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f08a7cc u0 com.test.thalitest/.MainActivity t128} time:110604
08-31 15:24:57.857  1014  1044 W ActivityManager: mDVFSHelper.release()
08-31 15:24:57.857   257   440 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-31 15:24:57.867   257   445 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-31 15:24:57.917  6186  6186 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6186
,08-31 15:24:57.927  1785  1785 D SamsungIME: Dismiss ExpandCandiate
,08-31 15:24:58.057  6186  6186 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 15:24:58.067  1785  1785 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 15:24:58.107  1785  1785 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 15:24:58.117  1785  1785 I SamsungIME: KeybaordView init() : load resources
,08-31 15:24:58.137  1785  1785 I SamsungIME: getCurrentKeyboard
,08-31 15:24:58.137  1785  1785 I SamsungIME: getTextKeyboard
,08-31 15:24:58.157  6186  6229 D jxcore_app_log: JniHelper::setJavaVM(0xb7f65328), pthread_self() = -1202939752
,08-31 15:24:58.157  1785  1785 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 15:24:58.167  6186  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@270b3ba1 added. We now have 1 listener(s)
,08-31 15:24:58.167  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-31 15:24:58.167  6186  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 15:24:58.167  6186  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:24:58.167  6186  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 15:24:58.177  6186  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f5c8cb4 added. We now have 1 listener(s)
,08-31 15:24:58.177  6186  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:24:58.187  6186  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-31 15:24:58.197  6186  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:24:58.197  6186  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:24:58.197  6186  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 15:24:58.197  6186  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:24:58.197  6186  6229 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 15:24:58.207  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:24:58.207  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:24:58.237  6186  6186 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 15:24:58.697  1785  6233 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 15:24:58.717  6186  6238 W jxcore-log: Initializing JXcore engine
08-31 15:24:58.717  6186  6238 W jxcore-log: JXcore engine is ready
,08-31 15:24:58.777  1889  1889 E audit   : type=1400 msg=audit(1472649898.777:205): avc:  denied  { ioctl } for  pid=6238 comm="Thread-1073" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3088 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-31 15:24:58.777  1889  1889 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:24:58.777  1889  1889 E audit   : type=1300 msg=audit(1472649898.777:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ecc08f8 items=0 ppid=312 ppcomm=main pid=6238 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1073" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 15:24:58.777  1889  1889 E audit   : type=1320 msg=audit(1472649898.777:205): 
,08-31 15:24:58.787  6186  6238 W jxcore-log: Starting JXcore engine
,08-31 15:24:58.907  6186  6238 W jxcore-log: Platform android
08-31 15:24:58.907  6186  6238 W jxcore-log: 
08-31 15:24:58.907  6186  6238 W jxcore-log: Process ARCH arm
08-31 15:24:58.907  6186  6238 W jxcore-log: 
,08-31 15:24:59.107  6186  6238 I jxcore-log: JXcore Cordova bridge is ready!
08-31 15:24:59.107  6186  6238 I jxcore-log: 
,08-31 15:24:59.107  6186  6238 W jxcore-log: JXcore engine is started
,08-31 15:24:59.117  6186  6229 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 15:24:59.117  6186  6186 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 15:24:59.987  1014  1094 V AlarmManager: waitForAlarm result :8,
,08-31 15:25:00.137   287   287 E SMD     : DCD OFF,
,08-31 15:25:01.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:01.177  5386  5386 D FactoryTest: Not factory mode,
08-31 15:25:01.177  5386  5386 D FactoryTest: Not factory mode. isFactoryMode() returend false
08-31 15:25:01.177  5386  5386 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 15:25:01.177  5386  5386 D MTPRx   : still no open session command from host, so toast
,08-31 15:25:01.177  5386  5386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-31 15:25:01.177  5386  5386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-31 15:25:01.177  5386  5386 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113927
,08-31 15:25:01.177  1014  1027 E PersonaManagerService: inState():  stateMachine is null !!
,08-31 15:25:01.177  1014  1027 I PersonaManagerService: PersonaId don't exist
,08-31 15:25:01.177  1014  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-31 15:25:01.187  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 15:25:01.187  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:01.187  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:01.187  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-31 15:25:01.187  1014  1027 W ActivityManager: mDVFSHelper.acquire(),
,08-31 15:25:01.197  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:01.207  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 15:25:01.207  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 15:25:01.207  1014  1027 D InputDispatcher: Focused application set to: xxxx
08-31 15:25:01.207  1014  1027 D InputDispatcher: Focus left window: 6186
,08-31 15:25:01.217  5386  5386 E MTPRx   : started activity for popup
,08-31 15:25:01.217  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 15:25:01.217  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 15:25:01.237  5386  5386 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 15:25:01.257  5386  5386 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-31 15:25:01.257  1014  1251 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-31 15:25:01.257  1014  1251 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 15:25:01.257  1014  1251 D InputDispatcher: Focused application set to: xxxx
,08-31 15:25:01.267  1014  1251 D InputDispatcher: Focus entered window: 6186
,08-31 15:25:01.267  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 15:25:01.267  1014  1493 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 15:25:01.267  1014  1493 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@387b26cf attribute=null, token = android.os.BinderProxy@19ba87df
,08-31 15:25:01.267  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 15:25:01.317  5386  5386 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-31 15:25:01.327  5386  5386 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 15:25:01.327  5386  5386 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-31 15:25:01.347  6186  6186 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 15:25:01.347  6186  6186 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-31 15:25:01.347  6186  6186 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-31 15:25:01.347  6186  6186 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-31 15:25:01.347  1014  1312 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-31 15:25:01.347  1014  1312 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 15:25:01.347  1014  1312 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-31 15:25:01.347  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 15:25:01.347  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 15:25:01.367  6186  6186 D io.jxcore.node.LifeCycleMonitor: onActivityPaused,
08-31 15:25:01.367  6186  6186 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-31 15:25:01.367  6186  6186 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@de1ae3e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@26152c66, 16908290=android.view.AbsSavedState$1@26152c66}, android:focusedViewId=100}]}]
,08-31 15:25:01.367  6186  6186 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-31 15:25:01.367  6186  6186 V ActivityThread: updateVisibility : ActivityRecord{c69e431 token=android.os.BinderProxy@14708bbb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 15:25:01.367  6186  6186 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-31 15:25:01.367  6186  6186 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-31 15:25:01.367  6186  6186 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@14708bbb time:114118
,08-31 15:25:01.377  1014  1493 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:02.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:03.137   287   287 E SMD     : DCD OFF,
,08-31 15:25:03.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:03.317  1014  1991 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 15:25:03.317  1014  1991 D BatteryService: level:62, scale:100, status:2, health:2, present:true, voltage: 3901, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 15:25:03.317  1014  1991 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 15:25:03.317  1014  1991 D BatteryService: stay LED for charging
08-31 15:25:03.317  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 15:25:03.317  1014  1014 I MotionRecognitionService: Plugged
,08-31 15:25:03.317  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 15:25:03.317  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 15:25:03.317  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate,
08-31 15:25:03.317  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 15:25:03.317  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 62
,08-31 15:25:03.327  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-31 15:25:03.327  2649  2723 D HeadsetStateMachine: Disconnected process message: 10
,08-31 15:25:03.347  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:03.347  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
08-31 15:25:03.347  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:03.797  1014  2773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 15:25:04.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:04.187  1014  1039 W ActivityManager: mDVFSHelper.release()
,08-31 15:25:04.527  1014  2730 D SSRM:n  : SIOP:: AP = 340
,08-31 15:25:05.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:06.137   287   287 E SMD     : DCD OFF
,08-31 15:25:06.167   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-31 15:25:07.217  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-31 15:25:07.257  1014  1094 V AlarmManager: waitForAlarm result :4
,08-31 15:25:07.267  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.277  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-31 15:25:07.277  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-31 15:25:07.277  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-31 15:25:07.277  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-31 15:25:07.277  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 15:25:07.297  1926  1926 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 15:25:07.307  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 15:25:07.307  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 15:25:07.317  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 15:25:07.317  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-31 15:25:07.317  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-31 15:25:07.337  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:07.337  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 15:25:07.337  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.347  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.347  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.347  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.357  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 15:25:07.367  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 15:25:07.387  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 15:25:07.397  3785  3785 D ConnectivityManager: CallingUid : 10012, CallingPid : 3785
,08-31 15:25:07.407  1014  1251 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 15:25:07.407  1014  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-31 15:25:07.407  1014  1129 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-31 15:25:07.407  1014  1129 D ConnectivityService: apparently satisfied.  currentScore=60
,08-31 15:25:07.407  3785  6248 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 15:25:07.457  3785  6249 W DriveInitializer: Background init thread started
,08-31 15:25:07.477   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-31 15:25:07.477   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:07.477  3785  6249 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-31 15:25:07.527  1014  1251 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:07.527  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.527  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:07.527  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.527  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.537  3785  6249 W DriveInitializer: Background init thread ended
,08-31 15:25:07.547  1014  1312 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-31 15:25:07.547  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.567  1014  1251 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:07.567  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.567  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.567  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:07.567  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.607  3785  6257 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-31 15:25:07.607  3785  6257 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 15:25:07.617  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 15:25:07.647  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.647  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.647  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.717  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:07.717  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.717  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.717  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.717  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.747  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:07.747  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-31 15:25:07.747  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.747  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.747  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.817  1014  1312 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:07.817  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.817  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.817  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.847  1014  1746 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:07.847  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.847  1014  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:07.847  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.907  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:07.907  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:07.917  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:07.917  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:07.917  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:07.917  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:07.917  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:07.917  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:07.927  6262  6262 E Zygote  : MountEmulatedStorage()
,08-31 15:25:07.927  6262  6262 E Zygote  : v2
08-31 15:25:07.927  6262  6262 I libpersona: KNOX_SDCARD checking this for 10012
08-31 15:25:07.927  6262  6262 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:07.937  1014  1027 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6262 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-31 15:25:07.937  6262  6262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:07.937  6262  6262 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:07.937  6262  6262 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 15:25:07.967  6262  6262 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:07.967  6262  6262 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:07.987  6262  6262 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-31 15:25:07.987  6262  6262 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 15:25:08.027  6262  6262 I MultiDex: VM with version 2.1.0 has multidex support
08-31 15:25:08.027  6262  6262 I MultiDex: install
08-31 15:25:08.027  6262  6262 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 15:25:08.067  6262  6262 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 15:25:08.127  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-31 15:25:08.127  6262  6262 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 15:25:08.127  6262  6262 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2066839b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 15:25:08.127  6262  6262 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 15:25:08.127  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.137  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:08.137  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.137  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.147  6262  6262 D ChimeraCfgMgr: Reading stored module config
,08-31 15:25:08.157  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.157  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:08.157  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.157  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.197  1926  1926 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=abed0873-c411-48c1-8f6c-93e20dba1687
,08-31 15:25:08.207  1014  2928 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 15:25:08.207  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 15:25:08.217  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:08.217  1014  2928 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.217  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.217  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 15:25:08.227  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 15:25:08.257  6262  6281 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 15:25:08.267  1014  4552 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.267  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:08.267  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.267  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.267  6262  6262 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 15:25:08.267  6262  6262 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 15:25:08.347  1926  2120 I art     : Explicit concurrent mark sweep GC freed 66851(3MB) AllocSpace objects, 14(464KB) LOS objects, 39% free, 14MB/23MB, paused 3.024ms total 86.819ms
,08-31 15:25:08.367   282  1012 D WVCdm   : Instantiating CDM.
,08-31 15:25:08.367   282   678 I WVCdm   : CdmEngine::OpenSession
08-31 15:25:08.367   282   678 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-31 15:25:08.387   282   678 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 15:25:08.407   282   678 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-31 15:25:08.407   282   678 D DrmWidevineDash: Service_Initialize: starts!
08-31 15:25:08.407   282   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-31 15:25:08.407   282   678 D QSEECOMAPI: : App is not loaded in QSEE
,08-31 15:25:08.407   282   678 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-31 15:25:08.407   282   678 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-31 15:25:08.407   282   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-31 15:25:08.407   282   678 D QSEECOMAPI: : App is not loaded in QSEE
,08-31 15:25:08.407   282   678 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-31 15:25:08.407   282   678 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-31 15:25:08.407   282   678 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-31 15:25:08.407   282   678 D QSEECOMAPI: : App is not loaded in QSEE
,08-31 15:25:08.437   282   678 D QSEECOMAPI: : Loaded image: APP id = 11
,08-31 15:25:08.437   282   678 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-31 15:25:08.437   282   678 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-31 15:25:08.437   282   678 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-31 15:25:08.437   282   678 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1663000
08-31 15:25:08.437   282   678 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1663000
,08-31 15:25:08.437   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.437   428   437 D DrmLibTime: got the req here! ret=0
08-31 15:25:08.437   428   437 D DrmLibTime: command id, time_cmd_id = 770
08-31 15:25:08.437   428   437 D DrmLibTime: time_getutcsec starts!
08-31 15:25:08.437   428   437 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-31 15:25:08.437   428   437 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-31 15:25:08.437   428   437 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-31 15:25:08.437   428   437 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-31 15:25:08.447   428   437 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-31 15:25:08.447   428   437 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-31 15:25:08.447   428   437 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,08-31 15:25:08.447   428   437 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-31 15:25:08.447   331   416 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-31 15:25:08.447   331  6285 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-31 15:25:08.447   331  6285 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-31 15:25:08.447   331  6285 D QC-time-services: offset is: 0 for base: 0
08-31 15:25:08.447   428   437 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-31 15:25:08.447   428   437 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-31 15:25:08.447   428   437 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472649908
08-31 15:25:08.447   428   437 D DrmLibTime: time_getutcsec returns 0, sec = 1472649908; nsec = 0
08-31 15:25:08.447   428   437 D DrmLibTime: time_getutcsec finished! 
08-31 15:25:08.447   428   437 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-31 15:25:08.447   428   437 D DrmLibTime: before calling ioctl to read the next time_cmd
08-31 15:25:08.447   331   416 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-31 15:25:08.447   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-31 15:25:08.457   282   678 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-31 15:25:08.457   282   678 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-31 15:25:08.457   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.457   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.457   282   678 D DrmWidevineDash: hlos api version =  9
08-31 15:25:08.457   282   678 D DrmWidevineDash: tz api version =  9
08-31 15:25:08.457   282   678 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-31 15:25:08.457   282   678 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-31 15:25:08.457   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.467  6262  6276 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 15:25:08.467  6262  6276 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 15:25:08.467  6262  6276 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 15:25:08.467  6262  6276 I System.out: (HTTPLog)-Thread-1055-777409148: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 15:25:08.467  6262  6276 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:08.467   277   969 D EnterpriseController: uids 10012
08-31 15:25:08.467   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:08.467   277   969 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-31 15:25:08.497   282   678 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb18b7960
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb722b008, dataLength=8
08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb72032f0, wrapped_rsa_key_length=1280
08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.497   282   678 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-31 15:25:08.497   282   678 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-31 15:25:08.497   282   678 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 15:25:08.507   282   696 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-31 15:25:08.507   282   696 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 15:25:08.507   282   696 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-31 15:25:08.507   282   696 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb71ff4b8, idLength=0xb17b7730
,08-31 15:25:08.507   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.507  1605  4182 I art     : Explicit concurrent mark sweep GC freed 1454(49KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 712us total 23.606ms
,08-31 15:25:08.517  6262  6276 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 15:25:08.517  6262  6276 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6262, getuid(): 10012
,08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb17b7746, maximum = 0xb17b7747
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: hlos api version =  9
08-31 15:25:08.527   282   696 D DrmWidevineDash: tz api version =  9
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb17b77b4
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,08-31 15:25:08.527   282   696 D WVCdm   : PrepareKeyRequest: nonce=2519648939
08-31 15:25:08.527   282   696 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb71fea50
08-31 15:25:08.527   282   696 D DrmWidevineDash: message_length=1599, signature=0xb71ff098, signature_length=0xb17b7714
08-31 15:25:08.527   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.647  1926  2103 W GCoreFlp: No location to return for getLastLocation()
,08-31 15:25:08.677  1014  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.677  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:08.677  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.677  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.677  1014  1746 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.687  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:08.687  1014  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.687  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.687   282   696 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.687   282   696 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-31 15:25:08.687  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:08.687   282  1012 I WVCdm   : CdmEngine::CloseSession
08-31 15:25:08.687   282  1012 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.687  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.687   282  1012 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-31 15:25:08.687   282  1012 I WVCdm   : L3 Terminate.
08-31 15:25:08.687   282  1012 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 15:25:08.687  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 15:25:08.687   282  1012 D DrmWidevineDash: Service_Uninitialize: starts!
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-31 15:25:08.687   282  1012 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-31 15:25:08.687   282  1012 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-31 15:25:08.697   282  1012 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
08-31 15:25:08.697  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:08.717  3785  6258 D UdcContextInitService: registered all accounts: true
,08-31 15:25:08.717  1926  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 15:25:08.727  1926  2120 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-31 15:25:08.767  6262  6276 I qtaguid : Untagging socket 30
,08-31 15:25:08.857  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:08.857  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
,08-31 15:25:08.857  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:08.857  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-31 15:25:08.857  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.047  1014  1076 I art     : Explicit concurrent mark sweep GC freed 36654(1971KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 28MB/42MB, paused 2.591ms total 153.343ms
,08-31 15:25:09.087  1014  1319 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 15:25:09.087  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 15:25:09.087  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.087  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:09.087  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.117  6294  6294 I dex2oat : ----------------------------------------------------
08-31 15:25:09.117  6294  6294 I dex2oat : <SS>: S T A R T I N G . . .
08-31 15:25:09.117  6294  6294 I dex2oat : <SS>: Zip is absent. Canceled.
,08-31 15:25:09.117  6294  6294 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 15:25:09.137   287   287 E SMD     : DCD OFF
,08-31 15:25:09.147  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.147  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.147  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:09.147  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.167  6294  6294 I dex2oat : dex2oat took 43.682ms (threads: 4)
,08-31 15:25:09.177  6262  6276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 15:25:09.177  6262  6276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 15:25:09.177  6262  6276 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 15:25:09.177  6262  6276 I Adreno-EGL: Local Branch: 
08-31 15:25:09.177  6262  6276 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 15:25:09.177  6262  6276 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 15:25:09.177  6262  6276 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 15:25:09.187  1014  4552 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.187  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.187  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:09.187  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.227  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.227  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.227  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:09.227  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.227  1926  6301 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 15:25:09.237  1926  6293 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 15:25:09.237  1014  4552 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.237  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.237  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:09.237  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.267  1014  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.267  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.267  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:09.267  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.267  6262  6276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 15:25:09.267  6262  6276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 15:25:09.267  6262  6276 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 15:25:09.267  6262  6276 I Adreno-EGL: Local Branch: 
08-31 15:25:09.267  6262  6276 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 15:25:09.267  6262  6276 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 15:25:09.267  6262  6276 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 15:25:09.267  1926  6301 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 15:25:09.267  1926  6293 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-31 15:25:09.267  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.267  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.277  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:09.277  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.297  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:09.297  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.297  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:09.297  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.297  1926  6301 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-31 15:25:09.297  1926  6293 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-31 15:25:09.297  1926  6293 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-31 15:25:09.297  1926  6293 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 15:25:09.357  1014  1312 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 15:25:09.397  1014  4552 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 15:25:09.397  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 15:25:09.397  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:09.397  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:09.397  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:09.407  1926  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:09.407   277   969 D EnterpriseController: uids 10012
08-31 15:25:09.407   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:09.407   277   969 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 15:25:09.407  1926  6293 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 15:25:09.407  1926  6293 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:09.457  1926  6293 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:09.527  6262  6276 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 15:25:09.527  6262  6276 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 15:25:09.527  6262  6276 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 15:25:09.527  6262  6276 I Adreno-EGL: Local Branch: 
08-31 15:25:09.527  6262  6276 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 15:25:09.527  6262  6276 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 15:25:09.527  6262  6276 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 15:25:09.737  1014  1251 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 15:25:09.747  1926  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:09.747  1926  6293 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:09.797  1926  6260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:09.807   277   969 D EnterpriseController: uids 10012
08-31 15:25:09.807   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:09.807   277   969 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 15:25:09.807  1926  6260 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 15:25:09.807  1926  6260 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1926, getuid(): 10012
,08-31 15:25:09.847  1926  6260 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1926, getuid(): 10012
,08-31 15:25:09.877  1014  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 15:25:09.877  1926  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:09.877  1926  6293 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:10.027  1014  1076 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-31 15:25:10.037  1926  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:10.037  1926  6293 I qtaguid : Tagging socket 73 with tag 1106583100000000{285628465,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:10.317  1926  2120 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 15:25:10.327  1926  2120 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-31 15:25:10.327  1926  2120 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-31 15:25:08.846+0200, stopTime=2016-08-31 15:25:10.341+0200, duration=1495ms
,08-31 15:25:10.347  1926  6309 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:10.357   277   969 D EnterpriseController: uids 10012
08-31 15:25:10.357   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:10.357   277   969 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 15:25:10.357  1926  6309 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-31 15:25:10.357  1926  6309 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1926, getuid(): 10012
,08-31 15:25:10.387  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-31 15:25:10.397  1926  6309 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1926, getuid(): 10012
,08-31 15:25:10.687  1926  6309 I qtaguid : Untagging socket 66
,08-31 15:25:10.697  1926  2120 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-31 15:25:11.167   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:11.757  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 15:25:11.757  6186  6238 I jxcore-log: 
,08-31 15:25:11.757  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 15:25:11.757  6186  6238 I jxcore-log: 
,08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:11.767  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:11.767  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:11.767  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 15:25:11.767  6186  6238 I jxcore-log: 
,08-31 15:25:11.767  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 15:25:11.767  6186  6238 I jxcore-log: 
,08-31 15:25:12.137   287   287 E SMD     : DCD OFF,
,08-31 15:25:12.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:12.417  6186  6238 D executeNativeTests: Running unit tests
,08-31 15:25:12.437  1926  6310 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:12.437  1926  6310 I qtaguid : Tagging socket 66 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1926, getuid(): 10012
,08-31 15:25:12.497  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:12.497  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 added. We now have 2 listener(s)
,08-31 15:25:12.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:12.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:12.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:12.507  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:12.507  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 added. We now have 2 listener(s)
08-31 15:25:12.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:12.507  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:12.507  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:12.507  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:12.507  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:12.517  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:25:12.517  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-31 15:25:12.517  6186  6238 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-31 15:25:12.517  6186  6238 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:25:12.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-31 15:25:12.517  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.517  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.517  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:12.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.517  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.517  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:12.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 removed from the list
08-31 15:25:12.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.517  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 removed from the list
,08-31 15:25:12.517  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.517  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.517  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.517  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.517  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.527  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-31 15:25:12.527  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.527  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.527  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.527  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.527  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.527  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.527  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.527  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.527  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:25:12.527  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:25:12.527  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.527  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.527  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.537  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.537  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.537  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.537  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.537  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.537  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.537  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.537  6186  6238 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:12.537  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:12.537  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.537  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:12.537  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:12.537  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:12.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-31 15:25:12.547  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:12.547  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-31 15:25:12.547  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:12.547  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-31 15:25:12.557  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:12.557  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 15:25:12.557  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 15:25:12.557  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-31 15:25:12.567  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 15:25:12.577  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-31 15:25:12.587  2649  2659 D BtGatt.GattService: registerClient() - UUID=ebf83fb0-bf79-447b-b09a-6793c08648f8
,08-31 15:25:12.637  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=ebf83fb0-bf79-447b-b09a-6793c08648f8, clientIf=6
,08-31 15:25:12.637  6186  6195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 15:25:12.637  2649  2658 D BtGatt.GattService: start scan with filters
,08-31 15:25:12.637  2649  2720 D BtGatt.ScanManager: handling starting scan
08-31 15:25:12.637  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:12.637  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:25:12.637  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:25:12.637  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:25:12.647  2649  2720 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:12.647  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-31 15:25:12.647  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 15:25:12.647  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:12.647  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:12.657  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 15:25:12.657  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.657  2649  2720 D BtGatt.ScanManager: allow scan with filters
,08-31 15:25:12.657  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 15:25:12.657  2649  2720 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 15:25:12.657  6186  6238 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 15:25:12.667  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 15:25:12.667  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.667  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.667  6186  6238 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 15:25:12.667  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.667  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:25:12.667  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.667  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:12.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:25:12.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:12.667  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:12.667  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:25:12.667  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:25:12.667  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 15:25:12.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:25:12.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 15:25:12.677  2649  2906 D BtGatt.GattService: stopScan() - queue size =1,
08-31 15:25:12.677  2649  2659 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 15:25:12.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:12.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 15:25:12.677  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 15:25:12.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:25:12.677  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:25:12.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:12.687  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 15:25:12.687  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:12.687  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 15:25:12.687  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:12.687  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-31 15:25:12.687  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:12.687  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:25:12.687  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:25:12.687  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:12.687  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.687  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.687  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:12.687  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.687  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:12.687  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.687  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.687  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.687  6186  6238 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 15:25:12.687  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 15:25:12.697  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:12.697  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:12.707  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.707  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:12.707  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:12.707  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:12.707  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:12.707  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:12.707  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:12.707  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:25:12.707  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.707  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:12.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:12.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:25:12.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 15:25:12.717  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:25:12.727  2649  2722 D BtGatt.GattService: registerClient() - UUID=44edc959-3f97-4b7d-9362-4a15b4143020
,08-31 15:25:12.737  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27,
,08-31 15:25:12.737  2649  2720 D BtGatt.ScanManager: filter size is 1
,08-31 15:25:12.737  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 15:25:12.747  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 15:25:12.747  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.747  2649  2720 D BtGatt.ScanManager: stopping BLe Batch
,08-31 15:25:12.757  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:12.757  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:12.757  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 15:25:12.757  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 15:25:12.757  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.767  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=44edc959-3f97-4b7d-9362-4a15b4143020, clientIf=6
08-31 15:25:12.767  6186  6194 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 15:25:12.767  2649  2659 D BtGatt.GattService: start scan with filters
08-31 15:25:12.767  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:12.767  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:25:12.767  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 15:25:12.767  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:25:12.777  2649  2720 D BtGatt.ScanManager: handling starting scan
,08-31 15:25:12.777  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:25:12.777  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 15:25:12.777  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:12.777  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:12.777  6186  6238 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 15:25:12.777  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 15:25:12.777  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:12.777  2649  2720 D BtGatt.ScanManager: allow scan with filters
,08-31 15:25:12.777  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 15:25:12.777  2649  2720 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 15:25:12.787  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 15:25:12.787  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.787  6186  6238 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 15:25:12.787  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.787  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:25:12.787  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 15:25:12.787  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:12.787  2649  2906 D BtGatt.GattService: stopScan() - queue size =1
,08-31 15:25:12.787  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:25:12.787  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 15:25:12.787  2649  2722 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 15:25:12.787  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:25:12.787  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.797  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:12.797  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.797  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.797  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.797  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:12.797  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:12.797  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:12.797  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.797  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.797  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 15:25:12.797  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.797  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.797  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.797  6186  6238 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-31 15:25:12.807  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-31 15:25:12.807  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:12.807  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:12.817  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:12.817  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:12.817  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:25:12.827  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.827  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:12.827  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
,08-31 15:25:12.827  2649  2720 D BtGatt.ScanManager: filter size is 1
,08-31 15:25:12.827  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 15:25:12.827  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 15:25:12.827  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-31 15:25:12.837  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:12.837  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:12.837  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:12.837  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 15:25:12.837  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.837  2649  2720 D BtGatt.ScanManager: stopping BLe Batch,
,08-31 15:25:12.837  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:25:12.847  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:12.847  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.847  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 15:25:12.847  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-31 15:25:12.847  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.847  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:12.847  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:12.857  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:25:12.857  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 15:25:12.857  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:25:12.857  2649  2659 D BtGatt.GattService: registerClient() - UUID=f8b396da-8c39-4543-bdce-1c3c008114b1
,08-31 15:25:12.897  2649  2717 D BtGatt.GattService: onClientRegistered() - UUID=f8b396da-8c39-4543-bdce-1c3c008114b1, clientIf=6
,08-31 15:25:12.897  6186  6194 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-31 15:25:12.897  2649  2658 D BtGatt.GattService: start scan with filters
08-31 15:25:12.907  2649  2720 D BtGatt.ScanManager: handling starting scan,
08-31 15:25:12.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:12.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:25:12.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-31 15:25:12.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:25:12.907  2649  2717 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-31 15:25:12.907  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.907  2649  2720 D BtGatt.ScanManager: allow scan with filters
,08-31 15:25:12.907  2649  2720 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 15:25:12.907  2649  2720 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-31 15:25:12.917  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 15:25:12.917  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.917  2649  2720 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 15:25:12.917  2649  2720 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 15:25:12.917  2649  2717 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-31 15:25:12.917  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.917  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:12.917  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 15:25:12.917  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.927  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:25:12.927  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 15:25:12.927  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:12.937  6186  6238 I io.jxcore.node.ConnectionHelper: start: OK
,08-31 15:25:12.937  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:12.937  6186  6238 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 15:25:12.937  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.937  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-31 15:25:12.937  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:12.937  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:12.937  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-31 15:25:12.937  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-31 15:25:12.937  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:12.937  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:25:12.937  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-31 15:25:12.937  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 15:25:12.947  2649  2659 D BtGatt.GattService: stopScan() - queue size =1
,08-31 15:25:12.947  2649  2720 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,08-31 15:25:12.947  2649  2720 D BtGatt.ScanManager: filter size is 1
08-31 15:25:12.947  2649  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
08-31 15:25:12.947  2649  2720 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 15:25:12.947  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:12.947  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 15:25:12.947  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 15:25:12.947  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:25:12.947  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:25:12.947  2649  2717 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 15:25:12.947  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.947  2649  2720 D BtGatt.ScanManager: stopping BLe Batch
,08-31 15:25:12.947  1926  6310 I qtaguid : Untagging socket 66
,08-31 15:25:12.947  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:12.957  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:12.957  2649  2717 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:12.957  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.957  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:12.957  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.957  6186  6238 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-31 15:25:12.957  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.957  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:12.957  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.957  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:12.957  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.957  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.957  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.957  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.957  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:25:12.957  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:12.957  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.957  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.967  2649  2720 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.967  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.967  1926  2120 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-31 15:25:12.967  6186  6238 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-31 15:25:12.967  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.967  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.967  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.967  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.967  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.967  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:12.967  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.967  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.967  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.967  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.967  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.967  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.967  2649  2717 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 15:25:12.967  2649  2717 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.967  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.967  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.977  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-31 15:25:12.977  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.977  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.977  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.977  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.977  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.977  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.977  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.977  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.977  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.977  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.977  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.977  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.977  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.977  6186  6238 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-31 15:25:12.977  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:12.977  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:12.977  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.977  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.977  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.977  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
,08-31 15:25:12.977  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.977  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.977  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:25:12.977  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.987  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.987  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.987  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-31 15:25:12.987  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.987  6186  6238 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-31 15:25:12.987  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.987  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:25:12.987  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.987  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-31 15:25:12.987  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.987  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
,08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-31 15:25:12.987  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.987  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.987  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.987  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.987  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.987  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.987  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 15:25:12.987  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:12.987  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:12.987  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-31 15:25:12.997  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:12.997  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:25:12.997  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:12.997  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.997  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.997  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
,08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.997  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:12.997  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.997  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:12.997  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:12.997  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:12.997  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-31 15:25:12.997  6186  6238 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:12.997  6186  6238 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-31 15:25:12.997  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-31 15:25:12.997  6186  6238 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:12.997  6186  6238 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:12.997  6186  6238 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:12.997  6186  6238 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-31 15:25:12.997  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:12.997  6186  6238 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-31 15:25:12.997  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-31 15:25:13.007  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-31 15:25:13.007  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-31 15:25:13.007  6186  6238 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-31 15:25:13.007  6186  6238 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-31 15:25:13.007  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.007  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.007  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.007  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.007  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.007  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-31 15:25:13.007  6186  6320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1137)
08-31 15:25:13.007  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.007  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.007  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.007  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.007  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.007  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.007  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.007  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.017  6186  6321 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1137
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.017  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.017  6186  6238 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-31 15:25:13.017  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.017  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.017  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.017  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.017  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.017  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.017  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.017  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.017  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:13.017  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.017  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.017  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.017  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.017  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.017  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.017  6186  6320 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-31 15:25:13.027  6186  6238 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-31 15:25:13.027  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.027  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.027  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.027  6186  6320 D BluetoothSocket: connect(): myUserId = 0
08-31 15:25:13.027  6186  6320 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-31 15:25:13.027  6186  6238 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:13.027  6186  6238 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:25:13.027  6186  6238 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:25:13.027  6186  6238 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-31 15:25:13.027  6186  6238 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-31 15:25:13.027  6186  6238 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-31 15:25:13.027  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.027  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.027  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.027  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.027  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.027  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.027  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.027  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.037  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
,08-31 15:25:13.037  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.037  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.037  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.037  2649  2659 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.037  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.037  6186  6320 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.037  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.037  6186  6238 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-31 15:25:13.037  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-31 15:25:13.047  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:25:13.047  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.047  6186  6186 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-31 15:25:13.047  6186  6186 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:13.047  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.047  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:13.047  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.047  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:13.047  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:13.047  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.047  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.047  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.047  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.047  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.047  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.047  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.047  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.047  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.047  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.047  6186  6322 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-31 15:25:13.047  6186  6322 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-31 15:25:13.047  6186  6186 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.057  6186  6238 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-31 15:25:13.057  6186  6238 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-31 15:25:13.057  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-31 15:25:13.057  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.057  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.057  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.057  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.057  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:13.057  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.057  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.057  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.057  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.057  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.057  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.057  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.067  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.067  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:13.067  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:13.067  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:13.067  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:13.067  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.067  6186  6238 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d244c97 not in the list
08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.067  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:13.067  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.067  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:13.067  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:13.067  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:13.067  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:13.067  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b94ce84 not in the list
,08-31 15:25:13.067  6186  6238 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:13.067  6186  6238 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-31 15:25:13.067  6186  6238 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2,
08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-31 15:25:13.067  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-31 15:25:13.077  6186  6238 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:25:13.077  6186  6238 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-31 15:25:13.077  6186  6238 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed,
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-31 15:25:13.077  6186  6238 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-31 15:25:13.077  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:13.077  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@18a2d5c6 added. We now have 2 listener(s),
08-31 15:25:13.077  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:13.077  6186  6238 D BluetoothAdapter: enable(),
,08-31 15:25:13.077  6186  6238 D BluetoothAdapter: enable(): BT is already enabled..!
,08-31 15:25:13.077  1014  1493 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 15:25:13.077  1014  1493 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 15:25:13.077  1014  1493 D SecContentProvider2: mCursor = null
,08-31 15:25:13.087  1014  1493 W WifiService: Failed getting userId using ActivityManagerNative
08-31 15:25:13.087  1014  1493 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 15:25:13.087  1014  1493 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 15:25:13.087  1014  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 15:25:13.087  1014  1493 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 15:25:13.087  1014  1493 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 15:25:13.087  1014  1493 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-31 15:25:13.087  1014  1493 D WifiService: setWifiEnabled: true pid=6186, uid=10155
08-31 15:25:13.087  1014  1493 D SettingsProvider: name = wifi_on
08-31 15:25:13.087  1014  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@379b8987 added. We now have 3 listener(s)
08-31 15:25:13.087  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@368ae0b4 added. We now have 4 listener(s)
,08-31 15:25:13.087  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:13.087  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d0b4dd added. We now have 5 listener(s)
08-31 15:25:13.087  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:13.097  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-31 15:25:13.097  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 15:25:13.097  1014  1027 D SecContentProvider2: mCursor = null
,08-31 15:25:13.097  1014  1027 D WifiService: setWifiEnabled: false pid=6186, uid=10155
08-31 15:25:13.097  1014  1027 D SettingsProvider: name = wifi_on
,08-31 15:25:13.097  1014  1127 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-31 15:25:13.097  2096  2096 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 15:25:13.097  2096  2096 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 15:25:13.107  6186  6238 D BluetoothAdapter: disable()
08-31 15:25:13.107  2096  2096 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 15:25:13.107  2096  2096 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 15:25:13.107  1014  1312 D SettingsProvider: name = bluetooth_on
,08-31 15:25:13.107  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:25:13.107  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:13.117  2649  2714 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 15:25:13.117  2649  2714 D BluetoothAdapterProperties: Setting state to 13
08-31 15:25:13.117  2649  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-31 15:25:13.117  2649  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 15:25:13.117  2649  2714 D BluetoothAdapterService: updateAdapterState state is 13
08-31 15:25:13.117  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:13.117  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
,08-31 15:25:13.117  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:13.117  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.117  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.117  2649  2649 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-31 15:25:13.127  2649  2714 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:13.127  2649  2714 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-31 15:25:13.127  2649  2714 D BluetoothAdapterService: terminating service from this receiver
,08-31 15:25:13.127  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@35fdcf49, channel: 19, state: LISTENING
08-31 15:25:13.127  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@35fdcf49, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ca17338, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25da056fmSocket: android.net.LocalSocket@2e56527c impl:android.net.LocalSocketImpl@2d5a835a fd:FileDescriptor[74]
08-31 15:25:13.127  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2e56527c impl:android.net.LocalSocketImpl@2d5a835a fd:FileDescriptor[74]
,08-31 15:25:13.127  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-31 15:25:13.127  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:13.127  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 15:25:13.127  1014  1127 E WifiNative-wlan0: do suspend true
08-31 15:25:13.127  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.127  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:13.127  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:13.127  1291  1291 D BluetoothPbap: Proxy object disconnected
08-31 15:25:13.127  1291  1291 D PbapServerProfile: Bluetooth service disconnected
08-31 15:25:13.127  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.127  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.127  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.127  2649  2714 D BluetoothAdapterProperties: onBluetoothDisable()
08-31 15:25:13.127  2649  2714 D BluetoothAdapterProperties: mDiscovering is false
08-31 15:25:13.127  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:13.127  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-31 15:25:13.127  1014  1991 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 15:25:13.137  2649  2714 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-31 15:25:13.137  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.137  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 15:25:13.137  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 15:25:13.147  2649  2717 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 15:25:13.147  2649  2717 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:25:13.147  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-31 15:25:13.147  2649  2714 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-31 15:25:13.147  2649  2714 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-31 15:25:13.147  2649  2714 E bt-btif : cmd socket is not created
08-31 15:25:13.147  2649  4961 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-31 15:25:13.147  2649  2714 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-31 15:25:13.147  2649  2782 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 15:25:13.147  2649  2782 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-31 15:25:13.147  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 15:25:13.147  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:13.147  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-31 15:25:13.147  6186  6320 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c1d3723, channel: -1, state: INIT
08-31 15:25:13.147  6186  6320 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c1d3723, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@374f5420, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2928c1d9mSocket: android.net.LocalSocket@3840d79e impl:android.net.LocalSocketImpl@1782227f fd:FileDescriptor[106]
08-31 15:25:13.147  6186  6320 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3840d79e impl:android.net.LocalSocketImpl@1782227f fd:FileDescriptor[106]
08-31 15:25:13.147  6186  6320 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1137)
08-31 15:25:13.147  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:13.147  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:13.147  2649  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:13.147  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:13.167  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.167  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-31 15:25:13.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:13.177  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 15:25:13.177  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 15:25:13.177  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
08-31 15:25:13.177  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
08-31 15:25:13.177  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.177  1178  1178 D BluetoothTile:  getBluetoothState : 13
08-31 15:25:13.187  1785  1785 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 15:25:13.187  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33f41a68, channel: 5, state: LISTENING
08-31 15:25:13.187  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33f41a68, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7294f11, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@136b1e81mSocket: android.net.LocalSocket@ad7b26 impl:android.net.LocalSocketImpl@ac73367 fd:FileDescriptor[76]
08-31 15:25:13.187  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ad7b26 impl:android.net.LocalSocketImpl@ac73367 fd:FileDescriptor[76]
,08-31 15:25:13.187  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 15:25:13.187  2649  2649 I BtOppRfcommListener: stopping Accept Thread
08-31 15:25:13.187  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@31247514, channel: 12, state: LISTENING
08-31 15:25:13.187  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@31247514, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38c7cb13, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29aa21bdmSocket: android.net.LocalSocket@28e623b2 impl:android.net.LocalSocketImpl@16899f03 fd:FileDescriptor[79]
08-31 15:25:13.187  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28e623b2 impl:android.net.LocalSocketImpl@16899f03 fd:FileDescriptor[79]
,08-31 15:25:13.187  2649  4961 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-31 15:25:13.187  1014  2928 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:13.187  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 15:25:13.197  1014  1746 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:13.197  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:13.197  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-31 15:25:13.197  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 15:25:13.197  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:13.197  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.197  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.197  1014  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:13.197  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:13.197  2649  2649 V BluetoothOppManager: cleanUp...
,08-31 15:25:13.207  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:13.207  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 15:25:13.207  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.207  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.207  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.207  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:13.207  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:13.217  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:13.217  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.217  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 15:25:13.227  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 15:25:13.227  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.227  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.227  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.227  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.237  6328  6328 E Zygote  : MountEmulatedStorage(),
08-31 15:25:13.237  6328  6328 I libpersona: KNOX_SDCARD checking this for 10003
08-31 15:25:13.237  6328  6328 E Zygote  : v2
,08-31 15:25:13.237  6328  6328 I libpersona: KNOX_SDCARD not a persona,
08-31 15:25:13.237  6328  6328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:13.237  1014  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6328 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-31 15:25:13.247  6328  6328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:13.247  6328  6328 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:13.277  6328  6328 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:13.277  6328  6328 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:13.317  6328  6328 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 15:25:13.347  6328  6328 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-31 15:25:13.347  6328  6328 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-31 15:25:13.347  6328  6328 D UserAnalysis: Create SecureDbHelper
,08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:13.347  2649  2782 W bt-btif : ag scb idx 1 not allocated
08-31 15:25:13.347  2649  2782 W bt-btif : ag scb idx 2 not allocated
08-31 15:25:13.347  2649  2782 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:25:13.347  2649  2838 I bt_userial_mct: exiting userial_read_thread
08-31 15:25:13.347  2649  2838 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:25:13.347  2649  2717 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:25:13.347  2649  2784 I bt_vendor: hw_epilog_process
08-31 15:25:13.347  2649  2717 D bt_userial_mct: userial_close
08-31 15:25:13.347  2649  2717 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 15:25:13.347  6328  6328 D IntelligenceServiceApplication: onCreate(),
,08-31 15:25:13.357  1014  1026 I ActivityManager: Killing 5291:com.google.android.talk/u0a104 (adj 15): empty #31
,08-31 15:25:13.367  6328  6328 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 15:25:13.367  1014  1319 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 15:25:13.367  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.367  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.367  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.367  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.377  1014  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 15:25:13.377  1014  1027 D BatteryService: level:62, scale:100, status:2, health:2, present:true, voltage: 3881, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 15:25:13.377  1014  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 15:25:13.377  1014  1027 D BatteryService: stay LED for charging
08-31 15:25:13.377  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 15:25:13.377  6347  6347 E Zygote  : MountEmulatedStorage(),
08-31 15:25:13.377  6347  6347 E Zygote  : v2
,08-31 15:25:13.377  6347  6347 I libpersona: KNOX_SDCARD checking this for 10107
08-31 15:25:13.377  6347  6347 I libpersona: KNOX_SDCARD not a persona,
08-31 15:25:13.387  6347  6347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:13.387  1014  1319 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6347 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-31 15:25:13.387  6347  6347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:13.387  6347  6347 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-31 15:25:13.387  1014  1014 I MotionRecognitionService: Plugged
08-31 15:25:13.387  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 15:25:13.387  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
08-31 15:25:13.387  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 15:25:13.387  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 15:25:13.387  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 62
,08-31 15:25:13.397  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:13.397  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 15:25:13.397  2649  2723 D HeadsetStateMachine: Disconnected process message: 10
,08-31 15:25:13.397  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-31 15:25:13.397  6328  6328 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 15:25:13.407  6328  6328 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-31 15:25:13.417  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:13.417  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:13.417  6347  6347 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:13.417  6347  6347 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:13.447  1014  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-31 15:25:13.447  1014  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 15:25:13.447   277   973 D CommandListener: Clearing all IP addresses on wlan0
08-31 15:25:13.457  1926  4384 V NativeCrypto: Read error: ssl=0xb84656f8: I/O error during system call, Connection timed out
,08-31 15:25:13.457  1926  4384 V NativeCrypto: SSL shutdown failed: ssl=0xb84656f8: I/O error during system call, Broken pipe
08-31 15:25:13.457  1926  4384 E GCM     : Wifi connection closed with errorCode 20
08-31 15:25:13.457  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:13.457  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:13.457  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-31 15:25:13.457  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 15:25:13.457  1014  1312 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-31 15:25:13.457  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.467  1014  1126 D WifiP2pService: InactiveState{ what=131204 }
08-31 15:25:13.457  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.467  1014  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 15:25:13.457  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.457  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.457  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:13.457  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:13.457  1014  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:25:13.467  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-5ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:13.467  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-5ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:13.467  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-31 15:25:13.467  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:13.467  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-31 15:25:13.467  1014  2210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 15:25:13.467  1014  2210 I qtaguid : Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
08-31 15:25:13.467  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 15:25:13.467  1014  2210 I qtaguid : Untagging socket 358
08-31 15:25:13.467  1014  2210 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:13.477  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:13.487  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-31 15:25:13.487  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:13.487  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:13.487  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:13.497  1014  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:13.497  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.497  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.497  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:13.497  1014  1014 D RttService: SCAN_AVAILABLE : 1,
08-31 15:25:13.497  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:13.497  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-31 15:25:13.497  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,08-31 15:25:13.497  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-31 15:25:13.497  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 15:25:13.497  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 15:25:13.507  1014  1126 D WifiP2pService: P2pDisablingState,
08-31 15:25:13.507  1014  1127 E WifiNative-wlan0: do suspend true
08-31 15:25:13.507  1014  1126 D WifiP2pService: P2pDisablingState{ what=147458 },
08-31 15:25:13.507  1014  1126 D WifiP2pService: p2p socket connection lost
08-31 15:25:13.507  1014  1126 D WifiP2pService: P2pDisabledState
08-31 15:25:13.507  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-31 15:25:13.507  1014  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
08-31 15:25:13.507  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 15:25:13.507  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-31 15:25:13.507  1014  1044 D WifiDisplayController: disconnect
08-31 15:25:13.507  1014  1044 D WifiDisplayController: updateConnection
08-31 15:25:13.507  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-31 15:25:13.507  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:13.517  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 15:25:13.517  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-31 15:25:13.517  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:13.517  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-31 15:25:13.517  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.517  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 15:25:13.517  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.517  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 15:25:13.517  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 15:25:13.517  1014  1126 D WifiP2pService: DefaultState{ what=143375 }
08-31 15:25:13.517  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.517  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 15:25:13.517  1014  2928 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-31 15:25:13.517  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 15:25:13.537   277   969 D EnterpriseController: uids 1000
,08-31 15:25:13.537   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:13.537   277   969 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 15:25:13.537   277   973 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:13.537  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-31 15:25:13.537  1014  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-31 15:25:13.537  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-31 15:25:13.537  1014  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-31 15:25:13.537  1178  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 15:25:13.537  1014  1129 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:13.537  1014  2210 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:13.537  1014  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-31 15:25:13.537  1014  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 15:25:13.537  1014  1129 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-31 15:25:13.537  3785  6248 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-31 15:25:13.537  1014  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 15:25:13.537  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-31 15:25:13.537  1457  1457 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 15:25:13.537  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 15:25:13.537  2096  2096 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 15:25:13.547  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:13.547  6186  6186 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:25:13.547  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-31 15:25:13.547  1014  1130 D Tethering: MasterInitialState.processMessage what=3
08-31 15:25:13.547  1014  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 15:25:13.547  1014  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 15:25:13.547  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:13.547  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:13.547  1014  1129 E ConnectivityService: updateNetworkInfo()
,08-31 15:25:13.547  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:13.557  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.557  1014  1124 V NetworkStats: updateIfacesLocked()
08-31 15:25:13.557  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:13.557  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 15:25:13.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 15:25:13.557  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-31 15:25:13.557  1014  1124 V NetworkStats: performPollLocked() took 4ms,
08-31 15:25:13.557  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.557  1014  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 15:25:13.557  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.557  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.557  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.557  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: EthernetConnected: false,
,08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-31 15:25:13.557  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 15:25:13.557  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 15:25:13.567  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.567  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:13.567  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.567  1014  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 15:25:13.567  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:13.567  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:13.577  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:13.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:13.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.577  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:13.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:13.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 15:25:13.577  1178  1178 D HotspotTile: onReceive : 0, 0
08-31 15:25:13.577  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 15:25:13.577  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:13.577  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false,
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:13.577  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:13.587  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:13.587  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:13.587  2649  2717 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 15:25:13.587  2649  2717 I bt_vendor: bluetooth satus is on
08-31 15:25:13.587  2649  2717 I bt_vendor: bt-vendor : resetting BT status
08-31 15:25:13.587  2649  2717 I bt_vendor: Starting hciattach daemon
08-31 15:25:13.587  2649  2717 I bt_vendor: try to set false
08-31 15:25:13.587  2649  2717 I bt_vendor: Starting hciattach daemon
,08-31 15:25:13.587  2649  2717 I bt_vendor: try to set false
,08-31 15:25:13.587  2649  2717 I bt_vendor: cleanup
08-31 15:25:13.587  2649  2782 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-31 15:25:13.587  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:13.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:13.587  2649  2717 I GKI_LINUX: GKI_exit_task 0 done
08-31 15:25:13.587  2649  2717 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 15:25:13.587  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:13.587  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:13.597  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-31 15:25:13.597  2649  2714 D BtConfig.SecureMode: isSecureModeOn:false
08-31 15:25:13.597  2649  2714 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-31 15:25:13.597  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 15:25:13.597  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 15:25:13.597  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 15:25:13.597  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.597  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.597  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.597  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.597  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.607  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:13.607  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 15:25:13.607  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:25:13.607  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:13.607  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
08-31 15:25:13.607  2649  2649 D BtGatt.GattService: stop()
08-31 15:25:13.607  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
,08-31 15:25:13.607  2096  2096 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 15:25:13.607  1014  1076 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.607  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.607  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.607  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.607  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.617  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:13.617  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.617  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:13.617  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:13.617  1014  2928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.617  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.617  2649  2649 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:25:13.617  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:13.617  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.617  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:13.617  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 15:25:13.617  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 15:25:13.617  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 15:25:13.627  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.627  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-31 15:25:13.627  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 15:25:13.627  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.627  1291  1291 D HeadsetProfile: Bluetooth service disconnected
08-31 15:25:13.627  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.627  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.627  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:13.627  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 15:25:13.627  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 15:25:13.627  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 15:25:13.627  1014  2928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.627  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.627  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.627  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.627  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.637  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-31 15:25:13.637  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 15:25:13.637  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 15:25:13.637  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:13.637  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.637  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.637  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.637  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:13.637  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:13.637  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.637  2649  2714 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:13.637  1014  1312 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.647  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:13.647  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.647  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.647  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:13.647  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:13.647  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:13.647  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-31 15:25:13.647  2096  2096 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-31 15:25:13.647  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 15:25:13.647  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 15:25:13.647  2649  2714 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 15:25:13.647  1014  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:13.647  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0,
08-31 15:25:13.647  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.647  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.647  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:13.647  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:13.647  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:13.657  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 15:25:13.657  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 15:25:13.657  2649  2714 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 15:25:13.657  2649  2714 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 15:25:13.657  2649  2714 D BluetoothAdapterState: Stopping profile services that were post enabled
08-31 15:25:13.657  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-31 15:25:13.657  2649  2649 D A2dpService: Received stop request...Stopping profile...
,08-31 15:25:13.657  2649  2731 D A2dpStateMachine: Exit Disconnected: -1
,08-31 15:25:13.657  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.667  1291  1291 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:13.667  2863  2863 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:13.667  1291  1291 D A2dpProfile: Bluetooth service disconnected
,08-31 15:25:13.667  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:13.667  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-31 15:25:13.667  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 15:25:13.667  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:13.667  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 15:25:13.667  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-31 15:25:13.667  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-31 15:25:13.667  2649  2649 D HidService: Received stop request...Stopping profile...
08-31 15:25:13.667  2649  2649 D HidService: Stopping Bluetooth HidService
08-31 15:25:13.667  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:25:13.667  2649  2649 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 15:25:13.667  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-31 15:25:13.677  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.677  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-31 15:25:13.677  1291  1291 D HidProfile: Bluetooth service disconnected
08-31 15:25:13.677  2649  2649 D HealthService: Received stop request...Stopping profile...
08-31 15:25:13.677  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.677  2096  2096 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 15:25:13.677  2096  2096 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 15:25:13.677  2096  2096 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 15:25:13.677  2096  2096 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 15:25:13.677  2096  2096 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-31 15:25:13.677  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.677  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.677  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:13.677  2649  2649 D PanService: Received stop request...Stopping profile...
08-31 15:25:13.677  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
08-31 15:25:13.677  1014  1130 D Tethering: InitialState.processMessage what=4
,08-31 15:25:13.677  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.677  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:25:13.677  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.677  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:13.677  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
08-31 15:25:13.677  1014  1130 E Tethering: No numeric data
,08-31 15:25:13.677  1014  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:13.677  1014  1130 D Tethering: clearTetheredNotification()
,08-31 15:25:13.687  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.687  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 15:25:13.687  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-31 15:25:13.687  1291  1291 D PanProfile: Bluetooth service disconnected
,08-31 15:25:13.687  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 15:25:13.687  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:13.687  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:13.687  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.687  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:13.687  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:13.687  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:13.687  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:13.697  2649  2649 D SapService: Received stop request...Stopping profile...
,08-31 15:25:13.697  1291  1291 D BluetoothMap: Proxy object disconnected
,08-31 15:25:13.697  1291  1291 D MapProfile: Bluetooth service disconnected
,08-31 15:25:13.697  2649  2649 D SapService: Stopping Bluetooth SapService
,08-31 15:25:13.697  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
08-31 15:25:13.697  1014  1127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-31 15:25:13.697  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.697  1014  1124 V NetworkStats: performPollLocked() took 12ms
,08-31 15:25:13.697  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-31 15:25:13.697  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:13.697  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 15:25:13.697  2649  2649 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:13.697  2649  2649 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 15:25:13.697  2649  2732 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-31 15:25:13.697  2649  2649 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:25:13.697  2649  2649 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-31 15:25:13.707  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:13.707  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:13.707  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 15:25:13.707  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 15:25:13.707  1291  1291 D SapProfile: Bluetooth service disconnected
08-31 15:25:13.707  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 15:25:13.707  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-31 15:25:13.707  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:13.707  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 15:25:13.707  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:13.707  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:25:13.707  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 15:25:13.707  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 15:25:13.707  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 15:25:13.707  2649  2649 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 15:25:13.707  2649  2649 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-31 15:25:13.707  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 15:25:13.707  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 15:25:13.707  2649  2714 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-31 15:25:13.707  2649  2714 D BluetoothAdapterProperties: Setting state to 10
08-31 15:25:13.707  2649  2714 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 15:25:13.707  2649  2714 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 15:25:13.707  2649  2714 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 15:25:13.707  2649  2714 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:13.707  2649  2714 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 15:25:13.707  2649  2714 I BluetoothAdapterState: Entering OffState
08-31 15:25:13.707  2649  2659 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.707  2649  2659 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.717  1291  1301 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 15:25:13.717  1291  1301 D Bluetoothsap: Unbinding service...
,08-31 15:25:13.717  6186  6194 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.717  6186  6194 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.717  6186  6194 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 15:25:13.717  6186  6194 D BluetoothLeAdvertiser: Exit stop advertising
,08-31 15:25:13.717  6186  6194 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-31 15:25:13.717  6186  6194 D BluetoothLeScanner: Exiting stopAllScan
,08-31 15:25:13.717  1440  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.717  1440  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.727  1430  2721 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.727  1430  2721 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.727  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.727  1291  1301 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:25:13.727  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.727  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 15:25:13.727  1014  2928 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-31 15:25:13.727  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-31 15:25:13.737  1014  2928 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:13.737  1014  2928 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:13.737  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-31 15:25:13.737  2649  2658 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:13.737  1291  1303 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 15:25:13.737   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb845f7c8
08-31 15:25:13.737   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-31 15:25:13.737  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.737   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 15:25:13.737  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 15:25:13.737   272   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1203374792)
08-31 15:25:13.737  1926  2108 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.737  1926  2108 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 15:25:13.737  2863  2879 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:13.747  1291  1301 D BluetoothPbap: onBluetoothStateChange: up=false
08-31 15:25:13.747  2863  2879 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.747  2863  2879 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 15:25:13.747  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.747  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 15:25:13.747  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.747  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.757  1291  1303 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:25:13.757  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.757  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 15:25:13.757  1178  1883 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.757  1178  1883 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 15:25:13.757  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.757  1291  1301 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.757  1291  1301 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.757  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.767  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.767  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.767  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 15:25:13.767  1457  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:13.767  1457  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:13.767  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.767  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.767  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.777  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.777  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
08-31 15:25:13.777  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.777  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-31 15:25:13.777  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.777  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.777  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-31 15:25:13.777  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-31 15:25:13.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-31 15:25:13.787  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.787  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.787  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.787  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-31 15:25:13.787  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 15:25:13.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.797  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-31 15:25:13.797  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-31 15:25:13.797  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-31 15:25:13.797  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.797  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 15:25:13.797  1178  1703 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=277 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=270 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.util.,jni.NativeHelper.initialize(PG:48)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThr,ead$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  1178  1178 D BluetoothTile:  getBluetoothState : 10
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=197 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.k.c(PG:583)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.807  1014  1312 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 15:25:13.797  6347  6347 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:13.797  6347  6347 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:13.807  1014  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 15:25:13.797  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.797  1178  1703 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.807   272   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-31 15:25:13.807   272   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 15:25:13.807   272   324 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1203374792) wakelock released: 1, error no: 0
08-31 15:25:13.807   272   324 I rmt_storage: 
08-31 15:25:13.807  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.807  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.807   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb845f7c8
08-31 15:25:13.807  1785  1785 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 15:25:13.807  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 15:25:13.817  2096  2096 I wpa_supplicant: Blacklist: Clear (all) 
08-31 15:25:13.817  1926  2119 D BluetoothAdapter: 37864785: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.817  1926  2119 D BluetoothAdapter: 37864785: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:13.817  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:13.817  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:13.817  1014  2928 I ActivityManager: Killing 4998:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-31 15:25:13.817  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:13.827  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:13.827  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-31 15:25:13.827  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.827  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:13.827  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 15:25:13.827  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 15:25:13.827  2649  2717 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-31 15:25:13.837  2649  2649 I GKI_LINUX: GKI_exit_task 1 done
08-31 15:25:13.837  2649  2649 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-31 15:25:13.837  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 15:25:13.837  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 15:25:13.837  2649  2649 I art     : System.exit called, status: 0
08-31 15:25:13.837  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-31 15:25:13.847  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 15:25:13.847  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:13.847  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:13.857  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.857  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:13.857  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 15:25:13.857  3632  3632 I Hs20UtilService: Starting #8
08-31 15:25:13.857  3632  3681 I Hs20UtilService: Message received 5007
08-31 15:25:13.857  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 15:25:13.857  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 15:25:13.857  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 15:25:13.857  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 15:25:13.857  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:13.857  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 15:25:13.857  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 15:25:13.867  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-31 15:25:13.867  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 15:25:13.867  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 15:25:13.867  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 15:25:13.867  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:13.867  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 15:25:13.867  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 15:25:13.867  2096  2096 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-31 15:25:13.867  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.867  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:13.867  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:13.867  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-31 15:25:13.877  6347  6373 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-31 15:25:13.877  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.877  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.877  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.877  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.887  6401  6401 E Zygote  : MountEmulatedStorage()
08-31 15:25:13.887  6401  6401 I libpersona: KNOX_SDCARD checking this for 10068
08-31 15:25:13.887  6401  6401 E Zygote  : v2
08-31 15:25:13.887  6401  6401 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:13.887  6401  6401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:13.897  6401  6401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:13.897  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6401 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:13.897  1014  4552 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:13.897  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:13.897  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:13.897  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-31 15:25:13.897  6401  6401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:13.907  1014  1991 I ActivityManager: Process com.android.bluetooth (pid 2649)(adj 0) has died(44,1089)
,08-31 15:25:13.917  6401  6401 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 15:25:13.917  6401  6401 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:13.927  6401  6401 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 15:25:13.947  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:13.947  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 15:25:13.967  6401  6401 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 15:25:13.977  1014  1319 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-31 15:25:13.977  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.977  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.977  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:13.977  1014  1319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:13.987  6416  6416 E Zygote  : MountEmulatedStorage(),
,08-31 15:25:13.987  6416  6416 E Zygote  : v2
08-31 15:25:13.987  6416  6416 I libpersona: KNOX_SDCARD checking this for 10069
,08-31 15:25:13.987  1014  1319 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6416 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:13.987  6416  6416 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:13.987  6416  6416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:13.987  1014  1319 I ActivityManager: Killing 5445:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-31 15:25:13.987  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-31 15:25:13.987  6416  6416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:13.987  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 15:25:13.997  1014  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 15:25:13.997  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:13.997  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:13.997  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.997  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.997  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:13.997  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:13.997  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:13.997  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 15:25:13.997  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 15:25:13.997  6416  6416 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:13.997  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:13.997  1926  2119 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:13.997  1178  1178 D HotspotTile: onReceive : 1, 0
08-31 15:25:14.007  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:14.007  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:14.007  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:14.017  6416  6416 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:14.017  6416  6416 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:14.037  6416  6416 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:14.047  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.047  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.047  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-31 15:25:14.047  1014  1991 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 15:25:14.047  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.047  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.047  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.047  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.047  1014  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:14.067  6432  6432 E Zygote  : MountEmulatedStorage()
08-31 15:25:14.067  6432  6432 I libpersona: KNOX_SDCARD checking this for 10104
,08-31 15:25:14.067  6432  6432 E Zygote  : v2
08-31 15:25:14.067  6432  6432 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:14.067  6432  6432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:14.067  1014  1991 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6432 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-31 15:25:14.077  6432  6432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:14.077  1014  1251 I ActivityManager: Killing 5535:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-31 15:25:14.077  1014  1014 I ApplicationPolicy: updateDataUsageMap
08-31 15:25:14.087  6432  6432 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 15:25:14.097  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:14.097  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:14.097  3162  3162 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-31 15:25:14.097  3162  3162 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-31 15:25:14.107  6432  6432 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:14.107  6432  6432 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:14.127  6432  6432 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 15:25:14.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:14.207  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:14.287  6432  6455 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-31 15:25:14.287  6432  6455 I Babel   : MmsConfig.loadMmsSettings
,08-31 15:25:14.287  6432  6455 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-31 15:25:14.287  6432  6455 I Babel   : MmsConfig.loadFromDatabase
,08-31 15:25:14.297  1014  1319 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-31 15:25:14.297  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 15:25:14.297  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.307  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.307  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 15:25:14.307  6432  6432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:25:14.307  6432  6455 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-31 15:25:14.307  6432  6455 I Babel   : MmsConfig.loadFromResources
,08-31 15:25:14.307  6432  6455 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 15:25:14.307  6432  6455 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-31 15:25:14.347  6432  6432 I Babel_StickerModule: App launched.
,08-31 15:25:14.367  1014  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:14.367  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:14.367  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.367  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.367  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:14.367  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:14.367  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:14.367  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:14.377  3632  3632 I Hs20UtilService: Starting #9
,08-31 15:25:14.377  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:14.377  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:14.377  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:14.377  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:14.377  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:14.377  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.377  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.377  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.387   282  1012 W QCamera2Factory: getCameraInfo: E, camera_id = 0
08-31 15:25:14.387   282  1012 W QCamera2Factory: getCameraInfo: X
,08-31 15:25:14.387   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,08-31 15:25:14.387   282   282 W QCamera2Factory: getCameraInfo: X
,08-31 15:25:14.407  6432  6432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 15:25:14.407  6432  6432 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 15:25:14.407  6432  6432 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 15:25:14.417  6432  6432 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 15:25:14.427  6432  6432 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 15:25:14.427  6432  6432 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 15:25:14.437  6432  6432 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 15:25:14.437  6432  6432 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 15:25:14.447  6432  6432 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 15:25:14.447  6432  6432 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 15:25:14.447  6432  6432 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 15:25:14.457  6432  6432 W VideoCapabilities: Unsupported mime video/mp43
,08-31 15:25:14.457  6432  6432 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 15:25:14.457  6432  6432 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 15:25:14.477  6432  6432 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 15:25:14.497  1014  1041 D Tethering: interfaceRemoved wlan0
08-31 15:25:14.497  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 15:25:14.497  1014  1312 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-31 15:25:14.497  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-31 15:25:14.497  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.497  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.497  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 15:25:14.507  1014  1493 I ActivityManager: Killing 5769:com.sec.pcw.device/1000 (adj 15): empty #31
,08-31 15:25:14.507  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,08-31 15:25:14.517  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-31 15:25:14.517  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-31 15:25:14.517  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=962)
,08-31 15:25:14.537  1014  2730 D SSRM:n  : SIOP:: AP = 350
,08-31 15:25:14.567  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.567  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.567  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.567  1014  2928 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:14.567  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:14.567  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.567  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:14.567  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:14.577  1014  1991 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-31 15:25:14.577  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.577  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.577  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.577  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.577  3632  3632 I Hs20UtilService: Starting #10
,08-31 15:25:14.577  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:14.587  6458  6458 E Zygote  : MountEmulatedStorage()
,08-31 15:25:14.587  6458  6458 E Zygote  : v2
08-31 15:25:14.587  6458  6458 I libpersona: KNOX_SDCARD checking this for 1000
08-31 15:25:14.587  6458  6458 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:14.587  1014  1991 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6458 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
08-31 15:25:14.587  6458  6458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:14.597  6458  6458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 15:25:14.597  6458  6458 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:14.607  6458  6458 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 15:25:14.607  6458  6458 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:14.647  1014  1041 D Tethering: interfaceRemoved p2p0
,08-31 15:25:14.647  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 15:25:14.647  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 15:25:14.647  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 15:25:14.647  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 15:25:14.657  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:14.657  1014  1480 I ActivityManager: Killing 5784:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-31 15:25:14.667  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.667  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.667  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.667  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.667  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.667  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.667  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.667  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.667  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.677  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.677  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.677  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.677  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.677  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:14.677  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.687  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.687  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.687  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.687  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.697  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.697  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.697  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.697  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.707  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.707  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.707  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.707  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.707  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.707  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-31 15:25:14.717  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:14.717  1014  1319 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 15:25:14.717  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:14.717  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.717  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:14.717  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:14.727  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:14.727  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:14.727  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:14.727  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 15:25:14.727  1014  1991 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-31 15:25:14.737  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 15:25:14.737  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.737  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.737  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.747  6475  6475 E Zygote  : MountEmulatedStorage()
,08-31 15:25:14.747  1014  1991 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6475 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-31 15:25:14.747  6475  6475 E Zygote  : v2
08-31 15:25:14.747  6475  6475 I libpersona: KNOX_SDCARD checking this for 1002
08-31 15:25:14.747  6475  6475 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:14.747  6475  6475 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:14.757  6475  6475 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 15:25:14.757  6475  6475 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:14.777  6475  6475 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:14.777  6475  6475 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:14.787  1014  1746 I ActivityManager: Killing 5083:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-31 15:25:14.787  6475  6475 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-31 15:25:14.787  6475  6475 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 15:25:14.817  6475  6475 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding GattService
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding HidService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding HealthService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding PanService
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding SapService
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 15:25:14.857  6475  6475 D BtSettings.ProfileConfig: Adding HidDevService
08-31 15:25:14.857  6475  6475 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 15:25:14.857  1014  1076 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 15:25:14.857  1014  1076 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.857  1014  1076 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.857  1014  1076 D SettingsProvider: selectionArgs: false
08-31 15:25:14.857  1014  1076 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.857  1014  1076 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.857  1014  1076 D SettingsProvider: ret = -1
08-31 15:25:14.857  1014  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:14.857  1014  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.857  1014  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.857  1014  1251 D SettingsProvider: selectionArgs: false
08-31 15:25:14.857  1014  1251 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.857  1014  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.857  1014  1251 D SettingsProvider: ret = -1
,08-31 15:25:14.857  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 15:25:14.867  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:14.867  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1027 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1027 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  1027 D SettingsProvider: ret = -1
,08-31 15:25:14.867  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-31 15:25:14.867  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:14.867  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1026 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1026 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  1026 D SettingsProvider: ret = -1
,08-31 15:25:14.867  1014  1746 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 15:25:14.867  1014  1746 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.867  1014  1746 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1746 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1746 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1746 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  1746 D SettingsProvider: ret = -1
,08-31 15:25:14.867  1014  1312 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 15:25:14.867  1014  1312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.867  1014  1312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1312 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1312 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1312 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:14.867  1014  1312 D SettingsProvider: ret = -1
08-31 15:25:14.867  1014  2928 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 15:25:14.867  1014  2928 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:14.867  1014  2928 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  2928 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  2928 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  2928 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:14.867  1014  2928 D SettingsProvider: ret = -1
08-31 15:25:14.867  1014  4552 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 15:25:14.867  1014  4552 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.867  1014  4552 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  4552 D SettingsProvider: selectionArgs: false
,08-31 15:25:14.867  1014  4552 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  4552 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  4552 D SettingsProvider: ret = -1
08-31 15:25:14.867  1014  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:14.867  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:14.867  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1493 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1493 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:14.867  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  1493 D SettingsProvider: ret = -1
,08-31 15:25:14.867  1014  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:14.867  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:14.867  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.867  1014  1480 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1480 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:14.867  1014  1480 D SettingsProvider: ret = -1
08-31 15:25:14.867  1014  1991 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 15:25:14.867  1014  1991 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.867  1014  1991 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 15:25:14.867  1014  1991 D SettingsProvider: selectionArgs: false
08-31 15:25:14.867  1014  1991 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.867  1014  1991 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:14.867  1014  1991 D SettingsProvider: ret = -1
08-31 15:25:14.877  1014  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-31 15:25:14.877  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:14.877  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:14.877  1014  1319 D SettingsProvider: selectionArgs: false
08-31 15:25:14.877  1014  1319 D SettingsProvider: selectionArgs: 1002
08-31 15:25:14.877  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:14.877  1014  1319 D SettingsProvider: ret = -1
,08-31 15:25:14.887  1014  1076 I ActivityManager: Killing 5470:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-31 15:25:14.887  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:14.887  1014  1312 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:14.887  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:14.887  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.887  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.887  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:14.897  1926  6491 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 15:25:14.897  1014  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:14.907  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:14.907  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.907  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.907  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:14.927  1014  2928 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:14.927  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:14.927  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:14.927  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:14.927  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:14.937  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:14.937  3632  3632 I Hs20UtilService: Starting #11
,08-31 15:25:14.937  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:14.937  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:14.937  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:14.937  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:14.947  1926  6491 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 15:25:14.947  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:14.947  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:14.947  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:14.947  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:14.947  1014  1251 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 15:25:14.957  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.957  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:14.957  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.957  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:14.967  6492  6492 E Zygote  : MountEmulatedStorage(),
08-31 15:25:14.967  1014  1251 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-31 15:25:14.967  6492  6492 E Zygote  : v2
08-31 15:25:14.967  6492  6492 I libpersona: KNOX_SDCARD checking this for 1000
08-31 15:25:14.967  6492  6492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-31 15:25:14.967  6492  6492 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:14.967  6492  6492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:14.977  6492  6492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:14.987  6492  6492 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:14.987  6492  6492 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.007  6492  6492 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 15:25:15.007  6492  6492 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 15:25:15.007  6492  6492 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 15:25:15.017  6492  6492 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 15:25:15.017  6492  6492 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 15:25:15.017  6492  6492 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 15:25:15.017  6492  6492 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:15.017  1014  1312 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-31 15:25:15.017  1014  1312 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 15:25:15.017  1014  1312 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-31 15:25:15.017  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.017  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.017  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.017  1014  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.027  6492  6507 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-31 15:25:15.037  6509  6509 E Zygote  : MountEmulatedStorage(),
08-31 15:25:15.037  6509  6509 E Zygote  : v2
08-31 15:25:15.037  6509  6509 I libpersona: KNOX_SDCARD checking this for 10111
08-31 15:25:15.037  6509  6509 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:15.037  6509  6509 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:15.037  6509  6509 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-31 15:25:15.037  1014  1312 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6509 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 15:25:15.037  6509  6509 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-31 15:25:15.047  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
08-31 15:25:15.047  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.047  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.047  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.047  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-31 15:25:15.057  6509  6509 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.057  6509  6509 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.067  6524  6524 E Zygote  : MountEmulatedStorage(),
08-31 15:25:15.067  6524  6524 E Zygote  : v2
08-31 15:25:15.067  6524  6524 I libpersona: KNOX_SDCARD checking this for 10009
08-31 15:25:15.067  6524  6524 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:15.067  6524  6524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:15.067  6524  6524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:15.067  6524  6524 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 15:25:15.067  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6524 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:15.077  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-31 15:25:15.077  1705  1705 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-31 15:25:15.077  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.077  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.077  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.077  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.087   312   312 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 25.427ms
,08-31 15:25:15.097  6524  6524 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.097  6524  6524 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.107   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 592us total 16.869ms
,08-31 15:25:15.127   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 16.956ms
,08-31 15:25:15.137  6539  6539 E Zygote  : MountEmulatedStorage(),
08-31 15:25:15.137  6539  6539 E Zygote  : v2
08-31 15:25:15.137  6539  6539 I libpersona: KNOX_SDCARD checking this for 10145,
08-31 15:25:15.137  6539  6539 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:15.137  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6539 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-31 15:25:15.137   287   287 E SMD     : DCD OFF
08-31 15:25:15.147  6539  6539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:15.147  6539  6539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:15.147  6539  6539 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 15:25:15.157  1705  1705 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-31 15:25:15.157  1705  1705 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-31 15:25:15.157  1705  1705 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-31 15:25:15.157  1705  1705 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 15:25:15.167  1705  1705 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 15:25:15.167  1705  1705 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
08-31 15:25:15.167  1315  2726 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
08-31 15:25:15.167  1014  1251 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast,
08-31 15:25:15.167  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.167  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.167  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.167  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:15.187  6539  6539 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 15:25:15.187  6539  6539 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.197  1014  1251 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6554 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:15.197  6554  6554 E Zygote  : MountEmulatedStorage()
08-31 15:25:15.197  6554  6554 E Zygote  : v2
08-31 15:25:15.197  6554  6554 I libpersona: KNOX_SDCARD checking this for 10081
08-31 15:25:15.197  6554  6554 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:15.197  6554  6554 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:15.197  6554  6554 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:15.197  6554  6554 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 15:25:15.207  1705  1705 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-31 15:25:15.217  6539  6539 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-31 15:25:15.217  6539  6539 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:15.217  6539  6539 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 15:25:15.217  6539  6539 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 15:25:15.217  6539  6539 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 15:25:15.217  6554  6554 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.217  6554  6554 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.247  1014  1251 I ActivityManager: Killing 5802:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-31 15:25:15.247  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 15:25:15 GMT+02:00 2016
,08-31 15:25:15.247  1014  4552 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 15:25:15.247  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.247  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:15.247  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:15.247  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 15:25:15.257  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 15:25:15.257  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 15:25:15.257  3684  3684 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 15:25:15.267  1014  1991 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 15:25:15.267  3684  3684 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 15:25:15.267  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.267  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.267  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.267  1014  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.267  3684  6573 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 15:25:15.267  3684  6573 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 15:25:15.277  6509  6509 I MusicStore: Database version: 108
,08-31 15:25:15.277  3684  6573 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-31 15:25:15.277  3684  6573 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-31 15:25:15.277  6576  6576 E Zygote  : MountEmulatedStorage(),
08-31 15:25:15.277  6576  6576 E Zygote  : v2
08-31 15:25:15.277  6576  6576 I libpersona: KNOX_SDCARD checking this for 10034
08-31 15:25:15.287  6576  6576 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:15.287  6576  6576 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:15.287  6576  6576 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:15.287  6576  6576 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 15:25:15.287  1014  1991 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6576 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-31 15:25:15.297  1014  1493 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.297  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 15:25:15.307  6576  6576 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.307  6576  6576 D ActivityThread: Added TimaKeyStore provider
08-31 15:25:15.307  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.307  1014  1251 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 15:25:15.307  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 15:25:15.317  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:15.317  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.317  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.347  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 15:25:15.347  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.347  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.347  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.347  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.347  6576  6576 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-31 15:25:15.367  1014  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6596 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:15.367  6596  6596 E Zygote  : MountEmulatedStorage()
08-31 15:25:15.367  6596  6596 E Zygote  : v2
08-31 15:25:15.367  6596  6596 I libpersona: KNOX_SDCARD checking this for 10113
08-31 15:25:15.367  6596  6596 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:15.367  1014  1027 I ActivityManager: Killing 5819:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-31 15:25:15.367  6596  6596 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:15.367  6596  6596 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:15.367  1014  1493 I ActivityManager: Killing 5504:com.sec.knox.bridge/1000 (adj 15): empty #31
08-31 15:25:15.367  6596  6596 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 15:25:15.377  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 15:25:15.377  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.397  3202  6608 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-31 15:25:15.397  6596  6596 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.397  6596  6596 D ActivityThread: Added TimaKeyStore provider
08-31 15:25:15.397  3202  6608 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-31 15:25:15.397  3202  6608 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-31 15:25:15.397  1014  1251 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.407  3202  6608 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-31 15:25:15.407  3202  6608 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 15:25:15.417  6509  6509 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-31 15:25:15.417  6509  6509 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 15:25:15.417  6018  6018 I SA      : [DM] init START
,08-31 15:25:15.427  6018  6018 I SA      : [DM] This device is not a Vodafone
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-31 15:25:15.437  6018  6018 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-31 15:25:15.437  6018  6018 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 15:25:15.447  6018  6018 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-31 15:25:15.457  6018  6018 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-31 15:25:15.467  5906  5920 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 15:25:15.477  6018  6018 I SA      : [SCU] isHaveSA() - false
08-31 15:25:15.477  6018  6018 I SA      : support phone number id : false
08-31 15:25:15.477  6018  6018 I SA      : [DM] Supports Ref Jpn : true
08-31 15:25:15.477  6018  6018 I SA      : [DM] init END
08-31 15:25:15.477  6018  6018 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-31 15:25:15.477  5906  5920 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-31 15:25:15.477  5906  5920 D BadgeProvider: sendNotify, [notify] : null
08-31 15:25:15.477  5906  5920 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-31 15:25:15.477  5906  5920 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 15:25:15.477  5906  5920 D BadgeProvider: update, [UpdateCount] : 1
,08-31 15:25:15.477  1014  1746 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.477  6018  6018 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-31 15:25:15.477  6018  6018 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 15:25:15.477  1477  1477 D Launcher.Model: reloadBadges entered.
,08-31 15:25:15.477  6018  6018 I SA      : [SLFUCHKMGR] constructor called
,08-31 15:25:15.487  6509  6509 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 15:25:15.497  6018  6018 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 15:25:15.497  6018  6018 I SA      : [OR] == isSIMCardReady false ==
,08-31 15:25:15.497  6018  6018 I SA      : [SCU] == networkStateCheck == false
,08-31 15:25:15.497  1014  1312 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.497  6018  6018 I SA      : [OR] onReceive END
,08-31 15:25:15.507  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:15.517  1014  1319 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.527  1014  1251 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:15.537  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:15.537  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:15.537  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:15.537  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:15.537  1014  1746 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-31 15:25:15.537  1014  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.537  1014  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.537  1014  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.537  1014  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.557  1014  1746 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6619 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 15:25:15.557  6619  6619 E Zygote  : MountEmulatedStorage()
08-31 15:25:15.557  6619  6619 I libpersona: KNOX_SDCARD checking this for 10159
08-31 15:25:15.557  6619  6619 E Zygote  : v2
08-31 15:25:15.557  6619  6619 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:15.557  6619  6619 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:15.557  6619  6619 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:15.557  6619  6619 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-31 15:25:15.577  6509  6509 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 15:25:15.577  6509  6509 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35703602: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-31 15:25:15.577  6509  6509 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 15:25:15.577  6509  6509 D AndroidMusic: GMSCore installation verified
,08-31 15:25:15.587  6619  6619 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 15:25:15.587  6619  6619 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.617  1014  1480 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 15:25:15.617  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-31 15:25:15.617  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.617  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:15.617  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.627  6509  6509 I ConfigStore: Config Database version: 1
,08-31 15:25:15.647  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:15.647  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.647  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.647  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:15.647  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:15.657  3785  3785 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-31 15:25:15.657  1014  1991 I art     : Explicit concurrent mark sweep GC freed 52419(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 28MB/42MB, paused 2.831ms total 174.380ms
,08-31 15:25:15.657  3785  4556 I iu.UploadsManager: num queued entries: 0
,08-31 15:25:15.657  3785  4556 I iu.UploadsManager: num updated entries: 0
,08-31 15:25:15.657  3785  4556 I iu.SyncManager: NEXT; no task
,08-31 15:25:15.697  1014  4552 I ActivityManager: Killing 5834:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-31 15:25:15.747   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 15:25:15.747   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.747  6509  6509 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 15:25:15.747   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 15:25:15.747   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.747  6509  6509 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 15:25:15.757   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 15:25:15.757   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.757  6509  6509 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 15:25:15.757  1014  1312 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-31 15:25:15.757  1014  1312 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:15.757  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
08-31 15:25:15.757  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.757  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.787  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.787  1014  1319 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 15:25:15.787  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.787  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.787  1014  1991 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:15.787  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-31 15:25:15.797  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.797  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.797  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.817  1014  1991 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:15.817  1014  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:15.817   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 15:25:15.817   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.817  6596  6641 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 15:25:15.817  1014  4552 I AudioService: getStreamVolume 3 index 0
,08-31 15:25:15.827   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 15:25:15.827   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.827  6596  6641 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
08-31 15:25:15.827  6509  6509 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-31 15:25:15.827  6509  6509 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-31 15:25:15.837   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 15:25:15.837   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.847  6596  6644 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 15:25:15.847   256   531 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 15:25:15.847   256   531 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 15:25:15.847  6596  6644 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 15:25:15.857  1014  4552 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:15.857  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 15:25:15.857  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.857  1014  4552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.857  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.857  1014  1312 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:15.857  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.857  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.857  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:15.857  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.867  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:15.867  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.867  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:15.867  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.867  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.877  1014  2928 I ActivityManager: Killing 5751:com.android.mms/u0a46 (adj 15): empty #31
,08-31 15:25:15.877  1014  1480 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:15.887  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 15:25:15.897  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.897  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.897  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:15.897  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:15.907  6649  6649 E Zygote  : MountEmulatedStorage(),
08-31 15:25:15.907  6649  6649 I libpersona: KNOX_SDCARD checking this for 10002
08-31 15:25:15.907  6649  6649 E Zygote  : v2
08-31 15:25:15.907  6649  6649 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:15.907  6649  6649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:15.907  6649  6649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:15.907  6649  6649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 15:25:15.907  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6649 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:15.937  6649  6649 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:15.937  6649  6649 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:15.947  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-31 15:25:15.947  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 15:25:15.947  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:15.947  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.947  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-31 15:25:15.947  6509  6509 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-31 15:25:15.947  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 15:25:15.947  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 15:25:15.947  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:15.957  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:15.957  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:15.967  1014  1027 D CountryDetector: No listener is left
,08-31 15:25:15.977  1014  4552 I ActivityManager: Killing 5945:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-31 15:25:15.997  1014  1026 I ActivityManager: Killing 5965:com.wsomacp/u0a25 (adj 15): empty #31
,08-31 15:25:15.997  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 15:25:16.007  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.007  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.007  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.007  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.017  6681  6681 E Zygote  : MountEmulatedStorage()
08-31 15:25:16.017  6681  6681 E Zygote  : v2
08-31 15:25:16.017  6681  6681 I libpersona: KNOX_SDCARD checking this for 1000
08-31 15:25:16.017  6681  6681 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:16.017  6681  6681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-31 15:25:16.017  1014  1026 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6681 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-31 15:25:16.027  1014  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:16.027  6681  6681 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:16.027  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:16.027  1014  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:16.027  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 15:25:16.027  6681  6681 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:16.037  6596  6596 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-31 15:25:16.047  6681  6681 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:16.047  6681  6681 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:16.047  6596  6596 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8797-8798)
,08-31 15:25:16.047  6596  6596 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:25:16.057  6596  6596 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {152b898b}
,08-31 15:25:16.057  6596  6596 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 15:25:16.057  6596  6596 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 15:25:16.077  6596  6596 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 15:25:16.077  6596  6596 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 15:25:16.077  6596  6596 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 15:25:16.087  6681  6681 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 15:25:16.097  6596  6596 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-31 15:25:16.097  6596  6596 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-31 15:25:16.097  6596  6596 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-31 15:25:16.107  6596  6596 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 15:25:16.107  6596  6596 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 15:25:16.107  6596  6596 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 15:25:16.107  6596  6596 I Adreno-EGL: Local Branch: 
08-31 15:25:16.107  6596  6596 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 15:25:16.107  6596  6596 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 15:25:16.107  6596  6596 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 15:25:16.127  1014  1076 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 15:25:16.127  1014  1076 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 15:25:16.127  1014  1076 D SecContentProvider2: mCursor = null
,08-31 15:25:16.127  1014  1076 D WifiService: setWifiEnabled: true pid=6186, uid=10155
,08-31 15:25:16.127  1014  1076 W ActivityManager: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 15:25:16.137  1014  1076 W WifiService: Failed getting userId using ActivityManagerNative
08-31 15:25:16.137  1014  1076 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 15:25:16.137  1014  1076 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 15:25:16.137  1014  1076 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 15:25:16.137  1014  1076 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 15:25:16.137  1014  1076 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 15:25:16.137  1014  1076 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 15:25:16.137  1014  1076 D SettingsProvider: name = wifi_on
,08-31 15:25:16.137  1014  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 15:25:16.177   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-31 15:25:16.177  6596  6710 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-31 15:25:16.187  6596  6596 I NSApplication: Starting up...
,08-31 15:25:16.217  1014  1251 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 15:25:16.217  6681  6681 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 15:25:16.217  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.217  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.217  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.217  1014  1251 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.227  6681  6681 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
08-31 15:25:16.227  6681  6681 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-31 15:25:16.227  6681  6681 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 15:25:16.227  6681  6681 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
08-31 15:25:16.227  6681  6681 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-31 15:25:16.237  6715  6715 E Zygote  : MountEmulatedStorage()
,08-31 15:25:16.237  1014  1251 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6715 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:16.237  1014  1251 I ActivityManager: Killing 5986:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-31 15:25:16.237  6715  6715 E Zygote  : v2
08-31 15:25:16.237  6715  6715 I libpersona: KNOX_SDCARD checking this for 10120
08-31 15:25:16.237  6715  6715 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:16.237  1014  1251 I ActivityManager: Killing 5870:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-31 15:25:16.237  6715  6715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:16.247  6715  6715 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:16.247  6715  6715 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 15:25:16.267  6715  6715 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:16.267  6715  6715 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:16.277  6715  6715 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 15:25:16.527  1014  1041 D Tethering: interfaceAdded wlan0
,08-31 15:25:16.527  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 15:25:16.527  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:16.527  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:16.537  1014  1130 E Tethering: No numeric data
,08-31 15:25:16.547   277   973 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-31 15:25:16.547   277   973 D SoftapController: Softap fwReload - Ok
,08-31 15:25:16.547  1014  1041 D Tethering: interfaceAdded p2p0
,08-31 15:25:16.547  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 15:25:16.547  1014  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:25:16.547  1014  1130 D Tethering: clearTetheredNotification()
08-31 15:25:16.547  1014  1130 D Tethering: InitialState.processMessage what=4
,08-31 15:25:16.547  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:16.547  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:16.547  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-31 15:25:16.547  1014  1130 E Tethering: No numeric data
,08-31 15:25:16.547   277   973 D CommandListener: Setting iface cfg
08-31 15:25:16.547   277   973 D CommandListener: Trying to bring down wlan0
,08-31 15:25:16.547  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:16.547  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 15:25:16.557   277   973 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:16.557  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:16.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:16.557  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:16.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 15:25:16.557  1014  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:16.557  1014  1130 D Tethering: clearTetheredNotification()
08-31 15:25:16.557  1014  1124 V NetworkStats: performPollLocked() took 7ms,
08-31 15:25:16.557  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:16.557  1014  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 15:25:16.557  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:16.557  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:16.557  1014  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-31 15:25:16.567  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:16.567  1014  1127 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-31 15:25:16.567  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:16.567  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:16.567  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:16.567  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:16.567  1014  1124 V NetworkStats: performPollLocked() took 5ms
,08-31 15:25:16.577  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:16.577  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:16.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:16.577  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 15:25:16.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:16.577  1178  1178 D HotspotTile: onReceive : 2, 0
08-31 15:25:16.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:16.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:16.577  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:16.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:16.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-31 15:25:16.577  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:16.587  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:16.587  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:16.587  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:16.587  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:16.587  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:16.587  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:16.617  6742  6742 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-31 15:25:16.617  6742  6742 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-31 15:25:16.617  6742  6742 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 15:25:16.627  1014  2928 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
08-31 15:25:16.637  1014  2928 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.637  1014  2928 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.637  1014  2928 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:16.637  1014  2928 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:16.637  6742  6742 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 15:25:16.637   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6742
,08-31 15:25:16.637   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 15:25:16.637  6742  6742 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 15:25:16.637  6742  6742 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:16.637  6742  6742 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 15:25:16.637  6742  6742 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 15:25:16.637   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6742
08-31 15:25:16.637   406   406 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-31 15:25:16.647  1014  2928 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6745 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-31 15:25:16.647  1014  2928 I ActivityManager: Killing 5851:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-31 15:25:16.657  6745  6745 E Zygote  : MountEmulatedStorage()
,08-31 15:25:16.657  6745  6745 I libpersona: KNOX_SDCARD checking this for 10125
08-31 15:25:16.657  6745  6745 E Zygote  : v2
08-31 15:25:16.657  6745  6745 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:16.657  6745  6745 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:16.657  6745  6745 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:16.657  6745  6745 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:16.677  6745  6745 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:16.677  6745  6745 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:16.687  6745  6745 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:16.687  6745  6745 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 15:25:16.687  6745  6745 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 15:25:16.707  6745  6745 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:16.707  6745  6745 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 15:25:16.707  6745  6745 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 15:25:16.707  1014  1027 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 15:25:16.717  1014  1027 I ActivityManager: Killing 6049:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-31 15:25:16.727  1014  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:16.727  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:16.727  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:16.727  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:16.727  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:16.727  3632  3632 I Hs20UtilService: Starting #12
,08-31 15:25:16.727  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:16.727  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:16.727  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:16.727  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:16.727  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:16.807   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-31 15:25:16.807  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-31 15:25:16.877  6742  6742 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 15:25:16.877  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 15:25:16.887  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-31 15:25:16.887   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6742
08-31 15:25:16.887   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 15:25:16.887  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-31 15:25:16.887  6742  6742 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:16.887  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:16.887  6742  6742 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:16.887  6742  6742 E wpa_supplicant: SIM READ ERROR
08-31 15:25:16.887  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:16.887  6742  6742 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-31 15:25:16.887  6742  6742 E wpa_supplicant: SIM READ ERROR
08-31 15:25:16.887  6742  6742 I wpa_supplicant: Blacklist: Clear (all) 
08-31 15:25:16.887  6742  6742 I wpa_supplicant: wpa_default_ap_write_once
08-31 15:25:16.887  6742  6742 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 15:25:16.887  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:16.887  6742  6742 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 15:25:16.887  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:16.887  6742  6742 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 15:25:16.887  6742  6742 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-31 15:25:16.887  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:16.887  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:16.887  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:17.007  6742  6742 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 15:25:17.137  6742  6742 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 15:25:17.137  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 15:25:17.147  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-31 15:25:17.147   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6742
08-31 15:25:17.147   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-31 15:25:17.147  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-31 15:25:17.147  6742  6742 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:17.147  6742  6742 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 15:25:17.147  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-31 15:25:17.167  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-31 15:25:17.167   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6742
08-31 15:25:17.167   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 15:25:17.167  6742  6742 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-31 15:25:17.167  6742  6742 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:17.167  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:17.167  6742  6742 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-31 15:25:17.167  6742  6742 E wpa_supplicant: SIM READ ERROR
08-31 15:25:17.167  6742  6742 I wpa_supplicant: wpa_default_ap_write_once
08-31 15:25:17.167  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:17.167  6742  6742 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 15:25:17.167  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:17.167  6742  6742 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 15:25:17.167  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:17.167  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-31 15:25:17.177  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:17.177  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-31 15:25:17.217  6742  6742 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 15:25:17.217  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 15:25:17.327  6742  6742 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-31 15:25:17.327  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 15:25:17.327  6742  6742 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 15:25:17.517  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 15:25:17.517  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:17.517  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-31 15:25:17.567  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 15:25:17.567  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 15:25:17.567  6742  6742 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 15:25:17.567  6742  6742 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:17.577  6742  6742 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:17.577  6742  6742 E wpa_supplicant: SIM READ ERROR
08-31 15:25:17.577  6742  6742 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 15:25:17.607  6742  6742 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-31 15:25:17.617  1014  1127 D WifiNative-wlan0: callSECApiInt - ID [210],
,08-31 15:25:17.617  6742  6742 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 15:25:17.617  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:17.617  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:17.617  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:17.617  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:17.617  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:17.617  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:17.617  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:17.617  1014  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:25:17.627  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 15:25:17.627  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:17.627  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 15:25:17.627  1178  1178 D HotspotTile: onReceive : 3, 0
,08-31 15:25:17.627  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:17.637  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:17.637  1014  2928 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:17.637  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:17.637  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:17.637  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:17.637  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:17.637  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:17.637  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:17.637  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:17.637  1014  1127 E WifiConfigStore: Not a HS20
,08-31 15:25:17.637  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:17.637  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:17.637  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 15:25:17.637  1014  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 15:25:17.637  3632  3632 I Hs20UtilService: Starting #13
,08-31 15:25:17.637  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:17.647  1014  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 15:25:17.647  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 15:25:17.647  6742  6742 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 15:25:17.647  6742  6742 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-31 15:25:17.647  6742  6742 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 15:25:17.647  6742  6742 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 15:25:17.647  6742  6742 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 15:25:17.647  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 15:25:17.647  6742  6742 I wpa_supplicant: First Scan Start
,08-31 15:25:17.647  6742  6742 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 15:25:17.647  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 15:25:17.647  1014  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-31 15:25:17.647  1014  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:17.647  1014  1127 I WifiNative-HAL: startHal
08-31 15:25:17.647  1014  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9e16288c
08-31 15:25:17.647  1014  1127 I WifiNative-HAL: Could not start hal
,08-31 15:25:17.647  6432  6432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:25:17.657  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:17.657  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:17.657  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:17.657  1014  1127 E WifiNative-wlan0: do suspend true
,08-31 15:25:17.657  1014  1126 D WifiP2pService: P2pDisabledState{ what=131203 },
,08-31 15:25:17.657   277   973 D CommandListener: Setting iface cfg
08-31 15:25:17.657   277   973 D CommandListener: Trying to bring up p2p0
,08-31 15:25:17.657  1014  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:25:17.657  1014  1126 D WifiP2pService: P2pEnablingState
08-31 15:25:17.657  1014  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 15:25:17.657  1014  1126 D WifiP2pService: P2p socket connection successful
08-31 15:25:17.657  1014  1126 D WifiP2pService: P2pEnabledState
,08-31 15:25:17.667  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 15:25:17.667  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 15:25:17.667  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-31 15:25:17.667  1014  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 15:25:17.667  1014  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 15:25:17.667  1014  1127 E WifiNative-wlan0: invaild command id : 215
08-31 15:25:17.667  1014  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:17.667  1014  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 15:25:17.667  1014  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 15:25:17.667  1014  1127 E WifiNative-wlan0: invaild command id : 215
08-31 15:25:17.667  1014  1149 D WifiScanningService: DefaultState got{ when=-3ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:17.667  1014  1149 I WifiNative-HAL: startHal
08-31 15:25:17.667  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d0339bc
08-31 15:25:17.667  1014  1149 I WifiNative-HAL: Could not start hal
08-31 15:25:17.667  1014  1149 E WifiScanningService: could not start HAL
,08-31 15:25:17.667  6742  6742 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 15:25:17.677  6742  6742 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 15:25:17.677  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 15:25:17.677  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:17.677  6742  6742 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-31 15:25:17.677  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
,08-31 15:25:17.677  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 15:25:17.677  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-31 15:25:17.677  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:17.677  1014  1044 D WifiDisplayController: disconnect
,08-31 15:25:17.677  1014  1127 D SecContentProvider2: mCursor = null
08-31 15:25:17.677  1014  1044 D WifiDisplayController: updateConnection
08-31 15:25:17.677  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 15:25:17.677  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:17.677  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 15:25:17.677  1014  1991 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 15:25:17.677  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 15:25:17.687  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:17.687  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-31 15:25:17.687  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 15:25:17.687  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 15:25:17.687  1014  1126 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 15:25:17.687  1014  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-31 15:25:17.687  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:17.687  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:17.687  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 15:25:17.687  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:17.687  1014  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-31 15:25:17.687  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 15:25:17.687  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  secondary type: null
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  wps: 0
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  grpcapab: 0
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  devcapab: 0
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  status: 3
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  wfdInfo: null
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-31 15:25:17.687  1014  1044 D WifiDisplayController:  SConnectInfo : null
,08-31 15:25:17.687  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:17.687  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:17.687  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 15:25:17.697  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:17.697  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:17.697  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 15:25:17.697  6401  6401 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 15:25:17.697  6416  6416 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:17.717  1014  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-31 15:25:17.717  1014  1126 D WifiP2pService: InactiveState
,08-31 15:25:17.717  1014  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-31 15:25:17.717  1014  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 15:25:17.717  6742  6742 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-31 15:25:17.717  1014  1126 D WifiP2pService: InactiveState{ what=143376 }
,08-31 15:25:17.717  1014  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 15:25:18.147   287   287 E SMD     : DCD OFF,
,08-31 15:25:18.887  6742  6742 I wpa_supplicant: nl80211: Received scan results (20 BSSes),
08-31 15:25:18.887  6742  6742 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 15:25:18.887  6742  6742 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-31 15:25:18.887  6742  6742 I wpa_supplicant: Trying to associate with  'G700'
08-31 15:25:18.887  6742  6742 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 15:25:18.887  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 15:25:18.897  1014  6763 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-31 15:25:18.907  1014  1039 I ActivityManager: Killing 6071:com.samsung.helphub/1000 (adj 15): empty #31
,08-31 15:25:18.907  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:18.907  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:19.007  6742  6742 E wpa_supplicant: Cmd 35605 not handled
,08-31 15:25:19.007  6742  6742 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 15:25:19.007  6742  6742 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-31 15:25:19.007  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.007  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.007  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:19.007  6742  6742 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-31 15:25:19.007  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 15:25:19.007  6742  6742 I wpa_supplicant: Associated with F4.99.3E
08-31 15:25:19.007  6742  6742 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 15:25:19.007  6742  6742 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 15:25:19.007  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 15:25:19.007  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.007  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.007  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:19.007  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 15:25:19.007  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.007  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:19.017  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 15:25:19.017  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 15:25:19.017  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,08-31 15:25:19.017  1014  1130 E Tethering: No numeric data
,08-31 15:25:19.017  1014  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:25:19.017  1014  1130 D Tethering: clearTetheredNotification()
,08-31 15:25:19.017  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
,08-31 15:25:19.017  6742  6742 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 15:25:19.017  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:19.017  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:19.017  6742  6742 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 15:25:19.017  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:19.027  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:19.027  6742  6742 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-31 15:25:19.027  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 15:25:19.027  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:19.027  6742  6742 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-31 15:25:19.027  6742  6742 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-31 15:25:19.027  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:19.027  1014  1127 D SecContentProvider2: mCursor = null,
08-31 15:25:19.027  6742  6742 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,08-31 15:25:19.027  6742  6742 I wpa_supplicant: Blacklist: Clear (temp) 
,08-31 15:25:19.027  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 15:25:19.027  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-31 15:25:19.037  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:19.037  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:19.037  1014  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 15:25:19.037  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:19.037  1014  1124 V NetworkStats: performPollLocked() took 18ms
,08-31 15:25:19.047  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
08-31 15:25:19.047  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
08-31 15:25:19.047  1014  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 15:25:19.047  1014  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 15:25:19.047  1014  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 15:25:19.047  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:19.047  1014  1129 E ConnectivityService: updateNetworkInfo()
,08-31 15:25:19.057  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.057  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:19.057  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.057  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.057  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.057  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.057  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-31 15:25:19.057  1014  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-31 15:25:19.057  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:19.057  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-31 15:25:19.057  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-31 15:25:19.057  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:19.057  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:19.057  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:19.067  3632  3632 I Hs20UtilService: Starting #14
08-31 15:25:19.067  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:19.067  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:19.067  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:19.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:19.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:19.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:19.067  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:19.077  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:25:19.077  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:19.087   277   973 D CommandListener: Setting iface cfg
,08-31 15:25:19.087  1014  1127 E WifiStateMachine: Start Dhcp Watchdog 2
,08-31 15:25:19.087  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 15:25:19.087  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:19.097  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.097  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 15:25:19.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.107  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.107  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 15:25:19.107  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:19.117  1014  1127 E WifiNative-wlan0: do suspend false
,08-31 15:25:19.117  1014  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-31 15:25:19.117  1014  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 15:25:19.147  1014  1991 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 15:25:19.147  1014  1991 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-31 15:25:19.147  1014  1991 D SecContentProvider2: mCursor = null
,08-31 15:25:19.147  1014  1991 D WifiService: setWifiEnabled: false pid=6186, uid=10155
,08-31 15:25:19.147  1014  1991 D SettingsProvider: name = wifi_on
,08-31 15:25:19.167  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:25:19.177  1014  1127 E WifiNative-wlan0: do suspend true,
,08-31 15:25:19.197  1014  1126 D WifiP2pService: InactiveState{ what=143375 },
,08-31 15:25:19.197  1014  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 15:25:19.207  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.207  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:19.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.207   277   973 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:19.207  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:19.217  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:19.217  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:19.217  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-31 15:25:19.217  1014  1127 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-31 15:25:19.217   277   973 E Netd    : no such netId 503
,08-31 15:25:19.217  1014  1126 D WifiP2pService: InactiveState{ what=131204 },
08-31 15:25:19.217  1014  1126 D WifiP2pService: P2pEnabledState{ what=131204 }
08-31 15:25:19.217  1014  1129 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)',
08-31 15:25:19.217  1014  1129 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-31 15:25:19.217  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-31 15:25:19.217  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:19.217  1014  1129 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-31 15:25:19.217  1014  6769 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:19.217  1014  6769 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-31 15:25:19.217  1014  1129 D ConnectivityService: nai.networkMonitor.doQuit()
08-31 15:25:19.217  1014  1129 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 15:25:19.217  1014  1129 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-31 15:25:19.217  1014  1129 E ConnectivityService: updateNetworkInfo()
,08-31 15:25:19.227  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.227  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 15:25:19.227  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.227  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.227  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.227  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.227  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
,08-31 15:25:19.237  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:19.237  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-31 15:25:19.237  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:19.237  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-31 15:25:19.237  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,08-31 15:25:19.237  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 15:25:19.237  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-31 15:25:19.237  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 15:25:19.237  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:19.247  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 15:25:19.247  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-31 15:25:19.247  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 15:25:19.247  1014  1044 D WifiDisplayController: disconnect
08-31 15:25:19.247  1014  1044 D WifiDisplayController: updateConnection
08-31 15:25:19.247  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 15:25:19.247  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:19.247  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:19.247  1014  1126 D WifiP2pService: P2pDisablingState
,08-31 15:25:19.247  1014  1126 D WifiP2pService: P2pDisablingState{ what=147458 }
08-31 15:25:19.247  1014  1126 D WifiP2pService: p2p socket connection lost
,08-31 15:25:19.247  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:19.247  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:19.247  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:19.247  1014  1126 D WifiP2pService: P2pDisabledState
08-31 15:25:19.247  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 15:25:19.247  3632  3632 I Hs20UtilService: Starting #15
08-31 15:25:19.247  1014  1127 E WifiNative-wlan0: do suspend true
,08-31 15:25:19.247  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:19.247  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-31 15:25:19.247  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-31 15:25:19.247  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-31 15:25:19.247  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 15:25:19.257  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-31 15:25:19.257  1014  1076 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:19.257  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-31 15:25:19.257  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:19.257  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:19.257  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:19.267  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:19.267  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:19.267  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:19.267  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:19.277  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 15:25:19.277  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:19.277  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:19.277  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:19.277  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:19.277  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:19.277  1014  1126 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-31 15:25:19.277  1014  1126 D WifiP2pService: DefaultState{ what=143375 }
08-31 15:25:19.277  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:19.287  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:19.287  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:19.287  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.287  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.287  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.287  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.287   277   973 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:19.287  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:19.287  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:19.287  6742  6742 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-31 15:25:19.297  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 15:25:19.297  6401  6401 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.297  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.297  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:19.297  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:19.297  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:19.297  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:19.307  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-31 15:25:19.307  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 15:25:19.307  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-31 15:25:19.307  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:19.307  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:19.307  1178  1178 D HotspotTile: onReceive : 0, 0
,08-31 15:25:19.307  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:19.307  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:19.307  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:19.307  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:19.307  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:19.307  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:19.307  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:19.317  6416  6416 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-31 15:25:19.327  6772  6772 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 15:25:19.327  6772  6772 I dhcpcd  : version 5.5.6 starting
,08-31 15:25:19.337  1014  1076 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-31 15:25:19.337  6772  6772 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-31 15:25:19.337  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:19.337  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:19.337  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:19.337  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:19.337  3632  3632 I Hs20UtilService: Starting #16
,08-31 15:25:19.337  3632  3681 I Hs20UtilService: Message received 5007
08-31 15:25:19.337  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:19.347  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-31 15:25:19.347  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-31 15:25:19.347  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 15:25:19.347  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
08-31 15:25:19.347  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:19.357  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:19.357  1014  1312 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:19.357  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-31 15:25:19.357  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:19.357  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:19.357  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:19.367  3632  3632 I Hs20UtilService: Starting #17,
,08-31 15:25:19.367  3632  3681 I Hs20UtilService: Message received 5011,
,08-31 15:25:19.367  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:19.367  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
08-31 15:25:19.367  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:19.367  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:19.397  6772  6772 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 15:25:19.397  6772  6772 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-31 15:25:19.397  6772  6772 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-31 15:25:19.397  6772  6772 I dhcpcd  : bssid match,
08-31 15:25:19.397  6772  6772 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-31 15:25:19.397  6742  6742 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 15:25:19.467  6772  6772 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,08-31 15:25:19.517  6742  6742 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-31 15:25:19.517  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:19.517  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:19.517  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-31 15:25:19.547  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-31 15:25:19.547  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.547  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:19.547  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.547  1014  1130 D Tethering: InitialState.processMessage what=4
,08-31 15:25:19.557  1014  1127 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-31 15:25:19.547  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.557  1014  1124 V NetworkStats: performPollLocked(flags=0x1),
08-31 15:25:19.547  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:19.547  1014  1130 E Tethering: No numeric data,
08-31 15:25:19.557  1014  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
,08-31 15:25:19.557  1014  1130 D Tethering: clearTetheredNotification()
,08-31 15:25:19.557  6742  6742 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-31 15:25:19.557  6742  6742 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-31 15:25:19.557  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 15:25:19.557  6742  6742 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-31 15:25:19.557  1178  1178 D HotspotTile: updateTetherState():false, false
08-31 15:25:19.557  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:19.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:19.557  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:19.557  6742  6742 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-31 15:25:19.557  6742  6742 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 15:25:19.567  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-31 15:25:19.567  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:19.567  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:19.567  1014  1124 V NetworkStats: performPollLocked() took 11ms
,08-31 15:25:19.567  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:19.567  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:19.567  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:19.627  6772  6772 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-31 15:25:20.007  6742  6742 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 15:25:20.007  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:20.007  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:20.007  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:20.087  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:20.087  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:20.087  1014  1041 D Tethering: interfaceStatusChanged wlan0, false,
08-31 15:25:20.087  6742  6742 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-31 15:25:20.197  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-31 15:25:20.197  6432  6432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 15:25:20.197  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-31 15:25:20.197  1014  1127 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 15:25:20.207  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:20.207  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:20.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:20.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:20.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:20.207  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:20.207  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:20.207  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-31 15:25:20.207  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 15:25:20.217  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:20.217  1178  1178 D HotspotTile: onReceive : 1, 0
,08-31 15:25:20.217  1926  2119 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:25:20.217  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:20.227  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:20.227  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:20.227  1014  1991 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:20.227  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:20.227  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.227  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:20.227  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:20.237  3632  3632 I Hs20UtilService: Starting #18
,08-31 15:25:20.237  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:20.237  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:20.237  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:20.237  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:20.247  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:20.827  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.827  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.827  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.837  1014  1991 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-31 15:25:20.837  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-31 15:25:20.837  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.837  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:20.837  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 15:25:20.837  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-31 15:25:20.837  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-31 15:25:20.837  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:20.837  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.837  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.847  6596  6642 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-31 15:25:20.847  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.847  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.847  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.857  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:20.857  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-31 15:25:20.857  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:20.857  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:20.867  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-31 15:25:20.867  1014  2928 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 15:25:20.867  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
08-31 15:25:20.867  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.867  1014  2928 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.867  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.877  1014  1312 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:20.877  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 15:25:20.877  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:20.877  1014  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.877  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.887  1014  1076 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-31 15:25:20.887  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-31 15:25:20.887  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.887  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.887  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.897  1014  1041 D Tethering: interfaceRemoved wlan0
,08-31 15:25:20.897  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-31 15:25:20.897   277   967 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-31 15:25:20.907  1014  1991 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:20.917  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:20.917  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:20.917  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-31 15:25:20.917  1926  1926 D WearableService: callingUid 10012, callindPid: 1926
,08-31 15:25:20.937  1014  1991 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 15:25:20.937  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-31 15:25:20.937  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:20.937  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:20.937  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 15:25:20.977  6509  6509 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-31 15:25:20.987  6509  6802 I MusicLeanback: Conditions not met for autocaching.
,08-31 15:25:20.987  6509  6802 I MusicLeanback: Stop autocaching.
,08-31 15:25:20.987  6509  6807 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-31 15:25:21.107  1014  1041 D Tethering: interfaceRemoved p2p0
,08-31 15:25:21.107  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-31 15:25:21.157   287   287 E SMD     : DCD OFF
,08-31 15:25:21.907  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-31 15:25:22.167  6186  6238 D BluetoothAdapter: enable()
,08-31 15:25:22.167  1014  1076 W ActivityManager: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 15:25:22.167  1014  1076 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-31 15:25:22.167  1014  1076 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 15:25:22.167  1014  1076 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.167  1014  1076 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.167  1014  1076 D SettingsProvider: name = bluetooth_on,
,08-31 15:25:22.177  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.177  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.177  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-31 15:25:22.177  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 15:25:22.217  6475  6475 D BluetoothAdapterState: make
,08-31 15:25:22.217  6475  6475 I bluedroid: init
,08-31 15:25:22.227  6475  6809 I BluetoothAdapterState: Entering OffState
,08-31 15:25:22.227  6475  6475 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 15:25:22.227  6475  6475 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:25:22.227  6475  6475 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:25:22.227  6475  6475 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 15:25:22.227  6475  6475 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-31 15:25:22.227  6475  6475 I bluedroid: get_profile_interface socket
08-31 15:25:22.227  6475  6475 I bluedroid: get_profile_interface map_client
,08-31 15:25:22.227  6475  6812 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 15:25:22.227  6475  6475 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 15:25:22.237  6475  6812 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 15:25:22.237  6475  6812 E BluetoothServiceJni: populateRssiValuesNative
08-31 15:25:22.237  6475  6812 I bluedroid: getModelRssiValues
08-31 15:25:22.237  6475  6812 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 15:25:22.237  6475  6812 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 15:25:22.237  6475  6475 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:22.237  6475  6812 D BluetoothAdapterProperties: Name is: A5-1
08-31 15:25:22.237  1014  1014 D SettingsProvider: name = bluetooth_name
,08-31 15:25:22.237  1014  1076 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 15:25:22.237  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.237  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:22.237  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.237  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.247  6475  6484 I bluedroid: config_hci_snoop_log
,08-31 15:25:22.247  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-31 15:25:22.247  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
08-31 15:25:22.247  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 15:25:22.247  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
08-31 15:25:22.247  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 15:25:22.257  6475  6475 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 15:25:22.267  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.267  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:22.267  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 15:25:22.267  6475  6809 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 15:25:22.267  6475  6809 D BluetoothAdapterProperties: Setting state to 11
08-31 15:25:22.267  6475  6809 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 15:25:22.267  6475  6809 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 15:25:22.267  6475  6809 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 15:25:22.267  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 15:25:22.267  6475  6809 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:22.267  6475  6809 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 15:25:22.277  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:22.277  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-31 15:25:22.277  6475  6809 D BluetoothSecureManager: getInstant: null
08-31 15:25:22.277  6475  6809 D BluetoothSecureManager: calling getMethod for getService
08-31 15:25:22.277  6475  6809 D BluetoothSecureManager: calling getService
,08-31 15:25:22.277  6475  6809 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1d45affd
,08-31 15:25:22.277  1014  1312 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 15:25:22.277  1014  1312 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 15:25:22.277  6475  6809 D BtConfig.SecureMode: isSecureModeOn:false
08-31 15:25:22.277  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 15:25:22.287  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 15:25:22.287  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:22.287  1178  1178 D BluetoothTile:  getBluetoothState : 11
08-31 15:25:22.287  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 15:25:22.287  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:22.287  1785  1785 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 15:25:22.297  1014  1312 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:22.297  1014  1746 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 15:25:22.297  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 15:25:22.297  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-31 15:25:22.297  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:22.297  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:22.297  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 15:25:22.297  6475  6809 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 15:25:22.307  6475  6809 D BluetoothBondStateMachine: make
,08-31 15:25:22.307  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:22.307  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:22.307  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:22.307  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.307  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:22.307  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:22.307  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:22.307  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 15:25:22.307  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 15:25:22.307  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 15:25:22.307  1014  1991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:22.307  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.307  6475  6814 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 15:25:22.307  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.307  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.307  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.317  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 15:25:22.317  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 15:25:22.317  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:22.317  6475  6475 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 15:25:22.317  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:22.317  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-31 15:25:22.317  6475  6475 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:25:22.317  6475  6475 D BtGatt.GattService: start()
08-31 15:25:22.317  6475  6475 D BtGatt.GattService: start()
08-31 15:25:22.317  6475  6475 I bluedroid: get_profile_interface gatt
08-31 15:25:22.317  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.317  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.317  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.317  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:22.317  6475  6475 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:25:22.317  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 15:25:22.317  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 15:25:22.317  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:22.317  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:22.327  1014  4552 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:22.327  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.327  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.327  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.327  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.327  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 15:25:22.327  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:22.327  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 15:25:22.327  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:22.327  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-31 15:25:22.327  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:22.337  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.327  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 15:25:22.337  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.337  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.337  6475  6475 D BtGatt.GattService: mStartError = false,
08-31 15:25:22.337  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.337  6475  6475 D HeadsetService: Received start request. Starting profile...
08-31 15:25:22.337  6475  6475 D HeadsetService: start()
,08-31 15:25:22.337  6475  6475 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:25:22.337  6475  6475 D HeadsetStateMachine: make
,08-31 15:25:22.337  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 15:25:22.337  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 15:25:22.337  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 15:25:22.337  6475  6475 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 15:25:22.347  1014  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:22.347  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.347  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.347  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.347  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.347  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 15:25:22.347  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 15:25:22.347  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 15:25:22.357  1014  4552 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:22.357  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.357  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:22.357  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.357  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.357  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 15:25:22.357  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.357  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.357  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 15:25:22.357  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:22.357  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:22.357  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.357  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 15:25:22.357  1014  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:22.357  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.357  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:22.367  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:22.367  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.367  1014  1076 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 15:25:22.367  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.367  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:22.367  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.367  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 15:25:22.367  6475  6475 I bluedroid: get_profile_interface handsfree
,08-31 15:25:22.367  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 15:25:22.367  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 15:25:22.367  6475  6809 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 15:25:22.367  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:22.367  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 15:25:22.377  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:22.377  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:22.377  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:22.377  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:22.377  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 15:25:22.377  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-31 15:25:22.377  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 15:25:22.377  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 15:25:22.377  6475  6809 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 15:25:22.387  6475  6475 I DualScoManager: Instantiating Dual Sco Manager
,08-31 15:25:22.387  6475  6475 I DualScoManager: Set HeadsetServiceHelper
,08-31 15:25:22.387  6475  6475 D BluetoothAtMessage: createCMTIContentObservers
,08-31 15:25:22.387  1014  1991 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 15:25:22.387  1014  1991 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:22.387  1014  1991 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:22.387  1014  1991 D SettingsProvider: selectionArgs: false
08-31 15:25:22.387  1014  1991 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:22.387  1014  1991 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:22.387  1014  1991 D SettingsProvider: ret = -1
08-31 15:25:22.387  6475  6818 D HeadsetStateMachine: Enter Disconnected: -2
08-31 15:25:22.387  6475  6475 D HeadsetService: mStartError = false
,08-31 15:25:22.387  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.397  6475  6818 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-31 15:25:22.397  6475  6818 D HeadsetStateMachine: map size, before remove : 0
,08-31 15:25:22.397  6475  6818 D HeadsetStateMachine: map size, after remove: 0
,08-31 15:25:22.397  6475  6475 D A2dpService: Received start request. Starting profile...
08-31 15:25:22.397  6475  6475 D A2dpService: start()
,08-31 15:25:22.397  6475  6475 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:25:22.397  6475  6475 I bluedroid: get_profile_interface avrcp
,08-31 15:25:22.397  6475  6475 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:25:22.417  6475  6475 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 15:25:22.417  6475  6822 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-31 15:25:22.417  6475  6475 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:25:22.417  6475  6475 D A2dpStateMachine: make
,08-31 15:25:22.427  6475  6475 I bluedroid: get_profile_interface a2dp
,08-31 15:25:22.427  6475  6824 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 15:25:22.427  6475  6475 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 15:25:22.427  6475  6475 D A2dpService: mStartError = false
08-31 15:25:22.427  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.427  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 15:25:22.427  6475  6475 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:25:22.427  6475  6823 D A2dpStateMachine: Enter Disconnected: -2
08-31 15:25:22.427  6475  6475 D HidService: Received start request. Starting profile...
08-31 15:25:22.427  6475  6475 D HidService: start()
08-31 15:25:22.427  6475  6475 I bluedroid: get_profile_interface hidhost
08-31 15:25:22.427  6475  6475 D HidService: setHidService(): set to: null
08-31 15:25:22.427  6475  6475 D HidService: mStartError = false
08-31 15:25:22.427  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.427  6475  6475 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 15:25:22.427  6475  6475 D HealthService: Received start request. Starting profile...
08-31 15:25:22.427  6475  6475 D HealthService: start()
,08-31 15:25:22.427  6475  6475 I bluedroid: get_profile_interface health
,08-31 15:25:22.427  6475  6475 D HealthService: mStartError = false
08-31 15:25:22.427  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.437  6475  6475 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:25:22.437  6475  6475 D PanService: Received start request. Starting profile...
,08-31 15:25:22.437  6475  6475 D PanService: start()
08-31 15:25:22.437  6475  6475 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:25:22.437  6475  6475 I bluedroid: get_profile_interface pan
,08-31 15:25:22.437  6475  6475 D PanService: mStartError = false
08-31 15:25:22.437  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:22.437  6475  6475 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 15:25:22.437  1430  2721 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 15:25:22.437  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 15:25:22.437  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 15:25:22.447  1430  2721 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 15:25:22.447  6475  6475 D BluetoothMapService: Received start request. Starting profile...
08-31 15:25:22.447  6475  6475 D BluetoothMapService: start()
,08-31 15:25:22.447  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:22.447  6475  6475 D BluetoothMapService: mStartError = false
08-31 15:25:22.447  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:22.447  6475  6475 D HeadsetStateMachine: Proxy object connected
,08-31 15:25:22.447  6475  6475 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 15:25:22.447  6475  6475 D SapService: Received start request. Starting profile...
08-31 15:25:22.447  6475  6475 D SapService: start()
08-31 15:25:22.447  6475  6475 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 15:25:22.447  6475  6475 I bluedroid: get_profile_interface sap
08-31 15:25:22.447  6475  6475 D SapService: mStartError = false
08-31 15:25:22.447  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:22.447  6475  6475 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 15:25:22.447  6475  6475 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 15:25:22.447  6475  6475 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 15:25:22.447  6475  6475 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 15:25:22.447  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-31 15:25:22.447  6475  6475 D BluetoothA2dp: Proxy object connected
08-31 15:25:22.447  6475  6475 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 15:25:22.447  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 15:25:22.447  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 15:25:22.447  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-31 15:25:22.447  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 15:25:22.447  6475  6818 D HeadsetStateMachine: Disconnected process message: 11
08-31 15:25:22.447  6475  6818 D HeadsetStateMachine: Disconnected process message: 18
08-31 15:25:22.447  6475  6818 D HeadsetStateMachine: Disconnected process message: 10
,08-31 15:25:22.457  6475  6818 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-31 15:25:22.457  6475  6818 D HeadsetStateMachine: Disconnected process message: 11
,08-31 15:25:22.457  6475  6822 D BluetoothMediaBrowser: no now playing list
08-31 15:25:22.457  6475  6822 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 15:25:22.457  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:22.477  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 15:25:22.477  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 15:25:22.477  6475  6809 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 15:25:22.477  6475  6809 I bluedroid: enable
,08-31 15:25:22.477  6475  6809 I bt_hci_bdroid: init
,08-31 15:25:22.487  6475  6828 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 15:25:22.487  6475  6809 I bt_vendor: bt-vendor : init
,08-31 15:25:22.487  6475  6809 I bt_vendor: bt-vendor : get_bt_soc_type
,08-31 15:25:22.487  6475  6809 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:25:22.487  6475  6809 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-31 15:25:22.487  6475  6809 D bt_userial_mct: userial_init
,08-31 15:25:22.487  6475  6809 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 15:25:22.487  6475  6809 I bt_vendor: Starting hciattach daemon
,08-31 15:25:22.487  6475  6809 I bt_vendor: try to set false
,08-31 15:25:22.487  6475  6809 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 15:25:22.487  6475  6809 I bt_vendor: Starting hciattach daemon
08-31 15:25:22.487  6475  6809 I bt_vendor: try to set true
,08-31 15:25:22.507  6832  6832 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-31 15:25:22.547  6838  6838 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 15:25:22.557  6839  6839 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 15:25:22.577  6841  6841 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 15:25:22.587  6842  6842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 15:25:22.587  6843  6843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 15:25:22.597  6844  6844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 15:25:22.817  6847  6847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-31 15:25:22.827  6848  6848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 15:25:22.837  6475  6809 I bt_vendor: bluetooth satus is on
08-31 15:25:22.837  6475  6830 D bt_userial_mct: userial_open(port:0)
08-31 15:25:22.837  6475  6830 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 15:25:22.847  6475  6830 I bt_vendor: Done intiailizing UART,
,08-31 15:25:22.847  6475  6830 I bt_vendor: Done intiailizing UART
,08-31 15:25:22.847  6475  6830 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-31 15:25:22.847  6475  6830 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-31 15:25:22.857  6475  6850 D bt_userial_mct: Entering userial_read_thread()
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_A2D
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_PAN
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_SDP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_GATT
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_SMP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-31 15:25:22.867  6475  6828 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 15:25:22.967  6475  6828 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 15:25:22.977  6475  6828 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40b46e9 
,08-31 15:25:22.977  6475  6828 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40b46e9 
,08-31 15:25:22.987  6475  6812 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 15:25:22.997  6475  6812 E bt-btif : Calling BTA_HhEnable
,08-31 15:25:22.997  6475  6812 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 15:25:22.997  6475  6812 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 15:25:22.997  6475  6812 E BluetoothServiceJni: populateRssiValuesNative
,08-31 15:25:22.997  6475  6812 I bluedroid: getModelRssiValues
,08-31 15:25:22.997  6475  6812 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 15:25:22.997  6475  6812 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 15:25:23.007  6475  6812 D BluetoothAdapterProperties: Name is: A5-1,
08-31 15:25:23.007  1014  1014 D SettingsProvider: name = bluetooth_name
,08-31 15:25:23.007  6475  6812 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 15:25:23.007  6475  6812 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:23.007  6475  6812 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:25:23.007  6475  6812 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-31 15:25:23.007  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:23.007  6475  6812 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 15:25:23.007  6475  6812 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 15:25:23.007  6475  6812 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-31 15:25:23.007  6475  6812 E bt-btif : btif_sock_init: !vhci_init
,08-31 15:25:23.017  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:23.017  6475  6812 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 15:25:23.017  6475  6812 D IOP_DB_BT: db_open: db_open : handle 3028566032l, read 13894 bytes onto local cache
,08-31 15:25:23.017  6475  6812 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 15:25:23.017  6475  6812 D IOP_DB_BT: db_query: result 1
,08-31 15:25:23.017  6475  6850 E bt_mct  : hci lib postload completed
08-31 15:25:23.017  6475  6812 I         : iop_db_open: iop_db_open status 0
,08-31 15:25:23.017  6475  6812 D bte_conf: Device ID record 1 : primary
,08-31 15:25:23.017  6475  6812 D bte_conf:   vendorId            = 0075
,08-31 15:25:23.017  6475  6812 D bte_conf:   vendorIdSource      = 0001
,08-31 15:25:23.017  6475  6812 D bte_conf:   product             = 0100
,08-31 15:25:23.017  6475  6812 D bte_conf:   version             = 0200
,08-31 15:25:23.017  6475  6812 D bte_conf:   clientExecutableURL = 
,08-31 15:25:23.027  6475  6812 D bte_conf:   serviceDescription  = 
08-31 15:25:23.027  6475  6812 D bte_conf:   documentationURL    = 
08-31 15:25:23.027  6475  6812 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 15:25:23.027  6475  6812 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 15:25:23.027  6475  6809 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 15:25:23.027  6475  6809 D BluetoothAdapterProperties: ScanMode =  20
,08-31 15:25:23.027  6475  6809 D BluetoothAdapterProperties: State =  11
,08-31 15:25:23.027  1014  4552 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 15:25:23.027  6475  6809 D BluetoothAdapterProperties: Setting state to 12
08-31 15:25:23.027  6475  6809 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 15:25:23.037  6475  6812 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 15:25:23.037  6475  6812 D BluetoothAdapterProperties: Scan Mode:21
,08-31 15:25:23.037  6475  6812 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:25:23.037  1014  1319 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 15:25:23.037  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:23.037  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:23.037  1014  1319 D SettingsProvider: selectionArgs: false
08-31 15:25:23.037  1014  1319 D SettingsProvider: selectionArgs: 1002
08-31 15:25:23.037  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:23.037  1014  1319 D SettingsProvider: ret = -1
,08-31 15:25:23.037  6475  6809 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 15:25:23.037  6475  6809 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 15:25:23.037  1014  4552 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:23.047  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.047  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.047  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:23.047  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.057  6475  6809 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:23.057  6475  6809 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 15:25:23.057  6475  6809 D BluetoothAdapterService: starting service from this receiver
,08-31 15:25:23.057  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:23.057  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.057  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.057  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:23.057  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.057  6475  6809 I BluetoothAdapterState: Entering On State from state = 11
,08-31 15:25:23.057  1291  1301 D Bluetoothsap: onBluetoothStateChange: up=true
,08-31 15:25:23.057  1291  1301 D Bluetoothsap: Binding service...
,08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:23.067  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:23.067  1291  1301 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 15:25:23.067  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 15:25:23.067  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.067  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.067  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.067  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.077  1291  1301 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 15:25:23.077  6186  6194 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 15:25:23.077  6186  6194 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.077  1440  1455 D BluetoothAdapter: onBluetoothStateChange: up=true,
,08-31 15:25:23.077  1440  1455 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.087  1430  1441 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.087  1430  1441 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 15:25:23.087  6475  6483 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:23.087  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.087  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-31 15:25:23.087  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:23.087  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.087  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 15:25:23.087  6475  6475 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 15:25:23.087  1291  1303 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.087  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 15:25:23.087  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:23.087  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:23.097  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.097  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.097  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.097  1291  1303 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:23.097  1291  1301 D BluetoothMap: onBluetoothStateChange: up=true,
,08-31 15:25:23.097  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:23.097  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 15:25:23.097  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.097  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.097  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.097  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.107  1291  1303 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-31 15:25:23.107  6475  6475 I BluetoothPbapService: Handler(): got msg=1,
08-31 15:25:23.107  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 15:25:23.107  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-31 15:25:23.107  1014  2928 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 15:25:23.107  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.107  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.107  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.107  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 15:25:23.107  1291  1291 D SapProfile: Bluetooth service connected
08-31 15:25:23.107  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-31 15:25:23.107  1430  1444 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.107  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 15:25:23.117  6475  6855 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 15:25:23.117  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 15:25:23.117  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.117  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.117  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.117  1430  1444 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 15:25:23.117  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-31 15:25:23.117  1926  2108 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 15:25:23.117  1926  2108 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.117  2863  2879 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:23.127  2863  2879 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.127  1291  1291 D BluetoothMap: Proxy object connected
08-31 15:25:23.127  1291  1291 D MapProfile: Bluetooth service connected
08-31 15:25:23.127  1291  1291 D BluetoothMap: getConnectedDevices()
,08-31 15:25:23.127  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 15:25:23.127  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.127  6475  6855 D BluetoothSocket: bindListen(): myUserId = 0
08-31 15:25:23.127  6475  6855 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:23.127  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.127  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.127  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.127  6475  6855 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-31 15:25:23.127  6475  6855 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:23.127  6475  6855 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 15:25:23.127  6475  6855 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7294f11
08-31 15:25:23.127  1291  1291 D BluetoothInputDevice: Proxy object connected
08-31 15:25:23.127  1291  1291 D HidProfile: Bluetooth service connected
,08-31 15:25:23.127  6475  6855 D BluetoothSocket: channel: 19
08-31 15:25:23.137  6475  6855 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 15:25:23.137  2863  2874 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.137  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 15:25:23.137  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.137  2863  2863 D BluetoothA2dp: Proxy object connected
,08-31 15:25:23.137  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.137  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.137  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.137  2863  2874 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:23.137  1014  1043 D BluetoothPan: Binding service...
,08-31 15:25:23.137  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 15:25:23.137  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.137  1291  1303 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:25:23.137  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:25:23.147  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 15:25:23.147  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.147  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.147  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.147  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.147  2863  6856 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 15:25:23.147  2863  6856 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.147  1291  1291 D BluetoothPbap: Proxy object connected
08-31 15:25:23.147  1291  1291 D PbapServerProfile: Bluetooth service connected
08-31 15:25:23.147  1291  1301 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:23.147  1291  1301 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.147  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 15:25:23.147  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.147  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.147  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.147  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.147  1291  1291 D BluetoothA2dp: Proxy object connected
,08-31 15:25:23.147  1430  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.147  1291  1291 D A2dpProfile: Bluetooth service connected
,08-31 15:25:23.157  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:23.157  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.157  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.157  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.157  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.157  1430  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:23.157  1178  1188 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 15:25:23.157  1178  1188 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  6475  6483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.157  6475  6483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  1291  1301 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.157  1291  1301 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  1430  2721 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.157  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:23.157  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.157  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.157  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.157  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.157  1430  2721 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:23.157  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.157  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  1457  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.157  1457  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  6347  6362 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:23.157  6347  6362 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:23.157  1457  1906 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.167  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:23.167  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:23.167  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.167  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:23.167  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
08-31 15:25:23.167  1457  1906 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:23.167  1291  6853 D BluetoothPan: Binding service...
,08-31 15:25:23.167  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 15:25:23.167  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.167  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.167  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.167  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.167  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 15:25:23.167  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:23.167  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 15:25:23.167  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.167  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 15:25:23.167  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 15:25:23.167  1014  1014 D BluetoothA2dp: Proxy object connected
,08-31 15:25:23.177  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:25:23.177  1291  1291 D PanProfile: Bluetooth service connected
,08-31 15:25:23.177  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1f5c8cb4, true
,08-31 15:25:23.177  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 15:25:23.177  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 15:25:23.177  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:23.177  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-31 15:25:23.177  1430  1430 D BluetoothHeadset: registerMessageListener
,08-31 15:25:23.187  1785  1785 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:23.187  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:23.187  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.187  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.187  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:23.187  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:23.187  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:23.187  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:23.187  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-31 15:25:23.187  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 15:25:23.187  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:23.187  6475  6813 D HeadsetService: registerMessageListener
,08-31 15:25:23.187  6475  6859 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-31 15:25:23.187  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:23.187  6475  6813 D HeadsetService: registerMessageListener
08-31 15:25:23.187  6475  6818 D HeadsetStateMachine: Disconnected process message: 70
,08-31 15:25:23.187  6475  6818 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1ad40876
08-31 15:25:23.187  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 15:25:23.187  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 15:25:23.197  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:23.187  1014  1991 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 15:25:23.187  1014  1991 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 15:25:23.197  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:23.197  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-31 15:25:23.197  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 15:25:23.197  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 15:25:23.197  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 15:25:23.197  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null,
,08-31 15:25:23.197  6475  6859 D BluetoothSocket: bindListen(): myUserId = 0
08-31 15:25:23.197  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 15:25:23.197  6475  6859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:23.197  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 15:25:23.197  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 15:25:23.207  6475  6859 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-31 15:25:23.207  6475  6859 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:23.207  6475  6859 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-31 15:25:23.207  6475  6859 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@81fbe77
08-31 15:25:23.207  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
08-31 15:25:23.207  6475  6859 D BluetoothSocket: channel: 5
,08-31 15:25:23.207  6475  6818 D HeadsetStateMachine: Disconnected process message: 9
,08-31 15:25:23.207  6475  6818 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 15:25:23.207  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:23.207  1014  2928 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 15:25:23.207  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.207  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.207  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:23.207  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:23.217   282   696 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-31 15:25:23.217   282   696 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 15:25:23.217   282   696 V voice   : voice_set_parameters: exit with code(-2)
08-31 15:25:23.217   282   696 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 15:25:23.217   282   696 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 15:25:23.217   282   696 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 15:25:23.217   282   696 V audio_hw_primary: adev_set_parameters: exit
,08-31 15:25:23.217  6475  6818 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 15:25:23.227  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:23.227  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:23.237  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:23.237  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 15:25:23.237  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:23.237  6475  6475 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 15:25:23.237  1014  1991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:23.237  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.247  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.247  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:23.247  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:23.257  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:23.257  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:23.257  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:23.257  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.257  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:23.257  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:23.267  1014  2928 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 15:25:23.267  1926  6865 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-31 15:25:23.267  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:23.287  6475  6869 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 15:25:23.287  6475  6869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:23.287  6475  6869 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-31 15:25:23.287  6475  6869 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:23.287  6475  6869 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 15:25:23.287  6475  6869 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38c7cb13
,08-31 15:25:23.287  6475  6869 D BluetoothSocket: channel: 12
,08-31 15:25:23.287  6475  6869 I BtOppRfcommListener: Accept thread started.
,08-31 15:25:23.357  1926  2104 I art     : Explicit concurrent mark sweep GC freed 63123(3MB) AllocSpace objects, 49(1909KB) LOS objects, 40% free, 14MB/24MB, paused 1.390ms total 80.375ms
,08-31 15:25:23.437  1014  1493 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 15:25:23.437  1014  1493 D BatteryService: level:62, scale:100, status:2, health:2, present:true, voltage: 3891, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 15:25:23.437  1014  1493 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 15:25:23.437  1014  1493 D BatteryService: stay LED for charging
08-31 15:25:23.437  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 15:25:23.437  1014  1014 I MotionRecognitionService: Plugged
,08-31 15:25:23.437  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 15:25:23.437  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 15:25:23.437  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 15:25:23.437  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 15:25:23.437  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 62
,08-31 15:25:23.447  6475  6475 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 15:25:23.447  6475  6818 D HeadsetStateMachine: Disconnected process message: 10
,08-31 15:25:23.467  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:23.467  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:23.467  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:23.517  1014  1251 I art     : Explicit concurrent mark sweep GC freed 65100(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.370ms total 158.209ms
,08-31 15:25:23.517  1014  1251 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:23.517  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:23.517  1014  1251 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:23.517  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:23.527  1014  1991 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:23.527  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:23.527  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:23.527  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:23.537  1926  6865 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 15:25:23.797  1014  2773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 15:25:24.157   287   287 E SMD     : DCD OFF
,08-31 15:25:24.557  1014  2730 D SSRM:n  : SIOP:: AP = 340
,08-31 15:25:25.187  6186  6238 D BluetoothAdapter: disable()
,08-31 15:25:25.187  1014  4552 D SettingsProvider: name = bluetooth_on
,08-31 15:25:25.197  6475  6809 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-31 15:25:25.197  6475  6809 D BluetoothAdapterProperties: Setting state to 13
,08-31 15:25:25.197  6475  6809 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-31 15:25:25.197  6475  6809 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-31 15:25:25.197  6475  6809 D BluetoothAdapterService: updateAdapterState state is 13
08-31 15:25:25.197  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 15:25:25.197  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.207  1014  1746 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:25.207  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.207  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-31 15:25:25.207  6475  6809 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:25.207  6475  6809 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13,
08-31 15:25:25.207  6475  6809 D BluetoothAdapterService: terminating service from this receiver
,08-31 15:25:25.207  6475  6475 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13,
08-31 15:25:25.207  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.207  6475  6475 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30a37150, channel: 19, state: LISTENING
,08-31 15:25:25.217  6475  6475 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30a37150, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7294f11, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@35fdcf49mSocket: android.net.LocalSocket@2dafb04e impl:android.net.LocalSocketImpl@25da056f fd:FileDescriptor[75]
,08-31 15:25:25.217  6475  6475 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2dafb04e impl:android.net.LocalSocketImpl@25da056f fd:FileDescriptor[75]
,08-31 15:25:25.217  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:25.217  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:25.217  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.217  6475  6809 D BluetoothAdapterProperties: onBluetoothDisable()
,08-31 15:25:25.217  6475  6809 D BluetoothAdapterProperties: mDiscovering is false
,08-31 15:25:25.217  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-31 15:25:25.217  6475  6809 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-31 15:25:25.227  1291  1291 D BluetoothPbap: Proxy object disconnected
,08-31 15:25:25.227  1291  1291 D PbapServerProfile: Bluetooth service disconnected
,08-31 15:25:25.227  6475  6812 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 15:25:25.227  6475  6812 D BluetoothAdapterProperties: Scan Mode:20
,08-31 15:25:25.227  6475  6809 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-31 15:25:25.227  6475  6809 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-31 15:25:25.237  6475  6809 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-31 15:25:25.237  6475  6809 E bt-btif : HAL bt_hal_cbacks->log_co
,08-31 15:25:25.237  6475  6809 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 15:25:25.237  6475  6869 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-31 15:25:25.237  6475  6828 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-31 15:25:25.237  6475  6828 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-31 15:25:25.237  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:25.237  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:25.237  6475  6828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-31 15:25:25.237  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:25.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:25.247  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:25.247  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:25.247  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:25.247  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:25.247  6186  6186 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 15:25:25.257  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:25.257  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.257  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-31 15:25:25.267  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 15:25:25.267  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 15:25:25.277  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.277  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-31 15:25:25.277  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:25.277  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:25.277  1014  1076 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:25.277  1785  1785 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:25.287  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 15:25:25.287  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 15:25:25.287  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.287  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 15:25:25.287  6475  6475 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@fcb1705, channel: 5, state: LISTENING
08-31 15:25:25.287  6475  6475 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@fcb1705, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@81fbe77, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d5a835amSocket: android.net.LocalSocket@152b898b impl:android.net.LocalSocketImpl@33f41a68 fd:FileDescriptor[77]
08-31 15:25:25.287  6475  6475 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@152b898b impl:android.net.LocalSocketImpl@33f41a68 fd:FileDescriptor[77]
,08-31 15:25:25.287  6475  6475 I BtOppRfcommListener: stopping Accept Thread
,08-31 15:25:25.287  6475  6475 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@136b1e81, channel: 12, state: LISTENING
,08-31 15:25:25.297  6475  6475 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@136b1e81, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38c7cb13, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ad7b26mSocket: android.net.LocalSocket@ac73367 impl:android.net.LocalSocketImpl@31247514 fd:FileDescriptor[81]
,08-31 15:25:25.297  6475  6475 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ac73367 impl:android.net.LocalSocketImpl@31247514 fd:FileDescriptor[81]
,08-31 15:25:25.297  6475  6869 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-31 15:25:25.297  1014  1746 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:25.297  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.297  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.297  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:25.297  1014  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:25.297  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:25.297  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:25.297  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:25.297  1014  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 15:25:25.297  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.307  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.307  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.307  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:25.307  6475  6475 V BluetoothOppManager: cleanUp...
,08-31 15:25:25.337  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:25.337  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:25.337  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:25.337  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-31 15:25:25.357  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:25.357  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:25.407  1014  1337 E Watchdog: !@Sync 4
,08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-31 15:25:25.437  6475  6828 W bt-btif : ag scb idx 1 not allocated
08-31 15:25:25.437  6475  6828 W bt-btif : ag scb idx 2 not allocated
08-31 15:25:25.437  6475  6828 E bt-btif : BTA AG is already disabled, ignoring ...
08-31 15:25:25.437  6475  6850 I bt_userial_mct: exiting userial_read_thread
08-31 15:25:25.437  6475  6850 D bt_userial_mct: Leaving userial_evt_read_thread()
08-31 15:25:25.437  6475  6812 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-31 15:25:25.437  6475  6830 I bt_vendor: hw_epilog_process
08-31 15:25:25.437  6475  6812 D bt_userial_mct: userial_close
08-31 15:25:25.437  6475  6812 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-31 15:25:25.807  6475  6812 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-31 15:25:25.807  6475  6812 I bt_vendor: bluetooth satus is on
08-31 15:25:25.807  6475  6812 I bt_vendor: bt-vendor : resetting BT status
08-31 15:25:25.807  6475  6812 I bt_vendor: Starting hciattach daemon
08-31 15:25:25.807  6475  6812 I bt_vendor: try to set false
,08-31 15:25:25.807  6475  6812 I bt_vendor: Starting hciattach daemon
08-31 15:25:25.807  6475  6812 I bt_vendor: try to set false
,08-31 15:25:25.807  6475  6812 I bt_vendor: cleanup
,08-31 15:25:25.807  6475  6828 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-31 15:25:25.807  6475  6812 I GKI_LINUX: GKI_exit_task 0 done
08-31 15:25:25.807  6475  6812 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-31 15:25:25.807  6475  6809 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-31 15:25:25.807  6475  6809 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 15:25:25.807  6475  6809 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
,08-31 15:25:25.807  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-31 15:25:25.807  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 15:25:25.807  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 15:25:25.817  1014  2928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 15:25:25.817  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.817  1014  2928 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:25.817  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:25.817  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.817  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-31 15:25:25.817  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:25.817  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
08-31 15:25:25.817  6475  6475 D BtGatt.DebugUtils: handleDebugAction() action=null,
08-31 15:25:25.817  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-31 15:25:25.817  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
,08-31 15:25:25.827  6475  6475 D BtGatt.GattService: Received stop request...Stopping profile...,
08-31 15:25:25.827  6475  6475 D BtGatt.GattService: stop()
08-31 15:25:25.827  6475  6475 D BtGatt.AdvertiseManager: advertise clients cleared
08-31 15:25:25.827  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.827  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.827  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:25.827  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 15:25:25.827  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 15:25:25.827  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 15:25:25.827  1014  1991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:25.827  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:25.827  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-31 15:25:25.827  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.827  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.827  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.827  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 15:25:25.827  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:25.827  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:25.827  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.827  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-31 15:25:25.827  6475  6475 D HeadsetService: Received stop request...Stopping profile...
,08-31 15:25:25.837  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.837  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.837  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 15:25:25.837  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 15:25:25.837  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 15:25:25.837  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:25.837  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-31 15:25:25.837  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-31 15:25:25.837  1291  1291 D HeadsetProfile: Bluetooth service disconnected
,08-31 15:25:25.837  1014  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:25.837  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.837  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.837  1014  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.837  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.837  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-31 15:25:25.837  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 15:25:25.837  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 15:25:25.847  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:25.847  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.847  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:25.847  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:25.847  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-31 15:25:25.847  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:25.847  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:25.847  6475  6809 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:25.847  1014  2928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:25.847  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.857  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:25.857  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:25.857  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.857  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-31 15:25:25.857  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 15:25:25.857  6475  6809 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 15:25:25.857  1014  4552 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:25.857  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.857  1014  4552 W ActivityManager: userId = 0, bbcId = -10000,
,08-31 15:25:25.857  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:25.857  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
08-31 15:25:25.867  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-31 15:25:25.867  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService,
08-31 15:25:25.867  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
,08-31 15:25:25.867  6475  6809 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
08-31 15:25:25.867  6475  6809 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-31 15:25:25.867  6475  6809 D BluetoothAdapterState: Stopping profile services that were post enabled,
08-31 15:25:25.867  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-31 15:25:25.867  6475  6475 D A2dpService: Received stop request...Stopping profile...
,08-31 15:25:25.867  6475  6823 D A2dpStateMachine: Exit Disconnected: -1
08-31 15:25:25.877  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
08-31 15:25:25.877  1291  1291 D BluetoothA2dp: Proxy object disconnected
,08-31 15:25:25.877  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:25.877  1291  1291 D A2dpProfile: Bluetooth service disconnected
08-31 15:25:25.877  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-31 15:25:25.877  2863  2863 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:25.877  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-31 15:25:25.877  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:25.877  6475  6475 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-31 15:25:25.877  6475  6475 D HidService: Received stop request...Stopping profile...
08-31 15:25:25.877  6475  6475 D HidService: Stopping Bluetooth HidService
08-31 15:25:25.877  6475  6475 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-31 15:25:25.877  6475  6475 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-31 15:25:25.877  6475  6475 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-31 15:25:25.877  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:25.877  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-31 15:25:25.877  1291  1291 D HidProfile: Bluetooth service disconnected
,08-31 15:25:25.877  6475  6475 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-31 15:25:25.877  6475  6475 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-31 15:25:25.877  6475  6475 D HealthService: Received stop request...Stopping profile...
,08-31 15:25:25.887  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc,
,08-31 15:25:25.887  6475  6475 D PanService: Received stop request...Stopping profile...
,08-31 15:25:25.887  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:25.887  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:25:25.887  6475  6475 D BluetoothMapService: Received stop request...Stopping profile...
,08-31 15:25:25.887  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:25.897  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-31 15:25:25.897  1291  1291 D PanProfile: Bluetooth service disconnected
08-31 15:25:25.897  1291  1291 D BluetoothMap: Proxy object disconnected
08-31 15:25:25.897  1291  1291 D MapProfile: Bluetooth service disconnected
08-31 15:25:25.897  6475  6475 D SapService: Received stop request...Stopping profile...
08-31 15:25:25.897  6475  6475 D SapService: Stopping Bluetooth SapService
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a289bc
,08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-31 15:25:25.897  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-31 15:25:25.897  6475  6824 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-31 15:25:25.897  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-31 15:25:25.897  6475  6475 I GKI_LINUX: GKI_exit_task 2 done
08-31 15:25:25.897  6475  6475 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-31 15:25:25.897  6475  6475 D BluetoothA2dp: Proxy object disconnected
08-31 15:25:25.897  1291  1291 D SapProfile: Bluetooth service disconnected
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-31 15:25:25.897  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-31 15:25:25.897  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:25.897  6475  6475 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-31 15:25:25.897  6475  6475 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-31 15:25:25.897  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:25.897  6475  6475 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-31 15:25:25.897  6475  6475 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-31 15:25:25.897  6475  6475 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 15:25:25.897  6475  6475 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-31 15:25:25.897  6475  6475 E BluetoothAdapterService(44206524): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-31 15:25:25.897  6475  6475 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-31 15:25:25.897  6475  6475 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-31 15:25:25.907  6475  6809 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-31 15:25:25.907  6475  6809 D BluetoothAdapterProperties: Setting state to 10
08-31 15:25:25.907  6475  6809 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-31 15:25:25.907  6475  6809 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 15:25:25.907  6475  6809 D BluetoothAdapterService: updateAdapterState state is 10
,08-31 15:25:25.907  6475  6809 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:25.907  6475  6809 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-31 15:25:25.907  6475  6809 I BluetoothAdapterState: Entering OffState
08-31 15:25:25.907  1291  1301 D Bluetoothsap: onBluetoothStateChange: up=false
08-31 15:25:25.907  1291  1301 D Bluetoothsap: Unbinding service...
08-31 15:25:25.907  6186  6194 D BluetoothAdapter: onBluetoothStateChange: up=false
08-31 15:25:25.907  6186  6194 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-31 15:25:25.907  6186  6194 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-31 15:25:25.907  6186  6194 D BluetoothLeAdvertiser: Exit stop advertising
08-31 15:25:25.907  6186  6194 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-31 15:25:25.907  6186  6194 D BluetoothLeScanner: Exiting stopAllScan
,08-31 15:25:25.907  1440  1455 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.907  1440  1455 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.907  1430  1444 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.907  1430  1444 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.907  6475  6857 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:25.907  1291  1303 D BluetoothMap: onBluetoothStateChange: up=false
,08-31 15:25:25.907  1291  1301 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-31 15:25:25.917  1926  1936 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.917  1926  1936 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.917  2863  2879 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:25.917  1291  6853 D BluetoothPbap: onBluetoothStateChange: up=false
,08-31 15:25:25.917  2863  2874 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.917  2863  2874 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.917  1291  1303 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:25.917  1178  2712 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.917  1178  2712 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.917  6475  6858 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.917  6475  6858 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.927  1291  1301 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.927  1291  1301 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.927  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.927  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.927  1457  1692 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.927  1457  1692 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.927  6347  6360 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-31 15:25:25.927  6347  6360 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-31 15:25:25.927  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-31 15:25:25.927  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-31 15:25:25.937  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 15:25:25.937  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.937  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-31 15:25:25.937  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-31 15:25:25.947  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
,08-31 15:25:25.947  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-31 15:25:25.947  1178  1703 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
,08-31 15:25:25.947  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.947  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-31 15:25:25.947  1178  1703 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
,08-31 15:25:25.947  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:25.947  1178  1178 D BluetoothAdapter: 424506204: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:25.947  1785  1785 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:25.947  1014  1076 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:25.957  1014  4552 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 15:25:25.957  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:25.957  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 15:25:25.957  1926  2119 D BluetoothAdapter: 37864785: getState() :  mService = null. Returning STATE_OFF
,08-31 15:25:25.957  1926  2119 D BluetoothAdapter: 37864785: getState() :  mService = null. Returning STATE_OFF
08-31 15:25:25.957  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 15:25:25.957  6475  6812 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-31 15:25:25.957  6475  6475 I GKI_LINUX: GKI_exit_task 1 done
,08-31 15:25:25.957  6475  6475 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-31 15:25:25.957  6475  6475 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-31 15:25:25.957  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:25.957  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:25.957  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:25.957  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.957  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:25.957  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:25.957  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:25.967  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:25.967  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-31 15:25:25.967  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:25.967  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:25.967  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:25.967  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:25.977  6475  6475 I art     : System.exit called, status: 0
08-31 15:25:25.977  6475  6475 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-31 15:25:25.977  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:25.977  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:25.987  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:25.987  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-31 15:25:26.047  1014  4552 I ActivityManager: Process com.android.bluetooth (pid 6475)(adj 0) has died(63,1078)
,08-31 15:25:26.057  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:26.057  1014  1991 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-31 15:25:26.057  1014  1991 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:26.057  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:26.057  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:26.057  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:26.067  1926  6886 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 15:25:26.067  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:26.077  1014  1319 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:26.077  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:26.077  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:26.077  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:26.087  1926  6886 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-31 15:25:26.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:27.157   287   287 E SMD     : DCD OFF
,08-31 15:25:27.187   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:28.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:28.197  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
,08-31 15:25:28.197  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:29.177   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 15:25:29.517  1014  1974 V SAMP_SPCM_test: CSC File load.. 
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control,
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location,
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
,08-31 15:25:29.527  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-31 15:25:29.557  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-31 15:25:29.567  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-31 15:25:29.567  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-31 15:25:29.567  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-31 15:25:29.567  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application,
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth,
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-31 15:25:29.577  1014  1974 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-31 15:25:29.587  1014  1974 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-31 15:25:30.157   287   287 E SMD     : DCD OFF
,08-31 15:25:30.187   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 15:25:31.177   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-31 15:25:31.207  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:31.207  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1625924c added. We now have 6 listener(s)
,08-31 15:25:31.207  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:31.207  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:31.207  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@135aa295 added. We now have 7 listener(s)
,08-31 15:25:31.207  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:31.207  6186  6238 I System.out: IsBluetoothEnabled
,08-31 15:25:31.207  6186  6238 D BluetoothAdapter: disable()
,08-31 15:25:31.207  1014  4552 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-31 15:25:31.217  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:31.217  6186  6238 D BluetoothAdapter: enable()
,08-31 15:25:31.217  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 15:25:31.217  1014  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-31 15:25:31.217  1014  1026 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 15:25:31.217  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 15:25:31.217  1014  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:31.217  1014  1026 D SettingsProvider: name = bluetooth_on
,08-31 15:25:31.227  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 15:25:31.227  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:31.237  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-31 15:25:31.237  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 15:25:31.237  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:31.237  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:31.237  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:31.237  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:31.257  6892  6892 E Zygote  : MountEmulatedStorage()
08-31 15:25:31.257  6892  6892 I libpersona: KNOX_SDCARD checking this for 1002
08-31 15:25:31.257  6892  6892 E Zygote  : v2
,08-31 15:25:31.257  6892  6892 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:31.257  1014  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6892 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-31 15:25:31.257  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:31.267  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 15:25:31.267  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:31.297  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:31.297  6892  6892 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:31.307  6892  6892 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 15:25:31.307  6892  6892 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 15:25:31.337  6892  6892 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 15:25:31.367  6892  6892 D BtSettings.ProfileConfig: Adding GattService
,08-31 15:25:31.367  6892  6892 D BtSettings.ProfileConfig: Adding HeadsetService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding HidService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding HealthService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding PanService
,08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding SapService
,08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding SapClientService
08-31 15:25:31.377  6892  6892 D BtSettings.ProfileConfig: Adding HidDevService,
08-31 15:25:31.377  6892  6892 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 15:25:31.377  1014  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 15:25:31.377  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 15:25:31.377  1014  1480 D SettingsProvider: selectionArgs: false
08-31 15:25:31.377  1014  1480 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.377  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.377  1014  1480 D SettingsProvider: ret = -1,
08-31 15:25:31.377  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-31 15:25:31.377  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 15:25:31.377  1014  1027 D SettingsProvider: selectionArgs: false
08-31 15:25:31.377  1014  1027 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.377  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.377  1014  1027 D SettingsProvider: ret = -1
08-31 15:25:31.377  1014  1251 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 15:25:31.377  1014  1251 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  1251 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.377  1014  1251 D SettingsProvider: selectionArgs: false
08-31 15:25:31.377  1014  1251 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:31.377  1014  1251 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:31.377  1014  1251 D SettingsProvider: ret = -1
08-31 15:25:31.377  1014  4552 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-31 15:25:31.377  1014  4552 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  4552 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.377  1014  4552 D SettingsProvider: selectionArgs: false,
08-31 15:25:31.377  1014  4552 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.377  1014  4552 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.377  1014  4552 D SettingsProvider: ret = -1
08-31 15:25:31.377  1014  1746 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 15:25:31.377  1014  1746 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  1746 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.377  1014  1746 D SettingsProvider: selectionArgs: false
08-31 15:25:31.377  1014  1746 D SettingsProvider: selectionArgs: 1002,
08-31 15:25:31.377  1014  1746 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.377  1014  1746 D SettingsProvider: ret = -1
08-31 15:25:31.377  1014  1312 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-31 15:25:31.377  1014  1312 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.377  1014  1312 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.377  1014  1312 D SettingsProvider: selectionArgs: false
08-31 15:25:31.377  1014  1312 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.377  1014  1312 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.377  1014  1312 D SettingsProvider: ret = -1
08-31 15:25:31.387  1014  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 15:25:31.387  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,08-31 15:25:31.387  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  1319 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  1319 D SettingsProvider: selectionArgs: 1002,
08-31 15:25:31.387  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.387  1014  1319 D SettingsProvider: ret = -1
08-31 15:25:31.387  1014  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 15:25:31.387  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:31.387  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  1026 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:31.387  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.387  1014  1026 D SettingsProvider: ret = -1
08-31 15:25:31.387  1014  1991 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.387  1014  1991 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.387  1014  1991 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  1991 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  1991 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:31.387  1014  1991 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.387  1014  1991 D SettingsProvider: ret = -1
08-31 15:25:31.387  1014  2928 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:31.387  1014  2928 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.387  1014  2928 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  2928 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  2928 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.387  1014  2928 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 15:25:31.387  1014  2928 D SettingsProvider: ret = -1
08-31 15:25:31.387  1014  1076 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-31 15:25:31.387  1014  1076 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.387  1014  1076 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  1076 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  1076 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.387  1014  1076 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.387  1014  1076 D SettingsProvider: ret = -1
,08-31 15:25:31.387  1014  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 15:25:31.387  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.387  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.387  1014  1493 D SettingsProvider: selectionArgs: false
08-31 15:25:31.387  1014  1493 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.387  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.387  1014  1493 D SettingsProvider: ret = -1
,08-31 15:25:31.397  6892  6892 D BluetoothAdapterState: make
,08-31 15:25:31.407  6892  6892 I bluedroid: init,
08-31 15:25:31.407  6892  6907 I BluetoothAdapterState: Entering OffState
,08-31 15:25:31.407  6892  6892 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-31 15:25:31.407  6892  6892 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-31 15:25:31.407  6892  6892 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 15:25:31.407  6892  6892 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 15:25:31.407  6892  6892 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-31 15:25:31.407  6892  6892 I bluedroid: get_profile_interface socket
08-31 15:25:31.407  6892  6892 I bluedroid: get_profile_interface map_client
,08-31 15:25:31.407  6892  6910 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 15:25:31.407  6892  6892 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 15:25:31.417  6892  6910 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB,
08-31 15:25:31.417  6892  6910 E BluetoothServiceJni: populateRssiValuesNative
08-31 15:25:31.417  6892  6910 I bluedroid: getModelRssiValues
08-31 15:25:31.417  6892  6910 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 15:25:31.417  6892  6910 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-31 15:25:31.417  6892  6910 D BluetoothAdapterProperties: Name is: A5-1
,08-31 15:25:31.417  1014  1014 D SettingsProvider: name = bluetooth_name
,08-31 15:25:31.417  6892  6892 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:31.417  1014  1076 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 15:25:31.417  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.417  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.417  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.417  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.417  6892  6900 I bluedroid: config_hci_snoop_log
,08-31 15:25:31.427  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-31 15:25:31.427  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,08-31 15:25:31.427  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
08-31 15:25:31.427  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 15:25:31.427  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 15:25:31.427  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 15:25:31.427  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 15:25:31.427  6892  6892 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-31 15:25:31.437  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 15:25:31.437  6892  6907 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-31 15:25:31.437  6892  6907 D BluetoothAdapterProperties: Setting state to 11
08-31 15:25:31.437  6892  6907 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-31 15:25:31.437  6892  6907 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 15:25:31.437  6892  6907 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 15:25:31.437  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 15:25:31.437  6892  6907 D BluetoothAdapterService: Autoconnection is available 
,08-31 15:25:31.437  6892  6907 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 15:25:31.447  6892  6907 D BluetoothSecureManager: getInstant: null
08-31 15:25:31.447  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:31.447  6892  6907 D BluetoothSecureManager: calling getMethod for getService
08-31 15:25:31.447  6892  6907 D BluetoothSecureManager: calling getService
,08-31 15:25:31.447  6892  6907 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@166e07a7
08-31 15:25:31.447  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-31 15:25:31.447  1014  2928 D BluetoothSecureManagerService: isSecureModeEnabled
,08-31 15:25:31.447  1014  2928 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 15:25:31.447  6892  6907 D BtConfig.SecureMode: isSecureModeOn:false
08-31 15:25:31.447  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 15:25:31.447  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 15:25:31.447  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 15:25:31.457  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:31.457  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:31.457  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-31 15:25:31.457  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:31.457  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-31 15:25:31.457  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 15:25:31.457  1785  1785 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:31.457  1014  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.457  6892  6907 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.457  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 15:25:31.457  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ),
08-31 15:25:31.467  6892  6907 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:31.467  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 15:25:31.467  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:31.467  6892  6907 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 15:25:31.467  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 15:25:31.467  6892  6907 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-31 15:25:31.467  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-31 15:25:31.467  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 15:25:31.467  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.467  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.467  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:31.467  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:31.477  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:31.477  6892  6907 D BluetoothBondStateMachine: make
,08-31 15:25:31.477  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 15:25:31.477  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 15:25:31.477  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-31 15:25:31.477  6892  6912 I BluetoothBondStateMachine: StableState(): Entering Off State
08-31 15:25:31.477  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:31.477  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:31.477  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 15:25:31.477  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.487  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.487  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.487  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.487  6892  6892 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-31 15:25:31.487  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 15:25:31.487  6892  6892 D BtGatt.GattService: Received start request. Starting profile...
08-31 15:25:31.487  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 15:25:31.487  6892  6892 D BtGatt.GattService: start()
08-31 15:25:31.487  6892  6892 D BtGatt.GattService: start()
08-31 15:25:31.487  6892  6892 I bluedroid: get_profile_interface gatt
08-31 15:25:31.487  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 15:25:31.487  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
08-31 15:25:31.487  6892  6892 D BtGatt.AdvertiseManager: advertise manager created
,08-31 15:25:31.487  1014  1076 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:31.497  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.497  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:31.497  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.497  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.497  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 15:25:31.497  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 15:25:31.497  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-31 15:25:31.497  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:31.497  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.507  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:31.507  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.507  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.507  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 15:25:31.507  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 15:25:31.507  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 15:25:31.507  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:31.507  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.507  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:31.507  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:31.507  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.507  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 15:25:31.507  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 15:25:31.507  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 15:25:31.507  6892  6892 D BtGatt.GattService: mStartError = false
,08-31 15:25:31.507  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.517  1014  1746 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:31.517  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.517  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:31.517  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.517  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.517  6892  6892 D HeadsetService: Received start request. Starting profile...
08-31 15:25:31.517  6892  6892 D HeadsetService: start()
,08-31 15:25:31.517  6892  6892 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 15:25:31.517  6892  6892 D HeadsetStateMachine: make
08-31 15:25:31.517  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 15:25:31.517  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 15:25:31.517  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-31 15:25:31.517  6892  6892 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 15:25:31.517  1014  1076 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:31.517  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.527  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.527  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.527  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.527  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-31 15:25:31.527  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 15:25:31.527  6892  6907 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 15:25:31.527  1014  1480 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-31 15:25:31.527  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.527  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.527  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.527  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 15:25:31.537  1014  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:31.537  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.537  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.537  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.537  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.537  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-31 15:25:31.537  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.537  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 15:25:31.537  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 15:25:31.537  6892  6907 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-31 15:25:31.537  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:31.537  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.537  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 15:25:31.537  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:31.537  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 15:25:31.547  6892  6892 I bluedroid: get_profile_interface handsfree
,08-31 15:25:31.547  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:31.547  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:31.547  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.547  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:31.547  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 15:25:31.547  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 15:25:31.547  6892  6907 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 15:25:31.547  6892  6907 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 15:25:31.547  6892  6907 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 15:25:31.557  6892  6892 I DualScoManager: Instantiating Dual Sco Manager
,08-31 15:25:31.557  6892  6892 I DualScoManager: Set HeadsetServiceHelper
,08-31 15:25:31.567  6892  6892 D BluetoothAtMessage: createCMTIContentObservers
,08-31 15:25:31.567  1014  1493 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 15:25:31.567  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 15:25:31.567  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 15:25:31.567  1014  1493 D SettingsProvider: selectionArgs: false
,08-31 15:25:31.567  1014  1493 D SettingsProvider: selectionArgs: 1002
08-31 15:25:31.567  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:31.567  1014  1493 D SettingsProvider: ret = -1,
,08-31 15:25:31.567  6892  6915 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 15:25:31.567  6892  6892 D HeadsetService: mStartError = false
08-31 15:25:31.567  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.567  6892  6892 D A2dpService: Received start request. Starting profile...
08-31 15:25:31.567  6892  6892 D A2dpService: start()
08-31 15:25:31.567  6892  6892 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-31 15:25:31.577  6892  6892 I bluedroid: get_profile_interface avrcp
08-31 15:25:31.577  6892  6915 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 15:25:31.577  6892  6915 D HeadsetStateMachine: map size, before remove : 0
,08-31 15:25:31.577  6892  6915 D HeadsetStateMachine: map size, after remove: 0
,08-31 15:25:31.577  6892  6892 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 15:25:31.597  6892  6892 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-31 15:25:31.597  6892  6920 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 15:25:31.597  6892  6892 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 15:25:31.597  6892  6892 D A2dpStateMachine: make
,08-31 15:25:31.597  6892  6892 I bluedroid: get_profile_interface a2dp
08-31 15:25:31.597  6892  6922 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 15:25:31.597  6892  6892 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 15:25:31.597  6892  6892 D A2dpService: mStartError = false
08-31 15:25:31.597  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.597  6892  6921 D A2dpStateMachine: Enter Disconnected: -2
08-31 15:25:31.597  6892  6892 I BluetoothHidServiceJni: classInitNative: succeeds
,08-31 15:25:31.607  6892  6892 D HidService: Received start request. Starting profile...
08-31 15:25:31.607  6892  6892 D HidService: start()
08-31 15:25:31.607  6892  6892 I bluedroid: get_profile_interface hidhost
08-31 15:25:31.607  6892  6892 D HidService: setHidService(): set to: null
08-31 15:25:31.607  6892  6892 D HidService: mStartError = false
08-31 15:25:31.607  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.607  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-31 15:25:31.607  6892  6892 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-31 15:25:31.607  6892  6892 D HealthService: Received start request. Starting profile...
08-31 15:25:31.607  6892  6892 D HealthService: start()
,08-31 15:25:31.607  6892  6892 I bluedroid: get_profile_interface health
,08-31 15:25:31.607  6892  6892 D HealthService: mStartError = false
08-31 15:25:31.607  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.607  6892  6892 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 15:25:31.607  6892  6892 D PanService: Received start request. Starting profile...
08-31 15:25:31.607  6892  6892 D PanService: start()
08-31 15:25:31.607  6892  6892 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 15:25:31.607  6892  6892 I bluedroid: get_profile_interface pan
,08-31 15:25:31.617  6892  6892 D PanService: mStartError = false
08-31 15:25:31.617  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.617  6892  6892 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 15:25:31.617  1430  1441 I Telecom : BluetoothPhoneService: queryPhoneState
,08-31 15:25:31.617  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-31 15:25:31.617  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 15:25:31.617  1430  1441 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 15:25:31.617  6892  6920 D BluetoothMediaBrowser: no now playing list
08-31 15:25:31.617  6892  6920 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-31 15:25:31.617  6892  6892 D BluetoothMapService: Received start request. Starting profile...
08-31 15:25:31.617  6892  6892 D BluetoothMapService: start()
,08-31 15:25:31.627  6892  6892 D BluetoothMapService: mStartError = false
08-31 15:25:31.627  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:31.627  6892  6892 D HeadsetStateMachine: Proxy object connected
,08-31 15:25:31.627  6892  6892 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 15:25:31.627  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:31.627  6892  6892 D SapService: Received start request. Starting profile...
08-31 15:25:31.627  6892  6892 D SapService: start()
08-31 15:25:31.627  6892  6892 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 15:25:31.627  6892  6892 I bluedroid: get_profile_interface sap
08-31 15:25:31.627  6892  6892 D SapService: mStartError = false
08-31 15:25:31.627  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
08-31 15:25:31.627  6892  6892 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 15:25:31.627  6892  6892 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 15:25:31.627  6892  6892 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 15:25:31.627  6892  6915 D HeadsetStateMachine: Disconnected process message: 11
08-31 15:25:31.627  6892  6892 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 15:25:31.627  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-31 15:25:31.627  6892  6915 D HeadsetStateMachine: Disconnected process message: 18
08-31 15:25:31.627  6892  6915 D HeadsetStateMachine: Disconnected process message: 10
08-31 15:25:31.627  6892  6892 D BluetoothA2dp: Proxy object connected
08-31 15:25:31.627  6892  6892 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-31 15:25:31.627  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-31 15:25:31.627  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 15:25:31.627  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 15:25:31.627  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 15:25:31.627  6892  6915 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,08-31 15:25:31.627  6892  6915 D HeadsetStateMachine: Disconnected process message: 11
,08-31 15:25:31.637  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:31.657  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 15:25:31.657  6892  6892 E BluetoothAdapterService(225625486): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 15:25:31.657  6892  6907 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-31 15:25:31.657  6892  6907 I bluedroid: enable
,08-31 15:25:31.657  6892  6907 I bt_hci_bdroid: init
,08-31 15:25:31.657  6892  6927 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 15:25:31.657  6892  6907 I bt_vendor: bt-vendor : init
,08-31 15:25:31.657  6892  6907 I bt_vendor: bt-vendor : get_bt_soc_type
,08-31 15:25:31.657  6892  6907 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 15:25:31.667  6892  6907 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-31 15:25:31.667  6892  6907 D bt_userial_mct: userial_init
,08-31 15:25:31.667  6892  6907 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 15:25:31.667  6892  6907 I bt_vendor: Starting hciattach daemon
08-31 15:25:31.667  6892  6907 I bt_vendor: try to set false
,08-31 15:25:31.667  6892  6907 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 15:25:31.667  6892  6907 I bt_vendor: Starting hciattach daemon
08-31 15:25:31.667  6892  6907 I bt_vendor: try to set true
,08-31 15:25:31.677  6931  6931 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-31 15:25:31.737  6937  6937 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 15:25:31.737  6938  6938 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 15:25:31.757  6940  6940 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 15:25:31.767  6941  6941 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-31 15:25:31.777  6942  6942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-31 15:25:31.787  6943  6943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 15:25:31.987  6946  6946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-31 15:25:31.997  6947  6947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 15:25:32.027  6892  6907 I bt_vendor: bluetooth satus is on
,08-31 15:25:32.027  6892  6929 D bt_userial_mct: userial_open(port:0)
08-31 15:25:32.027  6892  6929 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 15:25:32.027  6892  6929 I bt_vendor: Done intiailizing UART,
,08-31 15:25:32.027  6892  6929 I bt_vendor: Done intiailizing UART,
08-31 15:25:32.027  6892  6929 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-31 15:25:32.027  6892  6929 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-31 15:25:32.037  6892  6949 D bt_userial_mct: Entering userial_read_thread()
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_HCI
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_GAP
,08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 15:25:32.037  6892  6927 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 15:25:32.047  6892  6927 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 15:25:32.147  6892  6927 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 15:25:32.147  6892  6927 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40b46e9 
,08-31 15:25:32.147  6892  6927 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40b46e9 
,08-31 15:25:32.167  6892  6910 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 15:25:32.167  6892  6910 E bt-btif : Calling BTA_HhEnable
,08-31 15:25:32.167  6892  6910 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 15:25:32.167  6892  6910 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 15:25:32.167  6892  6910 E BluetoothServiceJni: populateRssiValuesNative
,08-31 15:25:32.167  6892  6910 I bluedroid: getModelRssiValues
08-31 15:25:32.167  6892  6910 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-31 15:25:32.177  6892  6910 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-31 15:25:32.177  6892  6910 D BluetoothAdapterProperties: Name is: A5-1
08-31 15:25:32.177  1014  1014 D SettingsProvider: name = bluetooth_name
,08-31 15:25:32.177  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:32.187  6892  6910 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-31 15:25:32.187  6892  6910 D BluetoothAdapterProperties: Scan Mode:20
08-31 15:25:32.187  6892  6910 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 15:25:32.187  6892  6910 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-31 15:25:32.187  6892  6910 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 15:25:32.187  6892  6910 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 15:25:32.187  6892  6910 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-31 15:25:32.187  6892  6910 E bt-btif : btif_sock_init: !vhci_init
08-31 15:25:32.187  6892  6910 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 15:25:32.187  6892  6910 D IOP_DB_BT: db_open: db_open : handle 3026411536l, read 13894 bytes onto local cache
,08-31 15:25:32.187  6892  6910 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 15:25:32.187  6892  6910 D IOP_DB_BT: db_query: result 1
,08-31 15:25:32.187  6892  6910 I         : iop_db_open: iop_db_open status 0
,08-31 15:25:32.187  6892  6910 D bte_conf: Device ID record 1 : primary
,08-31 15:25:32.187  6892  6949 E bt_mct  : hci lib postload completed
,08-31 15:25:32.187  6892  6910 D bte_conf:   vendorId            = 0075
08-31 15:25:32.187  6892  6910 D bte_conf:   vendorIdSource      = 0001
,08-31 15:25:32.197  6892  6910 D bte_conf:   product             = 0100
08-31 15:25:32.197  6892  6910 D bte_conf:   version             = 0200
08-31 15:25:32.197  6892  6910 D bte_conf:   clientExecutableURL = 
08-31 15:25:32.197  6892  6910 D bte_conf:   serviceDescription  = 
08-31 15:25:32.197  6892  6910 D bte_conf:   documentationURL    = 
08-31 15:25:32.197  6892  6910 D bte_conf: bte_load_did_conf no section named DID2.
,08-31 15:25:32.197  6892  6910 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 15:25:32.197  6892  6907 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-31 15:25:32.197  6892  6907 D BluetoothAdapterProperties: ScanMode =  20
,08-31 15:25:32.197  6892  6907 D BluetoothAdapterProperties: State =  11
,08-31 15:25:32.197  1014  1312 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 15:25:32.197  6892  6907 D BluetoothAdapterProperties: Setting state to 12
,08-31 15:25:32.207  6892  6907 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-31 15:25:32.207  6892  6910 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 15:25:32.207  6892  6910 D BluetoothAdapterProperties: Scan Mode:21
08-31 15:25:32.207  6892  6910 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 15:25:32.207  1014  1319 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-31 15:25:32.207  1014  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 15:25:32.207  1014  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 15:25:32.207  1014  1319 D SettingsProvider: selectionArgs: false
,08-31 15:25:32.207  1014  1319 D SettingsProvider: selectionArgs: 1002
,08-31 15:25:32.217  1014  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 15:25:32.217  1014  1319 D SettingsProvider: ret = -1
,08-31 15:25:32.217  6892  6907 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-31 15:25:32.217  6892  6907 D BluetoothAdapterService: updateAdapterState state is 12
,08-31 15:25:32.217  1014  1251 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:32.217  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.217  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.217  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:32.217  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.237  6892  6907 D BluetoothAdapterService: Autoconnection is available 
08-31 15:25:32.237  6892  6907 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 15:25:32.237  6892  6907 D BluetoothAdapterService: starting service from this receiver
08-31 15:25:32.237  1291  6853 D Bluetoothsap: onBluetoothStateChange: up=true
08-31 15:25:32.237  1291  6853 D Bluetoothsap: Binding service...
,08-31 15:25:32.237  1014  1312 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 15:25:32.237  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.237  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.237  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.237  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.237  1291  6853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-31 15:25:32.237  6892  6907 I BluetoothAdapterState: Entering On State from state = 11
,08-31 15:25:32.237  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-31 15:25:32.237  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:32.237  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:32.237  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.237  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.237  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.237  1291  6853 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 15:25:32.247  6186  6195 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.247  6186  6195 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.247  1440  1739 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.247  1440  1739 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.247  1430  1444 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.247  1430  1444 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.247  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-31 15:25:32.247  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:32.247  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-31 15:25:32.247  6892  6892 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-31 15:25:32.247  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:32.247  1291  1301 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.247  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 15:25:32.247  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.247  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.247  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:32.247  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.247  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.257  1291  1301 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:32.257  1291  1303 D BluetoothMap: onBluetoothStateChange: up=true
,08-31 15:25:32.257  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 15:25:32.257  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.257  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.257  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.257  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:32.257  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:32.257  1291  6853 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-31 15:25:32.257  6892  6892 I BluetoothPbapService: Handler(): got msg=1
,08-31 15:25:32.267  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 15:25:32.267  1291  1291 D SapProfile: Bluetooth service connected
08-31 15:25:32.267  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-31 15:25:32.267  1014  4552 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 15:25:32.267  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:32.267  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:32.267  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f5ecfaa added. We now have 8 listener(s)
,08-31 15:25:32.267  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:32.277  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-31 15:25:32.277  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.277  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.277  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.277  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.277  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-31 15:25:32.277  6892  6953 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 15:25:32.277  1014  2928 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-31 15:25:32.277  1014  2928 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 15:25:32.277  1014  2928 D SecContentProvider2: mCursor = null
,08-31 15:25:32.277  1291  1291 D BluetoothMap: Proxy object connected
,08-31 15:25:32.277  1291  1291 D MapProfile: Bluetooth service connected
08-31 15:25:32.277  1291  1291 D BluetoothMap: getConnectedDevices()
08-31 15:25:32.277  1014  2928 D WifiService: setWifiEnabled: false pid=6186, uid=10155
,08-31 15:25:32.287  1014  2928 D SettingsProvider: name = wifi_on
,08-31 15:25:32.287  1430  2721 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.287  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:32.287  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.287  6892  6953 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 15:25:32.287  6892  6953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-31 15:25:32.287  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.287  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.287  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.287  1430  2721 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:32.287  1291  1291 D BluetoothInputDevice: Proxy object connected
,08-31 15:25:32.287  1291  1291 D HidProfile: Bluetooth service connected
08-31 15:25:32.287  1926  1936 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.287  1926  1936 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.287  2863  2874 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:32.287  6892  6953 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 15:25:32.287  6892  6953 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:32.287  6892  6953 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-31 15:25:32.287  6892  6953 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2066839b
08-31 15:25:32.287  6892  6953 D BluetoothSocket: channel: 19
08-31 15:25:32.287  6892  6953 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 15:25:32.297  2863  2874 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.297  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:32.297  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 15:25:32.297  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.297  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 15:25:32.297  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 15:25:32.297  1014  1026 D SecContentProvider2: mCursor = null
,08-31 15:25:32.297  1014  1026 D WifiService: setWifiEnabled: true pid=6186, uid=10155
08-31 15:25:32.297  1014  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 15:25:32.297  1014  1026 W WifiService: Failed getting userId using ActivityManagerNative
08-31 15:25:32.297  1014  1026 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6186, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 15:25:32.297  1014  1026 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 15:25:32.297  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 15:25:32.297  1014  1026 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
,08-31 15:25:32.297  1014  1026 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 15:25:32.297  1014  1026 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 15:25:32.297  1014  1026 D SettingsProvider: name = wifi_on
08-31 15:25:32.297  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.297  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.297  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.297  2863  2863 D BluetoothA2dp: Proxy object connected
,08-31 15:25:32.307  2863  2879 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.307  1014  1127 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 15:25:32.317  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:32.317  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.317  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.317  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.317  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.317  2863  2879 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 15:25:32.317  1014  1043 D BluetoothPan: Binding service...
,08-31 15:25:32.317  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 15:25:32.317  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.317  6892  6900 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-31 15:25:32.317  6892  6900 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.317  1291  1303 D BluetoothPbap: onBluetoothStateChange: up=true
,08-31 15:25:32.317  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 15:25:32.317  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-31 15:25:32.317  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.327  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.327  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.327  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.327  2863  6856 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.327  2863  6856 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.327  6892  6916 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:32.327  1291  6853 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:32.327  1291  1291 D BluetoothPbap: Proxy object connected
08-31 15:25:32.327  1291  6853 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.327  1291  1291 D PbapServerProfile: Bluetooth service connected
08-31 15:25:32.327  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 15:25:32.327  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.327  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.327  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.327  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.327  1291  1291 D BluetoothA2dp: Proxy object connected
08-31 15:25:32.337  1291  1291 D A2dpProfile: Bluetooth service connected
,08-31 15:25:32.337  1430  1444 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.337  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:32.337  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.337  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.337  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:32.337  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-31 15:25:32.337  1430  1444 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:32.337  1178  2713 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-31 15:25:32.337  1178  2713 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 15:25:32.337  1291  6853 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.337  1291  6853 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
,08-31 15:25:32.337  1430  2721 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.347  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-31 15:25:32.347  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.347  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.347  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.347  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.347  1430  2721 E BluetoothHeadset: BluetoothHeadset service is binded
08-31 15:25:32.347  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.347  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.347  1457  1695 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.347  1457  1695 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.347  6347  6362 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 15:25:32.347  6347  6362 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 15:25:32.347  1457  1692 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 15:25:32.347  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 15:25:32.347  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 15:25:32.347  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.347  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.347  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.347  1457  1692 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 15:25:32.347  1291  1301 D BluetoothPan: Binding service...
,08-31 15:25:32.357  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-31 15:25:32.357  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.357  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.357  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.357  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.357  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-31 15:25:32.357  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-31 15:25:32.357  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 15:25:32.357  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-31 15:25:32.357  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.357  1291  1291 D PanProfile: Bluetooth service connected
08-31 15:25:32.357  1014  1014 D BluetoothA2dp: Proxy object connected
08-31 15:25:32.357  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 15:25:32.357  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 15:25:32.367  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@147ef0dd, true
,08-31 15:25:32.367  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-31 15:25:32.367  1430  1430 D BluetoothHeadset: registerMessageListener
,08-31 15:25:32.367  1785  1785 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 15:25:32.367  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 15:25:32.367  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:32.367  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-31 15:25:32.377  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:32.377  1014  1746 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 15:25:32.377  1014  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:32.377  6892  6901 D HeadsetService: registerMessageListener
,08-31 15:25:32.377  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.377  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:32.377  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,08-31 15:25:32.377  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:32.377  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 15:25:32.377  1014  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 15:25:32.377  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 15:25:32.377  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.377  1014  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:32.377  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:32.387  6892  6901 D HeadsetService: registerMessageListener,
08-31 15:25:32.387  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 15:25:32.387  6892  6915 D HeadsetStateMachine: Disconnected process message: 70
08-31 15:25:32.387  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 15:25:32.387  6892  6915 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2ca17338
08-31 15:25:32.387  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
08-31 15:25:32.387  6892  6960 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 15:25:32.387  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 15:25:32.387  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 15:25:32.387  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 15:25:32.387  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-31 15:25:32.387  6892  6915 D HeadsetStateMachine: Disconnected process message: 9
08-31 15:25:32.387  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
08-31 15:25:32.387  6892  6915 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 15:25:32.387  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-31 15:25:32.387  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-31 15:25:32.387  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-31 15:25:32.387  1178  1703 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 15:25:32.397  6892  6960 D BluetoothSocket: bindListen(): myUserId = 0
08-31 15:25:32.397  6892  6960 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:32.397   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 15:25:32.397   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 15:25:32.397   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-31 15:25:32.397   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 15:25:32.397   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 15:25:32.397   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 15:25:32.397   282   282 V audio_hw_primary: adev_set_parameters: exit
,08-31 15:25:32.397  6892  6960 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 15:25:32.397  6892  6960 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:32.397  6892  6960 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 15:25:32.397  6892  6960 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7294f11
08-31 15:25:32.397  6892  6960 D BluetoothSocket: channel: 5
,08-31 15:25:32.397  6892  6915 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 15:25:32.407  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 15:25:32.407  1014  1312 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 15:25:32.407  1014  1312 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.407  1014  1312 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.407  1014  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.407  1014  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 15:25:32.417  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-31 15:25:32.417  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 15:25:32.427  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 15:25:32.427  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 15:25:32.437  6892  6892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
,08-31 15:25:32.437  6892  6892 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 15:25:32.437  1014  4552 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-31 15:25:32.437  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.437  1014  4552 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.437  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.437  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 15:25:32.447  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 15:25:32.447  1014  1746 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:32.457  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:32.457  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:32.457  1014  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:32.457  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:32.477  1014  2928 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 15:25:32.487  1926  6966 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 15:25:32.487  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 15:25:32.487  1014  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:32.487  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.487  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:32.487  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:32.497  6892  6970 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 15:25:32.497  6892  6970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 15:25:32.507  6892  6970 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-31 15:25:32.507  6892  6970 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 15:25:32.507  6892  6970 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 15:25:32.507  6892  6970 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38c7cb13
,08-31 15:25:32.507  6892  6970 D BluetoothSocket: channel: 12
08-31 15:25:32.507  6892  6970 I BtOppRfcommListener: Accept thread started.
,08-31 15:25:32.507  1014  1076 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 15:25:32.507  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:32.507  1014  1076 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 15:25:32.507  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:32.517  1926  6966 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 15:25:32.697  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 15:25:32.697  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:32.697  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:32.707  1014  1041 D Tethering: interfaceAdded wlan0
,08-31 15:25:32.707  1014  1041 D Tethering: interfaceAdded p2p0
,08-31 15:25:32.707  1014  1130 E Tethering: No numeric data
,08-31 15:25:32.717  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring,
08-31 15:25:32.717  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:32.717  1014  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 15:25:32.717  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:32.717  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-31 15:25:32.717  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:32.717  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:32.717  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:32.717  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,08-31 15:25:32.717  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-31 15:25:32.717  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:32.727   277   973 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-31 15:25:32.727  1014  1130 D Tethering: clearTetheredNotification()
,08-31 15:25:32.727   277   973 D SoftapController: Softap fwReload - Ok
,08-31 15:25:32.727  1014  1124 V NetworkStats: performPollLocked() took 14ms
08-31 15:25:32.727  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:32.727   277   973 D CommandListener: Setting iface cfg
08-31 15:25:32.727   277   973 D CommandListener: Trying to bring down wlan0
,08-31 15:25:32.727  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:32.727  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:32.727   277   973 D CommandListener: Clearing all IP addresses on wlan0
,08-31 15:25:32.737  1014  1127 E WifiHW  : supplicant_name : p2p_supplicant
,08-31 15:25:32.777  6978  6978 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-31 15:25:32.777  6978  6978 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 15:25:32.777  6978  6978 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 15:25:32.787  6978  6978 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-31 15:25:32.787   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6978
08-31 15:25:32.787   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-31 15:25:32.787  6978  6978 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 15:25:32.797  6978  6978 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:32.797  6978  6978 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 15:25:32.797  6978  6978 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-31 15:25:32.797   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6978
08-31 15:25:32.797   406   406 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-31 15:25:32.837  1014  1127 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-31 15:25:32.847  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:32.847  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 15:25:32.847  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:32.847  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:32.847  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:32.847  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:32.847  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:32.847  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 15:25:32.847  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 15:25:32.847  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 15:25:32.847  1178  1178 D HotspotTile: onReceive : 2, 0
,08-31 15:25:32.847  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:32.857  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:32.857  1014  1076 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:32.857  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:32.857  1014  1076 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:32.857  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:32.857  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:32.857  3632  3632 I Hs20UtilService: Starting #19
08-31 15:25:32.857  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:32.867  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 15:25:32.867  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-31 15:25:32.867  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
08-31 15:25:32.867  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:32.947   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-31 15:25:32.957  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-31 15:25:33.027  6978  6978 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 15:25:33.027  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 15:25:33.037  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 15:25:33.037   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6978
08-31 15:25:33.037   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 15:25:33.037  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 15:25:33.037  6978  6978 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:33.037  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-31 15:25:33.037  6978  6978 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:33.037  6978  6978 E wpa_supplicant: SIM READ ERROR
08-31 15:25:33.037  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:33.037  6978  6978 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:33.037  6978  6978 E wpa_supplicant: SIM READ ERROR
08-31 15:25:33.037  6978  6978 I wpa_supplicant: Blacklist: Clear (all) 
08-31 15:25:33.037  6978  6978 I wpa_supplicant: wpa_default_ap_write_once
08-31 15:25:33.037  6978  6978 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 15:25:33.037  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:33.037  6978  6978 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 15:25:33.037  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:33.037  6978  6978 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-31 15:25:33.037  6978  6978 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:25:33.037  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:33.037  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:33.037  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:33.037  1014  1130 D Tethering: InitialState.processMessage what=4
,08-31 15:25:33.037  1014  1130 E Tethering: No numeric data
08-31 15:25:33.047  1014  1130 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 15:25:33.047  1014  1130 D Tethering: clearTetheredNotification()
,08-31 15:25:33.047  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:33.047  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:33.047  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:33.047  1178  1178 D HotspotTile: updateTetherState():false, false,
08-31 15:25:33.047  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-31 15:25:33.047  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:33.047  1014  1124 V NetworkStats: performPollLocked() took 3ms
,08-31 15:25:33.047  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:33.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:33.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:33.147  6978  6978 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-31 15:25:33.157   287   287 E SMD     : DCD OFF
,08-31 15:25:33.337  6978  6978 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-31 15:25:33.337  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 15:25:33.347  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 15:25:33.347   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6978
08-31 15:25:33.347   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 15:25:33.347  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 15:25:33.347  6978  6978 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:33.347  6978  6978 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 15:25:33.347  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-31 15:25:33.367  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-31 15:25:33.367   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6978
08-31 15:25:33.367   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-31 15:25:33.367  6978  6978 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-31 15:25:33.367  6978  6978 I wpa_supplicant: ssSupport state is = 1
08-31 15:25:33.367  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:33.367  6978  6978 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:33.367  6978  6978 E wpa_supplicant: SIM READ ERROR
08-31 15:25:33.367  6978  6978 I wpa_supplicant: wpa_default_ap_write_once
08-31 15:25:33.367  6978  6978 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 15:25:33.367  6978  6978 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-31 15:25:33.367  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-31 15:25:33.367  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:33.367  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-31 15:25:33.367  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:33.367  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 15:25:33.367  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-31 15:25:33.407  6978  6978 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-31 15:25:33.407  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 15:25:33.497  1014  1312 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-31 15:25:33.497  1014  1312 D BatteryService: level:62, scale:100, status:2, health:2, present:true, voltage: 3920, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 15:25:33.497  1014  1312 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 15:25:33.497  1014  1312 D BatteryService: stay LED for charging
08-31 15:25:33.497  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 15:25:33.497  1014  1014 I MotionRecognitionService: Plugged
,08-31 15:25:33.497  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 15:25:33.497  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 15:25:33.497  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-31 15:25:33.507  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 15:25:33.507  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 62
,08-31 15:25:33.517  6892  6892 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 15:25:33.517  6892  6915 D HeadsetStateMachine: Disconnected process message: 10
,08-31 15:25:33.517  6978  6978 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-31 15:25:33.517  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-31 15:25:33.517  6978  6978 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 15:25:33.527  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-31 15:25:33.527  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
08-31 15:25:33.527  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
08-31 15:25:33.527  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:62 status:2 health:2
,08-31 15:25:33.527  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 15:25:33.527  6978  6978 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 15:25:33.527  6978  6978 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 15:25:33.527  6978  6978 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 15:25:33.527  6978  6978 E wpa_supplicant: SIM READ ERROR
08-31 15:25:33.527  6978  6978 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 15:25:33.557  6978  6978 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-31 15:25:33.567  6978  6978 I wpa_supplicant: Skip scan - bUseNetwork false
08-31 15:25:33.567  1014  1127 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 15:25:33.567  1014  1127 D WifiConfigStore: Loading config and enabling all networks 
,08-31 15:25:33.567  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:33.567  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:33.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:33.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:33.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:33.567  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:33.567  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:33.577  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-31 15:25:33.577  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:33.577  1178  1703 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 15:25:33.577  1178  1178 D HotspotTile: onReceive : 3, 0
,08-31 15:25:33.577  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:33.587  6186  6186 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:33.587  1014  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:33.587  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:33.587  1014  1127 E WifiConfigStore: Not a HS20
,08-31 15:25:33.587  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:33.587  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:33.587  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 15:25:33.587  1014  1127 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-31 15:25:33.587  3632  3632 I Hs20UtilService: Starting #20
,08-31 15:25:33.587  3632  3681 I Hs20UtilService: Message received 5011
,08-31 15:25:33.597  6186  6186 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:33.597  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:33.597  1014  1127 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 15:25:33.597  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
08-31 15:25:33.597  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 15:25:33.597  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:33.597  1014  1127 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 15:25:33.597  6978  6978 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 15:25:33.597  6978  6978 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 15:25:33.597  6978  6978 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 15:25:33.597  6978  6978 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 15:25:33.597  6978  6978 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-31 15:25:33.597  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 15:25:33.597  6978  6978 I wpa_supplicant: First Scan Start
08-31 15:25:33.597  6978  6978 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 15:25:33.597  1014  1127 D WifiNative-wlan0: Setting external_sim to 1
,08-31 15:25:33.607  1014  1127 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 15:25:33.607  1014  1127 I WifiNative-HAL: startHal
08-31 15:25:33.607  1014  1127 E wifi    : getStaticLongField sWifiHalHandle 0x9e16288c
08-31 15:25:33.607  1014  1127 I WifiNative-HAL: Could not start hal
,08-31 15:25:33.607  6432  6432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 15:25:33.607  1014  1127 E WifiNative-wlan0: do suspend true
,08-31 15:25:33.607  1014  1126 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 15:25:33.607   277   973 D CommandListener: Setting iface cfg
08-31 15:25:33.607   277   973 D CommandListener: Trying to bring up p2p0
,08-31 15:25:33.607  1014  1126 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 15:25:33.607  1014  1126 D WifiP2pService: P2pEnablingState
08-31 15:25:33.607  1014  1127 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 15:25:33.617  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 15:25:33.617  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:33.617  1014  1149 I WifiNative-HAL: startHal
08-31 15:25:33.617  1014  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 15:25:33.617  1014  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 15:25:33.617  1014  1127 E WifiNative-wlan0: invaild command id : 215
,08-31 15:25:33.617  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d0339bc
08-31 15:25:33.617  1014  1149 I WifiNative-HAL: Could not start hal
08-31 15:25:33.617  1014  1149 E WifiScanningService: could not start HAL
,08-31 15:25:33.617  1014  1127 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 15:25:33.617  1014  1127 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 15:25:33.617  1014  1127 E WifiNative-wlan0: invaild command id : 215
,08-31 15:25:33.617  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-31 15:25:33.617  1014  1126 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-31 15:25:33.617  1014  1126 D WifiP2pService: P2p socket connection successful
08-31 15:25:33.617  1014  1126 D WifiP2pService: P2pEnabledState
,08-31 15:25:33.617  1014  1150 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:33.617  1014  1126 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-31 15:25:33.617  6978  6978 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 15:25:33.617  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 15:25:33.627  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 15:25:33.627  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 15:25:33.627  1014  1044 D WifiDisplayController: disconnect
08-31 15:25:33.627  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:33.627  1014  1044 D WifiDisplayController: updateConnection
08-31 15:25:33.627  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 15:25:33.627  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 15:25:33.627  6978  6978 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 15:25:33.627  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 15:25:33.627  1014  1493 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-31 15:25:33.627  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-31 15:25:33.627  6978  6978 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-31 15:25:33.627  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 15:25:33.627  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-31 15:25:33.627  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-31 15:25:33.627  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-31 15:25:33.627  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 15:25:33.637  1014  1127 D SecContentProvider2: mCursor = null
08-31 15:25:33.637  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 15:25:33.637  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:33.637  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:33.637  1014  1126 D WifiNative-p2p0: p2pGetDeviceAddress
,08-31 15:25:33.637  1014  1126 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-31 15:25:33.637  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:33.637  1014  1126 D WifiP2pService: DeviceAddress: 7e:96:ac
08-31 15:25:33.637  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:33.637  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 15:25:33.637  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:33.637  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:33.637  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  secondary type: null
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  wps: 0
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  grpcapab: 0
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  devcapab: 0
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  status: 3
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  wfdInfo: null
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-31 15:25:33.637  1014  1044 D WifiDisplayController:  SConnectInfo : null
08-31 15:25:33.637  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:33.637  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:33.647  6401  6401 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-31 15:25:33.647  6401  6401 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 15:25:33.647  6416  6416 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 15:25:33.657  1014  1126 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 15:25:33.657  1014  1126 D WifiP2pService: InactiveState,
08-31 15:25:33.657  1014  1126 D WifiP2pService: InactiveState{ what=143376 }
08-31 15:25:33.657  1014  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 15:25:33.657  6978  6978 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 15:25:33.657  1014  1126 D WifiP2pService: InactiveState{ what=143376 }
08-31 15:25:33.657  1014  1126 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 15:25:33.697  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 15:25:33.697  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 15:25:33.697  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:34.337  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:34.337  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:34.337  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-31 15:25:34.347  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
,08-31 15:25:34.347  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@de1ae3e Bundle[{}]
,08-31 15:25:34.347  6186  6238 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 15:25:34.347  6186  6238 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-31 15:25:34.347  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-31 15:25:34.347  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-31 15:25:34.357  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-31 15:25:34.357  6186  6238 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-31 15:25:34.357  6186  6238 I System.out: Running OutgoingSocketThread
,08-31 15:25:34.357  6186  6988 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1167)
,08-31 15:25:34.367  6186  6988 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46738
,08-31 15:25:34.367  6186  6988 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-31 15:25:34.577  1014  2730 D SSRM:n  : SIOP:: AP = 330
,08-31 15:25:34.887  6978  6978 I wpa_supplicant: nl80211: Received scan results (22 BSSes)
08-31 15:25:34.887  6978  6978 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 15:25:34.887  6978  6978 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-31 15:25:34.887  6978  6978 I wpa_supplicant: Trying to associate with  'G700'
,08-31 15:25:34.887  6978  6978 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-31 15:25:34.887  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-31 15:25:34.897  1014  6984 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-31 15:25:34.907  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:34.907  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:35.007  6978  6978 E wpa_supplicant: Cmd 35605 not handled
,08-31 15:25:35.007  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:35.007  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:35.007  6978  6978 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 15:25:35.007  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-31 15:25:35.007  6978  6978 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-31 15:25:35.007  6978  6978 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-31 15:25:35.007  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 15:25:35.007  6978  6978 I wpa_supplicant: Associated with F4.99.3E
08-31 15:25:35.007  6978  6978 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 15:25:35.017  6978  6978 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-31 15:25:35.017  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-31 15:25:35.017  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-31 15:25:35.017  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 15:25:35.017  1014  1041 D Tethering: interfaceStatusChanged wlan0, false,
,08-31 15:25:35.017  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
08-31 15:25:35.017  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 15:25:35.017  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-31 15:25:35.017  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-31 15:25:35.017  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 15:25:35.017  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,08-31 15:25:35.017  1014  1130 E Tethering: No numeric data
,08-31 15:25:35.017  1014  1130 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 15:25:35.027  1014  1130 D Tethering: clearTetheredNotification()
08-31 15:25:35.027  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:35.027  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:35.027  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 15:25:35.027  1178  1178 D HotspotTile: updateTetherState():false, false
,08-31 15:25:35.027  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-31 15:25:35.027  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 15:25:35.027  6978  6978 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-31 15:25:35.027  6978  6978 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-31 15:25:35.027  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-31 15:25:35.027  1014  1127 D SecContentProvider2: mCursor = null
08-31 15:25:35.027  6978  6978 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-31 15:25:35.027  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 15:25:35.027  6978  6978 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 15:25:35.027  6978  6978 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-31 15:25:35.027  6978  6978 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 15:25:35.037  6978  6978 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 15:25:35.037  6978  6978 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-31 15:25:35.037  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 15:25:35.037  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-31 15:25:35.037  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,08-31 15:25:35.037  1014  1124 V NetworkStats: performPollLocked() took 12ms
08-31 15:25:35.037  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:35.037  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:35.037  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:35.037  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:35.037  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:35.047  1014  1127 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 15:25:35.047  1014  1127 E WifiConfigStore: setLastSelectedConfiguration -1,
08-31 15:25:35.047  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:35.047  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 15:25:35.047  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.047  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 15:25:35.057  1014  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 15:25:35.047  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:35.047  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.057  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-31 15:25:35.057  1014  1129 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 15:25:35.057  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 15:25:35.057  1014  1129 E ConnectivityService: updateNetworkInfo()
,08-31 15:25:35.057  1014  1991 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:35.057  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:35.057  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:35.057  1014  1991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:35.067  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
08-31 15:25:35.067  1014  1127 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 15:25:35.067  3632  3632 I Hs20UtilService: Starting #21
,08-31 15:25:35.067  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:35.067  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:35.067  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 15:25:35.077  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 15:25:35.077   277   973 D CommandListener: Setting iface cfg
,08-31 15:25:35.077  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-31 15:25:35.077  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 15:25:35.077  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-31 15:25:35.077  1291  3064 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-31 15:25:35.087  1014  1127 E WifiStateMachine: Start Dhcp Watchdog 3
,08-31 15:25:35.087  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 15:25:35.087  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:35.097  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:35.097  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:35.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.097  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:35.107  1014  1127 E WifiNative-wlan0: do suspend false
,08-31 15:25:35.107  1014  1126 D WifiP2pService: InactiveState{ what=143375 }
,08-31 15:25:35.107  1014  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 15:25:35.107  1014  1127 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 15:25:35.107  1014  1127 D SecContentProvider2: mCursor = null
,08-31 15:25:35.327  6991  6991 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 15:25:35.327  6991  6991 I dhcpcd  : version 5.5.6 starting,
,08-31 15:25:35.327  6991  6991 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 15:25:35.357  6186  6238 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1168),
08-31 15:25:35.357  6186  6238 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1168)
08-31 15:25:35.367  6186  6238 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1173),
08-31 15:25:35.367  6186  6238 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-31 15:25:35.367  6186  6238 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1174),
,08-31 15:25:35.367  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-31 15:25:35.367  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1620679b added. We now have 2 listener(s)
08-31 15:25:35.367  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-31 15:25:35.367  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.367  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.367  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:35.367  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f8738 added. We now have 9 listener(s)
08-31 15:25:35.367  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:35.367  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:35.387  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:35.387  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:35.397  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 15:25:35.397  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:35.397  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.397  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eb23c76 added. We now have 3 listener(s)
,08-31 15:25:35.397  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.397  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2993e277 added. We now have 10 listener(s)
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:35.407  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:35.407  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:35.407  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.407  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1620679b removed from the list
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f8738 removed from the list
08-31 15:25:35.407  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:35.407  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.407  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.407  6991  6991 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:35.407  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@83f8738 not in the list
08-31 15:25:35.407  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.407  6991  6991 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address,
08-31 15:25:35.407  6991  6991 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-31 15:25:35.407  6991  6991 I dhcpcd  : bssid match
08-31 15:25:35.407  6991  6991 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2993e277 removed from the list
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.407  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.407  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.407  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eb23c76 removed from the list
,08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.407  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2201dee4 added. We now have 2 listener(s)
,08-31 15:25:35.417  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 15:25:35.417  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:25:35.417  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:25:35.417  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:35.417  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@150d8f4d added. We now have 9 listener(s)
,08-31 15:25:35.417  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:35.417  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:35.427  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:35.427  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:35.427  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:35.427  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 15:25:35.437  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.437  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275a2f13 added. We now have 3 listener(s)
,08-31 15:25:35.437  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:35.437  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:35.437  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.437  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.437  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.437  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37700550 added. We now have 10 listener(s)
08-31 15:25:35.437  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:35.437  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:35.437  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:35.437  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:35.437  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:35.437  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:35.437  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.437  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:25:35.447  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:35.447  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:35.447  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:25:35.447  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 15:25:35.447  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:25:35.457  6892  6957 D BtGatt.GattService: registerClient() - UUID=30a824f9-56ef-4b94-a50d-409d8d930850
,08-31 15:25:35.497  6892  6910 D BtGatt.GattService: onClientRegistered() - UUID=30a824f9-56ef-4b94-a50d-409d8d930850, clientIf=6
,08-31 15:25:35.497  6186  6195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-31 15:25:35.497  6892  6901 D BtGatt.GattService: start scan with filters
,08-31 15:25:35.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:35.507  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:25:35.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:25:35.507  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-31 15:25:35.507  6892  6914 D BtGatt.ScanManager: handling starting scan
,08-31 15:25:35.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:35.507  6892  6914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d72c58e
08-31 15:25:35.507  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-31 15:25:35.507  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:35.507  6892  6910 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-31 15:25:35.517  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.517  6892  6914 D BtGatt.ScanManager: allow scan with filters
,08-31 15:25:35.517  6892  6914 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-31 15:25:35.517  6892  6914 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-31 15:25:35.517  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:35.517  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-31 15:25:35.517  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.517  6892  6914 D BtGatt.ScanManager: Starting BLE batch scan
,08-31 15:25:35.517  6892  6914 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 15:25:35.527  6892  6910 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-31 15:25:35.527  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.527  6186  6238 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-31 15:25:35.527  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:35.527  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-31 15:25:35.527  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:35.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-31 15:25:35.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:35.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:35.527  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:25:35.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:25:35.527  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-31 15:25:35.527  6892  6900 D BtGatt.GattService: stopScan() - queue size =1
,08-31 15:25:35.527  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 15:25:35.527  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.527  6892  6957 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 15:25:35.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-31 15:25:35.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 15:25:35.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 15:25:35.537  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-31 15:25:35.537  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:25:35.547  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:35.547  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-31 15:25:35.547  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-31 15:25:35.547  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 15:25:35.547  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:35.557  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:35.557  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:35.557  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:35.557  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:35.557  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:25:35.557  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-31 15:25:35.557  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.557  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.557  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:35.557  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.557  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2201dee4 removed from the list
08-31 15:25:35.557  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.557  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@150d8f4d removed from the list
08-31 15:25:35.557  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:35.557  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.557  6892  6914 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,08-31 15:25:35.567  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.567  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.567  6991  6991 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.567  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@150d8f4d not in the list
08-31 15:25:35.567  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:35.567  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.567  6892  6914 D BtGatt.ScanManager: filter size is 1
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.567  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37700550 removed from the list
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.567  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.567  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.567  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.567  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@275a2f13 removed from the list
,08-31 15:25:35.567  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.567  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1758267c added. We now have 2 listener(s)
,08-31 15:25:35.567  6892  6914 D BtGatt.ScanManager: delete FilterIndex - 3
,08-31 15:25:35.567  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-31 15:25:35.577  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.577  6892  6914 D BtGatt.ScanManager: stopping BLe Batch
,08-31 15:25:35.577  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 15:25:35.577  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 15:25:35.577  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:35.577  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.577  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:25:35.577  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.577  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a5b05 added. We now have 9 listener(s)
08-31 15:25:35.577  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:35.577  6892  6914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 15:25:35.577  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:35.587  6892  6910 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 15:25:35.587  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.587  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:35.587  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:35.597  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:35.597  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:35.597  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.597  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f266d8b added. We now have 3 listener(s)
,08-31 15:25:35.597  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.597  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.597  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 15:25:35.597  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.597  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 15:25:35.597  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-31 15:25:35.597  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3f2e68 added. We now have 10 listener(s)
08-31 15:25:35.607  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:35.607  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-31 15:25:35.607  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:35.607  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:35.607  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-31 15:25:35.607  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:35.607  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:35.607  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:25:35.617  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:35.617  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:35.617  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:25:35.617  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-31 15:25:35.617  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:25:35.617  6892  6916 D BtGatt.GattService: registerClient() - UUID=dafdf81a-f711-4a40-9763-c2dcf34f50f3
,08-31 15:25:35.647  6991  6991 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-31 15:25:35.667  6892  6910 D BtGatt.GattService: onClientRegistered() - UUID=dafdf81a-f711-4a40-9763-c2dcf34f50f3, clientIf=6
08-31 15:25:35.667  6186  6194 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 15:25:35.667  6892  6901 D BtGatt.GattService: start scan with filters
08-31 15:25:35.667  6892  6914 D BtGatt.ScanManager: handling starting scan,
08-31 15:25:35.667  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:35.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-31 15:25:35.667  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:25:35.667  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-31 15:25:35.667  6892  6910 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-31 15:25:35.667  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.667  6892  6914 D BtGatt.ScanManager: allow scan with filters
08-31 15:25:35.667  6892  6914 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 15:25:35.667  6892  6914 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-31 15:25:35.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-31 15:25:35.677  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 15:25:35.677  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 15:25:35.677  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-31 15:25:35.677  6892  6914 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:25:35.677  6892  6914 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-31 15:25:35.677  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:25:35.677  6892  6910 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-31 15:25:35.677  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.687  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:35.687  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 15:25:35.687  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.697  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:35.697  6186  6238 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-31 15:25:35.697  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:35.697  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:35.697  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.697  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.697  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1758267c removed from the list
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.697  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a5b05 removed from the list
08-31 15:25:35.697  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:35.697  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 15:25:35.697  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.697  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2a5b05 not in the list
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-31 15:25:35.697  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-31 15:25:35.697  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-31 15:25:35.707  6892  6900 D BtGatt.GattService: stopScan() - queue size =1
,08-31 15:25:35.707  6892  6957 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-31 15:25:35.707  6892  6914 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,08-31 15:25:35.707  6892  6914 D BtGatt.ScanManager: filter size is 1
08-31 15:25:35.707  6892  6914 D BtGatt.ScanManager: delete FilterIndex - 4
,08-31 15:25:35.707  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-31 15:25:35.707  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.707  6892  6914 D BtGatt.ScanManager: stopping BLe Batch
,08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-31 15:25:35.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:25:35.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-31 15:25:35.717  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:35.717  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.717  6892  6914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:35.717  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 15:25:35.717  6892  6910 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-31 15:25:35.717  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.717  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.727  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:35.727  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:35.727  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d3f2e68 removed from the list
08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.727  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.727  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f266d8b removed from the list
,08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160cc914 added. We now have 2 listener(s)
08-31 15:25:35.727  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:35.727  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.727  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.727  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222de5bd added. We now have 9 listener(s)
08-31 15:25:35.727  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:35.727  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 15:25:35.737  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:35.747  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 15:25:35.757  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-31 15:25:35.757  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:35.757  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.757  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107d0303 added. We now have 3 listener(s)
,08-31 15:25:35.757  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-31 15:25:35.757  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:35.757  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.757  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.757  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.757  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33776280 added. We now have 10 listener(s)
08-31 15:25:35.757  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:35.757  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:35.757  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-31 15:25:35.757  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-31 15:25:35.757  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-31 15:25:35.757  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-31 15:25:35.757  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.767  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-31 15:25:35.767  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-31 15:25:35.767  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-31 15:25:35.777  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-31 15:25:35.777  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-31 15:25:35.777  6186  6238 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-31 15:25:35.777  6892  6916 D BtGatt.GattService: registerClient() - UUID=40794f03-550e-43e2-933e-d9ae2db4610c
,08-31 15:25:35.817  6892  6910 D BtGatt.GattService: onClientRegistered() - UUID=40794f03-550e-43e2-933e-d9ae2db4610c, clientIf=6,
08-31 15:25:35.817  6186  6195 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-31 15:25:35.827  6892  6958 D BtGatt.GattService: start scan with filters
,08-31 15:25:35.827  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-31 15:25:35.827  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
08-31 15:25:35.827  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-31 15:25:35.827  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-31 15:25:35.827  6892  6914 D BtGatt.ScanManager: handling starting scan
,08-31 15:25:35.827  6892  6910 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-31 15:25:35.827  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.827  6892  6914 D BtGatt.ScanManager: allow scan with filters
08-31 15:25:35.827  6892  6914 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-31 15:25:35.827  6892  6914 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6,
08-31 15:25:35.827  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-31 15:25:35.827  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-31 15:25:35.827  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-31 15:25:35.837  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-31 15:25:35.837  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.837  6892  6914 D BtGatt.ScanManager: Starting BLE batch scan
08-31 15:25:35.837  6892  6914 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-31 15:25:35.837  6892  6910 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-31 15:25:35.837  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.837  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-31 15:25:35.837  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-31 15:25:35.837  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.867  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-31 15:25:35.867  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:35.867  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.867  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.867  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@160cc914 removed from the list,
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.867  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222de5bd removed from the list
08-31 15:25:35.867  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:35.867  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-31 15:25:35.867  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.867  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@222de5bd not in the list
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-31 15:25:35.867  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-31 15:25:35.867  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
08-31 15:25:35.867  6892  6958 D BtGatt.GattService: stopScan() - queue size =1
,08-31 15:25:35.867  6892  6901 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-31 15:25:35.877  6892  6914 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
,08-31 15:25:35.877  6892  6914 D BtGatt.ScanManager: filter size is 1
08-31 15:25:35.877  6892  6914 D BtGatt.ScanManager: delete FilterIndex - 5
,08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-31 15:25:35.877  6892  6910 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-31 15:25:35.877  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-31 15:25:35.877  6892  6914 D BtGatt.ScanManager: stopping BLe Batch
08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.877  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33776280 removed from the list
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:25:35.877  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.877  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.877  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.877  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@107d0303 removed from the list
08-31 15:25:35.877  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-31 15:25:35.877  6186  6186 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-31 15:25:35.877  6186  6186 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-31 15:25:35.877  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.877  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3026ac added. We now have 2 listener(s)
,08-31 15:25:35.887  6892  6910 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-31 15:25:35.887  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-31 15:25:35.887  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:35.887  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.887  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.887  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.887  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17510f75 added. We now have 9 listener(s)
08-31 15:25:35.887  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 15:25:35.887  6892  6914 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-31 15:25:35.887  6892  6910 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-31 15:25:35.887  6892  6910 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-31 15:25:35.887  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 15:25:35.887  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 15:25:35.897  6186  6238 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 15:25:35.897  6186  6238 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 15:25:35.897  6186  6238 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 15:25:35.897  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-31 15:25:35.897  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1971cf7b added. We now have 3 listener(s)
,08-31 15:25:35.897  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 15:25:35.897  6186  6186 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 15:25:35.897  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-31 15:25:35.897  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-31 15:25:35.897  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-31 15:25:35.897  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-31 15:25:35.897  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cf0198 added. We now have 10 listener(s)
08-31 15:25:35.897  6186  6238 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-31 15:25:35.897  6186  6238 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-31 15:25:35.897  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-31 15:25:35.897  6186  6238 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-31 15:25:35.907  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.907  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3026ac removed from the list
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.907  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17510f75 removed from the list
08-31 15:25:35.907  6186  6238 D io.jxcore.node.ConnectivityMonitor: stop
08-31 15:25:35.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-31 15:25:35.907  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-31 15:25:35.907  6186  6238 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17510f75 not in the list
,08-31 15:25:35.907  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-31 15:25:35.907  6186  6238 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36cf0198 removed from the list
08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-31 15:25:35.907  6186  6238 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-31 15:25:35.907  6186  6238 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-31 15:25:35.907  6186  6238 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-31 15:25:35.907  6186  6238 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1971cf7b removed from the list
,08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-31 15:25:35.907  6186  6238 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-31 15:25:35.917  1014  1127 E WifiNative-wlan0: do suspend true
,08-31 15:25:35.927  6186  7024 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1181, name: My test thread name)
,08-31 15:25:35.927  6186  7024 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1181, thread name: My test thread name)
,08-31 15:25:35.927  6186  7024 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1181, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 15:25:35.927  6186  7025 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1183, name: My test thread name)
,08-31 15:25:35.927  6186  7025 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1183, thread name: My test thread name)
08-31 15:25:35.927  6186  7025 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-31 15:25:35.927  6186  6238 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-31 15:25:35.927  6186  6238 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-31 15:25:35.927  6186  6238 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-31 15:25:35.927  6186  6238 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-31 15:25:35.927  6186  6238 D com.test.thalitest.ThaliTestRunner: Total duration: 23433 ms
,08-31 15:25:35.937  6186  6238 I jxcore-log: *Native tests were executed*
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: Total number of executed tests:  80
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: Number of passed tests:  80
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: Number of failed tests:  0
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: Number of ignored tests:  0
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: Total duration:  23433
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.937  6186  6238 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-31 15:25:35.937  6186  6238 I jxcore-log: 
,08-31 15:25:35.947  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.947  6186  6238 I jxcore-log: 
08-31 15:25:35.947  1014  1127 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-31 15:25:35.947  1014  1127 E WifiStateMachine: VerifyingLinkState enter
08-31 15:25:35.947  1014  1126 D WifiP2pService: InactiveState{ what=143375 }
08-31 15:25:35.947  1014  1126 D WifiP2pService: P2pEnabledState{ what=143375 }
08-31 15:25:35.947  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.947  6186  6238 I jxcore-log: 
08-31 15:25:35.947  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.947  6186  6238 I jxcore-log: 
08-31 15:25:35.947  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:35.947  1014  1127 D WifiNative-wlan0: callSECApiInt - ID [210]
08-31 15:25:35.947  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:35.947  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.947  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.947  6186  6238 I jxcore-log: 
08-31 15:25:35.947  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:35.957  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.957  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.957  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.957  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.957  6186  6238 I jxcore-log: 
08-31 15:25:35.957  1014  1129 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-31 15:25:35.957  1014  1129 D ConnectivityService: Adding iface wlan0 to network 504
,08-31 15:25:35.957  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.957  6186  6238 I jxcore-log: 
,08-31 15:25:35.957  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.957  6186  6238 I jxcore-log: 
,08-31 15:25:35.967  1014  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-31 15:25:35.967  1014  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
08-31 15:25:35.967  1014  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-31 15:25:35.967  1014  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 15:25:35.967  1014  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
,08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
,08-31 15:25:35.967  6186  6186 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
,08-31 15:25:35.967  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.967  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:35.977  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.977  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.977  6186  6238 I jxcore-log: 
,08-31 15:25:35.977  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:35.977  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.977  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  1014  1251 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:35.987  1014  1251 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:35.987  1014  1251 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:35.987  1014  1251 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:35.987  1014  1251 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  1014  1127 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 15:25:35.987  6186  6238 I jxcore-log: 
08-31 15:25:35.987  3632  3632 I Hs20UtilService: Starting #22
08-31 15:25:35.997  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:35.997  1014  1129 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-31 15:25:35.997  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 15:25:35.997  1014  1129 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-31 15:25:35.997  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
08-31 15:25:35.997  1014  1129 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-31 15:25:35.997  1014  1129 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 15:25:35.997  1014  1129 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-31 15:25:35.997  1014  1129 D ConnectivityService: LTETest block dns file not exists
,08-31 15:25:35.997  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:36.007  1014  1129 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-31 15:25:36.007  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:36.007  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 15:25:36.007  1014  1129 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 15:25:36.007  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:36.007  1014  1129 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-31 15:25:36.007  1014  1129 E ConnectivityService: updateNetworkInfo()
08-31 15:25:36.007  1014  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-31 15:25:36.007  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.007  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.007  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.007  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.007  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 15:25:36.007  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-31 15:25:36.007  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-31 15:25:36.007  1014  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 15:25:36.007  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-31 15:25:36.007  1014  1127 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 15:25:36.007  1014  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 15:25:36.007   277   969 D EnterpriseController: uids 1000
08-31 15:25:36.007   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:36.007   277   969 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-31 15:25:36.017  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 15:25:36.017  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
08-31 15:25:36.017  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
08-31 15:25:36.017  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-31 15:25:36.027  1014  1126 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 15:25:36.027  1014  1129 D ConnectivityService:    accepting network in place of null
08-31 15:25:36.027  1014  1127 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-31 15:25:36.027  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-31 15:25:36.027  1457  1457 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 15:25:36.027  1014  1129 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 15:25:36.027  1014  1129 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-31 15:25:36.027  1014  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-31 15:25:36.027  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:36.027  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 15:25:36.027  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.037  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.037  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.037  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:36.037  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 15:25:36.037  1014  1129 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-31 15:25:36.037  1014  1130 D Tethering: MasterInitialState.processMessage what=3
08-31 15:25:36.037  1014  1124 V NetworkStats: updateIfacesLocked()
08-31 15:25:36.037  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.037  1014  1124 V NetworkStats: performPollLocked(flags=0x1)
08-31 15:25:36.037  1014  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-31 15:25:36.037  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:36.037  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:36.037  1178  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 15:25:36.037  3785  6248 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.047  1014  1124 V NetworkStats: performPollLocked() took 6ms
08-31 15:25:36.047  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.047  1014  1125 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.047  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:36.057  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-31 15:25:36.057  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 15:25:36.057  6186  6186 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:25:36.057  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 15:25:36.057  1014  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 15:25:36.057  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-31 15:25:36.057  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 15:25:36.057  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 15:25:36.057  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 15:25:36.057  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:25:36.057  6186  6238 I jxcore-log: 
,08-31 15:25:36.057  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:36.057  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:36.057  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:36.067  3632  3632 I Hs20UtilService: Starting #23
,08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 15:25:36.067  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.067  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.067  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:36.067  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 15:25:36.067  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-31 15:25:36.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 15:25:36.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-31 15:25:36.067  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 15:25:36.067  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 15:25:36.077  1014  1076 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 15:25:36.077  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 15:25:36.077  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:36.077  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:36.077  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 15:25:36.077  3632  3632 I Hs20UtilService: Starting #24
,08-31 15:25:36.077  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-31 15:25:36.077  3632  3681 I Hs20UtilService: Message received 5007
,08-31 15:25:36.087  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 15:25:36.087  1014  1312 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 15:25:36.087  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 15:25:36.087  1014  1027 D SecContentProvider2: mCursor = null
,08-31 15:25:36.097  1014  1076 D SecContentProvider2: uri = 15 selection = getToastGravity
08-31 15:25:36.097  1014  1076 D SecContentProvider2: mCursor = null
,08-31 15:25:36.097  1014  1026 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-31 15:25:36.097  1014  1026 D SecContentProvider2: mCursor = null
,08-31 15:25:36.097  1014  1991 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 15:25:36.097  1014  1991 D SecContentProvider2: mCursor = null
,08-31 15:25:36.097  1014  1493 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-31 15:25:36.097  1014  1493 D SecContentProvider2: mCursor = null
,08-31 15:25:36.097  1014  1480 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-31 15:25:36.097  1014  1480 D SecContentProvider2: mCursor = null
,08-31 15:25:36.107  1014  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 15:25:36.127   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-31 15:25:36.137  1014  1076 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-31 15:25:36.147  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 15:25:36.157   287   287 E SMD     : DCD OFF,
,08-31 15:25:36.177  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 13:25:36 GMT], X-Android-Received-Millis=[1472649936185], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472649936145]}
,08-31 15:25:36.177  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-31 15:25:36.177  1014  6989 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-31 15:25:36.177  1014  1129 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
,08-31 15:25:36.177  1014  1129 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-31 15:25:36.177  1014  1129 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-31 15:25:36.177  1014  1129 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-31 15:25:36.177  1014  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 15:25:36.177  3785  6248 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 15:25:36.177  1178  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 15:25:36.187  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 15:25:36.187  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 15:25:36.197  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 15:25:36.197  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 15:25:36.197  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.197  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.197  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 15:25:36.197  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 15:25:36.227  6186  6186 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:25:36.227  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:25:36.227  6186  6238 I jxcore-log: 
,08-31 15:25:36.227  7030  7030 D AndroidRuntime: 
08-31 15:25:36.227  7030  7030 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-31 15:25:36.227  7030  7030 D AndroidRuntime: CheckJNI is OFF
,08-31 15:25:36.227  7030  7030 D AndroidRuntime: readGMSProperty: start,
08-31 15:25:36.227  7030  7030 D AndroidRuntime: readGMSProperty: already setted!!
08-31 15:25:36.227  7030  7030 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,08-31 15:25:36.227  7030  7030 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 15:25:36.227  7030  7030 D AndroidRuntime: readGMSProperty: end
08-31 15:25:36.227  7030  7030 D AndroidRuntime: addProductProperty: start
,08-31 15:25:36.377  6186  6186 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-31 15:25:36.377  6186  6238 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-31 15:25:36.377  6186  6238 I jxcore-log: 
,08-31 15:25:36.397  7030  7030 E AffinityControl: AffinityControl: registerfunction enter
,08-31 15:25:36.417  7030  7030 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 15:25:36.437  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-31 15:25:36.437  1014  1026 D PackageManager: START PACKAGE DELETE: observer{295399205}
08-31 15:25:36.437  1014  1026 D PackageManager: pkg{<packageName>}
08-31 15:25:36.437  1014  1026 D PackageManager: user{0}
,08-31 15:25:36.437  1014  1026 D PackageManager: caller{2000}
08-31 15:25:36.437  1014  1026 D PackageManager: flags{2}
08-31 15:25:36.437  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-31 15:25:36.437  1014  1026 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-31 15:25:36.437  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-31 15:25:36.437  1014  1026 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 15:25:36.437  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-31 15:25:36.437  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-31 15:25:36.437  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 15:25:36.437  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 15:25:36.437  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 15:25:36.437  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-31 15:25:36.437  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
08-31 15:25:36.437  1014  1039 I ActivityManager: Killing 6186:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
08-31 15:25:36.447  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{3f08a7cc u0 com.test.thalitest/.MainActivity t128}
,08-31 15:25:36.447  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,08-31 15:25:36.537  1014  1129 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:36.557  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-31 15:25:36.567  1014  1054 I ActivityManager:   Force finishing activity ActivityRecord{3f08a7cc u0 com.test.thalitest/.MainActivity t128 f}
08-31 15:25:36.567  1014  1054 W ActivityManager: Duplicate finish request for ActivityRecord{3f08a7cc u0 com.test.thalitest/.MainActivity t128 f}
,08-31 15:25:36.567  1014  1480 I WindowState: WIN DEATH: Window{3f4bfc2c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 15:25:36.567   257   440 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-31 15:25:36.567   257  1096 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
08-31 15:25:36.567   257   440 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-31 15:25:36.567  1014  1480 D InputDispatcher: Focus left window: 6186
,08-31 15:25:36.587  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 15:25:36.587  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 15:25:36.617  5636  5636 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 684us total 26.407ms
,08-31 15:25:36.617  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 15:25:36.627  3162  3162 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-31 15:25:36.637  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-31 15:25:36.647  3785  3785 I art     : Explicit concurrent mark sweep GC freed 24714(1497KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.347ms total 72.877ms
,08-31 15:25:36.647  5426  5426 I art     : Explicit concurrent mark sweep GC freed 394(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 730us total 50.647ms
,08-31 15:25:36.657  1014  1039 D InputDispatcher: Focused application released
,08-31 15:25:36.657  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-31 15:25:36.667  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-31 15:25:36.667  3162  3162 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,08-31 15:25:36.677  6509  6509 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 15:25:36.677  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-31 15:25:36.677  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:36.707  1014  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 15:25:36.727  1785  1785 E SamsungIME: mOCRHelper is null
,08-31 15:25:36.737  1014  1124 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-31 15:25:36.737  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.737  1014  1124 V NetworkStats: performPollLocked(flags=0x3)
,08-31 15:25:36.737  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 15:25:36.737  1014  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 15:25:36.747  1014  1124 V NetworkStats: performPollLocked() took 6ms
08-31 15:25:36.747  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:36.757  3162  3162 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-31 15:25:36.767  3162  3162 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-31 15:25:36.777  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:36.787  6492  6492 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 15:25:36.787  6492  6492 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 15:25:36.787  6492  6492 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 15:25:36.787  6492  6492 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:36.787  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-31 15:25:36.797  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-31 15:25:36.797  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:36.797  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-31 15:25:36.817  1014  1493 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-31 15:25:36.817  1014  1493 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-31 15:25:36.827  1014  1014 I art     : Explicit concurrent mark sweep GC freed 84620(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 29MB/43MB, paused 2.990ms total 208.312ms
,08-31 15:25:36.827  1014  1312 I art     : WaitForGcToComplete blocked for 105.444ms for cause Explicit
,08-31 15:25:36.827  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-31 15:25:36.837  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-31 15:25:36.837  3162  3162 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-31 15:25:36.847  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 15:25:36.847  1014  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 15:25:36.847  3162  3162 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-31 15:25:36.847  3162  3162 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-31 15:25:36.847  3162  3162 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-31 15:25:36.847  1014  1027 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 15:25:36.847  1014  1027 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-31 15:25:36.847  1014  1027 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 15:25:36.847  3162  3162 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-31 15:25:36.957  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-31 15:25:36.957  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 15:25:36.957  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 15:25:36.957  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-31 15:25:36.957  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-31 15:25:36.957  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-31 15:25:36.967  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-31 15:25:36.967  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 15:25:36.967  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 15:25:36.967  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 15:25:36.967  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 15:25:36.967  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 15:25:36.977  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 15:25:36.977  1014  2730 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-31 15:25:36.977  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 15:25:36.977  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-31 15:25:36.977  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-31 15:25:36.977  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-31 15:25:36.977  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-31 15:25:36.997  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-31 15:25:36.997  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-31 15:25:36.997  1014  1312 I art     : Explicit concurrent mark sweep GC freed 17292(1387KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 6.786ms total 174.778ms
08-31 15:25:36.997  1014  1054 I art     : WaitForGcToComplete blocked for 374.111ms for cause Explicit
,08-31 15:25:37.007  1926  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 15:25:37.007  1014  1319 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=32
,08-31 15:25:37.007   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-31 15:25:37.007  1014  1319 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 15:25:37.007  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-31 15:25:37.017  6509  6509 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
08-31 15:25:37.017  1014  1027 D InputDispatcher: Focus entered window: 3162
,08-31 15:25:37.017  1014  1026 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 15:25:37.017  1014  1026 D SecContentProvider2: mCursor = null
,08-31 15:25:37.017  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 15:25:37.017  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 15:25:37.017  3162  3162 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 15:25:37.017  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 15:25:37.017  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-31 15:25:37.027  1014  1038 W TextServicesManagerService: no available spell checker services found
,08-31 15:25:37.027  3162  3162 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-31 15:25:37.027  3162  3162 V ActivityThread: updateVisibility : ActivityRecord{5464132 token=android.os.BinderProxy@2a37a9f1 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-31 15:25:37.037  1014  1129 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-31 15:25:37.047  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.047  1178  1178 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-31 15:25:37.057  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
08-31 15:25:37.057  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:37.057  1178  1178 D PanelView: There is/are notification(s) 
08-31 15:25:37.057  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 15:25:37.057  1705  1705 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 15:25:37.057  1014  1493 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 15:25:37.057  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,08-31 15:25:37.057  1178  1178 D PanelView: There is/are notification(s) 
,08-31 15:25:37.057  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 15:25:37.067  1014  1493 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6186 uid 10155
,08-31 15:25:37.067  1014  7046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 15:25:37.067  6524  6524 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 15:25:37.077  1785  1785 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-31 15:25:37.077  1705  1705 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-31 15:25:37.077  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:37.087  3162  3162 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a37a9f1 time:149831
,08-31 15:25:37.087  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.087  1178  1178 D PanelView: There is/are notification(s) 
,08-31 15:25:37.087  1705  1705 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,08-31 15:25:37.087  1705  1705 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-31 15:25:37.087  1705  1705 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 15:25:37.087  1315  4824 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-31 15:25:37.097  1014  1076 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 15:25:37.097  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.107  1014  1044 W ActivityManager: mDVFSHelper.release()
,08-31 15:25:37.107  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{102904a8 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149853
,08-31 15:25:37.107  1705  1705 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 15:25:37.117  1705  1705 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-31 15:25:37.117  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 15:25:37.117  6458  6458 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 15:25:37.117  6458  6458 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 15:25:37.117  6458  6458 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 15:25:37.117  1705  1705 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-31 15:25:37.117  6524  6524 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 15:25:37.127  6681  6681 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:37.127  6681  6681 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 15:25:37.127  6681  6681 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-31 15:25:37.127  6681  6681 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 15:25:37.127  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-31 15:25:37.127  6524  6524 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 15:25:37.137  6524  6524 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 15:25:37.167  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 15:25:37 GMT+02:00 2016
,08-31 15:25:37.177  1014  2928 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 15:25:37.177  1014  2928 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 15:25:37.177  1014  1054 I art     : Explicit concurrent mark sweep GC freed 7999(469KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 3.359ms total 179.643ms
,08-31 15:25:37.187  1014  2928 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:37.187  1014  2928 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:37.187  1014  2928 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 15:25:37.197  1014  1991 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 15:25:37.197  1014  1991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
08-31 15:25:37.197  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 15:25:37.197  1014  1991 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:37.197  1014  1991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 15:25:37.197  1014  1991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 15:25:37.197  1014  2928 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 15:25:37.197  1014  2928 D SecContentProvider2: mCursor = null
,08-31 15:25:37.207  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 15:25:37.207   277   969 D EnterpriseController: uids 10012
08-31 15:25:37.207   277   969 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 15:25:37.207   277   969 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,08-31 15:25:37.217  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.217  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 15:25:37.217  3684  3684 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 15:25:37.227  3785  3785 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 15:25:37.227  3684  3684 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 15:25:37.227  3684  7051 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 15:25:37.227  3684  7051 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 15:25:37.237  1014  1054 D PackageManager: delete codoeFile: 
,08-31 15:25:37.237  3785  4556 I iu.UploadsManager: num queued entries: 0
,08-31 15:25:37.237  3785  4556 I iu.UploadsManager: num updated entries: 0
,08-31 15:25:37.237  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-31 15:25:37.237  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-31 15:25:37.237  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:37.237  3684  7051 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
08-31 15:25:37.237  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 15:25:37.237  3684  7051 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,08-31 15:25:37.237  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-31 15:25:37.237  3785  4556 I iu.SyncManager: NEXT; no task
,08-31 15:25:37.247  3684  7051 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,08-31 15:25:37.247  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-31 15:25:37.247  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-31 15:25:37.247  1014  1054 D PackageManager: result of delete: 1{295399205}
08-31 15:25:37.247  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 15:25:37.257  3684  7051 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,08-31 15:25:37.257  3684  7051 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
08-31 15:25:37.267  7030  7030 D AndroidRuntime: Shutting down VM
08-31 15:25:37.267  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.267  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 15:25:37.267  1014  1054 D PackageManager: userId{-1}
08-31 15:25:37.267  1014  1054 D PackageManager: andCode{true}
,08-31 15:25:37.277  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 15:25:37.277  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:37.277  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 15:25:37.277  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.277  6745  6745 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:37.287  5929  5929 D WaitQueueForNetworkActivate: notifyNetworkActivated
08-31 15:25:37.287  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 15:25:37.297  6745  6745 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-31 15:25:37.297  6745  6745 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 15:25:37.297  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-31 15:25:37.317  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.317  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.317  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 15:25:37.317  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 15:25:37.327  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.327  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 15:25:37.327  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 15:25:37.327  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 15:25:37.327  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 15:25:37.337  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 15:25:37.337  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-31 15:25:37.337  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 15:25:37.337  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-31 15:25:37.337  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.337  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.337  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.337  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.347  3202  7063 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-31 15:25:37.347  3202  7063 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-31 15:25:37.347  3202  7063 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 15:25:37.357  7064  7064 E Zygote  : MountEmulatedStorage()
08-31 15:25:37.357  7064  7064 E Zygote  : v2
08-31 15:25:37.357  7064  7064 I libpersona: KNOX_SDCARD checking this for 10035
08-31 15:25:37.357  7064  7064 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:37.357  7064  7064 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:37.367  7064  7064 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:37.367  7064  7064 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-31 15:25:37.367  1014  1027 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7064 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 15:25:37.387   312   312 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 746us total 22.062ms
,08-31 15:25:37.397  7064  7064 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:37.397  7064  7064 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:37.407   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 18.072ms
,08-31 15:25:37.407  3202  7063 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
08-31 15:25:37.407  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
08-31 15:25:37.407  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
08-31 15:25:37.407  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-31 15:25:37.407  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-31 15:25:37.417  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-31 15:25:37.417  3202  7063 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 15:25:37.417  3202  7063 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-31 15:25:37.427   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 18.887ms
,08-31 15:25:37.427  3202  7063 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-31 15:25:37.447  3202  7063 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 15:25:37.457  7064  7082 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-31 15:25:37.467  7064  7082 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-31 15:25:37.467  7064  7064 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-31 15:25:37.467  6018  6018 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-31 15:25:37.467  6018  6018 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-31 15:25:37.467  6018  6018 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 15:25:37.477  6018  6018 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 15:25:37.477  6018  6018 I SA      : [OR] == isSIMCardReady false ==
,08-31 15:25:37.477  7064  7082 D SPPClientService: PushLog.txt file is not deleted.
,08-31 15:25:37.477  7064  7082 D SPPClientService: PushLog.txt file is not deleted.
08-31 15:25:37.477  7064  7082 D SPPClientService: ============PushLog. stop!
,08-31 15:25:37.477  6018  6018 I SA      : [SCU] == networkStateCheck == true
,08-31 15:25:37.477  6018  6018 I SA      : [DM] getCountryCodeFromCSC : PL
08-31 15:25:37.477  6018  6018 I SA      : isChinaCountryCode : false
08-31 15:25:37.477  6018  6018 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 15:25:37.477  6018  6018 I SA      : [OR] == networkStateCheck true ==
,08-31 15:25:37.477  6018  6018 I SA      : [OR] GetMyCountryZoneTask
,08-31 15:25:37.477  6018  6018 I SA      : [OR] onReceive END
,08-31 15:25:37.477  6018  7084 I SA      : [SRS] prepareGetMyCountryZone
,08-31 15:25:37.487  7030  7030 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 15:25:37.487  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 15:25:37.487  1014  4552 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-31 15:25:37.487  1014  4552 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-31 15:25:37.497  1014  4552 W ActivityManager: userId = 0, bbcId = -10000,
08-31 15:25:37.497  1014  4552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:37.497  1014  4552 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
08-31 15:25:37.497  6018  7084 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-31 15:25:37.497  6018  7084 I SA      : [SSP] query invoked
,08-31 15:25:37.497  6018  7084 I SA      : [TPMU] GetMccFromDB : null
,08-31 15:25:37.507  6018  7084 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-31 15:25:37.507  6018  7084 I SA      : [LBE] isSupportCheckDomainRegion : false
08-31 15:25:37.507  6018  7084 I SA      : [TPM] isNoProxy(default) : true
,08-31 15:25:37.507  1014  1493 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-31 15:25:37.507  1014  1319 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-31 15:25:37.507  1014  1319 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
08-31 15:25:37.507  1014  1493 D SecContentProvider2: mCursor = null
,08-31 15:25:37.507  1014  1319 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:37.507  1014  1319 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 15:25:37.507  1014  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-31 15:25:37.507  1014  1312 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 15:25:37.517  6018  7084 E File    : fail readDirectory() errno=2
,08-31 15:25:37.517  5929  5929 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-31 15:25:37.517  5929  5929 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-31 15:25:37.517  5929  5929 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-31 15:25:37.517  5929  5929 D InitializeManagerStateMachine: exit::IDLE
08-31 15:25:37.517  5929  5929 D InitializeManagerStateMachine: entry::NETWORK_CHECK
08-31 15:25:37.527  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 15:25:37 GMT+02:00 2016
,08-31 15:25:37.527  1014  1076 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-31 15:25:37.527  1014  1076 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-31 15:25:37.527  5929  5929 D InitializeManagerStateMachine: entry::SUCCESS
,08-31 15:25:37.527  5929  5929 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
08-31 15:25:37.527  1014  1076 W ActivityManager: userId = 0, bbcId = -10000
08-31 15:25:37.527  1014  1076 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:37.527  1014  1076 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 15:25:37.527  3684  3684 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 15:25:37.527  1014  1493 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-31 15:25:37.527  1014  1493 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-31 15:25:37.527  1014  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-31 15:25:37.537  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.537  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.537  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.537  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.537  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 15:25:37.537  3684  3684 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,08-31 15:25:37.547  3684  3684 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 15:25:37.547  7089  7089 E Zygote  : MountEmulatedStorage()
,08-31 15:25:37.547  7089  7089 E Zygote  : v2
08-31 15:25:37.547  7089  7089 I libpersona: KNOX_SDCARD checking this for 10094
08-31 15:25:37.547  7089  7089 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:37.547  7089  7089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 15:25:37.547  1014  1493 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7089 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-31 15:25:37.547  5929  5929 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-31 15:25:37.557  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-31 15:25:37.547  5929  5929 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
08-31 15:25:37.557  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.557  7089  7089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:37.557  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.557  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-31 15:25:37.557  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.557  5929  5929 D InitializeManagerStateMachine: exit::SUCCESS
08-31 15:25:37.557  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.557  5929  5929 D InitializeManagerStateMachine: entry::IDLE
08-31 15:25:37.557  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
08-31 15:25:37.557  7089  7089 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 15:25:37.557  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
08-31 15:25:37.557  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-31 15:25:37.577  7089  7089 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:37.577  7089  7089 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:37.587  7103  7103 E Zygote  : MountEmulatedStorage()
,08-31 15:25:37.587  7103  7103 I libpersona: KNOX_SDCARD checking this for 10044
08-31 15:25:37.587  7103  7103 E Zygote  : v2
08-31 15:25:37.587  7103  7103 I libpersona: KNOX_SDCARD not a persona
08-31 15:25:37.587  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:37.587  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7103 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,08-31 15:25:37.587  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 15:25:37.587  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-31 15:25:37.587  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 15:25:37.597  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.597  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.597  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.597  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.607  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:37.617  7103  7103 D ActivityThread: Added TimaKeyStore provider
08-31 15:25:37.617  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-31 15:25:37.617  7120  7120 E Zygote  : MountEmulatedStorage()
08-31 15:25:37.617  7120  7120 I libpersona: KNOX_SDCARD checking this for 10149
08-31 15:25:37.617  7120  7120 E Zygote  : v2
08-31 15:25:37.617  7120  7120 I libpersona: KNOX_SDCARD not a persona
,08-31 15:25:37.617  7120  7120 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 15:25:37.627  7120  7120 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 15:25:37.627  7120  7120 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-31 15:25:37.627  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7120 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-31 15:25:37.637  1926  7049 I qtaguid : Tagging socket 55 with tag 1000040700000000{268436487,0} for uid -1, pid: 1926, getuid(): 10012
,08-31 15:25:37.637  3684  7087 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-31 15:25:37.647  3684  7087 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-31 15:25:37.657  5734  7113 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 15:25:37.657  7103  7103 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 15:25:37.657  7120  7120 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 15:25:37.657  7120  7120 D ActivityThread: Added TimaKeyStore provider
,08-31 15:25:37.657  3684  3684 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 15:25:37.677  5734  7113 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/seatbelt.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-31 15:25:37.707  7089  7089 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
08-31 15:25:37.707  5734  5734 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/history.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-31 15:25:37.707  7089  7089 D elm:15183: ELMEngine.ELMEngine( context ).
,08-31 15:25:37.707  7089  7089 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-31 15:25:37.707  1014  1746 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-31 15:25:37.707  1014  1746 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-31 15:25:37.707  1014  1746 W ActivityManager: userId = 0, bbcId = -10000
,08-31 15:25:37.707  1014  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 15:25:37.707  1014  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-31 15:25:37.717  7089  7089 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-31 15:25:37.717  3339  3339 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-31 15:25:37.717  3339  3339 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-31 15:25:37.717  3339  3339 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-31 15:25:37.717  3339  3339 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-31 15:25:37.717  3339  3339 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:37.717  3339  3339 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:37.717  3339  3339 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:37.717  3339  3339 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:37.717  3339  3339 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 15:25:37.727  5734  5734 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-31 15:25:37.727  5734  5734 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM discovered_threats WHERE package_name=?] disk I/O error
08-31 15:25:37.727  5734  7113 I art     : Explicit concurrent mark sweep GC freed 718(53KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 1.349ms total 52.151ms
,08-31 15:25:37.727  6492  6492 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-31 15:25:37.727  6492  6492 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 15:25:37.727  6492  6492 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-31 15:25:37.727  6492  6492 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-31 15:25:37.727  5734  5734 D AndroidRuntime: Shutting down VM
,08-31 15:25:37.737  5734  5734 E AndroidRuntime: FATAL EXCEPTION: main
08-31 15:25:37.737  5734  5734 E AndroidRuntime: Process: com.samsung.android.sm, PID: 5734
08-31 15:25:37.737  5734  5734 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:145)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	,at com.samsung.android.sm.common.security.i.c(MalwareDatabaseHelper.java:207)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:192)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-31 15:25:37.737  5734  5734 E AndroidRuntime: 	... 9 more
08-31 15:25:37.737  7089  7089 D elm:15183: ElmAgentService : onCreate()
08-31 15:25:37.737  7120  7120 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-31 15:25:37.737  7120  7120 D ThemeInfoUtil: isCurrentFestival = false
,08-31 15:25:37.737  7089  7136 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-31 15:25:37.737  7089  7136 D elm:15183: MainReceiver.listeningToPackageRemoved()
,08-31 15:25:37.737  7089  7136 D elm:15183: MDMBridge.getInstance()
,08-31 15:25:37.737  7089  7136 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 15:25:37.737  1014  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
,08-31 15:25:37.737  7089  7136 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-31 15:25:37.747  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-31 15:25:37.747  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.747  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.747  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 15:25:37.747  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 15:25:37.757  5906  5918 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-31 15:25:37.757  5906  5918 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,08-31 15:25:37.757  5906  5918 E DatabaseUtils: Writing exception to parcel
08-31 15:25:37.757  5906  5918 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-31 15:25:37.757  5906  5918 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 15:25:37.757  7103  7103 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30),

```
