#### Test 8359140042466a2_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
,09-01 10:59:13.236   287   287 E SMD     : DCD OFF
09-01 10:59:13.496  6212  6212 D AndroidRuntime: 
09-01 10:59:13.496  6212  6212 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 10:59:13.506  6212  6212 D AndroidRuntime: CheckJNI is OFF
09-01 10:59:13.506  6212  6212 D AndroidRuntime: readGMSProperty: start
09-01 10:59:13.506  6212  6212 D AndroidRuntime: readGMSProperty: already setted!!
09-01 10:59:13.506  6212  6212 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-01 10:59:13.506  6212  6212 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-01 10:59:13.506  6212  6212 D AndroidRuntime: readGMSProperty: end
09-01 10:59:13.506  6212  6212 D AndroidRuntime: addProductProperty: start
09-01 10:59:13.656  6212  6212 E AffinityControl: AffinityControl: registerfunction enter
09-01 10:59:13.686  6212  6212 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-01 10:59:13.696  1015  1028 E PersonaManagerService: inState():  stateMachine is null !!
09-01 10:59:13.696  1015  1028 I PersonaManagerService: PersonaId don't exist
09-01 10:59:13.696  1015  1028 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-01 10:59:13.696  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-01 10:59:13.716  1015  1028 W ActivityManager: mDVFSHelper.acquire()
09-01 10:59:13.726  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-01 10:59:13.726  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-01 10:59:13.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:13.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:13.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:13.726  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:13.736  6223  6223 E Zygote  : MountEmulatedStorage()
09-01 10:59:13.736  6223  6223 I libpersona: KNOX_SDCARD checking this for 10155
09-01 10:59:13.736  6223  6223 E Zygote  : v2
09-01 10:59:13.736  6223  6223 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:13.746  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 10:59:13.746  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-01 10:59:13.746   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-01 10:59:13.746  1015  1028 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6223 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-01 10:59:13.746  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-01 10:59:13.746  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 10:59:13.756  6223  6223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:13.756  1015  1028 D InputDispatcher: Focused application set to: xxxx
09-01 10:59:13.756  1015  1028 D InputDispatcher: Focus left window: 3141
09-01 10:59:13.756  6212  6212 D AndroidRuntime: Shutting down VM
09-01 10:59:13.756  6223  6223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:13.756  6223  6223 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-01 10:59:13.776  6223  6223 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:13.776  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:13.776  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-01 10:59:13.786  6223  6223 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:13.786  1015  1015 V ActivityManager: Display changed displayId=0
09-01 10:59:13.796  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-01 10:59:13.806  1015  1475 D PersonaManager: isKioskContainerExistOnDevice
09-01 10:59:13.806  3141  3141 V ActivityThread: updateVisibility : ActivityRecord{133f6d9d token=android.os.BinderProxy@1d36d578 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-01 10:59:13.836   257   427 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-01 10:59:13.846   257   429 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-01 10:59:13.916  6223  6223 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-01 10:59:13.926  6223  6223 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3557-3558)
09-01 10:59:13.926  6223  6223 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 10:59:13.966  6212  6212 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-01 10:59:13.966  6223  6223 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3ca3c7e9}
09-01 10:59:13.966  6223  6223 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 10:59:13.966  6223  6223 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 10:59:14.006  6223  6223 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-01 10:59:14.006  6223  6223 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:14.006  6223  6223 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-01 10:59:14.026  6223  6223 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-01 10:59:14.026  6223  6223 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
09-01 10:59:14.026  6223  6223 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-01 10:59:14.026  6223  6223 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:14.026  6223  6223 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:14.026  6223  6223 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:14.026  6223  6223 I Adreno-EGL: Local Branch: 
09-01 10:59:14.026  6223  6223 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:14.026  6223  6223 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:14.026  6223  6223 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:14.156  6223  6249 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-01 10:59:14.206  6223  6223 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:14.216  6223  6223 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 10:59:14.226  6223  6223 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-01 10:59:14.226  6223  6223 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-01 10:59:14.236  6223  6223 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-01 10:59:14.236  6223  6223 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:14.236  6223  6223 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:14.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:14.286  6223  6262 D OpenGLRenderer: Render dirty regions requested: true
,09-01 10:59:14.286  1015  1475 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-01 10:59:14.286  1015  1475 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-01 10:59:14.286  1015  1475 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-01 10:59:14.286  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-01 10:59:14.286  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-01 10:59:14.306  6223  6223 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-01 10:59:14.306  6223  6223 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-01 10:59:14.306   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-01 10:59:14.316  1015  1138 D InputDispatcher: Focus entered window: 6223
,09-01 10:59:14.316  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:14.316  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:14.326  6223  6223 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-01 10:59:14.326  6223  6262 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 10:59:14.326  6223  6262 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-01 10:59:14.326  6223  6262 D OpenGLRenderer: Enabling debug mode 0
,09-01 10:59:14.346  6223  6223 V ActivityThread: updateVisibility : ActivityRecord{1e85b0b8 token=android.os.BinderProxy@28ff7d2a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-01 10:59:14.376  1015  3154 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:14.376  1175  1175 D PanelView: There is/are notification(s) 
,09-01 10:59:14.376  1015  6265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:14.386  1814  1814 I SamsungIME: getCurrentCandidateView
,09-01 10:59:14.396  6223  6223 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-01 10:59:14.396  6223  6223 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28ff7d2a time:114022
,09-01 10:59:14.396  1015  1046 I ActivityManager: Displayed Component not be shown by security: +589ms (total +670ms)
,09-01 10:59:14.396  1015  1046 W ActivityManager: mDVFSHelper.release()
09-01 10:59:14.396  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f76414 u0 com.test.thalitest/.MainActivity t128} time:114026
,09-01 10:59:14.396   257   429 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-01 10:59:14.406   257  1037 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-01 10:59:14.476  6223  6223 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6223
,09-01 10:59:14.496  1814  1814 D SamsungIME: Dismiss ExpandCandiate
,09-01 10:59:14.586  6223  6223 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 10:59:14.626  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,09-01 10:59:14.666  1814  1814 I SamsungIME: getDebugLevel  : 0x4f4c
,09-01 10:59:14.676  1814  1814 I SamsungIME: KeybaordView init() : load resources
,09-01 10:59:14.686  6223  6267 D jxcore_app_log: JniHelper::setJavaVM(0xb70f3328), pthread_self() = -1218085736
,09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 10:59:14.696  6223  6267 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2422b7e8 added. We now have 1 listener(s)
,09-01 10:59:14.706  1814  1814 I SamsungIME: getCurrentKeyboard
09-01 10:59:14.706  1814  1814 I SamsungIME: getTextKeyboard
,09-01 10:59:14.706  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-01 10:59:14.706  6223  6267 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:14.706  6223  6267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:14.706  6223  6267 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:14.716  1814  1814 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 10:59:14.726  6223  6267 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ee68ee7 added. We now have 1 listener(s)
,09-01 10:59:14.726  6223  6267 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:14.726  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:14.726  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 10:59:14.726  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-01 10:59:14.726  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 10:59:14.726  6223  6267 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 10:59:14.736  6223  6267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:14.736  6223  6267 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-01 10:59:14.746  6223  6267 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:14.746  6223  6267 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:14.746  6223  6267 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 10:59:14.746  6223  6267 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:14.746  6223  6267 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 10:59:14.746  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:14.746  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:14.776  6223  6223 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 10:59:15.086  5412  5412 D FactoryTest: Not factory mode
,09-01 10:59:15.086  5412  5412 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-01 10:59:15.086  5412  5412 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-01 10:59:15.086  5412  5412 D MTPRx   : still no open session command from host, so toast
,09-01 10:59:15.086  5412  5412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-01 10:59:15.086  5412  5412 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114718
09-01 10:59:15.086  5412  5412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-01 10:59:15.086  1015  3140 E PersonaManagerService: inState():  stateMachine is null !!
,09-01 10:59:15.086  1015  3140 I PersonaManagerService: PersonaId don't exist
09-01 10:59:15.086  1015  3140 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-01 10:59:15.096  1015  3140 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.096  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:15.096  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:15.096  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-01 10:59:15.096  1015  3140 W ActivityManager: mDVFSHelper.acquire()
,09-01 10:59:15.106  1015  3140 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:15.116  1015  3140 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-01 10:59:15.116  1015  3140 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.116  1015  3140 D InputDispatcher: Focused application set to: xxxx
,09-01 10:59:15.116  1015  3140 D InputDispatcher: Focus left window: 6223
,09-01 10:59:15.116  5412  5412 E MTPRx   : started activity for popup
,09-01 10:59:15.116  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-01 10:59:15.126  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:15.146  5412  5412 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:15.176  5412  5412 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-01 10:59:15.176  1015  3162 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-01 10:59:15.176  1015  3162 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-01 10:59:15.176  1015  3162 D InputDispatcher: Focused application set to: xxxx
,09-01 10:59:15.176  1015  3162 D InputDispatcher: Focus entered window: 6223
,09-01 10:59:15.176  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,09-01 10:59:15.186  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101,
,09-01 10:59:15.186  1015  1476 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:15.186  1015  1476 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@355bc537 attribute=null, token = android.os.BinderProxy@1a313c47
,09-01 10:59:15.226  5412  5412 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-01 10:59:15.226  5412  5412 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-01 10:59:15.226  5412  5412 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-01 10:59:15.246  6223  6223 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-01 10:59:15.246  6223  6223 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-01 10:59:15.246  6223  6223 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 10:59:15.246  6223  6223 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-01 10:59:15.256  1015  3154 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-01 10:59:15.256  1015  3154 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-01 10:59:15.256  1015  3154 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-01 10:59:15.256  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-01 10:59:15.256  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-01 10:59:15.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:15.256  1814  6271 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-01 10:59:15.266  6223  6223 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 10:59:15.266  6223  6223 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 10:59:15.266  6223  6223 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c17d59 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@39e3e380, 16908290=android.view.AbsSavedState$1@39e3e380}, android:focusedViewId=100}]}]
09-01 10:59:15.266  6223  6223 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-01 10:59:15.276  1015  1475 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:15.276  6223  6223 V ActivityThread: updateVisibility : ActivityRecord{1e85b0b8 token=android.os.BinderProxy@28ff7d2a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-01 10:59:15.276  6223  6223 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
09-01 10:59:15.276  6223  6223 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-01 10:59:15.276  6223  6223 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@28ff7d2a time:114904
,09-01 10:59:15.306  6223  6275 W jxcore-log: Initializing JXcore engine
09-01 10:59:15.306  6223  6275 W jxcore-log: JXcore engine is ready
,09-01 10:59:15.356  1901  1901 E audit   : type=1400 msg=audit(1472720355.356:205): avc:  denied  { ioctl } for  pid=6275 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-01 10:59:15.356  1901  1901 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:15.356  1901  1901 E audit   : type=1300 msg=audit(1472720355.356:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ed008f8 items=0 ppid=302 ppcomm=main pid=6275 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-01 10:59:15.356  1901  1901 E audit   : type=1320 msg=audit(1472720355.356:205): 
,09-01 10:59:15.366  6223  6275 W jxcore-log: Starting JXcore engine
,09-01 10:59:15.476  6223  6275 W jxcore-log: Platform android,
09-01 10:59:15.476  6223  6275 W jxcore-log: 
09-01 10:59:15.476  6223  6275 W jxcore-log: Process ARCH arm,
09-01 10:59:15.476  6223  6275 W jxcore-log: 
,09-01 10:59:15.676  6223  6275 I jxcore-log: JXcore Cordova bridge is ready!
09-01 10:59:15.676  6223  6275 I jxcore-log: 
,09-01 10:59:15.676  6223  6275 W jxcore-log: JXcore engine is started
,09-01 10:59:15.686  6223  6267 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 10:59:15.686  6223  6223 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,09-01 10:59:16.236   287   287 E SMD     : DCD OFF
,09-01 10:59:16.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:16.436  1015  1138 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:16.436  1015  1138 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4021, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-01 10:59:16.436  1015  1138 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-01 10:59:16.436  1015  1138 D BatteryService: stay LED for charging
,09-01 10:59:16.436  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:16.446  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-01 10:59:16.446  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-01 10:59:16.446  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-01 10:59:16.446  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-01 10:59:16.446  1015  1015 I MotionRecognitionService: Plugged
,09-01 10:59:16.446  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:16.466  2637  2637 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-01 10:59:16.466  2637  2719 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:16.476  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:16.476  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:16.476  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:17.056  1015  2741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-01 10:59:17.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:18.096  1015  1041 W ActivityManager: mDVFSHelper.release(),
,09-01 10:59:18.176  1015  2703 D SSRM:n  : SIOP:: AP = 320,
,09-01 10:59:18.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:19.236   287   287 E SMD     : DCD OFF,
,09-01 10:59:19.256   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-01 10:59:20.376  1015  1094 V AlarmManager: waitForAlarm result :4
,09-01 10:59:20.376  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,09-01 10:59:20.396  1913  1913 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-01 10:59:20.426  1015  1314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.426  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.426  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.436  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:20.436  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.496  3781  3781 D ConnectivityManager: CallingUid : 10012, CallingPid : 3781
,09-01 10:59:20.496  1015  3140 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 10:59:20.496  1015  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-01 10:59:20.496  1015  1132 D ConnectivityService: apparently satisfied.  currentScore=60
,09-01 10:59:20.496  1015  1132 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-01 10:59:20.506  3781  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:20.556  3781  6282 W DriveInitializer: Background init thread started
,09-01 10:59:20.576   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-01 10:59:20.576   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:20.576  3781  6282 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-01 10:59:20.626  1015  1559 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:20.626  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.636  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.636  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.636  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.656  1015  3161 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-01 10:59:20.656  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.676  1015  1559 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:20.676  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.676  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.676  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.676  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.686  3781  6282 W DriveInitializer: Background init thread ended
,09-01 10:59:20.706  3781  6290 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-01 10:59:20.706  3781  6290 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-01 10:59:20.716  1913  1913 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-01 10:59:20.746  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.746  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.746  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.826  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.826  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
09-01 10:59:20.826  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:20.826  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:20.826  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.856  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:20.856  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-01 10:59:20.856  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:20.856  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.856  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.916  1015  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:20.916  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.916  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.916  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:20.956  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:20.956  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:20.956  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:20.956  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.006  1015  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.006  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.006  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.006  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.016  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:21.016  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:21.016  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:21.016  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:21.036  6295  6295 E Zygote  : MountEmulatedStorage(),
09-01 10:59:21.036  6295  6295 E Zygote  : v2
09-01 10:59:21.036  6295  6295 I libpersona: KNOX_SDCARD checking this for 10012
09-01 10:59:21.036  6295  6295 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:21.036  1015  1314 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6295 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,09-01 10:59:21.036  6295  6295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:21.046  6295  6295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:21.046  6295  6295 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-01 10:59:21.066  6295  6295 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:21.066  6295  6295 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:21.076  6295  6295 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-01 10:59:21.076  6295  6295 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-01 10:59:21.116  6295  6295 I MultiDex: VM with version 2.1.0 has multidex support
09-01 10:59:21.116  6295  6295 I MultiDex: install
09-01 10:59:21.116  6295  6295 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-01 10:59:21.146  6295  6295 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-01 10:59:21.206  6295  6295 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 10:59:21.206  6295  6295 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e3cd88a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-01 10:59:21.206  6295  6295 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-01 10:59:21.246  6295  6295 D ChimeraCfgMgr: Reading stored module config
,09-01 10:59:21.336  6295  6295 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-01 10:59:21.336  6295  6295 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-01 10:59:21.376  6295  6312 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-01 10:59:21.376  1015  3154 I art     : Explicit concurrent mark sweep GC freed 56373(3MB) AllocSpace objects, 24(384KB) LOS objects, 33% free, 28MB/42MB, paused 2.628ms total 165.203ms
,09-01 10:59:21.436  1015  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-01 10:59:21.436  1015  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.446   282   695 D WVCdm   : Instantiating CDM.
,09-01 10:59:21.446   282   685 I WVCdm   : CdmEngine::OpenSession
,09-01 10:59:21.446   282   685 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-01 10:59:21.446  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.446  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.446  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.466  1015  3162 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.476  1015  3162 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:21.476  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.476  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.476   282   685 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-01 10:59:21.506   282   685 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-01 10:59:21.506   282   685 D DrmWidevineDash: Service_Initialize: starts!
09-01 10:59:21.506   282   685 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-01 10:59:21.506   282   685 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 10:59:21.516  6295  6309 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-01 10:59:21.516  6295  6309 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-01 10:59:21.516  6295  6309 I System.out: (HTTPLog)-Static: isShipBuild true
09-01 10:59:21.516  6295  6309 I System.out: (HTTPLog)-Thread-1060-785388239: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-01 10:59:21.516  6295  6309 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:21.516   282   685 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-01 10:59:21.516   282   685 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-01 10:59:21.516   282   685 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-01 10:59:21.516   282   685 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 10:59:21.516   282   685 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-01 10:59:21.516   282   685 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-01 10:59:21.516   282   685 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-01 10:59:21.516   282   685 D QSEECOMAPI: : App is not loaded in QSEE
,09-01 10:59:21.516   276   984 D EnterpriseController: uids 10012
09-01 10:59:21.516   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:21.516   276   984 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-01 10:59:21.526  1015  3166 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-01 10:59:21.526  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-01 10:59:21.526  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.526  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.526  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.526  1913  1913 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=75c91a91-e574-4963-8c8e-fe08143fd166
,09-01 10:59:21.536  1913  1913 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-01 10:59:21.536  1913  1913 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-01 10:59:21.546   282   685 D QSEECOMAPI: : Loaded image: APP id = 11
,09-01 10:59:21.546   282   685 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-01 10:59:21.546   282   685 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-01 10:59:21.546   282   685 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-01 10:59:21.546   282   685 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1710000
09-01 10:59:21.546   282   685 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1710000
,09-01 10:59:21.546   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.556   426   438 D DrmLibTime: got the req here! ret=0
09-01 10:59:21.556   426   438 D DrmLibTime: command id, time_cmd_id = 770
09-01 10:59:21.556   426   438 D DrmLibTime: time_getutcsec starts!
09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-01 10:59:21.556   426   438 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
09-01 10:59:21.556   426   438 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-01 10:59:21.556   426   438 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-01 10:59:21.556   426   438 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!,
09-01 10:59:21.556   317   558 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-01 10:59:21.556   317  6320 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-01 10:59:21.556   317  6320 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2,
09-01 10:59:21.556   317  6320 D QC-time-services: offset is: 0 for base: 0,
,09-01 10:59:21.556   426   438 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,09-01 10:59:21.556   426   438 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472720361
09-01 10:59:21.556   426   438 D DrmLibTime: time_getutcsec returns 0, sec = 1472720361; nsec = 0
09-01 10:59:21.556   426   438 D DrmLibTime: time_getutcsec finished! 
09-01 10:59:21.556   426   438 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-01 10:59:21.556   426   438 D DrmLibTime: before calling ioctl to read the next time_cmd
,09-01 10:59:21.566   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.566   317   558 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-01 10:59:21.566  6295  6309 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:21.566  6295  6309 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6295, getuid(): 10012
,09-01 10:59:21.576  1015  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.576  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.576  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.576  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.576   282   685 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-01 10:59:21.576   282   685 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 10:59:21.576   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.576   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-01 10:59:21.576   282   685 D DrmWidevineDash: hlos api version =  9
09-01 10:59:21.576   282   685 D DrmWidevineDash: tz api version =  9
09-01 10:59:21.576   282   685 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-01 10:59:21.576   282   685 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-01 10:59:21.576   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-01 10:59:21.616   282   685 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1943960
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb75fabe8, dataLength=8
09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-01 10:59:21.616  1640  4319 I art     : Explicit concurrent mark sweep GC freed 1409(48KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.338ms total 27.870ms
,09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb75880e8, wrapped_rsa_key_length=1280
09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.616   282   685 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.616   282   685 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-01 10:59:21.616   282   685 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-01 10:59:21.616   282   282 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,09-01 10:59:21.626   282   282 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-01 10:59:21.626   282   282 I WVCdm   : CdmEngine::GenerateKeyRequest
09-01 10:59:21.626   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb75ef628, idLength=0xbee12f80
09-01 10:59:21.626   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.636   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-01 10:59:21.636   282   282 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-01 10:59:21.636   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xbee12f96, maximum = 0xbee12f97
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.646   282   282 D DrmWidevineDash: hlos api version =  9
09-01 10:59:21.646   282   282 D DrmWidevineDash: tz api version =  9
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xbee13004
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-01 10:59:21.646   282   282 D WVCdm   : PrepareKeyRequest: nonce=3932736917
09-01 10:59:21.646   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb75c39a0
09-01 10:59:21.646   282   282 D DrmWidevineDash: message_length=1599, signature=0xb75bf7c8, signature_length=0xbee12f64
09-01 10:59:21.646   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.786  1913  2132 I art     : Explicit concurrent mark sweep GC freed 57116(3MB) AllocSpace objects, 10(400KB) LOS objects, 40% free, 14MB/23MB, paused 1.441ms total 71.356ms
,09-01 10:59:21.796   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.796   282   282 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-01 10:59:21.796   282   695 I WVCdm   : CdmEngine::CloseSession
09-01 10:59:21.796   282   695 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-01 10:59:21.796   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-01 10:59:21.796   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.796   282   695 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-01 10:59:21.796   282   695 I WVCdm   : L3 Terminate.
09-01 10:59:21.796   282   695 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-01 10:59:21.796   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-01 10:59:21.796   282   695 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-01 10:59:21.796   282   695 D DrmWidevineDash: Service_Uninitialize: starts!
09-01 10:59:21.796   282   695 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-01 10:59:21.796   282   695 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-01 10:59:21.796   282   695 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-01 10:59:21.796   282   695 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-01 10:59:21.836  1913  2107 W GCoreFlp: No location to return for getLastLocation()
,09-01 10:59:21.846  6295  6309 I qtaguid : Untagging socket 30
,09-01 10:59:21.876  1015  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.876  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.876  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.876  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.886  3781  6291 D UdcContextInitService: registered all accounts: true
,09-01 10:59:21.886  1015  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.886  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:21.886  1015  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:21.886  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.886  1015  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:21.906  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:21.906  1913  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-01 10:59:21.906  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:21.906  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:21.926  1913  2132 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-01 10:59:22.036  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:22.036  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-01 10:59:22.036  1015  1027 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:22.036  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.036  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.076  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-01 10:59:22.076  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-01 10:59:22.086  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.086  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.086  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.166  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.166  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:22.176  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.176  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.186  1015  1314 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-01 10:59:22.186  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-01 10:59:22.186  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.186  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.186  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.206  1913  2132 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.206   276   984 D EnterpriseController: uids 10012
09-01 10:59:22.206   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:22.206   276   984 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-01 10:59:22.206  1913  2132 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:22.216  1913  2132 I qtaguid : Tagging socket 71 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:22.216  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.216  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.216  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.216  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.236   287   287 E SMD     : DCD OFF
,09-01 10:59:22.256  1913  2132 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:22.266  1015  3162 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.266  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.266  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.266  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.266  1913  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-01 10:59:22.266  1913  6325 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-01 10:59:22.266  1015  3154 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.266  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.276  1015  3154 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.276  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.286  6332  6332 I dex2oat : ----------------------------------------------------
09-01 10:59:22.286  6332  6332 I dex2oat : <SS>: S T A R T I N G . . .
09-01 10:59:22.286  6332  6332 I dex2oat : <SS>: Zip is absent. Canceled.
,09-01 10:59:22.286  6332  6332 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-01 10:59:22.296  1015  3161 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.296  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.296  1015  3161 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.296  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.296  1913  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
09-01 10:59:22.296  1913  6325 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-01 10:59:22.296  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-01 10:59:22.296  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:22.306  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:22.306  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.326  6332  6332 I dex2oat : dex2oat took 33.136ms (threads: 4)
,09-01 10:59:22.326  1015  1500 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:22.326  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:22.326  1015  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:22.326  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:22.336  1913  6331 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-01 10:59:22.336  1913  6325 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-01 10:59:22.336  1913  6325 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-01 10:59:22.336  6295  6309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.336  6295  6309 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.336  6295  6309 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.336  6295  6309 I Adreno-EGL: Local Branch: 
09-01 10:59:22.336  6295  6309 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.336  6295  6309 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.336  6295  6309 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.346  1913  6325 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 10:59:22.406  1015  1476 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.426  6295  6309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.426  6295  6309 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.426  6295  6309 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.426  6295  6309 I Adreno-EGL: Local Branch: 
09-01 10:59:22.426  6295  6309 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.426  6295  6309 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.426  6295  6309 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.446  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.446   276   984 D EnterpriseController: uids 10012
09-01 10:59:22.446   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:22.446   276   984 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-01 10:59:22.446  1913  6325 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:22.446  1913  6325 I qtaguid : Tagging socket 77 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:22.486  1913  6325 I qtaguid : Tagging socket 80 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:22.516  6295  6309 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:22.516  6295  6309 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:22.516  6295  6309 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:22.516  6295  6309 I Adreno-EGL: Local Branch: 
09-01 10:59:22.516  6295  6309 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:22.516  6295  6309 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:22.516  6295  6309 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:22.816  1015  3161 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.826  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.826  1913  6325 I qtaguid : Tagging socket 77 with tag fffff6c300000000{4294964931,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:22.906  1913  6293 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.906  1913  6293 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-01 10:59:22.906  1913  6293 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:22.916  1015  1558 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:22.926  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:22.926  1913  6325 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:22.936  1913  6293 I qtaguid : Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:23.046  1015  1557 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:23.056  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:23.056  1913  6325 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:23.096  1913  2132 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-01 10:59:23.096  1913  2132 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-01 10:59:23.106  1913  2132 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-01 10:59:21.990+0200, stopTime=2016-09-01 10:59:23.109+0200, duration=1119ms
,09-01 10:59:23.116  1913  6343 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:23.116   276   984 D EnterpriseController: uids 10012
09-01 10:59:23.116   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:23.116   276   984 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-01 10:59:23.126  1913  6343 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:23.126  1913  6343 I qtaguid : Tagging socket 85 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:23.156  1913  6343 I qtaguid : Tagging socket 87 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:23.186  1015  1475 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:23.196  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:23.196  1913  6325 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:23.316  1015  3162 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-01 10:59:23.326  1913  6325 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:23.326  1913  6325 I qtaguid : Tagging socket 77 with tag 1106583100000000{285628465,0} for uid -1, pid: 1913, getuid(): 10012
,09-01 10:59:23.366  1913  6343 I qtaguid : Untagging socket 85
,09-01 10:59:23.376  1913  2132 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-01 10:59:23.776  1015  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-01 10:59:24.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:25.216  1913  6344 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-01 10:59:25.216  1913  6344 I qtaguid : Tagging socket 85 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1913, getuid(): 10012
,09-01 10:59:25.236   287   287 E SMD     : DCD OFF
,09-01 10:59:25.256   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:25.426  1913  6344 I qtaguid : Untagging socket 85
,09-01 10:59:25.426  1913  2132 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-01 10:59:25.456  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-01 10:59:26.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:26.496  1015  1559 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:26.496  1015  1559 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4020, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-01 10:59:26.496  1015  1559 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-01 10:59:26.496  1015  1559 D BatteryService: stay LED for charging
,09-01 10:59:26.496  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:26.506  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-01 10:59:26.506  1015  1015 I MotionRecognitionService: Plugged
09-01 10:59:26.506  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-01 10:59:26.506  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-01 10:59:26.506  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-01 10:59:26.506  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-01 10:59:26.516  2637  2637 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-01 10:59:26.516  2637  2719 D HeadsetStateMachine: Disconnected process message: 10
,09-01 10:59:26.526  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:26.526  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:26.526  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:27.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:27.896  1015  1027 I ActivityManager: Killing 5331:com.google.android.talk/u0a104 (adj 15): empty #31
,09-01 10:59:28.096  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
,09-01 10:59:28.206  1015  2703 D SSRM:n  : SIOP:: AP = 330
,09-01 10:59:28.236   287   287 E SMD     : DCD OFF
,09-01 10:59:28.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 10:59:28.256  6223  6275 I jxcore-log: 
,09-01 10:59:28.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 10:59:28.256  6223  6275 I jxcore-log: 
,09-01 10:59:28.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:28.266  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:28.266  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:28.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 10:59:28.266  6223  6275 I jxcore-log: 
,09-01 10:59:28.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 10:59:28.266  6223  6275 I jxcore-log: 
,09-01 10:59:28.916  6223  6275 D executeNativeTests: Running unit tests
,09-01 10:59:28.996  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:28.996  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 added. We now have 2 listener(s)
,09-01 10:59:28.996  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-01 10:59:28.996  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:28.996  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:28.996  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:28.996  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 added. We now have 2 listener(s)
09-01 10:59:28.996  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:28.996  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:28.996  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.006  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:29.006  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:29.006  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:29.006  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.006  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:29.006  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:29.006  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 10:59:29.006  6223  6275 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 10:59:29.016  6223  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:29.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:29.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 10:59:29.016  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:29.016  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:29.016  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.016  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.016  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:29.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 removed from the list
09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 removed from the list
09-01 10:59:29.016  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.016  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:29.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.016  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.026  6223  6275 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-01 10:59:29.026  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.026  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.026  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.026  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.026  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.026  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 10:59:29.026  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.026  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.026  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.026  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.026  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.026  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.026  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections,: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 10:59:29.036  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.036  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.036  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.036  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.036  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.036  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.036  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.036  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.036  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.036  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.036  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.036  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.036  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.036  6223  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:29.036  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.046  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:29.046  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.046  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:29.046  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:29.046  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:29.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:29.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:29.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:29.046  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:29.046  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:29.056  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:29.056  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:29.066  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:29.066  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:29.066  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:29.076  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:29.076  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 10:59:29.076  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 10:59:29.086  2637  2646 D BtGatt.GattService: registerClient() - UUID=142278d5-4dee-4368-8392-4fc1a8fc80e1
,09-01 10:59:29.136  2637  2707 D BtGatt.GattService: onClientRegistered() - UUID=142278d5-4dee-4368-8392-4fc1a8fc80e1, clientIf=6
,09-01 10:59:29.136  6223  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:29.136  2637  2967 D BtGatt.GattService: start scan with filters
,09-01 10:59:29.136  2637  2717 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:29.146  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 10:59:29.146  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:29.146  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:29.146  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:29.146  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.146  2637  2717 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:29.156  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.156  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:29.156  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:29.156  2637  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:29.156  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.156  2637  2717 D BtGatt.ScanManager: allow scan with filters
,09-01 10:59:29.156  2637  2717 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 10:59:29.166  2637  2717 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-01 10:59:29.166  6223  6275 I io.jxcore.node.ConnectionHelper: start: OK,
,09-01 10:59:29.166  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 10:59:29.166  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.166  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.166  6223  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:29.166  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.166  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:29.166  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:29.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:29.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:29.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:29.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:29.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:29.166  2637  2717 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:29.166  2637  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-01 10:59:29.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:29.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:29.176  2637  2650 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:29.176  2637  2646 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:29.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:29.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:29.176  2637  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 10:59:29.176  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:29.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:29.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:29.186  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-01 10:59:29.186  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:29.186  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:29.186  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:29.186  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.186  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:29.186  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list,
,09-01 10:59:29.186  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.186  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.186  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:29.186  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.186  6223  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:29.186  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:29.186  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:29.186  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.196  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:29.196  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:29.196  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:29.196  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:29.196  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-01 10:59:29.196  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:29.196  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:29.196  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:29.206  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-01 10:59:29.206  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:29.206  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.206  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:29.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:29.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:29.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:29.216  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:29.216  2637  2646 D BtGatt.GattService: registerClient() - UUID=3e5c9abf-602a-4068-b983-52a385fe64b3
,09-01 10:59:29.236  2637  2717 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 51
,09-01 10:59:29.246  2637  2717 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.samsung.android.app.FileShareServer 4. Count : 1
,09-01 10:59:29.246  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.246  1015  1041 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.246  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,09-01 10:59:29.246  2637  2717 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.wssyncmldm 4. Count : 127
,09-01 10:59:29.256  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.256  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.256  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
,09-01 10:59:29.256  2637  2717 D BtGatt.ScanManager: Write on CV = 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 51
,09-01 10:59:29.256  1015  1557 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:29.256  2637  2707 D BtGatt.GattService: onClientRegistered() - UUID=3e5c9abf-602a-4068-b983-52a385fe64b3, clientIf=6
,09-01 10:59:29.256  1015  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.256  6223  6231 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 10:59:29.256  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.providers.context
09-01 10:59:29.266  2637  2724 D BtGatt.GattService: start scan with filters
,09-01 10:59:29.266   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-01 10:59:29.266  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:29.266  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:29.266  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:29.266  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:29.266  2637  2717 D BtGatt.ScanManager: filter size is 1
09-01 10:59:29.266  2637  2717 D BtGatt.ScanManager: delete FilterIndex - 3
,09-01 10:59:29.266  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.266  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.266  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:29.276  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:29.276  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.276  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 10:59:29.276  2637  2717 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:29.276  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:29.276  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.276  2637  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:29.276  6223  6275 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 10:59:29.276  2637  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:29.276  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.286  2637  2717 D BtGatt.ScanManager: handling starting scan
09-01 10:59:29.286  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:29.286  6223  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:29.286  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.286  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:29.286  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:29.286  2637  2724 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:29.286  2637  2650 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:29.286  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:29.286  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:29.286  2637  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:29.296  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:29.296  2637  2717 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:29.296  2637  2717 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:29.296  2637  2717 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-01 10:59:29.296  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:29.296  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:29.296  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.296  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:29.296  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.296  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.296  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.296  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:29.296  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:29.296  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 10:59:29.296  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:29.296  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.296  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.296  2637  2717 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 10:59:29.296  2637  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-01 10:59:29.296  6223  6275 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-01 10:59:29.306  2637  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 10:59:29.306  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.306  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.306  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:29.306  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-01 10:59:29.306  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:29.306  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 10:59:29.306  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:29.306  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:29.316  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:29.316  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:29.316  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:29.316  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.316  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:29.316  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.316  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.326  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:29.326  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:29.326  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:29.326  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:29.326  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:29.326  2637  2646 D BtGatt.GattService: registerClient() - UUID=fa59080a-1b02-4320-b621-86b348eb62a6
,09-01 10:59:29.336  2637  2717 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 1
,09-01 10:59:29.336  2637  2717 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:29.336  2637  2717 D BtGatt.ScanManager: delete FilterIndex - 4
,09-01 10:59:29.336  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-01 10:59:29.336  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.336  2637  2717 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:29.346  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-01 10:59:29.346  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.346  2637  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:29.356  2637  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:29.356  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.366  2637  2707 D BtGatt.GattService: onClientRegistered() - UUID=fa59080a-1b02-4320-b621-86b348eb62a6, clientIf=6
,09-01 10:59:29.366  6223  6231 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:29.366  2637  2724 D BtGatt.GattService: start scan with filters
,09-01 10:59:29.376  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:29.376  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:29.376  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:29.376  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:29.376  2637  2717 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:29.376  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.376  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:29.376  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:29.376  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:29.386  6223  6275 I io.jxcore.node.ConnectionHelper: start: OK
,09-01 10:59:29.386  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.386  6223  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:29.386  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.386  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:29.386  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.386  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:29.386  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:29.386  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:29.386  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:29.386  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:29.386  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:29.386  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:29.386  2637  2646 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:29.386  2637  2724 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:29.386  2637  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:29.386  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.386  2637  2717 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:29.386  2637  2717 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:29.386  2637  2717 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-01 10:59:29.386  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:29.396  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:29.396  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:29.396  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:29.396  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-01 10:59:29.396  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.396  2637  2717 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 10:59:29.396  2637  2717 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:29.396  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:29.396  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:29.396  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:29.406  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.406  6223  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:29.406  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.406  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.406  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:29.406  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.406  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.406  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.406  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:29.406  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.406  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.406  6223  6275 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-01 10:59:29.406  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:29.406  2637  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-01 10:59:29.406  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:29.406  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.406  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.406  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.406  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.406  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.406  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.406  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.406  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.406  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.406  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.416  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:29.416  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.416  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.416  6223  6275 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-01 10:59:29.416  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.416  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop,
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.416  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:29.416  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.416  6223  6275 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 10:59:29.416  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.416  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.416  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.416  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.416  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.416  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.416  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:29.426  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:29.426  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:29.426  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.426  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.426  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.426  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-01 10:59:29.426  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.426  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list,
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.426  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.426  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.426  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.426  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.426  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.426  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:29.426  6223  6275 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:29.426  6223  6275 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:29.426  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 10:59:29.426  6223  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:29.426  6223  6275 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:29.426  6223  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:29.426  6223  6275 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 10:59:29.426  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:29.426  6223  6275 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:29.426  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 10:59:29.436  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 10:59:29.436  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-01 10:59:29.436  6223  6275 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-01 10:59:29.436  6223  6275 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 10:59:29.436  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.436  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.436  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.436  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:29.436  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.436  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 10:59:29.436  6223  6356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
09-01 10:59:29.436  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.436  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.436  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.436  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.436  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.436  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.436  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.436  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.446  6223  6275 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-01 10:59:29.446  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.446  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.446  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.446  6223  6357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
,09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.446  6223  6275 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,09-01 10:59:29.446  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.446  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.446  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.446  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.446  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.446  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.446  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 10:59:29.446  6223  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 10:59:29.446  6223  6356 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:29.446  6223  6275 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 10:59:29.446  6223  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:29.446  6223  6275 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 10:59:29.446  6223  6275 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 10:59:29.456  6223  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 10:59:29.456  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:29.456  6223  6275 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 10:59:29.456  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.456  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.456  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6356 D BluetoothSocket: connect(): myUserId = 0
09-01 10:59:29.456  6223  6356 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:29.456  2637  2717 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 2
09-01 10:59:29.456  2637  2717 D BtGatt.ScanManager: filter size is 1
09-01 10:59:29.456  2637  2717 D BtGatt.ScanManager: delete FilterIndex - 5
,09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.456  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.456  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.456  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:2,9.456  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.456  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.456  2637  2646 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.456  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.456  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.456  6223  6356 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
,09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:29.466  6223  6223 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-01 10:59:29.466  6223  6223 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 10:59:29.466  6223  6358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:29.466  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:29.466  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:29.466  6223  6223 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-01 10:59:29.466  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.466  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.466  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.466  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.466  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.466  6223  6275 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-01 10:59:29.466  6223  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:29.466  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:29.466  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.466  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.466  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.466  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.466  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.466  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.466  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.466  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.476  2637  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:29.476  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.476  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.476  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.476  2637  2717 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:29.476  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:29.476  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ab675f6 not in the list
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:29.476  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:29.476  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-01 10:59:29.476  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e55df7 not in the list
,09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:29.476  6223  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:29.476  2637  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:29.476  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.476  6223  6275 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:29.476  6223  6275 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 10:59:29.476  2637  2717 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-01 10:59:29.476  6223  6275 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 10:59:29.476  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:29.476  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d58b201 added. We now have 2 listener(s)
09-01 10:59:29.476  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:29.486  2637  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
,09-01 10:59:29.486  2637  2707 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:29.486  6223  6275 D BluetoothAdapter: enable()
,09-01 10:59:29.486  6223  6275 D BluetoothAdapter: enable(): BT is already enabled..!
,09-01 10:59:29.496  1015  1559 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:29.496  1015  1559 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 10:59:29.496  1015  1559 D SecContentProvider2: mCursor = null
,09-01 10:59:29.496  1015  1559 D WifiService: setWifiEnabled: true pid=6223, uid=10155
,09-01 10:59:29.496  1015  1559 W ActivityManager: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:29.496  1015  1559 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:29.496  1015  1559 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:29.496  1015  1559 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-01 10:59:29.496  1015  1559 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:29.496  1015  1559 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:29.496  1015  1559 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:29.496  1015  1559 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 10:59:29.496  1015  1559 D SettingsProvider: name = wifi_on
,09-01 10:59:29.496  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:29.496  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12c648a6 added. We now have 3 listener(s)
09-01 10:59:29.496  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:29.506  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:29.506  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ef3b2e7 added. We now have 4 listener(s)
09-01 10:59:29.506  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:29.506  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:29.506  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13efbe94 added. We now have 5 listener(s)
09-01 10:59:29.506  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:29.506  1015  1558 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:29.506  1015  1558 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:29.506  1015  1558 D SecContentProvider2: mCursor = null
,09-01 10:59:29.506  1015  1558 D WifiService: setWifiEnabled: false pid=6223, uid=10155
,09-01 10:59:29.506  1015  1558 D SettingsProvider: name = wifi_on
,09-01 10:59:29.516  1015  1130 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 10:59:29.516  2099  2099 I wpa_supplicant: reset timer : RESET_TIMER 0,
09-01 10:59:29.516  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-01 10:59:29.516  2099  2099 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:29.526  2099  2099 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-01 10:59:29.526  6223  6275 D BluetoothAdapter: disable()
,09-01 10:59:29.526  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:29.526  1015  1027 D SettingsProvider: name = bluetooth_on
,09-01 10:59:29.536  1015  1130 E WifiNative-wlan0: do suspend true
,09-01 10:59:29.536  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:29.536  2637  2704 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-01 10:59:29.536  2637  2704 D BluetoothAdapterProperties: Setting state to 13
09-01 10:59:29.536  2637  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 10:59:29.536  2637  2704 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:29.536  2637  2704 D BluetoothAdapterService: updateAdapterState state is 13
,09-01 10:59:29.536  1015  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:29.536  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:29.536  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.536  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:29.536  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:29.546  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.546  2637  2637 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.546  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:29.546  2637  2637 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5e5c273, channel: 19, state: LISTENING
09-01 10:59:29.546  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
09-01 10:59:29.546  2637  2704 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:29.546  2637  2704 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-01 10:59:29.546  2637  2637 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@5e5c273, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@e3cd88a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c050530mSocket: android.net.LocalSocket@28d805a9 impl:android.net.LocalSocketImpl@3f6a172e fd:FileDescriptor[74]
09-01 10:59:29.546  2637  2704 D BluetoothAdapterService: terminating service from this receiver
09-01 10:59:29.546  2637  2637 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28d805a9 impl:android.net.LocalSocketImpl@3f6a172e fd:FileDescriptor[74]
09-01 10:59:29.546  1015  3154 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:29.546  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:29.546  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:29.546  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.546  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:29.546  2637  2704 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 10:59:29.546  2637  2704 D BluetoothAdapterProperties: mDiscovering is false
09-01 10:59:29.546  1015  3161 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-01 10:59:29.546  1322  1322 D BluetoothPbap: Proxy object disconnected
,09-01 10:59:29.546  1322  1322 D PbapServerProfile: Bluetooth service disconnected
09-01 10:59:29.546  2637  2704 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-01 10:59:29.546  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:29.556  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.556  2637  2707 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 10:59:29.556  2637  2707 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:29.556  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.566  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:29.566  2637  2704 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 10:59:29.566  2637  2704 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-01 10:59:29.566  2637  2704 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:29.566  2637  2704 E bt-btif : cmd socket is not created
,09-01 10:59:29.566  2637  2704 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-01 10:59:29.566  2637  4988 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 10:59:29.566  2637  2801 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-01 10:59:29.566  2637  2801 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-01 10:59:29.566  6223  6356 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3b7e4932, channel: -1, state: INIT
09-01 10:59:29.566  6223  6356 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3b7e4932, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1dbe9683, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28543000mSocket: android.net.LocalSocket@3278a039 impl:android.net.LocalSocketImpl@2343c67e fd:FileDescriptor[107]
09-01 10:59:29.566  6223  6356 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3278a039 impl:android.net.LocalSocketImpl@2343c67e fd:FileDescriptor[107]
,09-01 10:59:29.566  6223  6356 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
09-01 10:59:29.566  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:29.566  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:29.566  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:29.566  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:29.566  2637  2801 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:29.566  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.586  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:29.586  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-01 10:59:29.596  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:29.596  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:29.606  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:29.606  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-01 10:59:29.606  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:29.606  1814  1814 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-01 10:59:29.606  1015  1559 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
09-01 10:59:29.606  1015  1216 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:29.606  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:29.606  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
09-01 10:59:29.606  2637  2637 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, state: LISTENING
09-01 10:59:29.606  2637  2637 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f6d445c, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2067eb18, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@37825365mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
09-01 10:59:29.606  2637  2637 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d04783a impl:android.net.LocalSocketImpl@e650ceb fd:FileDescriptor[76]
,09-01 10:59:29.606  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 10:59:29.606  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:29.606  2637  2637 I BtOppRfcommListener: stopping Accept Thread
09-01 10:59:29.606  2637  2637 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, state: LISTENING
,09-01 10:59:29.606  2637  2637 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@13b84a48, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28b7eee2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@7c9c0e1mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
09-01 10:59:29.606  2637  2637 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@18b1de06 impl:android.net.LocalSocketImpl@34058cc7 fd:FileDescriptor[80]
,09-01 10:59:29.616  2637  4988 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 10:59:29.616  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.616  1015  1314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:29.616  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:29.616  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.616  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:29.616  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:29.616  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:29.616  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:29.626  1015  1559 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 10:59:29.626  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:29.626  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:29.626  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:29.626  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:29.636  2637  2637 V BluetoothOppManager: cleanUp...
,09-01 10:59:29.646  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:29.646  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:29.656  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:29.656  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 10:59:29.656  1015  3166 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-01 10:59:29.656  1015  3166 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.656  1015  3166 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.656  1015  3166 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.656  1015  3166 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.666  1015  3166 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6364 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,09-01 10:59:29.666  6364  6364 E Zygote  : MountEmulatedStorage()
09-01 10:59:29.666  6364  6364 I libpersona: KNOX_SDCARD checking this for 10003
09-01 10:59:29.666  6364  6364 E Zygote  : v2
09-01 10:59:29.666  6364  6364 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:29.676  6364  6364 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:29.676  6364  6364 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:29.676  6364  6364 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:29.696  6364  6364 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:29.696  6364  6364 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:29.726  6364  6364 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-01 10:59:29.756  6364  6364 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-01 10:59:29.766  6364  6364 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-01 10:59:29.766  6364  6364 D UserAnalysis: Create SecureDbHelper
,09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:29.766  2637  2801 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:29.766  2637  2892 I bt_userial_mct: exiting userial_read_thread
,09-01 10:59:29.766  2637  2801 W bt-btif : ag scb idx 1 not allocated
09-01 10:59:29.766  2637  2801 W bt-btif : ag scb idx 2 not allocated
09-01 10:59:29.766  2637  2801 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 10:59:29.766  2637  2892 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 10:59:29.766  2637  2707 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 10:59:29.766  2637  2803 I bt_vendor: hw_epilog_process
,09-01 10:59:29.766  2637  2707 D bt_userial_mct: userial_close
,09-01 10:59:29.766  2637  2707 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-01 10:59:29.766  6364  6364 D IntelligenceServiceApplication: onCreate()
,09-01 10:59:29.776  1015  1500 I ActivityManager: Killing 5763:com.google.android.gms:car/u0a12 (adj 15): empty #31
,09-01 10:59:29.776  1015  1500 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-01 10:59:29.776  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.776  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.776  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:29.776  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:29.786  6364  6364 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-01 10:59:29.796  6383  6383 E Zygote  : MountEmulatedStorage()
,09-01 10:59:29.796  6383  6383 E Zygote  : v2
09-01 10:59:29.796  6383  6383 I libpersona: KNOX_SDCARD checking this for 10107
,09-01 10:59:29.796  6383  6383 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:29.796  1015  1500 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6383 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-01 10:59:29.796  6383  6383 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:29.796  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0,
09-01 10:59:29.796  6364  6364 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-01 10:59:29.796  6383  6383 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:29.796  6383  6383 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:29.806  6364  6364 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-01 10:59:29.816  6383  6383 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:29.816  6383  6383 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:29.876  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-01 10:59:29.876   276   988 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:29.876  1913  4385 V NativeCrypto: Read error: ssl=0xb75fe010: I/O error during system call, Connection timed out,
09-01 10:59:29.886  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 10:59:29.886  1913  4385 V NativeCrypto: SSL shutdown failed: ssl=0xb75fe010: I/O error during system call, Broken pipe
,09-01 10:59:29.886  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:29.886  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:29.886  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.886  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.886  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.886  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.886  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:29.886  1913  4385 E GCM     : Wifi connection closed with errorCode 20
09-01 10:59:29.886  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-01 10:59:29.886  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:29.896  1015  1558 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-01 10:59:29.896  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:29.896  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:29.896  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-01 10:59:29.896  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:29.896  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-01 10:59:29.896  1015  2237 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-01 10:59:29.896  1015  2237 I qtaguid : Tagging socket 352 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,09-01 10:59:29.896  1015  2237 I qtaguid : Untagging socket 352
,09-01 10:59:29.896  1015  2237 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,09-01 10:59:29.906  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-01 10:59:29.926  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:29.926  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:29.926  1015  1125 D WifiP2pService: InactiveState{ what=131204 },
09-01 10:59:29.926  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-01 10:59:29.926  1015  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 10:59:29.926  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-01 10:59:29.926  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-01 10:59:29.926  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.926  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.926  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:29.926  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
09-01 10:59:29.926  1015  1015 D RttService: SCAN_AVAILABLE : 1
09-01 10:59:29.926  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:29.926  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:29.936  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 10:59:29.936  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:29.936  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 10:59:29.936  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 10:59:29.946  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:29.946  1015  1125 D WifiP2pService: P2pDisablingState
,09-01 10:59:29.946  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:29.946  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 10:59:29.946  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 10:59:29.946  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:29.946  1015  1046 D WifiDisplayController: disconnect
09-01 10:59:29.946  1015  1046 D WifiDisplayController: updateConnection
09-01 10:59:29.946  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:29.946  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:29.946  1015  1125 D WifiP2pService: p2p socket connection lost
09-01 10:59:29.946  1015  1125 D WifiP2pService: P2pDisabledState
,09-01 10:59:29.946  1015  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-01 10:59:29.946   276   984 D EnterpriseController: uids 1000
09-01 10:59:29.946   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:29.946   276   984 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-01 10:59:29.946  1015  1130 E WifiNative-wlan0: do suspend true
09-01 10:59:29.946  1015  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-01 10:59:29.946  1175  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-01 10:59:29.946  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-01 10:59:29.946  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-01 10:59:29.946  1015  2237 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:29.956  1015  1132 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-01 10:59:29.956  1015  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-01 10:59:29.956  1015  1132 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-01 10:59:29.956  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-01 10:59:29.956  3781  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-01 10:59:29.956  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 10:59:29.956  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:29.956  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:29.956  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-01 10:59:29.956  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:29.956  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:29.956  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-01 10:59:29.956  1456  1456 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 10:59:29.956  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
09-01 10:59:29.956  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 10:59:29.956   276   988 D CommandListener: Clearing all IP addresses on wlan0
09-01 10:59:29.956  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-01 10:59:29.956  1015  1132 D ConnectivityService: nai.networkMonitor.doQuit()
09-01 10:59:29.956  1015  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 10:59:29.956  1015  1132 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-01 10:59:29.956  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:29.956  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:29.956  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:29.956  1015  1557 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:29.966  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:29.966  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-01 10:59:29.966  1015  1123 V NetworkStats: updateIfacesLocked()
09-01 10:59:29.966  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:29.966  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-01 10:59:29.966  1015  1133 D Tethering: MasterInitialState.processMessage what=3
09-01 10:59:29.966  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-01 10:59:29.966  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 10:59:29.966  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:29.966  6223  6223 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:29.966  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-01 10:59:29.966  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-01 10:59:29.966  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:29.966  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:29.966  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:29.966  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-01 10:59:29.966  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:29.966  1015  1123 V NetworkStats: performPollLocked() took 7ms
,09-01 10:59:29.976  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:29.976  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:29.976  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-01 10:59:29.976  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:29.976  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:29.976  2099  2099 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 10:59:29.976  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:29.976  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:29.976  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.976  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.986  1015  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:29.986  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:29.986  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:29.986  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:29.986  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:29.986  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.986  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.986  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.986  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:29.986  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:29.986  1015  1130 D SecContentProvider2: mCursor = null
09-01 10:59:29.986  2637  2707 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-01 10:59:29.986  2637  2707 I bt_vendor: bluetooth satus is on
09-01 10:59:29.986  2637  2707 I bt_vendor: bt-vendor : resetting BT status
09-01 10:59:29.986  2637  2707 I bt_vendor: Starting hciattach daemon
09-01 10:59:29.986  2637  2707 I bt_vendor: try to set false
,09-01 10:59:29.996  2637  2707 I bt_vendor: Starting hciattach daemon
09-01 10:59:29.996  2637  2707 I bt_vendor: try to set false
09-01 10:59:29.996  2637  2707 I bt_vendor: cleanup
,09-01 10:59:29.996  2637  2801 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-01 10:59:29.996  2637  2707 I GKI_LINUX: GKI_exit_task 0 done
09-01 10:59:29.996  2637  2707 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-01 10:59:29.996  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:29.996  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:29.996  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.996  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.996  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.996  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:29.996  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:29.996  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-01 10:59:29.996  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:29.996  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:30.006  1175  1175 D HotspotTile: onReceive : 0, 0
,09-01 10:59:30.006  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:30.006  2637  2704 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-01 10:59:30.006  2637  2704 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:30.006  2637  2704 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-01 10:59:30.006  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-01 10:59:30.006  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:30.006  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:30.006  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:30.006  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-01 10:59:30.016  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:30.016  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:30.016  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.016  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.016  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.016  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.016  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:30.016  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:30.016  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:30.016  2637  2637 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:30.016  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,09-01 10:59:30.016  2637  2637 D BtGatt.GattService: Received stop request...Stopping profile...
,09-01 10:59:30.016  2637  2637 D BtGatt.GattService: stop()
09-01 10:59:30.016  2637  2637 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 10:59:30.026  1015  3162 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.016  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:30.026  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:30.016  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:30.026  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:30.026  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:30.026  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.026  1015  3162 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.026  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:30.026  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
09-01 10:59:30.026  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:30.026  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:30.026  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:30.026  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-01 10:59:30.026  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:30.026  2637  2637 D HeadsetService: Received stop request...Stopping profile...
09-01 10:59:30.026  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.026  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.026  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-01 10:59:30.026  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:30.026  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:30.026  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-01 10:59:30.026  1015  3161 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.026  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.036  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.036  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.036  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:30.036  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.036  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-01 10:59:30.036  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:30.036  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 10:59:30.036  1015  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.036  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 10:59:30.036  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-01 10:59:30.036  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.036  1322  1322 D HeadsetProfile: Bluetooth service disconnected
09-01 10:59:30.046  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.046  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:30.046  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:30.046  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 10:59:30.046  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 10:59:30.046  1015  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.046  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.046  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.046  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.046  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:30.046  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.046  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:30.056  2637  2704 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:30.056  1015  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:30.056  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.056  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.056  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.056  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:30.056  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-01 10:59:30.056  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:30.056  2637  2704 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:30.066  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:30.066  1015  3154 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:30.066  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.066  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.066  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:30.066  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:30.066  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:30.066  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:30.066  2637  2704 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:30.066  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:30.066  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 10:59:30.076  2637  2704 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:30.076  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService,
09-01 10:59:30.076  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:30.076  2637  2704 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
09-01 10:59:30.076  2637  2704 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:30.076  2637  2704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService,
09-01 10:59:30.076  2637  2704 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:30.076  2637  2704 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 10:59:30.076  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-01 10:59:30.076  2637  2637 D A2dpService: Received stop request...Stopping profile...
,09-01 10:59:30.076  2637  2732 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:30.076  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.076  1015  1015 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:30.076  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-01 10:59:30.086  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-01 10:59:30.086  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:30.086  2637  2637 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 10:59:30.086  1322  1322 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:30.086  1322  1322 D A2dpProfile: Bluetooth service disconnected
,09-01 10:59:30.086  2637  2637 D HidService: Received stop request...Stopping profile...
09-01 10:59:30.086  2637  2637 D HidService: Stopping Bluetooth HidService
09-01 10:59:30.086  2637  2637 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:30.086  2637  2637 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 10:59:30.086  2637  2637 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 10:59:30.086  2845  2845 D BluetoothA2dp: Proxy object disconnected
,09-01 10:59:30.086  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.096  2099  2099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-01 10:59:30.096  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 10:59:30.096  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
09-01 10:59:30.096  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:30.096  1322  1322 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:30.096  1322  1322 D HidProfile: Bluetooth service disconnected
,09-01 10:59:30.096  2637  2637 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 10:59:30.096  2637  2637 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 10:59:30.096  2637  2637 D HealthService: Received stop request...Stopping profile...
09-01 10:59:30.106  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.106  2637  2637 D PanService: Received stop request...Stopping profile...
09-01 10:59:30.106  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.106  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 10:59:30.106  1015  3161 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-01 10:59:30.106  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-01 10:59:30.106  1322  1322 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:30.106  1322  1322 D PanProfile: Bluetooth service disconnected
,09-01 10:59:30.116  2637  2637 D BluetoothMapService: Received stop request...Stopping profile...
09-01 10:59:30.116  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.116  1015  3161 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:30.116  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-01 10:59:30.116  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.116  2637  2637 D SapService: Received stop request...Stopping profile...
,09-01 10:59:30.116  2637  2637 D SapService: Stopping Bluetooth SapService
,09-01 10:59:30.116  2637  2637 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ca3c7e9
,09-01 10:59:30.126  1322  1322 D BluetoothMap: Proxy object disconnected
09-01 10:59:30.126  1322  1322 D MapProfile: Bluetooth service disconnected
,09-01 10:59:30.126  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-01 10:59:30.126  2099  2099 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-01 10:59:30.126  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:30.126  2637  2637 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 10:59:30.126  2099  2099 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 10:59:30.126  2099  2099 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-01 10:59:30.126  2637  2637 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:30.126  2637  2637 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-01 10:59:30.126  2099  2099 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:30.126  2099  2099 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:30.126  2637  2734 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-01 10:59:30.126  2637  2637 I GKI_LINUX: GKI_exit_task 2 done
09-01 10:59:30.126  2637  2637 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-01 10:59:30.136  1015  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-01 10:59:30.136  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.136  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 10:59:30.136  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:30.136  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.136  1015  1133 D Tethering: InitialState.processMessage what=4
09-01 10:59:30.136  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.136  2637  2637 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:30.136  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 10:59:30.136  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.136  2637  2637 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.136  2637  2637 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-01 10:59:30.136  2637  2637 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 10:59:30.136  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.136  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-01 10:59:30.136  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.136  2637  2637 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:30.136  2637  2637 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 10:59:30.136  2637  2637 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 10:59:30.136  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:30.136  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-01 10:59:30.136  2637  2637 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:30.136  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-01 10:59:30.136  1322  1322 D SapProfile: Bluetooth service disconnected
09-01 10:59:30.136  2637  2637 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-01 10:59:30.136  2637  2637 E BluetoothAdapterService(1017366505): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-01 10:59:30.136  2637  2637 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-01 10:59:30.136  2637  2637 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-01 10:59:30.136  2637  2704 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-01 10:59:30.136  2637  2704 D BluetoothAdapterProperties: Setting state to 10
09-01 10:59:30.136  2637  2704 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 10:59:30.136  2637  2704 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:30.136  2637  2704 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 10:59:30.136  2637  2704 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:30.136  2637  2704 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-01 10:59:30.136  2637  2704 I BluetoothAdapterState: Entering OffState
,09-01 10:59:30.136  2637  2650 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:30.146  1015  1133 E Tethering: No numeric data
,09-01 10:59:30.146  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.146  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:30.146  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:30.146  1322  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.146  1322  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.146  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.146  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:30.146  6223  6231 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.146  6223  6231 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.146  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.146  6223  6231 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 10:59:30.146  6223  6231 D BluetoothLeAdvertiser: Exit stop advertising
09-01 10:59:30.146  6223  6231 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 10:59:30.146  6223  6231 D BluetoothLeScanner: Exiting stopAllScan
,09-01 10:59:30.146  1322  1332 D Bluetoothsap: onBluetoothStateChange: up=false
09-01 10:59:30.146  1322  1332 D Bluetoothsap: Unbinding service...
09-01 10:59:30.146  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 10:59:30.146  1015  1133 D Tethering: clearTetheredNotification()
,09-01 10:59:30.146  1322  6415 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 10:59:30.156  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:30.156  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:30.156  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:30.156  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:30.156  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:30.156  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:30.156  2845  2858 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:30.156  1456  1790 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.156  1456  1790 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:30.166  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:30.166  1015  1123 V NetworkStats: performPollLocked() took 9ms
,09-01 10:59:30.166  1322  1332 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 10:59:30.166  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:30.166  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:30.166  1322  6415 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=303 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=295 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  2637  2967 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.166  2637  2967 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.k.c(PG:583)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.176  1015  1314 I ActivityManager: Killing 5029:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-01 10:59:30.166  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:30.166  6383  6383 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.io.File.exists(File.java:363)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:30.166  6383  6383 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-01 10:59:30.176  1175  1896 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.176  1175  1896 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.186  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.186  1438  3371 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.186  1438  3371 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.186  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:30.186  1322  1333 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:30.186  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.186   268   268 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8c697c8
09-01 10:59:30.186   268   268 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-01 10:59:30.186  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.186   268   268 I rmt_storage: wakelock acquired: 1, error no: 42
09-01 10:59:30.186   268   361 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1194945224)
09-01 10:59:30.196  1430  1445 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.196  1430  1445 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:30.206  1913  4629 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.206  1913  4629 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.206  2845  2863 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:30.206  2845  2863 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:30.206  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.206  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.206  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.206  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.206  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-01 10:59:30.206  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-01 10:59:30.216  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:30.216  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:30.216  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.216  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.216  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:30.226  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-01 10:59:30.226  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:30.226  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.226  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.226  3623  3623 I Hs20UtilService: Starting #8
09-01 10:59:30.226  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 10:59:30.226  3623  3665 I Hs20UtilService: Message received 5007
09-01 10:59:30.236  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.236  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.236  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:30.236  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-01 10:59:30.236  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 10:59:30.246  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.246  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 10:59:30.246  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.246  6383  6402 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 10:59:30.246  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:30.246  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:30.246  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:30.246  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.246  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.246  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-01 10:59:30.246   268   361 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-01 10:59:30.246   268   361 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,09-01 10:59:30.246  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.246   268   361 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1194945224) wakelock released: 1, error no: 0
09-01 10:59:30.246   268   361 I rmt_storage: 
,09-01 10:59:30.246  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.246   268   268 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8c697c8
,09-01 10:59:30.246  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:30.246  1175  1735 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:30.246  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:30.256  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:30.256  1175  1175 D BluetoothTile:  getBluetoothState : 10
09-01 10:59:30.256  1175  1735 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:30.256  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.256  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.256  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:30.256  1015  3154 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:30.256  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:30.256  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:30.256  1814  1814 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:30.256  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:30.256  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-01 10:59:30.256  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.256  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.256  1913  2125 D BluetoothAdapter: 295479110: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:30.266  1913  2125 D BluetoothAdapter: 295479110: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:30.266  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:30.266  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.266  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:30.266  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.266  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:30.266  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:30.266  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:30.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:30.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.266  1015  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:30.266  2637  2707 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-01 10:59:30.266  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.266  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.266  2637  2637 I GKI_LINUX: GKI_exit_task 1 done
09-01 10:59:30.266  2637  2637 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-01 10:59:30.266  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.266  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:30.266  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-01 10:59:30.266  2637  2637 I BluetoothServiceJni: cleanupNative: return from cleanup
09-01 10:59:30.276  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.276  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-01 10:59:30.276  2637  2637 I art     : System.exit called, status: 0
09-01 10:59:30.276  2637  2637 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 10:59:30.276  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.276  1015  1559 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-01 10:59:30.276  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:30.276  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-01 10:59:30.276  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-01 10:59:30.276  1456  1456 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-01 10:59:30.276  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:30.276  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.276  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:30.276  1456  1456 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-01 10:59:30.276  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.286  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:30.296  6435  6435 E Zygote  : MountEmulatedStorage()
,09-01 10:59:30.296  6435  6435 I libpersona: KNOX_SDCARD checking this for 10104
09-01 10:59:30.296  6435  6435 E Zygote  : v2
09-01 10:59:30.296  6435  6435 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:30.296  6435  6435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:30.296  1015  1559 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6435 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-01 10:59:30.306  6435  6435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:30.306  6435  6435 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:30.326  6435  6435 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:30.326  6435  6435 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:30.346  6435  6435 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 10:59:30.346  2099  2099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-01 10:59:30.346  1015  3162 I ActivityManager: Process com.android.bluetooth (pid 2637)(adj 0) has died(51,1085)
09-01 10:59:30.346  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.346  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:30.346  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:30.356  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-01 10:59:30.356  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-01 10:59:30.356  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 10:59:30.366  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:30.366  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-01 10:59:30.366  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:30.366  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:30.366  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:30.366  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:30.366  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:30.366  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-01 10:59:30.376  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:30.376  1913  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 10:59:30.376  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:30.376  1175  1175 D HotspotTile: onReceive : 1, 0
,09-01 10:59:30.376  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:30.376  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:30.386  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:30.456  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:30.486  1015  1015 I ApplicationPolicy: updateDataUsageMap
,09-01 10:59:30.486  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:30.496  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:30.496  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:30.496  3141  3141 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-01 10:59:30.516  3141  3141 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-01 10:59:30.556  6435  6461 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-01 10:59:30.556  6435  6461 I Babel   : MmsConfig.loadMmsSettings
,09-01 10:59:30.556  6435  6461 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-01 10:59:30.556  6435  6461 I Babel   : MmsConfig.loadFromDatabase
,09-01 10:59:30.566  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-01 10:59:30.566  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.566  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.576  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:30.576  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-01 10:59:30.576  6435  6461 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-01 10:59:30.576  6435  6461 I Babel   : MmsConfig.loadFromResources
,09-01 10:59:30.576  6435  6461 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-01 10:59:30.576  6435  6461 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-01 10:59:30.576  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:30.606  6435  6435 I Babel_StickerModule: App launched.
,09-01 10:59:30.616  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 10:59:30.616  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:30.626  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:30.626  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:30.626  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 10:59:30.626  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:30.626  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:30.626  1015  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-01 10:59:30.626  1015  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.626  1015  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:30.626  1015  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.626  1015  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.646  1015  1558 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6463 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-01 10:59:30.646  6463  6463 E Zygote  : MountEmulatedStorage()
09-01 10:59:30.646  6463  6463 I libpersona: KNOX_SDCARD checking this for 10068
09-01 10:59:30.646  6463  6463 E Zygote  : v2
09-01 10:59:30.646  6463  6463 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:30.646  6463  6463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:30.646   282   695 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-01 10:59:30.646   282   695 W QCamera2Factory: getCameraInfo: X
,09-01 10:59:30.656   282  1013 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-01 10:59:30.656   282  1013 W QCamera2Factory: getCameraInfo: X
,09-01 10:59:30.656  6463  6463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:30.656  6463  6463 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:30.676  6463  6463 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:30.676  6463  6463 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:30.686  6435  6435 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-01 10:59:30.686  6435  6435 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 10:59:30.686  6435  6435 W AudioCapabilities: Unsupported mime audio/qcelp
,09-01 10:59:30.686  6435  6435 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-01 10:59:30.686  6435  6435 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-01 10:59:30.696  6463  6463 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:30.706  6435  6435 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-01 10:59:30.706  6435  6435 W AudioCapabilities: Unsupported mime audio/x-ima
,09-01 10:59:30.706  6435  6435 W AudioCapabilities: Unsupported mime audio/qcelp
,09-01 10:59:30.706  6435  6435 W AudioCapabilities: Unsupported mime audio/evrc
,09-01 10:59:30.716  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:30.716  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-01 10:59:30.726  6435  6435 W VideoCapabilities: Unsupported mime video/wvc1
,09-01 10:59:30.726  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 10:59:30.726  6435  6435 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-01 10:59:30.736  6435  6435 W VideoCapabilities: Unsupported mime video/wvc1
,09-01 10:59:30.736  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-01 10:59:30.736  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-01 10:59:30.736  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-01 10:59:30.736  6435  6435 W VideoCapabilities: Unsupported mime video/mp43
,09-01 10:59:30.746  6435  6435 W VideoCapabilities: Unsupported mime video/sorenson
,09-01 10:59:30.746  6435  6435 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-01 10:59:30.746  6463  6463 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:30.746  1015  1314 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-01 10:59:30.756  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.756  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.756  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:30.756  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:30.766  6478  6478 E Zygote  : MountEmulatedStorage(),
09-01 10:59:30.766  6478  6478 I libpersona: KNOX_SDCARD checking this for 10069
,09-01 10:59:30.766  6478  6478 E Zygote  : v2
09-01 10:59:30.766  6478  6478 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:30.766  6478  6478 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-01 10:59:30.766  6478  6478 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:30.766  1015  1314 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6478 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:30.766  6478  6478 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:30.766  1015  1314 I ActivityManager: Killing 5475:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-01 10:59:30.776  6435  6435 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-01 10:59:30.786  6478  6478 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:30.786  6478  6478 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:30.806  6478  6478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:30.816  1015  1138 I ActivityManager: Killing 5565:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-01 10:59:30.816  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:30.816  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:30.826  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.826  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.826  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:30.826  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:30.826  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:30.826  3623  3623 I Hs20UtilService: Starting #9
09-01 10:59:30.826  3623  3665 I Hs20UtilService: Message received 5007
,09-01 10:59:30.826  1015  3166 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-01 10:59:30.826  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-01 10:59:30.836  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:30.836  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:30.836  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:30.836  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-01 10:59:30.836  1015  1043 D Tethering: interfaceRemoved wlan0
,09-01 10:59:30.836  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 10:59:30.836  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:30.836  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:30.836  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:30.836  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:30.836  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:30.846  1015  3162 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:30.846  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:30.846  1015  1558 I ActivityManager: Killing 5839:com.sec.pcw.device/1000 (adj 15): empty #31
,09-01 10:59:31.026  1015  3166 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:31.026  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:31.026  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.026  1015  3166 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:31.026  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:31.036  1015  1314 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-01 10:59:31.036  3623  3623 I Hs20UtilService: Starting #10
,09-01 10:59:31.036  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:31.036  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.036  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.036  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.036  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.036  1015  1043 D Tethering: interfaceRemoved p2p0
,09-01 10:59:31.036  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 10:59:31.046  6494  6494 E Zygote  : MountEmulatedStorage()
09-01 10:59:31.046  1015  1314 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-01 10:59:31.046  6494  6494 E Zygote  : v2
09-01 10:59:31.046  6494  6494 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:31.046  6494  6494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:31.046  6494  6494 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.056  6494  6494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:31.056  6494  6494 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.066  6494  6494 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-01 10:59:31.066  6494  6494 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.096  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:31.096  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:31.096  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:31.106  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:31.106  1015  1028 I ActivityManager: Killing 5854:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-01 10:59:31.116  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.116  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.116  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.116  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.116  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.116  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.126  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.126  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.126  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.126  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.126  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.136  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.136  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.136  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.136  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.136  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.146  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.146  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.146  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.146  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.146  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.146  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.146  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.146  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.156  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.156  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.156  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.156  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.156  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.156  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-01 10:59:31.156  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:31.156  1015  1138 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 10:59:31.156  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:31.166  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.166  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.166  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:31.166  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:31.166  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:31.176  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:31.176  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 10:59:31.176  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-01 10:59:31.186  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.186  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.186  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.186  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.196  6511  6511 E Zygote  : MountEmulatedStorage(),
09-01 10:59:31.196  6511  6511 E Zygote  : v2
09-01 10:59:31.196  6511  6511 I libpersona: KNOX_SDCARD checking this for 1002
09-01 10:59:31.196  6511  6511 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.196  6511  6511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-01 10:59:31.196  6511  6511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:31.206  6511  6511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:31.206  1015  1475 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6511 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-01 10:59:31.226  6511  6511 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:31.226  6511  6511 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.236   287   287 E SMD     : DCD OFF,
09-01 10:59:31.236  6511  6511 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 10:59:31.236  6511  6511 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:31.276  6511  6511 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-01 10:59:31.306  6511  6511 D BtSettings.ProfileConfig: Adding GattService
,09-01 10:59:31.306  6511  6511 D BtSettings.ProfileConfig: Adding HeadsetService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding A2dpService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding HidService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding HealthService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding PanService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding BluetoothMapService,
09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding SapService
09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding SapClientService
,09-01 10:59:31.316  6511  6511 D BtSettings.ProfileConfig: Adding HidDevService
,09-01 10:59:31.316  6511  6511 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-01 10:59:31.316  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-01 10:59:31.316  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.316  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.316  1015  1027 D SettingsProvider: selectionArgs: false
09-01 10:59:31.316  1015  1027 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1027 D SettingsProvider: ret = -1
,09-01 10:59:31.326  1015  3162 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:31.326  1015  3162 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  3162 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.326  1015  3162 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  3162 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  3162 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  3162 D SettingsProvider: ret = -1
,09-01 10:59:31.326  1015  3154 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:31.326  1015  3154 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  3154 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:31.326  1015  3154 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  3154 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:31.326  1015  3154 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  3154 D SettingsProvider: ret = -1
,09-01 10:59:31.326  1015  1138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-01 10:59:31.326  1015  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.326  1015  1138 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  1138 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1138 D SettingsProvider: ret = -1
09-01 10:59:31.326  1015  1557 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-01 10:59:31.326  1015  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.326  1015  1557 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  1557 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1557 D SettingsProvider: ret = -1,
,09-01 10:59:31.326  1015  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-01 10:59:31.326  1015  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
,09-01 10:59:31.326  1015  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:31.326  1015  1500 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  1500 D SettingsProvider: selectionArgs: 1002,
,09-01 10:59:31.326  1015  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1500 D SettingsProvider: ret = -1
09-01 10:59:31.326  1015  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-01 10:59:31.326  1015  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.326  1015  1558 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  1558 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1558 D SettingsProvider: ret = -1
09-01 10:59:31.326  1015  1216 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,09-01 10:59:31.326  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.326  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.326  1015  1216 D SettingsProvider: selectionArgs: false
09-01 10:59:31.326  1015  1216 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.326  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.326  1015  1216 D SettingsProvider: ret = -1
09-01 10:59:31.336  1015  1559 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:31.336  1015  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.336  1015  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-01 10:59:31.336  1015  1559 D SettingsProvider: selectionArgs: false
09-01 10:59:31.336  1015  1559 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.336  1015  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.336  1015  1559 D SettingsProvider: ret = -1
09-01 10:59:31.336  1015  3161 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:31.336  1015  3161 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.336  1015  3161 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.336  1015  3161 D SettingsProvider: selectionArgs: false
09-01 10:59:31.336  1015  3161 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.336  1015  3161 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.336  1015  3161 D SettingsProvider: ret = -1
09-01 10:59:31.336  1015  3166 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-01 10:59:31.336  1015  3166 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.336  1015  3166 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.336  1015  3166 D SettingsProvider: selectionArgs: false
,09-01 10:59:31.336  1015  3166 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.336  1015  3166 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.336  1015  3166 D SettingsProvider: ret = -1
09-01 10:59:31.336  1015  1314 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-01 10:59:31.336  1015  1314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:31.336  1015  1314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:31.336  1015  1314 D SettingsProvider: selectionArgs: false
09-01 10:59:31.336  1015  1314 D SettingsProvider: selectionArgs: 1002
09-01 10:59:31.336  1015  1314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:31.336  1015  1314 D SettingsProvider: ret = -1
,09-01 10:59:31.346  1015  1476 I ActivityManager: Killing 5109:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-01 10:59:31.356  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:31.356  1015  3162 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:31.356  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-01 10:59:31.356  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.356  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:31.356  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:31.366  1913  6527 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:31.376  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:31.516  1015  1558 I art     : Explicit concurrent mark sweep GC freed 54472(3MB) AllocSpace objects, 7(160KB) LOS objects, 33% free, 28MB/42MB, paused 2.484ms total 156.360ms
,09-01 10:59:31.516  1015  3140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:31.526  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.526  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:31.526  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:31.536  1015  1559 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:31.536  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:31.536  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.536  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.536  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:31.536  1015  3166 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:31.536  3623  3623 I Hs20UtilService: Starting #11
,09-01 10:59:31.546  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:31.546  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:31.546  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:31.546  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:31.546  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:31.546  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:31.546  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:31.546  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-01 10:59:31.546  1913  6527 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-01 10:59:31.556  1015  3140 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-01 10:59:31.556  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.556  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.556  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.566  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.576  6528  6528 E Zygote  : MountEmulatedStorage(),
09-01 10:59:31.576  6528  6528 E Zygote  : v2
09-01 10:59:31.576  6528  6528 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:31.576  6528  6528 I libpersona: KNOX_SDCARD not a persona,
09-01 10:59:31.576  6528  6528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:31.576  1015  3140 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6528 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,09-01 10:59:31.576  6528  6528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:31.576  6528  6528 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.586  6528  6528 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:31.596  6528  6528 D ActivityThread: Added TimaKeyStore provider,
,09-01 10:59:31.616  6528  6528 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-01 10:59:31.616  6528  6528 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-01 10:59:31.616  6528  6528 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-01 10:59:31.626  6528  6528 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-01 10:59:31.626  6528  6528 I PCWCLIENTTRACE_PushUtil: sales region : global
09-01 10:59:31.626  6528  6528 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-01 10:59:31.626  6528  6528 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:31.626  1015  3140 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-01 10:59:31.626  1015  3140 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-01 10:59:31.626  1015  3140 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-01 10:59:31.626  6528  6544 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-01 10:59:31.626  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.626  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.626  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.626  1015  3140 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.646  6546  6546 E Zygote  : MountEmulatedStorage(),
,09-01 10:59:31.646  6546  6546 E Zygote  : v2,
09-01 10:59:31.646  6546  6546 I libpersona: KNOX_SDCARD checking this for 10111
09-01 10:59:31.646  6546  6546 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.646  6546  6546 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:31.656  1015  3140 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6546 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:31.656  6546  6546 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:31.656  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-01 10:59:31.656  6546  6546 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.656  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 10:59:31.656  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.656  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.656  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.676  6546  6546 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:31.676  6546  6546 D ActivityThread: Added TimaKeyStore provider,
09-01 10:59:31.676   302   302 I art     : Explicit concurrent mark sweep GC freed 8729(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 990us total 31.937ms
,09-01 10:59:31.706   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 719us total 25.243ms
,09-01 10:59:31.726   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 713us total 19.797ms
,09-01 10:59:31.736  6561  6561 E Zygote  : MountEmulatedStorage()
,09-01 10:59:31.736  6561  6561 E Zygote  : v2
09-01 10:59:31.736  6561  6561 I libpersona: KNOX_SDCARD checking this for 10009,
09-01 10:59:31.736  6561  6561 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.746  6561  6561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-01 10:59:31.746  1015  1041 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6561 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-01 10:59:31.756  6561  6561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:31.756  6561  6561 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-01 10:59:31.756  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
09-01 10:59:31.756  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-01 10:59:31.756  1720  1720 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:31.766  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.766  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.766  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.766  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.786  6570  6570 E Zygote  : MountEmulatedStorage()
09-01 10:59:31.786  6570  6570 I libpersona: KNOX_SDCARD checking this for 10145
09-01 10:59:31.786  6570  6570 E Zygote  : v2
09-01 10:59:31.786  6570  6570 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.786  6570  6570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:31.796  1015  1041 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6570 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-01 10:59:31.796  6570  6570 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:31.796  6570  6570 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.806  1720  1720 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-01 10:59:31.806  6561  6561 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-01 10:59:31.806  6561  6561 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.816  1720  1720 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-01 10:59:31.816  1720  1720 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-01 10:59:31.816  1720  1720 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-01 10:59:31.826  1720  1720 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-01 10:59:31.826  1298  1313 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 20
,09-01 10:59:31.836  1720  1720 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-01 10:59:31.836  1015  1500 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-01 10:59:31.836  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.836  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.836  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.836  1015  1500 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.846  6570  6570 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:31.846  6570  6570 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.856  6591  6591 E Zygote  : MountEmulatedStorage()
09-01 10:59:31.856  1015  1500 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6591 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-01 10:59:31.856  6591  6591 E Zygote  : v2
09-01 10:59:31.856  6591  6591 I libpersona: KNOX_SDCARD checking this for 10081
09-01 10:59:31.856  6591  6591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:31.856  6591  6591 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:31.866  6591  6591 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:31.866  6591  6591 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.866  1720  1720 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-01 10:59:31.876  6591  6591 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:31.886  6591  6591 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.886  6570  6570 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-01 10:59:31.886  6570  6570 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:31.886  6570  6570 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:31.886  6570  6570 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:31.886  6570  6570 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:31.906  6546  6546 I MusicStore: Database version: 108
,09-01 10:59:31.916  1015  1028 I ActivityManager: Killing 5500:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-01 10:59:31.916  3668  3668 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 01 10:59:31 GMT+02:00 2016
,09-01 10:59:31.916  1015  1314 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-01 10:59:31.916  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:31.926  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.926  1015  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:31.926  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-01 10:59:31.926  3668  3668 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-01 10:59:31.936  1015  3140 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-01 10:59:31.936  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-01 10:59:31.936  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:31.936  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:31.936  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:31.936  3668  3668 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-01 10:59:31.936  1015  3154 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-01 10:59:31.946  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.946  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:31.946  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.946  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:31.946  3668  3668 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,09-01 10:59:31.956  6613  6613 E Zygote  : MountEmulatedStorage()
09-01 10:59:31.956  6613  6613 I libpersona: KNOX_SDCARD checking this for 10034
09-01 10:59:31.956  6613  6613 E Zygote  : v2
09-01 10:59:31.956  6613  6613 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:31.956  6613  6613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:31.956  1015  3154 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6613 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
09-01 10:59:31.956  1015  1475 D RCPManagerService: exchangeData() failure , invalid userId
09-01 10:59:31.956  3668  3668 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-01 10:59:31.966  6613  6613 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:31.966  6613  6613 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:31.976  3668  6611 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-01 10:59:31.976  3668  6611 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-01 10:59:31.986  3668  6611 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-01 10:59:31.986  3668  6611 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-01 10:59:31.986  3668  3668 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-01 10:59:31.986  6613  6613 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:31.986  6613  6613 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:31.986  1015  3162 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.016  1015  1559 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-01 10:59:32.016  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.016  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.016  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-01 10:59:32.016  1015  1559 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.026  6546  6546 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-01 10:59:32.026  6546  6546 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-01 10:59:32.026  6633  6633 E Zygote  : MountEmulatedStorage()
09-01 10:59:32.026  6633  6633 E Zygote  : v2
09-01 10:59:32.026  6633  6633 I libpersona: KNOX_SDCARD checking this for 10113
09-01 10:59:32.026  6633  6633 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:32.026  6633  6633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:32.036  6633  6633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:32.036  6633  6633 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:32.036  1015  1559 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6633 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:32.046  6613  6613 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-01 10:59:32.056  1015  3166 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.056  6633  6633 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:32.056  6633  6633 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:32.056  1015  3154 I ActivityManager: Killing 5872:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-01 10:59:32.066  1015  3161 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.086  3172  6650 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-01 10:59:32.086  3172  6650 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-01 10:59:32.086  3172  6650 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-01 10:59:32.086  6546  6546 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-01 10:59:32.086  3172  6650 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-01 10:59:32.096  3172  6650 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-01 10:59:32.096  5906  5906 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-01 10:59:32.106  6098  6098 I SA      : [DM] init START
,09-01 10:59:32.106  6098  6098 I SA      : [DM] This device is not a Vodafone
,09-01 10:59:32.116  1015  1314 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-01 10:59:32.116  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.116  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.116  1015  1314 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-01 10:59:32.116  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-01 10:59:32.126  6098  6098 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-01 10:59:32.136  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.146  6098  6098 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-01 10:59:32.146  6098  6098 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
09-01 10:59:32.156  6098  6098 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-01 10:59:32.156  5906  6653 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-01 10:59:32.166  6000  6011 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-01 10:59:32.176  6098  6098 I SA      : [SCU] isHaveSA() - false
09-01 10:59:32.176  6098  6098 I SA      : support phone number id : false
09-01 10:59:32.176  6098  6098 I SA      : [DM] Supports Ref Jpn : true
,09-01 10:59:32.176  6098  6098 I SA      : [DM] init END
,09-01 10:59:32.176  6098  6098 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-01 10:59:32.176  1015  3162 D RCPManagerService: exchangeData() failure , invalid userId,
,09-01 10:59:32.176  6546  6546 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-01 10:59:32.176  6546  6546 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22a45bad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-01 10:59:32.186  6546  6546 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-01 10:59:32.186  6546  6546 D AndroidMusic: GMSCore installation verified
,09-01 10:59:32.186  6098  6098 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-01 10:59:32.186  6098  6098 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-01 10:59:32.186  6098  6098 I SA      : [SLFUCHKMGR] constructor called
,09-01 10:59:32.196  1015  3154 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-01 10:59:32.196  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-01 10:59:32.196  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:32.196  1015  3154 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.196  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.206  6000  6011 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,09-01 10:59:32.206  1477  1477 D Launcher.Model: reloadBadges entered.
09-01 10:59:32.206  6000  6011 D BadgeProvider: sendNotify, [notify] : null
,09-01 10:59:32.206  6546  6546 I ConfigStore: Config Database version: 1
09-01 10:59:32.206  6000  6011 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-01 10:59:32.206  6000  6011 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-01 10:59:32.206  6000  6011 D BadgeProvider: update, [UpdateCount] : 1
,09-01 10:59:32.216  6098  6098 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-01 10:59:32.216  6098  6098 I SA      : [OR] == isSIMCardReady false ==
,09-01 10:59:32.216  6098  6098 I SA      : [SCU] == networkStateCheck == false
09-01 10:59:32.216  6098  6098 I SA      : [OR] onReceive END
,09-01 10:59:32.226  1226  1226 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:32.236  1015  3154 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.246  1015  1476 D RCPManagerService: exchangeData() failure , invalid userId
,09-01 10:59:32.256  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:32.256  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:32.256  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:32.256  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:32.256  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-01 10:59:32.266  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.266  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.266  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.266  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.286  6663  6663 E Zygote  : MountEmulatedStorage()
,09-01 10:59:32.286  6663  6663 E Zygote  : v2
09-01 10:59:32.286  6663  6663 I libpersona: KNOX_SDCARD checking this for 10159
09-01 10:59:32.286  6663  6663 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:32.286  6663  6663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:32.286  6663  6663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:32.296  6663  6663 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-01 10:59:32.296  1015  1216 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6663 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-01 10:59:32.296  1015  1216 I ActivityManager: Killing 5889:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-01 10:59:32.316  6663  6663 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:32.316  6663  6663 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:32.346   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-01 10:59:32.346   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.346  6546  6546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-01 10:59:32.346   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-01 10:59:32.346   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.346  6546  6546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-01 10:59:32.356   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-01 10:59:32.356   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.356  6546  6546 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-01 10:59:32.356  1015  1028 I ActivityManager: Killing 5533:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-01 10:59:32.366  1015  3140 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-01 10:59:32.366  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.366  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:32.366  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.366  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.366  1015  3161 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:32.366  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.366  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.366  1015  3161 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.366  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:32.376  3781  3781 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-01 10:59:32.386  3781  4583 I iu.UploadsManager: num queued entries: 0
,09-01 10:59:32.386  3781  4583 I iu.UploadsManager: num updated entries: 0
,09-01 10:59:32.386  3781  4583 I iu.SyncManager: NEXT; no task
,09-01 10:59:32.396   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 10:59:32.396   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.396  6633  6681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-01 10:59:32.406   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 10:59:32.406   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.406  6633  6681 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 10:59:32.406  1015  1314 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-01 10:59:32.406  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-01 10:59:32.406  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:32.406  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.406  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.426  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:32.436  1015  3154 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:32.436   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-01 10:59:32.436   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.436  6633  6684 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-01 10:59:32.436   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-01 10:59:32.436   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:32.436  6633  6684 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-01 10:59:32.436  1015  1557 I AudioService: getStreamVolume 3 index 0
,09-01 10:59:32.446  6546  6546 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-01 10:59:32.446  6546  6546 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-01 10:59:32.466  1015  3166 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:32.476  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-01 10:59:32.476  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.476  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.476  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.476  1015  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:32.476  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.476  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.476  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.476  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.486  1015  3166 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:32.496  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.496  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:32.496  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.496  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.496  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.496  1015  1558 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-01 10:59:32.496  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.496  1015  1216 I ActivityManager: Killing 5820:com.android.mms/u0a46 (adj 15): empty #31
,09-01 10:59:32.496  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.496  1015  1559 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:32.516  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-01 10:59:32.516  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.516  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.516  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.526  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.536  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6689 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:32.536  6689  6689 E Zygote  : MountEmulatedStorage()
,09-01 10:59:32.536  6689  6689 E Zygote  : v2
,09-01 10:59:32.536  6689  6689 I libpersona: KNOX_SDCARD checking this for 10002
09-01 10:59:32.536  6689  6689 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:32.536  6689  6689 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-01 10:59:32.546  6689  6689 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:32.546  6689  6689 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:32.546  1015  1475 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:32.546  1015  1475 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 10:59:32.546  1015  1475 D SecContentProvider2: mCursor = null
,09-01 10:59:32.556  1015  1475 D WifiService: setWifiEnabled: true pid=6223, uid=10155
,09-01 10:59:32.556  1015  1475 W ActivityManager: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:32.556  1015  1475 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:32.556  1015  1475 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:32.556  1015  1475 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-01 10:59:32.556  1015  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:32.556  1015  1475 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:32.556  1015  1475 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:32.556  1015  1475 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 10:59:32.556  1015  1475 D SettingsProvider: name = wifi_on
,09-01 10:59:32.556  1015  3166 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
09-01 10:59:32.556  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-01 10:59:32.556  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.556  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.556  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-01 10:59:32.556  1015  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 10:59:32.566  6546  6546 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-01 10:59:32.566  1015  3161 D CountryDetector: No listener is left
,09-01 10:59:32.576  1015  3140 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-01 10:59:32.576  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-01 10:59:32.576  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:32.576  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.576  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:32.576  6689  6689 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:32.576  6689  6689 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:32.606  1015  1559 I ActivityManager: Killing 6019:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-01 10:59:32.646  1015  3162 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:32.646  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:32.646  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:32.646  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-01 10:59:32.656  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-01 10:59:32.656  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.656  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.656  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.656  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.676  1015  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-01 10:59:32.676  6633  6633 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-01 10:59:32.676  6722  6722 E Zygote  : MountEmulatedStorage(),
09-01 10:59:32.676  6722  6722 E Zygote  : v2
09-01 10:59:32.676  6722  6722 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:32.676  6722  6722 I libpersona: KNOX_SDCARD not a persona,
09-01 10:59:32.676  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:32.686  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:32.686  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:32.686  6633  6633 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2317-2319),
09-01 10:59:32.686  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 10:59:32.696  6633  6633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d04783a}
,09-01 10:59:32.696  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 10:59:32.696  6633  6633 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 10:59:32.706  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:32.706  6722  6722 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:32.716  6633  6633 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 10:59:32.716  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-01 10:59:32.726  6633  6633 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 10:59:32.746  6633  6633 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-01 10:59:32.746  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-01 10:59:32.746  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-01 10:59:32.746  6633  6633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-01 10:59:32.746  6633  6633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-01 10:59:32.746  6633  6633 I Adreno-EGL: Build Date: 04/06/15 Mon
09-01 10:59:32.746  6633  6633 I Adreno-EGL: Local Branch: 
09-01 10:59:32.746  6633  6633 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-01 10:59:32.746  6633  6633 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-01 10:59:32.746  6633  6633 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-01 10:59:32.756  6722  6722 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-01 10:59:32.816  6633  6755 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 10:59:32.816  6633  6633 I NSApplication: Starting up...
,09-01 10:59:32.826  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-01 10:59:32.826  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.826  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.826  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:32.826  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:32.846  6760  6760 E Zygote  : MountEmulatedStorage(),
09-01 10:59:32.846  6760  6760 E Zygote  : v2,
09-01 10:59:32.846  6760  6760 I libpersona: KNOX_SDCARD checking this for 10120
09-01 10:59:32.846  6760  6760 I libpersona: KNOX_SDCARD not a persona,
,09-01 10:59:32.846  6760  6760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:32.846  6760  6760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:32.846  1015  1475 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6760 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-01 10:59:32.846  1015  1475 I ActivityManager: Killing 6067:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
09-01 10:59:32.856  6760  6760 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-01 10:59:32.846  1015  1475 I ActivityManager: Killing 6035:com.wsomacp/u0a25 (adj 15): empty #32
,09-01 10:59:32.876  6760  6760 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:32.876  6760  6760 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:32.886  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-01 10:59:32.886  6760  6760 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 10:59:32.896  6722  6722 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-01 10:59:32.896  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:32.896  6722  6722 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-01 10:59:32.896  6722  6722 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-01 10:59:32.896  6722  6722 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-01 10:59:32.896  1015  1558 I ActivityManager: Killing 5949:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-01 10:59:32.936  1015  1043 D Tethering: interfaceAdded wlan0
,09-01 10:59:32.946  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:32.946  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:32.946  1015  1133 E Tethering: No numeric data
,09-01 10:59:32.956  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:32.956  1015  1043 D Tethering: interfaceAdded p2p0
,09-01 10:59:32.956  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
09-01 10:59:32.956   276   988 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-01 10:59:32.956   276   988 D SoftapController: Softap fwReload - Ok
,09-01 10:59:32.956  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-01 10:59:32.956  1015  1133 D Tethering: clearTetheredNotification()
09-01 10:59:32.956  1015  1133 D Tethering: InitialState.processMessage what=4
,09-01 10:59:32.966  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:32.966  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:32.966   276   988 D CommandListener: Setting iface cfg
09-01 10:59:32.966   276   988 D CommandListener: Trying to bring down wlan0
,09-01 10:59:32.966  1015  1133 E Tethering: No numeric data
09-01 10:59:32.966   276   988 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:32.966  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:32.966  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:32.966  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-01 10:59:32.966  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:32.966  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:32.966  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:32.976  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 10:59:32.976  1015  1123 V NetworkStats: performPollLocked() took 7ms
09-01 10:59:32.976  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:32.976  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:32.976  1015  1133 D Tethering: clearTetheredNotification()
,09-01 10:59:32.986  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:32.986  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:32.986  1015  1130 E WifiHW  : supplicant_name : p2p_supplicant,
09-01 10:59:32.986  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:32.986  1015  1123 V NetworkStats: performPollLocked(flags=0x1),
09-01 10:59:32.986  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:32.986  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:32.986  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:32.986  1015  1123 V NetworkStats: performPollLocked() took 5ms
,09-01 10:59:32.996  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:32.996  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:32.996  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:32.996  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:33.036  6776  6776 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-01 10:59:33.036  6776  6776 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 10:59:33.036  6776  6776 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 10:59:33.046  6776  6776 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-01 10:59:33.046   342   342 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6776
09-01 10:59:33.046   342   342 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-01 10:59:33.046  6776  6776 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 10:59:33.046  6776  6776 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:33.046  6776  6776 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 10:59:33.046  6776  6776 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-01 10:59:33.046   342   342 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6776
09-01 10:59:33.046   342   342 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-01 10:59:33.086  1015  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-01 10:59:33.096  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:33.096  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:33.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:33.096  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:33.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:33.096  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:33.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:33.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:33.096  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:33.096  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-01 10:59:33.096  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:33.106  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:33.106  1175  1175 D HotspotTile: onReceive : 2, 0
09-01 10:59:33.106  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:33.216   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-01 10:59:33.216  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-01 10:59:33.256  1015  1314 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-01 10:59:33.256  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:33.256  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:33.256  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:33.256  1015  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:33.266  6784  6784 E Zygote  : MountEmulatedStorage()
09-01 10:59:33.266  6784  6784 E Zygote  : v2
09-01 10:59:33.266  6784  6784 I libpersona: KNOX_SDCARD checking this for 10125
09-01 10:59:33.266  6784  6784 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:33.266  6784  6784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:33.276  1015  1314 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6784 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
09-01 10:59:33.276  1015  1314 I ActivityManager: Killing 5804:com.samsung.android.sm/1000 (adj 15): empty #31
,09-01 10:59:33.276  6784  6784 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-01 10:59:33.276  6784  6784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:33.296  6776  6776 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 10:59:33.296  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 10:59:33.306  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-01 10:59:33.306   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6776
09-01 10:59:33.306   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 10:59:33.306  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 10:59:33.306  6776  6776 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:33.306  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-01 10:59:33.306  6776  6776 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:33.306  6784  6784 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:33.306  6776  6776 E wpa_supplicant: SIM READ ERROR
09-01 10:59:33.306  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:33.306  6776  6776 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:33.306  6776  6776 E wpa_supplicant: SIM READ ERROR
09-01 10:59:33.306  6784  6784 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:33.306  6776  6776 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:33.316  6776  6776 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:33.316  6776  6776 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 10:59:33.316  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:33.316  6776  6776 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-01 10:59:33.316  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:33.316  6776  6776 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 10:59:33.316  6776  6776 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:33.316  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:33.316  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:33.316  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:33.326  6784  6784 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 10:59:33.326  6784  6784 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:33.326  6784  6784 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:33.336  6784  6784 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:33.336  6784  6784 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-01 10:59:33.346  6784  6784 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-01 10:59:33.346  1015  3161 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-01 10:59:33.346  1015  3161 I ActivityManager: Killing 5922:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-01 10:59:33.356  1015  1558 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:33.356  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:33.356  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:33.356  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:33.356  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:33.356  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:33.356  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:33.356  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:33.356  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:33.366  3623  3623 I Hs20UtilService: Starting #12
,09-01 10:59:33.366  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:33.376  6776  6776 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-01 10:59:33.576  6776  6776 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-01 10:59:33.576  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-01 10:59:33.586  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 10:59:33.596   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6776
09-01 10:59:33.596   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-01 10:59:33.596  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 10:59:33.596  6776  6776 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:33.596  6776  6776 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-01 10:59:33.596  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-01 10:59:33.606  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-01 10:59:33.606   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6776
09-01 10:59:33.606   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 10:59:33.606  6776  6776 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-01 10:59:33.606  6776  6776 I wpa_supplicant: ssSupport state is = 1,
09-01 10:59:33.606  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:33.606  6776  6776 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:33.606  6776  6776 E wpa_supplicant: SIM READ ERROR
09-01 10:59:33.606  6776  6776 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:33.606  6776  6776 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-01 10:59:33.606  6776  6776 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:33.606  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:33.606  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:33.606  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:33.616  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:33.616  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:33.616  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:33.666  6776  6776 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-01 10:59:33.666  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 10:59:33.726  6776  6776 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-01 10:59:33.726  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-01 10:59:33.726  6776  6776 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:33.736  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-01 10:59:33.736  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:33.736  6776  6776 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-01 10:59:33.736  6776  6776 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-01 10:59:33.746  6776  6776 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:33.746  6776  6776 E wpa_supplicant: SIM READ ERROR
09-01 10:59:33.746  6776  6776 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:33.766  6776  6776 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-01 10:59:33.776  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210],
09-01 10:59:33.776  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:33.776  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:33.776  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:33.776  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:33.776  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:33.776  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:33.776  6776  6776 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:33.786  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:33.786  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:33.786  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-01 10:59:33.786  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:33.786  1175  1175 D HotspotTile: onReceive : 3, 0
,09-01 10:59:33.786  1015  1130 D WifiConfigStore: Loading config and enabling all networks 
,09-01 10:59:33.786  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:33.786  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:33.786  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:33.786  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:33.786  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:33.796  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:33.796  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:33.796  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:33.796  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:33.796  1015  1314 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:33.796  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:33.796  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:33.796  1015  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:33.796  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:33.796  1015  1130 E WifiConfigStore: Not a HS20
,09-01 10:59:33.796  1015  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 10:59:33.806  3623  3623 I Hs20UtilService: Starting #13
,09-01 10:59:33.806  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:33.806  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-01 10:59:33.806  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-01 10:59:33.806  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:33.806  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:33.806  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:33.806  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-01 10:59:33.806  6776  6776 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-01 10:59:33.806  6776  6776 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-01 10:59:33.806  6776  6776 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 10:59:33.806  6776  6776 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:33.806  6776  6776 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 10:59:33.806  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-01 10:59:33.806  6776  6776 I wpa_supplicant: First Scan Start
09-01 10:59:33.806  6776  6776 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 10:59:33.816  1015  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-01 10:59:33.816  1015  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 10:59:33.816  1015  1130 I WifiNative-HAL: startHal
09-01 10:59:33.816  1015  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9c76e88c
09-01 10:59:33.816  1015  1130 I WifiNative-HAL: Could not start hal
,09-01 10:59:33.816  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:33.816  1015  1130 E WifiNative-wlan0: do suspend true
,09-01 10:59:33.816  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-01 10:59:33.816  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 10:59:33.816  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 10:59:33.826  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-01 10:59:33.826  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:33.826   276   988 D CommandListener: Setting iface cfg
09-01 10:59:33.826   276   988 D CommandListener: Trying to bring up p2p0
,09-01 10:59:33.826  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 10:59:33.826  1015  1125 D WifiP2pService: P2pEnablingState
09-01 10:59:33.826  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-01 10:59:33.826  1015  1125 D WifiP2pService: P2p socket connection successful
09-01 10:59:33.826  1015  1149 D WifiScanningService: DefaultState got{ when=-4ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:33.826  1015  1149 I WifiNative-HAL: startHal
09-01 10:59:33.826  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d9209bc
09-01 10:59:33.826  1015  1149 I WifiNative-HAL: Could not start hal
09-01 10:59:33.826  1015  1149 E WifiScanningService: could not start HAL
09-01 10:59:33.826  1015  1125 D WifiP2pService: P2pEnabledState
,09-01 10:59:33.826  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:33.826  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:33.826  1015  1130 E WifiNative-wlan0: invaild command id : 215
,09-01 10:59:33.826  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 10:59:33.826  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:33.826  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:33.826  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:33.826  1015  1130 E WifiNative-wlan0: invaild command id : 215
,09-01 10:59:33.826  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 10:59:33.826  6776  6776 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:33.836  6776  6776 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-01 10:59:33.836  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 10:59:33.836  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:33.836  1015  1046 D WifiDisplayController: disconnect
09-01 10:59:33.836  1015  1046 D WifiDisplayController: updateConnection
09-01 10:59:33.836  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:33.836  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:33.836  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-01 10:59:33.836  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:33.836  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-01 10:59:33.836  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 10:59:33.836  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-01 10:59:33.836  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-01 10:59:33.836  1015  3140 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:33.836  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-01 10:59:33.836  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 10:59:33.836  6776  6776 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-01 10:59:33.836  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
09-01 10:59:33.836  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 10:59:33.836  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:33.836  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  secondary type: null
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  wps: 0
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  grpcapab: 0
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  devcapab: 0
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  status: 3
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  wfdInfo: null
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-01 10:59:33.836  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-01 10:59:33.846  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:33.846  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:33.846  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:33.846  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:33.846  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:33.846  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:33.846  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:33.846  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:33.846  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:33.856  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:33.856  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 10:59:33.856  6463  6463 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:33.856  6478  6478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:33.866  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 10:59:33.866  1015  1125 D WifiP2pService: InactiveState
,09-01 10:59:33.866  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
09-01 10:59:33.866  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:33.866  6776  6776 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-01 10:59:33.866  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
09-01 10:59:33.866  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:33.946  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 10:59:33.946  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:33.946  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:34.236   287   287 E SMD     : DCD OFF,
,09-01 10:59:35.006  6776  6776 I wpa_supplicant: nl80211: Received scan results (23 BSSes)
09-01 10:59:35.006  6776  6776 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-01 10:59:35.006  6776  6776 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-01 10:59:35.006  6776  6776 I wpa_supplicant: Trying to associate with  'G700'
,09-01 10:59:35.006  6776  6776 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
09-01 10:59:35.006  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
09-01 10:59:35.006  1015  6802 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-01 10:59:35.026  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:35.026  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.116  6776  6776 E wpa_supplicant: Cmd 35605 not handled
,09-01 10:59:35.116  6776  6776 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-01 10:59:35.116  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,09-01 10:59:35.116  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:35.116  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:35.116  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,09-01 10:59:35.116  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:35.116  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:35.116  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:35.116  6776  6776 I wpa_supplicant: Associated with F4.99.3E
,09-01 10:59:35.126  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:35.126  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-01 10:59:35.126  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-01 10:59:35.126  6776  6776 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
09-01 10:59:35.126  1015  1133 E Tethering: No numeric data,
,09-01 10:59:35.126  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 10:59:35.126  1015  1133 D Tethering: clearTetheredNotification()
09-01 10:59:35.126  6776  6776 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 10:59:35.126  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
,09-01 10:59:35.126  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:35.126  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:35.136  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-01 10:59:35.136  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:35.136  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:35.136  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:35.136  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:35.136  1015  1123 V NetworkStats: performPollLocked() took 6ms
09-01 10:59:35.136  6776  6776 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:35.136  6776  6776 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-01 10:59:35.136  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:35.136  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:35.136  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:35.136  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.146  6776  6776 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-01 10:59:35.146  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-01 10:59:35.146  6776  6776 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 10:59:35.146  6776  6776 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-01 10:59:35.146  6776  6776 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-01 10:59:35.146  6776  6776 I wpa_supplicant: Blacklist: Clear (temp) 
09-01 10:59:35.146  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-01 10:59:35.146  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:35.146  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:35.146  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,09-01 10:59:35.146  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:35.146  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.156  1015  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-01 10:59:35.156  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-01 10:59:35.166  1015  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-01 10:59:35.166  1015  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:35.166  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:35.166  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 10:59:35.166  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:35.166  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:35.166  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.166  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.166  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.166  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.176  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:35.176  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:35.176  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:35.176  1015  1216 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:35.176  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.176  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:35.176  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 10:59:35.186  3623  3623 I Hs20UtilService: Starting #14,
09-01 10:59:35.186  3623  3665 I Hs20UtilService: Message received 5007
09-01 10:59:35.186  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:35.186  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:35.186  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:35.186  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:35.186  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 10:59:35.186  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:35.186  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:35.196   276   988 D CommandListener: Setting iface cfg,
,09-01 10:59:35.196  1015  1130 E WifiStateMachine: Start Dhcp Watchdog 2
,09-01 10:59:35.206  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:35.206  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.206  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,09-01 10:59:35.206  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:35.206  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.206  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.206  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.206  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.216  1015  1130 E WifiNative-wlan0: do suspend false
,09-01 10:59:35.216  1015  1125 D WifiP2pService: InactiveState{ what=143375 },
09-01 10:59:35.216  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-01 10:59:35.216  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:35.216  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.426  6809  6809 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-01 10:59:35.436  6809  6809 I dhcpcd  : version 5.5.6 starting,
,09-01 10:59:35.436  6809  6809 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-01 10:59:35.476  6809  6809 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-01 10:59:35.476  6809  6809 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 10:59:35.476  6809  6809 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-01 10:59:35.476  6809  6809 I dhcpcd  : bssid match
09-01 10:59:35.476  6809  6809 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-01 10:59:35.536  6809  6809 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,09-01 10:59:35.566  1015  1476 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-01 10:59:35.566  1015  1476 D WifiService: setWifiEnabled: false pid=6223, uid=10155
09-01 10:59:35.566  1015  1476 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-01 10:59:35.566  1015  1476 D SecContentProvider2: mCursor = null,
09-01 10:59:35.566  1015  1476 D SettingsProvider: name = wifi_on
,09-01 10:59:35.576  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:35.586  1015  1130 E WifiNative-wlan0: do suspend true
,09-01 10:59:35.606  1015  1125 D WifiP2pService: InactiveState{ what=143375 },
,09-01 10:59:35.606  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 },
,09-01 10:59:35.616   276   988 D CommandListener: Clearing all IP addresses on wlan0
09-01 10:59:35.616  6809  6809 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-01 10:59:35.616  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:35.616  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:35.616  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:35.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.616  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-01 10:59:35.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.616  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.616  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:35.616  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:35.626   276   988 E Netd    : no such netId 503
,09-01 10:59:35.626  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
,09-01 10:59:35.626  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-01 10:59:35.626  1015  1132 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
,09-01 10:59:35.626  1015  1132 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-01 10:59:35.626  1015  1130 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 10:59:35.626  1015  1132 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-01 10:59:35.626  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:35.626  1015  6806 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:35.626  1015  6806 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-01 10:59:35.626  1015  1132 D ConnectivityService: nai.networkMonitor.doQuit()
,09-01 10:59:35.626  1015  1132 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:35.626  1015  1132 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-01 10:59:35.626  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-01 10:59:35.636  1015  1132 E ConnectivityService: updateNetworkInfo(),
,09-01 10:59:35.636  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,09-01 10:59:35.636  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:35.646  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:35.646  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:35.646  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.646  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.646  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.646  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.646  1015  1015 D RttService: SCAN_AVAILABLE : 1
,09-01 10:59:35.646  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-01 10:59:35.656  1015  1041 I ActivityManager: Killing 6136:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-01 10:59:35.666  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-01 10:59:35.666  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:35.666  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:35.666  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
09-01 10:59:35.666  1015  3154 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:35.666  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:35.666  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.666  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.666  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:35.666  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-01 10:59:35.666  1015  1132 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:35.676  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-01 10:59:35.676  3623  3623 I Hs20UtilService: Starting #15
,09-01 10:59:35.676  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-01 10:59:35.676  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:35.676  1015  1046 D WifiDisplayController: disconnect
09-01 10:59:35.676  1015  1046 D WifiDisplayController: updateConnection
09-01 10:59:35.676  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:35.676  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:35.676  3623  3665 I Hs20UtilService: Message received 5007
,09-01 10:59:35.676  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-01 10:59:35.686  1015  1557 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:35.686  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-01 10:59:35.686  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:35.686  1015  1125 D WifiP2pService: P2pDisablingState
09-01 10:59:35.686  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
09-01 10:59:35.686  1015  1125 D WifiP2pService: p2p socket connection lost
09-01 10:59:35.686  1015  1125 D WifiP2pService: P2pDisabledState
09-01 10:59:35.686  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 10:59:35.686  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-01 10:59:35.686  1015  1130 E WifiNative-wlan0: do suspend true
,09-01 10:59:35.696  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-01 10:59:35.696  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:35.696  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:35.696  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 10:59:35.696  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:35.696  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:35.696  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:35.696  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:35.706  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-01 10:59:35.706  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:35.716  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:35.716  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:35.726  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:35.726  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-01 10:59:35.726   276   988 D CommandListener: Clearing all IP addresses on wlan0,
09-01 10:59:35.726  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
09-01 10:59:35.726  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
,09-01 10:59:35.726  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:35.726  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:35.726  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.726  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.726  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:35.726  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.736  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-01 10:59:35.736  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:35.736  6776  6776 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-01 10:59:35.736  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:35.736  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 10:59:35.736  6463  6463 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:35.746  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:35.746  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:35.746  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.746  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.746  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.746  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:35.746  6478  6478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:35.746  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:35.746  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:35.756  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:35.756  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:35.756  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.756  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.756  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.756  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:35.756  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:35.756  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-01 10:59:35.756  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-01 10:59:35.756  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:35.756  1175  1175 D HotspotTile: onReceive : 0, 0
,09-01 10:59:35.756  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:35.756  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:35.756  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:35.756  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:35.756  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:35.766  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:35.766  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:35.766  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:35.766  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:35.766  1015  1557 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
09-01 10:59:35.766  1015  1557 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:35.766  1015  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:35.766  1015  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:35.766  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:35.766  3623  3623 I Hs20UtilService: Starting #16
09-01 10:59:35.766  3623  3665 I Hs20UtilService: Message received 5007
,09-01 10:59:35.776  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-01 10:59:35.786  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:35.786  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
,09-01 10:59:35.786  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-01 10:59:35.786  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:35.786  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:35.786  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:35.796  1015  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:35.796  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:35.796  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:35.796  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:35.796  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:35.806  3623  3623 I Hs20UtilService: Starting #17
,09-01 10:59:35.806  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:35.806  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
09-01 10:59:35.806  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:35.806  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:35.806  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:35.846  6776  6776 I wpa_supplicant: Blacklist: Clear (all) ,
,09-01 10:59:36.006  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:36.006  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:36.006  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
09-01 10:59:36.006  6776  6776 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-01 10:59:36.036  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.036  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:36.036  6776  6776 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-01 10:59:36.036  1015  1133 D Tethering: InitialState.processMessage what=4,
,09-01 10:59:36.036  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:36.036  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.046  1015  1130 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-01 10:59:36.036  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:36.046  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.036  6776  6776 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-01 10:59:36.046  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:36.036  6776  6776 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-01 10:59:36.046  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:36.046  6776  6776 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:36.046  1175  1175 D HotspotTile: updateTetherState():false, false
09-01 10:59:36.046  6776  6776 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-01 10:59:36.046  1015  1133 E Tethering: No numeric data
09-01 10:59:36.046  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-01 10:59:36.046  1015  1133 D Tethering: clearTetheredNotification()
09-01 10:59:36.046  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:36.046  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:36.046  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:36.046  1015  1123 V NetworkStats: performPollLocked() took 6ms
,09-01 10:59:36.046  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:36.056  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.056  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:36.056  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:36.056  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:36.056  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:36.116  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.116  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:36.116  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:36.366  6776  6776 I wpa_supplicant: Blacklist: Clear (all) ,
,09-01 10:59:36.486  6776  6776 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-01 10:59:36.506  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:36.506  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:36.506  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:36.556  1015  3161 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:36.556  1015  3161 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4033, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-01 10:59:36.556  1015  3161 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-01 10:59:36.556  1015  3161 D BatteryService: stay LED for charging
09-01 10:59:36.556  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-01 10:59:36.566  1015  1015 I MotionRecognitionService: Plugged
,09-01 10:59:36.566  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:36.566  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-01 10:59:36.566  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-01 10:59:36.566  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-01 10:59:36.566  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75,
,09-01 10:59:36.596  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:36.596  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:36.596  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:36.596  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-01 10:59:36.596  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:36.596  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 10:59:36.606  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:36.606  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:36.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:36.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:36.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:36.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:36.606  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:36.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:36.606  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-01 10:59:36.606  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:36.606  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:36.606  1175  1175 D HotspotTile: onReceive : 1, 0
,09-01 10:59:36.606  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:36.616  1913  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-01 10:59:36.616  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 10:59:36.616  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:36.616  1015  3162 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:36.616  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:36.616  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:36.616  1015  3162 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:36.616  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:36.616  3623  3623 I Hs20UtilService: Starting #18
,09-01 10:59:36.616  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:36.616  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:36.616  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-01 10:59:36.616  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:36.626  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:37.066  1015  2741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:37.246   287   287 E SMD     : DCD OFF,
,09-01 10:59:37.316  1015  1043 D Tethering: interfaceRemoved wlan0
,09-01 10:59:37.316  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-01 10:59:37.406  1015  1314 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-01 10:59:37.406  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.416  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.416  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:37.416  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-01 10:59:37.426  6633  6682 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-01 10:59:37.436  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.436  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:37.436  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.446  1015  3154 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-01 10:59:37.446  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.446  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:37.446  1015  3154 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.446  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.456  1015  1043 D Tethering: interfaceRemoved p2p0
09-01 10:59:37.456  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-01 10:59:37.456  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.456  1015  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.466  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.476  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:37.476  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.476  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.476  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:37.476  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.486  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-01 10:59:37.486  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-01 10:59:37.486  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.486  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:37.486  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.486  1015  1475 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:37.486  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-01 10:59:37.486  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.486  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:37.486  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.506  1015  3162 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-01 10:59:37.506  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
09-01 10:59:37.506  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:37.506  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.506  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.536  1015  1559 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:37.546  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.546  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.546  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-01 10:59:37.556  1913  1913 D WearableService: callingUid 10012, callindPid: 1913
,09-01 10:59:37.576  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-01 10:59:37.576  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-01 10:59:37.576  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:37.576  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:37.576  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-01 10:59:37.586  6546  6842 I MusicLeanback: Conditions not met for autocaching.
,09-01 10:59:37.586  6546  6842 I MusicLeanback: Stop autocaching.
,09-01 10:59:37.626  6546  6546 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-01 10:59:37.626  6546  6847 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-01 10:59:38.226  1015  2703 D SSRM:n  : SIOP:: AP = 330
,09-01 10:59:38.396  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-01 10:59:38.576  6223  6275 D BluetoothAdapter: enable()
,09-01 10:59:38.576  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:38.576  1015  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-01 10:59:38.576  1015  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:38.586  1015  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-01 10:59:38.586  1015  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:38.586  1015  1027 D SettingsProvider: name = bluetooth_on,
,09-01 10:59:38.586  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:38.586  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:38.596  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-01 10:59:38.596  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-01 10:59:38.626  6511  6511 D BluetoothAdapterState: make
,09-01 10:59:38.636  6511  6511 I bluedroid: init
,09-01 10:59:38.636  6511  6853 I BluetoothAdapterState: Entering OffState,
,09-01 10:59:38.636  6511  6511 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 10:59:38.636  6511  6511 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 10:59:38.636  6511  6511 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-01 10:59:38.646  6511  6511 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-01 10:59:38.646  6511  6511 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-01 10:59:38.646  6511  6511 I bluedroid: get_profile_interface socket
09-01 10:59:38.646  6511  6511 I bluedroid: get_profile_interface map_client,
09-01 10:59:38.646  6511  6856 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
,09-01 10:59:38.646  6511  6511 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-01 10:59:38.646  6511  6856 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-01 10:59:38.646  6511  6856 E BluetoothServiceJni: populateRssiValuesNative
,09-01 10:59:38.646  6511  6856 I bluedroid: getModelRssiValues
09-01 10:59:38.646  6511  6856 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:38.646  6511  6856 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:38.656  6511  6856 D BluetoothAdapterProperties: Name is: A5-1
,09-01 10:59:38.656  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:38.656  6511  6511 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:38.656  1015  1138 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:38.656  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.656  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.656  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.656  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.666  6511  6519 I bluedroid: config_hci_snoop_log
,09-01 10:59:38.666  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-01 10:59:38.666  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-01 10:59:38.666  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-01 10:59:38.666  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-01 10:59:38.666  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:38.676  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:38.676  6511  6511 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-01 10:59:38.676  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:38.676  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-01 10:59:38.676  6511  6853 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-01 10:59:38.676  6511  6853 D BluetoothAdapterProperties: Setting state to 11
,09-01 10:59:38.676  6511  6853 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-01 10:59:38.676  6511  6853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:38.676  6511  6853 D BluetoothAdapterService: updateAdapterState state is 11
,09-01 10:59:38.676  6511  6853 D BluetoothAdapterService: Autoconnection is available 
,09-01 10:59:38.676  6511  6853 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-01 10:59:38.686  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:38.686  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-01 10:59:38.686  6511  6853 D BluetoothSecureManager: getInstant: null
09-01 10:59:38.686  6511  6853 D BluetoothSecureManager: calling getMethod for getService
09-01 10:59:38.686  6511  6853 D BluetoothSecureManager: calling getService
09-01 10:59:38.686  6511  6853 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@214ec234
,09-01 10:59:38.686  1015  1557 D BluetoothSecureManagerService: isSecureModeEnabled
,09-01 10:59:38.686  1015  1557 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-01 10:59:38.696  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:38.696  6511  6853 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:38.696  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:38.696  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:38.696  1814  1814 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:38.696  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
09-01 10:59:38.696  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:38.696  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.696  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:38.706  1015  3166 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:38.706  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:38.706  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:38.706  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:38.706  6511  6853 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-01 10:59:38.706  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:38.706  6511  6853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.706  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.706  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:38.706  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-01 10:59:38.706  6511  6853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.706  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-01 10:59:38.716  6511  6853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.716  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:38.716  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-01 10:59:38.716  6511  6853 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-01 10:59:38.716  6511  6853 D BluetoothBondStateMachine: make
,09-01 10:59:38.716  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-01 10:59:38.716  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 10:59:38.716  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-01 10:59:38.716  6511  6859 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 10:59:38.856  1015  1557 I art     : Explicit concurrent mark sweep GC freed 68190(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.512ms total 152.547ms
,09-01 10:59:38.856  1015  1314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:38.856  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.856  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.856  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:38.856  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:38.866  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:38.866  1015  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.866  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.866  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.866  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.866  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.866  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:38.866  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:38.866  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:38.866  6511  6511 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:38.866  6511  6511 D BtGatt.GattService: Received start request. Starting profile...
09-01 10:59:38.866  6511  6511 D BtGatt.GattService: start()
09-01 10:59:38.866  6511  6511 D BtGatt.GattService: start()
09-01 10:59:38.866  6511  6511 I bluedroid: get_profile_interface gatt
,09-01 10:59:38.866  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:38.866  6511  6511 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:38.876  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.876  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.876  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.876  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.876  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.876  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:38.876  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:38.876  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:38.886  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:38.886  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-01 10:59:38.886  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.886  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.886  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.886  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.886  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.886  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-01 10:59:38.886  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:38.886  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 10:59:38.886  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.886  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.896  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:38.896  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:38.896  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:38.896  6511  6511 D BtGatt.GattService: mStartError = false
09-01 10:59:38.896  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:38.896  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-01 10:59:38.896  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 10:59:38.896  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-01 10:59:38.896  6511  6511 D HeadsetService: Received start request. Starting profile...
09-01 10:59:38.896  6511  6511 D HeadsetService: start()
,09-01 10:59:38.896  6511  6511 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 10:59:38.896  6511  6511 D HeadsetStateMachine: make
,09-01 10:59:38.896  1015  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.896  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.906  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.906  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.906  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.906  6511  6511 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 10:59:38.906  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:38.906  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:38.906  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-01 10:59:38.906  1015  3166 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.916  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.916  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.916  1015  3166 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.916  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.916  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.916  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:38.916  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:38.916  1015  1475 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-01 10:59:38.916  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.916  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.916  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.916  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:38.916  1015  3161 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:38.916  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.916  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.916  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.916  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.926  1015  1321 E Watchdog: !@Sync 4
,09-01 10:59:38.926  1015  1138 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-01 10:59:38.926  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.926  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.926  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:38.926  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:38.926  6511  6511 I bluedroid: get_profile_interface handsfree
,09-01 10:59:38.936  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-01 10:59:38.936  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:38.936  6511  6853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:38.936  1015  3140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:38.936  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:38.936  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:38.936  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:38.936  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.946  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.946  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.946  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:38.946  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:38.946  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-01 10:59:38.946  6511  6853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-01 10:59:38.946  6511  6511 I DualScoManager: Instantiating Dual Sco Manager
,09-01 10:59:38.946  6511  6511 I DualScoManager: Set HeadsetServiceHelper
,09-01 10:59:38.946  6511  6511 D BluetoothAtMessage: createCMTIContentObservers
,09-01 10:59:38.946  1015  1558 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-01 10:59:38.946  1015  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-01 10:59:38.946  1015  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:38.946  1015  1558 D SettingsProvider: selectionArgs: false
09-01 10:59:38.946  1015  1558 D SettingsProvider: selectionArgs: 1002
09-01 10:59:38.946  1015  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:38.946  1015  1558 D SettingsProvider: ret = -1
09-01 10:59:38.946  6511  6863 D HeadsetStateMachine: Enter Disconnected: -2
09-01 10:59:38.956  6511  6511 D HeadsetService: mStartError = false,
09-01 10:59:38.956  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:38.956  6511  6863 D HeadsetStateMachine: Clear mHeadsetBrsf
09-01 10:59:38.956  6511  6511 D A2dpService: Received start request. Starting profile...
09-01 10:59:38.956  6511  6511 D A2dpService: start()
,09-01 10:59:38.956  6511  6863 D HeadsetStateMachine: map size, before remove : 0
,09-01 10:59:38.956  6511  6863 D HeadsetStateMachine: map size, after remove: 0
,09-01 10:59:38.956  6511  6511 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-01 10:59:38.956  6511  6511 I bluedroid: get_profile_interface avrcp
,09-01 10:59:38.966  6511  6511 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,09-01 10:59:38.976  6511  6511 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 10:59:38.976  6511  6867 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 10:59:38.976  6511  6511 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 10:59:38.976  6511  6511 D A2dpStateMachine: make
,09-01 10:59:38.976  6511  6511 I bluedroid: get_profile_interface a2dp
09-01 10:59:38.976  6511  6869 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-01 10:59:38.976  6511  6511 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 10:59:38.986  6511  6511 D A2dpService: mStartError = false
09-01 10:59:38.986  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:38.986  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-01 10:59:38.986  6511  6511 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 10:59:38.986  6511  6511 D HidService: Received start request. Starting profile...
09-01 10:59:38.986  6511  6511 D HidService: start()
09-01 10:59:38.986  6511  6511 I bluedroid: get_profile_interface hidhost
09-01 10:59:38.986  6511  6511 D HidService: setHidService(): set to: null
09-01 10:59:38.986  6511  6511 D HidService: mStartError = false
09-01 10:59:38.986  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:38.986  6511  6511 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 10:59:38.986  6511  6511 D HealthService: Received start request. Starting profile...
09-01 10:59:38.986  6511  6511 D HealthService: start()
09-01 10:59:38.986  6511  6868 D A2dpStateMachine: Enter Disconnected: -2
,09-01 10:59:38.986  6511  6511 I bluedroid: get_profile_interface health
09-01 10:59:38.996  6511  6511 D HealthService: mStartError = false
09-01 10:59:38.996  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:38.996  6511  6511 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 10:59:38.996  6511  6867 D BluetoothMediaBrowser: no now playing list
09-01 10:59:38.996  6511  6867 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 10:59:38.996  6511  6511 D PanService: Received start request. Starting profile...
09-01 10:59:38.996  6511  6511 D PanService: start()
09-01 10:59:38.996  6511  6511 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 10:59:38.996  6511  6511 I bluedroid: get_profile_interface pan
,09-01 10:59:38.996  6511  6511 D PanService: mStartError = false
09-01 10:59:38.996  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:38.996  6511  6511 D HeadsetStateMachine: Try to query the phonestate on bind
09-01 10:59:38.996  1430  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:38.996  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-01 10:59:38.996  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:38.996  1430  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 10:59:39.006  6511  6511 D BluetoothMapService: Received start request. Starting profile...
09-01 10:59:39.006  6511  6511 D BluetoothMapService: start()
,09-01 10:59:39.006  6511  6511 D BluetoothMapService: mStartError = false
09-01 10:59:39.006  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:39.006  6511  6511 D HeadsetStateMachine: Proxy object connected
,09-01 10:59:39.006  6511  6511 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 10:59:39.006  6511  6863 D HeadsetStateMachine: Disconnected process message: 11
09-01 10:59:39.006  6511  6511 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-01 10:59:39.006  6511  6511 D SapService: Received start request. Starting profile...
09-01 10:59:39.006  6511  6511 D SapService: start()
09-01 10:59:39.006  6511  6511 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 10:59:39.006  6511  6511 I bluedroid: get_profile_interface sap
09-01 10:59:39.006  6511  6511 D SapService: mStartError = false
09-01 10:59:39.006  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:39.006  6511  6511 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 10:59:39.006  6511  6511 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-01 10:59:39.006  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-01 10:59:39.006  6511  6511 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 10:59:39.006  6511  6511 D BluetoothA2dp: Proxy object connected
09-01 10:59:39.006  6511  6511 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-01 10:59:39.006  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,09-01 10:59:39.006  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-01 10:59:39.006  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-01 10:59:39.006  6511  6863 D HeadsetStateMachine: Disconnected process message: 18
09-01 10:59:39.006  6511  6863 D HeadsetStateMachine: Disconnected process message: 10
09-01 10:59:39.006  6511  6863 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-01 10:59:39.006  6511  6863 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:39.016  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-01 10:59:39.016  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:39.026  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:39.046  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-01 10:59:39.046  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 10:59:39.046  6511  6853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-01 10:59:39.046  6511  6853 I bluedroid: enable
,09-01 10:59:39.046  6511  6853 I bt_hci_bdroid: init
,09-01 10:59:39.046  6511  6873 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-01 10:59:39.056  6511  6853 I bt_vendor: bt-vendor : init
,09-01 10:59:39.056  6511  6853 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 10:59:39.056  6511  6853 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-01 10:59:39.056  6511  6853 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-01 10:59:39.056  6511  6853 D bt_userial_mct: userial_init
,09-01 10:59:39.056  6511  6853 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 10:59:39.056  6511  6853 I bt_vendor: Starting hciattach daemon
09-01 10:59:39.056  6511  6853 I bt_vendor: try to set false
,09-01 10:59:39.066  6511  6853 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-01 10:59:39.066  6511  6853 I bt_vendor: Starting hciattach daemon
,09-01 10:59:39.066  6511  6853 I bt_vendor: try to set true
,09-01 10:59:39.076  6877  6877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,09-01 10:59:39.126  6883  6883 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-01 10:59:39.136  6884  6884 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:39.146  6886  6886 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:39.156  6887  6887 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-01 10:59:39.166  6888  6888 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:39.176  6889  6889 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-01 10:59:39.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-01 10:59:39.416  6892  6892 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-01 10:59:39.426  6893  6893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:39.476  6511  6853 I bt_vendor: bluetooth satus is on,
09-01 10:59:39.476  6511  6875 D bt_userial_mct: userial_open(port:0)
09-01 10:59:39.476  6511  6875 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-01 10:59:39.476  6511  6875 I bt_vendor: Done intiailizing UART,
,09-01 10:59:39.476  6511  6875 I bt_vendor: Done intiailizing UART,
09-01 10:59:39.476  6511  6875 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-01 10:59:39.476  6511  6875 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
09-01 10:59:39.476  6511  6895 D bt_userial_mct: Entering userial_read_thread()
,09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_HCI
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_A2D,
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_BTM
,09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_PAN,
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_SAP
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_SDP,
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_SMP,
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 10:59:39.486  6511  6873 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-01 10:59:39.586  6511  6873 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-01 10:59:39.596  6511  6873 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa408d6e9 
,09-01 10:59:39.596  6511  6873 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa408d6e9 
,09-01 10:59:39.606  6511  6856 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-01 10:59:39.616  6511  6856 E bt-btif : Calling BTA_HhEnable
,09-01 10:59:39.616  6511  6856 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-01 10:59:39.616  6511  6856 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-01 10:59:39.616  6511  6856 E BluetoothServiceJni: populateRssiValuesNative
,09-01 10:59:39.616  6511  6856 I bluedroid: getModelRssiValues
,09-01 10:59:39.616  6511  6856 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:39.616  6511  6856 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:39.616  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:39.626  6511  6856 D BluetoothAdapterProperties: Name is: A5-1
,09-01 10:59:39.626  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:39.626  6511  6856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:39.626  6511  6856 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:39.626  6511  6856 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:39.626  6511  6856 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-01 10:59:39.626  6511  6856 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-01 10:59:39.636  6511  6856 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-01 10:59:39.636  6511  6856 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-01 10:59:39.636  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:39.636  6511  6856 E bt-btif : btif_sock_init: !vhci_init
,09-01 10:59:39.636  6511  6856 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-01 10:59:39.636  6511  6895 E bt_mct  : hci lib postload completed
,09-01 10:59:39.636  6511  6856 D IOP_DB_BT: db_open: db_open : handle 2968834064l, read 13894 bytes onto local cache
09-01 10:59:39.636  6511  6856 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-01 10:59:39.636  6511  6856 D IOP_DB_BT: db_query: result 1
,09-01 10:59:39.636  6511  6856 I         : iop_db_open: iop_db_open status 0
,09-01 10:59:39.636  6511  6856 D bte_conf: Device ID record 1 : primary
,09-01 10:59:39.636  6511  6856 D bte_conf:   vendorId            = 0075
09-01 10:59:39.636  6511  6856 D bte_conf:   vendorIdSource      = 0001
,09-01 10:59:39.636  6511  6856 D bte_conf:   product             = 0100
09-01 10:59:39.636  6511  6856 D bte_conf:   version             = 0200
,09-01 10:59:39.636  6511  6856 D bte_conf:   clientExecutableURL = 
09-01 10:59:39.646  6511  6856 D bte_conf:   serviceDescription  = 
,09-01 10:59:39.646  6511  6856 D bte_conf:   documentationURL    = 
,09-01 10:59:39.646  6511  6856 D bte_conf: bte_load_did_conf no section named DID2.
,09-01 10:59:39.646  6511  6853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-01 10:59:39.646  6511  6853 D BluetoothAdapterProperties: ScanMode =  20
09-01 10:59:39.646  6511  6853 D BluetoothAdapterProperties: State =  11
,09-01 10:59:39.646  6511  6856 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 10:59:39.646  1015  3140 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:39.646  6511  6853 D BluetoothAdapterProperties: Setting state to 12
,09-01 10:59:39.646  6511  6853 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:39.656  6511  6856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:39.656  6511  6856 D BluetoothAdapterProperties: Scan Mode:21
09-01 10:59:39.656  6511  6856 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:39.656  1015  3161 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-01 10:59:39.656  1015  3161 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:39.656  1015  3161 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:39.656  1015  3161 D SettingsProvider: selectionArgs: false
09-01 10:59:39.656  1015  3161 D SettingsProvider: selectionArgs: 1002
09-01 10:59:39.656  1015  3161 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:39.656  1015  3161 D SettingsProvider: ret = -1
,09-01 10:59:39.656  6511  6853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:39.656  6511  6853 D BluetoothAdapterService: updateAdapterState state is 12
,09-01 10:59:39.656  1015  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:39.656  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.656  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.656  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.656  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.666  6511  6853 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:39.666  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:39.666  6511  6853 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 10:59:39.666  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-01 10:59:39.666  6511  6853 D BluetoothAdapterService: starting service from this receiver
09-01 10:59:39.666  6511  6857 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:39.666  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.666  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.666  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:39.676  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.676  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.676  1322  6415 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:39.676  1322  6415 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:39.676  6511  6853 I BluetoothAdapterState: Entering On State from state = 11
,09-01 10:59:39.686  6223  6231 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:39.686  6223  6231 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.686  1322  1332 D Bluetoothsap: onBluetoothStateChange: up=true
,09-01 10:59:39.686  1322  1332 D Bluetoothsap: Binding service...
,09-01 10:59:39.686  1322  1332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-01 10:59:39.686  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-01 10:59:39.696  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:39.696  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:39.696  6511  6511 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-01 10:59:39.706  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.706  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.706  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.706  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:39.706  1322  1332 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-01 10:59:39.706  1322  1333 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:39.706  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:39.706  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-01 10:59:39.716  6511  6511 I BluetoothPbapService: Handler(): got msg=1
,09-01 10:59:39.716  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.716  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.716  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:39.716  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.716  1015  3166 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:39.716  1015  1045 D BluetoothPan: Binding service...
,09-01 10:59:39.716  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-01 10:59:39.716  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.716  2845  2894 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:39.716  2845  2894 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.716  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:39.716  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.726  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.726  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.726  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.726  6511  6899 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 10:59:39.726  2845  2845 D BluetoothA2dp: Proxy object connected
,09-01 10:59:39.726  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 10:59:39.726  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:39.726  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 10:59:39.726  1322  1322 D SapProfile: Bluetooth service connected
09-01 10:59:39.726  1322  1322 D Bluetoothsap: getConnectedDevices()
,09-01 10:59:39.726  1430  6412 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.726  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:39.726  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.726  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.726  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.726  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.736  1430  6412 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.736  1430  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.736  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:39.736  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.736  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.736  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.736  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.736  1430  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.736  1456  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.736  1322  1322 D BluetoothMap: Proxy object connected
09-01 10:59:39.736  1322  1322 D MapProfile: Bluetooth service connected
09-01 10:59:39.736  1322  1322 D BluetoothMap: getConnectedDevices()
09-01 10:59:39.736  6511  6899 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:39.736  6511  6899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:39.736  1456  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.736  6511  6899 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-01 10:59:39.736  6511  6899 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:39.736  6511  6899 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:39.736  6511  6899 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2067eb18
,09-01 10:59:39.736  6511  6899 D BluetoothSocket: channel: 19
09-01 10:59:39.736  6511  6899 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-01 10:59:39.746  1322  6415 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.746  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:39.746  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.746  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:39.746  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.746  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.746  1322  6415 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.746  1322  1333 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 10:59:39.746  1322  1322 D HeadsetProfile: Bluetooth service connected
,09-01 10:59:39.746  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-01 10:59:39.746  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.756  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.756  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.756  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.756  1322  1332 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 10:59:39.756  1322  1322 D BluetoothInputDevice: Proxy object connected
,09-01 10:59:39.756  1322  1322 D HidProfile: Bluetooth service connected
,09-01 10:59:39.756  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 10:59:39.756  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.756  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:39.756  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.756  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.756  1322  1322 D BluetoothPbap: Proxy object connected
09-01 10:59:39.756  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:39.756  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:39.756  1322  1322 D PbapServerProfile: Bluetooth service connected
09-01 10:59:39.766  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:39.766  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:39.766  1015  1015 D BluetoothA2dp: Proxy object connected
,09-01 10:59:39.766  2845  2863 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.766  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:39.766  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.766  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.766  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.766  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.766  2845  2863 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.766  1456  1680 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.766  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:39.766  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.766  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.766  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.766  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.766  1456  1680 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.766  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:39.766  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:39.766  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.776  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
09-01 10:59:39.776  1175  1196 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.776  1175  1196 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.776  1438  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.776  1438  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:39.776  6511  6525 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.776  6511  6525 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.776  1322  6415 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:39.776  1322  6415 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:39.776  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:39.776  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.776  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.776  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.776  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.776  1430  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.776  1430  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.776  1913  1922 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.776  1913  1922 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:39.776  1322  1322 D BluetoothA2dp: Proxy object connected
09-01 10:59:39.776  1322  1322 D A2dpProfile: Bluetooth service connected
,09-01 10:59:39.776  1322  1333 D BluetoothPan: Binding service...
,09-01 10:59:39.786  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 10:59:39.786  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.786  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.786  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.786  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.786  6383  6398 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:39.786  6383  6398 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.786  2845  2894 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:39.786  2845  2894 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:39.786  1322  1322 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 10:59:39.786  1430  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:39.786  1322  1322 D PanProfile: Bluetooth service connected
09-01 10:59:39.786  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:39.786  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:39.786  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.786  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.786  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.786  1430  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:39.786  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 10:59:39.786  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:39.786  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:39.796  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-01 10:59:39.796  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 10:59:39.796  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:39.796  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3ee68ee7, true
,09-01 10:59:39.796  1430  1430 D BluetoothHeadset: registerMessageListener,
09-01 10:59:39.796  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:39.796  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:39.796  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-01 10:59:39.806  1814  1814 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:39.806  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:39.806  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:39.806  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:39.806  1015  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:39.806  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.806  1015  3162 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-01 10:59:39.806  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:39.806  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.816  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:39.816  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:39.816  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:39.816  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:39.816  6511  6858 D HeadsetService: registerMessageListener
,09-01 10:59:39.816  6511  6858 D HeadsetService: registerMessageListener
,09-01 10:59:39.816  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-01 10:59:39.816  6511  6863 D HeadsetStateMachine: Disconnected process message: 70
09-01 10:59:39.816  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-01 10:59:39.816  6511  6900 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-01 10:59:39.816  6511  6863 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22709971
09-01 10:59:39.816  1322  1322 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-01 10:59:39.816  1322  1322 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 10:59:39.816  1322  1322 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-01 10:59:39.816  1322  1322 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 10:59:39.826  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 10:59:39.826  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-01 10:59:39.826  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-01 10:59:39.826  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:39.826  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
09-01 10:59:39.826  6511  6863 D HeadsetStateMachine: Disconnected process message: 9
09-01 10:59:39.826  6511  6900 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:39.826  6511  6900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:39.826  6511  6863 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 10:59:39.826  6511  6900 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-01 10:59:39.826  6511  6900 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:39.826  6511  6900 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:39.826  6511  6900 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1717f356
,09-01 10:59:39.826  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:39.826  1015  3161 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:39.826  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.826  6511  6900 D BluetoothSocket: channel: 5
,09-01 10:59:39.826  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.826  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.826  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:39.836   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-01 10:59:39.836   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 10:59:39.836   282   282 V voice   : voice_set_parameters: exit with code(-2)
,09-01 10:59:39.836   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-01 10:59:39.836   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 10:59:39.836   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,09-01 10:59:39.836   282   282 V audio_hw_primary: adev_set_parameters: exit
09-01 10:59:39.836  6511  6863 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-01 10:59:39.846  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:39.856  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:39.856  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:39.856  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-01 10:59:39.866  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:39.866  6511  6511 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:39.866  1015  3166 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:39.866  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.866  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:39.866  1015  3166 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:39.866  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:39.886  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:39.886  1015  1557 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:39.886  1015  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:39.886  1015  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:39.886  1015  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:39.886  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:39.896  1015  1500 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:39.896  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-01 10:59:39.896  1913  6908 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:39.896  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:39.906  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:39.906  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:39.906  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:39.906  6511  6911 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:39.906  6511  6911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:39.906  6511  6911 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-01 10:59:39.906  6511  6911 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:39.906  6511  6911 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:39.906  6511  6911 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28b7eee2
,09-01 10:59:39.906  6511  6911 D BluetoothSocket: channel: 12
09-01 10:59:39.906  6511  6911 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:40.006  1913  2105 I art     : Explicit concurrent mark sweep GC freed 66656(3MB) AllocSpace objects, 83(3MB) LOS objects, 40% free, 14MB/24MB, paused 1.722ms total 88.492ms
,09-01 10:59:40.006  1015  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:40.006  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:40.006  1015  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:40.006  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:40.016  1913  6908 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-01 10:59:40.246   287   287 E SMD     : DCD OFF
,09-01 10:59:40.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:41.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:41.596  6223  6275 D BluetoothAdapter: disable()
,09-01 10:59:41.596  1015  3166 D SettingsProvider: name = bluetooth_on
,09-01 10:59:41.606  6511  6853 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-01 10:59:41.606  6511  6853 D BluetoothAdapterProperties: Setting state to 13
,09-01 10:59:41.606  6511  6853 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-01 10:59:41.606  6511  6853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-01 10:59:41.606  6511  6853 D BluetoothAdapterService: updateAdapterState state is 13,
,09-01 10:59:41.606  1015  3161 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-01 10:59:41.606  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-01 10:59:41.616  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:41.616  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:41.616  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:41.616  6511  6511 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-01 10:59:41.616  6511  6511 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5e5c273, channel: 19, state: LISTENING
09-01 10:59:41.616  6511  6511 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@5e5c273, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2067eb18, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c050530mSocket: android.net.LocalSocket@28d805a9 impl:android.net.LocalSocketImpl@3f6a172e fd:FileDescriptor[75]
09-01 10:59:41.616  6511  6511 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@28d805a9 impl:android.net.LocalSocketImpl@3f6a172e fd:FileDescriptor[75]
,09-01 10:59:41.616  6511  6853 D BluetoothAdapterService: Autoconnection is available 
,09-01 10:59:41.616  6511  6853 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-01 10:59:41.616  6511  6853 D BluetoothAdapterService: terminating service from this receiver
,09-01 10:59:41.616  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:41.616  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,09-01 10:59:41.636  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:41.636  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:41.636  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:41.636  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:41.636  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-01 10:59:41.636  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:41.646  1814  1814 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-01 10:59:41.646  1015  1557 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:41.646  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:41.646  1015  3166 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 10:59:41.646  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-01 10:59:41.656  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:41.656  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:41.656  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:41.656  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:41.656  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:41.666  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:41.666  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:41.666  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-01 10:59:41.666  6511  6511 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ed012cf, channel: 5, state: LISTENING
09-01 10:59:41.666  6511  6511 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ed012cf, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1717f356, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f6d445cmSocket: android.net.LocalSocket@37825365 impl:android.net.LocalSocketImpl@3d04783a fd:FileDescriptor[77]
09-01 10:59:41.666  6511  6511 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37825365 impl:android.net.LocalSocketImpl@3d04783a fd:FileDescriptor[77]
,09-01 10:59:41.666  6511  6511 I BtOppRfcommListener: stopping Accept Thread
09-01 10:59:41.666  6511  6511 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e650ceb, channel: 12, state: LISTENING
09-01 10:59:41.666  6511  6511 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e650ceb, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28b7eee2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@13b84a48mSocket: android.net.LocalSocket@7c9c0e1 impl:android.net.LocalSocketImpl@18b1de06 fd:FileDescriptor[79]
09-01 10:59:41.666  6511  6511 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@7c9c0e1 impl:android.net.LocalSocketImpl@18b1de06 fd:FileDescriptor[79]
09-01 10:59:41.666  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:41.666  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:41.666  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:41.666  6511  6911 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-01 10:59:41.666  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:41.666  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:41.676  6511  6853 D BluetoothAdapterProperties: onBluetoothDisable()
09-01 10:59:41.676  6511  6853 D BluetoothAdapterProperties: mDiscovering is false
09-01 10:59:41.676  6511  6911 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 10:59:41.676  1015  1476 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-01 10:59:41.676  6511  6853 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-01 10:59:41.676  6223  6223 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:41.676  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:41.676  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:41.676  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:41.676  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:41.676  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:41.686  1015  3161 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-01 10:59:41.686  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:41.686  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:41.686  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:41.686  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:41.696  6511  6856 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:41.696  6511  6856 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:41.696  1322  1322 D BluetoothPbap: Proxy object disconnected
,09-01 10:59:41.706  1322  1322 D PbapServerProfile: Bluetooth service disconnected
,09-01 10:59:41.706  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:41.706  6511  6853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-01 10:59:41.706  6511  6853 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-01 10:59:41.706  6511  6853 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-01 10:59:41.706  6511  6853 E bt-btif : cmd socket is not created
,09-01 10:59:41.706  6511  6873 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-01 10:59:41.706  6511  6853 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-01 10:59:41.716  6511  6873 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 10:59:41.716  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:41.716  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:41.716  6511  6873 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-01 10:59:41.716  6511  6511 V BluetoothOppManager: cleanUp...
,09-01 10:59:41.716  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:41.726  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:41.726  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:41.736  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:41.736  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-01 10:59:41.756  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:41.766  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-01 10:59:41.916  6511  6873 W bt-btif : ag scb idx 1 not allocated
09-01 10:59:41.916  6511  6873 W bt-btif : ag scb idx 2 not allocated
09-01 10:59:41.916  6511  6873 E bt-btif : BTA AG is already disabled, ignoring ...
09-01 10:59:41.916  6511  6895 I bt_userial_mct: exiting userial_read_thread
09-01 10:59:41.916  6511  6895 D bt_userial_mct: Leaving userial_evt_read_thread()
09-01 10:59:41.916  6511  6856 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-01 10:59:41.916  6511  6875 I bt_vendor: hw_epilog_process
09-01 10:59:41.916  6511  6856 D bt_userial_mct: userial_close
09-01 10:59:41.916  6511  6856 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-01 10:59:42.266   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:42.726  6511  6856 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-01 10:59:42.726  6511  6856 I bt_vendor: bluetooth satus is on
,09-01 10:59:42.726  6511  6856 I bt_vendor: bt-vendor : resetting BT status
09-01 10:59:42.726  6511  6856 I bt_vendor: Starting hciattach daemon
,09-01 10:59:42.726  6511  6856 I bt_vendor: try to set false
,09-01 10:59:42.736  6511  6856 I bt_vendor: Starting hciattach daemon,
09-01 10:59:42.736  6511  6856 I bt_vendor: try to set false
,09-01 10:59:42.736  6511  6856 I bt_vendor: cleanup,
09-01 10:59:42.736  6511  6873 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-01 10:59:42.736  6511  6856 I GKI_LINUX: GKI_exit_task 0 done
,09-01 10:59:42.736  6511  6856 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-01 10:59:42.736  6511  6853 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
09-01 10:59:42.736  6511  6853 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:42.736  6511  6853 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-01 10:59:42.736  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-01 10:59:42.736  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 10:59:42.736  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-01 10:59:42.746  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.746  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.746  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.746  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-01 10:59:42.746  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:42.746  1015  1314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.746  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:42.746  1015  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-01 10:59:42.746  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:42.746  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-01 10:59:42.746  6511  6511 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 10:59:42.746  6511  6511 D BtGatt.GattService: Received stop request...Stopping profile...
09-01 10:59:42.746  6511  6511 D BtGatt.GattService: stop()
09-01 10:59:42.746  6511  6511 D BtGatt.AdvertiseManager: advertise clients cleared
09-01 10:59:42.746  1015  1314 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.746  1015  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.746  1015  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:42.746  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:42.746  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:42.746  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:42.746  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:42.746  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:42.746  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:42.746  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.746  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.746  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:42.756  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.756  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:42.756  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-01 10:59:42.756  1015  3154 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:42.756  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.756  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 10:59:42.756  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.756  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-01 10:59:42.756  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-01 10:59:42.756  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.756  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.756  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:42.756  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:42.756  1015  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-01 10:59:42.756  1015  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:42.756  1015  1557 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.756  1015  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.756  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.756  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:42.756  6511  6853 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:42.766  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.766  1015  3161 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.766  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.766  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:42.766  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-01 10:59:42.766  1015  3166 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-01 10:59:42.766  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-01 10:59:42.766  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-01 10:59:42.766  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.766  1015  3166 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.766  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:42.766  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:42.766  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:42.766  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:42.766  6511  6853 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:42.766  6511  6853 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:42.766  6511  6853 D BluetoothAdapterState: Stopping profile services that were post enabled
09-01 10:59:42.766  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-01 10:59:42.766  6511  6511 D HeadsetService: Received stop request...Stopping profile...
,09-01 10:59:42.766  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:42.776  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-01 10:59:42.776  1322  1322 D HeadsetProfile: Bluetooth service disconnected
,09-01 10:59:42.776  6511  6511 D A2dpService: Received stop request...Stopping profile...
,09-01 10:59:42.776  6511  6868 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:42.776  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:42.786  1015  1015 D BluetoothA2dp: Proxy object disconnected
,09-01 10:59:42.786  1322  1322 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:42.786  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-01 10:59:42.786  6511  6511 D HidService: Received stop request...Stopping profile...
09-01 10:59:42.786  6511  6511 D HidService: Stopping Bluetooth HidService
09-01 10:59:42.786  2845  2845 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:42.786  6511  6511 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:42.786  6511  6511 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-01 10:59:42.786  6511  6511 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 10:59:42.786  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:42.786  1322  1322 D A2dpProfile: Bluetooth service disconnected
,09-01 10:59:42.786  1322  1322 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:42.786  6511  6511 D HealthService: Received stop request...Stopping profile...
,09-01 10:59:42.786  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:42.786  1322  1322 D HidProfile: Bluetooth service disconnected
,09-01 10:59:42.786  6511  6511 D PanService: Received stop request...Stopping profile...
,09-01 10:59:42.786  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:42.796  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-01 10:59:42.796  6511  6511 D BluetoothMapService: Received stop request...Stopping profile...
,09-01 10:59:42.796  1322  1322 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:42.796  1322  1322 D PanProfile: Bluetooth service disconnected
,09-01 10:59:42.796  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f,
,09-01 10:59:42.806  6511  6511 D SapService: Received stop request...Stopping profile...
09-01 10:59:42.806  6511  6511 D SapService: Stopping Bluetooth SapService
09-01 10:59:42.806  6511  6511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:42.806  1322  1322 D BluetoothMap: Proxy object disconnected
09-01 10:59:42.806  1322  1322 D MapProfile: Bluetooth service disconnected
,09-01 10:59:42.806  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-01 10:59:42.806  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-01 10:59:42.806  6511  6511 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-01 10:59:42.806  6511  6511 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-01 10:59:42.806  6511  6511 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-01 10:59:42.806  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-01 10:59:42.806  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:42.806  6511  6511 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-01 10:59:42.806  6511  6511 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:42.806  6511  6511 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-01 10:59:42.806  6511  6869 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-01 10:59:42.806  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-01 10:59:42.806  1322  1322 D SapProfile: Bluetooth service disconnected
,09-01 10:59:42.806  6511  6511 I GKI_LINUX: GKI_exit_task 2 done
09-01 10:59:42.806  6511  6511 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-01 10:59:42.806  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-01 10:59:42.806  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.806  6511  6511 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.816  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-01 10:59:42.816  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.816  6511  6511 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.816  6511  6511 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-01 10:59:42.816  6511  6511 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 10:59:42.816  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-01 10:59:42.816  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.816  6511  6511 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:42.816  6511  6511 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 10:59:42.816  6511  6511 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-01 10:59:42.816  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-01 10:59:42.816  6511  6511 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:42.816  6511  6511 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-01 10:59:42.816  6511  6511 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-01 10:59:42.816  6511  6853 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-01 10:59:42.816  6511  6853 D BluetoothAdapterProperties: Setting state to 10
,09-01 10:59:42.816  6511  6853 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-01 10:59:42.816  6511  6853 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:42.816  6511  6853 D BluetoothAdapterService: updateAdapterState state is 10
,09-01 10:59:42.816  6511  6511 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,09-01 10:59:42.816  6511  6511 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-01 10:59:42.816  6511  6853 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:42.816  6511  6853 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-01 10:59:42.816  6511  6901 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:42.816  6511  6853 I BluetoothAdapterState: Entering OffState
09-01 10:59:42.816  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:42.826  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.826  1322  1333 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:42.826  1322  1333 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:42.826  6223  6231 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:42.826  6223  6231 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.826  6223  6231 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-01 10:59:42.826  6223  6231 D BluetoothLeAdvertiser: Exit stop advertising
09-01 10:59:42.826  6223  6231 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-01 10:59:42.826  6223  6231 D BluetoothLeScanner: Exiting stopAllScan
09-01 10:59:42.826  1322  1332 D Bluetoothsap: onBluetoothStateChange: up=false
,09-01 10:59:42.826  1322  1332 D Bluetoothsap: Unbinding service...
09-01 10:59:42.826  1322  6415 D BluetoothMap: onBluetoothStateChange: up=false
,09-01 10:59:42.826  2845  2863 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:42.826  1456  1790 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.826  1456  1790 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.826  1322  1332 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-01 10:59:42.826  1322  6415 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 10:59:42.826  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:42.836  1175  3067 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.836  1175  3067 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-01 10:59:42.836  1438  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
09-01 10:59:42.836  1438  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.836  6511  6857 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.836  6511  6857 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.836  1322  1333 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:42.836  1430  6412 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.836  1430  6412 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.836  1913  1922 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.836  1913  1922 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.836  6383  6398 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.836  6383  6398 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.836  2845  2858 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-01 10:59:42.846  2845  2858 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-01 10:59:42.846  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-01 10:59:42.846  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-01 10:59:42.856  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:42.856  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
09-01 10:59:42.856  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-01 10:59:42.856  6511  6856 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-01 10:59:42.856  6511  6511 I GKI_LINUX: GKI_exit_task 1 done
09-01 10:59:42.856  6511  6511 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-01 10:59:42.856  6511  6511 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 10:59:42.856  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:42.856  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:42.856  1175  1735 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:42.856  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:42.856  1175  1175 D BluetoothTile:  getBluetoothState : 10
09-01 10:59:42.856  1175  1735 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:42.866  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:42.866  1175  1175 D BluetoothAdapter: 32474382: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:42.866  1015  1314 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:42.866  1015  3154 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-01 10:59:42.866  1814  1814 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:42.866  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:42.866  6511  6511 I art     : System.exit called, status: 0
,09-01 10:59:42.866  6511  6511 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-01 10:59:42.866  1913  2125 D BluetoothAdapter: 295479110: getState() :  mService = null. Returning STATE_OFF
09-01 10:59:42.866  1913  2125 D BluetoothAdapter: 295479110: getState() :  mService = null. Returning STATE_OFF
,09-01 10:59:42.866  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:42.866  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:42.866  1015  1559 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:42.876  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:42.876  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:42.876  1015  1559 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:42.876  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:42.876  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:42.876  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:42.876  1015  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:42.876  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:42.876  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:42.876  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:42.876  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:42.886  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:42.886  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:42.896  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:42.896  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-01 10:59:42.906  1015  1216 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-01 10:59:42.916  1015  1216 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-01 10:59:42.916  1015  1216 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-01 10:59:42.916  1015  1216 W BroadcastQueue: android.os.TransactionTooLargeException
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-01 10:59:42.916  1015  1216 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:42.916  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-01 10:59:42.916  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:42.916  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:42.916  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:42.916  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:42.936  6928  6928 E Zygote  : MountEmulatedStorage(),
,09-01 10:59:42.936  6928  6928 E Zygote  : v2,
09-01 10:59:42.936  6928  6928 I libpersona: KNOX_SDCARD checking this for 1002
,09-01 10:59:42.936  6928  6928 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:42.936  1015  1216 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6928 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-01 10:59:42.946  6928  6928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:42.946  6928  6928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:42.946  6928  6928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:42.966   302   302 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 23.760ms
,09-01 10:59:42.976  6928  6928 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:42.976  6928  6928 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:42.986  6928  6928 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-01 10:59:42.986   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 23.011ms
,09-01 10:59:42.986  6928  6928 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:43.006   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 592us total 16.855ms
,09-01 10:59:43.006  6928  6928 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-01 10:59:43.026  1015  1958 V SAMP_SPCM_test: CSC File load.. 
,09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
,09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-01 10:59:43.036  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages,
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-01 10:59:43.066  1015  1958 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-01 10:59:43.076  1015  1958 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,09-01 10:59:43.076  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.076  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.076  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:43.076  1015  1958 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding GattService
,09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding HeadsetService
,09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding A2dpService
,09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding HidService
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding HealthService,
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding PanService
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding SapService,
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-01 10:59:43.086  6943  6943 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding SapClientService,
09-01 10:59:43.086  6943  6943 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:43.086  6928  6928 D BtSettings.ProfileConfig: Adding HidDevService
09-01 10:59:43.086  6943  6943 E Zygote  : MountEmulatedStorage(),
,09-01 10:59:43.086  6943  6943 E Zygote  : v2
09-01 10:59:43.086  6928  6928 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
09-01 10:59:43.086  6943  6943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:43.096  6943  6943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:43.096  1015  1958 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6943 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-01 10:59:43.096  1015  3154 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-01 10:59:43.096  6943  6943 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:43.096  1015  3154 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  3154 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  3154 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  3154 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  3154 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  3154 D SettingsProvider: ret = -1
09-01 10:59:43.096  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-01 10:59:43.096  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  1028 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  1028 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  1028 D SettingsProvider: ret = -1
,09-01 10:59:43.096  1015  1314 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-01 10:59:43.096  1015  1314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  1314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  1314 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  1314 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  1314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  1314 D SettingsProvider: ret = -1
09-01 10:59:43.096  1015  3140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-01 10:59:43.096  1015  3140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  3140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  3140 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  3140 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  3140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  3140 D SettingsProvider: ret = -1
09-01 10:59:43.096  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-01 10:59:43.096  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  1475 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  1475 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  1475 D SettingsProvider: ret = -1
09-01 10:59:43.096  1015  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-01 10:59:43.096  1015  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.096  1015  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.096  1015  1500 D SettingsProvider: selectionArgs: false
09-01 10:59:43.096  1015  1500 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.096  1015  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.096  1015  1500 D SettingsProvider: ret = -1
,09-01 10:59:43.096  1015  3166 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-01 10:59:43.106  1015  3166 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  3166 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  3166 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  3166 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  3166 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  3166 D SettingsProvider: ret = -1
,09-01 10:59:43.106  1015  1557 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-01 10:59:43.106  1015  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  1557 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  1557 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  1557 D SettingsProvider: ret = -1
,09-01 10:59:43.106  1015  3161 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:43.106  1015  3161 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  3161 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  3161 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  3161 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  3161 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  3161 D SettingsProvider: ret = -1
,09-01 10:59:43.106  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:43.106  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  1027 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  1027 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  1027 D SettingsProvider: ret = -1
,09-01 10:59:43.106  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-01 10:59:43.106  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  1216 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  1216 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  1216 D SettingsProvider: ret = -1
09-01 10:59:43.106  1015  1559 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-01 10:59:43.106  1015  1559 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:43.106  1015  1559 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:43.106  1015  1559 D SettingsProvider: selectionArgs: false
09-01 10:59:43.106  1015  1559 D SettingsProvider: selectionArgs: 1002
09-01 10:59:43.106  1015  1559 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:43.106  1015  1559 D SettingsProvider: ret = -1
,09-01 10:59:43.116  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:43.116  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:43.116  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:43.116  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:43.116  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:43.116  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:43.126  1913  6959 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:43.136  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.,
,09-01 10:59:43.136  6943  6943 D TimaKeyStoreProvider: TimaSignature is unavailable
09-01 10:59:43.136  6943  6943 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:43.146  1015  3166 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:43.146  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:43.146  1015  3166 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:43.146  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:43.156  6943  6943 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:43.156  1913  6959 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-01 10:59:43.186  1015  1958 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-01 10:59:43.246   287   287 E SMD     : DCD OFF
,09-01 10:59:43.276   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-01 10:59:44.266   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-01 10:59:44.606  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop,
09-01 10:59:44.606  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:46.246   287   287 E SMD     : DCD OFF
,09-01 10:59:46.626  1015  3166 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-01 10:59:46.626  1015  3166 D BatteryService: level:75, scale:100, status:2, health:2, present:true, voltage: 4043, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
09-01 10:59:46.626  1015  3166 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-01 10:59:46.636  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-01 10:59:46.626  1015  3166 D BatteryService: stay LED for charging
,09-01 10:59:46.636  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-01 10:59:46.626  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-01 10:59:46.626  1015  1015 I MotionRecognitionService: Plugged,
,09-01 10:59:46.626  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,09-01 10:59:46.636  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-01 10:59:46.636  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 75
,09-01 10:59:46.666  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:46.666  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:46.666  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:75 status:2 health:2
,09-01 10:59:47.606  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-01 10:59:47.606  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dca17df added. We now have 6 listener(s)
,09-01 10:59:47.606  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:47.606  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:47.606  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27cc4c2c added. We now have 7 listener(s)
09-01 10:59:47.606  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:47.606  6223  6275 I System.out: IsBluetoothEnabled
09-01 10:59:47.606  6223  6275 D BluetoothAdapter: disable()
09-01 10:59:47.606  1015  3162 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
09-01 10:59:47.616  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-01 10:59:47.616  6223  6275 D BluetoothAdapter: enable()
09-01 10:59:47.616  1015  3154 W ActivityManager: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116),
09-01 10:59:47.616  1015  3154 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-01 10:59:47.616  1015  3154 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-01 10:59:47.616  1015  3154 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:47.626  1015  3154 D SettingsProvider: name = bluetooth_on,
,09-01 10:59:47.636  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-01 10:59:47.636  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-01 10:59:47.636  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-01 10:59:47.636  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-01 10:59:47.656  6928  6928 D BluetoothAdapterState: make
,09-01 10:59:47.666  6928  6928 I bluedroid: init
,09-01 10:59:47.666  6928  6966 I BluetoothAdapterState: Entering OffState
,09-01 10:59:47.666  6928  6928 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 10:59:47.666  6928  6928 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-01 10:59:47.666  6928  6928 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 10:59:47.666  6928  6928 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 10:59:47.666  6928  6928 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-01 10:59:47.666  6928  6928 I bluedroid: get_profile_interface socket
09-01 10:59:47.666  6928  6928 I bluedroid: get_profile_interface map_client
,09-01 10:59:47.666  6928  6969 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-01 10:59:47.676  6928  6928 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-01 10:59:47.676  6928  6969 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-01 10:59:47.676  6928  6928 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:47.676  1015  1476 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-01 10:59:47.676  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.686  6928  6969 E BluetoothServiceJni: populateRssiValuesNative
09-01 10:59:47.686  6928  6969 I bluedroid: getModelRssiValues
09-01 10:59:47.686  6928  6969 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:47.686  6928  6969 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:47.686  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.686  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.686  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.686  6928  6969 D BluetoothAdapterProperties: Name is: A5-1
,09-01 10:59:47.686  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:47.686  6928  6937 I bluedroid: config_hci_snoop_log
,09-01 10:59:47.686  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-01 10:59:47.696  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,09-01 10:59:47.696  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-01 10:59:47.696  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-01 10:59:47.696  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:47.696  6928  6928 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-01 10:59:47.706  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:47.706  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-01 10:59:47.706  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-01 10:59:47.716  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-01 10:59:47.716  6928  6966 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-01 10:59:47.716  6928  6966 D BluetoothAdapterProperties: Setting state to 11
09-01 10:59:47.716  6928  6966 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-01 10:59:47.716  6928  6966 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-01 10:59:47.716  6928  6966 D BluetoothAdapterService: updateAdapterState state is 11
,09-01 10:59:47.716  6928  6966 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:47.716  6928  6966 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-01 10:59:47.716  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:47.716  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,09-01 10:59:47.726  6928  6966 D BluetoothSecureManager: getInstant: null
09-01 10:59:47.726  6928  6966 D BluetoothSecureManager: calling getMethod for getService
09-01 10:59:47.726  6928  6966 D BluetoothSecureManager: calling getService
,09-01 10:59:47.726  6928  6966 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@214ec234
,09-01 10:59:47.726  1015  3140 D BluetoothSecureManagerService: isSecureModeEnabled
09-01 10:59:47.726  1015  3140 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-01 10:59:47.726  6928  6966 D BtConfig.SecureMode: isSecureModeOn:false
09-01 10:59:47.726  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-01 10:59:47.726  1814  1814 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:47.726  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-01 10:59:47.726  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:47.726  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-01 10:59:47.726  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:47.726  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-01 10:59:47.726  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:47.726  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:47.726  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-01 10:59:47.726  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-01 10:59:47.736  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-01 10:59:47.736  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:47.736  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:47.736  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-01 10:59:47.736  1015  3162 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-01 10:59:47.736  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:47.736  1015  1558 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:47.736  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:47.736  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:47.736  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-01 10:59:47.736  6928  6966 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-01 10:59:47.736  6928  6966 D BluetoothBondStateMachine: make
,09-01 10:59:47.746  1015  3162 W ActivityManager: userId = 0, bbcId = -10000,
09-01 10:59:47.746  1015  1476 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-01 10:59:47.746  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-01 10:59:47.746  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-01 10:59:47.746  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-01 10:59:47.746  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-01 10:59:47.746  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-01 10:59:47.746  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-01 10:59:47.746  6928  6971 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 10:59:47.746  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:47.756  1015  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:47.756  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.756  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.756  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.756  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.756  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-01 10:59:47.756  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-01 10:59:47.756  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-01 10:59:47.756  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:47.756  6928  6928 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:47.756  6928  6928 D BtGatt.GattService: Received start request. Starting profile...
09-01 10:59:47.756  6928  6928 D BtGatt.GattService: start()
09-01 10:59:47.756  6928  6928 D BtGatt.GattService: start()
09-01 10:59:47.756  6928  6928 I bluedroid: get_profile_interface gatt
,09-01 10:59:47.756  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:47.756  6928  6928 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:47.756  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.756  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.756  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.756  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.766  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:47.766  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-01 10:59:47.776  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-01 10:59:47.776  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-01 10:59:47.776  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-01 10:59:47.776  6928  6928 D BtGatt.GattService: mStartError = false
09-01 10:59:47.776  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:47.776  6928  6928 D HeadsetService: Received start request. Starting profile...
,09-01 10:59:47.776  6928  6928 D HeadsetService: start()
,09-01 10:59:47.776  6928  6928 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 10:59:47.776  6928  6928 D HeadsetStateMachine: make
,09-01 10:59:47.776  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:47.776  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-01 10:59:47.776  6928  6928 E HeadsetStateMachine: # of Max HF connection is 2
,09-01 10:59:47.776  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.776  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.786  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.786  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-01 10:59:47.786  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-01 10:59:47.786  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-01 10:59:47.786  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:47.786  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.796  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:47.796  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.796  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.796  1015  1557 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-01 10:59:47.796  1015  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.796  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-01 10:59:47.796  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService,
09-01 10:59:47.796  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-01 10:59:47.796  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:47.796  1015  1557 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:47.796  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-01 10:59:47.796  1015  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.796  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:47.796  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:47.796  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.796  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.796  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-01 10:59:47.796  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-01 10:59:47.796  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-01 10:59:47.796  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.796  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-01 10:59:47.806  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.806  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.806  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-01 10:59:47.806  6928  6928 I bluedroid: get_profile_interface handsfree
,09-01 10:59:47.806  1015  1559 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:47.806  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.806  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.806  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.806  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.816  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:47.816  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-01 10:59:47.816  6928  6966 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-01 10:59:47.816  1015  3166 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:47.816  1015  3166 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.826  1015  3166 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:47.826  1015  3166 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:47.826  1015  3166 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.826  6928  6928 I DualScoManager: Instantiating Dual Sco Manager
,09-01 10:59:47.826  6928  6928 I DualScoManager: Set HeadsetServiceHelper
,09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-01 10:59:47.836  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-01 10:59:47.836  1015  3161 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-01 10:59:47.836  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:47.836  6928  6928 D BluetoothAtMessage: createCMTIContentObservers
,09-01 10:59:47.836  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:47.836  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:47.836  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:47.836  1015  3162 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-01 10:59:47.836  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:47.836  1015  3162 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:47.836  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-01 10:59:47.836  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-01 10:59:47.836  6928  6966 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-01 10:59:47.836  6928  6966 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-01 10:59:47.836  6928  6966 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-01 10:59:47.836  1015  3162 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:47.836  1015  3162 D SettingsProvider: selectionArgs: false
09-01 10:59:47.836  1015  3162 D SettingsProvider: selectionArgs: 1002
09-01 10:59:47.836  1015  3162 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:47.836  1015  3162 D SettingsProvider: ret = -1
,09-01 10:59:47.836  6928  6975 D HeadsetStateMachine: Enter Disconnected: -2
,09-01 10:59:47.836  6928  6928 D HeadsetService: mStartError = false
09-01 10:59:47.836  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:47.836  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-01 10:59:47.846  6928  6975 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-01 10:59:47.846  6928  6975 D HeadsetStateMachine: map size, before remove : 0
09-01 10:59:47.846  6928  6975 D HeadsetStateMachine: map size, after remove: 0
,09-01 10:59:47.846  6928  6928 D A2dpService: Received start request. Starting profile...
,09-01 10:59:47.846  6928  6928 D A2dpService: start()
,09-01 10:59:47.846  6928  6928 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-01 10:59:47.846  6928  6928 I bluedroid: get_profile_interface avrcp
,09-01 10:59:47.856  6928  6928 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 10:59:47.866  6928  6928 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-01 10:59:47.876  6928  6979 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-01 10:59:47.876  6928  6928 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 10:59:47.876  6928  6928 D A2dpStateMachine: make
,09-01 10:59:47.876  6928  6928 I bluedroid: get_profile_interface a2dp
,09-01 10:59:47.876  6928  6981 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-01 10:59:47.876  6928  6928 E bt-btif : warning : media task started media_task_refcnt 1 
,09-01 10:59:47.876  6928  6928 D A2dpService: mStartError = false
09-01 10:59:47.876  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:47.886  6928  6980 D A2dpStateMachine: Enter Disconnected: -2
,09-01 10:59:47.886  6928  6928 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 10:59:47.886  6928  6928 D HidService: Received start request. Starting profile...
09-01 10:59:47.886  6928  6928 D HidService: start()
09-01 10:59:47.886  6928  6928 I bluedroid: get_profile_interface hidhost
09-01 10:59:47.886  6928  6928 D HidService: setHidService(): set to: null
09-01 10:59:47.886  6928  6928 D HidService: mStartError = false
09-01 10:59:47.886  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:47.886  6928  6928 D HeadsetStateMachine: Try to query the phonestate on bind
,09-01 10:59:47.886  1430  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:47.886  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-01 10:59:47.886  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:47.886  1430  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,09-01 10:59:47.886  6928  6928 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-01 10:59:47.896  6928  6928 D HealthService: Received start request. Starting profile...
09-01 10:59:47.896  6928  6928 D HealthService: start()
,09-01 10:59:47.896  6928  6928 I bluedroid: get_profile_interface health
,09-01 10:59:47.896  6928  6928 D HealthService: mStartError = false
09-01 10:59:47.896  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:47.896  6928  6928 D HeadsetStateMachine: Proxy object connected
,09-01 10:59:47.896  6928  6928 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 10:59:47.896  6928  6928 D PanService: Received start request. Starting profile...
09-01 10:59:47.896  6928  6928 D PanService: start()
09-01 10:59:47.896  6928  6928 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 10:59:47.896  6928  6928 I bluedroid: get_profile_interface pan
,09-01 10:59:47.896  6928  6928 D PanService: mStartError = false
09-01 10:59:47.896  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:47.896  6928  6928 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-01 10:59:47.896  6928  6928 D HeadsetPhoneState: sendDeviceDataStateChanged
09-01 10:59:47.896  6928  6975 D HeadsetStateMachine: Disconnected process message: 11
09-01 10:59:47.896  6928  6928 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-01 10:59:47.896  6928  6975 D HeadsetStateMachine: Disconnected process message: 18
,09-01 10:59:47.896  6928  6928 D BluetoothMapService: Received start request. Starting profile...
09-01 10:59:47.896  6928  6928 D BluetoothMapService: start()
,09-01 10:59:47.906  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:47.906  6928  6979 D BluetoothMediaBrowser: no now playing list
09-01 10:59:47.906  6928  6979 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-01 10:59:47.906  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:47.906  6928  6928 D BluetoothMapService: mStartError = false
09-01 10:59:47.906  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:47.906  6928  6928 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-01 10:59:47.906  6928  6928 D SapService: Received start request. Starting profile...
09-01 10:59:47.906  6928  6928 D SapService: start()
09-01 10:59:47.906  6928  6928 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-01 10:59:47.906  6928  6928 I bluedroid: get_profile_interface sap
09-01 10:59:47.906  6928  6928 D SapService: mStartError = false
09-01 10:59:47.906  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:47.906  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-01 10:59:47.906  6928  6928 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-01 10:59:47.906  6928  6928 D BluetoothA2dp: Proxy object connected
09-01 10:59:47.906  6928  6928 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-01 10:59:47.906  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-01 10:59:47.906  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-01 10:59:47.906  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-01 10:59:47.906  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-01 10:59:47.906  6928  6975 D HeadsetStateMachine: Disconnected process message: 10
09-01 10:59:47.906  6928  6975 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-01 10:59:47.906  6928  6975 D HeadsetStateMachine: Disconnected process message: 11
,09-01 10:59:47.936  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-01 10:59:47.936  6928  6928 E BluetoothAdapterService(213729039): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-01 10:59:47.936  6928  6966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-01 10:59:47.936  6928  6966 I bluedroid: enable
,09-01 10:59:47.946  6928  6986 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
,09-01 10:59:47.946  6928  6966 I bt_hci_bdroid: init
,09-01 10:59:47.946  6928  6966 I bt_vendor: bt-vendor : init
,09-01 10:59:47.946  6928  6966 I bt_vendor: bt-vendor : get_bt_soc_type
09-01 10:59:47.946  6928  6966 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-01 10:59:47.946  6928  6966 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,09-01 10:59:47.946  6928  6966 D bt_userial_mct: userial_init
,09-01 10:59:47.946  6928  6966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-01 10:59:47.946  6928  6966 I bt_vendor: Starting hciattach daemon
09-01 10:59:47.946  6928  6966 I bt_vendor: try to set false
,09-01 10:59:47.946  6928  6966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-01 10:59:47.946  6928  6966 I bt_vendor: Starting hciattach daemon
09-01 10:59:47.946  6928  6966 I bt_vendor: try to set true
,09-01 10:59:47.966  6990  6990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-01 10:59:48.016  6996  6996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-01 10:59:48.026  6997  6997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:48.046  6999  6999 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-01 10:59:48.046  7000  7000 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-01 10:59:48.056  7001  7001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-01 10:59:48.066  7002  7002 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-01 10:59:48.256  7005  7005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,09-01 10:59:48.256  1015  2703 D SSRM:n  : SIOP:: AP = 320,
,09-01 10:59:48.266  7006  7006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-01 10:59:48.306  6928  6966 I bt_vendor: bluetooth satus is on
,09-01 10:59:48.306  6928  6988 D bt_userial_mct: userial_open(port:0)
09-01 10:59:48.306  6928  6988 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-01 10:59:48.306  6928  6988 I bt_vendor: Done intiailizing UART,
,09-01 10:59:48.306  6928  6988 I bt_vendor: Done intiailizing UART,
09-01 10:59:48.306  6928  6988 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
09-01 10:59:48.306  6928  6988 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-01 10:59:48.316  6928  7008 D bt_userial_mct: Entering userial_read_thread(),
,09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 10:59:48.316  6928  6986 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_SAP
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_BTIF
09-01 10:59:48.326  6928  6986 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-01 10:59:48.416  6928  6986 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-01 10:59:48.426  6928  6986 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40706e9 
,09-01 10:59:48.426  6928  6986 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40706e9 
,09-01 10:59:48.446  6928  6969 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-01 10:59:48.446  6928  6969 E bt-btif : Calling BTA_HhEnable
,09-01 10:59:48.456  6928  6969 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-01 10:59:48.456  6928  6969 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-01 10:59:48.456  6928  6969 E BluetoothServiceJni: populateRssiValuesNative
09-01 10:59:48.456  6928  6969 I bluedroid: getModelRssiValues
09-01 10:59:48.456  6928  6969 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-01 10:59:48.456  6928  6969 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-01 10:59:48.456  6928  6969 D BluetoothAdapterProperties: Name is: A5-1
,09-01 10:59:48.456  1015  1015 D SettingsProvider: name = bluetooth_name
,09-01 10:59:48.456  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.466  6928  6969 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-01 10:59:48.466  6928  6969 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:48.466  6928  6969 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:48.466  6928  6969 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-01 10:59:48.466  6928  6969 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-01 10:59:48.466  6928  6969 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-01 10:59:48.466  6928  6969 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-01 10:59:48.466  6928  6969 E bt-btif : btif_sock_init: !vhci_init
,09-01 10:59:48.466  6928  7008 E bt_mct  : hci lib postload completed
,09-01 10:59:48.466  6928  6969 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-01 10:59:48.476  6928  6969 D IOP_DB_BT: db_open: db_open : handle 3026071568l, read 13894 bytes onto local cache
,09-01 10:59:48.476  6928  6969 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-01 10:59:48.476  6928  6969 D IOP_DB_BT: db_query: result 1
,09-01 10:59:48.476  6928  6969 I         : iop_db_open: iop_db_open status 0
,09-01 10:59:48.476  6928  6969 D bte_conf: Device ID record 1 : primary
,09-01 10:59:48.476  6928  6969 D bte_conf:   vendorId            = 0075
09-01 10:59:48.476  6928  6969 D bte_conf:   vendorIdSource      = 0001
,09-01 10:59:48.476  6928  6969 D bte_conf:   product             = 0100
09-01 10:59:48.476  6928  6969 D bte_conf:   version             = 0200
,09-01 10:59:48.476  6928  6969 D bte_conf:   clientExecutableURL = 
09-01 10:59:48.476  6928  6969 D bte_conf:   serviceDescription  = 
,09-01 10:59:48.476  6928  6969 D bte_conf:   documentationURL    = 
09-01 10:59:48.476  6928  6969 D bte_conf: bte_load_did_conf no section named DID2.
09-01 10:59:48.476  6928  6969 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-01 10:59:48.476  6928  6966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-01 10:59:48.476  6928  6966 D BluetoothAdapterProperties: ScanMode =  20,
09-01 10:59:48.476  6928  6966 D BluetoothAdapterProperties: State =  11
09-01 10:59:48.476  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-01 10:59:48.486  6928  6966 D BluetoothAdapterProperties: Setting state to 12
09-01 10:59:48.486  6928  6966 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:48.486  6928  6969 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-01 10:59:48.486  6928  6969 D BluetoothAdapterProperties: Scan Mode:21
09-01 10:59:48.486  6928  6969 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:48.486  1015  3161 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-01 10:59:48.486  1015  3161 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-01 10:59:48.486  1015  3161 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-01 10:59:48.486  1015  3161 D SettingsProvider: selectionArgs: false
09-01 10:59:48.486  1015  3161 D SettingsProvider: selectionArgs: 1002
,09-01 10:59:48.486  1015  3161 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-01 10:59:48.486  1015  3161 D SettingsProvider: ret = -1
09-01 10:59:48.486  6928  6966 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-01 10:59:48.486  6928  6966 D BluetoothAdapterService: updateAdapterState state is 12
,09-01 10:59:48.486  1015  3140 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:48.496  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.496  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.496  1015  3140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:48.496  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.506  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:48.506  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:48.506  6928  6966 D BluetoothAdapterService: Autoconnection is available 
09-01 10:59:48.506  6928  6966 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-01 10:59:48.506  6928  6966 D BluetoothAdapterService: starting service from this receiver
,09-01 10:59:48.506  1322  1333 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.506  1322  1333 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:48.506  6223  6235 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.506  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:48.506  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-01 10:59:48.506  6223  6235 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.506  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.506  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.506  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.506  6928  6966 I BluetoothAdapterState: Entering On State from state = 11
,09-01 10:59:48.506  6928  6970 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:48.506  1322  6415 D Bluetoothsap: onBluetoothStateChange: up=true
09-01 10:59:48.506  1322  6415 D Bluetoothsap: Binding service...
,09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:48.516  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:48.516  1322  6415 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-01 10:59:48.526  6928  6928 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-01 10:59:48.526  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:48.636  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:48.636  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:48.636  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:48.646  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@73a06f5 added. We now have 8 listener(s)
09-01 10:59:48.646  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:48.646  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:48.646  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:48.646  1015  1028 D SecContentProvider2: mCursor = null
,09-01 10:59:48.646  1015  1028 D WifiService: setWifiEnabled: false pid=6223, uid=10155
,09-01 10:59:48.646  1015  1028 D SettingsProvider: name = wifi_on
,09-01 10:59:48.656  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.656  1015  3162 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-01 10:59:48.656  1015  3162 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-01 10:59:48.656  1015  3162 D SecContentProvider2: mCursor = null
,09-01 10:59:48.656  1015  3162 D WifiService: setWifiEnabled: true pid=6223, uid=10155
,09-01 10:59:48.656  1015  3162 W ActivityManager: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-01 10:59:48.656  1015  3162 W WifiService: Failed getting userId using ActivityManagerNative
09-01 10:59:48.656  1015  3162 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6223, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-01 10:59:48.656  1015  3162 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-01 10:59:48.656  1015  3162 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-01 10:59:48.656  1015  3162 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-01 10:59:48.656  1015  3162 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-01 10:59:48.656  1015  3162 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:48.656  1015  3162 D SettingsProvider: name = wifi_on
,09-01 10:59:48.666  1015  1130 E WifiHW  : ##################### set firmware type 0 #####################
,09-01 10:59:48.686  1015  1045 I art     : Explicit concurrent mark sweep GC freed 28583(1644KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.735ms total 167.036ms
09-01 10:59:48.686  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-01 10:59:48.686  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.686  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.686  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.686  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.686  1322  6415 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-01 10:59:48.686  1322  1332 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 10:59:48.686  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-01 10:59:48.686  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.686  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.686  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.686  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.686  1015  1045 D BluetoothPan: Binding service...
09-01 10:59:48.686  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-01 10:59:48.686  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.686  6928  6928 I BluetoothPbapService: Handler(): got msg=1
,09-01 10:59:48.686  2845  2858 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:48.696  1015  1216 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
09-01 10:59:48.696  2845  2858 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:48.696  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:48.696  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.696  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.696  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.696  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.696  2845  2845 D BluetoothA2dp: Proxy object connected
,09-01 10:59:48.696  1430  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.696  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:48.696  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.696  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.696  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.696  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.696  6928  7016 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-01 10:59:48.706  1430  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.706  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,09-01 10:59:48.706  1322  1322 D Bluetoothsap: BluetoothSAP Proxy object connected
09-01 10:59:48.706  1430  6412 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.706  1322  1322 D SapProfile: Bluetooth service connected
09-01 10:59:48.706  1322  1322 D Bluetoothsap: getConnectedDevices()
,09-01 10:59:48.706  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:48.706  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.706  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.706  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.706  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.706  1430  6412 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.706  1456  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:48.706  1456  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.706  6928  7016 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:48.706  6928  7016 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:48.706  1322  6415 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-01 10:59:48.706  1322  1322 D BluetoothMap: Proxy object connected
,09-01 10:59:48.706  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:48.706  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.706  1322  1322 D MapProfile: Bluetooth service connected
09-01 10:59:48.706  1322  1322 D BluetoothMap: getConnectedDevices(),
09-01 10:59:48.706  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.706  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.706  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-01 10:59:48.706  1322  6415 E BluetoothHeadset: BluetoothHeadset service is binded,
09-01 10:59:48.716  1322  1332 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 10:59:48.716  6928  7016 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-01 10:59:48.716  6928  7016 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:48.716  6928  7016 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:48.716  6928  7016 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2067eb18
09-01 10:59:48.716  6928  7016 D BluetoothSocket: channel: 19
,09-01 10:59:48.716  6928  7016 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-01 10:59:48.716  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-01 10:59:48.716  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.716  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-01 10:59:48.716  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.716  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.716  1322  1322 D HeadsetProfile: Bluetooth service connected
09-01 10:59:48.716  1322  6415 D BluetoothPbap: onBluetoothStateChange: up=true
,09-01 10:59:48.716  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-01 10:59:48.716  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.716  1322  1322 D BluetoothInputDevice: Proxy object connected
09-01 10:59:48.716  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.716  1322  1322 D HidProfile: Bluetooth service connected
09-01 10:59:48.716  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.716  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.716  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:48.716  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.726  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:48.726  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.726  1015  1015 D BluetoothA2dp: Proxy object connected
,09-01 10:59:48.726  2845  2863 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.726  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-01 10:59:48.726  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.726  1322  1322 D BluetoothPbap: Proxy object connected
09-01 10:59:48.726  1322  1322 D PbapServerProfile: Bluetooth service connected
,09-01 10:59:48.726  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.726  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.726  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.726  2845  2863 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.726  1456  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.726  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:48.736  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.736  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.736  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.736  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.736  1456  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.736  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.736  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:48.736  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.736  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.736  1175  3067 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.736  1175  3067 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.736  1438  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.736  1438  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:48.736  1322  1333 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:48.736  1322  1333 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.746  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-01 10:59:48.746  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.746  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:48.746  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.746  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.746  6928  7011 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:48.746  6928  7011 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:48.746  1322  1322 D BluetoothA2dp: Proxy object connected
09-01 10:59:48.746  1430  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.746  1430  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-01 10:59:48.746  1322  1322 D A2dpProfile: Bluetooth service connected
,09-01 10:59:48.746  1913  1924 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.746  1913  1924 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.746  1322  1332 D BluetoothPan: Binding service...
,09-01 10:59:48.746  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-01 10:59:48.746  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.746  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.746  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.746  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.746  1322  1322 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:48.746  1322  1322 D PanProfile: Bluetooth service connected
,09-01 10:59:48.746  6383  6396 D BluetoothAdapter: onBluetoothStateChange: up=true
09-01 10:59:48.746  6383  6396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.756  2845  2858 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-01 10:59:48.756  2845  2858 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-01 10:59:48.756  1430  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-01 10:59:48.756  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-01 10:59:48.756  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-01 10:59:48.756  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.756  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.756  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.756  1430  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-01 10:59:48.756  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-01 10:59:48.756  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-01 10:59:48.756  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:48.756  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
09-01 10:59:48.756  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-01 10:59:48.766  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@355f6a94, true
,09-01 10:59:48.766  1430  1430 D BluetoothHeadset: registerMessageListener
09-01 10:59:48.766  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-01 10:59:48.766  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-01 10:59:48.766  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:48.766  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:48.766  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:48.766  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-01 10:59:48.776  1175  1735 D BluetoothTile:  handleUpdatestate:false name:null
,09-01 10:59:48.776  1015  1500 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:48.776  1015  3162 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-01 10:59:48.776  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-01 10:59:48.786  1814  1814 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-01 10:59:48.786  1322  1322 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:48.786  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:48.786  1015  3140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:48.786  6928  6970 D HeadsetService: registerMessageListener
,09-01 10:59:48.786  1015  3140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.786  6928  6970 D HeadsetService: registerMessageListener
,09-01 10:59:48.786  6928  6975 D HeadsetStateMachine: Disconnected process message: 70
,09-01 10:59:48.796  6928  6975 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@22709971
09-01 10:59:48.796  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-01 10:59:48.796  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-01 10:59:48.796  1015  3140 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.796  1015  3140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:48.796  1015  3140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:48.796  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-01 10:59:48.806  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-01 10:59:48.806  6928  7017 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-01 10:59:48.806  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-01 10:59:48.806  1322  1322 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-01 10:59:48.806  1322  1322 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-01 10:59:48.806  1322  1322 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-01 10:59:48.806  1322  1322 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-01 10:59:48.806  6928  6975 D HeadsetStateMachine: Disconnected process message: 9
,09-01 10:59:48.806  6928  6975 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-01 10:59:48.816  6928  7017 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:48.816  6928  7017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:48.816  6928  7017 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-01 10:59:48.816  6928  7017 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:48.816  6928  7017 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:48.816  6928  7017 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1717f356
,09-01 10:59:48.816  6928  7017 D BluetoothSocket: channel: 5
09-01 10:59:48.816   282   685 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-01 10:59:48.816   282   685 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-01 10:59:48.816   282   685 V voice   : voice_set_parameters: exit with code(-2)
09-01 10:59:48.816   282   685 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-01 10:59:48.816   282   685 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-01 10:59:48.816   282   685 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-01 10:59:48.816   282   685 V audio_hw_primary: adev_set_parameters: exit
,09-01 10:59:48.816  6928  6975 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-01 10:59:48.816  1322  1322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:48.816  1015  3162 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-01 10:59:48.816  1015  3162 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.816  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.816  1015  3162 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:48.816  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-01 10:59:48.836  1322  1322 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:48.836  1322  1322 D BluetoothNotiBroadcastReceiver: onReceive
,09-01 10:59:48.836  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:48.836  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-01 10:59:48.846  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
,09-01 10:59:48.846  6928  6928 D BtConfig.SecureMode: isSecureModeOn:false
,09-01 10:59:48.846  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-01 10:59:48.846  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.846  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.856  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:48.856  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-01 10:59:48.866  1913  1913 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:48.866  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-01 10:59:48.866  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-01 10:59:48.876  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.876  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:48.876  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:48.886  1015  3161 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-01 10:59:48.886  1913  7024 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-01 10:59:48.886  1913  1913 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-01 10:59:48.886  1015  3162 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:48.896  1015  3162 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.896  1015  3162 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:48.896  1015  3162 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:48.906  6928  7027 D BluetoothSocket: bindListen(): myUserId = 0
09-01 10:59:48.906  6928  7027 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:48.906  6928  7027 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-01 10:59:48.906  6928  7027 D BluetoothSocket: bindListen(), new LocalSocket 
09-01 10:59:48.906  6928  7027 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-01 10:59:48.906  6928  7027 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28b7eee2
,09-01 10:59:48.906  6928  7027 D BluetoothSocket: channel: 12
09-01 10:59:48.906  6928  7027 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:48.906  1015  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-01 10:59:48.916  1015  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:48.916  1015  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-01 10:59:48.916  1015  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-01 10:59:48.926  1913  7024 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-01 10:59:49.056  1015  1043 D Tethering: interfaceAdded wlan0
,09-01 10:59:49.056  1015  1133 E Tethering: No numeric data
,09-01 10:59:49.056  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 10:59:49.066  1015  1133 D Tethering: clearTetheredNotification()
,09-01 10:59:49.066  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:49.066  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.066  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-01 10:59:49.066  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:49.066  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-01 10:59:49.076  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:49.076  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:49.076  1015  1123 V NetworkStats: performPollLocked() took 10ms
09-01 10:59:49.076  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.076  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:49.076  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.076  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:49.076  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:49.076  1015  1133 D Tethering: InitialState.processMessage what=4
,09-01 10:59:49.076  1015  1043 D Tethering: interfaceAdded p2p0
,09-01 10:59:49.086  1015  1133 E Tethering: No numeric data
,09-01 10:59:49.086  1015  1133 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-01 10:59:49.086  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
09-01 10:59:49.086  1015  1133 D Tethering: clearTetheredNotification()
,09-01 10:59:49.086  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-01 10:59:49.086  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:49.086  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
09-01 10:59:49.086  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-01 10:59:49.086  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:49.086  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:49.096   276   988 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-01 10:59:49.096   276   988 D SoftapController: Softap fwReload - Ok,
09-01 10:59:49.096  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:49.096  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:49.096  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-01 10:59:49.096  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.096  1015  1123 V NetworkStats: performPollLocked() took 11ms
,09-01 10:59:49.096   276   988 D CommandListener: Setting iface cfg
09-01 10:59:49.096   276   988 D CommandListener: Trying to bring down wlan0
09-01 10:59:49.106  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.106  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:49.106   276   988 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:49.106  1015  1130 E WifiHW  : supplicant_name : p2p_supplicant
,09-01 10:59:49.116  1015  1130 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-01 10:59:49.116  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:49.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-01 10:59:49.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:49.116  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:49.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:49.116  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-01 10:59:49.126  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:49.126  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:49.126  1175  1175 D HotspotTile: onReceive : 2, 0
,09-01 10:59:49.126  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:49.136  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:49.136  1015  3154 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:49.136  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:49.136  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:49.136  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:49.136  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:49.136  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:49.136  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:49.136  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
09-01 10:59:49.136  3623  3623 I Hs20UtilService: Starting #19
09-01 10:59:49.136  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:49.146  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:49.156  7035  7035 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-01 10:59:49.156  7035  7035 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-01 10:59:49.166  7035  7035 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-01 10:59:49.176  7035  7035 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
09-01 10:59:49.176   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7035
09-01 10:59:49.176   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-01 10:59:49.176  7035  7035 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-01 10:59:49.176  7035  7035 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:49.176  7035  7035 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-01 10:59:49.176  7035  7035 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-01 10:59:49.176   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7035
09-01 10:59:49.176   342   342 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-01 10:59:49.246   287   287 E SMD     : DCD OFF
,09-01 10:59:49.326   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,09-01 10:59:49.336  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-01 10:59:49.406  7035  7035 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 10:59:49.406  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-01 10:59:49.416  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,09-01 10:59:49.416   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7035
09-01 10:59:49.416   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-01 10:59:49.416  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,09-01 10:59:49.416  7035  7035 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:49.416  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:49.416  7035  7035 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-01 10:59:49.416  7035  7035 E wpa_supplicant: SIM READ ERROR
09-01 10:59:49.416  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:49.416  7035  7035 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:49.416  7035  7035 E wpa_supplicant: SIM READ ERROR
,09-01 10:59:49.416  7035  7035 I wpa_supplicant: Blacklist: Clear (all) 
09-01 10:59:49.416  7035  7035 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:49.416  7035  7035 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-01 10:59:49.416  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-01 10:59:49.416  7035  7035 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-01 10:59:49.416  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:49.416  7035  7035 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 10:59:49.416  7035  7035 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-01 10:59:49.416  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:49.416  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-01 10:59:49.416  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,09-01 10:59:49.476  7035  7035 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-01 10:59:49.806  7035  7035 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-01 10:59:49.806  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-01 10:59:49.816  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-01 10:59:49.816   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7035
09-01 10:59:49.816   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-01 10:59:49.826  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
09-01 10:59:49.826  7035  7035 I wpa_supplicant: ssSupport state is = 1
,09-01 10:59:49.826  7035  7035 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-01 10:59:49.826  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-01 10:59:49.836  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-01 10:59:49.836   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7035
09-01 10:59:49.836   342   342 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-01 10:59:49.836  7035  7035 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
09-01 10:59:49.836  7035  7035 I wpa_supplicant: ssSupport state is = 1
09-01 10:59:49.836  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:49.836  7035  7035 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-01 10:59:49.836  7035  7035 E wpa_supplicant: SIM READ ERROR
09-01 10:59:49.836  7035  7035 I wpa_supplicant: wpa_default_ap_write_once
09-01 10:59:49.836  7035  7035 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-01 10:59:49.836  7035  7035 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-01 10:59:49.836  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:49.836  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:49.846  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:49.846  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
09-01 10:59:49.846  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,09-01 10:59:49.846  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:49.926  7035  7035 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-01 10:59:49.926  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-01 10:59:50.046  7035  7035 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-01 10:59:50.046  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-01 10:59:50.046  7035  7035 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:50.056  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-01 10:59:50.056  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-01 10:59:50.056  7035  7035 I wpa_supplicant: HOTSPOT20_ENABLE called
09-01 10:59:50.056  7035  7035 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-01 10:59:50.056  7035  7035 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-01 10:59:50.056  7035  7035 E wpa_supplicant: SIM READ ERROR
09-01 10:59:50.056  7035  7035 I wpa_supplicant: Blacklist: Clear (all) 
,09-01 10:59:50.066  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,09-01 10:59:50.066  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
09-01 10:59:50.066  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-01 10:59:50.076  7035  7035 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-01 10:59:50.086  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
09-01 10:59:50.086  7035  7035 I wpa_supplicant: Skip scan - bUseNetwork false
,09-01 10:59:50.086  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-01 10:59:50.086  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-01 10:59:50.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:50.086  1015  1130 D WifiConfigStore: Loading config and enabling all networks 
,09-01 10:59:50.086  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:50.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:50.096  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:50.096  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-01 10:59:50.096  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-01 10:59:50.096  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:50.096  1175  1175 D HotspotTile: onReceive : 3, 0
,09-01 10:59:50.096  1175  1735 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-01 10:59:50.096  1322  1322 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:50.106  6223  6223 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:50.106  6223  6223 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:50.106  1015  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:50.106  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:50.106  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:50.106  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:50.106  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:50.106  1015  1130 E WifiConfigStore: Not a HS20
,09-01 10:59:50.116  1015  1130 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-01 10:59:50.116  3623  3623 I Hs20UtilService: Starting #20
,09-01 10:59:50.116  3623  3665 I Hs20UtilService: Message received 5011
,09-01 10:59:50.116  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-01 10:59:50.116  6494  6494 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-01 10:59:50.116  6494  6494 D SecurityLogAgent: StateMachine : Current State = 1
,09-01 10:59:50.116  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [65]
09-01 10:59:50.116  6494  6494 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-01 10:59:50.116  1015  1130 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-01 10:59:50.116  7035  7035 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-01 10:59:50.116  7035  7035 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-01 10:59:50.116  7035  7035 I wpa_supplicant: reset timer : RESET_TIMER 0
09-01 10:59:50.116  7035  7035 I wpa_supplicant: P2P: Current p2p state = IDLE
09-01 10:59:50.116  7035  7035 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-01 10:59:50.116  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-01 10:59:50.116  7035  7035 I wpa_supplicant: First Scan Start
09-01 10:59:50.116  7035  7035 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-01 10:59:50.126  1015  1130 D WifiNative-wlan0: Setting external_sim to 1
,09-01 10:59:50.126  1015  1130 D WifiStateMachine: Setting OUI to DA-A1-19
09-01 10:59:50.126  1015  1130 I WifiNative-HAL: startHal
09-01 10:59:50.126  1015  1130 E wifi    : getStaticLongField sWifiHalHandle 0x9c76e88c
09-01 10:59:50.126  1015  1130 I WifiNative-HAL: Could not start hal
,09-01 10:59:50.126  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:50.126  1015  1130 E WifiNative-wlan0: do suspend true
,09-01 10:59:50.136  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-01 10:59:50.136   276   988 D CommandListener: Setting iface cfg,
09-01 10:59:50.136   276   988 D CommandListener: Trying to bring up p2p0
09-01 10:59:50.136  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 10:59:50.136  1015  1130 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-01 10:59:50.136  1015  1125 D WifiP2pService: P2pEnablingState
09-01 10:59:50.136  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
09-01 10:59:50.136  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,09-01 10:59:50.136  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:50.136  1015  1125 D WifiP2pService: P2p socket connection successful
,09-01 10:59:50.136  1015  1149 I WifiNative-HAL: startHal
09-01 10:59:50.136  1015  1125 D WifiP2pService: P2pEnabledState
09-01 10:59:50.136  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9d9209bc
,09-01 10:59:50.136  1015  1149 I WifiNative-HAL: Could not start hal
09-01 10:59:50.136  1015  1149 E WifiScanningService: could not start HAL
09-01 10:59:50.136  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-01 10:59:50.136  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-01 10:59:50.136  1015  1130 E WifiNative-wlan0: invaild command id : 215
09-01 10:59:50.136  1015  1130 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-01 10:59:50.136  1015  1130 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-01 10:59:50.136  1015  1130 E WifiNative-wlan0: invaild command id : 215
,09-01 10:59:50.146  7035  7035 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:50.146  1015  1015 D RttService: SCAN_AVAILABLE : 3
09-01 10:59:50.146  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-01 10:59:50.146  7035  7035 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-01 10:59:50.146  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:50.146  1015  1132 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:50.146  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-01 10:59:50.146  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-01 10:59:50.146  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:50.146  1015  1046 D WifiDisplayController: disconnect
09-01 10:59:50.146  1015  1046 D WifiDisplayController: updateConnection
09-01 10:59:50.146  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-01 10:59:50.146  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:50.146  7035  7035 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-01 10:59:50.156  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-01 10:59:50.156  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
09-01 10:59:50.156  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-01 10:59:50.156  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-01 10:59:50.156  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:50.156  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:50.156  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-01 10:59:50.156  1015  1558 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-01 10:59:50.156  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-01 10:59:50.156  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
09-01 10:59:50.156  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-01 10:59:50.156  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:50.156  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-01 10:59:50.156  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:50.156  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:50.156  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:50.156  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-01 10:59:50.156  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  secondary type: null
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  wps: 0
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  grpcapab: 0
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  devcapab: 0
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  status: 3
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  wfdInfo: null
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  groupownerAddress: null
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  GOdeviceName: null
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  interfaceAddress: 
09-01 10:59:50.156  1015  1046 D WifiDisplayController:  SConnectInfo : null
,09-01 10:59:50.156  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:50.156  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-01 10:59:50.156  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:50.166  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:50.166  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:50.166  6463  6463 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-01 10:59:50.166  6463  6463 D FileShare-Client: Outbound.stopDelayTimer - 
,09-01 10:59:50.176  6478  6478 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-01 10:59:50.186  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-01 10:59:50.186  1015  1125 D WifiP2pService: InactiveState,
09-01 10:59:50.186  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
09-01 10:59:50.186  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 },
09-01 10:59:50.186  7035  7035 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-01 10:59:50.186  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
09-01 10:59:50.186  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:50.676  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:50.686  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:50.686  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 10:59:50.686  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 10:59:50.696  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2c17d59 Bundle[{}]
,09-01 10:59:50.696  6223  6275 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 10:59:50.696  6223  6275 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-01 10:59:50.696  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-01 10:59:50.696  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-01 10:59:50.696  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-01 10:59:50.696  6223  6275 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 10:59:50.706  6223  6275 I System.out: Running OutgoingSocketThread
,09-01 10:59:50.706  6223  7043 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1172)
,09-01 10:59:50.716  6223  7043 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35605
,09-01 10:59:50.716  6223  7043 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 10:59:51.346  7035  7035 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
09-01 10:59:51.346  7035  7035 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-01 10:59:51.346  7035  7035 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-01 10:59:51.346  7035  7035 I wpa_supplicant: Trying to associate with  'G700',
09-01 10:59:51.346  7035  7035 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-01 10:59:51.346  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-01 10:59:51.346  1015  7041 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-01 10:59:51.366  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:51.366  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:51.466  7035  7035 E wpa_supplicant: Cmd 35605 not handled
,09-01 10:59:51.476  7035  7035 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-01 10:59:51.476  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:51.476  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
,09-01 10:59:51.476  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,09-01 10:59:51.476  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-01 10:59:51.476  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:51.476  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:51.476  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
09-01 10:59:51.476  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-01 10:59:51.476  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
09-01 10:59:51.476  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 10:59:51.476  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:51.476  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
09-01 10:59:51.476  1015  1133 E Tethering: No numeric data
09-01 10:59:51.486  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-01 10:59:51.486  7035  7035 I wpa_supplicant: Associated with F4.99.3E
09-01 10:59:51.486  7035  7035 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-01 10:59:51.486  7035  7035 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-01 10:59:51.486  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-01 10:59:51.486  1015  1133 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-01 10:59:51.486  1015  1133 D Tethering: clearTetheredNotification()
,09-01 10:59:51.486  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,09-01 10:59:51.486  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:51.496  7035  7035 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-01 10:59:51.496  7035  7035 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-01 10:59:51.496  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-01 10:59:51.496  1175  1175 D HotspotTile: updateTetherState():false, false
,09-01 10:59:51.496  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:51.496  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:51.496  7035  7035 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-01 10:59:51.496  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-01 10:59:51.496  7035  7035 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP],
09-01 10:59:51.496  7035  7035 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-01 10:59:51.496  1015  1123 V NetworkStats: performPollLocked() took 10ms
09-01 10:59:51.496  7035  7035 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-01 10:59:51.506  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-01 10:59:51.496  7035  7035 I wpa_supplicant: Blacklist: Clear (temp) 
09-01 10:59:51.496  7035  7035 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-01 10:59:51.496  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:51.496  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:51.496  1015  1130 D SecContentProvider2: mCursor = null
09-01 10:59:51.506  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
09-01 10:59:51.506  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
09-01 10:59:51.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:51.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:51.506  1015  1130 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-01 10:59:51.516  1015  1130 E WifiConfigStore: setLastSelectedConfiguration -1
,09-01 10:59:51.516  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:51.516  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:51.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:51.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:51.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:51.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:51.516  1015  1130 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-01 10:59:51.516  1015  1132 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-01 10:59:51.516  1015  1132 E ConnectivityService: updateNetworkInfo()
,09-01 10:59:51.516  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-01 10:59:51.516  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:51.526  1015  3161 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-01 10:59:51.526  1015  3161 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-01 10:59:51.526  1015  3161 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:51.526  1015  3161 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:51.526  1015  3161 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-01 10:59:51.536  3623  3623 I Hs20UtilService: Starting #21
,09-01 10:59:51.536  1015  1130 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:51.536  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:51.536  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-01 10:59:51.536  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-01 10:59:51.536  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:51.536  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-01 10:59:51.536  1322  1322 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-01 10:59:51.536  1322  3060 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-01 10:59:51.536  3623  3665 I Hs20UtilService: Message received 5007
,09-01 10:59:51.546   276   988 D CommandListener: Setting iface cfg
,09-01 10:59:51.546  1015  1130 E WifiStateMachine: Start Dhcp Watchdog 3
,09-01 10:59:51.546  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:51.546  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:51.556  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-01 10:59:51.556  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:51.556  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:51.556  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-01 10:59:51.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:51.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:51.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:51.556  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:51.566  1015  1130 E WifiNative-wlan0: do suspend false
,09-01 10:59:51.566  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,09-01 10:59:51.566  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 10:59:51.566  1015  1130 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-01 10:59:51.566  1015  1130 D SecContentProvider2: mCursor = null
,09-01 10:59:51.706  6223  6275 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1173),
09-01 10:59:51.706  6223  6275 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1173)
,09-01 10:59:51.706  6223  6275 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1178)
,09-01 10:59:51.716  6223  6275 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-01 10:59:51.716  6223  6275 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
,09-01 10:59:51.716  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:51.716  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1851cc8a added. We now have 2 listener(s)
,09-01 10:59:51.716  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:51.726  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:51.726  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:51.726  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:51.726  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e252fb added. We now have 9 listener(s)
09-01 10:59:51.726  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:51.726  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:51.726  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:51.736  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:51.736  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:51.736  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:51.736  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:51.736  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a711d71 added. We now have 3 listener(s)
,09-01 10:59:51.736  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.736  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f882756 added. We now have 10 listener(s)
,09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:51.746  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:51.746  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:51.746  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:51.746  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1851cc8a removed from the list
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e252fb removed from the list
09-01 10:59:51.746  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:51.746  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.746  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e252fb not in the list
09-01 10:59:51.746  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f882756 removed from the list
09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:51.746  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.746  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:51.746  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:51.746  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a711d71 removed from the list
,09-01 10:59:51.756  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:51.756  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7923d7 added. We now have 2 listener(s)
,09-01 10:59:51.756  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:51.756  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:51.756  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:51.756  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:51.756  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9f4c4 added. We now have 9 listener(s)
09-01 10:59:51.756  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:51.756  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:51.756  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:51.766  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:51.766  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:51.766  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:51.766  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.766  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.766  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:51.766  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f762e2 added. We now have 3 listener(s)
,09-01 10:59:51.776  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-01 10:59:51.776  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:51.776  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:51.776  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:51.776  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b422673 added. We now have 10 listener(s),
09-01 10:59:51.776  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:51.776  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:51.776  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:51.776  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:51.776  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:51.776  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:51.786  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:51.786  7048  7048 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 10:59:51.786  7048  7048 I dhcpcd  : version 5.5.6 starting
,09-01 10:59:51.786  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-01 10:59:51.786  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:51.796  7048  7048 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-01 10:59:51.806  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:51.806  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:51.806  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:51.806  6928  6936 D BtGatt.GattService: registerClient() - UUID=89d52111-55e4-4c54-8688-8202ca6ebaff
,09-01 10:59:51.846  7048  7048 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-01 10:59:51.846  7048  7048 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-01 10:59:51.846  7048  7048 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-01 10:59:51.846  7048  7048 I dhcpcd  : bssid match
09-01 10:59:51.846  7048  7048 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
09-01 10:59:51.846  6928  6969 D BtGatt.GattService: onClientRegistered() - UUID=89d52111-55e4-4c54-8688-8202ca6ebaff, clientIf=6
09-01 10:59:51.846  6223  6231 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 10:59:51.846  6928  6970 D BtGatt.GattService: start scan with filters
,09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:51.856  6928  6974 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@cbd3f0f
09-01 10:59:51.856  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:51.856  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:51.856  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 10:59:51.856  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 10:59:51.856  6928  6969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-01 10:59:51.856  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: allow scan with filters
09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-01 10:59:51.856  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:51.856  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:51.856  6928  6974 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:51.856  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:51.856  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:51.856  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:51.866  6928  6969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-01 10:59:51.866  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.866  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-01 10:59:51.866  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.866  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:51.876  6223  6275 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-01 10:59:51.876  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:51.876  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:51.876  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:51.876  6928  6936 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:51.876  6928  6970 D BtGatt.GattService: unregisterClient() - clientIf=6,
,09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:51.876  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:51.876  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:51.886  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:51.886  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:51.886  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:51.886  6928  6974 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 3
,09-01 10:59:51.886  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-01 10:59:51.886  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:51.886  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:51.886  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b7923d7 removed from the list
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9f4c4 removed from the list
09-01 10:59:51.886  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop,
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:51.886  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.886  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ac9f4c4 not in the list
,09-01 10:59:51.886  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b422673 removed from the list
,09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:51.886  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:51.886  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19f762e2 removed from the list
09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:51.886  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378eb6cf added. We now have 2 listener(s)
,09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:51.886  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:51.896  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:51.896  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c added. We now have 9 listener(s)
09-01 10:59:51.896  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:51.896  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:51.896  6928  6974 D BtGatt.ScanManager: filter size is 1
09-01 10:59:51.896  6928  6974 D BtGatt.ScanManager: delete FilterIndex - 3
09-01 10:59:51.896  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:51.896  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:51.896  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:51.896  6928  6974 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:51.896  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:51.896  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:51.896  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.896  6928  6974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:51.896  6928  6969 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:51.896  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.906  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:51.906  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:51.906  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-01 10:59:51.906  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:51.906  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e6c3a added. We now have 3 listener(s)
,09-01 10:59:51.906  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.906  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:51.906  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:51.906  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:51.906  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:51.906  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e69f0eb added. We now have 10 listener(s)
09-01 10:59:51.906  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:51.906  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:51.906  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:51.906  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:51.906  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:51.906  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:51.906  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:51.906  7048  7048 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-01 10:59:51.916  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:51.916  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:51.916  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:51.916  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:51.916  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:51.916  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:51.926  6928  6970 D BtGatt.GattService: registerClient() - UUID=408adb9e-71e1-4343-be26-8ebabd15ff3b
,09-01 10:59:51.966  6928  6969 D BtGatt.GattService: onClientRegistered() - UUID=408adb9e-71e1-4343-be26-8ebabd15ff3b, clientIf=6
,09-01 10:59:51.966  6223  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-01 10:59:51.966  6928  6937 D BtGatt.GattService: start scan with filters
,09-01 10:59:51.966  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:51.966  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:51.966  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:51.966  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:51.966  6928  6974 D BtGatt.ScanManager: handling starting scan
,09-01 10:59:51.966  6928  6969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:51.966  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.966  6928  6974 D BtGatt.ScanManager: allow scan with filters
,09-01 10:59:51.976  6928  6974 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-01 10:59:51.976  6928  6974 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-01 10:59:51.976  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:51.976  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:51.976  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:51.976  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:51.976  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:51.976  6928  6974 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:51.976  6928  6974 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:51.976  6928  6969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-01 10:59:51.976  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:51.976  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-01 10:59:51.986  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:51.986  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:51.986  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:51.986  6223  6275 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-01 10:59:51.986  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:51.986  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:51.986  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:51.986  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:51.986  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@378eb6cf removed from the list
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.986  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c removed from the list
09-01 10:59:51.986  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:51.986  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 10:59:51.986  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:51.986  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1691185c not in the list
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 10:59:51.986  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:51.986  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:51.996  6928  6937 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:51.996  6928  6936 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:51.996  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 10:59:52.006  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-01 10:59:52.006  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:52.006  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:52.006  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:52.006  6928  6974 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 4
,09-01 10:59:52.006  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:52.006  6928  6974 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:52.006  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:52.006  6928  6974 D BtGatt.ScanManager: delete FilterIndex - 4
09-01 10:59:52.006  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 10:59:52.006  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:52.006  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-01 10:59:52.006  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.006  6928  6974 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:52.016  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:52.016  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:52.016  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e69f0eb removed from the list
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:52.016  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e6c3a removed from the list
,09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3974b0c7 added. We now have 2 listener(s)
,09-01 10:59:52.016  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-01 10:59:52.016  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.016  6928  6974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:52.016  6928  6969 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:52.016  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 added. We now have 9 listener(s)
09-01 10:59:52.016  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:52.016  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:52.016  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:52.016  7048  7048 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-01 10:59:52.026  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:52.036  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:52.046  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:52.046  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:52.046  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:52.046  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9824892 added. We now have 3 listener(s)
,09-01 10:59:52.046  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:52.046  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-01 10:59:52.046  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:52.046  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:52.046  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:52.046  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31819263 added. We now have 10 listener(s)
09-01 10:59:52.046  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:52.046  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:52.046  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:52.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:52.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:52.046  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,09-01 10:59:52.056  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:52.056  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:52.076  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
09-01 10:59:52.076  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:52.086  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:52.086  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:52.086  6223  6275 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:52.086  6928  6936 D BtGatt.GattService: registerClient() - UUID=b4cd7635-e436-4d7a-9cd6-fc0c3e4bbcac
,09-01 10:59:52.126  6928  6969 D BtGatt.GattService: onClientRegistered() - UUID=b4cd7635-e436-4d7a-9cd6-fc0c3e4bbcac, clientIf=6
,09-01 10:59:52.126  6223  6231 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-01 10:59:52.136  6928  6970 D BtGatt.GattService: start scan with filters
,09-01 10:59:52.136  6928  6974 D BtGatt.ScanManager: handling starting scan
09-01 10:59:52.136  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:52.136  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:52.136  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:52.136  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:52.136  6928  6969 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-01 10:59:52.136  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:52.136  6928  6974 D BtGatt.ScanManager: allow scan with filters
,09-01 10:59:52.136  6928  6974 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-01 10:59:52.136  6928  6974 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-01 10:59:52.136  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:52.136  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:52.136  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:52.146  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-01 10:59:52.146  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:52.146  6928  6974 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:52.146  6928  6974 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-01 10:59:52.146  6928  6969 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-01 10:59:52.146  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-01 10:59:52.146  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-01 10:59:52.146  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.156  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:52.166  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:52.166  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:52.166  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:52.166  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:52.166  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3974b0c7 removed from the list
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.166  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 removed from the list
09-01 10:59:52.166  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:52.166  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 10:59:52.166  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.166  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57616f4 not in the list
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:52.166  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:52.166  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:52.176  6928  6936 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:52.176  6928  6970 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:52.176  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.176  6223  6223 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:52.176  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31819263 removed from the list,
,09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:52.176  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.176  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 10:59:52.176  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:52.176  6223  6223 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-01 10:59:52.176  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9824892 removed from the list
09-01 10:59:52.186  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:52.186  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0f1bf added. We now have 2 listener(s)
09-01 10:59:52.186  6928  6974 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 5
09-01 10:59:52.186  6928  6974 D BtGatt.ScanManager: filter size is 1
,09-01 10:59:52.186  6928  6974 D BtGatt.ScanManager: delete FilterIndex - 5
,09-01 10:59:52.186  6928  6969 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-01 10:59:52.186  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.196  6928  6974 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:52.196  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-01 10:59:52.196  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:52.196  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:52.196  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:52.196  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c added. We now have 9 listener(s)
09-01 10:59:52.196  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:52.196  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:52.196  6928  6969 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-01 10:59:52.196  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.196  6928  6974 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-01 10:59:52.196  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:52.196  6928  6969 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-01 10:59:52.196  6928  6969 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:52.206  6223  6275 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:52.206  6223  6275 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:52.206  6223  6275 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:52.206  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:52.206  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382a57ea added. We now have 3 listener(s)
,09-01 10:59:52.216  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:52.216  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:52.216  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cceadb added. We now have 10 listener(s)
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:52.216  6223  6275 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:52.216  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:52.216  6223  6275 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:52.216  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:52.216  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ff0f1bf removed from the list
09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.216  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c removed from the list
09-01 10:59:52.216  6223  6223 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:52.216  6223  6275 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:52.216  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:52.216  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.216  6223  6275 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf9508c not in the list
09-01 10:59:52.216  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.216  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:52.226  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:52.226  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:52.226  6223  6275 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:52.226  6223  6275 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39cceadb removed from the list
09-01 10:59:52.226  6223  6275 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:52.226  6223  6275 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:52.226  6223  6275 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:52.226  6223  6275 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:52.226  6223  6275 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@382a57ea removed from the list
,09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 10:59:52.226  6223  6275 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-01 10:59:52.226  6223  7079 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1186, name: My test thread name)
,09-01 10:59:52.226  6223  7079 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1186, thread name: My test thread name),
09-01 10:59:52.226  6223  7079 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 10:59:52.236  6223  7081 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1188, name: My test thread name),
09-01 10:59:52.236  6223  7081 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1188, thread name: My test thread name)
09-01 10:59:52.236  6223  7081 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 10:59:52.236  6223  6275 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-01 10:59:52.236  6223  6275 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-01 10:59:52.236  6223  6275 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 10:59:52.236  6223  6275 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 10:59:52.236  6223  6275 D com.test.thalitest.ThaliTestRunner: Total duration: 23246 ms
,09-01 10:59:52.236  6223  6275 I jxcore-log: *Native tests were executed*
09-01 10:59:52.236  6223  6275 I jxcore-log: 
,09-01 10:59:52.236  6223  6275 I jxcore-log: Total number of executed tests:  80
09-01 10:59:52.236  6223  6275 I jxcore-log: 
09-01 10:59:52.236  6223  6275 I jxcore-log: Number of passed tests:  80
09-01 10:59:52.236  6223  6275 I jxcore-log: 
09-01 10:59:52.236  6223  6275 I jxcore-log: Number of failed tests:  0
09-01 10:59:52.236  6223  6275 I jxcore-log: 
09-01 10:59:52.236  6223  6275 I jxcore-log: Number of ignored tests:  0
09-01 10:59:52.236  6223  6275 I jxcore-log: 
,09-01 10:59:52.236  6223  6275 I jxcore-log: Total duration:  23246
09-01 10:59:52.236  6223  6275 I jxcore-log: 
,09-01 10:59:52.236  6223  6275 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 10:59:52.236  6223  6275 I jxcore-log: 
,09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.246  6223  6275 I jxcore-log: 
09-01 10:59:52.246  6223  6223 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 10:59:52.246   287   287 E SMD     : DCD OFF
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-01 10:59:52.256  6223  6275 I jxcore-log: 
,09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.256  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.256  6223  6275 I jxcore-log: 
09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.266  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:52.266  6223  6275 I jxcore-log: 
,09-01 10:59:52.376  1015  1130 E WifiNative-wlan0: do suspend true,
,09-01 10:59:52.386  6223  6223 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:52.386  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:52.386  6223  6275 I jxcore-log: ,
,09-01 10:59:52.406  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-01 10:59:52.406  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
09-01 10:59:52.406  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:52.406  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
09-01 10:59:52.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.406  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:52.406  1015  1130 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-01 10:59:52.406  1015  1130 E WifiStateMachine: VerifyingLinkState enter
09-01 10:59:52.416  1015  1130 D WifiNative-wlan0: callSECApiInt - ID [210]
09-01 10:59:52.416  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:52.416  1015  1132 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-01 10:59:52.416  1015  1132 D ConnectivityService: Adding iface wlan0 to network 504
09-01 10:59:52.426  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-01 10:59:52.426  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 10:59:52.426  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 10:59:52.426  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 10:59:52.426  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-01 10:59:52.426  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:52.426  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:52.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.426  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.436  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:52.436  1015  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:52.436  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:52.436  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:52.436  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:52.436  3623  3623 I Hs20UtilService: Starting #22
09-01 10:59:52.436  1015  1130 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-01 10:59:52.446  3623  3665 I Hs20UtilService: Message received 5007
09-01 10:59:52.446  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:52.446  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-01 10:59:52.456  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:52.466  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:52.466  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-01 10:59:52.466  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.466  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.466  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.466  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.466  1015  1132 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
09-01 10:59:52.466  1015  1132 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-01 10:59:52.466  1015  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 10:59:52.466  1015  1132 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-01 10:59:52.466  1015  1130 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-01 10:59:52.466  1015  1132 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-01 10:59:52.466  1015  1132 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-01 10:59:52.476  1015  1132 D ConnectivityService: LTETest block dns file not exists
09-01 10:59:52.476  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-01 10:59:52.476  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
09-01 10:59:52.476  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
09-01 10:59:52.476  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
09-01 10:59:52.476  1015  1559 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:52.476  1015  1559 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:52.476  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:52.476  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:52.486  1015  1132 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.476  1015  1559 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:52.486  1015  1132 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-01 10:59:52.476  1015  1559 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:52.486  1015  1132 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.476  1015  1559 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:52.486  1015  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.476  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.486  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:52.486  1015  1132 E ConnectivityService: updateNetworkInfo()
09-01 10:59:52.486  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:52.486  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-01 10:59:52.486  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-01 10:59:52.486  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-01 10:59:52.486  1015  7044 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-01 10:59:52.486  3623  3623 I Hs20UtilService: Starting #23
09-01 10:59:52.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.486  3623  3665 I Hs20UtilService: Message received 5007
09-01 10:59:52.486  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:52.496   276   984 D EnterpriseController: uids 1000
09-01 10:59:52.496  1015  1132 D ConnectivityService:    accepting network in place of null
09-01 10:59:52.496   276   984 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-01 10:59:52.496   276   984 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-01 10:59:52.496  1015  1130 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 10:59:52.496  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-01 10:59:52.496  1456  1456 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-01 10:59:52.496  1015  1132 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-01 10:59:52.496  1015  1132 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-01 10:59:52.496  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-01 10:59:52.496  1456  1456 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-01 10:59:52.496  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:52.496  1322  1322 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-01 10:59:52.506  1015  1132 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-01 10:59:52.506  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-01 10:59:52.506  1015  1133 D Tethering: MasterInitialState.processMessage what=3
09-01 10:59:52.506  1015  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.506  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1015  1123 V NetworkStats: updateIfacesLocked()
09-01 10:59:52.506  1175  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 10:59:52.506  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
09-01 10:59:52.506  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:52.506  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-01 10:59:52.506  3781  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-01 10:59:52.506  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-01 10:59:52.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1015  1123 V NetworkStats: performPollLocked() took 5ms
09-01 10:59:52.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-01 10:59:52.506  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.506  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-01 10:59:52.506  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 10:59:52.506  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:52.506  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:52.506  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:52.506  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-01 10:59:52.506  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-01 10:59:52.506  1322  1322 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-01 10:59:52.506  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
09-01 10:59:52.516  6223  6223 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-01 10:59:52.516  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:52.516  6223  6275 I jxcore-log: 
09-01 10:59:52.516  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.516  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-01 10:59:52.516  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.516  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.526  1015  3154 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-01 10:59:52.526  1015  3154 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-01 10:59:52.526  1015  3154 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:52.526  1015  3154 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:52.526  1015  3154 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-01 10:59:52.526  3623  3623 I Hs20UtilService: Starting #24
09-01 10:59:52.526  1322  1322 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-01 10:59:52.526  3623  3665 I Hs20UtilService: Message received 5007
09-01 10:59:52.526  1322  1322 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-01 10:59:52.536  7083  7083 D AndroidRuntime: 
09-01 10:59:52.536  7083  7083 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-01 10:59:52.536  1015  1476 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-01 10:59:52.536  7083  7083 D AndroidRuntime: CheckJNI is OFF
09-01 10:59:52.536  7083  7083 D AndroidRuntime: readGMSProperty: start
09-01 10:59:52.536  7083  7083 D AndroidRuntime: readGMSProperty: already setted!!
09-01 10:59:52.536  7083  7083 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-01 10:59:52.536  7083  7083 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-01 10:59:52.536  7083  7083 D AndroidRuntime: readGMSProperty: end
09-01 10:59:52.536  7083  7083 D AndroidRuntime: addProductProperty: start
09-01 10:59:52.536  1015  1475 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-01 10:59:52.536  1015  1475 D SecContentProvider2: mCursor = null
09-01 10:59:52.536  1015  1138 D SecContentProvider2: uri = 15 selection = getToastGravity
09-01 10:59:52.536  1015  1138 D SecContentProvider2: mCursor = null
09-01 10:59:52.546  1015  1216 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-01 10:59:52.546  1015  1216 D SecContentProvider2: mCursor = null
09-01 10:59:52.546  1015  3162 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-01 10:59:52.546  1015  3162 D SecContentProvider2: mCursor = null
09-01 10:59:52.546  1015  1559 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-01 10:59:52.546  1015  1559 D SecContentProvider2: mCursor = null
09-01 10:59:52.546  1015  3154 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-01 10:59:52.546  1015  3154 D SecContentProvider2: mCursor = null
09-01 10:59:52.576   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-01 10:59:52.586  1015  3166 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015,
,09-01 10:59:52.586  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-01 10:59:52.666  7083  7083 E AffinityControl: AffinityControl: registerfunction enter
,09-01 10:59:52.676  1015  7044 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-01 10:59:52.676  6223  6223 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:52.686  6223  6275 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:52.686  6223  6275 I jxcore-log: 
,09-01 10:59:52.696  7083  7083 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 10:59:52.696  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 08:59:52 GMT], X-Android-Received-Millis=[1472720392704], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472720392692]}
09-01 10:59:52.696  1015  1132 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.696  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.,
,09-01 10:59:52.696  1015  1132 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.696  1015  7044 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-01 10:59:52.696  1015  1132 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-01 10:59:52.696  3781  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:52.696  1015  1132 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-01 10:59:52.696  1175  1719 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-01 10:59:52.696  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: updateDataNetType()
09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-01 10:59:52.706  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-01 10:59:52.706  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,09-01 10:59:52.716  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700",
,09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.716  1015  1314 D PackageManager: START PACKAGE DELETE: observer{64838545}
09-01 10:59:52.716  1015  1314 D PackageManager: pkg{<packageName>}
09-01 10:59:52.716  1015  1314 D PackageManager: user{0}
,09-01 10:59:52.716  1015  1314 D PackageManager: caller{2000}
09-01 10:59:52.716  1015  1314 D PackageManager: flags{2}
09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-01 10:59:52.726  1015  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-01 10:59:52.716  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-01 10:59:52.716  1015  1314 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-01 10:59:52.716  1015  1314 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-01 10:59:52.716  1015  1314 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-01 10:59:52.716  1015  1314 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-01 10:59:52.716  1015  1314 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-01 10:59:52.726  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-01 10:59:52.726  1015  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-01 10:59:52.726  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
,09-01 10:59:52.726  1015  1056 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-01 10:59:52.726  1015  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-01 10:59:52.726  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-01 10:59:52.726  1015  1041 I ActivityManager: Killing 6223:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-01 10:59:52.736  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{1f76414 u0 com.test.thalitest/.MainActivity t128}
,09-01 10:59:52.746  1015  1041 W ActivityManager: mDVFSHelper.acquire(),
,09-01 10:59:52.846  1015  3154 I WindowState: WIN DEATH: Window{d3e7c74 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 10:59:52.846   257   429 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
09-01 10:59:52.846   257   429 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-01 10:59:52.856  1015  3154 D InputDispatcher: Focus left window: 6223
,09-01 10:59:52.866  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
,09-01 10:59:52.866  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-01 10:59:52.876  1015  1056 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-01 10:59:52.876  1015  1056 I ActivityManager:   Force finishing activity ActivityRecord{1f76414 u0 com.test.thalitest/.MainActivity t128 f}
,09-01 10:59:52.876  1015  1056 W ActivityManager: Duplicate finish request for ActivityRecord{1f76414 u0 com.test.thalitest/.MainActivity t128 f}
,09-01 10:59:52.906  1015  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-01 10:59:52.916  5667  5667 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 700us total 26.916ms
,09-01 10:59:52.926  3141  3141 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-01 10:59:52.936  1015  1041 D InputDispatcher: Focused application released
,09-01 10:59:52.956  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-01 10:59:52.956  5456  5456 I art     : Explicit concurrent mark sweep GC freed 386(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 15.941ms total 53.018ms
,09-01 10:59:52.966  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-01 10:59:52.976  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-01 10:59:52.976  3141  3141 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-01 10:59:52.986  3781  3781 I art     : Explicit concurrent mark sweep GC freed 23775(1429KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.318ms total 89.808ms
,09-01 10:59:52.986  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-01 10:59:52.996  1814  1814 E SamsungIME: mOCRHelper is null
,09-01 10:59:52.996  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 10:59:52.996  1015  1132 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:53.006  1913  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 10:59:53.026  1015  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
,09-01 10:59:53.026  1015  1123 V NetworkStats: performPollLocked(flags=0x3)
09-01 10:59:53.026  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:53.026  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
09-01 10:59:53.026  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-01 10:59:53.036  1015  1123 V NetworkStats: performPollLocked() took 8ms
09-01 10:59:53.036  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:53.046  3141  3141 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-01 10:59:53.056  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:53.056  3141  3141 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-01 10:59:53.066  3668  3668 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 01 10:59:53 GMT+02:00 2016
,09-01 10:59:53.086  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
09-01 10:59:53.086  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-01 10:59:53.086  1015  1040 W TextServicesManagerService: no available spell checker services found
,09-01 10:59:53.096  1015  1558 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-01 10:59:53.096  1015  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-01 10:59:53.096  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
09-01 10:59:53.096  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
09-01 10:59:53.096  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-01 10:59:53.096  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-01 10:59:53.096  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=23141)
09-01 10:59:53.106  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6928, ws=null) (elapsedTime=4784)
09-01 10:59:53.106  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'NetworkStats' (uid=1000, pid=1015, ws=null) (elapsedTime=73)
09-01 10:59:53.106  1015  1558 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:53.106  1015  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:53.106  1015  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-01 10:59:53.106  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-01 10:59:53.106  6546  6546 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-01 10:59:53.116  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-01 10:59:53.116  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-01 10:59:53.116  1015  1475 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-01 10:59:53.116  1015  1475 D SecContentProvider2: mCursor = null
,09-01 10:59:53.126  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-01 10:59:53.126  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-01 10:59:53.126  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-01 10:59:53.126  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-01 10:59:53.136  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-01 10:59:53.136  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,09-01 10:59:53.136  3668  3668 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-01 10:59:53.136  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-01 10:59:53.136  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-01 10:59:53.136  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-01 10:59:53.136  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 10:59:53.136  1015  1475 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-01 10:59:53.136  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
09-01 10:59:53.136  1015  1475 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-01 10:59:53.146  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-01 10:59:53.146  1015  3166 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-01 10:59:53.146  3668  3668 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-01 10:59:53.146  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:53.146  1015  3166 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-01 10:59:53.146  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.146  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.146  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:53.146  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.156  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.156  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.156  3668  3668 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-01 10:59:53.166  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-01 10:59:53.176  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:53.176  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,09-01 10:59:53.176  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-01 10:59:53.186  3141  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0,
09-01 10:59:53.186  3141  3141 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-01 10:59:53.186  3141  3141 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-01 10:59:53.186  7103  7103 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.186  7103  7103 E Zygote  : v2
09-01 10:59:53.186  7103  7103 I libpersona: KNOX_SDCARD checking this for 10094
09-01 10:59:53.186  7103  7103 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.186  3141  3141 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-01 10:59:53.186  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.186  1015  1475 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7103 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-01 10:59:53.196  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.196  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.196  3668  3668 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-01 10:59:53.196  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-01 10:59:53.196  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.196  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.196  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.196  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.206  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-01 10:59:53.216  7116  7116 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.216  7116  7116 E Zygote  : v2
09-01 10:59:53.216  7116  7116 I libpersona: KNOX_SDCARD checking this for 10044
09-01 10:59:53.216  7116  7116 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.216  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.216  1015  1041 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7116 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-01 10:59:53.216  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-01 10:59:53.216  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.216  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.226  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-01 10:59:53.226  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-01 10:59:53.226  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-01 10:59:53.226  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.226  7103  7103 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.236  1015  1056 I art     : Explicit concurrent mark sweep GC freed 73367(5MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 16.177ms total 306.502ms
,09-01 10:59:53.236  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.236  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.236  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.236  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.246  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.246  7116  7116 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.256  7134  7134 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.256  7134  7134 E Zygote  : v2
09-01 10:59:53.256  7134  7134 I libpersona: KNOX_SDCARD checking this for 10149
09-01 10:59:53.256  7134  7134 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.256  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.256  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.256  1015  1041 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7134 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:53.266  1015  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-01 10:59:53.266  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:53.266  1015  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-01 10:59:53.266  1015  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-01 10:59:53.266  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-01 10:59:53.266  1015  2703 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-01 10:59:53.266  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-01 10:59:53.276  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,09-01 10:59:53.276  3141  3141 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-01 10:59:53.296  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:53.306  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-01 10:59:53.306  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-01 10:59:53.306   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-01 10:59:53.306  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-01 10:59:53.306  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-01 10:59:53.306  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,09-01 10:59:53.306  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-01 10:59:53.316  1175  1175 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-01 10:59:53.316  1015  1475 D InputDispatcher: Focus entered window: 3141
,09-01 10:59:53.316  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-01 10:59:53.316  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
09-01 10:59:53.316  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
09-01 10:59:53.316  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
09-01 10:59:53.316  1175  1175 D PanelView: There is/are notification(s) 
09-01 10:59:53.316  1175  1175 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-01 10:59:53.316  3141  3141 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-01 10:59:53.316  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.316  7134  7134 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:53.316  7116  7116 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:53.336  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:53.336  1175  1175 D PanelView: There is/are notification(s) 
09-01 10:59:53.336  1175  1175 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-01 10:59:53.336  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-01 10:59:53.346  3141  3141 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-01 10:59:53.346  3141  3141 V ActivityThread: updateVisibility : ActivityRecord{133f6d9d token=android.os.BinderProxy@1d36d578 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-01 10:59:53.356  1015  3140 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-01 10:59:53.356  1015  3140 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6223 uid 10155
,09-01 10:59:53.356  3668  7102 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-01 10:59:53.356  3668  7102 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-01 10:59:53.356  1175  1175 D PanelView: There is/are notification(s) 
,09-01 10:59:53.366  1814  1814 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-01 10:59:53.376  3141  3141 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d36d578 time:153005
,09-01 10:59:53.376  1015  7150 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-01 10:59:53.386  3668  3668 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-01 10:59:53.386  6943  7126 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-01 10:59:53.386  1175  1175 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-01 10:59:53.386  7103  7103 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-01 10:59:53.396  7103  7103 D elm:15183: ELMEngine.ELMEngine( context ).
,09-01 10:59:53.406  7103  7103 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-01 10:59:53.406  1015  1027 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-01 10:59:53.406  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-01 10:59:53.406  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
09-01 10:59:53.406  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:53.406  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:53.406  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-01 10:59:53.416  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.416  1015  1046 W ActivityManager: mDVFSHelper.release()
09-01 10:59:53.416  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2efc2228 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:153049
,09-01 10:59:53.426  7103  7103 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-01 10:59:53.426  6943  6943 I art     : Explicit concurrent mark sweep GC freed 765(54KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 709us total 86.732ms
,09-01 10:59:53.436  3343  3343 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-01 10:59:53.436  7134  7134 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-01 10:59:53.436  7134  7134 D ThemeInfoUtil: isCurrentFestival = false
,09-01 10:59:53.436  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-01 10:59:53.436  7103  7103 D elm:15183: ElmAgentService : onCreate()
,09-01 10:59:53.436  7103  7152 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-01 10:59:53.436  3343  3343 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-01 10:59:53.436  3343  3343 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-01 10:59:53.436  3343  3343 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-01 10:59:53.436  3343  3343 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-01 10:59:53.436  3343  3343 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:53.436  3343  3343 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-01 10:59:53.436  3343  3343 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-01 10:59:53.436  3343  3343 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-01 10:59:53.436  7103  7152 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-01 10:59:53.436  7103  7152 D elm:15183: MDMBridge.getInstance()
09-01 10:59:53.436  7103  7152 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-01 10:59:53.446  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.446  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.446  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.446  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.446  7103  7152 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-01 10:59:53.446  6000  6011 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-01 10:59:53.446  6000  6011 D BadgeProvider: sendNotify, [notify] : null
09-01 10:59:53.446  6000  6011 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-01 10:59:53.446  6000  6011 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-01 10:59:53.446  6000  6011 D BadgeProvider: update, [UpdateCount] : 1
,09-01 10:59:53.446  1015  1557 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-01 10:59:53.456  1015  1557 D SecContentProvider2: mCursor = null
,09-01 10:59:53.456  7154  7154 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.456  7154  7154 E Zygote  : v2
09-01 10:59:53.456  7154  7154 I libpersona: KNOX_SDCARD checking this for 10152
09-01 10:59:53.456  7154  7154 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.456  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.456  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:53.456  1015  1475 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7154 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a,
09-01 10:59:53.456  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.466  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.486  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.486  7154  7154 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.486  6528  6528 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-01 10:59:53.486  6528  6528 I PCWCLIENTTRACE_PushUtil: sales region : global
09-01 10:59:53.486  6528  6528 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-01 10:59:53.486  6528  6528 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-01 10:59:53.496  7103  7103 D elm:15183: ElmAgentService : onDestroy().
,09-01 10:59:53.496  1015  3161 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-01 10:59:53.496  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.496  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.496  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.496  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.506  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.516  1015  1132 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network,
,09-01 10:59:53.516  7172  7172 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.516  7172  7172 E Zygote  : v2,
09-01 10:59:53.516  7172  7172 I libpersona: KNOX_SDCARD checking this for 10032
09-01 10:59:53.516  7172  7172 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.516  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.516  1015  1056 D PackageManager: delete codoeFile: ,
09-01 10:59:53.516  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:53.516  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.516  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:53.516  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.516  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-01 10:59:53.516  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.526  1015  1056 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-01 10:59:53.526  1015  1056 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,09-01 10:59:53.526  1015  3161 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7172 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-01 10:59:53.536  1015  1056 D PackageManager: result of delete: 1{64838545}
,09-01 10:59:53.536  1015  3161 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-01 10:59:53.536  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.536  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.536  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.536  1015  3161 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.536  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.546  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.546  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.546  7172  7172 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.546  7188  7188 E Zygote  : MountEmulatedStorage()
,09-01 10:59:53.546  7188  7188 E Zygote  : v2
09-01 10:59:53.546  7188  7188 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:53.556  7154  7154 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-01 10:59:53.546  7188  7188 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.556  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.556  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:53.556  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:53.556  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 10:59:53.556  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.556  1015  3161 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-01 10:59:53.556  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.556  7083  7083 D AndroidRuntime: Shutting down VM
,09-01 10:59:53.566  1015  3161 I ActivityManager: Killing 6154:com.samsung.helphub/1000 (adj 15): empty #31
,09-01 10:59:53.576  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-01 10:59:53.576  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-01 10:59:53.586  1015  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-01 10:59:53.586  1015  1056 D PackageManager: userId{-1}
09-01 10:59:53.586  1015  1056 D PackageManager: andCode{true}
,09-01 10:59:53.586  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.586  7188  7188 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:53.586  1015  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-01 10:59:53.596  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-01 10:59:53.596  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-01 10:59:53.596  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
09-01 10:59:53.596  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-01 10:59:53.596  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-01 10:59:53.616  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-01 10:59:53.616  1015  3154 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-01 10:59:53.616  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-01 10:59:53.616  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.616  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.616  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.616  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.626  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
09-01 10:59:53.626  7205  7205 I libpersona: KNOX_SDCARD checking this for 10156
09-01 10:59:53.626  7116  7116 D NearbySource: Nearby Source Create!
09-01 10:59:53.626  7205  7205 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.626  7116  7116 D NearbyContext: Nearby Context Create!
,09-01 10:59:53.626  7205  7205 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.626  7205  7205 E Zygote  : v2
09-01 10:59:53.626  7205  7205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.636  7205  7205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:53.636  1015  3154 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7205 uid=10156 gids={50156, 9997} abi=armeabi-v7a
09-01 10:59:53.636  7205  7205 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.646  1015  3140 I ActivityManager: Killing 5456:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-01 10:59:53.666  1015  1475 D PersonaManager: isKioskContainerExistOnDevice
,09-01 10:59:53.666  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-01 10:59:53.676  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-01 10:59:53.676  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:53.676   256   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-01 10:59:53.676   256   518 W Vold    : Returning OperationFailed - no handler for errno 0
,09-01 10:59:53.676  7205  7205 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.676  7205  7205 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.686  7116  7116 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-01 10:59:53.686  7116  7116 D SLinkSource: Samsung link source created
,09-01 10:59:53.686  7188  7188 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-01 10:59:53.696  1015  1500 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-01 10:59:53.696  1015  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-01 10:59:53.696  1015  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-01 10:59:53.696  1015  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-01 10:59:53.696  1015  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-01 10:59:53.706  1015  3162 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-01 10:59:53.706  7172  7220 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-01 10:59:53.706  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.706  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.706  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.706  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.716  7205  7205 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-01 10:59:53.716  7205  7205 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-01 10:59:53.726  7223  7223 E Zygote  : MountEmulatedStorage()
,09-01 10:59:53.726  7223  7223 I libpersona: KNOX_SDCARD checking this for 1000
09-01 10:59:53.726  7223  7223 E Zygote  : v2
09-01 10:59:53.726  7223  7223 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.726  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:53.726  7172  7220 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-01 10:59:53.726  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.726  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.726  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:53.726  7172  7220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:53.736  7205  7205 I TapandpayWidget:Utils: Clear T&P info.
09-01 10:59:53.736  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-01 10:59:53.736  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-01 10:59:53.736  1015  3162 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7223 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-01 10:59:53.736  1015  3162 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-01 10:59:53.736  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.736  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.736  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.736  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.736  7172  7220 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-01 10:59:53.756  7205  7205 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-01 10:59:53.756  7235  7235 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.756  7235  7235 E Zygote  : v2
09-01 10:59:53.756  7235  7235 I libpersona: KNOX_SDCARD checking this for 10035
09-01 10:59:53.756  7235  7235 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.756  7235  7235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.756  7235  7235 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.756  7235  7235 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.756  1015  3162 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7235 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:53.766  1015  3162 I ActivityManager: Killing 5586:com.android.vending/u0a28 (adj 15): empty #31
,09-01 10:59:53.776  7083  7083 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-01 10:59:53.776  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.776  1015  3154 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
09-01 10:59:53.776  7223  7223 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:53.776  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.776  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.776  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.776  1015  3154 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.786  7172  7220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:53.786  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.786  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:53.786  7235  7235 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.796  7235  7235 D ActivityThread: Added TimaKeyStore provider,
,09-01 10:59:53.796  7255  7255 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.796  7255  7255 I libpersona: KNOX_SDCARD checking this for 10160
09-01 10:59:53.796  7255  7255 E Zygote  : v2
09-01 10:59:53.796  7255  7255 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.796  7255  7255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.796  7255  7255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-01 10:59:53.796  7172  7220 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-01 10:59:53.796  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.796  7172  7220 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-01 10:59:53.796  7255  7255 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.806  1015  3154 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7255 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,09-01 10:59:53.806  1015  3154 I ActivityManager: Killing 6295:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,09-01 10:59:53.826   302   302 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 28.795ms
,09-01 10:59:53.826  7172  7220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-01 10:59:53.826  7255  7255 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:53.836  7255  7255 D ActivityThread: Added TimaKeyStore provider
09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 10:59:53.836  7172  7220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:53.846   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 601us total 18.832ms
,09-01 10:59:53.856  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.856  7172  7220 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 10:59:53.856  7172  7220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:53.866  1015  1216 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:53.866  1015  3154 I ActivityManager: Killing 6591:com.android.chrome/u0a81 (adj 15): empty #31
,09-01 10:59:53.876  7116  7227 D ContactProvider: getAllContactInfoList Start
09-01 10:59:53.876   302   302 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 683us total 22.754ms
09-01 10:59:53.876  1015  3166 I ActivityManager: Killing 6561:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,09-01 10:59:53.886  1015  3161 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-01 10:59:53.886  7116  7116 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-01 10:59:53.886  7255  7255 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-01 10:59:53.896  7223  7223 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.896  7172  7220 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-01 10:59:53.896  7172  7220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:53.896  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.896  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.896  7172  7220 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:53.916  7255  7255 D [0]UMC:UMCContentProvider: @onCreate
09-01 10:59:53.916  7116  7227 D ContactProvider: getAllContactInfoList End
,09-01 10:59:53.916  7116  7227 I syncContacts: thread: 1178, sync time = 170
,09-01 10:59:53.916  7172  7220 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-01 10:59:53.916  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.916  7172  7220 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-01 10:59:53.916  7172  7220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-01 10:59:53.916  7223  7223 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-01 10:59:53.916  1015  3162 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-01 10:59:53.916  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.916  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.916  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.916  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:53.916  1015  1500 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-01 10:59:53.916  1015  1500 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-01 10:59:53.926  7172  7220 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-01 10:59:53.926  7172  7220 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:53.926  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.926  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.926  7172  7220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:53.936  7273  7273 E Zygote  : MountEmulatedStorage()
,09-01 10:59:53.936  7273  7273 E Zygote  : v2
09-01 10:59:53.936  7273  7273 I libpersona: KNOX_SDCARD checking this for 10046
09-01 10:59:53.936  7273  7273 I libpersona: KNOX_SDCARD not a persona
,09-01 10:59:53.936  7273  7273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.936  7273  7273 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.936  7273  7273 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-01 10:59:53.936  1015  3162 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7273 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-01 10:59:53.946  1015  3162 I ActivityManager: Killing 6613:com.sec.android.soagent/u0a34 (adj 15): empty #31
,09-01 10:59:53.946  7172  7220 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-01 10:59:53.946  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-01 10:59:53.956  7235  7276 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-01 10:59:53.956  7235  7276 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-01 10:59:53.956  7255  7255 D [0]UMC:Core: onCreate(): 
09-01 10:59:53.956  1015  3162 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
09-01 10:59:53.956  7255  7255 D [0]UMC:Core: @isManagedProfileUser
09-01 10:59:53.956  7255  7255 D [0]UMC:Core: userId: 0
,09-01 10:59:53.956  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.956  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.956  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.956  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.956  7255  7255 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
09-01 10:59:53.956  7255  7255 D [0]UMC:Core: userInfo.isManagedProfile() : false
,09-01 10:59:53.976  7289  7289 E Zygote  : MountEmulatedStorage()
09-01 10:59:53.976  7289  7289 E Zygote  : v2
09-01 10:59:53.976  7289  7289 I libpersona: KNOX_SDCARD checking this for 10091
09-01 10:59:53.976  7289  7289 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:53.976  7289  7289 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-01 10:59:53.976  7289  7289 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-01 10:59:53.976  7289  7289 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-01 10:59:53.986  6943  6943 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched),
09-01 10:59:53.986  1015  3162 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7289 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-01 10:59:53.986  7273  7273 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:53.986  7172  7220 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:53.996  7273  7273 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:53.996  1015  3162 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,09-01 10:59:53.996  7235  7276 D SPPClientService: PushLog.txt file is not deleted.
09-01 10:59:53.996  7235  7276 D SPPClientService: PushLog.txt file is not deleted.
09-01 10:59:53.996  7235  7276 D SPPClientService: ============PushLog. stop!
,09-01 10:59:53.996  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.996  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.996  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-01 10:59:53.996  1015  3162 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-01 10:59:54.006  7255  7255 D [0]UMC:DeviceInfo: USA==US==
,09-01 10:59:54.016  7172  7220 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-01 10:59:54.016  7172  7220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-01 10:59:54.026  7289  7289 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:54.026  7289  7289 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:54.036  7306  7306 E Zygote  : MountEmulatedStorage()
,09-01 10:59:54.036  7306  7306 I libpersona: KNOX_SDCARD checking this for 10038
09-01 10:59:54.036  7306  7306 E Zygote  : v2
09-01 10:59:54.036  7306  7306 I libpersona: KNOX_SDCARD not a persona
09-01 10:59:54.036  7306  7306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-01 10:59:54.036  7306  7306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-01 10:59:54.036  1015  3162 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7306 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,09-01 10:59:54.036  7306  7306 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-01 10:59:54.036  1015  3162 I ActivityManager: Killing 6435:com.google.android.talk/u0a104 (adj 15): empty #31
,09-01 10:59:54.046  7172  7220 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-01 10:59:54.066  1015  1559 I ActivityManager: Killing 6633:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,09-01 10:59:54.066  6000  6011 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-01 10:59:54.066  6000  6011 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,09-01 10:59:54.066  6000  6011 E DatabaseUtils: Writing exception to parcel
09-01 10:59:54.066  6000  6011 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
09-01 10:59:54.066  6000  6011 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
,09-01 10:59:54.076  7306  7306 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-01 10:59:54.076  7306  7306 D ActivityThread: Added TimaKeyStore provider
,09-01 10:59:54.086  7273  7273 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-01 10:59:54.086  7273  7273 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-01 10:59:54.086  7273  7273 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-01 10:59:54.086  7273  7273 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:54.086  7273  7273 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-01 10:59:54.096  7273  7273 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-01 10:59:54.096  7306  7306 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-01 10:59:54.096  7306  7306 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-01 10:59:54.106  7255  7255 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,09-01 10:59:54.106  7255  7255 D [0]UMC:AdminManager: init - start
,09-01 10:59:54.136  7255  7255 D [0]UMC:AdminManager: loadAdmins

```
