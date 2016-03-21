#### Test 62548124bd1cdb6_thali02_samsung-SM-A300FU Logs


```
--------- beginning of main
03-21 07:35:42.199   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 07:35:42.249   289   289 E SMD     : DCD OFF
03-21 07:35:42.479  6206  6206 D AndroidRuntime: 
03-21 07:35:42.479  6206  6206 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 07:35:42.479  6206  6206 D AndroidRuntime: CheckJNI is OFF
03-21 07:35:42.479  6206  6206 D AndroidRuntime: readGMSProperty: start
03-21 07:35:42.479  6206  6206 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:35:42.479  6206  6206 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:35:42.479  6206  6206 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 07:35:42.479  6206  6206 D AndroidRuntime: readGMSProperty: end
03-21 07:35:42.479  6206  6206 D AndroidRuntime: addProductProperty: start
03-21 07:35:42.659  6206  6206 E AffinityControl: AffinityControl: registerfunction enter
03-21 07:35:42.679  6206  6206 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 07:35:42.699  1017  1030 E PersonaManagerService: inState():  stateMachine is null !!
03-21 07:35:42.699  1017  1030 I PersonaManagerService: PersonaId don't exist
03-21 07:35:42.699  1017  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 07:35:42.699  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
03-21 07:35:42.709  1017  1030 W ActivityManager: mDVFSHelper.acquire()
03-21 07:35:42.719  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:42.719  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:42.719  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:42.719  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:42.719  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:35:42.719  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 07:35:42.739  6218  6218 E Zygote  : MountEmulatedStorage()
03-21 07:35:42.739  6218  6218 E Zygote  : v2
03-21 07:35:42.739  6218  6218 I libpersona: KNOX_SDCARD checking this for 10167
03-21 07:35:42.739  6218  6218 I libpersona: KNOX_SDCARD not a persona
03-21 07:35:42.739  1017  1030 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6218 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:35:42.739  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 07:35:42.739  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:35:42.739  1017  1030 D InputDispatcher: Focused application set to: xxxx
03-21 07:35:42.739  1017  1030 D InputDispatcher: Focus left window: 5407
03-21 07:35:42.739  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:35:42.739  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:35:42.739  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:35:42.739  6206  6206 D AndroidRuntime: Shutting down VM
03-21 07:35:42.739  6218  6218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:35:42.739   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, uhalitest
03-21 07:35:42.749  6218  6218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:42.749  6218  6218 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 07:35:42.759  6218  6218 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:35:42.759  6218  6218 D ActivityThread: Added TimaKeyStore provider
03-21 07:35:42.769  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:35:42.769  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:35:42.769  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:35:42.789  1017  3009 D PersonaManager: isKioskContainerExistOnDevice
03-21 07:35:42.799  5407  5407 V ActivityThread: updateVisibility : ActivityRecord{6dffa3f token=android.os.BinderProxy@113912e3 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : false
03-21 07:35:42.819   258   451 I SurfaceFlinger: id=11 Removed YUIInstallC (4/10)
03-21 07:35:42.819  4406  4406 V ActivityThread: updateVisibility : ActivityRecord{14937851 token=android.os.BinderProxy@2e8c48c5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
03-21 07:35:42.819   258  1832 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/10)
03-21 07:35:42.859   258   451 I SurfaceFlinger: id=13 Removed TettingsRec (5/9)
03-21 07:35:42.859   258  1832 I SurfaceFlinger: id=13 Removed TettingsRec (-2/9)
03-21 07:35:42.939  6218  6218 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
03-21 07:35:42.949  6218  6218 I LibraryLoader: Loading: webviewchromium
03-21 07:35:42.949  6218  6218 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 4002-4006)
03-21 07:35:42.949  6218  6218 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 07:35:42.949  6206  6206 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-21 07:35:42.979  6218  6218 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1afa2c52}
03-21 07:35:42.979  6218  6218 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 07:35:42.989  6218  6218 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 07:35:43.019  6218  6218 I BrowserStartupController: Initializing chromium process, renderers=0
03-21 07:35:43.019  6218  6218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:43.059  6218  6218 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
03-21 07:35:43.059  6218  6218 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
03-21 07:35:43.059  6218  6218 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
03-21 07:35:43.069  6218  6218 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 07:35:43.069  6218  6218 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 07:35:43.069  6218  6218 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 07:35:43.069  6218  6218 I Adreno-EGL: Local Branch: 
03-21 07:35:43.069  6218  6218 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 07:35:43.069  6218  6218 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 07:35:43.069  6218  6218 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-21 07:35:43.199  6218  6245 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
03-21 07:35:43.199   319   319 I ServiceManager: Waiting for service AtCmdFwd...
03-21 07:35:43.209  6218  6218 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
03-21 07:35:43.239  6218  6218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:43.249  6218  6218 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-21 07:35:43.259  6218  6218 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 07:35:43.259  6218  6218 D PhoneWindow: *FMB* installDecor flags : -2139027200
03-21 07:35:43.259  6218  6218 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-21 07:35:43.269  6218  6218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:43.269  6218  6218 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:43.289  1017  1042 W ActivityManager: Activity pause timeout for ActivityRecord{17496afd u0 com.test.thalitest/.MainActivity t59}
03-21 07:35:43.329  6218  6257 D OpenGLRenderer: Render dirty regions requested: true
03-21 07:35:43.329  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 07:35:43.329  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:35:43.329  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 07:35:43.329  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 07:35:43.329  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 07:35:43.339  6218  6218 V ActivityThread: updateVisibility : ActivityRecord{4a9bd6f token=android.os.BinderProxy@1a28c749 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
03-21 07:35:43.339  6218  6218 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 07:35:43.339  6218  6218 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 07:35:43.359   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
03-21 07:35:43.359  1017  1556 D InputDispatcher: Focus entered window: 6218
03-21 07:35:43.369  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:35:43.369  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:35:43.369  6218  6218 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-21 07:35:43.369  6218  6257 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 07:35:43.369  6218  6257 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-21 07:35:43.369  6218  6257 D OpenGLRenderer: Enabling debug mode 0
03-21 07:35:43.399  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-21 07:35:43.399  1017  6263 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 07:35:43.399  1170  1170 I StatusBar: Icon Only
03-21 07:35:43.399  1170  1170 D PanelView: There is/are notification(s) 
03-21 07:35:43.409  1017  1047 I ActivityManager: Displayed Component not be shown by security: +624ms (total +695ms)
03-21 07:35:43.409  1017  1047 W ActivityManager: mDVFSHelper.release()
03-21 07:35:43.409  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{17496afd u0 com.test.thalitest/.MainActivity t59} time:224469
03-21 07:35:43.419   258   453 I SurfaceFlinger: id=14 Removed uhalitest (7/9)
03-21 07:35:43.419  6218  6218 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-21 07:35:43.419  6218  6218 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a28c749 time:224475
03-21 07:35:43.419   258  1097 I SurfaceFlinger: id=14 Removed uhalitest (-2/9)
03-21 07:35:43.429  1811  1811 I SamsungIME: getCurrentCandidateView
03-21 07:35:43.459  1811  1811 D SamsungIME: Dismiss ExpandCandiate
03-21 07:35:43.519  1017  6265 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-21 07:35:43.529  1811  1811 I SamsungIME: getDebugLevel  : 0x4f4c
03-21 07:35:43.649  1811  1811 I SamsungIME: getDebugLevel  : 0x4f4c
03-21 07:35:43.659  1811  1811 I SamsungIME: KeybaordView init() : load resources
03-21 07:35:43.689  1811  1811 I SamsungIME: getCurrentKeyboard
03-21 07:35:43.689  1811  1811 I SamsungIME: getTextKeyboard
03-21 07:35:43.709  1811  1811 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
03-21 07:35:43.719  6218  6218 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-21 07:35:43.939  6218  6270 D jxcore_app_log: JniHelper::setJavaVM(0xb73f3448), pthread_self() = -1214485760
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 07:35:43.949  6218  6270 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a98aaac added. We now have 1 listener(s)
03-21 07:35:43.959  6218  6270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
03-21 07:35:43.959  6218  6270 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
03-21 07:35:43.959  6218  6270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 07:35:43.959  6218  6270 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 07:35:43.959  6218  6270 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1847237b added. We now have 1 listener(s)
03-21 07:35:43.959  6218  6270 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-21 07:35:43.969  6218  6270 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-21 07:35:43.969  6218  6270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 07:35:43.969  6218  6270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-21 07:35:43.969  6218  6270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-21 07:35:43.969  6218  6270 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-21 07:35:43.969  6218  6270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 07:35:43.979  6218  6270 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 84:b2:61:1a:ce:70
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:35:43.979  6218  6270 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:35:43.979  6218  6270 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 07:35:43.979  6218  6270 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 07:35:43.979  6218  6270 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 07:35:43.989  6218  6218 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 07:35:43.989  6218  6218 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 07:35:43.999  6218  6218 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-21 07:35:43.999  6218  6218 I chromium: 
03-21 07:35:44.019  6218  6218 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-21 07:35:44.199   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 07:35:44.599  6218  6273 W jxcore-log: Initializing JXcore engine
03-21 07:35:44.599  6218  6273 W jxcore-log: JXcore engine is ready
,03-21 07:35:44.649  1855  1855 E audit   : type=1400 msg=audit(1458542144.649:205): avc:  denied  { ioctl } for  pid=6273 comm="Thread-1087" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-21 07:35:44.649  1855  1855 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:44.649  1855  1855 E audit   : type=1300 msg=audit(1458542144.649:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9fbfc8f8 items=0 ppid=311 ppcomm=main pid=6273 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1087" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 07:35:44.649  1855  1855 E audit   : type=1320 msg=audit(1458542144.649:205): 
,03-21 07:35:44.659  6218  6273 W jxcore-log: Starting JXcore engine
,03-21 07:35:44.759  6218  6273 W jxcore-log: Platform android
03-21 07:35:44.759  6218  6273 W jxcore-log: 
03-21 07:35:44.759  6218  6273 W jxcore-log: Process ARCH arm
03-21 07:35:44.759  6218  6273 W jxcore-log: 
,03-21 07:35:44.969  6218  6273 I jxcore-log: JXcore Cordova bridge is ready!
03-21 07:35:44.969  6218  6273 I jxcore-log: 
03-21 07:35:44.969  6218  6273 W jxcore-log: JXcore engine is started
,03-21 07:35:44.969  6218  6270 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 07:35:44.979  6218  6218 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 07:35:44.979  6218  6273 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-21 07:35:44.979  6218  6273 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-21 07:35:44.989  6218  6218 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-21 07:35:44.989  6218  6218 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-21 07:35:44.999  1017  1721 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 07:35:44.999  1017  1721 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 07:35:44.999  1017  1721 D InputDispatcher: Focused application set to: xxxx
03-21 07:35:44.999  1017  1721 I ActivityManager: Killing 5142:com.android.calendar/u0a131 (adj 15): empty #31
03-21 07:35:45.009  6218  6218 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-21 07:35:45.009  6218  6218 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-21 07:35:45.009  6218  6218 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-21 07:35:45.009  6218  6218 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 07:35:45.009  6218  6218 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 07:35:45.009  6218  6218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-21 07:35:45.009  6218  6218 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a98aaac removed from the list
03-21 07:35:45.009  6218  6218 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-21 07:35:45.009  6218  6218 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1847237b removed from the list
03-21 07:35:45.009  6218  6218 D io.jxcore.node.ConnectivityMonitor: stop
03-21 07:35:45.009  6218  6218 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
03-21 07:35:45.009  6218  6218 I io.jxcore.node.LifeCycleMonitor: stop: OK
03-21 07:35:45.009  6218  6218 W ScreenOrientationListener: Removing an inexistent observer!
,03-21 07:35:45.019   258   451 I SurfaceFlinger: id=15 Removed NainActivit (6/8)
,03-21 07:35:45.019   258   453 I SurfaceFlinger: id=15 Removed NainActivit (-2/8)
,03-21 07:35:45.019  1017  1030 D InputDispatcher: Focus left window: 6218
,03-21 07:35:45.019  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:35:45.019  6218  6218 E ViewRootImpl: sendUserActionEvent() mView == null
03-21 07:35:45.029  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:35:45.029  1017  1352 W ActivityManager: mDVFSHelper.acquire()
,03-21 07:35:45.059  1017  1077 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,03-21 07:35:45.059  1017  1077 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 07:35:45.059  1017  1077 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 07:35:45.059  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 07:35:45.059  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 07:35:45.059  1017  1017 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0,
,03-21 07:35:45.069  4406  4406 V ActivityThread: updateVisibility : ActivityRecord{14937851 token=android.os.BinderProxy@2e8c48c5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,03-21 07:35:45.079  1017  1352 D PersonaManager: isKioskContainerExistOnDevice
,03-21 07:35:45.099   258   258 I SurfaceFlinger: id=16 createSurf (540x960),1 flag=404, YUIInstallC,
,03-21 07:35:45.109  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,03-21 07:35:45.119  4406  4406 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 07:35:45.119   258   258 I SurfaceFlinger: id=17 createSurf (585x883),1 flag=4, TettingsRec
,03-21 07:35:45.119  1017  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_5142/cgroup.procs: No such file or directory
,03-21 07:35:45.119  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,03-21 07:35:45.129  1017  1361 D InputDispatcher: Focus entered window: 5407
,03-21 07:35:45.129  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 07:35:45.129  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 07:35:45.129  5407  5407 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 07:35:45.139  5407  5407 V ActivityThread: updateVisibility : ActivityRecord{6dffa3f token=android.os.BinderProxy@113912e3 {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,03-21 07:35:45.169  5407  5407 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@113912e3 time:226223
,03-21 07:35:45.169  1017  1047 W ActivityManager: mDVFSHelper.release()
,03-21 07:35:45.169  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f2c2578 u0 com.android.settings/.SettingsReceiverActivity t58} time:226229
,03-21 07:35:45.179  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36aed3a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t57} time:226230
,03-21 07:35:45.199   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 07:35:45.249   289   289 E SMD     : DCD OFF,
,03-21 07:35:45.269  1017  2718 D SSRM:n  : SIOP:: AP = 290
,03-21 07:35:45.299  6275  6275 D AndroidRuntime: 
03-21 07:35:45.299  6275  6275 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-21 07:35:45.299  6275  6275 D AndroidRuntime: CheckJNI is OFF
,03-21 07:35:45.299  6275  6275 D AndroidRuntime: readGMSProperty: start
03-21 07:35:45.299  6275  6275 D AndroidRuntime: readGMSProperty: already setted!!
03-21 07:35:45.299  6275  6275 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 07:35:45.299  6275  6275 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 07:35:45.299  6275  6275 D AndroidRuntime: readGMSProperty: end
03-21 07:35:45.299  6275  6275 D AndroidRuntime: addProductProperty: start
,03-21 07:35:45.459  6275  6275 E AffinityControl: AffinityControl: registerfunction enter,
,03-21 07:35:45.489  6275  6275 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,03-21 07:35:45.499  1017  3426 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 07:35:45.499  1017  3426 D PackageManager: START PACKAGE DELETE: observer{993106449}
03-21 07:35:45.499  1017  3426 D PackageManager: pkg{<packageName>}
03-21 07:35:45.499  1017  3426 D PackageManager: user{0}
03-21 07:35:45.499  1017  3426 D PackageManager: caller{2000}
03-21 07:35:45.499  1017  3426 D PackageManager: flags{2}
03-21 07:35:45.499  1017  3426 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 07:35:45.499  1017  3426 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 07:35:45.499  1017  3426 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 07:35:45.499  1017  3426 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-21 07:35:45.499  1017  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
03-21 07:35:45.499  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 07:35:45.499  1017  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-21 07:35:45.509  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled,
03-21 07:35:45.509  1017  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-21 07:35:45.509  1017  1055 D PackageManager: !@killApplicatoin: 10167, uninstall pkg,
,03-21 07:35:45.519  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-21 07:35:45.519  1017  1042 I ActivityManager: Killing 6218:com.test.thalitest/u0a167 (adj 9): stop com.test.thalitest cause uninstall pkg
,03-21 07:35:45.639  1017  3009 W ActivityManager: Spurious death for ProcessRecord{b35f776 6218:com.test.thalitest/u0a167}, curProc for 6218: null
,03-21 07:35:45.649  1017  1055 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-21 07:35:45.679  1017  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-21 07:35:45.699  4761  4761 I art     : Explicit concurrent mark sweep GC freed 2115(129KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 851us total 32.811ms
,03-21 07:35:45.719  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:35:45.729  1811  1811 E SamsungIME: mOCRHelper is null
,03-21 07:35:45.739  1876  2032 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 07:35:45.739  5690  5690 I art     : Explicit concurrent mark sweep GC freed 16279(1782KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 4MB/6MB, paused 1.071ms total 81.717ms
,03-21 07:35:45.769  2850  2850 I art     : Explicit concurrent mark sweep GC freed 20738(1305KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 965us total 95.953ms
,03-21 07:35:45.779  1017  1122 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-21 07:35:45.779  1017  1122 D NtpTrustedTime: currentTimeMillis() cache hit
03-21 07:35:45.779  1017  1122 V NetworkStats: performPollLocked(flags=0x3)
,03-21 07:35:45.779  1017  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
03-21 07:35:45.779  1017  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-21 07:35:45.789  1017  1122 V NetworkStats: performPollLocked() took 15ms
03-21 07:35:45.789  1017  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:35:45.799  3952  3952 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 21 07:35:45 GMT+01:00 2016
,03-21 07:35:45.809  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:35:45.809  1017  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 07:35:45.819  1017  3426 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-21 07:35:45.819  1017  1361 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:45.819  1017  3426 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4261, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-21 07:35:45.819  1017  1361 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:45.819  1017  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-21 07:35:45.829  1017  3426 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-21 07:35:45.829  1017  3426 D BatteryService: stay LED for fully charged
03-21 07:35:45.829  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 07:35:45.829  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-21 07:35:45.829  1017  1041 W TextServicesManagerService: no available spell checker services found
03-21 07:35:45.839  3952  3952 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
03-21 07:35:45.839  1017  1721 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
03-21 07:35:45.839  1017  1721 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,03-21 07:35:45.849  1017  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.849  1017  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.849  1017  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.849  1017  1721 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:45.849  3952  3952 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-21 07:35:45.859  3952  3952 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-21 07:35:45.859  6291  6291 E Zygote  : MountEmulatedStorage()
03-21 07:35:45.859  3952  3952 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-21 07:35:45.869  6291  6291 I libpersona: KNOX_SDCARD checking this for 10090
03-21 07:35:45.859  6291  6291 E Zygote  : v2
03-21 07:35:45.869  6291  6291 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:45.869  6291  6291 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:45.869  6291  6291 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:45.869  1017  1721 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6291 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-21 07:35:45.869  6291  6291 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:35:45.889  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-21 07:35:45.889  5903  5903 D Compatibility: onReceive() it will make start service
,03-21 07:35:45.899  6291  6291 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:35:45.899  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-21 07:35:45.899  6291  6291 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:45.909  1017  1017 I art     : Explicit concurrent mark sweep GC freed 49334(3MB) AllocSpace objects, 67(1072KB) LOS objects, 33% free, 22MB/33MB, paused 3.074ms total 230.324ms
03-21 07:35:45.909  1017  1055 I art     : WaitForGcToComplete blocked for 211.660ms for cause Explicit
,03-21 07:35:45.909  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-21 07:35:45.929  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:45.929  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.929  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.929  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:45.939  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:35:45.939  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-21 07:35:45.939  6306  6306 E Zygote  : MountEmulatedStorage(),
03-21 07:35:45.949  6306  6306 E Zygote  : v2
,03-21 07:35:45.949  6306  6306 I libpersona: KNOX_SDCARD checking this for 10032
03-21 07:35:45.949  6306  6306 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:35:45.949  6306  6306 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:45.949  6306  6306 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:35:45.949  6306  6306 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-21 07:35:45.949  1017  1622 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6306 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-21 07:35:45.959  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:45.969  1444  1444 D RegisteredServicesCache: empty dynamic service
,03-21 07:35:45.979  1017  1361 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:45.979  1017  1361 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:45.979  1017  1361 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-21 07:35:45.979  1017  3426 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-21 07:35:45.979  1017  3426 D SecContentProvider2: mCursor = null
,03-21 07:35:45.989  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.989  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.989  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:45.989  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:45.989  6306  6306 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:45.989  6306  6306 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:45.989  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:45.999  5903  6321 D Compatibility: onHandleIntent(),
,03-21 07:35:45.999  5903  6321 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-21 07:35:45.999  1017  1017 D RCPManagerService: PackageReceiver onReceive()
03-21 07:35:45.999  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-21 07:35:45.999  5903  6321 D Compatibility: found: 2
03-21 07:35:45.999  5903  6321 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-21 07:35:45.999  5903  6321 D Compatibility: skipping ResolveInfo{13059820 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-21 07:35:45.999  5903  6321 D Compatibility: considering ResolveInfo{167bb5d9 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
,03-21 07:35:45.999  5903  6321 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
03-21 07:35:45.999  5903  6321 D Compatibility: enabling receiver ResolveInfo{2eabb9e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-21 07:35:45.999  6322  6322 E Zygote  : MountEmulatedStorage()
,03-21 07:35:45.999  6322  6322 E Zygote  : v2
03-21 07:35:45.999  6322  6322 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:35:45.999  6322  6322 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:46.009  6322  6322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:46.009  6322  6322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-21 07:35:46.009  1017  1622 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:35:46.009  6322  6322 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:35:46.019  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-21 07:35:46.029  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-21 07:35:46.029  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.039  5903  6321 D Compatibility: enabling receiver ResolveInfo{3d50367f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-21 07:35:46.049  6322  6322 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.049  6322  6322 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.049  3952  6290 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-21 07:35:46.049  3952  6290 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
03-21 07:35:46.059  5903  6321 D Compatibility: enabling receiver ResolveInfo{30fc164c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-21 07:35:46.059  6291  6291 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-21 07:35:46.059  6291  6291 D elm:15121: ELMEngine.ELMEngine( context ).
03-21 07:35:46.059  6291  6291 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-21 07:35:46.059  1017  1721 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.059  1017  1721 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.059  1017  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 07:35:46.069  5903  6321 D Compatibility: enabling receiver ResolveInfo{34e8d695 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-21 07:35:46.079  5903  6321 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-21 07:35:46.079  1017  3009 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.079  1017  3009 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.079  1017  3009 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-21 07:35:46.079  3952  3952 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-21 07:35:46.089  6291  6291 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-21 07:35:46.089  2850  6337 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-21 07:35:46.109  6291  6291 D elm:15121: ElmAgentService : onCreate()
,03-21 07:35:46.109  6291  6338 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-21 07:35:46.109  6291  6338 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-21 07:35:46.109  6291  6338 D elm:15121: MDMBridge.getInstance()
03-21 07:35:46.109  6291  6338 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-21 07:35:46.109  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.109  6291  6338 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-21 07:35:46.119  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.119  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.119  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.129  6340  6340 E Zygote  : MountEmulatedStorage(),
03-21 07:35:46.129  6340  6340 E Zygote  : v2,
03-21 07:35:46.129  6340  6340 I libpersona: KNOX_SDCARD checking this for 10055
03-21 07:35:46.129  6340  6340 I libpersona: KNOX_SDCARD not a persona
03-21 07:35:46.139  6322  6322 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:35:46.139  6340  6340 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:35:46.139  1017  1622 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6340 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-21 07:35:46.139  6340  6340 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:46.139  6340  6340 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:35:46.139  1017  1484 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.139  1017  1484 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.139  1017  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,03-21 07:35:46.149  6291  6291 D elm:15121: ElmAgentService : onDestroy().
,03-21 07:35:46.149  1017  1055 I art     : Explicit concurrent mark sweep GC freed 8870(438KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 4.032ms total 237.454ms
,03-21 07:35:46.149  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.149  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.149  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.149  1017  1622 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.159  6356  6356 E Zygote  : MountEmulatedStorage()
03-21 07:35:46.159  6356  6356 E Zygote  : v2
,03-21 07:35:46.159  6356  6356 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:35:46.159  6356  6356 I libpersona: KNOX_SDCARD not a persona
03-21 07:35:46.159  6356  6356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:46.169  6356  6356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:46.169  6356  6356 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:35:46.169  1017  1622 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6356 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-21 07:35:46.179  6340  6340 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.179  6340  6340 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.189  6306  6363 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-21 07:35:46.189  6306  6363 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-21 07:35:46.189  1017  1622 I ActivityManager: Killing 5392:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-21 07:35:46.199   319   319 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 07:35:46.199  5888  5888 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-21 07:35:46.199  5888  5888 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-21 07:35:46.199  1017  1077 I ActivityManager: Killing 5302:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,03-21 07:35:46.209  6356  6356 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.209  6356  6356 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.209  1017  3426 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.209  1017  3426 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.209  1017  3426 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-21 07:35:46.219  6306  6363 D SPPClientService: PushLog.txt file is not deleted.
,03-21 07:35:46.219  6306  6363 D SPPClientService: PushLog.txt file is not deleted.
03-21 07:35:46.219  6306  6363 D SPPClientService: ============PushLog. stop!
,03-21 07:35:46.229  5318  5318 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-21 07:35:46.229  1017  1721 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.229  1017  1721 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.229  1017  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.239  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.239  1017  1706 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.239  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.259  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 07:35:46.269  4216  4216 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-21 07:35:46.269  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.269  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.269  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-21 07:35:46.279  6340  6340 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-21 07:35:46.279  6356  6375 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,03-21 07:35:46.279  6356  6375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,03-21 07:35:46.289  4216  6374 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-21 07:35:46.289  4216  6374 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,03-21 07:35:46.299  1017  1055 D PackageManager: delete codoeFile: 
,03-21 07:35:46.299  1017  1055 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-21 07:35:46.299  1017  1055 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-21 07:35:46.299  1017  1055 D PackageManager: result of delete: 1{993106449}
,03-21 07:35:46.309  6275  6275 D AndroidRuntime: Shutting down VM
,03-21 07:35:46.309  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.309  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.309  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.309  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.309  1017  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 07:35:46.309  1017  1055 D PackageManager: userId{-1}
03-21 07:35:46.309  1017  1055 D PackageManager: andCode{true}
,03-21 07:35:46.309  6340  6340 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-21 07:35:46.309  6340  6340 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-21 07:35:46.309  6340  6340 D UserAnalysis: Create SecureDbHelper
,03-21 07:35:46.319  6340  6340 D IntelligenceServiceApplication: onCreate()
,03-21 07:35:46.319  1017  3009 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.319  1017  3009 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.319  1017  3009 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
03-21 07:35:46.319  6340  6340 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-21 07:35:46.319  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.329  6356  6356 D AcmsService: Enter Oncreate
03-21 07:35:46.329  6356  6356 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
03-21 07:35:46.329  6356  6356 D AcmsService: creating AcmsCore
03-21 07:35:46.329  6356  6356 D AcmsCore: AcmsCore.getAcmsCore() - Enter
03-21 07:35:46.329  6356  6356 D AcmsCore: AcmsCore
,03-21 07:35:46.329  6356  6356 D AcmsCore: init
03-21 07:35:46.329  6356  6356 D AcmsCore: Looper handler is not null
03-21 07:35:46.329  6356  6356 D AcmsCore: Post to AcmsCoreHandler
03-21 07:35:46.329  6356  6356 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
03-21 07:35:46.329  6356  6356 D AcmsServiceMonitor: Incrementing - Counter value: 1
03-21 07:35:46.329  6356  6356 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,03-21 07:35:46.329  6356  6356 D AcmsService: onStartCommand
03-21 07:35:46.329  6356  6356 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
03-21 07:35:46.329  6356  6356 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
03-21 07:35:46.329  6356  6356 D AcmsServiceMonitor: Incrementing - Counter value: 2
03-21 07:35:46.329  6356  6356 D AcmsService: Incremented Counter Value : onStartCommand
,03-21 07:35:46.329  6340  6340 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-21 07:35:46.329  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:35:46.329  6356  6376 D AcmsCertificateMngr: AcmsCertificateMngr
,03-21 07:35:46.339  6356  6376 D AcmsRevocationMngr: AcmsRevocationMngr
,03-21 07:35:46.339  1017  1216 I TactileAssist: enable value -1
,03-21 07:35:46.339  1017  1216 I TactileAssist: internal enable value -1
03-21 07:35:46.339  1017  1216 I TactileAssist: intensity value -1
03-21 07:35:46.339  1017  1216 I TactileAssist: saveAppList value true
,03-21 07:35:46.349  1017  1216 I TactileAssist: List of disabled apps :
,03-21 07:35:46.359  6356  6356 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,03-21 07:35:46.359  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 07:35:46.359  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:35:46.359  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:35:46.359  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-21 07:35:46.359  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.369  1017  1352 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.369  1017  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.369  1017  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.379  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-21 07:35:46.379  5027  5027 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:35:46.389  1017  1621 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:35:46.389  1017  1621 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-21 07:35:46.389  1017  1621 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-21 07:35:46.389  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 07:35:46.389  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 07:35:46.389  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 07:35:46.399  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.399  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 07:35:46.399  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.399  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:35:46.399  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:35:46.399  1017  2718 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicy: uID is 10167
03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 07:35:46.399  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 07:35:46.399  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 07:35:46.409  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 07:35:46.409  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-21 07:35:46.409  1017  3009 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.409  1017  3009 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.409  1017  3009 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-21 07:35:46.409  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 07:35:46.409  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:35:46.409  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.419  6356  6356 D AcmsService: Inside handle Intent
03-21 07:35:46.419  6356  6356 D AcmsService: App removed - package name: com.test.thalitest
03-21 07:35:46.419  6356  6356 D AcmsCore: Post to AcmsCoreHandler
03-21 07:35:46.419  6356  6356 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
03-21 07:35:46.419  6356  6356 D AcmsServiceMonitor: Incrementing - Counter value: 3
03-21 07:35:46.419  6356  6356 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
03-21 07:35:46.419  6356  6356 D AcmsService: Decremented Counter Value : handleStartIntent
03-21 07:35:46.419  6356  6356 D AcmsServiceMonitor: Decrementing - Counter value: 2
,03-21 07:35:46.419  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 07:35:46.419  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 07:35:46.429  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 07:35:46.429  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-21 07:35:46.429  2850  6337 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 343 ms] updated apps [took 343 ms] 
,03-21 07:35:46.439  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,03-21 07:35:46.439  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-21 07:35:46.439  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-21 07:35:46.439  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,03-21 07:35:46.439  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,03-21 07:35:46.449  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,03-21 07:35:46.449  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-21 07:35:46.449  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-21 07:35:46.449  2630  2630 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 07:35:46.449  2630  2829 D HeadsetStateMachine: Disconnected process message: 10
,03-21 07:35:46.459  1017  1041 W libprocessgroup: failed to open /acct/uid_10146/pid_5392/cgroup.procs: No such file or directory
,03-21 07:35:46.459  1017  1041 W libprocessgroup: failed to open /acct/uid_10035/pid_5302/cgroup.procs: No such file or directory
,03-21 07:35:46.459  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 07:35:46.459  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 07:35:46.459  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-21 07:35:46.459  1170  1170 D SViewCoverView: level :100 plugged : 2
,03-21 07:35:46.459  6340  6340 D BluetoothAdapter: cancelDiscovery
,03-21 07:35:46.469  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.469  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.469  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.469  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.479  6384  6384 E Zygote  : MountEmulatedStorage()
03-21 07:35:46.479  6384  6384 E Zygote  : v2
03-21 07:35:46.479  6384  6384 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:35:46.479  6384  6384 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:46.479  6384  6384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:46.479  1017  1556 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6384 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-21 07:35:46.489  6384  6384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-21 07:35:46.489  6384  6384 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 07:35:46.489  1017  1159 D TaskPersister: removeObsoleteFile: deleting file=59_task.xml
,03-21 07:35:46.489  1017  1159 D TaskPersister: removeObsoleteFile: deleting file=58_task.xml
,03-21 07:35:46.499  1017  1017 I MotionRecognitionService: Plugged
,03-21 07:35:46.499  2630  2643 D BluetoothAdapterProperties: mDiscovering is false
,03-21 07:35:46.499  1793  1793 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
03-21 07:35:46.499  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-21 07:35:46.499  2630  2643 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
,03-21 07:35:46.499  6340  6340 D BluetoothAdapter: cancelDiscovery = true
03-21 07:35:46.499  6340  6340 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,03-21 07:35:46.509  1017  1352 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.509  1017  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.509  1017  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.509  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-21 07:35:46.509  6340  6340 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-21 07:35:46.509  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.509  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.509  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.509  1017  1556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.519  6384  6384 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 07:35:46.519  6384  6384 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.519  6275  6275 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-21 07:35:46.529  6399  6399 E Zygote  : MountEmulatedStorage(),
,03-21 07:35:46.529  6399  6399 E Zygote  : v2
,03-21 07:35:46.529  6399  6399 I libpersona: KNOX_SDCARD checking this for 1000
03-21 07:35:46.529  6399  6399 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:46.539  6399  6399 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:46.539  1017  1556 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6399 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-21 07:35:46.539  6399  6399 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:46.539  6399  6399 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 07:35:46.549  1017  1321 E Watchdog: !@Sync 7
03-21 07:35:46.549  1017  1216 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.549  1017  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.549  1017  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.549  1017  1556 I ActivityManager: Killing 4688:com.google.android.music:main/u0a108 (adj 15): empty #31
,03-21 07:35:46.559  1626  1626 I ConfigService: onCreate
,03-21 07:35:46.559  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.559  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-21 07:35:46.559  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.559  1626  1626 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
03-21 07:35:46.559  1793  1793 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-21 07:35:46.559  6399  6399 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.559  6399  6399 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.569  6384  6384 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 07:35:46.579  1626  1626 I ConfigService: onBind returning update interface
,03-21 07:35:46.579  1626  1626 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
03-21 07:35:46.579  1626  1626 I ConfigService: onBind returning config service
,03-21 07:35:46.589  1626  1626 I ConfigService: onDestroy
,03-21 07:35:46.589  6399  6399 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,03-21 07:35:46.589  1017  1706 D SecContentProvider2: uri = -1 selection = getSealedState
,03-21 07:35:46.589  1017  1706 D SecContentProvider2: mCursor = null
,03-21 07:35:46.589  6399  6399 I PopupuiReceiver_KNOX: getSealedState : true
,03-21 07:35:46.599  1017  1216 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
03-21 07:35:46.599  1017  1216 D SecContentProvider2: mCursor = null
,03-21 07:35:46.599  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.599  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.599  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.599  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.599  6399  6399 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,03-21 07:35:46.599  1017  1556 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
03-21 07:35:46.599  1017  1556 D SecContentProvider2: mCursor = null
03-21 07:35:46.599  6399  6399 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
03-21 07:35:46.599  6399  6399 D PopupuiReceiver: Action package removed
,03-21 07:35:46.609  6416  6416 E Zygote  : MountEmulatedStorage()
,03-21 07:35:46.609  6416  6416 I libpersona: KNOX_SDCARD checking this for 10011
03-21 07:35:46.609  6416  6416 E Zygote  : v2
03-21 07:35:46.609  6416  6416 I libpersona: KNOX_SDCARD not a persona
03-21 07:35:46.609  6416  6416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-21 07:35:46.609  6416  6416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-21 07:35:46.609  1017  3009 I ActivityManager: Start proc com.google.android.gms.ui for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver: pid=6416 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-21 07:35:46.619  6416  6416 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-21 07:35:46.619  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.619  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.619  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.619  1017  3009 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 07:35:46.619  6384  6384 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-21 07:35:46.629  1017  3426 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
03-21 07:35:46.629  1017  3426 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,03-21 07:35:46.629   311   311 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 22.900ms
,03-21 07:35:46.639  6416  6416 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.639  6416  6416 D ActivityThread: Added TimaKeyStore provider
,03-21 07:35:46.649   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.541ms,
,03-21 07:35:46.669   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 567us total 16.301ms
,03-21 07:35:46.679  6431  6431 E Zygote  : MountEmulatedStorage(),
03-21 07:35:46.679  6431  6431 E Zygote  : v2
03-21 07:35:46.679  6431  6431 I libpersona: KNOX_SDCARD checking this for 10145
03-21 07:35:46.679  6431  6431 I libpersona: KNOX_SDCARD not a persona
,03-21 07:35:46.679  1017  3009 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6431 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 07:35:46.679  1017  3009 I ActivityManager: Killing 5606:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-21 07:35:46.679  6431  6431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-21 07:35:46.689  6431  6431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-21 07:35:46.689  6431  6431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 07:35:46.699  1017  1721 W ActivityManager: userId = 0, bbcId = -10000
,03-21 07:35:46.699  1017  1721 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-21 07:35:46.699  1017  1721 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-21 07:35:46.709  6052  6052 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
03-21 07:35:46.709  6052  6052 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,03-21 07:35:46.709  1017  1706 W ActivityManager: userId = 0, bbcId = -10000
03-21 07:35:46.709  1017  1706 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 07:35:46.709  1017  1706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,03-21 07:35:46.719  6416  6416 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 07:35:46.719  6416  6416 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 07:35:46.719  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 07:35:46.719  6431  6431 D ActivityThread: Added TimaKeyStore provider
03-21 07:35:46.729  6052  6052 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
03-21 07:35:46.729  6052  6446 I FilterInstaller: FilterPackageService : ACTION_REMOVED
03-21 07:35:46.739  6052  6446 D FilterUnInstaller: before removeFromFS
03-21 07:35:46.739  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.739  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.739  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.739  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 07:35:46.749  6447  6447 E Zygote  : MountEmulatedStorage()

```
