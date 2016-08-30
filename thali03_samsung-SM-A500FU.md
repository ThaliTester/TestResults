#### Test 828946826174a68_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-30 17:07:52.951   287   287 E SMD     : DCD OFF
,08-30 17:07:53.761  6181  6181 D AndroidRuntime: 
08-30 17:07:53.761  6181  6181 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:07:53.771  6181  6181 D AndroidRuntime: CheckJNI is OFF
08-30 17:07:53.771  6181  6181 D AndroidRuntime: readGMSProperty: start
08-30 17:07:53.771  6181  6181 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:07:53.771  6181  6181 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:07:53.771  6181  6181 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:07:53.771  6181  6181 D AndroidRuntime: readGMSProperty: end
08-30 17:07:53.771  6181  6181 D AndroidRuntime: addProductProperty: start
08-30 17:07:53.931  6181  6181 E AffinityControl: AffinityControl: registerfunction enter
08-30 17:07:53.951  6181  6181 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 17:07:53.961  1015  1470 E PersonaManagerService: inState():  stateMachine is null !!
08-30 17:07:53.961  1015  1470 I PersonaManagerService: PersonaId don't exist
08-30 17:07:53.961  1015  1470 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 17:07:53.961  1015  1470 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-30 17:07:53.981  1015  1470 W ActivityManager: mDVFSHelper.acquire()
08-30 17:07:53.991  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 17:07:53.991  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 17:07:54.001  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:54.001  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:54.001  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:54.001  1015  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:07:54.011  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 17:07:54.011  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 17:07:54.011   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-30 17:07:54.011  1015  1470 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6192 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:07:54.011  6192  6192 E Zygote  : MountEmulatedStorage()
08-30 17:07:54.011  6192  6192 E Zygote  : v2
08-30 17:07:54.011  6192  6192 I libpersona: KNOX_SDCARD checking this for 10155
08-30 17:07:54.011  6192  6192 I libpersona: KNOX_SDCARD not a persona
08-30 17:07:54.011  1015  1470 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-30 17:07:54.011  1015  1470 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:07:54.021  6192  6192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:07:54.021  6192  6192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:07:54.021  6192  6192 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 17:07:54.031  1015  1470 D InputDispatcher: Focused application set to: xxxx
08-30 17:07:54.031  1015  1470 D InputDispatcher: Focus left window: 3173
08-30 17:07:54.031  6181  6181 D AndroidRuntime: Shutting down VM
08-30 17:07:54.031   304   304 I art     : Explicit concurrent mark sweep GC freed 8702(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 20.929ms
08-30 17:07:54.051  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:07:54.051  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 17:07:54.051   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 17.609ms
08-30 17:07:54.061  6192  6192 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:07:54.061  6192  6192 D ActivityThread: Added TimaKeyStore provider
08-30 17:07:54.061  1015  1015 V ActivityManager: Display changed displayId=0
08-30 17:07:54.071   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.774ms
08-30 17:07:54.071  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 17:07:54.081  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
08-30 17:07:54.131   257  1099 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
08-30 17:07:54.131   257   435 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
08-30 17:07:54.131  3173  3173 V ActivityThread: updateVisibility : ActivityRecord{159926e9 token=android.os.BinderProxy@12358bb4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-30 17:07:54.201  6192  6192 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-30 17:07:54.211  6192  6192 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1023-1024)
08-30 17:07:54.211  6192  6192 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:07:54.241  6181  6181 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 17:07:54.241  6192  6192 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11bc2af5}
,08-30 17:07:54.251  6192  6192 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:07:54.251  6192  6192 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:07:54.281  6192  6192 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,08-30 17:07:54.281  6192  6192 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-30 17:07:54.281  6192  6192 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-30 17:07:54.301  6192  6192 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 17:07:54.301  6192  6192 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-30 17:07:54.301  6192  6192 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-30 17:07:54.311  6192  6192 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:07:54.311  6192  6192 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:07:54.311  6192  6192 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:07:54.311  6192  6192 I Adreno-EGL: Local Branch: 
08-30 17:07:54.311  6192  6192 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:07:54.311  6192  6192 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:07:54.311  6192  6192 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:07:54.431  6192  6218 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-30 17:07:54.481  6192  6192 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:07:54.491  6192  6192 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 17:07:54.501  6192  6192 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-30 17:07:54.501  6192  6192 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 17:07:54.511  6192  6192 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 17:07:54.511  6192  6192 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:07:54.511  6192  6192 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:07:54.551  6192  6231 D OpenGLRenderer: Render dirty regions requested: true
,08-30 17:07:54.561  1015  5585 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 17:07:54.561  1015  5585 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:07:54.561  1015  5585 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 17:07:54.561  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 17:07:54.561  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 17:07:54.571  6192  6192 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 17:07:54.571  6192  6192 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 17:07:54.581   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-30 17:07:54.581  1015  1560 D InputDispatcher: Focus entered window: 6192
,08-30 17:07:54.591  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:07:54.591  6192  6192 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-30 17:07:54.591  6192  6231 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 17:07:54.591  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:07:54.591  6192  6231 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 17:07:54.591  6192  6231 D OpenGLRenderer: Enabling debug mode 0
,08-30 17:07:54.621  6192  6192 V ActivityThread: updateVisibility : ActivityRecord{4c1caf4 token=android.os.BinderProxy@2e86a606 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 17:07:54.641  1015  3085 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:07:54.651  1015  6234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:07:54.651  1177  1177 D PanelView: There is/are notification(s) 
,08-30 17:07:54.661  1828  1828 I SamsungIME: getCurrentCandidateView
,08-30 17:07:54.661  6192  6192 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-30 17:07:54.661  6192  6192 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e86a606 time:111474
,08-30 17:07:54.661  1015  1045 I ActivityManager: Displayed Component not be shown by security: +577ms (total +669ms)
,08-30 17:07:54.661  1015  1045 W ActivityManager: mDVFSHelper.release()
,08-30 17:07:54.671  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2962172 u0 com.test.thalitest/.MainActivity t128} time:111480
,08-30 17:07:54.671   257   442 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-30 17:07:54.671   257   435 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-30 17:07:54.731  6192  6192 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6192
,08-30 17:07:54.761  1828  1828 D SamsungIME: Dismiss ExpandCandiate
,08-30 17:07:54.841  6192  6192 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:07:54.901  1828  1828 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 17:07:54.931  1828  1828 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 17:07:54.941  1828  1828 I SamsungIME: KeybaordView init() : load resources
,08-30 17:07:54.951  6192  6236 D jxcore_app_log: JniHelper::setJavaVM(0xb8dac328), pthread_self() = -1187976152
,08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 17:07:54.961  6192  6236 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5e7d924 added. We now have 1 listener(s)
,08-30 17:07:54.971  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-30 17:07:54.971  1828  1828 I SamsungIME: getCurrentKeyboard
,08-30 17:07:54.971  1828  1828 I SamsungIME: getTextKeyboard
,08-30 17:07:54.981  6192  6236 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 17:07:54.981  6192  6236 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:07:54.981  6192  6236 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:07:54.981  6192  6236 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1dfb1e53 added. We now have 1 listener(s)
,08-30 17:07:54.991  6192  6236 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:07:54.991  1828  1828 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 17:07:54.991  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:07:54.991  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-30 17:07:54.991  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:07:54.991  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:07:54.991  6192  6236 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 17:07:55.001  6192  6236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:07:55.001  6192  6236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-30 17:07:55.011  6192  6236 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:07:55.011  6192  6236 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:07:55.011  6192  6236 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:07:55.011  6192  6236 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:07:55.011  6192  6236 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:07:55.011  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:07:55.011  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:07:55.041  6192  6192 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:07:55.541  1828  6241 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 17:07:55.581  6192  6244 W jxcore-log: Initializing JXcore engine
08-30 17:07:55.581  6192  6244 W jxcore-log: JXcore engine is ready
,08-30 17:07:55.641  1906  1906 E audit   : type=1400 msg=audit(1472569675.641:205): avc:  denied  { ioctl } for  pid=6244 comm="Thread-1073" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:07:55.641  1906  1906 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:07:55.641  1906  1906 E audit   : type=1300 msg=audit(1472569675.641:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e3048f8 items=0 ppid=304 ppcomm=main pid=6244 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1073" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-30 17:07:55.641  1906  1906 E audit   : type=1320 msg=audit(1472569675.641:205): 
,08-30 17:07:55.651  6192  6244 W jxcore-log: Starting JXcore engine
,08-30 17:07:55.761  6192  6244 W jxcore-log: Platform android
08-30 17:07:55.761  6192  6244 W jxcore-log: 
08-30 17:07:55.761  6192  6244 W jxcore-log: Process ARCH arm
08-30 17:07:55.761  6192  6244 W jxcore-log: 
,08-30 17:07:55.951   287   287 E SMD     : DCD OFF,
,08-30 17:07:55.961  6192  6244 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 17:07:55.961  6192  6244 I jxcore-log: 
08-30 17:07:55.961  6192  6244 W jxcore-log: JXcore engine is started
,08-30 17:07:55.961  6192  6236 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 17:07:55.971  6192  6192 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 17:07:56.971   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:07:57.481  5419  5419 D FactoryTest: Not factory mode
,08-30 17:07:57.481  5419  5419 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 17:07:57.481  5419  5419 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 17:07:57.481  5419  5419 D MTPRx   : still no open session command from host, so toast
08-30 17:07:57.481  5419  5419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 17:07:57.481  5419  5419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 17:07:57.481  5419  5419 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114296
08-30 17:07:57.481  1015  1476 E PersonaManagerService: inState():  stateMachine is null !!
08-30 17:07:57.481  1015  1476 I PersonaManagerService: PersonaId don't exist
,08-30 17:07:57.481  1015  1476 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 17:07:57.491  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-30 17:07:57.491  1015  1476 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:07:57.491  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:07:57.491  1015  1476 W ActivityManager: mDVFSHelper.acquire()
08-30 17:07:57.491  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,08-30 17:07:57.501  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:07:57.511  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 17:07:57.511  1015  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-30 17:07:57.521  1015  1476 D InputDispatcher: Focused application set to: xxxx
,08-30 17:07:57.521  1015  1476 D InputDispatcher: Focus left window: 6192
,08-30 17:07:57.521  5419  5419 E MTPRx   : started activity for popup
,08-30 17:07:57.521  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:07:57.521  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:07:57.541  5419  5419 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 17:07:57.541  5419  5419 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:07:57.551  5419  5419 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:07:57.551  5419  5419 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:07:57.551  5419  5419 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:07:57.551  5419  5419 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:07:57.561  5419  5419 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 17:07:57.571  1015  3082 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 17:07:57.571  1015  3082 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 17:07:57.571  1015  3082 D InputDispatcher: Focused application set to: xxxx
,08-30 17:07:57.571  1015  3082 D InputDispatcher: Focus entered window: 6192
,08-30 17:07:57.571  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 17:07:57.571  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:07:57.571  1015  1470 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:07:57.571  1015  1470 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1c2f79cd attribute=null, token = android.os.BinderProxy@58aff5d
,08-30 17:07:57.611  5419  5419 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-30 17:07:57.621  5419  5419 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-30 17:07:57.621  5419  5419 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 17:07:57.641  6192  6192 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:07:57.641  6192  6192 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 17:07:57.641  6192  6192 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:07:57.641  6192  6192 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 17:07:57.651  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 17:07:57.651  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-30 17:07:57.651  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 17:07:57.651  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 17:07:57.651  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 17:07:57.661  6192  6192 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:07:57.661  6192  6192 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 17:07:57.661  6192  6192 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15aebb65 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2b5087ad, 16908290=android.view.AbsSavedState$1@2b5087ad}, android:focusedViewId=100}]}]
08-30 17:07:57.661  6192  6192 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 17:07:57.661  6192  6192 V ActivityThread: updateVisibility : ActivityRecord{4c1caf4 token=android.os.BinderProxy@2e86a606 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 17:07:57.661  6192  6192 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 17:07:57.661  6192  6192 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 17:07:57.661  6192  6192 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e86a606 time:114479
,08-30 17:07:57.671  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:07:57.971   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:07:58.951   287   287 E SMD     : DCD OFF,
,08-30 17:07:58.971   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:07:59.251  1015  5585 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:07:59.251  1015  5585 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3935, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 17:07:59.251  1015  5585 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 17:07:59.251  1015  5585 D BatteryService: stay LED for charging
,08-30 17:07:59.251  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:07:59.251  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-30 17:07:59.251  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:07:59.251  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 17:07:59.251  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,08-30 17:07:59.251  1015  1015 I MotionRecognitionService: Plugged
08-30 17:07:59.251  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:07:59.261  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:07:59.271  2649  2739 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:07:59.281  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:07:59.281  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
08-30 17:07:59.281  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:07:59.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:07:59.991  1015  1093 V AlarmManager: waitForAlarm result :8,
,08-30 17:08:00.481  1015  2806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:00.491  1015  1040 W ActivityManager: mDVFSHelper.release()
,08-30 17:08:00.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:01.221  1015  2748 D SSRM:n  : SIOP:: AP = 340
,08-30 17:08:01.951   287   287 E SMD     : DCD OFF,
,08-30 17:08:01.981   312   312 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 17:08:03.191  1015  1093 V AlarmManager: waitForAlarm result :4,
,08-30 17:08:03.201  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,08-30 17:08:03.211  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___,
,08-30 17:08:03.211  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-30 17:08:03.211  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-30 17:08:03.211  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-30 17:08:03.211  1177  1177 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 17:08:03.221  1177  1177 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 17:08:03.231  1924  1924 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 17:08:03.231  1177  1177 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 17:08:03.241  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:03.241  1177  1177 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-30 17:08:03.241  1177  1177 I KeyguardEffectViewController: *** don't update sliding image ***
,08-30 17:08:03.411  1015  1560 I art     : Explicit concurrent mark sweep GC freed 55488(3MB) AllocSpace objects, 29(895KB) LOS objects, 33% free, 28MB/42MB, paused 2.506ms total 161.972ms
,08-30 17:08:03.431  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:03.431  1015  3085 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:03.431  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.431  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:03.431  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.431  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.441  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:03.441  3775  3775 D ConnectivityManager: CallingUid : 10012, CallingPid : 3775
,08-30 17:08:03.441  1177  1177 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:03.441  1015  1219 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:03.441  1015  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-30 17:08:03.441  1015  1132 D ConnectivityService: apparently satisfied.  currentScore=60
,08-30 17:08:03.451  1015  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-30 17:08:03.451  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 17:08:03.471  1177  1177 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 17:08:03.531  3775  6255 W DriveInitializer: Background init thread started
,08-30 17:08:03.541   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-30 17:08:03.541   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:03.551  3775  6255 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 17:08:03.591  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:03.591  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.591  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:03.591  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:03.591  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.621  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:03.621  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.621  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:03.621  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.621  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.631  1015  1560 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-30 17:08:03.631  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.641  3775  6255 W DriveInitializer: Background init thread ended
,08-30 17:08:03.651  3775  6263 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-30 17:08:03.651  3775  6263 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 17:08:03.671  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:03.691  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:03.691  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:03.691  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.771  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:03.771  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.771  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:03.771  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.771  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.801  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:03.811  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 17:08:03.811  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:03.811  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.811  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.861  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:03.861  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:03.861  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.861  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.901  1015  3082 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:03.911  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:03.911  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.911  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.961  1015  3085 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:03.961  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:03.961  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:03.961  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:03.961  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:03.961  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:03.961  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:03.971  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:03.981  6268  6268 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:03.981  6268  6268 E Zygote  : v2,
08-30 17:08:03.981  6268  6268 I libpersona: KNOX_SDCARD checking this for 10012
08-30 17:08:03.981  6268  6268 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:03.991  6268  6268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:03.991  1015  3085 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6268 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-30 17:08:03.991  6268  6268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:03.991  6268  6268 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:04.031  6268  6268 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:04.031  6268  6268 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:04.041  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 17:08:04.051  6268  6268 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 17:08:04.051  6268  6268 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:08:04.101  6268  6268 I MultiDex: VM with version 2.1.0 has multidex support
08-30 17:08:04.101  6268  6268 I MultiDex: install
08-30 17:08:04.101  6268  6268 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 17:08:04.131  6268  6268 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 17:08:04.191  6268  6268 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 17:08:04.191  6268  6268 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@32119f66: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 17:08:04.191  6268  6268 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-30 17:08:04.231  6268  6268 D ChimeraCfgMgr: Reading stored module config
,08-30 17:08:04.241  1924  1936 I art     : Explicit concurrent mark sweep GC freed 76968(4MB) AllocSpace objects, 14(464KB) LOS objects, 39% free, 13MB/23MB, paused 1.433ms total 76.057ms
,08-30 17:08:04.301  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.301  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.301  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:04.301  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.301  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.321  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.321  6268  6285 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 17:08:04.331  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.331  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.331  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.341  6268  6268 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 17:08:04.341  6268  6268 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 17:08:04.361  1924  1924 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=949ea14b-2bca-4c35-b9ad-5c7cfd9697c2
,08-30 17:08:04.371  1015  3083 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:04.371  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 17:08:04.371  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:04.371  1015  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:04.371  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.371  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:04.381  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:04.421  1015  3082 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.431  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.431  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.431  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.461   282   695 D WVCdm   : Instantiating CDM.
,08-30 17:08:04.461   282   726 I WVCdm   : CdmEngine::OpenSession
08-30 17:08:04.461   282   726 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 17:08:04.481   282   726 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 17:08:04.501   282   726 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,08-30 17:08:04.501   282   726 D DrmWidevineDash: Service_Initialize: starts!
08-30 17:08:04.501   282   726 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-30 17:08:04.501   282   726 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:08:04.511   282   726 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
,08-30 17:08:04.511   282   726 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 17:08:04.511   282   726 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 17:08:04.511   282   726 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:08:04.511   282   726 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-30 17:08:04.511   282   726 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 17:08:04.511   282   726 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 17:08:04.511   282   726 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 17:08:04.531   282   726 D QSEECOMAPI: : Loaded image: APP id = 11
,08-30 17:08:04.531   282   726 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-30 17:08:04.531   282   726 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-30 17:08:04.531   282   726 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-30 17:08:04.531   282   726 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb168c000
08-30 17:08:04.531   282   726 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb168c000
08-30 17:08:04.531   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.541   422   431 D DrmLibTime: got the req here! ret=0
08-30 17:08:04.541   422   431 D DrmLibTime: command id, time_cmd_id = 770
08-30 17:08:04.541   422   431 D DrmLibTime: time_getutcsec starts!
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-30 17:08:04.541   422   431 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
08-30 17:08:04.541   422   431 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-30 17:08:04.541   422   431 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-30 17:08:04.541   422   431 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
08-30 17:08:04.541   314   555 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-30 17:08:04.541   314  6291 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
08-30 17:08:04.541   314  6291 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-30 17:08:04.541   314  6291 D QC-time-services: offset is: 0 for base: 0,
,08-30 17:08:04.541   422   431 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-30 17:08:04.541   422   431 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472569684
,08-30 17:08:04.541   422   431 D DrmLibTime: time_getutcsec returns 0, sec = 1472569684; nsec = 0
08-30 17:08:04.541   422   431 D DrmLibTime: time_getutcsec finished! ,
08-30 17:08:04.541   422   431 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-30 17:08:04.541   422   431 D DrmLibTime: before calling ioctl to read the next time_cmd
08-30 17:08:04.541   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 17:08:04.551   314   555 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-30 17:08:04.561   282   726 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-30 17:08:04.561   282   726 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 17:08:04.561   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.561   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.561   282   726 D DrmWidevineDash: hlos api version =  9
08-30 17:08:04.561   282   726 D DrmWidevineDash: tz api version =  9
08-30 17:08:04.561   282   726 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-30 17:08:04.561   282   726 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-30 17:08:04.561   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.571  1628  1715 I art     : Explicit concurrent mark sweep GC freed 1412(48KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 714us total 25.212ms
,08-30 17:08:04.581   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-30 17:08:04.581   282   726 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb17e0960
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-30 17:08:04.581   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.581   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8c004f0, dataLength=8
08-30 17:08:04.581   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 17:08:04.581   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.581   282   726 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-30 17:08:04.591   282   726 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8bdcb68, wrapped_rsa_key_length=1280
08-30 17:08:04.591   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.591   282   726 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.591   282   726 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-30 17:08:04.591   282   726 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 17:08:04.591   282   695 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 17:08:04.591   282   695 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 17:08:04.591   282   695 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 17:08:04.591   282   695 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8bffe28, idLength=0xb18e0730
08-30 17:08:04.591   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb18e0746, maximum = 0xb18e0747
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: hlos api version =  9
08-30 17:08:04.611   282   695 D DrmWidevineDash: tz api version =  9
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18e07b4
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-30 17:08:04.611   282   695 D WVCdm   : PrepareKeyRequest: nonce=506219313
08-30 17:08:04.611   282   695 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8bdc808
08-30 17:08:04.611   282   695 D DrmWidevineDash: message_length=1599, signature=0xb8bdce50, signature_length=0xb18e0714
08-30 17:08:04.611   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.631  6268  6277 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 17:08:04.631  6268  6277 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:04.631  6268  6277 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 17:08:04.631  6268  6277 I System.out: (HTTPLog)-Thread-1052-479049403: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-30 17:08:04.631  6268  6277 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:04.631   277   947 D EnterpriseController: uids 10012
08-30 17:08:04.631   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:04.631   277   947 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 17:08:04.681  1924  2106 W GCoreFlp: No location to return for getLastLocation()
,08-30 17:08:04.711  1015  3085 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.711  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.711  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.711  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.721  1015  5585 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.721  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.721  1015  5585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.721  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.721  1015  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.721  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:04.721  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.721  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.741  3775  6264 D UdcContextInitService: registered all accounts: true
,08-30 17:08:04.741  1924  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:08:04.761  1924  2136 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 17:08:04.761   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.761   282   695 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-30 17:08:04.761   282   282 I WVCdm   : CdmEngine::CloseSession
,08-30 17:08:04.761   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-30 17:08:04.761   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.761   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 17:08:04.771   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-30 17:08:04.771   282   282 I WVCdm   : L3 Terminate.
08-30 17:08:04.771   282   282 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-30 17:08:04.771  6268  6277 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:04.771  6268  6277 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6268, getuid(): 10012
,08-30 17:08:04.771   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 17:08:04.771   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 17:08:04.771   282   282 D DrmWidevineDash: Service_Uninitialize: starts!
,08-30 17:08:04.771   282   282 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-30 17:08:04.771   282   282 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-30 17:08:04.771   282   282 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-30 17:08:04.771   282   282 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-30 17:08:04.881  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:04.881  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-30 17:08:04.881  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.881  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:04.881  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.921  1015  3083 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:04.921  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 17:08:04.921  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.921  1015  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.921  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:04.951   287   287 E SMD     : DCD OFF
,08-30 17:08:04.981  1015  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:04.981  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:04.981  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:04.981  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.011  1015  1470 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.011  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.011  1015  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.011  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.061  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.061  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.061  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.061  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.061  1924  6299 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:08:05.061  1924  6297 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:08:05.061  1015  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.061  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.061  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.061  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.091  1015  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.091  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.091  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.091  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.091  1924  6299 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:08:05.091  1924  6297 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:08:05.091  1015  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.091  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.091  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.091  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.121  1015  5585 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:05.121  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.121  1015  5585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.121  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.121  1924  6299 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 17:08:05.121  1924  6297 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 17:08:05.121  1924  6297 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 17:08:05.131  1924  6297 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 17:08:05.171  1015  1470 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:08:05.201  1015  1216 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:05.211  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 17:08:05.211  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:05.211  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:05.211  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:05.211  1924  6297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:05.211   277   947 D EnterpriseController: uids 10012
08-30 17:08:05.211   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:05.211   277   947 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 17:08:05.221  1924  6297 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:05.221  1924  6297 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1924, getuid(): 10012
,08-30 17:08:05.361  1924  6297 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1924, getuid(): 10012
,08-30 17:08:05.531  6268  6277 I qtaguid : Untagging socket 30
,08-30 17:08:05.891  6305  6305 I dex2oat : ----------------------------------------------------
,08-30 17:08:05.891  6305  6305 I dex2oat : <SS>: S T A R T I N G . . .
08-30 17:08:05.891  6305  6305 I dex2oat : <SS>: Zip is absent. Canceled.
08-30 17:08:05.891  6305  6305 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 17:08:05.931  6305  6305 I dex2oat : dex2oat took 36.300ms (threads: 4)
,08-30 17:08:05.941  6268  6277 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:08:05.941  6268  6277 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:05.941  6268  6277 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:05.941  6268  6277 I Adreno-EGL: Local Branch: 
08-30 17:08:05.941  6268  6277 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:05.941  6268  6277 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:05.941  6268  6277 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:06.021  6268  6277 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:08:06.021  6268  6277 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:06.021  6268  6277 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:06.021  6268  6277 I Adreno-EGL: Local Branch: 
08-30 17:08:06.021  6268  6277 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:06.021  6268  6277 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:06.021  6268  6277 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:06.071  6268  6277 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:08:06.071  6268  6277 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:06.071  6268  6277 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:06.071  6268  6277 I Adreno-EGL: Local Branch: 
08-30 17:08:06.071  6268  6277 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:06.071  6268  6277 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:06.071  6268  6277 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:06.291  1015  1476 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:08:06.301  1924  6297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:06.301  1924  6297 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1924, getuid(): 10012
,08-30 17:08:06.511  1924  6266 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:06.511   277   947 D EnterpriseController: uids 10012
08-30 17:08:06.511   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:06.511   277   947 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 17:08:06.511  1924  6266 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:06.521  1924  6266 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:06.921  1924  6266 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:06.941  1015  3085 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:08:06.951  1924  6297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:06.951  1924  6297 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1924, getuid(): 10012
,08-30 17:08:06.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:07.951   287   287 E SMD     : DCD OFF,
,08-30 17:08:07.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:08.081  1015  1560 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 17:08:08.091  1924  6297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:08.091  1924  6297 I qtaguid : Tagging socket 73 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1924, getuid(): 10012
,08-30 17:08:08.401  1924  2136 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 17:08:08.411  1924  2136 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 17:08:08.411  1924  2136 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 17:08:04.827+0200, stopTime=2016-08-30 17:08:08.418+0200, duration=3591ms
,08-30 17:08:08.421  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:08.431   277   947 D EnterpriseController: uids 10012
08-30 17:08:08.431   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:08.431   277   947 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 17:08:08.431  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:08.431  1924  6317 I qtaguid : Tagging socket 81 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:08.511  1924  2136 I art     : Explicit concurrent mark sweep GC freed 44881(2MB) AllocSpace objects, 45(1989KB) LOS objects, 40% free, 14MB/24MB, paused 1.594ms total 70.053ms
,08-30 17:08:08.521  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 17:08:08.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:08:08.541  6192  6244 I jxcore-log: 
,08-30 17:08:08.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:08:08.551  6192  6244 I jxcore-log: 
,08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:08.551  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:08.551  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:08.561  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:08:08.561  6192  6244 I jxcore-log: 
,08-30 17:08:08.561  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:08:08.561  6192  6244 I jxcore-log: 
,08-30 17:08:08.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:09.191  6192  6244 D executeNativeTests: Running unit tests
,08-30 17:08:09.271  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:09.271  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 added. We now have 2 listener(s)
,08-30 17:08:09.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:09.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:09.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:09.281  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:09.281  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 added. We now have 2 listener(s)
08-30 17:08:09.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:09.281  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:09.281  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.281  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:09.281  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:09.281  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:09.291  6192  6244 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 17:08:09.291  6192  6244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-30 17:08:09.291  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.291  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.291  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.291  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.291  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 removed from the list
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.291  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 removed from the list
,08-30 17:08:09.291  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.291  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.291  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.291  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:09.291  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.291  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.291  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.291  6192  6244 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 17:08:09.301  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.301  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.301  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 17:08:09.311  1015  3082 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:09.311  1015  3082 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3928, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:09.311  1015  3082 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:08:09.311  1015  3082 D BatteryService: stay LED for charging
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:09.311  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 17:08:09.301  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.301  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.301  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.301  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-30 17:08:09.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.301  6192  6244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 17:08:09.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:09.311  1015  1015 I MotionRecognitionService: Plugged
08-30 17:08:09.311  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.311  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:09.321  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 17:08:09.321  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
08-30 17:08:09.321  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:08:09.321  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 17:08:09.321  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.321  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:09.321  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:09.321  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:09.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:09.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:09.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:09.321  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.321  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.331  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:09.331  2649  2739 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:08:09.331  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 17:08:09.341  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
08-30 17:08:09.341  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
08-30 17:08:09.341  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
08-30 17:08:09.341  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:08:09.351  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:09.351  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 17:08:09.351  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 17:08:09.351  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:09.351  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:09.361  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 17:08:09.361  2649  2740 D BtGatt.GattService: registerClient() - UUID=9ceeb23b-d4fe-417c-804f-32d4b8430c90
,08-30 17:08:09.411  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=9ceeb23b-d4fe-417c-804f-32d4b8430c90, clientIf=6
,08-30 17:08:09.411  6192  6201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:09.411  2649  2664 D BtGatt.GattService: start scan with filters
,08-30 17:08:09.421  2649  2738 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:09.421  2649  2738 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:09.421  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:08:09.421  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:08:09.421  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 17:08:09.421  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:09.431  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:09.431  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.431  2649  2738 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:09.431  2649  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:09.431  2649  2738 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 17:08:09.441  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:09.441  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:09.441  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:09.441  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:08:09.441  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.441  2649  2738 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:08:09.441  2649  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:09.451  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:09.451  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:08:09.451  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.451  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:08:09.451  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.451  6192  6244 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:08:09.461  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.461  6192  6244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:09.461  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.461  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:09.461  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:09.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:09.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:09.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:09.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:09.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:09.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:09.471  2649  2659 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:09.471  2649  2740 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:09.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:09.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:09.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:09.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:09.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:09.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:09.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:09.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:09.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:09.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:09.481  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:09.481  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:09.481  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:09.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-30 17:08:09.481  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.481  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.481  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.481  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 17:08:09.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.481  6192  6244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:08:09.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:09.491  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:09.491  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:09.491  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:09.501  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:09.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:09.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:09.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 17:08:09.501  2649  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 71
,08-30 17:08:09.501  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:09.501  2649  2738 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:09.501  2649  2738 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 17:08:09.511  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:08:09.511  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.511  2649  2738 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:09.511  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:09.511  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:09.511  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 17:08:09.511  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.511  2649  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:09.511  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:09.511  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:09.511  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:09.521  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:09.521  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.521  2649  2868 D BtGatt.GattService: registerClient() - UUID=b8283386-8632-4f41-80e8-c352fbaa65e5
,08-30 17:08:09.561  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=b8283386-8632-4f41-80e8-c352fbaa65e5, clientIf=6
,08-30 17:08:09.561  6192  6201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 17:08:09.561  2649  2664 D BtGatt.GattService: start scan with filters
,08-30 17:08:09.561  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:08:09.561  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:09.561  2649  2738 D BtGatt.ScanManager: handling starting scan
08-30 17:08:09.561  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:09.561  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:09.561  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:09.561  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.561  2649  2738 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:09.561  2649  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:09.561  2649  2738 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-30 17:08:09.561  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:09.561  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:09.561  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:09.561  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:09.561  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-30 17:08:09.571  2649  2738 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 17:08:09.571  2649  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:09.571  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:09.571  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.571  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:09.571  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:09.571  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.581  6192  6244 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 17:08:09.581  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.581  6192  6244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:09.581  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.581  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:09.581  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:09.581  2649  2740 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:09.581  2649  2868 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 17:08:09.581  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:09.581  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:09.591  2649  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 72
,08-30 17:08:09.591  2649  2738 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:09.591  2649  2738 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:09.591  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:09.591  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.591  2649  2738 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.591  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:09.591  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:09.591  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.591  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.591  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.591  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.591  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.591  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.591  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.591  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:09.591  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.591  2649  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.591  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.591  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:08:09.591  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.591  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.591  6192  6244 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 17:08:09.601  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.601  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:09.601  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:09.601  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:09.601  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.601  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:09.601  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:09.601  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:09.601  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:09.601  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:09.611  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.611  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:09.611  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:09.611  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:09.621  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 17:08:09.621  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:09.621  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:09.621  2649  2664 D BtGatt.GattService: registerClient() - UUID=802c6b10-2bf4-4cf1-9eac-5c59c12825fc
,08-30 17:08:09.661  1924  6317 I qtaguid : Tagging socket 83 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:09.661  2649  2733 D BtGatt.GattService: onClientRegistered() - UUID=802c6b10-2bf4-4cf1-9eac-5c59c12825fc, clientIf=6
08-30 17:08:09.661  6192  6201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:09.661  2649  2659 D BtGatt.GattService: start scan with filters
,08-30 17:08:09.661  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 17:08:09.661  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:09.661  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:09.661  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:09.661  2649  2738 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:09.661  2649  2733 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:09.671  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-30 17:08:09.671  2649  2738 D BtGatt.ScanManager: allow scan with filters
08-30 17:08:09.671  2649  2738 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:09.671  2649  2738 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6,
08-30 17:08:09.671  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:09.671  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:09.671  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:09.671  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:09.671  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.671  2649  2738 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:09.671  2649  2738 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:09.671  2649  2733 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:08:09.671  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.681  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:09.681  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 17:08:09.681  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.691  6192  6244 I io.jxcore.node.ConnectionHelper: start: OK
08-30 17:08:09.691  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.691  6192  6244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:09.691  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.691  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:09.691  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.691  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:09.691  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:09.691  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:09.691  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:09.691  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:09.691  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:09.691  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:09.701  2649  2740 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:09.701  2649  2868 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:09.701  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:09.701  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:09.701  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:09.701  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:09.701  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:09.701  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:09.711  2649  2738 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 73,
08-30 17:08:09.711  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 17:08:09.711  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:09.711  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 17:08:09.711  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.711  2649  2738 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:09.711  2649  2738 D BtGatt.ScanManager: delete FilterIndex - 5
,08-30 17:08:09.711  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:09.711  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:09.711  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:09.711  2649  2733 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 17:08:09.711  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:09.711  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.711  6192  6244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 17:08:09.711  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.711  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 17:08:09.721  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:09.721  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:08:09.721  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.721  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 17:08:09.721  2649  2738 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:09.721  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.721  2649  2733 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:09.721  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.721  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.721  6192  6244 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported,
08-30 17:08:09.721  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.721  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.721  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.721  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.721  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.721  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.721  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.721  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.721  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.721  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.721  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.721  2649  2738 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:09.731  2649  2733 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:08:09.731  2649  2733 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.731  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:08:09.731  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.731  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.731  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.731  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.731  6192  6244 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 17:08:09.731  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.731  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.731  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.731  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:08:09.731  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.731  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.731  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:09.731  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.741  6192  6244 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 17:08:09.741  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.741  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.741  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.741  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 17:08:09.741  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:09.741  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 17:08:09.741  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 17:08:09.741  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.741  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.741  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.741  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.741  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.741  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.741  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.741  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.751  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:09.751  6192  6244 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-30 17:08:09.751  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:09.751  6192  6244 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 17:08:09.751  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 17:08:09.751  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 17:08:09.751  6192  6244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:09.751  6192  6244 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-30 17:08:09.751  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:09.751  6192  6244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:09.751  6192  6244 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-30 17:08:09.751  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:09.751  6192  6244 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 17:08:09.751  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-30 17:08:09.761  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-30 17:08:09.761  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 17:08:09.761  6192  6244 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 17:08:09.761  6192  6244 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 17:08:09.761  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:09.761  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.761  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.761  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.761  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.761  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-30 17:08:09.761  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.761  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.761  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.761  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.761  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.761  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:09.761  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.761  6192  6325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1137)
,08-30 17:08:09.761  6192  6326 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1137
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.761  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.761  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.771  6192  6244 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
,08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true,
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 17:08:09.771  6192  6244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:09.771  6192  6244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-30 17:08:09.771  6192  6244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 17:08:09.771  6192  6244 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 17:08:09.771  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.771  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.771  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.771  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.771  6192  6325 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.771  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.771  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  6192  6325 D BluetoothSocket: connect(): myUserId = 0
08-30 17:08:09.781  6192  6325 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not, in the list
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.781  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.781  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.781  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  2649  2664 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:09.781  6192  6325 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.781  6192  6192 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 17:08:09.781  6192  6327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 17:08:09.781  6192  6327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:09.781  6192  6192 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:09.781  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:09.781  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:09.781  6192  6192 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 17:08:09.781  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:09.781  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.781  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.781  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.781  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.781  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionMa,nager: dispose
08-30 17:08:09.781  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.781  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.791  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.791  6192  6244 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 17:08:09.791  6192  6244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 17:08:09.791  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 17:08:09.791  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.791  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.791  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.791  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.791  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.791  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.791  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.791  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:09.791  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.791  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.791  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.801  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:09.801  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:09.801  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:09.801  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:09.801  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.801  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.801  6192  6244 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175b9092 not in the list
08-30 17:08:09.801  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.801  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:09.801  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.801  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:09.801  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:09.801  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:09.801  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:09.801  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:09.801  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:09.801  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3af53a63 not in the list
,08-30 17:08:09.801  6192  6244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:09.801  6192  6244 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 17:08:09.801  6192  6244 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-30 17:08:09.801  6192  6244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:08:09.801  6192  6244 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 17:08:09.801  6192  6244 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 17:08:09.801  6192  6244 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-30 17:08:09.811  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:09.811  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@126f608d added. We now have 2 listener(s)
08-30 17:08:09.811  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:09.811  6192  6244 D BluetoothAdapter: enable()
,08-30 17:08:09.811  6192  6244 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 17:08:09.811  1015  3083 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:09.811  1015  3083 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:09.811  1015  3083 D SecContentProvider2: mCursor = null
08-30 17:08:09.811  1015  3083 D WifiService: setWifiEnabled: true pid=6192, uid=10155
08-30 17:08:09.811  1015  3083 W ActivityManager: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:09.811  1015  3083 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:09.811  1015  3083 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:09.811  1015  3083 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 17:08:09.811  1015  3083 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:08:09.811  1015  3083 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:09.811  1015  3083 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:09.811  1015  3083 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:08:09.821  1015  3083 D SettingsProvider: name = wifi_on
,08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e54242 added. We now have 3 listener(s)
08-30 17:08:09.821  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16d98253 added. We now have 4 listener(s)
,08-30 17:08:09.821  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:09.821  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f83f790 added. We now have 5 listener(s)
,08-30 17:08:09.821  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:09.831  1015  3085 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:09.831  1015  3085 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 17:08:09.831  1015  3085 D SecContentProvider2: mCursor = null
,08-30 17:08:09.831  1015  3085 D WifiService: setWifiEnabled: false pid=6192, uid=10155
,08-30 17:08:09.831  1015  3085 D SettingsProvider: name = wifi_on
,08-30 17:08:09.841  6192  6244 D BluetoothAdapter: disable()
,08-30 17:08:09.841  1015  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 17:08:09.841  2098  2098 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:09.841  2098  2098 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-30 17:08:09.841  2098  2098 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:08:09.841  2098  2098 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:08:09.841  1015  3082 D SettingsProvider: name = bluetooth_on
,08-30 17:08:09.851  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:09.851  2649  2730 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 17:08:09.851  1015  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:09.851  2649  2730 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:09.851  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 17:08:09.851  2649  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:09.851  2649  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:09.851  2649  2730 D BluetoothAdapterService: updateAdapterState state is 13
08-30 17:08:09.851  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.851  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:09.851  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:09.851  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.851  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.851  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:09.851  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.851  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:09.851  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:09.851  2649  2649 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-30 17:08:09.851  2649  2730 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:09.851  2649  2730 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:08:09.851  2649  2730 D BluetoothAdapterService: terminating service from this receiver
,08-30 17:08:09.861  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2632bf9f, channel: 19, state: LISTENING
08-30 17:08:09.861  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2632bf9f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ef622a7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@df838ecmSocket: android.net.LocalSocket@69054b5 impl:android.net.LocalSocketImpl@3e41674a fd:FileDescriptor[74]
08-30 17:08:09.861  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@69054b5 impl:android.net.LocalSocketImpl@3e41674a fd:FileDescriptor[74]
,08-30 17:08:09.861  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.861  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.861  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:09.861  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:09.861  2649  2730 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 17:08:09.861  2649  2730 D BluetoothAdapterProperties: mDiscovering is false
,08-30 17:08:09.861  1015  3083 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:09.861  2649  2730 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 17:08:09.871  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:08:09.871  1318  1318 D BluetoothPbap: Proxy object disconnected
08-30 17:08:09.871  1318  1318 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:08:09.871  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:09.871  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-30 17:08:09.871  1015  1130 E WifiNative-wlan0: do suspend true
,08-30 17:08:09.871  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.871  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:09.871  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.871  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:09.881  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:09.881  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:09.881  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:09.881  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:09.881  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-30 17:08:09.881  1828  1828 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:09.891  1015  3085 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:09.891  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:09.891  1015  1216 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:09.891  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:09.891  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:09.891  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:08:09.891  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:08:09.891  1015  3085 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:09.891  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.901  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:09.901  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:09.901  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 17:08:09.901  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.901  2649  2733 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:09.901  2649  2733 D BluetoothAdapterProperties: Scan Mode:20
08-30 17:08:09.901  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:09.901  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:09.901  2649  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:08:09.901  2649  2730 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 17:08:09.901  2649  2730 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-30 17:08:09.901  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.901  2649  2730 E bt-btif : cmd socket is not created
08-30 17:08:09.901  2649  2730 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:08:09.901  2649  2798 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 17:08:09.901  2649  2798 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:08:09.901  6192  6325 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d09408e, channel: -1, state: INIT
,08-30 17:08:09.901  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:09.901  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:09.901  6192  6325 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d09408e, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a6ff0af, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1358fcbcmSocket: android.net.LocalSocket@f4d1445 impl:android.net.LocalSocketImpl@325cd79a fd:FileDescriptor[107]
08-30 17:08:09.901  2649  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:09.901  6192  6325 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@f4d1445 impl:android.net.LocalSocketImpl@325cd79a fd:FileDescriptor[107],
08-30 17:08:09.911  2649  4977 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 17:08:09.911  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25a5f7d8, channel: 5, state: LISTENING
08-30 17:08:09.911  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25a5f7d8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2185d354, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@223e8731mSocket: android.net.LocalSocket@22b6ae16 impl:android.net.LocalSocketImpl@2bd70397 fd:FileDescriptor[76]
08-30 17:08:09.911  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@22b6ae16 impl:android.net.LocalSocketImpl@2bd70397 fd:FileDescriptor[76]
08-30 17:08:09.911  6192  6325 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1137)
08-30 17:08:09.911  2649  2649 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:09.911  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b6eb984, channel: 12, state: LISTENING
08-30 17:08:09.911  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b6eb984, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304b353e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ac3656dmSocket: android.net.LocalSocket@d6795a2 impl:android.net.LocalSocketImpl@21fe4233 fd:FileDescriptor[80]
08-30 17:08:09.911  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d6795a2 impl:android.net.LocalSocketImpl@21fe4233 fd:FileDescriptor[80]
,08-30 17:08:09.911  2649  4977 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:08:09.921  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:09.921  2649  2649 V BluetoothOppManager: cleanUp...
,08-30 17:08:09.921  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:09.921  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:09.931  1015  1028 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:09.931  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:09.931  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:09.931  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:09.931  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:09.941  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:09.941  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:09.941  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:09.941  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:08:09.951  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
,08-30 17:08:09.951  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.951  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.951  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:09.951  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:09.961  6333  6333 E Zygote  : MountEmulatedStorage()
,08-30 17:08:09.961  1015  1219 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6333 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-30 17:08:09.961  6333  6333 E Zygote  : v2
08-30 17:08:09.961  6333  6333 I libpersona: KNOX_SDCARD checking this for 10003
08-30 17:08:09.961  6333  6333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:09.961  6333  6333 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:09.971  6333  6333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:09.971  6333  6333 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:09.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:09.991  6333  6333 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:10.001  6333  6333 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:10.021  6333  6333 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 17:08:10.061  6333  6333 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 17:08:10.061  6333  6333 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-30 17:08:10.061  6333  6333 D UserAnalysis: Create SecureDbHelper
,08-30 17:08:10.071  6333  6333 D IntelligenceServiceApplication: onCreate()
,08-30 17:08:10.081  1015  1470 I ActivityManager: Killing 5350:com.google.android.talk/u0a104 (adj 15): empty #31
,08-30 17:08:10.081  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-30 17:08:10.081  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.081  6333  6333 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 17:08:10.081  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:10.081  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:10.081  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:10.101  6351  6351 E Zygote  : MountEmulatedStorage()
08-30 17:08:10.101  6351  6351 E Zygote  : v2
08-30 17:08:10.101  6351  6351 I libpersona: KNOX_SDCARD checking this for 10107
08-30 17:08:10.101  6351  6351 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:10.101  6351  6351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:10.101  1015  1475 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6351 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,08-30 17:08:10.101  6351  6351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:10.101  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 17:08:10.101  6351  6351 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:10.101  6333  6333 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.,
,08-30 17:08:10.101  2649  2798 W bt-l2cap: btif_mce_execute_service enable:0
08-30 17:08:10.101  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:10.101  2649  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:10.111  2649  2798 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:10.111  2649  2798 W bt-btif : ag scb idx 2 not allocated
08-30 17:08:10.111  2649  2798 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:08:10.111  2649  2857 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:10.111  2649  2857 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:10.111  2649  2733 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:10.111  2649  2801 I bt_vendor: hw_epilog_process
,08-30 17:08:10.111  2649  2733 D bt_userial_mct: userial_close
08-30 17:08:10.111  2649  2733 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 17:08:10.111  6333  6333 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 17:08:10.131  6351  6351 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:10.131  6351  6351 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:10.261  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:08:10.261  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:10.261   277   951 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:10.271  1924  4595 V NativeCrypto: Read error: ssl=0xb934fe68: I/O error during system call, Connection timed out
,08-30 17:08:10.281  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:08:10.281  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:10.281  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.281  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.281  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.281  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.281  1924  6317 I qtaguid : Untagging socket 81
,08-30 17:08:10.281  1924  4595 V NativeCrypto: SSL shutdown failed: ssl=0xb934fe68: I/O error during system call, Broken pipe
,08-30 17:08:10.281  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:10.281  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:10.281  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3,
,08-30 17:08:10.281  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:10.281  1015  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-30 17:08:10.281  1924  4595 E GCM     : Wifi connection closed with errorCode 20
08-30 17:08:10.281  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:10.281  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.291  6192  6192 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-30 17:08:10.291  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:10.291  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:10.291  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 17:08:10.291  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:10.291  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>,
08-30 17:08:10.291  1015  2209 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:10.291  1015  2209 I qtaguid : Tagging socket 357 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,08-30 17:08:10.291  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:10.301  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:10.301  1015  2209 I qtaguid : Untagging socket 357
08-30 17:08:10.301  1015  2209 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.311  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.311  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:10.311  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.311  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
,08-30 17:08:10.311  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-30 17:08:10.311  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-30 17:08:10.311  1015  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 17:08:10.311  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.311  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.311  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.311  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:10.311  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-30 17:08:10.311  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:10.311  1015  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:10.321  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:10.321  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:10.321  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:08:10.321  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:10.321  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:10.321  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:08:10.331   277   947 D EnterpriseController: uids 1000
08-30 17:08:10.331   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:10.331   277   947 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-30 17:08:10.331  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 17:08:10.331  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:10.331  1015  1045 D WifiDisplayController: disconnect
08-30 17:08:10.331  1015  1045 D WifiDisplayController: updateConnection
08-30 17:08:10.331  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:10.331  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:10.331  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 17:08:10.331  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 17:08:10.331  1015  1125 D WifiP2pService: P2pDisablingState
08-30 17:08:10.331  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 17:08:10.331  1015  1125 D WifiP2pService: p2p socket connection lost
,08-30 17:08:10.331  1015  1125 D WifiP2pService: P2pDisabledState
,08-30 17:08:10.331  1015  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 17:08:10.331  1015  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-30 17:08:10.331  1015  1130 E WifiNative-wlan0: do suspend true
,08-30 17:08:10.331  1177  1696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:08:10.331  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:10.331  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:10.331  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:10.331  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:10.331  1015  2209 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:10.331  1015  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:10.331  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:08:10.331  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:10.331  1015  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 17:08:10.331  1015  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 17:08:10.331  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:10.331  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 17:08:10.331  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
08-30 17:08:10.331  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 17:08:10.331  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 17:08:10.341  1924  6317 I qtaguid : Untagging socket 54
,08-30 17:08:10.341   277   951 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:10.341  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:10.341  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:10.341  2098  2098 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:10.341  2649  2733 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:10.341  2649  2733 I bt_vendor: bluetooth satus is on
08-30 17:08:10.341  2649  2733 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:10.341  2649  2733 I bt_vendor: Starting hciattach daemon
08-30 17:08:10.341  2649  2733 I bt_vendor: try to set false
,08-30 17:08:10.341  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.351  2649  2733 I bt_vendor: Starting hciattach daemon
08-30 17:08:10.351  2649  2733 I bt_vendor: try to set false
08-30 17:08:10.351  2649  2733 I bt_vendor: cleanup
08-30 17:08:10.351  2649  2798 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:10.351  2649  2733 I GKI_LINUX: GKI_exit_task 0 done
08-30 17:08:10.351  2649  2733 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-30 17:08:10.351  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:10.351  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
08-30 17:08:10.351  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 17:08:10.351  1924  6317 I qtaguid : Untagging socket 54
,08-30 17:08:10.361  1015  1219 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:10.361  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.361  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:10.361  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 17:08:10.361  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
08-30 17:08:10.361  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.361  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:10.361  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.361  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.361  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.361  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.361  1924  6317 I qtaguid : Untagging socket 54
08-30 17:08:10.361  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:10.361  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:10.361  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:10.361  1924  6317 I qtaguid : Untagging socket 54
08-30 17:08:10.361  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.361  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:10.361  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:10.361  1924  6317 I qtaguid : Untagging socket 54
,08-30 17:08:10.361  1924  6317 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 17:08:10.361  1924  6317 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-30 17:08:10.361  1924  6317 I qtaguid : Tagging socket 54 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1924, getuid(): 10012
,08-30 17:08:10.361  1924  6317 I qtaguid : Untagging socket 54
,08-30 17:08:10.371  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.371  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:10.371  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.371  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.371  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.371  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:10.371  1015  1132 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 17:08:10.371  1015  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 17:08:10.371  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 17:08:10.371  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:10.371  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:10.371  1015  1132 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:10.371  1015  1133 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:08:10.371  1015  1123 V NetworkStats: updateIfacesLocked()
08-30 17:08:10.371  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.371  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:10.371  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-30 17:08:10.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:10.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:10.381  2649  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 17:08:10.381  2649  2730 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:10.381  1015  1123 V NetworkStats: performPollLocked() took 4ms
08-30 17:08:10.381  2649  2730 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:08:10.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.381  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 17:08:10.381  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:08:10.381  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:10.381  1015  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 17:08:10.381  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.381  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-30 17:08:10.381  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:10.381  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:10.381  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:10.381  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 17:08:10.381  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:10.381  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 17:08:10.381  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:10.381  1015  1130 D SecContentProvider2: mCursor = null
08-30 17:08:10.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.391  1924  1924 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-30 17:08:10.391  1924  1924 E ctxmgr  : com.android.volley.NoConnectionError: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:151)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at iss.performRequest(:com.google.android.gms:64)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.volley.NetworkDispatcher.run(:com.google.android.gms:113)
08-30 17:08:10.391  1924  1924 E ctxmgr  : Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at java.net.Socket.connect(Socket.java:882)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.google.android.gms.http.GoogleHtt,pClient.a(:com.google.android.gms:943)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.volley.toolbox.HttpClientStack.performRequest(:com.google.android.gms:87)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at isr.performRequest(:com.google.android.gms:63)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:96)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	... 2 more
08-30 17:08:10.391  1924  1924 E ctxmgr  : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at libcore.io.Posix.connect(Native Method)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-30 17:08:10.391  1924  1924 E ctxmgr  : 	... 21 more
08-30 17:08:10.391  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 17:08:10.391  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.391  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.391  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.391  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:08:10.391  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:10.391  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 17:08:10.391  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 17:08:10.391  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:10.391  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 17:08:10.391  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 17:08:10.401  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.401  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:10.401  1177  1177 D, StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.401  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.401  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.401  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.401  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 17:08:10.401  2649  2649 D BtGatt.GattService: stop()
08-30 17:08:10.401  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 17:08:10.401  1924  2136 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
08-30 17:08:10.401  2098  2098 I wpa_supplicant: Blacklist: Clear (all) 
08-30 17:08:10.411  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.411  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:10.411  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.411  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.411  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.411  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.411  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.411  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.411  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 17:08:10.411  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:10.411  1177  1177 D HotspotTile: onReceive : 0, 0
08-30 17:08:10.421  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.421  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.421  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.421  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.421  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 17:08:10.421  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:10.421  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:10.421  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.421  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.421  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.421  1015  3085 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-30 17:08:10.421  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-30 17:08:10.421  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
08-30 17:08:10.421  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:10.421  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.421  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:10.421  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 17:08:10.421  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:10.421  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:10.421  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.421  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-30 17:08:10.431  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 17:08:10.431  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:10.431  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:10.431  1924  1924 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-30 17:08:10.431  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:10.431  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:10.431  1015  3082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.431  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:08:10.431  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.431  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.431  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.441  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 17:08:10.441  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:10.441  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 17:08:10.441  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.441  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 17:08:10.441  2649  2649 D HeadsetService: Received stop request...Stopping profile...
08-30 17:08:10.441  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.441  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.441  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.441  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:10.441  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:10.441  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 17:08:10.441  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.441  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-30 17:08:10.441  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
08-30 17:08:10.441  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.441  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.441  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.451  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:08:10.451  1318  1318 D HeadsetProfile: Bluetooth service disconnected
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=263 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=255 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=207 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=205 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=199 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.461  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.k.c(PG:583)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  6351  6351 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:10.451  6351  6351 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 17:08:10.451  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:10.461  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.451  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:10.461  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:08:10.451  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-30 17:08:10.461  2098  2098 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-30 17:08:10.461  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:10.461  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-30 17:08:10.471  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.471  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.471  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.471  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.471  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:10.471  1015  1216 I ActivityManager: Killing 5053:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-30 17:08:10.471  2649  2730 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.481  1015  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.481  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-30 17:08:10.481  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:10.481  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.481  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.481  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.481  2098  2098 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 17:08:10.481  2098  2098 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:08:10.481  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.481  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.481  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:10.481  2098  2098 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 17:08:10.481  2098  2098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:10.481  2098  2098 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 17:08:10.481  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:10.481  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:10.481  1015  1133 D Tethering: InitialState.processMessage what=4
08-30 17:08:10.481  2649  2730 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 17:08:10.481  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.481  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.481  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:10.481  1015  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-30 17:08:10.481  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.481  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.491  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:10.491  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 17:08:10.491  1015  1133 E Tethering: No numeric data
08-30 17:08:10.491  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:10.491  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 17:08:10.491  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.491  1015  1470 W ActivityManager: NORMAL SET : dst_,category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.491  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:10.491  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:10.491  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:10.491  2649  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:10.491  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:10.491  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:10.501  2649  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:10.501  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:10.501  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:10.501  2649  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:10.501  2649  2730 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:10.501  2649  2730 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:10.501  2649  2730 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:10.501  2649  2730 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 17:08:10.501  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-30 17:08:10.501  2649  2649 D A2dpService: Received stop request...Stopping profile...
08-30 17:08:10.501  2649  2742 D A2dpStateMachine: Exit Disconnected: -1
08-30 17:08:10.501  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:10.501  1015  1133 D Tethering: clearTetheredNotification()
08-30 17:08:10.501  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.501  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:10.501  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:10.501  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:10.501  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 17:08:10.501  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:10.501  1015  1123 V NetworkStats: performPollLocked() took 3ms
08-30 17:08:10.501  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.511  1015  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:10.511  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.511  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.511  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:10.511  6351  6375 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 17:08:10.521  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:10.521  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5,
08-30 17:08:10.521  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:10.521  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:10.521  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:10.521  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:10.521  3640  3640 I Hs20UtilService: Starting #8
08-30 17:08:10.521  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:10.521  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:10.521  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:10.521  2912  2912 D BluetoothA2dp: Proxy object disconnected
,08-30 17:08:10.531  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:10.531  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-30 17:08:10.531  1318  1318 D BluetoothA2dp: Proxy object disconnected
,08-30 17:08:10.531  2649  2649 D HidService: Received stop request...Stopping profile...
08-30 17:08:10.531  2649  2649 D HidService: Stopping Bluetooth HidService
08-30 17:08:10.531  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:10.531  1318  1318 D A2dpProfile: Bluetooth service disconnected
,08-30 17:08:10.531  2649  2649 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 17:08:10.531  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:10.531  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:10.531  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-30 17:08:10.531  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:10.541  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:10.541   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb744a7c8
08-30 17:08:10.541   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-30 17:08:10.541   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 17:08:10.541   272   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220237176)
,08-30 17:08:10.551  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true,
,08-30 17:08:10.551  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:10.551  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:08:10.551  2649  2649 D HealthService: Received stop request...Stopping profile...
08-30 17:08:10.551  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:10.561  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:10.561  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:10.561  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:10.561  1318  1318 D BluetoothInputDevice: Proxy object disconnected
08-30 17:08:10.561  1318  1318 D HidProfile: Bluetooth service disconnected
08-30 17:08:10.561  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:10.591   272   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-30 17:08:10.591   272   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 17:08:10.591   272   353 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220237176) wakelock released: 1, error no: 0
08-30 17:08:10.591   272   353 I rmt_storage: 
08-30 17:08:10.591   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb744a7c8
,08-30 17:08:10.671  2098  2098 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:10.701  1015  1475 I art     : Explicit concurrent mark sweep GC freed 48189(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 28MB/42MB, paused 2.431ms total 167.793ms,
,08-30 17:08:10.701  1015  1475 W ActivityManager: userId = 0, bbcId = -10000,
,08-30 17:08:10.701  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 17:08:10.701  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.701  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms,
,08-30 17:08:10.711  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 17:08:10.711  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:08:10.711  2649  2649 D PanService: Received stop request...Stopping profile...
08-30 17:08:10.711  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:10.721  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:10.721  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.721  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-30 17:08:10.721  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-30 17:08:10.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:10.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:10.741  6386  6386 E Zygote  : MountEmulatedStorage()
08-30 17:08:10.741  6386  6386 I libpersona: KNOX_SDCARD checking this for 10104
08-30 17:08:10.741  6386  6386 E Zygote  : v2
08-30 17:08:10.741  6386  6386 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:10.741  6386  6386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:10.741  1015  1219 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6386 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-30 17:08:10.741  6386  6386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:10.741  6386  6386 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:10.741  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:10.741  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
08-30 17:08:10.741  1318  1318 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:10.741  1318  1318 D PanProfile: Bluetooth service disconnected
,08-30 17:08:10.741  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:10.751  2649  2649 D SapService: Received stop request...Stopping profile...
08-30 17:08:10.751  2649  2649 D SapService: Stopping Bluetooth SapService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@11bc2af5
,08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-30 17:08:10.751  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:08:10.751  2649  2649 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 17:08:10.751  2649  2743 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:08:10.751  2649  2649 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:08:10.751  2649  2649 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:08:10.751  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 17:08:10.751  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:10.751  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-30 17:08:10.751  1318  1318 D BluetoothMap: Proxy object disconnected
08-30 17:08:10.751  1318  1318 D MapProfile: Bluetooth service disconnected
08-30 17:08:10.751  1318  1318 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 17:08:10.751  1318  1318 D SapProfile: Bluetooth service disconnected
,08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:08:10.751  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:10.751  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:10.751  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 17:08:10.751  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:10.751  2649  2649 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 17:08:10.751  2649  2649 E BluetoothAdapterService(297544437): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-30 17:08:10.751  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:08:10.751  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 17:08:10.761  2649  2730 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-30 17:08:10.761  2649  2730 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:10.761  2649  2730 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:10.761  2649  2730 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:10.761  2649  2730 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:08:10.761  2649  2730 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:10.761  2649  2730 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:08:10.761  2649  2730 I BluetoothAdapterState: Entering OffState
,08-30 17:08:10.761  6386  6386 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:10.761  6386  6386 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:10.781  1924  2136 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-30 17:08:10.781  1924  2136 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-30 17:08:10.781  1318  1336 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 17:08:10.781  6386  6386 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 17:08:10.781  1318  1339 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:10.801  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:10.801  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:10.801  2912  2922 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:10.801  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.811  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.811  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.811  1177  1862 D BluetoothAdapter: onBluetoothStateChange: up=false,
,08-30 17:08:10.811  1177  1862 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:10.811  1440  1461 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.811  1440  1461 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:10.811  6351  6361 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.811  6351  6361 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.811  1924  2112 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.811  1924  2112 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.811  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.821  1318  1336 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 17:08:10.821  1318  1336 D Bluetoothsap: Unbinding service...
08-30 17:08:10.821  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.821  2649  2868 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.821  2649  2868 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:10.821  1318  1339 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 17:08:10.821  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.821  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.821  2098  2098 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-30 17:08:10.821  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:08:10.821  2649  2740 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 17:08:10.831  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.831  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:10.831  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:10.831  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.831  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.831  1318  1336 D BluetoothMap: onBluetoothStateChange: up=false
08-30 17:08:10.831  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.831  2912  2926 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.831  2912  2926 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.831  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.831  1429  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.831  1429  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.831  1318  1339 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.831  1318  1339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:10.831  6192  6201 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.831  6192  6201 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.831  6192  6201 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:08:10.831  6192  6201 D BluetoothLeAdvertiser: Exit stop advertising
08-30 17:08:10.831  6192  6201 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false,
,08-30 17:08:10.831  6192  6201 D BluetoothLeScanner: Exiting stopAllScan
08-30 17:08:10.831  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.831  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.831  1453  1682 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:10.831  1453  1682 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:10.831  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.831  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.841  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-30 17:08:10.841  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-30 17:08:10.841  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-30 17:08:10.841  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-30 17:08:10.841  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=2649, ws=null) (elapsedTime=1416)
08-30 17:08:10.841  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=471)
08-30 17:08:10.841  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.841  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.841  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-30 17:08:10.841  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.841  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.841  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.841  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.851  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.851  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:10.851  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:08:10.851  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-30 17:08:10.851  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.851  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.851  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.851  2649  2733 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 17:08:10.851  2649  2649 I GKI_LINUX: GKI_exit_task 1 done
,08-30 17:08:10.851  2649  2649 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-30 17:08:10.851  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:08:10.851  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 17:08:10.851  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 17:08:10.851  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:10.851  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:10.851  1177  1719 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:10.851  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:10.851  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-30 17:08:10.851  1177  1719 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:10.851  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:10.851  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:10.861  1015  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:10.861  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.861  1828  1828 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 17:08:10.861  1015  1560 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:10.861  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:10.861  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 17:08:10.861  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:10.861  1924  2124 D BluetoothAdapter: 743929551: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:10.861  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-30 17:08:10.861  1924  2124 D BluetoothAdapter: 743929551: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:10.861  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-30 17:08:10.861  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 17:08:10.861  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:10.861  2649  2649 I art     : System.exit called, status: 0
08-30 17:08:10.861  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:08:10.861  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:10.861  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:10.861  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:10.861  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.871  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:10.881  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:10.881  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-30 17:08:10.891  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:10.891  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.901  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.901  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-30 17:08:10.911  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-30 17:08:10.931  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 17:08:10.931  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:10.931  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:08:10.931  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:10.931  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:10.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:10.931  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:10.931  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 17:08:10.931  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:10.931  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:10.931  1177  1177 D HotspotTile: onReceive : 1, 0
,08-30 17:08:10.941  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:10.941  1924  2124 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:10.941  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.941  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:10.941  1015  1216 I ActivityManager: Process com.android.bluetooth (pid 2649)(adj 0) has died(46,1087)
,08-30 17:08:10.961   287   287 E SMD     : DCD OFF
,08-30 17:08:10.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:11.001  6386  6430 I Babel   : MmsConfig: mnc/mcc: 0/0
08-30 17:08:11.001  6386  6430 I Babel   : MmsConfig.loadMmsSettings
08-30 17:08:11.001  6386  6430 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-30 17:08:11.001  6386  6430 I Babel   : MmsConfig.loadFromDatabase
,08-30 17:08:11.021  6386  6430 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-30 17:08:11.021  6386  6430 I Babel   : MmsConfig.loadFromResources
,08-30 17:08:11.021  1015  3083 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-30 17:08:11.021  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 17:08:11.021  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.021  1015  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:11.021  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:11.021  6386  6430 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 17:08:11.021  6386  6430 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-30 17:08:11.021  6386  6386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:11.071  6386  6386 I Babel_StickerModule: App launched.
,08-30 17:08:11.071  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:08:11.071  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:11.081  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:11.081  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:11.081  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:11.081  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:11.081  1015  3085 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
08-30 17:08:11.081  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:11.081  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.081  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.081  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.081  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.091  6432  6432 E Zygote  : MountEmulatedStorage(),
08-30 17:08:11.091  6432  6432 I libpersona: KNOX_SDCARD checking this for 10068
08-30 17:08:11.091  6432  6432 E Zygote  : v2
08-30 17:08:11.091  6432  6432 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:11.091  6432  6432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:11.101  6432  6432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:11.101  1015  3085 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6432 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:11.101  6432  6432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.101   282   726 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-30 17:08:11.101   282   726 W QCamera2Factory: getCameraInfo: X
,08-30 17:08:11.101   282   695 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-30 17:08:11.101   282   695 W QCamera2Factory: getCameraInfo: X
,08-30 17:08:11.121  6386  6386 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 17:08:11.121  6386  6386 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:08:11.121  6432  6432 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.121  6432  6432 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.131  6386  6386 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 17:08:11.131  6386  6386 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 17:08:11.141  6386  6386 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 17:08:11.141  6432  6432 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 17:08:11.151  6386  6386 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 17:08:11.151  6386  6386 W AudioCapabilities: Unsupported mime audio/x-ima
,08-30 17:08:11.151  6386  6386 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 17:08:11.151  6386  6386 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 17:08:11.161  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:11.161  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:08:11.181  6386  6386 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:08:11.181  6386  6386 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:08:11.201  6386  6386 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 17:08:11.201  6386  6386 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 17:08:11.201  6386  6386 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 17:08:11.201  6432  6432 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:11.211  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 17:08:11.211  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.211  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.211  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.211  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.211  6386  6386 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 17:08:11.211  6386  6386 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 17:08:11.211  6386  6386 W VideoCapabilities: Unsupported mime video/mp43
,08-30 17:08:11.221  6386  6386 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 17:08:11.221  1015  1216 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6447 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:11.221  1015  1216 I ActivityManager: Killing 5482:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-30 17:08:11.231  6386  6386 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 17:08:11.231  6447  6447 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.231  6447  6447 E Zygote  : v2
08-30 17:08:11.231  6447  6447 I libpersona: KNOX_SDCARD checking this for 10069
08-30 17:08:11.231  6447  6447 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.231  6447  6447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:11.231  6447  6447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:11.231  6447  6447 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.241  1015  2748 D SSRM:n  : SIOP:: AP = 350
,08-30 17:08:11.251  6447  6447 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.251  6447  6447 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.261  6386  6386 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 17:08:11.281  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:11.291  1015  5585 I ActivityManager: Killing 5570:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-30 17:08:11.291  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-30 17:08:11.291  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-30 17:08:11.291  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:11.291  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:11.291  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 17:08:11.301  1015  3083 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:11.301  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:11.301  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.301  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:11.301  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:11.301  3640  3640 I Hs20UtilService: Starting #9
,08-30 17:08:11.301  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:11.301  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:11.301  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:11.301  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:11.311  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:11.311  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:11.311  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:11.311  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:11.311  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.311  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.311  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.321  1015  1216 I ActivityManager: Killing 5775:com.sec.pcw.device/1000 (adj 15): empty #31
,08-30 17:08:11.351  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:11.351  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:11.351  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.351  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.361  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:11.361  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-30 17:08:11.361  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.361  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.361  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.361  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.361  3640  3640 I Hs20UtilService: Starting #10
,08-30 17:08:11.361  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:11.371  6464  6464 E Zygote  : MountEmulatedStorage()
08-30 17:08:11.371  6464  6464 E Zygote  : v2
08-30 17:08:11.371  6464  6464 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:11.371  6464  6464 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.371  6464  6464 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:11.371  6464  6464 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 17:08:11.381  1015  1219 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6464 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-30 17:08:11.381  6464  6464 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:11.401  6464  6464 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.401  6464  6464 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.421  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:11.431  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:11.431  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:11.431  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:11.431  1015  1213 I ActivityManager: Killing 5501:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-30 17:08:11.441  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.441  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.441  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.441  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:11.441  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.441  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.441  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.441  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.441  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.451  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.451  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:11.451  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.461  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.461  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.461  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.461  1015  1042 D Tethering: interfaceRemoved wlan0
08-30 17:08:11.461  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:08:11.461  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.461  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.461  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.471  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.471  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.471  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.471  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.481  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.481  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.481  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.481  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.481  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:11.481  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.491  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.491  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:11.491  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.491  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:11.491  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.491  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.501  1015  1219 I ActivityManager: Killing 5114:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-30 17:08:11.501  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:11.501  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.501  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 17:08:11.511  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:11.511  1015  3083 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:11.511  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:11.511  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:11.511  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:11.511  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:11.521  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:11.521  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:11.521  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:11.521  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:08:11.531  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 17:08:11.531  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.531  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.531  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.531  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.541  1015  1219 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6481 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-30 17:08:11.551  6481  6481 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.551  6481  6481 E Zygote  : v2
08-30 17:08:11.551  6481  6481 I libpersona: KNOX_SDCARD checking this for 1002
08-30 17:08:11.551  6481  6481 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.551  6481  6481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:11.551  6481  6481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 17:08:11.561  6481  6481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.581  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.581  6481  6481 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.591  6481  6481 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:08:11.591  6481  6481 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:11.621  6481  6481 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 17:08:11.641  1015  1042 D Tethering: interfaceRemoved p2p0
,08-30 17:08:11.641  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding GattService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding HeadsetService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding HidService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding HealthService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding PanService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding SapService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding SapClientService
,08-30 17:08:11.661  6481  6481 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 17:08:11.671  6481  6481 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 17:08:11.671  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 17:08:11.671  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.671  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.671  1015  1027 D SettingsProvider: selectionArgs: false
08-30 17:08:11.671  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:11.671  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.671  1015  1027 D SettingsProvider: ret = -1
,08-30 17:08:11.671  1015  3083 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:11.671  1015  3083 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.671  1015  3083 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.671  1015  3083 D SettingsProvider: selectionArgs: false
08-30 17:08:11.671  1015  3083 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:11.671  1015  3083 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.671  1015  3083 D SettingsProvider: ret = -1
,08-30 17:08:11.671  1015  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
08-30 17:08:11.671  1015  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.671  1015  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.671  1015  1560 D SettingsProvider: selectionArgs: false,
08-30 17:08:11.671  1015  1560 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.671  1015  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.671  1015  1560 D SettingsProvider: ret = -1
,08-30 17:08:11.671  1015  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 17:08:11.671  1015  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:11.671  1015  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:11.671  1015  1219 D SettingsProvider: selectionArgs: false
08-30 17:08:11.671  1015  1219 D SettingsProvider: selectionArgs: 1002,
,08-30 17:08:11.671  1015  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.671  1015  1219 D SettingsProvider: ret = -1
,08-30 17:08:11.671  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 17:08:11.671  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.671  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.671  1015  1475 D SettingsProvider: selectionArgs: false
08-30 17:08:11.671  1015  1475 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  1475 D SettingsProvider: ret = -1
,08-30 17:08:11.681  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 17:08:11.681  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  1028 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  1028 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  1028 D SettingsProvider: ret = -1
08-30 17:08:11.681  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:11.681  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  1213 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  1213 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  1213 D SettingsProvider: ret = -1
08-30 17:08:11.681  1015  5585 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
08-30 17:08:11.681  1015  5585 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  5585 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  5585 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  5585 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  5585 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  5585 D SettingsProvider: ret = -1
,08-30 17:08:11.681  1015  3085 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:11.681  1015  3085 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  3085 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  3085 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  3085 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  3085 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:11.681  1015  3085 D SettingsProvider: ret = -1
08-30 17:08:11.681  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:11.681  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  1476 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  1476 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  1476 D SettingsProvider: ret = -1
08-30 17:08:11.681  1015  3082 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:11.681  1015  3082 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  3082 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:11.681  1015  3082 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  3082 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  3082 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  3082 D SettingsProvider: ret = -1
08-30 17:08:11.681  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 17:08:11.681  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:11.681  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:11.681  1015  1216 D SettingsProvider: selectionArgs: false
08-30 17:08:11.681  1015  1216 D SettingsProvider: selectionArgs: 1002
08-30 17:08:11.681  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:11.681  1015  1216 D SettingsProvider: ret = -1
08-30 17:08:11.691  1015  1560 I ActivityManager: Killing 4103:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-30 17:08:11.691  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:11.691  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:11.691  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:11.701  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.701  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:11.701  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:11.711  1924  6497 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:11.711  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:11.711  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:11.711  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:11.711  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:11.711  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:11.721  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 17:08:11.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.721  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.731  6498  6498 E Zygote  : MountEmulatedStorage(),
08-30 17:08:11.731  6498  6498 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:11.731  6498  6498 E Zygote  : v2
08-30 17:08:11.731  6498  6498 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.731  6498  6498 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:11.741  6498  6498 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 17:08:11.741  1015  1219 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 17:08:11.741  6498  6498 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:11.741  1015  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,08-30 17:08:11.751  1015  1560 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:11.751  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:11.751  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:11.751  1924  6497 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 17:08:11.761  6498  6498 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.761  6498  6498 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.781  6498  6498 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 17:08:11.781  6498  6498 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 17:08:11.781  6498  6498 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 17:08:11.791  6498  6498 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 17:08:11.791  6498  6498 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:08:11.791  6498  6498 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-30 17:08:11.791  6498  6498 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:11.791  1015  3082 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-30 17:08:11.791  6498  6513 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
08-30 17:08:11.791  1015  3082 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-30 17:08:11.791  1015  3082 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-30 17:08:11.801  1015  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 17:08:11.801  1015  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.801  1015  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.801  1015  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.811  6515  6515 E Zygote  : MountEmulatedStorage()
,08-30 17:08:11.811  6515  6515 E Zygote  : v2
08-30 17:08:11.811  6515  6515 I libpersona: KNOX_SDCARD checking this for 10111
08-30 17:08:11.811  6515  6515 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.811  6515  6515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:11.811  1015  3082 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6515 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:11.811  6515  6515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:11.811  6515  6515 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 17:08:11.821  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 17:08:11.821  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.821  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.821  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.821  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.831  6525  6525 E Zygote  : MountEmulatedStorage(),
08-30 17:08:11.831  6525  6525 E Zygote  : v2
08-30 17:08:11.831  6525  6525 I libpersona: KNOX_SDCARD checking this for 10009
,08-30 17:08:11.831  6525  6525 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:11.831  6525  6525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:11.841  1015  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6525 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:11.841  6525  6525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 17:08:11.841  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-30 17:08:11.841  1726  1726 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:11.841  6525  6525 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 17:08:11.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.841  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.841  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.841  6515  6515 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.851   304   304 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 20.097ms,
,08-30 17:08:11.861  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.861  6525  6525 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.871   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 17.002ms
,08-30 17:08:11.891   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 16.864ms
,08-30 17:08:11.901  6545  6545 E Zygote  : MountEmulatedStorage(),
08-30 17:08:11.901  6545  6545 E Zygote  : v2
08-30 17:08:11.901  6545  6545 I libpersona: KNOX_SDCARD checking this for 10145
08-30 17:08:11.901  6545  6545 I libpersona: KNOX_SDCARD not a persona,
08-30 17:08:11.901  1015  1040 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6545 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-30 17:08:11.901  6545  6545 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:11.901  6545  6545 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:11.901  6545  6545 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.921  1726  1726 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-30 17:08:11.921  1726  1726 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-30 17:08:11.921  1726  1726 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-30 17:08:11.921  1726  1726 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:11.921  1726  1726 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 17:08:11.931  6545  6545 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:11.931  6545  6545 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:11.931  1726  1726 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-30 17:08:11.931  1300  1311 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
08-30 17:08:11.931  1015  1213 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 17:08:11.931  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.931  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.931  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:11.931  1015  1213 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:11.941  6560  6560 E Zygote  : MountEmulatedStorage(),
08-30 17:08:11.941  6560  6560 E Zygote  : v2
08-30 17:08:11.941  6560  6560 I libpersona: KNOX_SDCARD checking this for 10081
08-30 17:08:11.941  6560  6560 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:11.941  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:11.951  1015  1213 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6560 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:11.951  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:11.951  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-30 17:08:11.961  1726  1726 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-30 17:08:11.971  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:11.971  6560  6560 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:11.981  6545  6545 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 17:08:11.981  6545  6545 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:11.981  6545  6545 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 17:08:11.981  6545  6545 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:11.981  6545  6545 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 17:08:11.981   312   312 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 17:08:12.001  1015  1560 I ActivityManager: Killing 5818:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-30 17:08:12.011  6515  6515 I MusicStore: Database version: 108
,08-30 17:08:12.011  3677  3677 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:08:12 GMT+02:00 2016
,08-30 17:08:12.011  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-30 17:08:12.011  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.011  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:12.011  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:12.011  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:08:12.011  3677  3677 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:08:12.021  3677  3677 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-30 17:08:12.021  3677  3677 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:08:12.021  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 17:08:12.031  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.031  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.031  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.031  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.041  3677  3677 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:08:12.041  6582  6582 E Zygote  : MountEmulatedStorage(),
08-30 17:08:12.041  6582  6582 E Zygote  : v2
08-30 17:08:12.041  6582  6582 I libpersona: KNOX_SDCARD checking this for 10034,
08-30 17:08:12.041  6582  6582 I libpersona: KNOX_SDCARD not a persona,
08-30 17:08:12.041  6582  6582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:12.041  1015  1027 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6582 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
08-30 17:08:12.041  1015  3085 D RCPManagerService: exchangeData() failure , invalid userId
08-30 17:08:12.041  1015  1216 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 17:08:12.041  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0,
08-30 17:08:12.051  6582  6582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:12.051  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.051  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.051  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.051  6582  6582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:12.051  3677  6580 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-30 17:08:12.051  3677  6580 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-30 17:08:12.051  3677  6580 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 17:08:12.061  3677  6580 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-30 17:08:12.061  1015  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.061  3677  3677 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-30 17:08:12.071  6582  6582 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.071  6582  6582 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.101  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 17:08:12.101  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.101  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.101  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.101  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.111  6602  6602 E Zygote  : MountEmulatedStorage()
08-30 17:08:12.111  6602  6602 E Zygote  : v2
08-30 17:08:12.111  6602  6602 I libpersona: KNOX_SDCARD checking this for 10113
08-30 17:08:12.111  6602  6602 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:12.111  6602  6602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:12.121  6602  6602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:12.121  1015  1216 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6602 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:12.121  1015  1216 I ActivityManager: Killing 5807:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-30 17:08:12.121  6602  6602 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:12.131  1015  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.131  6582  6582 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 17:08:12.141  6602  6602 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.141  6602  6602 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.151  6515  6515 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 17:08:12.151  6515  6515 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 17:08:12.161  1015  1213 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.161  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 17:08:12.161  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.161  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.161  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.161  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.171  3241  6619 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 17:08:12.171  3241  6619 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-30 17:08:12.181  6620  6620 E Zygote  : MountEmulatedStorage()
08-30 17:08:12.181  6620  6620 E Zygote  : v2
08-30 17:08:12.181  6620  6620 I libpersona: KNOX_SDCARD checking this for 10035
08-30 17:08:12.181  6620  6620 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:12.181  3241  6619 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-30 17:08:12.181  6620  6620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:12.181  3241  6619 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-30 17:08:12.181  1015  1219 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6620 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:12.181  3241  6619 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-30 17:08:12.181  6620  6620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 17:08:12.191  6620  6620 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-30 17:08:12.201  6515  6515 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 17:08:12.221  6620  6620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.221  6620  6620 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.241  5934  5942 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 17:08:12.251  1015  1475 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.261  6515  6515 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 17:08:12.261  6515  6515 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31d191f9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 17:08:12.261  6515  6515 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 17:08:12.261  6515  6515 D AndroidMusic: GMSCore installation verified
,08-30 17:08:12.271  5934  5943 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-30 17:08:12.271  5934  5943 D BadgeProvider: sendNotify, [notify] : null
08-30 17:08:12.271  5934  5943 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 17:08:12.271  5934  5943 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 17:08:12.271  5934  5943 D BadgeProvider: update, [UpdateCount] : 1
,08-30 17:08:12.271  1478  1478 D Launcher.Model: reloadBadges entered.
,08-30 17:08:12.271  1015  1216 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.281  6620  6638 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-30 17:08:12.281  6620  6638 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-30 17:08:12.291  6620  6620 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-30 17:08:12.291  1015  3082 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-30 17:08:12.301  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.301  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.301  1015  3082 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 17:08:12.301  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-30 17:08:12.301  6023  6023 I SA      : [DM] init START
,08-30 17:08:12.301  6620  6638 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:12.301  6620  6638 D SPPClientService: PushLog.txt file is not deleted.
08-30 17:08:12.301  6620  6638 D SPPClientService: ============PushLog. stop!
08-30 17:08:12.301  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.301  1015  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:12.301  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-30 17:08:12.311  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.311  1015  1475 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 17:08:12.311  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.311  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.311  6023  6023 I SA      : [DM] This device is not a Vodafone
,08-30 17:08:12.311  6620  6642 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-30 17:08:12.321  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:12.321  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:12.321  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:12.321  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:12.321  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-30 17:08:12.321  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.321  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.321  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.321  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.341  1015  1219 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6645 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-30 17:08:12.351  6645  6645 E Zygote  : MountEmulatedStorage()
08-30 17:08:12.351  6645  6645 I libpersona: KNOX_SDCARD checking this for 10159
08-30 17:08:12.351  6645  6645 E Zygote  : v2
08-30 17:08:12.351  6645  6645 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:12.351  6645  6645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:12.351  1015  5585 I ActivityManager: Killing 5537:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-30 17:08:12.351  6515  6515 I ConfigStore: Config Database version: 1
08-30 17:08:12.351  6645  6645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:12.351  6645  6645 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-30 17:08:12.361  6023  6023 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-30 17:08:12.381  6023  6023 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-30 17:08:12.381  6645  6645 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-30 17:08:12.381  6645  6645 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-30 17:08:12.381  6023  6023 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-30 17:08:12.391  6023  6023 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-30 17:08:12.391  6023  6023 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-30 17:08:12.391  6023  6023 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-30 17:08:12.391  6023  6023 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-30 17:08:12.391  6023  6023 I SA      : [SCU] isHaveSA() - false
08-30 17:08:12.391  6023  6023 I SA      : support phone number id : false
08-30 17:08:12.391  6023  6023 I SA      : [DM] Supports Ref Jpn : true
,08-30 17:08:12.391  6023  6023 I SA      : [DM] init END
08-30 17:08:12.391  6023  6023 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-30 17:08:12.401  6023  6023 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 17:08:12.401  6023  6023 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 17:08:12.401  6023  6023 I SA      : [SLFUCHKMGR] constructor called
,08-30 17:08:12.411  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 17:08:12.421  6023  6023 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 17:08:12.421  6023  6023 I SA      : [OR] == isSIMCardReady false ==
,08-30 17:08:12.421  6023  6023 I SA      : [SCU] == networkStateCheck == false
08-30 17:08:12.421  6023  6023 I SA      : [OR] onReceive END
,08-30 17:08:12.421  1015  1470 I ActivityManager: Killing 5853:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-30 17:08:12.431  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:12.451  1015  1219 I ActivityManager: Killing 5910:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,08-30 17:08:12.461  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:12.461  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.461  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:12.461  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.461  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:12.471  3775  3775 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 17:08:12.471  3775  4562 I iu.UploadsManager: num queued entries: 0
,08-30 17:08:12.481  3775  4562 I iu.UploadsManager: num updated entries: 0
,08-30 17:08:12.481  3775  4562 I iu.SyncManager: NEXT; no task
,08-30 17:08:12.481  1015  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 17:08:12.491  1015  1027 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
08-30 17:08:12.491  1015  1027 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-30 17:08:12.491  1015  1027 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:12.491  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-30 17:08:12.491  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.491  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.491  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.491  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.501  6664  6664 E Zygote  : MountEmulatedStorage(),
,08-30 17:08:12.511  6664  6664 E Zygote  : v2
08-30 17:08:12.511  1015  1027 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6664 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-30 17:08:12.511  6664  6664 I libpersona: KNOX_SDCARD checking this for 10010
08-30 17:08:12.511  6664  6664 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:12.511  6664  6664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:12.511  6664  6664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 17:08:12.521  6664  6664 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,08-30 17:08:12.531   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 17:08:12.531   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.531  6515  6515 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 17:08:12.531   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:12.531   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.531   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 17:08:12.531  6602  6670 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
08-30 17:08:12.531   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.531  6515  6515 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 17:08:12.531   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 17:08:12.531   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.541  6515  6515 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 17:08:12.541  1015  3082 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-30 17:08:12.541  6664  6664 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:12.541  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.541  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.541  6664  6664 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.541  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.541  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.551  1015  1039 W libprocessgroup: failed to open /acct/uid_10010/pid_5910/cgroup.procs: No such file or directory
,08-30 17:08:12.561   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:12.561   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.561  6602  6670 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 17:08:12.571  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-30 17:08:12.571  1015  1028 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 17:08:12.571  1015  3082 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:12.571  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
08-30 17:08:12.571   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 17:08:12.571   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.571  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.571  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.571  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-30 17:08:12.571  6602  6684 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 17:08:12.581  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.581   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 17:08:12.581   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 17:08:12.581  6602  6684 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-30 17:08:12.581  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.601  1015  1475 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:12.611  1015  1219 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:12.611  1015  1475 I ActivityManager: Killing 5783:com.android.mms/u0a46 (adj 15): empty #31
,08-30 17:08:12.611  1015  3082 I AudioService: getStreamVolume 3 index 0
,08-30 17:08:12.621  6515  6515 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-30 17:08:12.621  6515  6515 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-30 17:08:12.641  1015  3082 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:12.641  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 17:08:12.641  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:12.641  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.651  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.651  1015  1475 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:12.651  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.651  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.651  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.651  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.651  1015  3085 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:12.661  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.661  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:12.661  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.661  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.661  1015  1470 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:12.681  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 17:08:12.681  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.681  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.681  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.681  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.691  6701  6701 E Zygote  : MountEmulatedStorage()
,08-30 17:08:12.691  6701  6701 I libpersona: KNOX_SDCARD checking this for 10002
08-30 17:08:12.691  6701  6701 E Zygote  : v2
08-30 17:08:12.691  6701  6701 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:12.691  6701  6701 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:12.691  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6701 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 17:08:12.691  6701  6701 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:12.691  6701  6701 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:12.701  1015  1560 D CountryDetector: No listener is left
,08-30 17:08:12.701  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-30 17:08:12.701  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 17:08:12.711  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:12.711  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 17:08:12.711  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 17:08:12.711  6515  6515 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-30 17:08:12.731  1015  1475 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 17:08:12.731  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 17:08:12.731  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.731  6701  6701 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.731  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.731  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:12.731  6701  6701 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.741  1015  1213 I ActivityManager: Killing 5952:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-30 17:08:12.751  1015  1213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:12.761  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:12.761  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:12.761  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 17:08:12.771  6602  6602 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-30 17:08:12.781  6602  6602 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9595-9597)
,08-30 17:08:12.781  6602  6602 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 17:08:12.791  6602  6602 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22b6ae16}
,08-30 17:08:12.791  6602  6602 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 17:08:12.791  6602  6602 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 17:08:12.801  1015  1560 I ActivityManager: Killing 5975:com.wsomacp/u0a25 (adj 15): empty #31
,08-30 17:08:12.801  1015  1560 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 17:08:12.811  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.811  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.811  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.811  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.821  6602  6602 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 17:08:12.821  6602  6602 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 17:08:12.821  6722  6722 E Zygote  : MountEmulatedStorage()
08-30 17:08:12.821  6602  6602 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:08:12.821  6722  6722 E Zygote  : v2
08-30 17:08:12.821  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000,
08-30 17:08:12.821  1015  1560 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 17:08:12.821  6722  6722 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:12.821  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:12.831  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:12.831  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:12.851  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.851  6722  6722 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:12.851  6602  6602 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 17:08:12.851  6602  6602 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-30 17:08:12.851  6602  6602 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-30 17:08:12.851  1015  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:08:12.851  1015  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:12.851  1015  1475 D SecContentProvider2: mCursor = null
,08-30 17:08:12.861  1015  1475 D WifiService: setWifiEnabled: true pid=6192, uid=10155
08-30 17:08:12.861  1015  1475 W ActivityManager: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:12.861  1015  1475 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:12.861  1015  1475 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:12.861  1015  1475 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 17:08:12.861  1015  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 17:08:12.861  1015  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:12.861  1015  1475 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:12.861  1015  1475 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:08:12.861  1015  1475 D SettingsProvider: name = wifi_on
,08-30 17:08:12.861  6602  6602 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 17:08:12.861  6602  6602 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 17:08:12.861  6602  6602 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 17:08:12.861  6602  6602 I Adreno-EGL: Local Branch: 
08-30 17:08:12.861  6602  6602 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 17:08:12.861  6602  6602 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 17:08:12.861  6602  6602 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 17:08:12.861  1015  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:08:12.911  6722  6722 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 17:08:12.921  6602  6749 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 17:08:12.921  6602  6602 I NSApplication: Starting up...
,08-30 17:08:12.941  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 17:08:12.941  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.941  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.941  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:12.941  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:12.951  6754  6754 E Zygote  : MountEmulatedStorage(),
08-30 17:08:12.951  6754  6754 E Zygote  : v2
08-30 17:08:12.951  6754  6754 I libpersona: KNOX_SDCARD checking this for 10120
08-30 17:08:12.951  6754  6754 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:08:12.951  6754  6754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:12.961  1015  1219 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6754 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,08-30 17:08:12.961  1015  1219 I ActivityManager: Killing 5838:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31,
08-30 17:08:12.961  1015  1219 I ActivityManager: Killing 5999:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
,08-30 17:08:12.961  6754  6754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:12.961  6754  6754 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-30 17:08:12.981  6754  6754 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:12.981  6754  6754 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:13.001  6754  6754 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 17:08:13.051  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 17:08:13.061  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 17:08:13.061  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:13.061  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 17:08:13.061  6722  6722 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-30 17:08:13.061  6722  6722 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 17:08:13.061  1015  1476 I ActivityManager: Killing 5869:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-30 17:08:13.251  1015  1042 D Tethering: interfaceAdded wlan0
,08-30 17:08:13.261  1015  1133 E Tethering: No numeric data
,08-30 17:08:13.261  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:13.261  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:13.261  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.261  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:13.271  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:13.271  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.271  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.271  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:13.271  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-30 17:08:13.271  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-30 17:08:13.271  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:13.271  1015  1133 D Tethering: InitialState.processMessage what=4
08-30 17:08:13.271  1015  1042 D Tethering: interfaceAdded p2p0
08-30 17:08:13.271  1015  1123 V NetworkStats: performPollLocked() took 10ms
,08-30 17:08:13.271  1015  1133 E Tethering: No numeric data
08-30 17:08:13.281  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.281  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 17:08:13.281  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 17:08:13.281  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:13.281  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:13.281  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:13.281  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:13.281   277   951 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-30 17:08:13.281  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:13.281   277   951 D SoftapController: Softap fwReload - Ok
08-30 17:08:13.281  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:13.291   277   951 D CommandListener: Setting iface cfg,
08-30 17:08:13.291   277   951 D CommandListener: Trying to bring down wlan0
08-30 17:08:13.291  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.291  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.291   277   951 D CommandListener: Clearing all IP addresses on wlan0,
,08-30 17:08:13.291  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.291  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:13.291  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:13.291  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:13.291  1015  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 17:08:13.291  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:13.291  1015  1123 V NetworkStats: performPollLocked() took 5ms
,08-30 17:08:13.301  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.301  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:13.341  6781  6781 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-30 17:08:13.341  6781  6781 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:08:13.341  6781  6781 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 17:08:13.361  6781  6781 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-30 17:08:13.361   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6781
08-30 17:08:13.361   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-30 17:08:13.361  6781  6781 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 17:08:13.361  6781  6781 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:13.361  6781  6781 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:08:13.361  6781  6781 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 17:08:13.361   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6781
,08-30 17:08:13.361   348   348 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-30 17:08:13.391  1015  1560 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 17:08:13.401  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:13.401  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:13.401  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:13.401  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:13.411  6784  6784 E Zygote  : MountEmulatedStorage(),
08-30 17:08:13.411  6784  6784 E Zygote  : v2
08-30 17:08:13.411  6784  6784 I libpersona: KNOX_SDCARD checking this for 10125,
08-30 17:08:13.411  6784  6784 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:13.411  6784  6784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:13.421  6784  6784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:13.421  6784  6784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:13.431  1015  1560 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6784 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
08-30 17:08:13.431  1015  1560 I ActivityManager: Killing 6057:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-30 17:08:13.431  1015  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 17:08:13.451   304   304 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 29.594ms
,08-30 17:08:13.461  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:13.461  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:13.461  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.461  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.461  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:13.461  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:13.461  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:13.461  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:13.461  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-30 17:08:13.471  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:13.471  1177  1177 D HotspotTile: onReceive : 2, 0
,08-30 17:08:13.471  6784  6784 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:13.471  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:13.471  6784  6784 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:13.471   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 18.640ms
08-30 17:08:13.471  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:13.481  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:13.491  6784  6784 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:13.491  6784  6784 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:08:13.491  6784  6784 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:13.491   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 19.531ms
,08-30 17:08:13.501  6784  6784 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:13.501  6784  6784 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 17:08:13.511  6784  6784 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 17:08:13.511  1015  5585 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-30 17:08:13.511  1015  5585 I ActivityManager: Killing 6080:com.samsung.helphub/1000 (adj 15): empty #31
,08-30 17:08:13.521  1015  3082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:13.521  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:13.521  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:13.521  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.521  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.521  3640  3640 I Hs20UtilService: Starting #11
,08-30 17:08:13.521  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:13.521  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:13.521  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:13.521  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:13.521  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:13.531  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:13.531  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:13.531  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:13.531  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:13.531  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:13.541  3640  3640 I Hs20UtilService: Starting #12
08-30 17:08:13.541  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:13.541  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:13.541  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:13.541  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:13.541  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:13.561   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-30 17:08:13.561  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-30 17:08:13.631  6781  6781 I wpa_supplicant: Ctrl_iface: loading cred from phone,
,08-30 17:08:13.631  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:13.641  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:08:13.641   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6781
08-30 17:08:13.641   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:13.641  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:08:13.641  6781  6781 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:13.641  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 17:08:13.641  6781  6781 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:13.641  6781  6781 E wpa_supplicant: SIM READ ERROR
08-30 17:08:13.641  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:13.641  6781  6781 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:13.641  6781  6781 E wpa_supplicant: SIM READ ERROR
08-30 17:08:13.641  6781  6781 I wpa_supplicant: Blacklist: Clear (all) ,
08-30 17:08:13.641  6781  6781 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:13.641  6781  6781 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:13.641  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:13.641  6781  6781 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 17:08:13.641  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:13.641  6781  6781 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,08-30 17:08:13.651  6781  6781 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 17:08:13.651  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:08:13.651  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:13.651  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:13.691  6781  6781 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-30 17:08:13.951  6781  6781 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 17:08:13.951  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:13.961   287   287 E SMD     : DCD OFF
,08-30 17:08:13.961  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:08:13.971   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6781
08-30 17:08:13.971   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:13.971  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:08:13.971  6781  6781 I wpa_supplicant: ssSupport state is = 1
,08-30 17:08:13.971  6781  6781 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:08:13.971  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 17:08:13.981  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 17:08:13.981   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6781
08-30 17:08:13.981   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:13.981  6781  6781 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 17:08:13.981  6781  6781 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:13.981  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 17:08:13.981  6781  6781 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:13.981  6781  6781 E wpa_supplicant: SIM READ ERROR
08-30 17:08:13.981  6781  6781 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:13.981  6781  6781 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:13.981  6781  6781 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 17:08:13.981  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 17:08:13.981  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:13.981  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:13.981  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 17:08:13.981  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:13.981  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:14.031  6781  6781 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 17:08:14.031  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:08:14.091  6781  6781 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 17:08:14.091  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 17:08:14.091  6781  6781 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:08:14.101  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-30 17:08:14.101  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:14.101  6781  6781 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-30 17:08:14.111  6781  6781 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 17:08:14.111  6781  6781 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:14.111  6781  6781 E wpa_supplicant: SIM READ ERROR,
08-30 17:08:14.111  6781  6781 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:14.141  6781  6781 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 17:08:14.151  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 17:08:14.151  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:14.151  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:14.151  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:14.151  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:14.151  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:14.151  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:14.151  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:14.151  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:14.151  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-30 17:08:14.151  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
08-30 17:08:14.151  6781  6781 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:08:14.151  1177  1177 D HotspotTile: onReceive : 3, 0
08-30 17:08:14.161  1015  1130 D WifiConfigStore: Loading config and enabling all networks ,
08-30 17:08:14.161  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:14.161  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:14.161  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.161  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-30 17:08:14.161  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:14.161  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:14.161  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:14.161  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:14.161  1015  1560 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:14.161  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:14.161  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:14.161  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:14.161  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:14.161  1015  1130 E WifiConfigStore: Not a HS20
,08-30 17:08:14.171  1015  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 17:08:14.171  3640  3640 I Hs20UtilService: Starting #13
,08-30 17:08:14.171  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:14.171  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 17:08:14.171  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:08:14.171  6781  6781 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:08:14.171  6781  6781 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:08:14.171  6781  6781 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:14.171  6781  6781 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:08:14.171  6781  6781 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:08:14.171  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:08:14.171  6781  6781 I wpa_supplicant: First Scan Start
,08-30 17:08:14.171  6781  6781 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:08:14.171  1015  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:08:14.181  1015  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:14.181  1015  1130 I WifiNative-HAL: startHal
08-30 17:08:14.181  1015  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9ca8988c
08-30 17:08:14.181  1015  1130 I WifiNative-HAL: Could not start hal
08-30 17:08:14.181  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 17:08:14.181  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:14.181  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:14.181  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 17:08:14.181  6386  6386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 17:08:14.181  1015  1130 E WifiNative-wlan0: do suspend true
08-30 17:08:14.181  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
08-30 17:08:14.181  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 17:08:14.181  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:08:14.181  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:14.181  1015  1148 I WifiNative-HAL: startHal
08-30 17:08:14.181  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dd399bc
08-30 17:08:14.181  1015  1148 I WifiNative-HAL: Could not start hal
08-30 17:08:14.181  1015  1148 E WifiScanningService: could not start HAL
08-30 17:08:14.181  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-30 17:08:14.181  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:14.181  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:14.181  1015  1130 E WifiNative-wlan0: invaild command id : 215
08-30 17:08:14.181  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:14.181  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:14.181  1015  1130 E WifiNative-wlan0: invaild command id : 215
08-30 17:08:14.191   277   951 D CommandListener: Setting iface cfg
08-30 17:08:14.191   277   951 D CommandListener: Trying to bring up p2p0
08-30 17:08:14.191  1015  1149 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:14.191  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-30 17:08:14.191  1015  1125 D WifiP2pService: P2pEnablingState
08-30 17:08:14.191  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-30 17:08:14.191  1015  1125 D WifiP2pService: P2p socket connection successful
08-30 17:08:14.191  1015  1125 D WifiP2pService: P2pEnabledState
,08-30 17:08:14.191  6781  6781 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:14.191  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 17:08:14.191  6781  6781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:14.191  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:08:14.191  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:14.191  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 17:08:14.191  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:14.191  1015  1045 D WifiDisplayController: disconnect
08-30 17:08:14.191  1015  1045 D WifiDisplayController: updateConnection
08-30 17:08:14.191  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:14.191  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:14.191  6781  6781 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
08-30 17:08:14.191  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:14.191  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-30 17:08:14.191  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:14.191  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-30 17:08:14.201  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:14.201  1015  1560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:14.201  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:14.201  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:08:14.201  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:14.201  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-30 17:08:14.201  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-30 17:08:14.201  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:14.201  1015  1130 D SecContentProvider2: mCursor = null
08-30 17:08:14.201  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-30 17:08:14.201  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  secondary type: null
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  wps: 0
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  grpcapab: 0
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  devcapab: 0
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  status: 3
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  wfdInfo: null
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-30 17:08:14.201  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-30 17:08:14.201  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:14.211  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:14.211  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:14.211  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:14.211  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:14.211  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:14.211  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:14.211  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:14.211  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 17:08:14.211  6432  6432 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:14.211  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:14.221  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 17:08:14.221  1015  1125 D WifiP2pService: InactiveState
,08-30 17:08:14.221  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:08:14.221  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:14.221  6781  6781 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:14.221  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:08:14.221  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:14.261  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:14.261  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:14.261  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:15.391  6781  6781 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
,08-30 17:08:15.391  6781  6781 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-30 17:08:15.401  1015  6802 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-30 17:08:15.401  6781  6781 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-30 17:08:15.401  6781  6781 I wpa_supplicant: Trying to associate with  'G700'
,08-30 17:08:15.401  6781  6781 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-30 17:08:15.401  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-30 17:08:15.421  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:15.421  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:15.511  6781  6781 E wpa_supplicant: Cmd 35605 not handled
,08-30 17:08:15.511  6781  6781 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:15.511  6781  6781 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-30 17:08:15.511  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:15.511  6781  6781 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 17:08:15.511  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:15.511  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:15.521  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 17:08:15.521  6781  6781 I wpa_supplicant: Associated with F4.99.3E
08-30 17:08:15.521  6781  6781 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:15.521  6781  6781 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:08:15.521  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:08:15.521  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-30 17:08:15.521  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:15.521  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:15.521  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:15.521  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:15.521  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:15.521  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:15.521  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:08:15.521  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-30 17:08:15.521  1015  1133 E Tethering: No numeric data
08-30 17:08:15.521  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 17:08:15.521  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:15.531  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:15.531  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:15.531  1015  1130 D SecContentProvider2: mCursor = null
08-30 17:08:15.531  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:08:15.531  6781  6781 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:15.531  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 17:08:15.531  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:15.531  6781  6781 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 17:08:15.531  6781  6781 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-30 17:08:15.531  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
08-30 17:08:15.531  6781  6781 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:15.541  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:15.531  6781  6781 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 17:08:15.541  1015  1123 V NetworkStats: performPollLocked() took 12ms
08-30 17:08:15.531  6781  6781 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 17:08:15.531  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:15.531  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:15.531  6781  6781 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 17:08:15.531  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:15.541  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:08:15.541  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-30 17:08:15.541  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:15.541  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:15.541  1015  1130 D SecContentProvider2: mCursor = null
08-30 17:08:15.541  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:15.541  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:15.551  1015  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 17:08:15.551  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:08:15.561  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:15.561  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:15.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.561  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:15.561  1015  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 17:08:15.561  1015  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-30 17:08:15.561  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:15.561  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:15.561  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:08:15.571  1015  1213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:15.571  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:15.571  1015  1213 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:15.571  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:15.571  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:15.581  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:15.581  3640  3640 I Hs20UtilService: Starting #14
,08-30 17:08:15.581  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:15.581  3640  3675 I Hs20UtilService: Message received 5007
08-30 17:08:15.581  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:15.581  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-30 17:08:15.581  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:15.581  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:15.581  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:15.581  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:15.591   277   951 D CommandListener: Setting iface cfg
,08-30 17:08:15.601  1015  1130 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 17:08:15.601  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:15.601  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:15.611  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:15.611  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:15.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.611  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:15.611  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:15.611  1015  1130 E WifiNative-wlan0: do suspend false,
,08-30 17:08:15.621  1015  1125 D WifiP2pService: InactiveState{ what=143375 },
08-30 17:08:15.621  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:15.831  6810  6810 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:08:15.831  6810  6810 I dhcpcd  : version 5.5.6 starting,
,08-30 17:08:15.841  6810  6810 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 17:08:15.861  1015  1470 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-30 17:08:15.871  1015  1470 D WifiService: setWifiEnabled: false pid=6192, uid=10155
08-30 17:08:15.861  1015  1470 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:15.861  1015  1470 D SecContentProvider2: mCursor = null,
08-30 17:08:15.871  1015  1470 D SettingsProvider: name = wifi_on
,08-30 17:08:15.871  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:15.891  1015  1130 E WifiNative-wlan0: do suspend true,
,08-30 17:08:15.901  6810  6810 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-30 17:08:15.901  6810  6810 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-30 17:08:15.911  6810  6810 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-30 17:08:15.911  6810  6810 I dhcpcd  : bssid match
08-30 17:08:15.911  6810  6810 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
08-30 17:08:15.911  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
08-30 17:08:15.911  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:15.911   277   951 D CommandListener: Clearing all IP addresses on wlan0,
08-30 17:08:15.911  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-30 17:08:15.911  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:15.911  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-30 17:08:15.911  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:15.911  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-30 17:08:15.911  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.921  1015  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
08-30 17:08:15.911  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.921  1015  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-30 17:08:15.911  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.921  1015  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-30 17:08:15.911  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:15.921  1015  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:15.921  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:15.921  1015  1132 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-30 17:08:15.921   277   951 E Netd    : no such netId 503
08-30 17:08:15.921  1015  6808 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:15.921  1015  6808 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-30 17:08:15.921  1015  1132 D ConnectivityService: nai.networkMonitor.doQuit()
,08-30 17:08:15.921  1015  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-30 17:08:15.931  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:15.931  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:15.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.931  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.931  1015  1040 I ActivityManager: Killing 5461:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-30 17:08:15.931  1015  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 17:08:15.931  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
08-30 17:08:15.931  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-30 17:08:15.931  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 17:08:15.941  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 17:08:15.941  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:15.941  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:15.941  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-30 17:08:15.941  1015  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 17:08:15.941  1015  3085 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:15.941  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:15.941  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:15.941  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:15.941  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:15.941  3640  3640 I Hs20UtilService: Starting #15
,08-30 17:08:15.941  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:15.941  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:15.941  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:15.941  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:15.941  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:15.941  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 17:08:15.941  1015  1132 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:15.941  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:08:15.941  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-30 17:08:15.941  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 17:08:15.941  1015  1045 D WifiDisplayController: disconnect
08-30 17:08:15.941  1015  1045 D WifiDisplayController: updateConnection
08-30 17:08:15.941  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:15.941  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:15.951  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:15.951  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:15.951  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:15.951  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:15.951  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:15.951  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:15.951  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 17:08:15.951  1015  1125 D WifiP2pService: P2pDisablingState
08-30 17:08:15.951  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 17:08:15.951  1015  1125 D WifiP2pService: p2p socket connection lost
08-30 17:08:15.951  1015  1125 D WifiP2pService: P2pDisabledState
08-30 17:08:15.951  1015  1130 E WifiNative-wlan0: do suspend true
,08-30 17:08:15.951  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 17:08:15.951  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:15.951  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:15.951  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 17:08:15.951  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 17:08:15.951  1015  1213 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:15.961  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:15.961  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 17:08:15.961  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:15.961  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:15.961  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:15.961  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:15.961  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 17:08:15.961  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:15.971  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:15.971  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 17:08:15.971  6432  6432 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:15.971  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:15.981  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 17:08:15.981  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-30 17:08:15.991   277   951 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:15.991  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:15.991  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:15.991  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:15.991  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:15.991  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:15.991  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:15.991  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-30 17:08:16.001  6781  6781 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:16.001  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:16.001  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:16.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.001  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:16.001  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:16.001  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:16.011  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:16.011  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:16.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:16.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.011  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:16.011  6810  6810 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-30 17:08:16.011  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:16.011  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 17:08:16.011  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:16.011  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:16.011  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:16.011  1177  1177 D HotspotTile: onReceive : 0, 0
,08-30 17:08:16.011  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:16.021  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:16.021  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:16.021  1015  3082 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:16.021  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:16.021  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.021  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:16.021  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:16.021  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:16.021  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:16.021  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:16.021  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:16.021  3640  3640 I Hs20UtilService: Starting #16
,08-30 17:08:16.021  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:16.031  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:16.031  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:16.031  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:16.031  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:16.031  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:16.031  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:16.031  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:16.041  1015  1213 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:16.041  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:16.041  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:16.041  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:16.041  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:16.041  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:16.041  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 17:08:16.041  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
08-30 17:08:16.041  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:16.041  3640  3640 I Hs20UtilService: Starting #17
,08-30 17:08:16.051  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:16.081  6810  6810 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-30 17:08:16.171  6781  6781 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:16.301  6781  6781 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-30 17:08:16.301  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:16.301  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:16.301  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:16.321  6781  6781 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 17:08:16.321  6781  6781 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 17:08:16.321  6781  6781 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 17:08:16.321  6781  6781 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-30 17:08:16.321  6781  6781 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-30 17:08:16.331  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.331  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-30 17:08:16.331  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:16.331  1015  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-30 17:08:16.331  1015  1133 D Tethering: InitialState.processMessage what=4
08-30 17:08:16.331  1015  1133 E Tethering: No numeric data
08-30 17:08:16.331  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:16.331  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:16.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:16.341  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:16.341  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.341  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:16.341  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:16.341  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:16.341  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:16.341  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 17:08:16.341  1015  1123 V NetworkStats: performPollLocked() took 6ms
08-30 17:08:16.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:16.341  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:16.341  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:16.341  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:16.341  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:16.341  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:16.511  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.511  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.511  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:16.741  6781  6781 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 17:08:16.901  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:08:16.901  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:16.901  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:16.901  6781  6781 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 17:08:16.961   287   287 E SMD     : DCD OFF,
,08-30 17:08:17.011  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-30 17:08:17.011  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:17.011  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 17:08:17.011  6386  6386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:17.021  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:17.021  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:17.021  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:17.021  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:17.021  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:17.021  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:17.021  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:17.021  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 17:08:17.021  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 17:08:17.021  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:17.021  1177  1177 D HotspotTile: onReceive : 1, 0
,08-30 17:08:17.021  1924  2124 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:17.031  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:17.031  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.031  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:17.031  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:17.031  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:17.031  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.031  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:17.031  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:17.041  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:17.041  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:17.041  3640  3640 I Hs20UtilService: Starting #18
,08-30 17:08:17.041  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:17.041  3640  3675 I Hs20UtilService: Message received 5011
08-30 17:08:17.041  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:17.671   277   945 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 17:08:17.671  1015  1042 D Tethering: interfaceRemoved wlan0
,08-30 17:08:17.671  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 17:08:17.701  1015  3083 I art     : Explicit concurrent mark sweep GC freed 77723(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.400ms total 170.059ms
,08-30 17:08:17.701  1015  3083 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-30 17:08:17.701  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.711  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.711  1015  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.711  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.711  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.711  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.711  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.721  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 17:08:17.731  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.731  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.731  6602  6675 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 17:08:17.731  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.731  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.731  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.731  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.731  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.751  1015  1219 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:17.751  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.751  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.751  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.751  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.751  1015  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:17.761  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.761  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.761  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.761  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.761  1015  3085 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:17.761  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 17:08:17.761  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.761  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.761  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.771  1015  1219 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 17:08:17.771  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-30 17:08:17.771  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.771  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.771  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.791  1015  1560 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:17.791  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:17.791  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.791  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 17:08:17.801  1924  1924 D WearableService: callingUid 10012, callindPid: 1924
,08-30 17:08:17.811  1015  1042 D Tethering: interfaceRemoved p2p0
08-30 17:08:17.811  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 17:08:17.811  1015  1219 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 17:08:17.811  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 17:08:17.811  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:17.811  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:17.811  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 17:08:17.851  6515  6515 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 17:08:17.851  6515  6846 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 17:08:17.871  6515  6841 I MusicLeanback: Conditions not met for autocaching.
08-30 17:08:17.871  6515  6841 I MusicLeanback: Stop autocaching.
,08-30 17:08:18.721  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 17:08:18.871  6192  6244 D BluetoothAdapter: enable()
,08-30 17:08:18.881  1015  1470 W ActivityManager: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 17:08:18.881  1015  1470 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: ,	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 17:08:18.881  1015  1470 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:18.881  1015  1470 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-30 17:08:18.881  1015  1470 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:18.881  1015  1470 D SettingsProvider: name = bluetooth_on
,08-30 17:08:18.891  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:18.891  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:18.891  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-30 17:08:18.891  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 17:08:18.931  6481  6481 D BluetoothAdapterState: make
,08-30 17:08:18.941  6481  6481 I bluedroid: init
,08-30 17:08:18.941  6481  6848 I BluetoothAdapterState: Entering OffState
,08-30 17:08:18.951  6481  6481 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:08:18.951  6481  6481 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:08:18.951  6481  6481 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:18.951  6481  6481 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:08:18.951  6481  6481 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 17:08:18.951  6481  6481 I bluedroid: get_profile_interface socket
08-30 17:08:18.951  6481  6481 I bluedroid: get_profile_interface map_client
,08-30 17:08:18.961  6481  6851 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
,08-30 17:08:18.961  6481  6481 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 17:08:18.961  6481  6851 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 17:08:18.961  6481  6851 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:08:18.961  6481  6851 I bluedroid: getModelRssiValues
08-30 17:08:18.961  6481  6851 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 17:08:18.971  6481  6851 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-30 17:08:18.971  6481  6851 D BluetoothAdapterProperties: Name is: A5-1
,08-30 17:08:18.971  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 17:08:18.971  6481  6481 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:18.971  1015  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:18.971  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:18.971  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:18.971  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:18.971  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:18.981  6481  6491 I bluedroid: config_hci_snoop_log
,08-30 17:08:18.981  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 17:08:18.981  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-30 17:08:18.981  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 17:08:18.981  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 17:08:18.981  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:18.991  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:18.991  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:18.991  6481  6481 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 17:08:18.991  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:08:18.991  6481  6848 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 17:08:18.991  6481  6848 D BluetoothAdapterProperties: Setting state to 11
,08-30 17:08:18.991  6481  6848 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-30 17:08:18.991  6481  6848 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:08:18.991  6481  6848 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 17:08:19.001  6481  6848 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:19.001  6481  6848 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 17:08:19.011  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.011  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-30 17:08:19.011  6481  6848 D BluetoothSecureManager: getInstant: null
08-30 17:08:19.011  6481  6848 D BluetoothSecureManager: calling getMethod for getService
08-30 17:08:19.011  6481  6848 D BluetoothSecureManager: calling getService
,08-30 17:08:19.011  6481  6848 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3bc18d30
,08-30 17:08:19.011  1015  1027 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 17:08:19.011  1015  1027 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-30 17:08:19.011  6481  6848 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:19.011  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:08:19.011  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 17:08:19.011  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:19.021  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:19.021  1828  1828 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:19.021  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.021  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 17:08:19.021  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-30 17:08:19.021  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:19.021  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:19.021  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 17:08:19.021  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 17:08:19.021  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:19.021  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 17:08:19.021  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 17:08:19.021  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 17:08:19.021  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:19.021  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 17:08:19.021  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 17:08:19.031  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 17:08:19.031  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:19.031  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:19.031  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:19.031  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:19.031  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:19.031  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 17:08:19.031  1015  3083 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:19.031  6481  6848 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 17:08:19.031  6481  6848 D BluetoothBondStateMachine: make
,08-30 17:08:19.031  1015  3085 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:19.041  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:19.041  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.041  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.041  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:19.041  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:19.041  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:19.041  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:19.041  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:19.041  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 17:08:19.041  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:19.041  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:19.051  6481  6852 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 17:08:19.051  1015  3082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:19.051  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.051  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.051  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:19.051  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.051  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:19.051  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:19.051  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:19.051  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:19.051  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.051  6481  6481 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:08:19.051  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.051  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.051  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.051  6481  6481 D BtGatt.GattService: Received start request. Starting profile...
,08-30 17:08:19.051  6481  6481 D BtGatt.GattService: start()
08-30 17:08:19.051  6481  6481 D BtGatt.GattService: start()
08-30 17:08:19.051  6481  6481 I bluedroid: get_profile_interface gatt
,08-30 17:08:19.051  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:19.051  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:19.051  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:19.051  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:19.051  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:19.051  6481  6481 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:08:19.061  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.061  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.061  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.061  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:19.061  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:19.061  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 17:08:19.061  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:19.061  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:08:19.071  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:19.071  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 17:08:19.071  1015  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:19.071  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.071  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.071  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.071  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.071  6481  6481 D BtGatt.GattService: mStartError = false
08-30 17:08:19.071  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.081  6481  6481 D HeadsetService: Received start request. Starting profile...
,08-30 17:08:19.081  6481  6481 D HeadsetService: start()
,08-30 17:08:19.081  6481  6481 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 17:08:19.081  6481  6481 D HeadsetStateMachine: make
,08-30 17:08:19.091  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 17:08:19.091  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:19.091  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:19.091  6481  6481 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 17:08:19.101  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 17:08:19.101  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.101  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.101  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.101  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:19.101  1015  3085 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:19.101  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.101  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.101  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.101  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.111  1015  1216 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 17:08:19.111  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.111  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.111  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:19.111  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:19.111  6481  6481 I bluedroid: get_profile_interface handsfree
,08-30 17:08:19.111  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:19.111  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:19.111  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:19.121  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:19.121  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.121  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:19.121  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.121  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.121  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:19.121  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:19.131  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:19.131  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:19.131  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.131  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.131  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.131  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.131  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-30 17:08:19.131  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:19.131  6481  6848 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:19.141  6481  6481 I DualScoManager: Instantiating Dual Sco Manager
,08-30 17:08:19.141  6481  6481 I DualScoManager: Set HeadsetServiceHelper
,08-30 17:08:19.151  6481  6481 D BluetoothAtMessage: createCMTIContentObservers
08-30 17:08:19.151  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:19.151  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:19.151  1015  1216 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 17:08:19.151  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:19.151  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:19.151  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:19.151  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:19.151  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:19.151  1015  1216 D SettingsProvider: selectionArgs: false
08-30 17:08:19.151  1015  1216 D SettingsProvider: selectionArgs: 1002
08-30 17:08:19.151  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:19.151  1015  1216 D SettingsProvider: ret = -1
,08-30 17:08:19.151  6481  6857 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 17:08:19.151  6481  6481 D HeadsetService: mStartError = false
,08-30 17:08:19.151  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:19.151  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:19.151  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:19.161  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:19.161  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:19.161  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:19.161  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:19.161  6481  6848 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 17:08:19.161  6481  6481 D A2dpService: Received start request. Starting profile...
,08-30 17:08:19.161  6481  6481 D A2dpService: start()
,08-30 17:08:19.161  6481  6857 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 17:08:19.161  6481  6857 D HeadsetStateMachine: map size, before remove : 0
08-30 17:08:19.161  6481  6857 D HeadsetStateMachine: map size, after remove: 0
,08-30 17:08:19.161  6481  6481 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 17:08:19.161  6481  6481 I bluedroid: get_profile_interface avrcp
,08-30 17:08:19.171  6481  6481 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:08:19.191  6481  6481 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:08:19.191  6481  6861 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-30 17:08:19.191  6481  6481 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:19.191  6481  6481 D A2dpStateMachine: make
,08-30 17:08:19.191  6481  6481 I bluedroid: get_profile_interface a2dp
08-30 17:08:19.191  6481  6863 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-30 17:08:19.191  6481  6481 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 17:08:19.201  6481  6481 D A2dpService: mStartError = false
08-30 17:08:19.201  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.201  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 17:08:19.201  6481  6481 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:08:19.201  6481  6481 D HidService: Received start request. Starting profile...
08-30 17:08:19.201  6481  6481 D HidService: start()
08-30 17:08:19.201  6481  6481 I bluedroid: get_profile_interface hidhost
08-30 17:08:19.201  6481  6481 D HidService: setHidService(): set to: null
08-30 17:08:19.201  6481  6481 D HidService: mStartError = false
08-30 17:08:19.201  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.201  6481  6481 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 17:08:19.201  6481  6862 D A2dpStateMachine: Enter Disconnected: -2
,08-30 17:08:19.201  1429  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:08:19.201  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 17:08:19.211  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 17:08:19.211  1429  1437 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 17:08:19.211  6481  6481 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:08:19.211  6481  6481 D HealthService: Received start request. Starting profile...
,08-30 17:08:19.211  6481  6481 D HealthService: start()
,08-30 17:08:19.211  6481  6861 D BluetoothMediaBrowser: no now playing list
08-30 17:08:19.211  6481  6861 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 17:08:19.211  6481  6481 I bluedroid: get_profile_interface health
,08-30 17:08:19.211  6481  6481 D HealthService: mStartError = false
08-30 17:08:19.211  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.211  6481  6481 D HeadsetStateMachine: Proxy object connected
,08-30 17:08:19.211  6481  6481 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 17:08:19.211  6481  6857 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:08:19.211  6481  6481 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:08:19.221  6481  6481 D PanService: Received start request. Starting profile...
08-30 17:08:19.221  6481  6481 D PanService: start()
08-30 17:08:19.221  6481  6481 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:19.221  6481  6481 I bluedroid: get_profile_interface pan
,08-30 17:08:19.221  6481  6481 D PanService: mStartError = false
08-30 17:08:19.221  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:19.221  6481  6481 D BluetoothMapService: Received start request. Starting profile...
08-30 17:08:19.221  6481  6481 D BluetoothMapService: start()
,08-30 17:08:19.231  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:19.231  6481  6481 D BluetoothMapService: mStartError = false
08-30 17:08:19.231  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:19.231  6481  6481 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 17:08:19.231  6481  6481 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-30 17:08:19.231  6481  6481 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-30 17:08:19.231  6481  6857 D HeadsetStateMachine: Disconnected process message: 18
,08-30 17:08:19.231  6481  6481 D SapService: Received start request. Starting profile...
08-30 17:08:19.231  6481  6481 D SapService: start()
08-30 17:08:19.231  6481  6481 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:08:19.231  6481  6481 I bluedroid: get_profile_interface sap
08-30 17:08:19.231  6481  6481 D SapService: mStartError = false
08-30 17:08:19.231  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:19.231  6481  6481 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:19.231  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 17:08:19.231  6481  6481 D BluetoothA2dp: Proxy object connected
08-30 17:08:19.231  6481  6481 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 17:08:19.231  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:08:19.231  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-30 17:08:19.231  6481  6857 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:08:19.231  6481  6857 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-30 17:08:19.231  6481  6857 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:08:19.241  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 17:08:19.241  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:08:19.241  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:19.261  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:08:19.261  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:08:19.261  6481  6848 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:08:19.261  6481  6848 I bluedroid: enable
08-30 17:08:19.261  6481  6848 I bt_hci_bdroid: init
,08-30 17:08:19.271  6481  6868 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 17:08:19.271  6481  6848 I bt_vendor: bt-vendor : init
,08-30 17:08:19.271  6481  6848 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:19.271  6481  6848 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-30 17:08:19.271  6481  6848 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-30 17:08:19.271  6481  6848 D bt_userial_mct: userial_init
,08-30 17:08:19.271  6481  6848 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:19.271  6481  6848 I bt_vendor: Starting hciattach daemon
08-30 17:08:19.271  6481  6848 I bt_vendor: try to set false
,08-30 17:08:19.271  6481  6848 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 17:08:19.271  6481  6848 I bt_vendor: Starting hciattach daemon
08-30 17:08:19.271  6481  6848 I bt_vendor: try to set true
,08-30 17:08:19.291  6872  6872 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 17:08:19.351  6878  6878 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 17:08:19.361  6879  6879 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:19.371  6881  6881 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:19.381  1015  3082 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-30 17:08:19.381  1015  3082 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3930, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 17:08:19.381  1015  3082 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 17:08:19.381  1015  3082 D BatteryService: stay LED for charging
08-30 17:08:19.381  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:08:19.381  6882  6882 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
08-30 17:08:19.381  1015  1015 I MotionRecognitionService: Plugged
08-30 17:08:19.381  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-30 17:08:19.391  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 17:08:19.391  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:08:19.391  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
08-30 17:08:19.391  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,08-30 17:08:19.401  6883  6883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-30 17:08:19.401  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:08:19.401  6481  6481 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:08:19.401  6481  6857 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:19.401  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-30 17:08:19.421  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
08-30 17:08:19.421  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:08:19.831  6887  6887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 17:08:19.841  6888  6888 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:19.881  6481  6848 I bt_vendor: bluetooth satus is on,
08-30 17:08:19.881  6481  6870 D bt_userial_mct: userial_open(port:0)
08-30 17:08:19.881  6481  6870 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 17:08:19.881  6481  6870 I bt_vendor: Done intiailizing UART,
,08-30 17:08:19.891  6481  6870 I bt_vendor: Done intiailizing UART,
08-30 17:08:19.891  6481  6870 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 17:08:19.891  6481  6870 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_HCI,
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_AVRC
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_SDP,
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:08:19.891  6481  6868 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 17:08:19.891  6481  6890 D bt_userial_mct: Entering userial_read_thread()
,08-30 17:08:19.961   287   287 E SMD     : DCD OFF
,08-30 17:08:19.991  6481  6868 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 17:08:20.001  6481  6868 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa405a6e9 
,08-30 17:08:20.001  6481  6868 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa405a6e9 
,08-30 17:08:20.021  6481  6851 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 17:08:20.031  6481  6851 E bt-btif : Calling BTA_HhEnable
,08-30 17:08:20.031  6481  6851 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:08:20.031  6481  6851 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 17:08:20.031  6481  6851 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:08:20.031  6481  6851 I bluedroid: getModelRssiValues
,08-30 17:08:20.031  6481  6851 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 17:08:20.031  6481  6851 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:20.031  6481  6851 D BluetoothAdapterProperties: Name is: A5-1
,08-30 17:08:20.031  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 17:08:20.041  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.041  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.041  6481  6851 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:08:20.041  6481  6851 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:20.041  6481  6851 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:20.051  6481  6851 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-30 17:08:20.051  6481  6851 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-30 17:08:20.051  6481  6851 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-30 17:08:20.051  6481  6851 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-30 17:08:20.051  6481  6851 E bt-btif : btif_sock_init: !vhci_init
,08-30 17:08:20.051  6481  6851 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 17:08:20.051  6481  6851 D IOP_DB_BT: db_open: db_open : handle 3028103184l, read 13894 bytes onto local cache
08-30 17:08:20.051  6481  6851 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 17:08:20.051  6481  6851 D IOP_DB_BT: db_query: result 1
08-30 17:08:20.051  6481  6851 I         : iop_db_open: iop_db_open status 0
,08-30 17:08:20.051  6481  6851 D bte_conf: Device ID record 1 : primary
08-30 17:08:20.051  6481  6851 D bte_conf:   vendorId            = 0075
08-30 17:08:20.051  6481  6851 D bte_conf:   vendorIdSource      = 0001
08-30 17:08:20.051  6481  6851 D bte_conf:   product             = 0100
08-30 17:08:20.051  6481  6851 D bte_conf:   version             = 0200
08-30 17:08:20.051  6481  6851 D bte_conf:   clientExecutableURL = 
08-30 17:08:20.051  6481  6851 D bte_conf:   serviceDescription  = 
08-30 17:08:20.051  6481  6851 D bte_conf:   documentationURL    = 
08-30 17:08:20.051  6481  6851 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 17:08:20.051  6481  6851 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:08:20.061  6481  6848 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:08:20.061  6481  6848 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:08:20.061  6481  6848 D BluetoothAdapterProperties: State =  11
,08-30 17:08:20.061  6481  6890 E bt_mct  : hci lib postload completed
,08-30 17:08:20.061  1015  1216 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:20.061  6481  6848 D BluetoothAdapterProperties: Setting state to 12
,08-30 17:08:20.061  6481  6848 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:08:20.061  6481  6851 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:20.061  6481  6851 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:20.061  6481  6851 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:20.061  1015  3082 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-30 17:08:20.061  1015  3082 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:20.061  1015  3082 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:20.061  1015  3082 D SettingsProvider: selectionArgs: false
08-30 17:08:20.061  1015  3082 D SettingsProvider: selectionArgs: 1002
08-30 17:08:20.061  1015  3082 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:20.061  1015  3082 D SettingsProvider: ret = -1
,08-30 17:08:20.061  6481  6848 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:20.061  6481  6848 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:08:20.071  1015  3083 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:20.071  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.071  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.071  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.071  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.081  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:20.081  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.081  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 17:08:20.081  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:08:20.081  2912  2922 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:20.081  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.081  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.081  6481  6848 D BluetoothAdapterService: Autoconnection is available 
08-30 17:08:20.081  6481  6848 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 17:08:20.081  6481  6848 D BluetoothAdapterService: starting service from this receiver
08-30 17:08:20.081  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.091  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.091  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.091  1015  1213 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:20.091  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.091  2912  2922 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:20.091  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.091  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:20.091  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:20.091  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:20.091  6481  6848 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:08:20.091  6481  6481 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 17:08:20.101  1318  1336 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:08:20.101  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:20.101  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 17:08:20.101  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.101  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.101  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.101  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:20.101  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:20.111  1318  1339 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:20.111  1318  1339 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.111  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:20.111  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.111  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.111  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.111  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.111  1318  1339 D BluetoothPan: Binding service...
,08-30 17:08:20.111  1318  1318 D BluetoothA2dp: Proxy object connected
08-30 17:08:20.111  1318  1318 D A2dpProfile: Bluetooth service connected
,08-30 17:08:20.121  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:20.121  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-30 17:08:20.121  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:08:20.121  6481  6481 I BluetoothPbapService: Handler(): got msg=1
,08-30 17:08:20.121  1015  1216 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:08:20.121  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.121  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.121  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.121  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.121  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.121  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.131  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.131  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:20.131  1318  1318 D BluetoothInputDevice: Proxy object connected
,08-30 17:08:20.131  1318  1318 D HidProfile: Bluetooth service connected
08-30 17:08:20.131  1429  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.131  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.131  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.131  6481  6897 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:08:20.131  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-30 17:08:20.131  1429  1446 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:08:20.131  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.131  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.131  2912  2926 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:20.131  1318  1318 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:20.131  1318  1318 D PanProfile: Bluetooth service connected
08-30 17:08:20.131  2912  2926 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.131  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:08:20.131  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.131  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.131  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.141  2912  2912 D BluetoothA2dp: Proxy object connected
,08-30 17:08:20.141  6481  6897 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:08:20.141  1318  1339 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.141  6481  6897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:20.141  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.141  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.141  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.141  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.141  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 17:08:20.141  1318  1339 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:20.141  1453  1466 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.141  6481  6897 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 17:08:20.141  6481  6897 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:20.141  6481  6897 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:20.141  6481  6897 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2185d354
08-30 17:08:20.141  6481  6897 D BluetoothSocket: channel: 19
08-30 17:08:20.141  6481  6897 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:08:20.141  1318  1318 D HeadsetProfile: Bluetooth service connected
,08-30 17:08:20.141  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:20.141  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.141  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.141  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.141  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.151  1453  1466 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:20.151  1177  1199 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.151  1177  1199 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.151  1440  6402 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:20.151  1440  6402 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.151  6351  6362 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.151  6351  6362 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.151  1924  1942 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.151  1924  1942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:20.151  1318  6895 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 17:08:20.151  1318  6895 D Bluetoothsap: Binding service...
,08-30 17:08:20.151  1318  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 17:08:20.151  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 17:08:20.151  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.151  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.151  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.151  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.161  1318  6895 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:08:20.161  1015  1044 D BluetoothPan: Binding service...
08-30 17:08:20.161  1318  1318 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 17:08:20.161  1318  1318 D SapProfile: Bluetooth service connected
08-30 17:08:20.161  1318  1318 D Bluetoothsap: getConnectedDevices()
,08-30 17:08:20.161  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:20.161  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.161  1318  1339 D BluetoothPbap: onBluetoothStateChange: up=true
08-30 17:08:20.161  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 17:08:20.161  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 17:08:20.161  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.161  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.161  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:20.161  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.161  6481  6489 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:20.161  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:20.161  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:20.161  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:08:20.161  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.161  1015  1015 D BluetoothA2dp: Proxy object connected
08-30 17:08:20.161  1318  1318 D BluetoothPbap: Proxy object connected
08-30 17:08:20.161  1318  1318 D PbapServerProfile: Bluetooth service connected
08-30 17:08:20.161  6481  6491 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.161  6481  6491 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:20.161  1318  6895 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:08:20.171  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 17:08:20.171  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.171  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.171  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.171  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.171  2912  6894 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.171  2912  6894 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.171  1429  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.171  1318  1318 D BluetoothMap: Proxy object connected
08-30 17:08:20.171  1318  1318 D MapProfile: Bluetooth service connected
08-30 17:08:20.171  1318  1318 D BluetoothMap: getConnectedDevices()
08-30 17:08:20.171  1429  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.171  1318  1336 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.171  1318  1336 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.171  6192  6200 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:20.171  6192  6200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:20.171  1429  6898 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:20.171  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:20.171  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:20.171  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.171  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.171  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.171  1429  6898 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:20.181  1453  1682 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:20.181  1453  1682 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:20.181  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 17:08:20.181  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:20.181  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:20.181  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-30 17:08:20.181  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:20.181  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:20.191  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1dfb1e53, true
,08-30 17:08:20.191  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:20.191  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.191  1177  1177 D BluetoothTile:  getBluetoothState : 12
,08-30 17:08:20.191  1429  1429 D BluetoothHeadset: registerMessageListener
,08-30 17:08:20.191  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:20.191  1828  1828 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:20.191  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.201  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.201  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:20.201  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:20.201  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.201  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:20.201  6481  6893 D HeadsetService: registerMessageListener
,08-30 17:08:20.201  6481  6893 D HeadsetService: registerMessageListener
,08-30 17:08:20.201  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:20.201  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.201  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 17:08:20.201  6481  6901 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 17:08:20.201  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 17:08:20.201  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.201  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.211  1015  1560 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:20.211  6481  6857 D HeadsetStateMachine: Disconnected process message: 70
,08-30 17:08:20.211  6481  6857 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1356c2fd
08-30 17:08:20.211  1015  1475 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-30 17:08:20.211  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 17:08:20.211  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:08:20.211  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:20.211  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 17:08:20.211  6481  6857 D HeadsetStateMachine: Disconnected process message: 9
,08-30 17:08:20.211  6481  6857 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-30 17:08:20.211  1318  1318 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 17:08:20.211  6481  6901 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:20.211  6481  6901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:20.211  1318  1318 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 17:08:20.211  1318  1318 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 17:08:20.211  1318  1318 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-30 17:08:20.221  6481  6901 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-30 17:08:20.221  6481  6901 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:20.221  6481  6901 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:20.221  6481  6901 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38084bf2
,08-30 17:08:20.221  6481  6901 D BluetoothSocket: channel: 5
,08-30 17:08:20.221   282   726 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 17:08:20.221   282   726 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:08:20.221   282   726 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:08:20.221   282   726 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 17:08:20.221   282   726 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 17:08:20.221   282   726 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:08:20.221   282   726 V audio_hw_primary: adev_set_parameters: exit
08-30 17:08:20.221  6481  6857 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:08:20.231  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:20.231  1015  1213 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:20.231  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.231  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.231  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.231  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:20.241  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:20.241  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:20.251  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:20.251  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:08:20.261  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:20.261  6481  6481 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:08:20.261  1015  3083 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:20.261  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.261  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.261  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:20.261  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:20.271  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:20.271  1015  1219 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:20.271  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:20.281  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.281  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.281  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.291  1015  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 17:08:20.291  1924  6908 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:20.291  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:20.301  1015  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:20.301  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:20.301  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.301  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.311  6481  6911 D BluetoothSocket: bindListen(): myUserId = 0
,08-30 17:08:20.311  6481  6911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:20.311  6481  6911 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-30 17:08:20.311  6481  6911 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:20.311  6481  6911 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:20.311  6481  6911 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304b353e
,08-30 17:08:20.311  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:20.311  6481  6911 D BluetoothSocket: channel: 12
08-30 17:08:20.311  6481  6911 I BtOppRfcommListener: Accept thread started.
,08-30 17:08:20.321  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:20.321  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:20.321  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:20.321  1924  6908 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 17:08:20.481  1015  2806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:21.261  1015  2748 D SSRM:n  : SIOP:: AP = 350
,08-30 17:08:21.571  1015  1317 E Watchdog: !@Sync 4,
,08-30 17:08:21.891  6192  6244 D BluetoothAdapter: disable()
,08-30 17:08:21.891  1015  3083 D SettingsProvider: name = bluetooth_on
,08-30 17:08:21.901  6481  6848 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-30 17:08:21.901  6481  6848 D BluetoothAdapterProperties: Setting state to 13
08-30 17:08:21.901  6481  6848 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 17:08:21.901  6481  6848 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 17:08:21.901  6481  6848 D BluetoothAdapterService: updateAdapterState state is 13
08-30 17:08:21.911  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:21.911  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 17:08:21.911  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:21.911  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:21.911  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:21.911  6481  6481 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 17:08:21.911  6481  6848 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:21.911  6481  6481 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2632bf9f, channel: 19, state: LISTENING
,08-30 17:08:21.911  6481  6481 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2632bf9f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2185d354, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@df838ecmSocket: android.net.LocalSocket@69054b5 impl:android.net.LocalSocketImpl@3e41674a fd:FileDescriptor[75]
08-30 17:08:21.911  6481  6481 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@69054b5 impl:android.net.LocalSocketImpl@3e41674a fd:FileDescriptor[75]
,08-30 17:08:21.911  6481  6848 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 17:08:21.911  6481  6848 D BluetoothAdapterService: terminating service from this receiver
,08-30 17:08:21.911  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:21.911  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-30 17:08:21.921  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:21.921  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 17:08:21.921  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:21.921  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:21.931  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:21.931  1177  1177 D BluetoothTile:  getBluetoothState : 13
,08-30 17:08:21.931  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:21.931  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:21.931  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:21.931  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:21.941  1828  1828 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:21.941  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:21.951  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.951  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:21.951  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.951  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:21.951  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:21.951  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:21.951  1015  1213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:21.951  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:21.951  6481  6848 D BluetoothAdapterProperties: onBluetoothDisable()
,08-30 17:08:21.951  6481  6848 D BluetoothAdapterProperties: mDiscovering is false
,08-30 17:08:21.951  1015  1560 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:21.951  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:21.951  1015  1219 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:21.951  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:21.951  6481  6848 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 17:08:21.961  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:21.961  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:21.961  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:21.961  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:21.961  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:21.961  6192  6192 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 17:08:21.961  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:21.961  1015  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:21.961  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:21.971  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:21.971  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:21.971  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:21.971  1318  1318 D BluetoothPbap: Proxy object disconnected
,08-30 17:08:21.971  1318  1318 D PbapServerProfile: Bluetooth service disconnected
,08-30 17:08:21.981  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:21.981  6481  6851 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:21.981  6481  6851 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:21.981  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:21.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:21.991  6481  6848 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 17:08:21.991  6481  6848 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 17:08:21.991  6481  6848 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 17:08:21.991  6481  6848 E bt-btif : cmd socket is not created
08-30 17:08:21.991  6481  6911 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 17:08:21.991  6481  6848 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 17:08:21.991  6481  6868 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 17:08:21.991  6481  6868 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 17:08:21.991  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:21.991  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:21.991  6481  6868 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 17:08:21.991  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:21.991  6481  6481 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1c8db6bb, channel: 5, state: LISTENING
08-30 17:08:21.991  6481  6481 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1c8db6bb, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38084bf2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@25a5f7d8mSocket: android.net.LocalSocket@223e8731 impl:android.net.LocalSocketImpl@22b6ae16 fd:FileDescriptor[77]
08-30 17:08:21.991  6481  6481 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@223e8731 impl:android.net.LocalSocketImpl@22b6ae16 fd:FileDescriptor[77]
,08-30 17:08:21.991  6481  6481 I BtOppRfcommListener: stopping Accept Thread
08-30 17:08:21.991  6481  6481 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2bd70397, channel: 12, state: LISTENING
08-30 17:08:21.991  6481  6481 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2bd70397, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304b353e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b6eb984mSocket: android.net.LocalSocket@1ac3656d impl:android.net.LocalSocketImpl@d6795a2 fd:FileDescriptor[79]
,08-30 17:08:21.991  6481  6481 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ac3656d impl:android.net.LocalSocketImpl@d6795a2 fd:FileDescriptor[79]
,08-30 17:08:22.001  6481  6911 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 17:08:22.001  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:22.001  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:22.001  6481  6481 V BluetoothOppManager: cleanUp...
08-30 17:08:22.001  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 17:08:22.031  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:22.041  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 17:08:22.191  6481  6868 W bt-btif : ag scb idx 1 not allocated
08-30 17:08:22.191  6481  6868 W bt-btif : ag scb idx 2 not allocated
08-30 17:08:22.191  6481  6868 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 17:08:22.191  6481  6890 I bt_userial_mct: exiting userial_read_thread
08-30 17:08:22.191  6481  6890 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 17:08:22.191  6481  6851 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 17:08:22.191  6481  6870 I bt_vendor: hw_epilog_process
08-30 17:08:22.191  6481  6851 D bt_userial_mct: userial_close
08-30 17:08:22.191  6481  6851 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 17:08:22.961   287   287 E SMD     : DCD OFF
,08-30 17:08:22.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:23.101  6481  6851 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 17:08:23.101  6481  6851 I bt_vendor: bluetooth satus is on
08-30 17:08:23.101  6481  6851 I bt_vendor: bt-vendor : resetting BT status
08-30 17:08:23.101  6481  6851 I bt_vendor: Starting hciattach daemon
08-30 17:08:23.101  6481  6851 I bt_vendor: try to set false
,08-30 17:08:23.101  6481  6851 I bt_vendor: Starting hciattach daemon
08-30 17:08:23.101  6481  6851 I bt_vendor: try to set false
,08-30 17:08:23.101  6481  6851 I bt_vendor: cleanup
,08-30 17:08:23.101  6481  6868 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-30 17:08:23.101  6481  6851 I GKI_LINUX: GKI_exit_task 0 done
,08-30 17:08:23.101  6481  6851 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 17:08:23.101  6481  6848 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 17:08:23.101  6481  6848 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:08:23.111  6481  6848 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 17:08:23.111  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:23.111  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:23.111  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.111  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.111  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.111  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:08:23.111  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:23.111  6481  6481 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:08:23.111  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:23.111  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 17:08:23.111  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.111  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.111  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:23.111  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:23.111  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:23.111  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-30 17:08:23.111  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 17:08:23.111  6481  6481 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 17:08:23.111  6481  6481 D BtGatt.GattService: stop()
08-30 17:08:23.111  6481  6481 D BtGatt.AdvertiseManager: advertise clients cleared,
,08-30 17:08:23.111  1015  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:23.121  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 17:08:23.111  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:23.121  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-30 17:08:23.111  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:23.121  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 17:08:23.121  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:23.121  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 17:08:23.121  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:23.121  1015  1476 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:23.121  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.121  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 17:08:23.121  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-30 17:08:23.121  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:23.121  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-30 17:08:23.121  6481  6481 D HeadsetService: Received stop request...Stopping profile...
,08-30 17:08:23.121  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.131  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-30 17:08:23.131  1015  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:23.131  1318  1318 D HeadsetProfile: Bluetooth service disconnected
08-30 17:08:23.131  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.131  6481  6481 D A2dpService: Received stop request...Stopping profile...
,08-30 17:08:23.131  6481  6862 D A2dpStateMachine: Exit Disconnected: -1
,08-30 17:08:23.131  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.131  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.131  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:23.131  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:23.131  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:23.131  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:23.131  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:23.131  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.131  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.131  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:23.131  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.131  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:23.131  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.131  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.131  6481  6848 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:23.131  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:23.131  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 17:08:23.141  2912  2912 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:23.141  1015  3082 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:23.141  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.141  1318  1318 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:23.141  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:23.141  1318  1318 D A2dpProfile: Bluetooth service disconnected
08-30 17:08:23.141  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.141  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:23.141  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:23.141  1015  3083 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:23.141  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.141  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.141  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.141  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:23.141  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:23.141  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:23.141  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:23.141  6481  6848 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:23.141  6481  6848 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:23.141  6481  6848 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-30 17:08:23.141  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 17:08:23.141  6481  6481 D HidService: Received stop request...Stopping profile...
08-30 17:08:23.141  6481  6481 D HidService: Stopping Bluetooth HidService
08-30 17:08:23.141  6481  6481 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 17:08:23.141  6481  6481 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 17:08:23.141  6481  6481 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 17:08:23.141  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.141  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-30 17:08:23.151  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:23.151  1318  1318 D BluetoothInputDevice: Proxy object disconnected
08-30 17:08:23.151  6481  6481 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 17:08:23.151  1318  1318 D HidProfile: Bluetooth service disconnected
,08-30 17:08:23.151  6481  6481 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-30 17:08:23.151  6481  6481 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 17:08:23.151  6481  6481 D HealthService: Received stop request...Stopping profile...
,08-30 17:08:23.151  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.151  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
08-30 17:08:23.151  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 17:08:23.151  6481  6481 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 17:08:23.151  6481  6481 D PanService: Received stop request...Stopping profile...,
,08-30 17:08:23.151  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:23.151  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 17:08:23.151  1318  1318 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 17:08:23.151  1318  1318 D PanProfile: Bluetooth service disconnected
08-30 17:08:23.151  6481  6481 D BluetoothA2dp: Proxy object disconnected
08-30 17:08:23.151  6481  6481 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 17:08:23.151  6481  6863 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 17:08:23.161  6481  6481 I GKI_LINUX: GKI_exit_task 2 done
08-30 17:08:23.161  6481  6481 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-30 17:08:23.161  6481  6481 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.161  1318  1318 D BluetoothMap: Proxy object disconnected
08-30 17:08:23.161  6481  6481 D SapService: Received stop request...Stopping profile...
08-30 17:08:23.161  6481  6481 D SapService: Stopping Bluetooth SapService
08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:23.161  1318  1318 D MapProfile: Bluetooth service disconnected
,08-30 17:08:23.161  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 17:08:23.161  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:23.161  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 17:08:23.161  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:23.161  6481  6481 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 17:08:23.161  6481  6481 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 17:08:23.161  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 17:08:23.161  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.161  6481  6481 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 17:08:23.161  6481  6481 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 17:08:23.161  1318  1318 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 17:08:23.161  1318  1318 D SapProfile: Bluetooth service disconnected
,08-30 17:08:23.161  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 17:08:23.161  6481  6481 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:23.161  6481  6481 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 17:08:23.161  6481  6481 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-30 17:08:23.171  6481  6481 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 17:08:23.171  6481  6481 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 17:08:23.171  6481  6848 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 17:08:23.171  6481  6848 D BluetoothAdapterProperties: Setting state to 10
08-30 17:08:23.171  6481  6848 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 17:08:23.171  6481  6848 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:23.171  6481  6848 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 17:08:23.171  6481  6848 D BluetoothAdapterService: Autoconnection is available ,
08-30 17:08:23.171  6481  6848 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 17:08:23.171  6481  6848 I BluetoothAdapterState: Entering OffState
,08-30 17:08:23.171  1318  6895 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 17:08:23.171  1318  1336 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:23.171  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:23.171  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:23.171  2912  6894 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:23.171  1177  1862 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:23.171  1177  1862 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.171  1440  6402 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.171  1440  6402 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.171  6351  6361 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.171  6351  6361 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.171  1924  2115 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.171  1924  2115 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.181  1318  1336 D Bluetoothsap: onBluetoothStateChange: up=false
,08-30 17:08:23.181  1318  1336 D Bluetoothsap: Unbinding service...
,08-30 17:08:23.181  1318  1339 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 17:08:23.181  6481  6489 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:23.181  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 17:08:23.181  6481  6899 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.181  6481  6899 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.181  1318  6895 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 17:08:23.181  2912  2926 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.181  2912  2926 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:23.181  1429  1446 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.181  1429  1446 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.181  1318  1336 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 17:08:23.181  1318  1336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.181  6192  6200 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:23.181  6192  6200 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 17:08:23.181  6192  6200 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 17:08:23.181  6192  6200 D BluetoothLeAdvertiser: Exit stop advertising
,08-30 17:08:23.181  6192  6200 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 17:08:23.181  6192  6200 D BluetoothLeScanner: Exiting stopAllScan
,08-30 17:08:23.181  1453  1472 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 17:08:23.181  1453  1472 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 17:08:23.191  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-30 17:08:23.191  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:23.201  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:23.201  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 17:08:23.201  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:23.201  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:23.201  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:23.201  1177  1719 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:23.201  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:23.201  1177  1719 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:23.201  1177  1177 D BluetoothTile:  getBluetoothState : 10
08-30 17:08:23.201  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:23.201  1177  1177 D BluetoothAdapter: 357956394: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:23.201  1015  1219 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-30 17:08:23.201  1828  1828 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:23.201  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:23.201  1924  2124 D BluetoothAdapter: 743929551: getState() :  mService = null. Returning STATE_OFF
08-30 17:08:23.201  1924  2124 D BluetoothAdapter: 743929551: getState() :  mService = null. Returning STATE_OFF
,08-30 17:08:23.201  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:23.211  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:23.211  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:23.211  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:23.211  1015  3083 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:23.211  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.211  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-30 17:08:23.211  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:23.211  1015  3083 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:23.211  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:23.211  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 17:08:23.221  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.221  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.221  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:23.221  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:23.221  6481  6851 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 17:08:23.221  6481  6481 I GKI_LINUX: GKI_exit_task 1 done
08-30 17:08:23.221  6481  6481 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-30 17:08:23.221  6481  6481 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 17:08:23.221  6481  6481 I art     : System.exit called, status: 0
08-30 17:08:23.221  6481  6481 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 17:08:23.231  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:23.231  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:23.241  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:23.241  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 17:08:23.241  1015  1560 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 17:08:23.251  1015  1560 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 17:08:23.251  1015  1560 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-30 17:08:23.251  1015  1560 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-30 17:08:23.251  1015  1560 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:23.251  1015  1560 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 17:08:23.251  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:23.251  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:23.251  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:23.251  1015  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:23.261  6928  6928 E Zygote  : MountEmulatedStorage()
08-30 17:08:23.261  6928  6928 I libpersona: KNOX_SDCARD checking this for 1002
08-30 17:08:23.261  6928  6928 E Zygote  : v2
08-30 17:08:23.261  6928  6928 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:23.261  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:23.271  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 17:08:23.271  1015  1560 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6928 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-30 17:08:23.271  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:23.291  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:23.291  6928  6928 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:23.301  6928  6928 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 17:08:23.301  6928  6928 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:23.331  6928  6928 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding GattService
,08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding A2dpService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding HidService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding HealthService
,08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding PanService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding SapService
,08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding SapClientService
08-30 17:08:23.361  6928  6928 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 17:08:23.361  6928  6928 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 17:08:23.371  1015  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 17:08:23.371  1015  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1219 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  1219 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  1219 D SettingsProvider: ret = -1
,08-30 17:08:23.371  1015  5585 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 17:08:23.371  1015  5585 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  5585 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  5585 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  5585 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  5585 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  5585 D SettingsProvider: ret = -1
,08-30 17:08:23.371  1015  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 17:08:23.371  1015  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:23.371  1015  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1560 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  1560 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  1560 D SettingsProvider: ret = -1
,08-30 17:08:23.371  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 17:08:23.371  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 17:08:23.371  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1216 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  1216 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:23.371  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  1216 D SettingsProvider: ret = -1
,08-30 17:08:23.371  1015  1213 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-30 17:08:23.371  1015  1213 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  1213 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1213 D SettingsProvider: selectionArgs: false,
08-30 17:08:23.371  1015  1213 D SettingsProvider: selectionArgs: 1002,
08-30 17:08:23.371  1015  1213 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-30 17:08:23.371  1015  1213 D SettingsProvider: ret = -1
08-30 17:08:23.371  1015  3083 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 17:08:23.371  1015  3083 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  3083 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  3083 D SettingsProvider: selectionArgs: false
,08-30 17:08:23.371  1015  3083 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  3083 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-30 17:08:23.371  1015  3083 D SettingsProvider: ret = -1
08-30 17:08:23.371  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 17:08:23.371  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1475 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  1475 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:23.371  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  1475 D SettingsProvider: ret = -1
08-30 17:08:23.371  1015  1027 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 17:08:23.371  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  1027 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:23.371  1015  1027 D SettingsProvider: ret = -1
08-30 17:08:23.371  1015  3085 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:23.371  1015  3085 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.371  1015  3085 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.371  1015  3085 D SettingsProvider: selectionArgs: false
08-30 17:08:23.371  1015  3085 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.371  1015  3085 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.371  1015  3085 D SettingsProvider: ret = -1
,08-30 17:08:23.381  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:23.381  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.381  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.381  1015  1028 D SettingsProvider: selectionArgs: false
08-30 17:08:23.381  1015  1028 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.381  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.381  1015  1028 D SettingsProvider: ret = -1
08-30 17:08:23.381  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:23.381  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.381  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.381  1015  1476 D SettingsProvider: selectionArgs: false
08-30 17:08:23.381  1015  1476 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.381  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:23.381  1015  1476 D SettingsProvider: ret = -1
08-30 17:08:23.381  1015  3082 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-30 17:08:23.381  1015  3082 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:23.381  1015  3082 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:23.381  1015  3082 D SettingsProvider: selectionArgs: false
08-30 17:08:23.381  1015  3082 D SettingsProvider: selectionArgs: 1002
08-30 17:08:23.381  1015  3082 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:23.381  1015  3082 D SettingsProvider: ret = -1
,08-30 17:08:23.391  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:23.391  1015  1560 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:23.391  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:23.391  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:23.391  1015  1560 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:23.391  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:23.401  1924  6944 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 17:08:23.401  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:23.411  1015  5585 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 17:08:23.411  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:23.411  1015  5585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:23.411  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:23.421  1924  6944 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 17:08:23.981   312   312 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 17:08:24.901  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 17:08:24.901  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:24.991   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:25.681  1015  1977 V SAMP_SPCM_test: CSC File load.. ,
,08-30 17:08:25.691  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-30 17:08:25.691  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-30 17:08:25.691  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,08-30 17:08:25.691  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-30 17:08:25.691  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location,
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn,
08-30 17:08:25.701  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 17:08:25.741  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-30 17:08:25.751  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time,
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling,
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn,
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 17:08:25.761  1015  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-30 17:08:25.771  1015  1977 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-30 17:08:25.971   287   287 E SMD     : DCD OFF
,08-30 17:08:25.991   312   312 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 17:08:26.991   312   312 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-30 17:08:27.911  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:27.911  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1654e8cb added. We now have 6 listener(s)
,08-30 17:08:27.911  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:27.911  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:27.911  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@391728a8 added. We now have 7 listener(s)
,08-30 17:08:27.911  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:27.911  6192  6244 I System.out: IsBluetoothEnabled
,08-30 17:08:27.911  6192  6244 D BluetoothAdapter: disable()
,08-30 17:08:27.921  1015  3082 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 17:08:27.921  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:27.921  6192  6244 D BluetoothAdapter: enable()
,08-30 17:08:27.921  1015  3083 W ActivityManager: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 17:08:27.921  1015  3083 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 17:08:27.921  1015  3083 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:27.921  1015  3083 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:27.921  1015  3083 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:27.921  1015  3083 D SettingsProvider: name = bluetooth_on
,08-30 17:08:27.931  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 17:08:27.931  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:27.941  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-30 17:08:27.941  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 17:08:27.961  6928  6928 D BluetoothAdapterState: make
,08-30 17:08:27.961  6928  6928 I bluedroid: init
,08-30 17:08:27.961  6928  6951 I BluetoothAdapterState: Entering OffState
,08-30 17:08:27.971  6928  6928 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 17:08:27.971  6928  6928 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 17:08:27.971  6928  6928 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 17:08:27.971  6928  6928 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 17:08:27.971  6928  6928 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-30 17:08:27.971  6928  6928 I bluedroid: get_profile_interface socket
,08-30 17:08:27.971  6928  6928 I bluedroid: get_profile_interface map_client
,08-30 17:08:27.971  6928  6954 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 17:08:27.971  6928  6928 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 17:08:27.981  6928  6954 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB,
08-30 17:08:27.981  6928  6954 E BluetoothServiceJni: populateRssiValuesNative
08-30 17:08:27.981  6928  6954 I bluedroid: getModelRssiValues
08-30 17:08:27.981  6928  6954 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:08:27.981  6928  6954 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:27.981  6928  6954 D BluetoothAdapterProperties: Name is: A5-1
,08-30 17:08:27.981  6928  6928 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:27.981  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 17:08:27.981  1015  1219 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:27.991  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:27.991  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:27.991  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:27.991  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:27.991  6928  6936 I bluedroid: config_hci_snoop_log
,08-30 17:08:27.991  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 17:08:28.001  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-30 17:08:28.001  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 17:08:28.001  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 17:08:28.001  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:28.001  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:28.001  6928  6928 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-30 17:08:28.001  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 17:08:28.011  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 17:08:28.011  6928  6951 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 17:08:28.011  6928  6951 D BluetoothAdapterProperties: Setting state to 11
,08-30 17:08:28.011  6928  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 17:08:28.011  6928  6951 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:28.011  6928  6951 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 17:08:28.011  6928  6951 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:28.011  6928  6951 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 17:08:28.021  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.021  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-30 17:08:28.021  6928  6951 D BluetoothSecureManager: getInstant: null
08-30 17:08:28.021  6928  6951 D BluetoothSecureManager: calling getMethod for getService
08-30 17:08:28.021  6928  6951 D BluetoothSecureManager: calling getService
,08-30 17:08:28.021  6928  6951 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3bc18d30
,08-30 17:08:28.021  1015  3082 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 17:08:28.021  1015  3082 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 17:08:28.021  6928  6951 D BtConfig.SecureMode: isSecureModeOn:false
08-30 17:08:28.021  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 17:08:28.021  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 17:08:28.021  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:28.021  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 17:08:28.021  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:28.021  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 17:08:28.021  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 17:08:28.031  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 17:08:28.031  1177  1177 D BluetoothTile:  getBluetoothState : 11
08-30 17:08:28.031  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:28.031  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
08-30 17:08:28.031  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:28.031  1828  1828 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:28.031  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:28.031  6928  6951 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:28.031  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 17:08:28.031  1015  1213 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 17:08:28.031  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 17:08:28.041  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:28.041  6928  6951 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:28.041  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 17:08:28.041  6928  6951 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 17:08:28.041  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:28.041  6928  6951 D BluetoothBondStateMachine: make
,08-30 17:08:28.041  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 17:08:28.041  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 17:08:28.041  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 17:08:28.041  6928  6956 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 17:08:28.041  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:28.041  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.041  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 17:08:28.051  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.051  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:28.051  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:28.051  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:28.051  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:28.051  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.051  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.051  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.051  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.051  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 17:08:28.051  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 17:08:28.051  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 17:08:28.051  6928  6928 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 17:08:28.061  6928  6928 D BtGatt.GattService: Received start request. Starting profile...
08-30 17:08:28.061  6928  6928 D BtGatt.GattService: start()
08-30 17:08:28.061  6928  6928 D BtGatt.GattService: start()
08-30 17:08:28.061  6928  6928 I bluedroid: get_profile_interface gatt
,08-30 17:08:28.061  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:28.061  6928  6928 D BtGatt.AdvertiseManager: advertise manager created
,08-30 17:08:28.061  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:28.061  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 17:08:28.061  1015  3085 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:28.061  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.061  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.061  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.061  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.071  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 17:08:28.071  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 17:08:28.071  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 17:08:28.071  1015  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:28.071  1015  1560 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.071  1015  1560 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:28.071  1015  1560 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.071  1015  1560 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.081  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 17:08:28.081  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 17:08:28.081  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 17:08:28.081  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:28.081  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.081  6928  6928 D BtGatt.GattService: mStartError = false
08-30 17:08:28.081  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.081  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:28.081  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.081  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.081  6928  6928 D HeadsetService: Received start request. Starting profile...
,08-30 17:08:28.081  6928  6928 D HeadsetService: start()
,08-30 17:08:28.091  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-30 17:08:28.091  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 17:08:28.091  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 17:08:28.091  6928  6928 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 17:08:28.091  6928  6928 D HeadsetStateMachine: make
,08-30 17:08:28.091  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:28.091  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.091  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:28.091  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.091  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.091  6928  6928 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 17:08:28.091  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 17:08:28.091  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 17:08:28.091  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 17:08:28.091  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:28.091  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.091  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.091  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.091  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.101  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:28.101  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 17:08:28.101  6928  6951 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 17:08:28.101  1015  5585 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:28.101  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.101  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.101  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.101  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.111  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 17:08:28.111  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 17:08:28.111  6928  6951 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 17:08:28.111  1015  3082 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 17:08:28.111  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.111  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:28.111  1015  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.111  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 17:08:28.111  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:28.111  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.111  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.111  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.111  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:28.111  1015  1475 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 17:08:28.111  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.111  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:28.111  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:28.111  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:28.121  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 17:08:28.121  6928  6928 I bluedroid: get_profile_interface handsfree
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:28.121  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 17:08:28.121  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 17:08:28.121  6928  6951 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 17:08:28.121  6928  6951 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 17:08:28.121  6928  6951 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 17:08:28.131  6928  6928 I DualScoManager: Instantiating Dual Sco Manager
08-30 17:08:28.131  6928  6928 I DualScoManager: Set HeadsetServiceHelper
,08-30 17:08:28.131  6928  6928 D BluetoothAtMessage: createCMTIContentObservers
,08-30 17:08:28.131  1015  3083 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-30 17:08:28.131  1015  3083 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:28.131  1015  3083 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 17:08:28.131  1015  3083 D SettingsProvider: selectionArgs: false
,08-30 17:08:28.131  1015  3083 D SettingsProvider: selectionArgs: 1002
08-30 17:08:28.131  1015  3083 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 17:08:28.131  1015  3083 D SettingsProvider: ret = -1
,08-30 17:08:28.141  6928  6960 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 17:08:28.141  6928  6928 D HeadsetService: mStartError = false
08-30 17:08:28.141  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.141  6928  6928 D A2dpService: Received start request. Starting profile...
,08-30 17:08:28.141  6928  6928 D A2dpService: start()
08-30 17:08:28.141  6928  6960 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 17:08:28.141  6928  6960 D HeadsetStateMachine: map size, before remove : 0
08-30 17:08:28.141  6928  6960 D HeadsetStateMachine: map size, after remove: 0
,08-30 17:08:28.141  6928  6928 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 17:08:28.141  6928  6928 I bluedroid: get_profile_interface avrcp
,08-30 17:08:28.151  6928  6928 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 17:08:28.161  6928  6928 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 17:08:28.161  6928  6964 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 17:08:28.171  6928  6928 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 17:08:28.171  6928  6928 D A2dpStateMachine: make
,08-30 17:08:28.171  6928  6928 I bluedroid: get_profile_interface a2dp
,08-30 17:08:28.171  6928  6966 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 17:08:28.171  6928  6928 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 17:08:28.171  6928  6928 D A2dpService: mStartError = false
08-30 17:08:28.171  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.171  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 17:08:28.171  6928  6928 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 17:08:28.171  6928  6928 D HidService: Received start request. Starting profile...
08-30 17:08:28.171  6928  6928 D HidService: start()
08-30 17:08:28.181  6928  6928 I bluedroid: get_profile_interface hidhost
08-30 17:08:28.181  6928  6928 D HidService: setHidService(): set to: null
08-30 17:08:28.181  6928  6928 D HidService: mStartError = false
08-30 17:08:28.181  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.181  6928  6965 D A2dpStateMachine: Enter Disconnected: -2
08-30 17:08:28.181  6928  6928 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 17:08:28.181  6928  6928 D HealthService: Received start request. Starting profile...
08-30 17:08:28.181  6928  6928 D HealthService: start()
,08-30 17:08:28.181  6928  6928 I bluedroid: get_profile_interface health
,08-30 17:08:28.181  6928  6928 D HealthService: mStartError = false
08-30 17:08:28.181  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.181  6928  6928 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 17:08:28.181  6928  6928 D PanService: Received start request. Starting profile...
08-30 17:08:28.181  6928  6928 D PanService: start()
08-30 17:08:28.191  6928  6928 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 17:08:28.191  6928  6928 I bluedroid: get_profile_interface pan
,08-30 17:08:28.191  6928  6928 D PanService: mStartError = false
08-30 17:08:28.191  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.191  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 17:08:28.191  6928  6928 D BluetoothMapService: Received start request. Starting profile...
,08-30 17:08:28.191  6928  6928 D BluetoothMapService: start()
,08-30 17:08:28.191  6928  6928 D BluetoothMapService: mStartError = false
,08-30 17:08:28.191  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:28.191  6928  6928 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 17:08:28.191  1429  1446 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 17:08:28.191  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 17:08:28.201  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 17:08:28.201  1429  1446 I Telecom : BluetoothPhoneService: Result of Message : true
,08-30 17:08:28.201  6928  6928 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 17:08:28.201  6928  6928 D SapService: Received start request. Starting profile...
08-30 17:08:28.201  6928  6928 D SapService: start()
08-30 17:08:28.201  6928  6928 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 17:08:28.201  6928  6928 I bluedroid: get_profile_interface sap
08-30 17:08:28.201  6928  6928 D SapService: mStartError = false
08-30 17:08:28.201  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
08-30 17:08:28.201  6928  6928 D HeadsetStateMachine: Proxy object connected
,08-30 17:08:28.201  6928  6928 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-30 17:08:28.201  6928  6928 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 17:08:28.201  6928  6928 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-30 17:08:28.201  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 17:08:28.201  6928  6928 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 17:08:28.201  6928  6928 D BluetoothA2dp: Proxy object connected
08-30 17:08:28.201  6928  6928 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 17:08:28.201  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 17:08:28.201  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-30 17:08:28.201  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 17:08:28.201  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 17:08:28.201  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 17:08:28.201  6928  6960 D HeadsetStateMachine: Disconnected process message: 11
08-30 17:08:28.201  6928  6960 D HeadsetStateMachine: Disconnected process message: 18
,08-30 17:08:28.201  6928  6960 D HeadsetStateMachine: Disconnected process message: 10
08-30 17:08:28.201  6928  6960 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,08-30 17:08:28.201  6928  6960 D HeadsetStateMachine: Disconnected process message: 11
,08-30 17:08:28.211  6928  6964 D BluetoothMediaBrowser: no now playing list
,08-30 17:08:28.211  6928  6964 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 17:08:28.231  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 17:08:28.231  6928  6928 E BluetoothAdapterService(619386619): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 17:08:28.231  6928  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 17:08:28.231  6928  6951 I bluedroid: enable
,08-30 17:08:28.231  6928  6951 I bt_hci_bdroid: init
,08-30 17:08:28.241  6928  6970 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 17:08:28.241  6928  6951 I bt_vendor: bt-vendor : init
08-30 17:08:28.241  6928  6951 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 17:08:28.241  6928  6951 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 17:08:28.241  6928  6951 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-30 17:08:28.241  6928  6951 D bt_userial_mct: userial_init
,08-30 17:08:28.241  6928  6951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 17:08:28.241  6928  6951 I bt_vendor: Starting hciattach daemon
08-30 17:08:28.241  6928  6951 I bt_vendor: try to set false
,08-30 17:08:28.241  6928  6951 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 17:08:28.241  6928  6951 I bt_vendor: Starting hciattach daemon
08-30 17:08:28.241  6928  6951 I bt_vendor: try to set true
,08-30 17:08:28.261  6974  6974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 17:08:28.311  6980  6980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 17:08:28.321  6981  6981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:28.341  6983  6983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 17:08:28.351  6984  6984 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 17:08:28.351  6985  6985 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 17:08:28.361  6986  6986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 17:08:28.751  6989  6989 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 17:08:28.761  6990  6990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 17:08:28.801  6928  6951 I bt_vendor: bluetooth satus is on,
08-30 17:08:28.801  6928  6972 D bt_userial_mct: userial_open(port:0)
08-30 17:08:28.801  6928  6972 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,08-30 17:08:28.801  6928  6972 I bt_vendor: Done intiailizing UART,
,08-30 17:08:28.801  6928  6972 I bt_vendor: Done intiailizing UART,
,08-30 17:08:28.801  6928  6972 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 17:08:28.801  6928  6972 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 17:08:28.811  6928  6992 D bt_userial_mct: Entering userial_read_thread()
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_BTM
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_GATT
,08-30 17:08:28.811  6928  6970 I         : BTE_InitTraceLevels -- TRC_SMP
08-30 17:08:28.821  6928  6970 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-30 17:08:28.821  6928  6970 I         : BTE_InitTraceLevels -- TRC_BTIF
08-30 17:08:28.821  6928  6970 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 17:08:28.921  6928  6970 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 17:08:28.921  6928  6970 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa405a6e9 
,08-30 17:08:28.921  6928  6970 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa405a6e9 
,08-30 17:08:28.941  6928  6954 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 17:08:28.941  6928  6954 E bt-btif : Calling BTA_HhEnable
,08-30 17:08:28.951  6928  6954 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 17:08:28.951  6928  6954 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 17:08:28.951  6928  6954 E BluetoothServiceJni: populateRssiValuesNative
,08-30 17:08:28.951  6928  6954 I bluedroid: getModelRssiValues
08-30 17:08:28.951  6928  6954 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 17:08:28.951  6928  6954 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 17:08:28.951  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 17:08:28.951  6928  6954 D BluetoothAdapterProperties: Name is: A5-1
,08-30 17:08:28.961  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:28.961  6928  6954 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 17:08:28.961  6928  6954 D BluetoothAdapterProperties: Scan Mode:20
,08-30 17:08:28.961  6928  6954 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:28.961  6928  6954 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-30 17:08:28.961  6928  6954 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-30 17:08:28.971  6928  6954 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-30 17:08:28.971   287   287 E SMD     : DCD OFF
,08-30 17:08:28.971  6928  6954 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 17:08:28.971  6928  6954 E bt-btif : btif_sock_init: !vhci_init
08-30 17:08:28.971  6928  6954 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-30 17:08:28.971  6928  6954 D IOP_DB_BT: db_open: db_open : handle 3028217872l, read 13894 bytes onto local cache
08-30 17:08:28.971  6928  6954 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-30 17:08:28.971  6928  6954 D IOP_DB_BT: db_query: result 1
08-30 17:08:28.971  6928  6954 I         : iop_db_open: iop_db_open status 0
08-30 17:08:28.971  6928  6954 D bte_conf: Device ID record 1 : primary
08-30 17:08:28.971  6928  6954 D bte_conf:   vendorId            = 0075
08-30 17:08:28.971  6928  6954 D bte_conf:   vendorIdSource      = 0001
08-30 17:08:28.971  6928  6954 D bte_conf:   product             = 0100
08-30 17:08:28.971  6928  6954 D bte_conf:   version             = 0200
08-30 17:08:28.971  6928  6954 D bte_conf:   clientExecutableURL = 
08-30 17:08:28.971  6928  6954 D bte_conf:   serviceDescription  = 
,08-30 17:08:28.971  6928  6954 D bte_conf:   documentationURL    = 
08-30 17:08:28.971  6928  6954 D bte_conf: bte_load_did_conf no section named DID2.
08-30 17:08:28.971  6928  6954 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 17:08:28.971  6928  6951 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 17:08:28.971  6928  6951 D BluetoothAdapterProperties: ScanMode =  20
,08-30 17:08:28.971  6928  6992 E bt_mct  : hci lib postload completed
,08-30 17:08:28.971  6928  6951 D BluetoothAdapterProperties: State =  11
,08-30 17:08:28.981  1015  5585 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 17:08:28.981  6928  6951 D BluetoothAdapterProperties: Setting state to 12
,08-30 17:08:28.981  6928  6951 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 17:08:28.981  6928  6954 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 17:08:28.981  6928  6954 D BluetoothAdapterProperties: Scan Mode:21
08-30 17:08:28.981  6928  6954 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 17:08:28.981  1015  1470 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 17:08:28.981  1015  1470 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 17:08:28.981  1015  1470 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 17:08:28.991  1015  1470 D SettingsProvider: selectionArgs: false
08-30 17:08:28.991  1015  1470 D SettingsProvider: selectionArgs: 1002
,08-30 17:08:28.991  1015  1470 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 17:08:28.991  1015  1470 D SettingsProvider: ret = -1
08-30 17:08:28.991  6928  6951 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 17:08:28.991  6928  6951 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 17:08:28.991  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:28.991  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:28.991  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:28.991  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:28.991  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:29.001  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:29.001  6928  6951 D BluetoothAdapterService: Autoconnection is available 
,08-30 17:08:29.001  6928  6951 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 17:08:29.001  6928  6951 D BluetoothAdapterService: starting service from this receiver
,08-30 17:08:29.001  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 17:08:29.001  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.001  6928  6936 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:29.001  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.001  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.001  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.001  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.011  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.011  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.011  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.011  6928  6951 I BluetoothAdapterState: Entering On State from state = 11
,08-30 17:08:29.011  2912  2926 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.021  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:29.031  6928  6928 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 17:08:29.171  1015  1044 I art     : Explicit concurrent mark sweep GC freed 32619(1908KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.431ms total 158.852ms
08-30 17:08:29.171  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.171  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.171  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.171  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.171  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.171  2912  2926 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.181  1318  1336 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 17:08:29.181  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 17:08:29.181  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.181  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.181  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.181  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.181  1318  1339 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:29.181  1318  1339 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.181  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:08:29.181  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.181  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.181  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.181  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.181  1318  1318 D BluetoothA2dp: Proxy object connected,
08-30 17:08:29.181  1318  1318 D A2dpProfile: Bluetooth service connected
,08-30 17:08:29.191  1318  6895 D BluetoothPan: Binding service...
,08-30 17:08:29.191  6928  6928 I BluetoothPbapService: Handler(): got msg=1
,08-30 17:08:29.191  1015  1470 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-30 17:08:29.191  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:29.191  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.191  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.191  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.191  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.191  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.191  1318  1318 D BluetoothInputDevice: Proxy object connected
08-30 17:08:29.191  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.191  1318  1318 D HidProfile: Bluetooth service connected
08-30 17:08:29.191  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.201  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.201  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.201  1429  6898 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.201  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.201  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.201  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.201  1429  6898 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 17:08:29.201  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.201  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:29.201  2912  2922 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 17:08:29.201  6928  6997 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 17:08:29.201  1318  1318 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:29.201  1318  1318 D PanProfile: Bluetooth service connected
08-30 17:08:29.201  2912  2922 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.201  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 17:08:29.201  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.201  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.201  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-30 17:08:29.201  6928  6997 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:29.201  6928  6997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 17:08:29.201  2912  2912 D BluetoothA2dp: Proxy object connected
,08-30 17:08:29.201  6928  6997 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 17:08:29.201  6928  6997 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:29.201  6928  6997 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:29.201  6928  6997 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2185d354
,08-30 17:08:29.201  6928  6997 D BluetoothSocket: channel: 19
08-30 17:08:29.201  6928  6997 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 17:08:29.211  1318  6895 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:29.211  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.211  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.211  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.211  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.211  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.211  1318  6895 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.211  1318  1318 D HeadsetProfile: Bluetooth service connected
,08-30 17:08:29.211  1453  2436 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.211  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 17:08:29.211  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.211  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.211  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.211  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.211  1453  2436 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.211  1177  1873 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:29.211  1177  1873 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.211  1440  6402 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.211  1440  6402 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.211  6351  6362 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:29.221  6351  6362 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on,
,08-30 17:08:29.221  1924  2112 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:29.221  1924  2112 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:29.221  1318  1339 D Bluetoothsap: onBluetoothStateChange: up=true
,08-30 17:08:29.221  1318  1339 D Bluetoothsap: Binding service...
,08-30 17:08:29.221  1318  1339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 17:08:29.221  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 17:08:29.221  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.221  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.221  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.221  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.221  1318  1339 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 17:08:29.221  1318  1318 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 17:08:29.221  1015  1044 D BluetoothPan: Binding service...
,08-30 17:08:29.231  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 17:08:29.231  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 17:08:29.231  1318  1318 D SapProfile: Bluetooth service connected
,08-30 17:08:29.231  1318  1318 D Bluetoothsap: getConnectedDevices()
08-30 17:08:29.231  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 17:08:29.231  1318  6895 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 17:08:29.231  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 17:08:29.231  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.231  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.231  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.231  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.231  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 17:08:29.231  1318  1318 D BluetoothPbap: Proxy object connected
08-30 17:08:29.231  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 17:08:29.231  1318  1318 D PbapServerProfile: Bluetooth service connected
08-30 17:08:29.231  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 17:08:29.231  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.231  6928  6937 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.231  6928  6937 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 17:08:29.231  1015  1015 D BluetoothA2dp: Proxy object connected
,08-30 17:08:29.231  1318  6895 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 17:08:29.231  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 17:08:29.231  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.231  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.231  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.231  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.231  2912  2926 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.231  2912  2926 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.241  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.241  1429  1437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.241  1318  1318 D BluetoothMap: Proxy object connected
08-30 17:08:29.241  1318  1318 D MapProfile: Bluetooth service connected
08-30 17:08:29.241  1318  1318 D BluetoothMap: getConnectedDevices()
08-30 17:08:29.241  1318  1336 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 17:08:29.241  1318  1336 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.241  6192  6201 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:29.241  6192  6201 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.241  1429  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 17:08:29.241  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 17:08:29.241  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 17:08:29.241  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:29.241  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.241  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.241  1429  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 17:08:29.241  1453  1472 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 17:08:29.241  1453  1472 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 17:08:29.241  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 17:08:29.241  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 17:08:29.251  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-30 17:08:29.251  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-30 17:08:29.251  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 17:08:29.251  1177  1177 D BluetoothTile:  onBluetoothStateChange:
,08-30 17:08:29.251  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@e5b6390, true
08-30 17:08:29.251  1177  1177 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 17:08:29.251  1177  1177 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 17:08:29.251  1177  1177 D BluetoothTile:  getBluetoothState : 12
08-30 17:08:29.261  1429  1429 D BluetoothHeadset: registerMessageListener
,08-30 17:08:29.261  1828  1828 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 17:08:29.261  1015  3085 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:29.261  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:29.261  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:29.261  1015  3083 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 17:08:29.261  1177  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 17:08:29.261  1177  1177 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 17:08:29.271  1318  1318 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:29.271  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:29.271  1015  1213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 17:08:29.271  1015  1213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.271  6928  6955 D HeadsetService: registerMessageListener
08-30 17:08:29.271  6928  6955 D HeadsetService: registerMessageListener
08-30 17:08:29.271  6928  6960 D HeadsetStateMachine: Disconnected process message: 70
,08-30 17:08:29.271  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 17:08:29.271  6928  6960 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1356c2fd
08-30 17:08:29.271  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 17:08:29.271  1015  1213 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.271  1015  1213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:29.271  1015  1213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:29.281  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 17:08:29.281  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 17:08:29.281  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 17:08:29.281  1318  1318 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-30 17:08:29.281  6928  6960 D HeadsetStateMachine: Disconnected process message: 9
,08-30 17:08:29.281  6928  6960 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-30 17:08:29.281  1318  1318 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 17:08:29.281  1318  1318 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 17:08:29.281  1318  1318 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-30 17:08:29.281  6928  6998 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 17:08:29.291   282   695 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-30 17:08:29.291   282   695 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 17:08:29.291   282   695 V voice   : voice_set_parameters: exit with code(-2)
08-30 17:08:29.291   282   695 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-30 17:08:29.291   282   695 V msm8974_platform: platform_set_parameters: exit with code(-2)
,08-30 17:08:29.291   282   695 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 17:08:29.291   282   695 V audio_hw_primary: adev_set_parameters: exit
08-30 17:08:29.291  6928  6998 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:29.291  6928  6998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:29.291  6928  6960 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 17:08:29.291  1318  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 17:08:29.301  1015  1219 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 17:08:29.301  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.301  6928  6998 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-30 17:08:29.301  6928  6998 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:29.301  6928  6998 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:29.301  6928  6998 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38084bf2
08-30 17:08:29.301  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.301  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.301  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 17:08:29.301  6928  6998 D BluetoothSocket: channel: 5
,08-30 17:08:29.311  1318  1318 D DockEventReceiver: finishStartingService: stopping service
,08-30 17:08:29.311  1318  1318 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 17:08:29.311  1177  1177 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 17:08:29.311  1177  1177 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 17:08:29.321  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:29.321  6928  6928 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 17:08:29.321  1015  1470 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 17:08:29.321  1015  1470 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 17:08:29.321  1015  1470 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.321  1015  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:29.321  1015  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 17:08:29.341  1924  1924 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 17:08:29.341  1015  3082 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 17:08:29.341  1015  3082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-30 17:08:29.341  1015  3082 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.341  1015  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:29.341  1015  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:29.351  1015  1028 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-30 17:08:29.351  1924  1924 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 17:08:29.351  1924  7007 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-30 17:08:29.361  1015  3085 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 17:08:29.361  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.361  1015  3085 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:29.361  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 17:08:29.361  6928  7008 D BluetoothSocket: bindListen(): myUserId = 0
08-30 17:08:29.361  6928  7008 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 17:08:29.371  6928  7008 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-30 17:08:29.371  6928  7008 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 17:08:29.371  6928  7008 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 17:08:29.371  6928  7008 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@304b353e
08-30 17:08:29.371  6928  7008 D BluetoothSocket: channel: 12
08-30 17:08:29.371  6928  7008 I BtOppRfcommListener: Accept thread started.
08-30 17:08:29.371  1015  5585 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 17:08:29.381  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:29.381  1015  5585 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 17:08:29.381  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 17:08:29.391  1924  7007 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 17:08:29.431  1015  3085 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 17:08:29.431  1015  3085 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3937, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 17:08:29.431  1015  3085 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 17:08:29.431  1015  3085 D BatteryService: stay LED for charging
08-30 17:08:29.431  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 17:08:29.431  1015  1015 I MotionRecognitionService: Plugged
,08-30 17:08:29.431  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 17:08:29.441  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 17:08:29.441  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 17:08:29.441  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 17:08:29.441  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,08-30 17:08:29.451  6928  6928 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 17:08:29.451  6928  6960 D HeadsetStateMachine: Disconnected process message: 10
,08-30 17:08:29.461  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:08:29.461  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:08:29.461  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:29.941  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:29.941  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:29.941  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:29.951  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@372fafc1 added. We now have 8 listener(s)
08-30 17:08:29.951  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:29.951  1015  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 17:08:29.951  1015  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-30 17:08:29.951  1015  1475 D SecContentProvider2: mCursor = null
,08-30 17:08:29.951  1015  1475 D WifiService: setWifiEnabled: false pid=6192, uid=10155
,08-30 17:08:29.951  1015  1475 D SettingsProvider: name = wifi_on
,08-30 17:08:29.961  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:08:29.961  1015  1213 D WifiService: setWifiEnabled: true pid=6192, uid=10155
,08-30 17:08:29.961  1015  1213 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 17:08:29.961  1015  1213 W ActivityManager: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:29.961  1015  1213 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 17:08:29.961  1015  1213 D SecContentProvider2: mCursor = null
08-30 17:08:29.961  1015  1213 W WifiService: Failed getting userId using ActivityManagerNative
08-30 17:08:29.961  1015  1213 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6192, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 17:08:29.961  1015  1213 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 17:08:29.961  1015  1213 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
,08-30 17:08:29.961  1015  1213 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 17:08:29.961  1015  1213 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 17:08:29.961  1015  1213 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 17:08:29.961  1015  1213 D SettingsProvider: name = wifi_on
,08-30 17:08:29.971  1015  1130 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 17:08:30.331  1015  1042 D Tethering: interfaceAdded wlan0
,08-30 17:08:30.341  1015  1133 E Tethering: No numeric data
,08-30 17:08:30.341  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:30.341  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:30.341  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:30.341  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.351  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:30.351  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-30 17:08:30.351  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 17:08:30.351  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-30 17:08:30.351  1177  1177 D HotspotTile: updateTetherState():false, false,
,08-30 17:08:30.351  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-30 17:08:30.351  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:30.351  1015  1133 D Tethering: InitialState.processMessage what=4
08-30 17:08:30.361  1015  1123 V NetworkStats: performPollLocked() took 15ms,
08-30 17:08:30.361  1015  1133 E Tethering: No numeric data
08-30 17:08:30.361  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 17:08:30.361  1015  1133 D Tethering: clearTetheredNotification()
08-30 17:08:30.361  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.361  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:30.361  1177  1177 D HotspotTile: updateTetherState():false, false
,08-30 17:08:30.361  1015  1042 D Tethering: interfaceAdded p2p0
,08-30 17:08:30.371  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-30 17:08:30.371  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-30 17:08:30.371  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:30.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:30.371  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.371  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.381  1015  1123 V NetworkStats: performPollLocked() took 10ms
08-30 17:08:30.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.381  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:30.381  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:30.381  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:30.391   277   951 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
,08-30 17:08:30.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:30.391  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:30.391   277   951 D SoftapController: Softap fwReload - Ok
,08-30 17:08:30.391   277   951 D CommandListener: Setting iface cfg
,08-30 17:08:30.391   277   951 D CommandListener: Trying to bring down wlan0
,08-30 17:08:30.401   277   951 D CommandListener: Clearing all IP addresses on wlan0
,08-30 17:08:30.411  1015  1130 E WifiHW  : supplicant_name : p2p_supplicant
,08-30 17:08:30.451  7022  7022 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-30 17:08:30.451  7022  7022 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 17:08:30.451  7022  7022 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 17:08:30.471  7022  7022 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-30 17:08:30.471   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7022
08-30 17:08:30.471   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 17:08:30.471  7022  7022 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-30 17:08:30.471  7022  7022 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:30.471  7022  7022 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 17:08:30.471  7022  7022 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 17:08:30.471   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7022,
08-30 17:08:30.471   348   348 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-30 17:08:30.511  1015  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 17:08:30.521  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:30.521  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 17:08:30.521  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.521  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.521  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.521  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:30.521  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:30.521  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 17:08:30.521  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:30.521  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-30 17:08:30.521  1177  1177 D HotspotTile: onReceive : 2, 0
,08-30 17:08:30.531  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:30.531  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-30 17:08:30.541  1015  3085 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:30.541  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:30.541  1015  3085 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:30.541  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:30.541  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-30 17:08:30.551  3640  3640 I Hs20UtilService: Starting #19
,08-30 17:08:30.551  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:30.551  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:30.551  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:30.551  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:30.551  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 17:08:30.651   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-30 17:08:30.651  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-30 17:08:30.721  7022  7022 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:08:30.721  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 17:08:30.731  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-30 17:08:30.731   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7022
08-30 17:08:30.731   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-30 17:08:30.731  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 17:08:30.731  7022  7022 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:30.731  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:30.731  7022  7022 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 17:08:30.731  7022  7022 E wpa_supplicant: SIM READ ERROR
08-30 17:08:30.731  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:30.731  7022  7022 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:30.731  7022  7022 E wpa_supplicant: SIM READ ERROR
08-30 17:08:30.731  7022  7022 I wpa_supplicant: Blacklist: Clear (all) ,
08-30 17:08:30.731  7022  7022 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:30.731  7022  7022 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:30.731  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:30.731  7022  7022 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-30 17:08:30.731  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:30.731  7022  7022 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:08:30.731  7022  7022 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-30 17:08:30.731  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 17:08:30.731  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:30.731  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:30.811  7022  7022 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-30 17:08:31.041  7022  7022 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 17:08:31.041  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-30 17:08:31.061  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 17:08:31.061   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7022
08-30 17:08:31.061   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-30 17:08:31.061  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,08-30 17:08:31.061  7022  7022 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:31.061  7022  7022 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 17:08:31.061  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-30 17:08:31.081  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 17:08:31.081   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7022
08-30 17:08:31.081   348   348 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 17:08:31.081  7022  7022 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 17:08:31.081  7022  7022 I wpa_supplicant: ssSupport state is = 1
08-30 17:08:31.081  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:31.081  7022  7022 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 17:08:31.081  7022  7022 E wpa_supplicant: SIM READ ERROR
08-30 17:08:31.081  7022  7022 I wpa_supplicant: wpa_default_ap_write_once
08-30 17:08:31.081  7022  7022 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 17:08:31.081  7022  7022 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 17:08:31.081  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 17:08:31.081  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:31.081  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:31.081  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 17:08:31.091  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 17:08:31.091  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:31.131  7022  7022 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 17:08:31.131  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 17:08:31.251  7022  7022 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-30 17:08:31.251  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 17:08:31.251  7022  7022 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 17:08:31.251  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-30 17:08:31.251  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 17:08:31.261  7022  7022 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-30 17:08:31.261  7022  7022 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 17:08:31.261  7022  7022 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-30 17:08:31.261  7022  7022 E wpa_supplicant: SIM READ ERROR
08-30 17:08:31.261  7022  7022 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 17:08:31.281  1015  2748 D SSRM:n  : SIOP:: AP = 340,
,08-30 17:08:31.281  7022  7022 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 17:08:31.291  7022  7022 I wpa_supplicant: Skip scan - bUseNetwork false,
08-30 17:08:31.291  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 17:08:31.291  1015  1130 D WifiConfigStore: Loading config and enabling all networks 
,08-30 17:08:31.291  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:31.291  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:31.291  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:31.291  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:31.291  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:31.291  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:31.291  1177  1177 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 17:08:31.291  1177  1177 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 17:08:31.291  1177  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 17:08:31.301  1177  1177 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 17:08:31.301  1177  1177 D HotspotTile: onReceive : 3, 0
,08-30 17:08:31.301  1318  1318 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:31.311  6192  6192 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:31.311  1015  1130 E WifiConfigStore: Not a HS20
,08-30 17:08:31.311  6192  6192 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:31.311  1015  3085 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:31.311  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:31.311  1015  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
08-30 17:08:31.311  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:31.311  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:31.311  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:31.321  3640  3640 I Hs20UtilService: Starting #20
08-30 17:08:31.321  3640  3675 I Hs20UtilService: Message received 5011
,08-30 17:08:31.321  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 17:08:31.321  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 17:08:31.321  6464  6464 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 17:08:31.321  6464  6464 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 17:08:31.321  6464  6464 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-30 17:08:31.321  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 17:08:31.321  7022  7022 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 17:08:31.321  7022  7022 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 17:08:31.331  7022  7022 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 17:08:31.331  7022  7022 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 17:08:31.331  7022  7022 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 17:08:31.331  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 17:08:31.331  7022  7022 I wpa_supplicant: First Scan Start
,08-30 17:08:31.331  7022  7022 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 17:08:31.331  1015  1130 D WifiNative-wlan0: Setting external_sim to 1
,08-30 17:08:31.331  1015  1130 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 17:08:31.331  1015  1130 I WifiNative-HAL: startHal
08-30 17:08:31.331  1015  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9ca8988c
08-30 17:08:31.331  1015  1130 I WifiNative-HAL: Could not start hal
,08-30 17:08:31.331  6386  6386 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 17:08:31.341  1015  1130 E WifiNative-wlan0: do suspend true
,08-30 17:08:31.341  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 17:08:31.341   277   951 D CommandListener: Setting iface cfg
08-30 17:08:31.341   277   951 D CommandListener: Trying to bring up p2p0
08-30 17:08:31.341  1015  1125 D WifiP2pService: P2pEnablingState
08-30 17:08:31.341  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 17:08:31.341  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 17:08:31.341  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 17:08:31.341  1015  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:31.341  1015  1148 I WifiNative-HAL: startHal
08-30 17:08:31.341  1015  1125 D WifiP2pService: P2p socket connection successful
08-30 17:08:31.341  1015  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dd399bc
08-30 17:08:31.341  1015  1148 I WifiNative-HAL: Could not start hal
08-30 17:08:31.341  1015  1148 E WifiScanningService: could not start HAL
08-30 17:08:31.341  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-30 17:08:31.341  1015  1125 D WifiP2pService: P2pEnabledState
08-30 17:08:31.341  1015  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:31.341  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 17:08:31.341  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:31.341  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:31.341  1015  1130 E WifiNative-wlan0: invaild command id : 215
,08-30 17:08:31.351  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 17:08:31.351  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 17:08:31.351  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 17:08:31.351  1015  1130 E WifiNative-wlan0: invaild command id : 215
,08-30 17:08:31.351  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 17:08:31.351  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-30 17:08:31.351  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 17:08:31.351  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:31.351  7022  7022 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:31.351  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 17:08:31.351  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true,
08-30 17:08:31.351  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 17:08:31.351  1015  1045 D WifiDisplayController: disconnect
08-30 17:08:31.351  1015  1045 D WifiDisplayController: updateConnection
08-30 17:08:31.351  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-30 17:08:31.351  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:31.351  7022  7022 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 17:08:31.351  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 17:08:31.351  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-30 17:08:31.351  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 17:08:31.351  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 17:08:31.361  7022  7022 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN,
,08-30 17:08:31.361  1177  1177 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 17:08:31.361  1015  1475 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:31.361  1177  1177 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 17:08:31.361  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:31.361  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:31.361  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 17:08:31.361  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-30 17:08:31.361  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  secondary type: null
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  wps: 0
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  grpcapab: 0
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  devcapab: 0
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  status: 3
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  wfdInfo: null
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-30 17:08:31.361  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-30 17:08:31.371  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
08-30 17:08:31.371  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 17:08:31.371  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:31.371  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:31.371  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:31.371  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 17:08:31.371  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:31.371  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 17:08:31.371  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off,
08-30 17:08:31.371  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:31.371  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:31.371  6432  6432 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
08-30 17:08:31.381  6432  6432 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 17:08:31.381  6447  6447 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 17:08:31.391  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
08-30 17:08:31.391  1015  1125 D WifiP2pService: InactiveState
,08-30 17:08:31.391  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-30 17:08:31.391  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:31.391  7022  7022 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-30 17:08:31.391  1015  1125 D WifiP2pService: InactiveState{ what=143376 },
08-30 17:08:31.391  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 17:08:31.971   287   287 E SMD     : DCD OFF,
,08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:31.981  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:31.991  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:31.991  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 17:08:31.991  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 17:08:31.991  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@15aebb65 Bundle[{}]
,08-30 17:08:32.001  6192  6244 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 17:08:32.001  6192  6244 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 17:08:32.001  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 17:08:32.001  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 17:08:32.001  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 17:08:32.001  6192  6244 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 17:08:32.011  6192  6244 I System.out: Running OutgoingSocketThread
,08-30 17:08:32.011  6192  7029 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1167)
,08-30 17:08:32.011  6192  7029 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46907
,08-30 17:08:32.021  6192  7029 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 17:08:32.541  7022  7022 I wpa_supplicant: nl80211: Received scan results (18 BSSes),
,08-30 17:08:32.541  7022  7022 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-30 17:08:32.541  7022  7022 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-30 17:08:32.541  1015  7027 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-30 17:08:32.541  7022  7022 I wpa_supplicant: Trying to associate with  'G700',
08-30 17:08:32.541  7022  7022 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-30 17:08:32.541  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-30 17:08:32.571  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:32.571  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:32.661  7022  7022 E wpa_supplicant: Cmd 35605 not handled
,08-30 17:08:32.661  7022  7022 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:32.661  7022  7022 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-30 17:08:32.661  7022  7022 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 17:08:32.661  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 17:08:32.661  7022  7022 I wpa_supplicant: Associated with F4.99.3E
08-30 17:08:32.661  7022  7022 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:32.661  7022  7022 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 17:08:32.661  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:32.661  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:32.661  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:32.661  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:32.661  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 17:08:32.661  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 17:08:32.661  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-30 17:08:32.661  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 17:08:32.661  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 17:08:32.661  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-30 17:08:32.661  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:32.661  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 17:08:32.661  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:08:32.671  1015  1133 E Tethering: No numeric data
,08-30 17:08:32.671  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-30 17:08:32.671  1015  1133 D Tethering: clearTetheredNotification()
,08-30 17:08:32.671  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:32.671  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:32.671  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:32.671  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:32.671  1177  1177 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 17:08:32.671  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:32.671  1177  1177 D HotspotTile: updateTetherState():false, false
08-30 17:08:32.671  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:32.671  7022  7022 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 17:08:32.681  7022  7022 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 17:08:32.681  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:32.681  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:32.681  7022  7022 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 17:08:32.681  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:32.681  7022  7022 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 17:08:32.681  1015  1123 V NetworkStats: performPollLocked() took 11ms
08-30 17:08:32.681  7022  7022 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 17:08:32.681  7022  7022 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 17:08:32.681  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:32.681  7022  7022 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 17:08:32.681  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 17:08:32.681  7022  7022 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 17:08:32.681  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 17:08:32.681  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-30 17:08:32.691  1015  1130 D WifiNative-wlan0: callSECApiVoid - ID [50],
08-30 17:08:32.691  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:32.691  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:32.691  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-30 17:08:32.701  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:32.701  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:32.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:32.701  1015  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 17:08:32.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.701  1015  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 17:08:32.701  1015  1132 E ConnectivityService: updateNetworkInfo()
,08-30 17:08:32.701  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 17:08:32.701  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-30 17:08:32.701  1015  1219 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:32.701  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:32.711  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:32.711  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:32.711  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:32.711  3640  3640 I Hs20UtilService: Starting #21
,08-30 17:08:32.721  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 17:08:32.721  3640  3675 I Hs20UtilService: Message received 5007
08-30 17:08:32.721  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:32.721  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 17:08:32.721  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,08-30 17:08:32.721  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 17:08:32.721  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 17:08:32.721  1318  1318 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 17:08:32.721  1318  3066 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 17:08:32.731   277   951 D CommandListener: Setting iface cfg
,08-30 17:08:32.731  1015  1130 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 17:08:32.731  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 17:08:32.741  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:32.741  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 17:08:32.741  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 17:08:32.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:32.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:32.751  1015  1130 E WifiNative-wlan0: do suspend false
,08-30 17:08:32.751  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-30 17:08:32.751  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 17:08:32.761  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 17:08:32.761  1015  1130 D SecContentProvider2: mCursor = null
,08-30 17:08:32.971  7032  7032 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 17:08:32.971  7032  7032 I dhcpcd  : version 5.5.6 starting
,08-30 17:08:32.971  7032  7032 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 17:08:33.011  6192  6244 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1168)
08-30 17:08:33.011  6192  6244 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1168)
08-30 17:08:33.011  6192  6244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1173)
08-30 17:08:33.011  6192  6244 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 17:08:33.011  6192  6244 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1174)
08-30 17:08:33.011  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.011  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3720d366 added. We now have 2 listener(s)
08-30 17:08:33.021  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:33.021  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.021  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.021  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.021  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@204746a7 added. We now have 9 listener(s)
08-30 17:08:33.021  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.021  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:08:33.021  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:33.021  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 17:08:33.021  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 17:08:33.021  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354686fd added. We now have 3 listener(s)
,08-30 17:08:33.031  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.031  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10d6bff2 added. We now have 10 listener(s)
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.031  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:33.031  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.031  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.031  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3720d366 removed from the list
,08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.031  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@204746a7 removed from the list
08-30 17:08:33.031  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.031  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.031  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.031  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@204746a7 not in the list
08-30 17:08:33.031  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.031  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.041  7032  7032 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-30 17:08:33.041  7032  7032 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 17:08:33.041  7032  7032 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 17:08:33.041  7032  7032 I dhcpcd  : bssid match
08-30 17:08:33.041  7032  7032 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10d6bff2 removed from the list
08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.041  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.041  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@354686fd removed from the list
,08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117a643 added. We now have 2 listener(s)
,08-30 17:08:33.041  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:33.041  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.041  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.041  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c64c0 added. We now have 9 listener(s)
08-30 17:08:33.041  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:33.041  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:33.051  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:33.051  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:33.051  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:33.051  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:33.051  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 17:08:33.051  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398ce93e added. We now have 3 listener(s)
,08-30 17:08:33.051  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:33.051  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.051  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.051  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.051  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1404639f added. We now have 10 listener(s)
08-30 17:08:33.051  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.051  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:33.051  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:33.051  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:33.051  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:33.051  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:33.061  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:33.061  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 17:08:33.061  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:33.061  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:08:33.061  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:33.061  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:33.071  6928  6995 D BtGatt.GattService: registerClient() - UUID=046d0c4e-580b-4d2e-9107-f1d3b827eee6,
,08-30 17:08:33.101  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7033
08-30 17:08:33.101  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7038
,08-30 17:08:33.101  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.101  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.111  6928  6954 D BtGatt.GattService: onClientRegistered() - UUID=046d0c4e-580b-4d2e-9107-f1d3b827eee6, clientIf=6
,08-30 17:08:33.111  7032  7032 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,08-30 17:08:33.111  6192  6201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:33.111  6928  6937 D BtGatt.GattService: start scan with filters
,08-30 17:08:33.121  6928  6959 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:33.121  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-30 17:08:33.121  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 17:08:33.121  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:33.121  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 17:08:33.121  6928  6959 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24eb16fb
,08-30 17:08:33.121  6928  6954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 17:08:33.121  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.121  6928  6959 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:33.121  6928  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 17:08:33.121  6928  6959 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 17:08:33.121  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 17:08:33.121  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.121  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 17:08:33.121  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:33.121  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:33.131  6928  6959 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:33.131  6928  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:33.131  6928  6954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:33.131  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.131  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:33.131  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:33.131  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.141  6192  6244 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 17:08:33.141  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.141  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 17:08:33.141  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:33.141  6928  6995 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:33.141  6928  6937 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:33.141  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:33.141  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:33.151  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 17:08:33.151  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:33.151  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:33.151  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:33.151  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.151  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 17:08:33.151  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.151  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.151  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:33.151  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.151  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117a643 removed from the list
08-30 17:08:33.151  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.151  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c64c0 removed from the list
08-30 17:08:33.151  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:33.151  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.151  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.151  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.151  6928  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 74
,08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.161  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68c64c0 not in the list
08-30 17:08:33.161  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.161  6928  6959 D BtGatt.ScanManager: filter size is 1
08-30 17:08:33.161  6928  6959 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1404639f removed from the list
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.161  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@398ce93e removed from the list
08-30 17:08:33.161  7032  7032 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd59abb added. We now have 2 listener(s)
,08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.161  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba0bd8 added. We now have 9 listener(s)
08-30 17:08:33.161  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:33.161  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:33.161  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:33.161  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.161  6928  6959 D BtGatt.ScanManager: stopping BLe Batch
,08-30 17:08:33.171  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 17:08:33.171  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.171  6928  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-30 17:08:33.171  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:33.181  6928  6954 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 17:08:33.181  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.181  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:33.181  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:33.181  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.181  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33fae216 added. We now have 3 listener(s)
,08-30 17:08:33.191  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-30 17:08:33.191  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.191  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:08:33.191  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.191  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b92797 added. We now have 10 listener(s)
08-30 17:08:33.191  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.191  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:33.191  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:33.191  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 17:08:33.191  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-30 17:08:33.191  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:33.191  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:33.191  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.191  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.191  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:33.201  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-30 17:08:33.201  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,08-30 17:08:33.211  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 17:08:33.211  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:33.211  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:33.231  6928  6937 D BtGatt.GattService: registerClient() - UUID=38e3ef32-78bc-44e1-89cb-2b753a2e9d42
,08-30 17:08:33.271  6928  6954 D BtGatt.GattService: onClientRegistered() - UUID=38e3ef32-78bc-44e1-89cb-2b753a2e9d42, clientIf=6
,08-30 17:08:33.271  6192  6200 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:33.281  6928  6995 D BtGatt.GattService: start scan with filters,
08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: handling starting scan
08-30 17:08:33.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:08:33.281  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:33.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 17:08:33.281  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-30 17:08:33.281  6928  6954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:08:33.281  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: allow scan with filters,
08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-30 17:08:33.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:33.281  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-30 17:08:33.281  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:33.281  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: Starting BLE batch scan
08-30 17:08:33.281  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 17:08:33.281  6928  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:33.281  6928  6954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 17:08:33.281  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.291  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:33.291  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:33.291  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.291  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:33.291  6192  6244 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-30 17:08:33.291  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 17:08:33.301  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.301  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.301  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fd59abb removed from the list
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.301  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba0bd8 removed from the list
08-30 17:08:33.301  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:33.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:08:33.301  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.301  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2aba0bd8 not in the list
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:33.301  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:33.301  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 17:08:33.301  6928  6995 D BtGatt.GattService: stopScan() - queue size =1
08-30 17:08:33.301  6928  6936 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:33.311  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:33.311  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:33.311  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:33.311  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.321  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b92797 removed from the list
08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.321  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.321  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.321  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33fae216 removed from the list
08-30 17:08:33.321  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:33.321  6928  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 75
08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21dea633 added. We now have 2 listener(s)
,08-30 17:08:33.321  6928  6959 D BtGatt.ScanManager: filter size is 1
,08-30 17:08:33.321  6928  6959 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 17:08:33.321  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-30 17:08:33.321  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.321  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 17:08:33.321  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.321  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.321  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e27df0 added. We now have 9 listener(s)
08-30 17:08:33.321  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:33.321  6928  6959 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:33.321  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:33.331  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:33.331  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.331  6928  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:33.331  6928  6954 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-30 17:08:33.331  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.331  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:33.341  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:33.351  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:33.351  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:08:33.351  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.351  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2641dee added. We now have 3 listener(s)
,08-30 17:08:33.351  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.351  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.361  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 17:08:33.361  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.361  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.361  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.361  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3728f added. We now have 10 listener(s)
08-30 17:08:33.361  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.361  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 17:08:33.361  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-30 17:08:33.361  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 17:08:33.361  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:08:33.361  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 17:08:33.371  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 17:08:33.371  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 17:08:33.371  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 17:08:33.381  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-30 17:08:33.381  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 17:08:33.381  6192  6244 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 17:08:33.381  6928  6937 D BtGatt.GattService: registerClient() - UUID=a63f642e-a62c-441c-a427-cd02557bba79
,08-30 17:08:33.421  6928  6954 D BtGatt.GattService: onClientRegistered() - UUID=a63f642e-a62c-441c-a427-cd02557bba79, clientIf=6,
08-30 17:08:33.421  6192  6201 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 17:08:33.431  6928  6955 D BtGatt.GattService: start scan with filters
08-30 17:08:33.431  6928  6959 D BtGatt.ScanManager: handling starting scan
,08-30 17:08:33.431  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 17:08:33.431  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 17:08:33.431  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-30 17:08:33.431  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 17:08:33.431  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 17:08:33.431  6928  6954 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 17:08:33.431  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.431  6928  6959 D BtGatt.ScanManager: allow scan with filters
,08-30 17:08:33.431  6928  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 17:08:33.431  6928  6959 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-30 17:08:33.441  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-30 17:08:33.441  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 17:08:33.441  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 17:08:33.441  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.441  6928  6959 D BtGatt.ScanManager: Starting BLE batch scan,
08-30 17:08:33.441  6928  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 17:08:33.441  6928  6954 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 17:08:33.441  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.441  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 17:08:33.441  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-30 17:08:33.451  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.461  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:33.461  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.461  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.461  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.461  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21dea633 removed from the list
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.461  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e27df0 removed from the list
08-30 17:08:33.461  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:33.461  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 17:08:33.461  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 17:08:33.461  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e27df0 not in the list
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 17:08:33.461  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-30 17:08:33.461  6928  6937 D BtGatt.GattService: stopScan() - queue size =1
,08-30 17:08:33.461  6928  6955 D BtGatt.GattService: unregisterClient() - clientIf=6,
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-30 17:08:33.461  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 17:08:33.471  6928  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 76,
08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 17:08:33.471  6928  6959 D BtGatt.ScanManager: filter size is 1
08-30 17:08:33.471  6928  6959 D BtGatt.ScanManager: delete FilterIndex - 5
,08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 17:08:33.471  6928  6954 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 17:08:33.471  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.471  6928  6959 D BtGatt.ScanManager: stopping BLe Batch
08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.471  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:33.471  6192  6192 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 17:08:33.471  6192  6192 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.471  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d3728f removed from the list
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.471  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.471  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.471  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.471  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2641dee removed from the list
08-30 17:08:33.471  6928  6954 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 17:08:33.471  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.471  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 17:08:33.471  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@149ea8ab added. We now have 2 listener(s)
,08-30 17:08:33.471  6928  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 17:08:33.481  6928  6954 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 17:08:33.481  6928  6954 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 17:08:33.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 17:08:33.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:08:33.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.481  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 17:08:33.481  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e341b08 added. We now have 9 listener(s)
08-30 17:08:33.481  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 17:08:33.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 17:08:33.481  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 17:08:33.491  6192  6244 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 17:08:33.491  6192  6244 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 17:08:33.491  6192  6244 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 17:08:33.491  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 17:08:33.491  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a8dfcc6 added. We now have 3 listener(s)
,08-30 17:08:33.491  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.491  6192  6192 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189d2487 added. We now have 10 listener(s)
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:08:33.501  6192  6244 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.501  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@149ea8ab removed from the list
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e341b08 removed from the list
08-30 17:08:33.501  6192  6244 D io.jxcore.node.ConnectivityMonitor: stop
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.501  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.501  6192  6244 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e341b08 not in the list
08-30 17:08:33.501  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189d2487 removed from the list,
08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 17:08:33.501  6192  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 17:08:33.501  6192  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 17:08:33.501  6192  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 17:08:33.501  6192  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a8dfcc6 removed from the list
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 17:08:33.501  6192  6244 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 17:08:33.511  6192  7065 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1181, name: My test thread name)
,08-30 17:08:33.511  6192  7065 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1181, thread name: My test thread name)
08-30 17:08:33.511  6192  7065 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1181, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:08:33.511  6192  7066 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1183, name: My test thread name),
08-30 17:08:33.511  6192  7066 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1183, thread name: My test thread name)
08-30 17:08:33.511  6192  7066 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1183, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-30 17:08:33.511  6192  6244 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 17:08:33.511  6192  6244 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-30 17:08:33.511  6192  6244 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 17:08:33.511  6192  6244 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 17:08:33.511  6192  6244 D com.test.thalitest.ThaliTestRunner: Total duration: 24244 ms,
08-30 17:08:33.511  6192  6244 I jxcore-log: *Native tests were executed*
08-30 17:08:33.511  6192  6244 I jxcore-log: 
,08-30 17:08:33.511  6192  6244 I jxcore-log: Total number of executed tests:  80
08-30 17:08:33.511  6192  6244 I jxcore-log: 
08-30 17:08:33.511  6192  6244 I jxcore-log: Number of passed tests:  80
08-30 17:08:33.511  6192  6244 I jxcore-log: 
,08-30 17:08:33.521  6192  6244 I jxcore-log: Number of failed tests:  0
08-30 17:08:33.521  6192  6244 I jxcore-log: 
08-30 17:08:33.521  6192  6244 I jxcore-log: Number of ignored tests:  0
08-30 17:08:33.521  6192  6244 I jxcore-log: 
08-30 17:08:33.521  6192  6244 I jxcore-log: Total duration:  24244
,08-30 17:08:33.521  6192  6244 I jxcore-log: 
08-30 17:08:33.521  6192  6244 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 17:08:33.521  6192  6244 I jxcore-log: 
,08-30 17:08:33.521  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.521  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6192 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.531  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.531  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
08-30 17:08:33.541  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.541  6192  6244 I jxcore-log: 
,08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
,08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
,08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
,08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
08-30 17:08:33.551  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 17:08:33.551  6192  6244 I jxcore-log: 
,08-30 17:08:33.571  1015  1130 E WifiNative-wlan0: do suspend true,
,08-30 17:08:33.601  1015  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
08-30 17:08:33.601  1015  1125 D WifiP2pService: InactiveState{ what=143375 },
08-30 17:08:33.601  1015  1130 E WifiStateMachine: VerifyingLinkState enter,
,08-30 17:08:33.601  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-30 17:08:33.611  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 17:08:33.611  1015  1132 D ConnectivityService: Adding iface wlan0 to network 504
08-30 17:08:33.611  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:33.611  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:33.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:33.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.611  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.611  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:33.611  1015  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-30 17:08:33.621  1015  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-30 17:08:33.631  1015  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 17:08:33.631  1015  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:33.631  1015  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:33.631  1015  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:33.641  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:33.641  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:33.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.641  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:33.651  6192  6192 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:08:33.651  1015  3083 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 17:08:33.651  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:33.651  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:33.651  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:33.651  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:33.651  1015  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-30 17:08:33.651  3640  3640 I Hs20UtilService: Starting #22,
08-30 17:08:33.651  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:33.651  6192  6244 I jxcore-log: 
08-30 17:08:33.661  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:33.661  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:33.671  1318  1318 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 17:08:33.671  1015  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-30 17:08:33.671  1015  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 17:08:33.671  1015  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-30 17:08:33.681  1015  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 17:08:33.681  1015  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 17:08:33.681  1015  1132 D ConnectivityService: LTETest block dns file not exists
,08-30 17:08:33.681  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:33.681  1015  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:08:33.681  1015  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 17:08:33.691  1177  1177 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:33.691  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 17:08:33.691  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.691  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.691  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.691  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:33.691  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 17:08:33.691  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-30 17:08:33.691  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-30 17:08:33.691  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-30 17:08:33.701  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:33.701  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-30 17:08:33.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.701  1015  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:33.701  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:33.701  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 17:08:33.701  1015  1132 E ConnectivityService: updateNetworkInfo()
08-30 17:08:33.701  1015  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:33.701  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:33.701  1015  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 17:08:33.701  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 17:08:33.701  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 17:08:33.701  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 17:08:33.701  1015  7030 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 17:08:33.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.701  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:33.711  1015  1132 D ConnectivityService:    accepting network in place of null
08-30 17:08:33.711  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 17:08:33.711  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 17:08:33.711  1015  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-30 17:08:33.711  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 17:08:33.711  1015  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 17:08:33.711  1015  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-30 17:08:33.711  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 17:08:33.711   277   947 D EnterpriseController: uids 1000
08-30 17:08:33.711   277   947 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 17:08:33.711   277   947 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-30 17:08:33.721  1015  5585 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:33.721  1015  5585 W ActivityManager: userId = 0, bbcId = -10000,
08-30 17:08:33.721  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 17:08:33.721  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 17:08:33.721  1015  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-30 17:08:33.721  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 17:08:33.721  1015  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:33.721  3640  3640 I Hs20UtilService: Starting #23
,08-30 17:08:33.721  3640  3675 I Hs20UtilService: Message received 5007
08-30 17:08:33.721  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 17:08:33.731  1177  1696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:33.731  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 17:08:33.731  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 17:08:33.731  1015  1133 D Tethering: MasterInitialState.processMessage what=3
,08-30 17:08:33.731  1015  1123 V NetworkStats: updateIfacesLocked()
08-30 17:08:33.731  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.731  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-30 17:08:33.731  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 17:08:33.731  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 17:08:33.731  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:33.731  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:33.731  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:33.731  1177  1177 D StatusBar.NetworkController: updateDataNetType()
,08-30 17:08:33.731  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:33.741  1015  1123 V NetworkStats: performPollLocked() took 8ms
08-30 17:08:33.731  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 17:08:33.741  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 17:08:33.741  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1318  1318 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:33.741  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:33.741  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.741  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:33.741  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 17:08:33.741  1318  1318 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 17:08:33.741  1318  1318 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 17:08:33.751  1015  3083 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 17:08:33.751  1015  3083 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 17:08:33.751  1015  3083 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:33.751  1015  3083 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:33.751  1015  3083 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 17:08:33.751  3640  3640 I Hs20UtilService: Starting #24
08-30 17:08:33.751  3640  3675 I Hs20UtilService: Message received 5007
,08-30 17:08:33.761  1318  1318 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 17:08:33.761  1318  1318 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 17:08:33.761  1015  5585 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 17:08:33.771  1015  1475 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-30 17:08:33.771  1015  1475 D SecContentProvider2: mCursor = null
,08-30 17:08:33.771  1015  1470 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 17:08:33.771  1015  1470 D SecContentProvider2: mCursor = null
08-30 17:08:33.771  1015  1213 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 17:08:33.771  1015  1213 D SecContentProvider2: mCursor = null
,08-30 17:08:33.771  1015  3083 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-30 17:08:33.771  1015  3083 D SecContentProvider2: mCursor = null
,08-30 17:08:33.771  1015  3085 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-30 17:08:33.771  1015  3085 D SecContentProvider2: mCursor = null
,08-30 17:08:33.771  1015  1027 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-30 17:08:33.771  1015  1027 D SecContentProvider2: mCursor = null
,08-30 17:08:33.801   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-30 17:08:33.801  1015  1475 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-30 17:08:33.811  1177  1177 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 17:08:33.821  6192  6192 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 17:08:33.821  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:33.821  6192  6244 I jxcore-log: 
,08-30 17:08:33.831  7067  7067 D AndroidRuntime: 
08-30 17:08:33.831  7067  7067 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:08:33.841  7067  7067 D AndroidRuntime: CheckJNI is OFF
,08-30 17:08:33.841  7067  7067 D AndroidRuntime: readGMSProperty: start
08-30 17:08:33.841  7067  7067 D AndroidRuntime: readGMSProperty: already setted!!
08-30 17:08:33.841  7067  7067 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 17:08:33.841  7067  7067 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 17:08:33.841  7067  7067 D AndroidRuntime: readGMSProperty: end
08-30 17:08:33.841  7067  7067 D AndroidRuntime: addProductProperty: start
,08-30 17:08:33.971  6192  6192 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-30 17:08:33.981  6192  6244 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 17:08:33.981  6192  6244 I jxcore-log: 
,08-30 17:08:33.981  7067  7067 E AffinityControl: AffinityControl: registerfunction enter
,08-30 17:08:34.011  7067  7067 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:08:34.021  1015  1028 D PackageManager: START PACKAGE DELETE: observer{51476290},
08-30 17:08:34.021  1015  1028 D PackageManager: pkg{<packageName>}
08-30 17:08:34.021  1015  1028 D PackageManager: user{0}
08-30 17:08:34.021  1015  1028 D PackageManager: caller{2000}
08-30 17:08:34.021  1015  1028 D PackageManager: flags{2}
,08-30 17:08:34.031  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 17:08:34.031  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 17:08:34.031  1015  1028 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 17:08:34.031  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-30 17:08:34.031  1015  1028 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 17:08:34.031  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-30 17:08:34.031  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-30 17:08:34.031  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 17:08:34.031  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 17:08:34.031  1015  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
08-30 17:08:34.031  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 17:08:34.041  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
08-30 17:08:34.041  1015  1040 I ActivityManager: Killing 6192:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 17:08:34.041  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{2962172 u0 com.test.thalitest/.MainActivity t128}
,08-30 17:08:34.041  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-30 17:08:34.081  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-30 17:08:34.091  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 17:08:34.101  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 17:08:34.111  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-30 17:08:34.111  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,08-30 17:08:34.121  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-30 17:08:34.141  1015  5585 I WindowState: WIN DEATH: Window{14eb40d2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:08:34.141   257   435 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-30 17:08:34.141   257   435 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-30 17:08:34.151  1015  5585 D InputDispatcher: Focus left window: 6192
,08-30 17:08:34.161  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-30 17:08:34.161  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:34.191  1015  1040 D InputDispatcher: Focused application released
,08-30 17:08:34.201  3173  3173 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-30 17:08:34.201  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,08-30 17:08:34.201  3173  3173 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:446 
,08-30 17:08:34.201  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-30 17:08:34.201  1015  1475 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,08-30 17:08:34.221  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-30 17:08:34.221  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:34.221  1015  7030 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 17:08:34.241  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-30 17:08:34.241  5675  5675 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 792us total 22.389ms
,08-30 17:08:34.241  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 17:08:34.261  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:08:34.271  1924  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:08:34.271  1828  1828 E SamsungIME: mOCRHelper is null
,08-30 17:08:34.281  3775  3775 I art     : Explicit concurrent mark sweep GC freed 22523(1362KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.314ms total 74.814ms
,08-30 17:08:34.291  3677  3677 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 17:08:34 GMT+02:00 2016
,08-30 17:08:34.331  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 17:08:34.331  1015  3085 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 17:08:34.331  1015  3085 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 17:08:34.341  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:34.351  1015  3085 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:34.351  1015  3085 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:34.351  1015  3085 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 17:08:34.351  3677  3677 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 17:08:34.361  1440  1440 D RegisteredServicesCache: empty dynamic service
,08-30 17:08:34.361  1015  5585 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44,
08-30 17:08:34.361  1015  5585 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 17:08:34.361  1015  1470 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
08-30 17:08:34.361  1015  1470 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-30 17:08:34.371  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 17:08:34.371  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-30 17:08:34.371  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-30 17:08:34.371  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 17:08:34.371  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.371  1015  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-30 17:08:34.371  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 17:08:34.371  1015  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-30 17:08:34.371  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 17:08:34.381  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 17:08:34.381  1015  1027 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-30 17:08:34.381  1015  1027 D SecContentProvider2: mCursor = null
08-30 17:08:34.381  3677  3677 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-30 17:08:34.381  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-30 17:08:34.381  6515  6515 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 17:08:34.381  1015  1123 V NetworkStats: performPollLocked() took 11ms
08-30 17:08:34.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:34.391  3677  3677 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 17:08:34.391  1015  5585 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-30 17:08:34.391  3173  3173 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-30 17:08:34.391  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-30 17:08:34.391  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-30 17:08:34.391  3173  3173 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-30 17:08:34.401  1015  5585 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.401  1015  5585 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.401  1015  5585 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.401  1015  5585 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.401  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.401  3677  3677 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 17:08:34.411  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 17:08:34.411  7085  7085 E Zygote  : MountEmulatedStorage()
,08-30 17:08:34.411  7085  7085 E Zygote  : v2
08-30 17:08:34.411  7085  7085 I libpersona: KNOX_SDCARD checking this for 10094
08-30 17:08:34.411  7085  7085 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:34.411  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.411  7085  7085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:34.411  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 15:08:34 GMT], X-Android-Received-Millis=[1472569714421], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472569714339]}
,08-30 17:08:34.411  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-30 17:08:34.411  1015  7030 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 17:08:34.411  1015  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-30 17:08:34.411  1015  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 17:08:34.411  1015  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-30 17:08:34.411  1015  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-30 17:08:34.411  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
08-30 17:08:34.411  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
08-30 17:08:34.411  1177  1696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 17:08:34.421  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
08-30 17:08:34.421  1015  5585 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7085 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-30 17:08:34.421  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 17:08:34.421  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-30 17:08:34.421  7085  7085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:34.421  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.421  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.421  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.421  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.421  7085  7085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:34.431  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-30 17:08:34.431  1015  1015 I art     : Explicit concurrent mark sweep GC freed 64653(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/42MB, paused 3.518ms total 203.014ms
,08-30 17:08:34.431  1015  1055 I art     : WaitForGcToComplete blocked for 69.244ms for cause Explicit
,08-30 17:08:34.441  7097  7097 E Zygote  : MountEmulatedStorage()
08-30 17:08:34.441  7097  7097 E Zygote  : v2
08-30 17:08:34.441  7097  7097 I libpersona: KNOX_SDCARD checking this for 10044
08-30 17:08:34.441  7097  7097 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:34.441  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:34.441  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 17:08:34.441  1015  1040 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7097 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-30 17:08:34.441  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-30 17:08:34.451  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 17:08:34.451  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 17:08:34.451  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 17:08:34.461  3173  3173 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-30 17:08:34.471  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-30 17:08:34.471  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.471  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.471  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.471  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.481   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-30 17:08:34.481  7116  7116 E Zygote  : MountEmulatedStorage(),
08-30 17:08:34.481  7116  7116 I libpersona: KNOX_SDCARD checking this for 10149
08-30 17:08:34.481  7116  7116 E Zygote  : v2
08-30 17:08:34.481  7116  7116 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:34.481  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:34.491  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 17:08:34.491  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 17:08:34.491  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:34.501  1015  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7116 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:34.511  1015  1027 D InputDispatcher: Focus entered window: 3173
,08-30 17:08:34.511  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 17:08:34.511  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 17:08:34.511  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-30 17:08:34.511  7085  7085 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:34.511  7085  7085 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.511  3173  3173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 17:08:34.511  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:34.521  7097  7097 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.521  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:34.531  7116  7116 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.531  3173  3173 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-30 17:08:34.551  1015  1216 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 17:08:34.561  1440  1440 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 17:08:34.561  1015  7132 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 17:08:34.561  1015  1216 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6192 uid 10155
,08-30 17:08:34.561  3677  7084 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 17:08:34.571  3677  7084 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 17:08:34.571  3173  3173 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12358bb4 time:151388
,08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 17:08:34.581  7097  7097 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 17:08:34.581  1015  1045 W ActivityManager: mDVFSHelper.release()
08-30 17:08:34.581  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1284cdf5 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:151397
,08-30 17:08:34.581  1440  1440 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:34.581  3677  3677 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
08-30 17:08:34.581  1828  1828 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 17:08:34.591  3173  3173 V ActivityThread: updateVisibility : ActivityRecord{159926e9 token=android.os.BinderProxy@12358bb4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-30 17:08:34.591  5755  7115 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 17:08:34.621  7085  7085 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 17:08:34.621  7085  7085 D elm:15183: ELMEngine.ELMEngine( context ).
,08-30 17:08:34.621  7085  7085 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-30 17:08:34.631  1015  1219 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-30 17:08:34.631  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-30 17:08:34.631  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-30 17:08:34.631  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:34.631  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 17:08:34.631  7085  7085 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 17:08:34.641  7116  7116 D ThemeInfoUtil: getCurrentFestivalName is [null]
,08-30 17:08:34.641  7116  7116 D ThemeInfoUtil: isCurrentFestival = false
,08-30 17:08:34.641  5755  5755 I art     : Explicit concurrent mark sweep GC freed 628(47KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 766us total 53.780ms
,08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: EthernetConnected: false
08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: updateDataNetType()
08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 17:08:34.641  1177  1177 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 17:08:34.641  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:34.641  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-30 17:08:34.641  1177  1177 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-30 17:08:34.651  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 17:08:34.651  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 17:08:34.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:34.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:34.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 17:08:34.651  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 17:08:34.651  7085  7085 D elm:15183: ElmAgentService : onCreate()
08-30 17:08:34.651  7085  7134 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-30 17:08:34.651  7085  7134 D elm:15183: MainReceiver.listeningToPackageRemoved()
,08-30 17:08:34.651  7085  7134 D elm:15183: MDMBridge.getInstance()
08-30 17:08:34.651  7085  7134 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 17:08:34.651  7085  7134 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 17:08:34.661  3391  3391 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-30 17:08:34.661  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-30 17:08:34.671  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.671  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.671  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.671  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.671  3391  3391 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 17:08:34.671  3391  3391 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-30 17:08:34.671  3391  3391 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,08-30 17:08:34.671  3391  3391 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-30 17:08:34.671  3391  3391 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-30 17:08:34.671  3391  3391 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-30 17:08:34.671  3391  3391 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-30 17:08:34.671  3391  3391 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-30 17:08:34.671  3391  3391 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 17:08:34.671  3391  3391 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:08:34.671  3391  3391 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:08:34.671  3391  3391 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 17:08:34.671  3391  3391 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-30 17:08:34.671  5934  5942 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-30 17:08:34.671  5934  5942 D BadgeProvider: sendNotify, [notify] : null
08-30 17:08:34.671  5934  5942 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-30 17:08:34.671  5934  5942 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 17:08:34.671  5934  5942 D BadgeProvider: update, [UpdateCount] : 1
,08-30 17:08:34.681  7136  7136 E Zygote  : MountEmulatedStorage(),
08-30 17:08:34.681  7136  7136 E Zygote  : v2
08-30 17:08:34.681  7136  7136 I libpersona: KNOX_SDCARD checking this for 10152
08-30 17:08:34.681  7136  7136 I libpersona: KNOX_SDCARD not a persona,
,08-30 17:08:34.681  7136  7136 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 17:08:34.681  1015  1028 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7136 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,08-30 17:08:34.691  7136  7136 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:34.691  7136  7136 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:34.701  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-30 17:08:34.701  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.721  7085  7085 D elm:15183: ElmAgentService : onDestroy().
,08-30 17:08:34.721  1015  1055 I art     : Explicit concurrent mark sweep GC freed 12735(1452KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 3.273ms total 279.271ms
,08-30 17:08:34.721  7136  7136 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:34.721  7136  7136 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.721  1015  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-30 17:08:34.731  1015  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 17:08:34.731  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.731  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.731  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.731  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.741  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.751  7152  7152 E Zygote  : MountEmulatedStorage()
08-30 17:08:34.751  7152  7152 E Zygote  : v2
08-30 17:08:34.751  7152  7152 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:34.751  7152  7152 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:34.751  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:34.751  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:34.761  1015  1476 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7152 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 17:08:34.761  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:34.761  1015  1476 I ActivityManager: Killing 6132:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-30 17:08:34.801  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:34.801  7152  7152 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.811  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.821  1015  1055 D PackageManager: delete codoeFile: 
,08-30 17:08:34.821  7136  7136 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-30 17:08:34.831  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:08:34.831  1015  5585 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:34.831  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:34.831  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:08:34.831  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,08-30 17:08:34.831  1015  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-30 17:08:34.841  1015  1055 D PackageManager: result of delete: 1{51476290}
,08-30 17:08:34.841  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.851  7067  7067 D AndroidRuntime: Shutting down VM
,08-30 17:08:34.851  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-30 17:08:34.851  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
08-30 17:08:34.851  7152  7152 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 17:08:34.851  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:34.861  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:34.861  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-30 17:08:34.861  1015  5585 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-30 17:08:34.861  1015  5585 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 17:08:34.861  1015  5585 W ActivityManager: userId = 0, bbcId = -10000
08-30 17:08:34.861  1015  5585 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 17:08:34.861  1015  5585 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-30 17:08:34.861  1015  3085 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 17:08:34.871  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.871  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.871  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.871  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.871  1015  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 17:08:34.871  1015  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-30 17:08:34.871  1015  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-30 17:08:34.881  1177  1696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
08-30 17:08:34.881  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 17:08:34.881  7170  7170 E Zygote  : MountEmulatedStorage()
08-30 17:08:34.881  7170  7170 E Zygote  : v2
08-30 17:08:34.881  7170  7170 I libpersona: KNOX_SDCARD checking this for 10156
08-30 17:08:34.881  7170  7170 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:34.881  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:34.881  7097  7097 D NearbySource: Nearby Source Create!
08-30 17:08:34.881  7097  7097 D NearbyContext: Nearby Context Create!
,08-30 17:08:34.881  1177  1696 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 17:08:34.891  1015  3085 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7170 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,08-30 17:08:34.891  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:34.891  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:34.891  3775  6254 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-30 17:08:34.901  1015  3085 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-30 17:08:34.901  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.901  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.901  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:34.901  1015  3085 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:34.911  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 17:08:34.911  1015  1055 D PackageManager: userId{-1}
08-30 17:08:34.911  1015  1055 D PackageManager: andCode{true}
,08-30 17:08:34.911  7183  7183 E Zygote  : MountEmulatedStorage()
08-30 17:08:34.911  7183  7183 E Zygote  : v2
08-30 17:08:34.911  7183  7183 I libpersona: KNOX_SDCARD checking this for 1000
08-30 17:08:34.911  7183  7183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:34.911  7183  7183 I libpersona: KNOX_SDCARD not a persona,
08-30 17:08:34.911  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:34.921  1015  1015 D RCPManagerService: PackageReceiver onReceive()
08-30 17:08:34.921  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0,
08-30 17:08:34.921  1015  3085 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 17:08:34.921  7183  7183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:34.921  7183  7183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 17:08:34.921  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:34.921  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 17:08:34.921  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-30 17:08:34.921  7170  7170 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:34.921  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
08-30 17:08:34.921  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-30 17:08:34.931  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.931  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-30 17:08:34.931  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 17:08:34.931  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 17:08:34.941  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:34.941  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:08:34.941  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:34.941  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 17:08:34.941   256   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-30 17:08:34.941   256   522 W Vold    : Returning OperationFailed - no handler for errno 0
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 17:08:34.941  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 17:08:34.941  7097  7097 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-30 17:08:34.941  7097  7097 D SLinkSource: Samsung link source created
08-30 17:08:34.941  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 17:08:34.951  7183  7183 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:34.951  7183  7183 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:34.951  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.961  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 17:08:34.961  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:34.961  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:34.961  7170  7170 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-30 17:08:34.961  7170  7170 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-30 17:08:34.961  1015  2748 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 17:08:34.961  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 17:08:34.961  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-30 17:08:34.961  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 17:08:34.961  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 17:08:34.971  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 17:08:34.971  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 17:08:34.971  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 17:08:34.971  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 17:08:34.971   287   287 E SMD     : DCD OFF
,08-30 17:08:34.971  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 17:08:34.981  7170  7170 I TapandpayWidget:Utils: Clear T&P info.
,08-30 17:08:34.981  6928  6952 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 17:08:34.981  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 17:08:34.981  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 17:08:34.981  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 17:08:34.981  1015  1476 I ActivityManager: Killing 5592:com.android.vending/u0a28 (adj 15): empty #31
08-30 17:08:34.981  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-30 17:08:34.991  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 17:08:34.991  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 17:08:35.001  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,08-30 17:08:35.001  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 17:08:35.001  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 17:08:35.001  1177  1177 D PanelView: There is/are notification(s) 
,08-30 17:08:35.001  1015  3085 I ActivityManager: Killing 6268:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,08-30 17:08:35.011  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-30 17:08:35.011  6498  6498 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 17:08:35.011  6498  6498 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 17:08:35.011  6498  6498 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 17:08:35.011  6498  6498 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 17:08:35.011  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-30 17:08:35.011  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:35.011  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.011  7170  7170 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-30 17:08:35.011  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:35.021  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:35.021  7183  7183 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:08:35.031  7203  7203 E Zygote  : MountEmulatedStorage(),
08-30 17:08:35.031  7203  7203 E Zygote  : v2
08-30 17:08:35.031  7203  7203 I libpersona: KNOX_SDCARD checking this for 10032
08-30 17:08:35.031  7203  7203 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 17:08:35.031  7203  7203 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:35.031  7203  7203 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:35.041  7203  7203 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:35.041  1015  5585 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 17:08:35.041  1015  5585 D SecContentProvider2: mCursor = null
08-30 17:08:35.041  1015  1219 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7203 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-30 17:08:35.041  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-30 17:08:35.051  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,08-30 17:08:35.051  7183  7183 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-30 17:08:35.051  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-30 17:08:35.051  7203  7203 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:35.061  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.061  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.061  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.061  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.061  7203  7203 D ActivityThread: Added TimaKeyStore provider
08-30 17:08:35.061  1015  1560 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 17:08:35.061  7067  7067 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-30 17:08:35.071  1015  3083 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-30 17:08:35.071  1015  3083 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-30 17:08:35.091  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-30 17:08:35.091  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,08-30 17:08:35.091  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
08-30 17:08:35.091  1177  1177 D PanelView: There is/are notification(s) 
08-30 17:08:35.091  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-30 17:08:35.091  7219  7219 E Zygote  : MountEmulatedStorage()
08-30 17:08:35.091  7219  7219 E Zygote  : v2
08-30 17:08:35.091  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
08-30 17:08:35.091  7219  7219 I libpersona: KNOX_SDCARD checking this for 10160
,08-30 17:08:35.091  1177  1177 D PanelView: There is/are notification(s) 
08-30 17:08:35.091  7219  7219 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:35.091  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
08-30 17:08:35.091  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:35.091  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:35.101  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 17:08:35.101  1015  1219 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7219 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,08-30 17:08:35.101  1015  1219 I ActivityManager: Killing 6560:com.android.chrome/u0a81 (adj 15): empty #31
,08-30 17:08:35.111  1015  1216 I ActivityManager: Killing 6525:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,08-30 17:08:35.111  1015  1219 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-30 17:08:35.111  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.111  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.111  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.111  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:35.121  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 17:08:35.121  7219  7219 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:35.131  1478  1478 D Launcher.Model: reloadBadges entered.
,08-30 17:08:35.151  1015  1219 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7237 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 17:08:35.161  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
08-30 17:08:35.161  7237  7237 I libpersona: KNOX_SDCARD checking this for 10091
08-30 17:08:35.161  7237  7237 E Zygote  : MountEmulatedStorage()
08-30 17:08:35.161  7237  7237 I libpersona: KNOX_SDCARD not a persona
08-30 17:08:35.161  7237  7237 E Zygote  : v2
08-30 17:08:35.161  7237  7237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 17:08:35.161  7237  7237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 17:08:35.161  1015  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 17:08:35.171  7237  7237 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 17:08:35.171  7097  7097 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-30 17:08:35.181  7097  7202 D ContactProvider: getAllContactInfoList Start
08-30 17:08:35.181  7219  7219 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 17:08:35.191   304   304 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 27.695ms
,08-30 17:08:35.191  7237  7237 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 17:08:35.201  7237  7237 D ActivityThread: Added TimaKeyStore provider
,08-30 17:08:35.201  7097  7097 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,08-30 17:08:35.201   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.360ms,
08-30 17:08:35.201  1015  1476 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast,
08-30 17:08:35.211  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.211  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.211  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 17:08:35.211  1015  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 17:08:35.211  7203  7253 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-30 17:08:35.221  5755  5755 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 17:08:35.221   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 17.681ms
,08-30 17:08:35.231  7219  7219 D [0]UMC:UMCContentProvider: @onCreate
,08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 17:08:35.231  7203  7253 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 17:08:35.241  7255  7255 E Zygote  : MountEmulatedStorage()
,08-30 17:08:35.241  7255  7255 E Zygote  : v2
08-30 17:08:35.241  7255  7255 I libpersona: KNOX_SDCARD checking this for 10046
08-30 17:08:35.241  7255  7255 I libpersona: KNOX_SDCARD not a persona
,08-30 17:08:35.241  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 17:08:35.241  1015  1476 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7255 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
08-30 17:08:35.241  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 17:08:35.241  1015  1476 I ActivityManager: Killing 6582:com.sec.android.soagent/u0a34 (adj 15): empty #31
08-30 17:08:35.241  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 17:08:35.241  7203  7253 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 17:08:35.251  5934  5942 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-30 17:08:35.251  5934  5942 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,08-30 17:08:35.261  7219  7219 D [0]UMC:Core: onCreate(): 
08-30 17:08:35.261  7219  7219 D [0]UMC:Core: @isManagedProfileUser
08-30 17:08:35.261  7219  7219 D [0]UMC:Core: userId: 0
08-30 17:08:35.261  7219  7219 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
08-30 17:08:35.261  7219  7219 D [0]UMC:Core: userInfo.isManagedProfile() : false
08-30 17:08:35.261  5934  5942 E DatabaseUtils: Writing exception to parcel
08-30 17:08:35.261  5934  5942 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-30 17:08:35.261  5934  5942 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 17:08:35.261  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 17:08:35.261  7255  7255 D ActivityThread: Added TimaKeyStore provider

```
