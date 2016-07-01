#### Test 757892680c366d1_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
,07-01 12:10:46.554   298   298 E SMD     : DCD ON
07-01 12:10:46.874  7703  7703 D AndroidRuntime: 
07-01 12:10:46.874  7703  7703 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:10:46.884  7703  7703 D AndroidRuntime: CheckJNI is OFF
07-01 12:10:46.884  7703  7703 D AndroidRuntime: readGMSProperty: start
07-01 12:10:46.884  7703  7703 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:10:46.884  7703  7703 D AndroidRuntime: readGMSProperty: end
07-01 12:10:46.884  7703  7703 D AndroidRuntime: addProductProperty: start
07-01 12:10:47.014  7703  7703 E AffinityControl: AffinityControl: registerfunction enter
07-01 12:10:47.034  7703  7703 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 12:10:47.044   912  1460 E PersonaManagerService: inState():  stateMachine is null !!
07-01 12:10:47.044   912  1460 I PersonaManagerService: PersonaId don't exist
07-01 12:10:47.044   912  1460 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 12:10:47.044   912  1460 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-01 12:10:47.044   912  1460 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 12:10:47.044   912  1460 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-01 12:10:47.054   912  1460 W ActivityManager: mDVFSHelper.acquire()
07-01 12:10:47.054   912  1460 D FocusedStackFrame: Set to : 0
07-01 12:10:47.054   912  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:47.054   912  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:47.054   912  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:47.054   912  1460 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:47.094  7717  7717 E Zygote  : MountEmulatedStorage()
07-01 12:10:47.094  7717  7717 I libpersona: KNOX_SDCARD checking this for 10079
07-01 12:10:47.094  7717  7717 E Zygote  : v2
07-01 12:10:47.094  7717  7717 I libpersona: KNOX_SDCARD not a persona
07-01 12:10:47.094   912  1460 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7717 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 12:10:47.114  7717  7717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:10:47.114  7703  7703 D AndroidRuntime: Shutting down VM
07-01 12:10:47.114  7717  7717 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:10:47.114  7717  7717 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 12:10:47.144  7717  7717 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:10:47.144  7717  7717 D ActivityThread: Added TimaKeyStore provider
07-01 12:10:47.154   912   912 V ActivityManager: Display changed displayId=0
07-01 12:10:47.174   912  3320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:47.174  7717  7717 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-01 12:10:47.174  1461  1461 D SurfaceWidgetView: destroyHardwareResources():1021209394
07-01 12:10:47.184   912  3320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:47.254   265  2010 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-01 12:10:47.254   265   399 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-01 12:10:47.254  7717  7717 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 12:10:47.254  7717  7717 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-01 12:10:47.264  1461  1461 D Launcher: onTrimMemory. Level: 20
07-01 12:10:47.264  1461  1461 V ActivityThread: updateVisibility : ActivityRecord{3d86f952 token=android.os.BinderProxy@b1dfc72 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 12:10:47.264  1787  1804 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-01 12:10:47.274  7717  7717 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2974-2977)
07-01 12:10:47.274  7717  7717 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:10:47.294  7717  7717 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1459dafc}
07-01 12:10:47.294  7717  7717 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:10:47.294  7717  7717 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:10:47.324  7717  7717 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:10:47.324  7717  7717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:10:47.324  7717  7717 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 12:10:47.344  7717  7717 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 12:10:47.344  7717  7717 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-01 12:10:47.344  7717  7717 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-01 12:10:47.354  7717  7717 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-01 12:10:47.354  7717  7717 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-01 12:10:47.354  7717  7717 I Adreno-EGL: Build Date: 11/19/14 Wed
07-01 12:10:47.354  7717  7717 I Adreno-EGL: Local Branch: mybranch5813579
07-01 12:10:47.354  7717  7717 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-01 12:10:47.354  7717  7717 I Adreno-EGL: Local Patches: NONE
07-01 12:10:47.354  7717  7717 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-01 12:10:47.494  7717  7754 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-01 12:10:47.524  7717  7717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:10:47.534  7717  7717 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 12:10:47.544  7717  7717 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-01 12:10:47.554  7717  7717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:10:47.554  7717  7717 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:10:47.614  7717  7717 D Activity: performCreate Call secproduct feature valuefalse
,07-01 12:10:47.614  7717  7717 D Activity: performCreate Call debug elastic valuetrue
,07-01 12:10:47.624  7717  7770 D OpenGLRenderer: Render dirty regions requested: true
,07-01 12:10:47.634   912   929 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 12:10:47.634   912   929 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 12:10:47.634   912   929 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-01 12:10:47.634   912   912 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 12:10:47.634   912   912 D PersonaManagerService: getPersonasForUser(): returning null!
,07-01 12:10:47.654   265   265 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,07-01 12:10:47.654  7717  7770 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 12:10:47.664  7717  7770 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3ca8060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-01 12:10:47.664  7717  7770 D OpenGLRenderer: Enabling debug mode 0
,07-01 12:10:47.674  7717  7717 V ActivityThread: updateVisibility : ActivityRecord{134e5e56 token=android.os.BinderProxy@3acf9e18 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-01 12:10:47.704  7717  7717 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3acf9e18 time:293406
,07-01 12:10:47.724   912  1038 W ActivityManager: mDVFSHelper.release()
07-01 12:10:47.724   912  1038 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{798d435 u0 com.test.thalitest/.MainActivity t23} time:293424
,07-01 12:10:47.724   912  1038 D MultiWindowConverter: This application or window do not support multiwindow
,07-01 12:10:47.764  7717  7717 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7717
,07-01 12:10:47.844  7717  7717 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 12:10:47.954  7717  7774 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358971776
,07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 12:10:47.964  7717  7774 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d90906 added. We now have 1 listener(s)
,07-01 12:10:47.964  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-01 12:10:47.964  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-01 12:10:47.974  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 12:10:47.974  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-01 12:10:47.974  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b05f11d added. We now have 1 listener(s)
07-01 12:10:47.974  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:47.994  7717  7774 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-01 12:10:47.994  7717  7774 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
07-01 12:10:47.994  7717  7774 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-01 12:10:47.994  7717  7774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 12:10:47.994  7717  7774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-01 12:10:48.004   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:48.004  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 12:10:48.004  7717  7774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:10:48.004  7717  7774 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 12:10:48.004  7717  7774 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 12:10:48.004   912  1719 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:48.014  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:10:48.014   912  1533 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:48.014  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:10:48.024  7717  7717 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 12:10:48.794  7717  7784 W jxcore-log: Initializing JXcore engine
,07-01 12:10:48.794  7717  7784 W jxcore-log: JXcore engine is ready
,07-01 12:10:48.844  1960  1960 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-01 12:10:48.844  1960  1960 E audit   : type=1400 msg=audit(1467367848.844:203): avc:  denied  { ioctl } for  pid=7784 comm="Thread-1268" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-01 12:10:48.844  1960  1960 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-01 12:10:48.844  1960  1960 E audit   : 
07-01 12:10:48.844   912  1026 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-01 12:10:48.844   912  1026 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-01 12:10:48.844   912  1026 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-01 12:10:48.844   912   997 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
07-01 12:10:48.844  1960  1960 E audit   : type=1300 msg=audit(1467367848.844:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=99ee08d8 items=0 ppid=331 ppcomm=main pid=7784 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1268" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-01 12:10:48.844  1960  1960 E audit   : type=1320 msg=audit(1467367848.844:203): 
07-01 12:10:48.844   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:48.844   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:48.844   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:48.844   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:10:48.864  7717  7784 W jxcore-log: Starting JXcore engine
,07-01 12:10:48.884   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:10:48.904   912   997 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 12:10:48.914  7785  7785 E Zygote  : MountEmulatedStorage()
,07-01 12:10:48.914  7785  7785 E Zygote  : v2
07-01 12:10:48.914  7785  7785 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:10:48.914  7785  7785 I libpersona: KNOX_SDCARD not a persona
,07-01 12:10:48.944  7785  7785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:10:48.944  7785  7785 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:10:48.944  7785  7785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:10:48.964  7717  7784 W jxcore-log: Platform android
07-01 12:10:48.964  7717  7784 W jxcore-log: 
,07-01 12:10:48.964  7717  7784 W jxcore-log: Process ARCH arm
07-01 12:10:48.964  7717  7784 W jxcore-log: 
,07-01 12:10:49.004  7785  7785 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:10:49.004  7785  7785 D ActivityThread: Added TimaKeyStore provider
,07-01 12:10:49.034  7785  7785 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-01 12:10:49.044  7785  7785 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-01 12:10:49.044  7785  7785 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-01 12:10:49.054   912  1094 I ActivityManager: Killing 6216:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,07-01 12:10:49.064   912  3320 D SSRM:n  : SIOP:: AP = 330, PST = 325, CUR = 450
,07-01 12:10:49.124   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:10:49.194  7717  7784 I jxcore-log: JXcore Cordova bridge is ready!
07-01 12:10:49.194  7717  7784 I jxcore-log: 
,07-01 12:10:49.194  7717  7784 W jxcore-log: JXcore engine is started
,07-01 12:10:49.204  7717  7774 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 12:10:49.204  7717  7717 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 12:10:49.544   298   298 E SMD     : DCD ON
,07-01 12:10:49.884   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:10:50.244   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:10:50.884   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:10:51.884   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:10:52.554   298   298 E SMD     : DCD ON
,07-01 12:10:52.884   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:10:53.564   912  1042 I PowerManagerService: [PWL] Off : 75s ago
,07-01 12:10:53.884   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-01 12:10:55.554   298   298 E SMD     : DCD ON
,07-01 12:10:57.104   912  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-01 12:10:58.554   298   298 E SMD     : DCD ON
,07-01 12:10:58.994  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-01 12:10:58.994  7717  7784 I jxcore-log: 
,07-01 12:10:58.994  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-01 12:10:58.994  7717  7784 I jxcore-log: 
,07-01 12:10:58.994   912  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:58.994  7717  7784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:10:59.004  7717  7784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-01 12:10:59.004  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-01 12:10:59.004  7717  7784 I jxcore-log: 
,07-01 12:10:59.004  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-01 12:10:59.004  7717  7784 I jxcore-log: 
,07-01 12:10:59.114   912  3320 D SSRM:n  : SIOP:: AP = 360, PST = 328, CUR = 450
,07-01 12:10:59.324  7717  7784 I jxcore-log: Unit Test app is loaded
07-01 12:10:59.324  7717  7784 I jxcore-log: 
,07-01 12:10:59.334  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:10:59.334  7717  7784 I jxcore-log: 
,07-01 12:10:59.334  7717  7784 I jxcore-log: My device name is: samsung-SM-N9005
07-01 12:10:59.334  7717  7784 I jxcore-log: 
,07-01 12:10:59.344  7717  7784 I jxcore-log: WARN testUtils: myNameCallback not set!
07-01 12:10:59.344  7717  7784 I jxcore-log: 
,07-01 12:10:59.344  7717  7717 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-01 12:10:59.414  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-01 12:10:59.414  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3972477 added. We now have 2 listener(s)
07-01 12:10:59.414  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:59.414  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
,07-01 12:10:59.414  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:10:59.414  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:10:59.414  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:10:59.414  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3972477 removed from the list
,07-01 12:10:59.424  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-01 12:10:59.424  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f80f8e4 added. We now have 2 listener(s)
,07-01 12:10:59.424  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:59.424  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:10:59.424  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:10:59.424  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:10:59.424  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:10:59.424  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f80f8e4 removed from the list
,07-01 12:10:59.434  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:10:59.434  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a17a14d added. We now have 2 listener(s)
07-01 12:10:59.434  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:10:59.434  7717  7774 I WifiManager: packageName : com.test.thalitest
,07-01 12:10:59.434   912  1719 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 12:10:59.434   912  1719 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 12:10:59.434   912  1719 D SecContentProvider2: mCursor = null
,07-01 12:10:59.434   912  1719 D WifiService: setWifiEnabled: false pid=7717, uid=10079
07-01 12:10:59.434   912  1719 D SettingsProvider: name = wifi_on
,07-01 12:10:59.444  7717  7774 D BluetoothAdapter: disable()
,07-01 12:10:59.444   912  1533 D SettingsProvider: name = bluetooth_on
,07-01 12:10:59.444   912  1149 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-01 12:10:59.444  1304  1304 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 12:10:59.444  1304  1304 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-01 12:10:59.444  1304  1304 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-01 12:10:59.454   912  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-01 12:10:59.454  7717  7774 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:10:59.454  3260  3312 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-01 12:10:59.454  3260  3312 D BluetoothAdapterProperties: Setting state to 13
07-01 12:10:59.454  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:10:59.454  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:10:59.454  3260  3312 D BluetoothAdapterService: updateAdapterState state is 13
,07-01 12:10:59.454   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.454   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.454   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c7b0764, r.packageName :com.android.bluetooth
,07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:59.454  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:10:59.454  7717  7774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:59.454  7717  7774 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:10:59.454  1304  1304 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 12:10:59.454  3260  3260 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-01 12:10:59.454  3260  3260 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@162f0f8e, channel: 19, state: LISTENING
07-01 12:10:59.454  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:10:59.454  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,07-01 12:10:59.454  3260  3260 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@162f0f8e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cde44b7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e9b13afmSocket: android.net.LocalSocket@3060e3bc impl:android.net.LocalSocketImpl@3e0c6f45 fd:FileDescriptor[80]
07-01 12:10:59.454  3260  3312 D BluetoothAdapterService: terminating service from this receiver
07-01 12:10:59.454  3260  3260 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3060e3bc impl:android.net.LocalSocketImpl@3e0c6f45 fd:FileDescriptor[80]
,07-01 12:10:59.454  3260  3312 D BluetoothAdapterProperties: onBluetoothDisable()
,07-01 12:10:59.464   912  1460 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.464   912  3696 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-01 12:10:59.464  3260  3312 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-01 12:10:59.464  3260  3315 D BluetoothAdapterProperties: Scan Mode:20
,07-01 12:10:59.464  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-01 12:10:59.464  4719  4719 D BluetoothPbap: Proxy object disconnected
07-01 12:10:59.464  4719  4719 D PbapServerProfile: Bluetooth service disconnected
,07-01 12:10:59.464  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:10:59.464   912  1456 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.464  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:10:59.464   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.474  3260  3318 D bt_vendor: op for 7
,07-01 12:10:59.474  3260  3312 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-01 12:10:59.474  3260  6070 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-01 12:10:59.474  3260  3312 E bt-btif : cmd socket is not created
,07-01 12:10:59.474  3260  3316 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,07-01 12:10:59.474  3260  3318 D bt_upio : proc btwrite assertion
,07-01 12:10:59.474  3260  3312 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:10:59.484  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 12:10:59.484   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.484   912  1149 E native  : do suspend true
,07-01 12:10:59.484  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-01 12:10:59.484  3260  3316 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:10:59.484  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.484  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.484   912  1148 D WifiP2pService: InactiveState{ what=143375 }
,07-01 12:10:59.484  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.484  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:10:59.484   912  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 12:10:59.484  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.484  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.494  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.494  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.494  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.494  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.494  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.494  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.494  3260  3318 D bt_vendor: op for 7
,07-01 12:10:59.494  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:10:59.494   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:10:59.504  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.504  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.504  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.504  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:10:59.504   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:10:59.504  3260  3260 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@358f3bcb, channel: 5, state: LISTENING
,07-01 12:10:59.504  3260  3318 D bt_vendor: op for 7
07-01 12:10:59.504  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:10:59.504  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:10:59.504  3260  3260 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@358f3bcb, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@237bbfb6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3c367fa8mSocket: android.net.LocalSocket@2209bac1 impl:android.net.LocalSocketImpl@27518266 fd:FileDescriptor[78]
07-01 12:10:59.514  3260  3260 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2209bac1 impl:android.net.LocalSocketImpl@27518266 fd:FileDescriptor[78]
,07-01 12:10:59.514  3260  3260 I BtOppRfcommListener: stopping Accept Thread
07-01 12:10:59.514  3260  3260 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1453c9a7, channel: 12, state: LISTENING
07-01 12:10:59.514  3260  3260 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1453c9a7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ee2389, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@d47ee54mSocket: android.net.LocalSocket@3b3641fd impl:android.net.LocalSocketImpl@4e35ef2 fd:FileDescriptor[84]
,07-01 12:10:59.514  3260  3260 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3b3641fd impl:android.net.LocalSocketImpl@4e35ef2 fd:FileDescriptor[84]
07-01 12:10:59.514  3260  6070 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-01 12:10:59.514   912   912 I InputMethodManagerService: [BT Setting State] State =13
,07-01 12:10:59.514  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.514  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 12:10:59.514  1746  1746 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:10:59.514  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-01 12:10:59.524  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:10:59.524  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.524   912  1533 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:10:59.524  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
07-01 12:10:59.524  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
07-01 12:10:59.524  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 12:10:59.524   912   928 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 12:10:59.534  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 12:10:59.534   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:10:59.534   912  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:10:59.534   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:10:59.534   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-01 12:10:59.534   912  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
07-01 12:10:59.534  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-01 12:10:59.534   912   912 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 12:10:59.534   912  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-01 12:10:59.534   912  3696 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-01 12:10:59.534   912  3696 D ActivityManager: caller:android.app.ApplicationThreadProxy@37facdcd, r.packageName :com.android.settings
,07-01 12:10:59.544   912  1533 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.544   912   912 D WifiScanningService: SCAN_AVAILABLE : 1
,07-01 12:10:59.544   912   912 D RttService: SCAN_AVAILABLE : 1
07-01 12:10:59.544   912  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:10:59.544   912  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:10:59.544   912  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-01 12:10:59.554   912  1148 D WifiP2pService: InactiveState{ what=131204 }
07-01 12:10:59.554   912  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-01 12:10:59.554   912  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D QSpanel : label top:23
,07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:10:59.554  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 12:10:59.554   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.554   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:10:59.554   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:10:59.554   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-01 12:10:59.564   912  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-01 12:10:59.564   912  1038 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-01 12:10:59.564   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:10:59.564   912  1038 D WifiDisplayController: disconnect
07-01 12:10:59.564   912  1038 D WifiDisplayController: updateConnection
07-01 12:10:59.564   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:10:59.564   912  1038 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:10:59.564   912   912 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:10:59.564   912  1485 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.564   912  1148 D WifiP2pService: P2pDisablingState
,07-01 12:10:59.564   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.564   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:10:59.564   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:10:59.564   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-01 12:10:59.574   912  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-01 12:10:59.574   912  1148 D WifiP2pService: p2p socket connection lost
,07-01 12:10:59.574   912  1148 D WifiP2pService: P2pDisabledState
,07-01 12:10:59.574  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 12:10:59.574   912   928 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-01 12:10:59.574   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.574   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.574   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 12:10:59.574   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.574   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:10:59.574   912  1767 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.574  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 12:10:59.574   912  1767 I qtaguid : Tagging socket 392 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 912, getuid(): 1000
07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:10:59.574   912  1149 E native  : do suspend true
07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.574  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:10:59.584  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:10:59.584  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:10:59.584  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.584   912  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.584  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.584   912  1456 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.584   912  1767 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 12:10:59.584   912  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
07-01 12:10:59.584   912  1148 D WifiP2pService: DefaultState{ what=143375 }
,07-01 12:10:59.584  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:10:59.584  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-01 12:10:59.584   912  1336 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 12:10:59.584  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-01 12:10:59.594   912   929 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:10:59.594  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:10:59.594  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.594  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:10:59.594  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:10:59.594   912  3696 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-01 12:10:59.604   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:59.604   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:59.604   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:10:59.604   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:10:59.624   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:10:59.624   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-01 12:10:59.624   912  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-01 12:10:59.624   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-01 12:10:59.624   912  1151 D ConnectivityService: calling update connectivity
07-01 12:10:59.624   912  1036 D EntConnectivity: Not allowed due to - mEnabled false
07-01 12:10:59.624   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:59.624   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.624   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:10:59.624   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:10:59.624   912  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:10:59.624  1195  1612 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-01 12:10:59.624   912  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-01 12:10:59.624   912  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-01 12:10:59.624   912  1151 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:59.624   912  1151 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:59.624  1428  1428 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:10:59.624   912  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-01 12:10:59.624   912  1151 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
07-01 12:10:59.624   912  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-01 12:10:59.644  7845  7845 E Zygote  : MountEmulatedStorage()
07-01 12:10:59.644  7845  7845 E Zygote  : v2
07-01 12:10:59.644  7845  7845 I libpersona: KNOX_SDCARD checking this for 10140
07-01 12:10:59.644  7845  7845 I libpersona: KNOX_SDCARD not a persona
07-01 12:10:59.644   912  3696 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7845 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 12:10:59.654   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.654   912  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:10:59.654   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:10:59.654   912  1146 V NetworkStats: updateIfacesLocked()
07-01 12:10:59.654   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:10:59.654   912  1146 V NetworkStats: performPollLocked(flags=0x1)
07-01 12:10:59.654   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:10:59.654   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 12:10:59.654   912  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:10:59.654   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-01 12:10:59.654   912  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 12:10:59.654   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:10:59.654   912  1152 D Tethering: MasterInitialState.processMessage what=3
07-01 12:10:59.654   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:10:59.654   912  1151 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-01 12:10:59.654   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:10:59.654   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.654  1304  1304 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-01 12:10:59.654   912  1146 V NetworkStats: performPollLocked() took 4ms
07-01 12:10:59.654   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.654   912   912 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-01 12:10:59.654   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.654   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:10:59.654   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:10:59.674  7845  7845 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:10:59.674  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 12:10:59.674  7845  7845 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:10:59.674  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-01 12:10:59.674  1195  1195 D StatusBar.NetworkController: updateDataNetType()
07-01 12:10:59.674  7845  7845 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-01 12:10:59.674   912  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.674   912  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-01 12:10:59.674   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 12:10:59.674  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:10:59.674  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-01 12:10:59.674  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 12:10:59.674  3260  3312 D BtConfig.SecureMode: isSecureModeOn:false
07-01 12:10:59.674  3260  3312 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-01 12:10:59.674  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
07-01 12:10:59.674  3260  3312 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-01 12:10:59.674  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:10:59.674  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:10:59.674  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 12:10:59.674   912  1245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.674   912  1245 D ActivityManager: caller:android.app.ApplicationThreadProxy@42df3ef, r.packageName :com.android.bluetooth
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:59.674  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:10:59.674  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:10:59.674  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.684   912   929 I AudioService: getStreamVolume 3 index 70
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:10:59.684  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:10:59.684  3260  3260 D HeadsetService: Received stop request...Stopping profile...
07-01 12:10:59.684  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.684   912   912 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:10:59.684  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:10:59.684   912  3696 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.684   912  3696 D ActivityManager: caller:android.app.ApplicationThreadProxy@21bddefc, r.packageName :com.android.bluetooth
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 12:10:59.684  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:10:59.684   912  1245 D SecContentProvider2: uri = 14 selection = getSealedState
07-01 12:10:59.684   912  1245 D SecContentProvider2: mCursor = null
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 12:10:59.684   912  1689 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.684   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ab0e985, r.packageName :com.android.bluetooth
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:10:59.684  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:10:59.684  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:10:59.684  4719  4719 D HeadsetProfile: Bluetooth service disconnected
07-01 12:10:59.684  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-01 12:10:59.694   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.694   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@365823da, r.packageName :com.android.bluetooth
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:10:59.694   912  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.694   912  1456 D ActivityManager: caller:android.app.ApplicationThreadProxy@130fe00b, r.packageName :com.android.bluetooth
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.694   912   929 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.694   912  1533 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 12:10:59.694   912  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
07-01 12:10:59.694   912   929 D ActivityManager: caller:android.app.ApplicationThreadProxy@787eee8, r.packageName :com.android.bluetooth
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:10:59.694  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 12:10:59.694  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:10:59.694  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-01 12:10:59.694  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-01 12:10:59.694   912  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:10:59.694   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@f1b9901, r.packageName :com.android.bluetooth
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:10:59.694  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 12:10:59.694  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:10:59.704  1304  1304 I wpa_supplicant: Blacklist: Clear (all) 
07-01 12:10:59.704  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 12:10:59.704  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 12:10:59.704  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:10:59.704  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 12:10:59.704  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 12:10:59.704  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:10:59.704  3260  3312 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 12:10:59.704  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-01 12:10:59.704  3260  3260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 12:10:59.704  3260  3260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:10:59.704  3260  3260 D A2dpService: Received stop request...Stopping profile...
07-01 12:10:59.704  3260  3260 V Avrcp   : doQuit
07-01 12:10:59.704  3260  3491 D A2dpStateMachine: Exit Disconnected: -1
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:10:59.704  3260  3260 D Avrcp   : Unregistering previous receiver
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.704  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.704  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.704   912   912 D BluetoothA2dp: Proxy object disconnected
07-01 12:10:59.704   912   912 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 12:10:59.704  3260  3260 D HidService: Received stop request...Stopping profile...
07-01 12:10:59.704  3260  3260 D HidService: Stopping Bluetooth HidService
07-01 12:10:59.704  3260  3260 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:10:59.704  3260  3260 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-01 12:10:59.704  3260  3260 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:10:59.704  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.704  7845  7845 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:10:59.704  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.704  7845  7845 D ActivityThread: Added TimaKeyStore provider
07-01 12:10:59.704  3260  3260 D HealthService: Received stop request...Stopping profile...
07-01 12:10:59.704  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.714  3407  3407 D BluetoothA2dp: Proxy object disconnected
07-01 12:10:59.714  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.714  3260  3260 D PanService: Received stop request...Stopping profile...
07-01 12:10:59.714  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.714  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.714   912   912 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:10:59.714  3260  3260 D BluetoothMapService: Received stop request...Stopping profile...
07-01 12:10:59.714  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.714  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.714  4719  4719 D BluetoothA2dp: Proxy object disconnected
07-01 12:10:59.714  4719  4719 D A2dpProfile: Bluetooth service disconnected
07-01 12:10:59.714  4719  4719 D BluetoothInputDevice: Proxy object disconnected
07-01 12:10:59.714  4719  4719 D HidProfile: Bluetooth service disconnected
07-01 12:10:59.714  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.714  4719  4719 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:10:59.714  4719  4719 D PanProfile: Bluetooth service disconnected
07-01 12:10:59.714  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:10:59.724  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.724  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 12:10:59.724  1304  1304 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:10:59.724  3260  3260 D SapService: Received stop request...Stopping profile...
07-01 12:10:59.724  3260  3260 D SapService: Stopping Bluetooth SapService
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:10:59.724  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 12:10:59.724  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-01 12:10:59.724  3260  3260 D BluetoothA2dp: Proxy object disconnected
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-01 12:10:59.724  1304  1304 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-01 12:10:59.724  4719  4719 D BluetoothMap: Proxy object disconnected
07-01 12:10:59.724  4719  4719 D MapProfile: Bluetooth service disconnected
07-01 12:10:59.724  1304  1304 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-01 12:10:59.724  4719  4719 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-01 12:10:59.724  4719  4719 D SapProfile: Bluetooth service disconnected
07-01 12:10:59.724  1304  1304 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
07-01 12:10:59.724  1304  1304 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-01 12:10:59.724  3260  3493 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:10:59.724  3260  3260 I GKI_LINUX: GKI_exit_task 2 done
07-01 12:10:59.724  3260  3260 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 12:10:59.724  3260  3260 V Avrcp   : cleanup
07-01 12:10:59.724  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:10:59.724  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.724  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:10:59.724  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.724  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.724  3260  3260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:10:59.724  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:10:59.724  3260  3260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:10:59.724  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.724  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:10:59.724  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.724  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.724  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-01 12:10:59.734  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:10:59.734  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.734  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:10:59.734  3260  3260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:10:59.734  3260  3260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.734  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-01 12:10:59.734  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:10:59.734  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:10:59.734  3260  3260 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-01 12:10:59.734  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-01 12:10:59.734  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.734  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:10:59.734  3260  3312 D BluetoothAdapterProperties: Setting state to 10
07-01 12:10:59.734  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:10:59.734  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:10:59.734  3260  3260 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-01 12:10:59.734  3260  3312 D BluetoothAdapterService: updateAdapterState state is 10
07-01 12:10:59.734  3260  3260 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:10:59.734  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:10:59.734  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:10:59.734  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-01 12:10:59.734  3260  3312 I BluetoothAdapterState: Entering OffState
07-01 12:10:59.734  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.734  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-01 12:10:59.734  3260  3449 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:10:59.734  4719  4729 D Bluetoothsap: onBluetoothStateChange: up=false
07-01 12:10:59.734  4719  4729 D Bluetoothsap: Unbinding service...
07-01 12:10:59.734  4719  4731 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 12:10:59.734  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:10:59.734  4719  4735 D BluetoothMap: onBluetoothStateChange: up=false
07-01 12:10:59.744  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.744  1195  1195 D HotspotTile: onReceive : 0, 0
07-01 12:10:59.744  1195  1195 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
07-01 12:10:59.744  4719  4735 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-01 12:10:59.744   912  1036 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:10:59.744  4719  4729 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:10:59.744  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:10:59.744  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:10:59.744  1195  1195 I PhoneStatusBar: Icon Only
07-01 12:10:59.744  1195  1195 I StatusBar: Icon Only
07-01 12:10:59.744  3407  3679 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:10:59.754  1195  1195 D PanelView: There is/are notification(s) 
07-01 12:10:59.754  1195  1195 D PanelView: There is/are notification(s) 
07-01 12:10:59.754   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.754   912   912 I InputMethodManagerService: [BT Setting State] State =10
07-01 12:10:59.754   912   912 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-01 12:10:59.754  1972  1972 W Coffee - Trustlet: Trustlet Bluetooth attempted to change its canProvideTrust state to the current state (ignored).
07-01 12:10:59.754  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.754  1972  1972 I Coffee - BluetoothConnectionTracker: Bluetooth adapter off, revoking trust
07-01 12:10:59.754  1746  1746 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:10:59.754  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.764  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.764  7845  7845 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
07-01 12:10:59.764  1195  1195 D QSpanel : label top:23
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:10:59.764  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 12:10:59.764  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.774  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:10:59.774  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:10:59.774  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.774   912  1456 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:10:59.774  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 12:10:59.774   912  1336 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-01 12:10:59.774  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.774  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 12:10:59.774  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D QSpanel : label top:23
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:10:59.774  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 12:10:59.784  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.784  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.784  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.794  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.794  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.794  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.794  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.814  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 12:10:59.824  1304  1304 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:10:59.984  1304  1304 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 12:10:59.984   912  1146 V NetworkStats: performPollLocked(flags=0x1)
07-01 12:10:59.984   912  1152 D Tethering: InitialState.processMessage what=4
07-01 12:10:59.984  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 12:10:59.984   912  1152 E Tethering: No numeric data
07-01 12:10:59.984  1195  1195 D HotspotTile: updateTetherState():false, false
07-01 12:10:59.984   912  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:10:59.984   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:10:59.984   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.984   912  1146 V NetworkStats: performPollLocked() took 2ms
07-01 12:10:59.984   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:10:59.984   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.984   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:10:59.984   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:10:59.984   912  1114 V AlarmManager: waitForAlarm result :8
,07-01 12:10:59.994   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-01 12:10:59.994   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 12:10:59.994   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:10:59.994   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 12:10:59.994  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:10:59.994  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:10:59.994  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:10:59.994  1972  1972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:10:59.994  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:10:59.994  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-01 12:10:59.994  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:10:59.994  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:59.994  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 12:10:59.994  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:10:59.994  1195  1195 D HotspotTile: onReceive : 1, 0
,07-01 12:11:00.004  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:00.024  1195  1195 D QSpanel : label top:23
,07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:00.024  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=203 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.File.exists(File.java:363)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 12:11:00.024  7845  7845 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.e.b(PG:170)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024   912  1655 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=148 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.k.c(PG:583)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.e.b(PG:170)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.024  7845  7845 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.io.File.exists(File.java:363)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:11:00.024  7845  7845 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:11:00.024   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.024   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.024   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.054  7845  7874 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-01 12:11:00.064  7883  7883 E Zygote  : MountEmulatedStorage()
07-01 12:11:00.064  7883  7883 E Zygote  : v2
07-01 12:11:00.064  7883  7883 I libpersona: KNOX_SDCARD checking this for 10038
07-01 12:11:00.064  7883  7883 I libpersona: KNOX_SDCARD not a persona
07-01 12:11:00.074   912  1655 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7883 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 12:11:00.074   912  1655 I ActivityManager: Killing 6258:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,07-01 12:11:00.124  7883  7883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:00.124  7883  7883 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:00.124  7883  7883 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 12:11:00.154   912  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:00.154   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:00.154   912   912 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:00.154   912  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 12:11:00.154   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:00.154   912   912 I ApplicationPolicy: updateDataUsageMap
07-01 12:11:00.154   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:00.154   912  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-01 12:11:00.154   912   995 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:00.154   912   995 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:00.154   912  1456 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:00.164   912   929 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:00.164  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:00.174  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:00.184  7883  7883 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:00.184  7883  7883 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:00.184  1496  1496 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-01 12:11:00.194   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-01 12:11:00.274   912  1468 I art     : Explicit concurrent mark sweep GC freed 285488(16MB) AllocSpace objects, 78(15MB) LOS objects, 30% free, 36MB/52MB, paused 1.473ms total 133.240ms
,07-01 12:11:00.274   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 12:11:00.304  7883  7883 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-01 12:11:00.304  7883  7883 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-01 12:11:00.434  7883  7883 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-01 12:11:00.454  7717  7774 I WifiManager: packageName : com.test.thalitest
,07-01 12:11:00.454   912  1094 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 12:11:00.454   912  1094 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 12:11:00.454   912  1094 D SecContentProvider2: mCursor = null
,07-01 12:11:00.454   912  1094 D WifiService: setWifiEnabled: true pid=7717, uid=10079
07-01 12:11:00.454   912  1094 W ActivityManager: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:00.454   912  1094 W WifiService: Failed getting userId using ActivityManagerNative
07-01 12:11:00.454   912  1094 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:00.454   912  1094 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 12:11:00.454   912  1094 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-01 12:11:00.454   912  1094 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-01 12:11:00.454   912  1094 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-01 12:11:00.454   912  1094 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 12:11:00.454   912  1094 D SettingsProvider: name = wifi_on
,07-01 12:11:00.464   912  1149 E WifiHW  : ##################### set firmware type 0 #####################
,07-01 12:11:00.464   293  1064 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-01 12:11:00.464   293  1064 I WifiHW  : module is semco
07-01 12:11:00.464   293  1064 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-01 12:11:00.464   293  1064 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-01 12:11:00.464   293  1064 E WifiHW  : TEMP_FAILURE_RETRY complete
07-01 12:11:00.464   293  1064 D SoftapController: Softap fwReload - Ok
,07-01 12:11:00.464   293  1064 D CommandListener: Setting iface cfg
07-01 12:11:00.464   293  1064 D CommandListener: Trying to bring down wlan0
07-01 12:11:00.464   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:11:00.464   912  1149 E WifiHW  : supplicant_name : p2p_supplicant
,07-01 12:11:00.464   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:00.474  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:00.474   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 12:11:00.474  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:00.474   912  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 12:11:00.474  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:00.474  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:11:00.474  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:00.474  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:11:00.474  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:00.474  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-01 12:11:00.474  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:00.474  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:11:00.474  1195  1195 D HotspotTile: onReceive : 2, 0
,07-01 12:11:00.494  1195  1195 D QSpanel : label top:23
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:00.494  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:00.494  7899  7899 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-01 12:11:00.494  7899  7899 I wpa_supplicant: Successfully initialized wpa_supplicant
07-01 12:11:00.504  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:00.504  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 12:11:00.504   347   347 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7899
07-01 12:11:00.504   347   347 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-01 12:11:00.504  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:00.504  7899  7899 I wpa_supplicant: ssSupport state is = 1
07-01 12:11:00.504  7899  7899 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
07-01 12:11:00.504  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-01 12:11:00.504   347   347 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7899
07-01 12:11:00.504   347   347 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-01 12:11:00.564  7883  7883 E BluetoothHeadset: BTStateChangeCB is registed
,07-01 12:11:00.564   912  1689 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:00.564  7883  7883 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:00.574   912  1468 I ActivityManager: Killing 6167:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,07-01 12:11:00.574  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:00.574  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:00.574   912  3665 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:00.574  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:00.574   912  1245 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-01 12:11:00.584  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:00.584  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:00.584  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 12:11:00.584  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:00.584   912   928 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:00.594  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:00.594  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-01 12:11:00.594  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 12:11:00.604  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:00.604   912  1094 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:00.604  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:00.604   912  1655 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:11:00.604  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:00.604  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:00.604  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 12:11:00.604  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:00.604  6583  6583 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 12:11:00.614   912  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-01 12:11:00.614   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.614   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.614   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.614   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:00.654   912  1485 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7907 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:00.654  7907  7907 E Zygote  : MountEmulatedStorage()
07-01 12:11:00.654  7907  7907 E Zygote  : v2
07-01 12:11:00.654  7907  7907 I libpersona: KNOX_SDCARD checking this for 10192
07-01 12:11:00.654  7907  7907 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:00.704  7907  7907 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:00.704  7907  7907 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:00.704  7907  7907 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:00.724  7907  7907 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:00.724  7907  7907 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:00.734  7907  7907 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-01 12:11:00.754  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 12:11:00.754  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-01 12:11:00.754  7907  7907 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 12:11:00.754  7907  7907 D WifiDirectBR: stopServiceTest : false
,07-01 12:11:00.764  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:11:00.764   912  1689 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-01 12:11:00.764   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.764   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:00.764   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:00.764   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:00.784   347   347 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-01 12:11:00.804  7922  7922 E Zygote  : MountEmulatedStorage()
07-01 12:11:00.804  7922  7922 E Zygote  : v2
07-01 12:11:00.804  7922  7922 I libpersona: KNOX_SDCARD checking this for 10131
07-01 12:11:00.804  7922  7922 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:00.814   912  1689 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7922 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:11:00.814   912  1689 I ActivityManager: Killing 6956:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-01 12:11:00.824   331   331 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 328us total 14.498ms
,07-01 12:11:00.834   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.555ms
,07-01 12:11:00.844   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 9.616ms
,07-01 12:11:00.854  7922  7922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:00.854  7922  7922 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:00.854  7922  7922 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 12:11:00.874  7922  7922 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:00.874  7922  7922 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:00.884  7922  7922 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-01 12:11:00.884  7922  7922 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 12:11:01.014  3260  3318 D bt_vendor: op for 7
,07-01 12:11:01.034  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-01 12:11:01.054  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:01.054  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 12:11:01.054   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7899
07-01 12:11:01.054   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 12:11:01.054  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:01.054  7899  7899 I wpa_supplicant: ssSupport state is = 1
07-01 12:11:01.054  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.054  7899  7899 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:01.054  7899  7899 E wpa_supplicant: SIM READ ERROR
07-01 12:11:01.054  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.054  7899  7899 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:01.054  7899  7899 E wpa_supplicant: SIM READ ERROR
07-01 12:11:01.054  7899  7899 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:11:01.054  7899  7899 I wpa_supplicant: wpa_default_ap_write_once
07-01 12:11:01.054  7899  7899 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 12:11:01.054  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.054  7899  7899 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-01 12:11:01.054  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.054  7899  7899 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-01 12:11:01.054  7899  7899 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:11:01.084  7922  7922 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-01 12:11:01.084  7922  7945 I Babel   : MmsConfig: mnc/mcc: 0/0
07-01 12:11:01.084  7922  7945 I Babel   : MmsConfig.loadMmsSettings
,07-01 12:11:01.084  7922  7945 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-01 12:11:01.084  7922  7945 I Babel   : MmsConfig.loadFromDatabase
,07-01 12:11:01.094  7922  7945 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,07-01 12:11:01.094  7922  7945 I Babel   : MmsConfig.loadFromResources
,07-01 12:11:01.094  7922  7945 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-01 12:11:01.094  7922  7945 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-01 12:11:01.104   912  1456 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-01 12:11:01.104  7922  7922 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:01.134  7922  7922 I Babel_StickerModule: App launched.
,07-01 12:11:01.134  7922  7922 I Babel_StickerModule: Trying first logged in account.
,07-01 12:11:01.134  7922  7922 W Babel_StickerModule: Unable to load, account not configured.
,07-01 12:11:01.144  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-01 12:11:01.144  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:01.144   912  1655 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.144  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:01.154   912  1689 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.154  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:01.154  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:01.154  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 12:11:01.154  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:01.154   912   928 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:01.154  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:01.164   304   304 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-01 12:11:01.164   304   304 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-01 12:11:01.164   304   304 W QCamera2Factory: getCameraInfo: X
,07-01 12:11:01.164   304   680 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-01 12:11:01.164   304   680 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-01 12:11:01.164   304   680 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-01 12:11:01.164   304   680 W QCamera2Factory: getCameraInfo: X
,07-01 12:11:01.164  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:01.174  7922  7922 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 12:11:01.184   912  3696 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:01.184  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-01 12:11:01.184  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:01.184  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
,07-01 12:11:01.184  7922  7922 W AudioCapabilities: Unsupported mime audio/qcelp
,07-01 12:11:01.184  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:01.184  7922  7922 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 12:11:01.194  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 12:11:01.194   912  1468 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 12:11:01.194   912  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e18c163, r.packageName :com.android.settings
,07-01 12:11:01.194  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:01.194  7922  7922 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-01 12:11:01.204  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/x-ima
,07-01 12:11:01.204  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/qcelp
,07-01 12:11:01.204  7922  7922 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 12:11:01.214  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:01.224   912  1456 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:01.224  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:01.224  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:01.224  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:01.224  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:01.224  7922  7922 W VideoCapabilities: Unsupported mime video/wvc1
,07-01 12:11:01.224  7922  7922 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-01 12:11:01.234  7148  7148 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-01 12:11:01.234  7148  7148 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 12:11:01.234  7148  7148 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 12:11:01.234  7148  7148 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:01.234  7148  7148 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-01 12:11:01.234   912   928 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-01 12:11:01.234   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.234   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.234   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.234   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unsupported mime video/wvc1
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-01 12:11:01.244  7922  7922 W VideoCapabilities: Unsupported mime video/mp43
,07-01 12:11:01.254  7922  7922 W VideoCapabilities: Unsupported mime video/sorenson
,07-01 12:11:01.254  7922  7922 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-01 12:11:01.264  7922  7922 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 12:11:01.274  7953  7953 E Zygote  : MountEmulatedStorage()
,07-01 12:11:01.274  7953  7953 E Zygote  : v2
07-01 12:11:01.274  7953  7953 I libpersona: KNOX_SDCARD checking this for 10144
07-01 12:11:01.274  7953  7953 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:01.284   912   928 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7953 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:01.354  7953  7953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:01.354  7953  7953 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:01.354  7953  7953 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 12:11:01.374   912  3696 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-01 12:11:01.384   912  1245 I ActivityManager: Killing 6609:com.sec.knox.bridge/1000 (adj 15): emptyCount ##41
,07-01 12:11:01.384  7953  7953 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:01.384  7953  7953 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:01.444  7953  7953 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-01 12:11:01.464  7717  7774 I WifiManager: packageName : com.test.thalitest
,07-01 12:11:01.464   912  1689 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 12:11:01.464   912  1689 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 12:11:01.464   912  1689 D SecContentProvider2: mCursor = null
,07-01 12:11:01.464   912  1689 D WifiService: setWifiEnabled: false pid=7717, uid=10079
,07-01 12:11:01.464   912  1689 D SettingsProvider: name = wifi_on
,07-01 12:11:01.474  3260  3435 D bt_upio : ..proc_btwrite_timeout..
,07-01 12:11:01.544  7953  7953 I MusicStore: Database version: 108
,07-01 12:11:01.554   298   298 E SMD     : DCD ON
,07-01 12:11:01.554   912  1458 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.604  7953  7953 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-01 12:11:01.614  7953  7953 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-01 12:11:01.614  7953  7953 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:11:01.634  7953  7953 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-01 12:11:01.684  7953  7953 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-01 12:11:01.684  7953  7953 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@358f3bcb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-01 12:11:01.684  7953  7953 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-01 12:11:01.684  7953  7953 D AndroidMusic: GMSCore installation verified
,07-01 12:11:01.704   912  1460 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.704   912  1152 E Tethering: No numeric data
,07-01 12:11:01.704   912  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-01 12:11:01.704   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:01.704   912  1146 V NetworkStats: performPollLocked(flags=0x1)
07-01 12:11:01.714   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:11:01.714   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:01.714  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-01 12:11:01.714   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:01.714   912  1146 V NetworkStats: performPollLocked() took 3ms
07-01 12:11:01.714  1195  1195 D HotspotTile: updateTetherState():false, false
07-01 12:11:01.714   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:01.714   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:01.714  7953  7953 I ConfigStore: Config Database version: 1
,07-01 12:11:01.744   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 12:11:01.744   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:01.744  7953  7953 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 12:11:01.744   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 12:11:01.744   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:01.744  7953  7953 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 12:11:01.744   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 12:11:01.744   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:01.744  7953  7953 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 12:11:01.754  7899  7899 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-01 12:11:01.754   912  1719 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-01 12:11:01.754   912  1719 D ActivityManager: caller:android.app.ApplicationThreadProxy@32423a9a, r.packageName :com.google.android.music
,07-01 12:11:01.764   912  3665 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.774   912  1655 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.784   912   929 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.784   912  1094 I AudioService: getStreamVolume 3 index 70
,07-01 12:11:01.794  7953  7953 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
07-01 12:11:01.794  7953  7953 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-01 12:11:01.794  7899  7899 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 12:11:01.794   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7899
07-01 12:11:01.794   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:01.794  7899  7899 I wpa_supplicant: ssSupport state is = 1
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 12:11:01.794   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7899
07-01 12:11:01.794   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 12:11:01.794  7899  7899 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:01.794  7899  7899 I wpa_supplicant: ssSupport state is = 1
07-01 12:11:01.794  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.794  7899  7899 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:01.794  7899  7899 E wpa_supplicant: SIM READ ERROR
07-01 12:11:01.794  7899  7899 I wpa_supplicant: wpa_default_ap_write_once
07-01 12:11:01.794  7899  7899 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 12:11:01.794  7899  7899 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:11:01.814   912  3665 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.814   912   929 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.814   912   928 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.824   912  3696 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.824   912  1719 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-01 12:11:01.824   912  1719 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.824   912  1719 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.824   912  1719 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:01.824   912  1719 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:01.834  7899  7899 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-01 12:11:01.834  7899  7899 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-01 12:11:01.864  7982  7982 E Zygote  : MountEmulatedStorage()
07-01 12:11:01.864  7982  7982 E Zygote  : v2
07-01 12:11:01.864  7982  7982 I libpersona: KNOX_SDCARD checking this for 10004
07-01 12:11:01.864  7982  7982 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:01.874   912  1719 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7982 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:01.884  7899  7899 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-01 12:11:01.884  7899  7899 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-01 12:11:01.884  7899  7899 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 12:11:01.884   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-01 12:11:01.884   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 12:11:01.884  7899  7899 I wpa_supplicant: HOTSPOT20_ENABLE called
07-01 12:11:01.884  7899  7899 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:01.884  7899  7899 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:01.884  7899  7899 E wpa_supplicant: SIM READ ERROR
07-01 12:11:01.884  7899  7899 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:11:01.904  7982  7982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:01.904  7982  7982 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:01.904  7982  7982 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:01.904  7899  7899 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-01 12:11:01.904  7899  7899 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 12:11:01.904   912  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 12:11:01.904   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.914   912  1149 D WifiConfigStore: Loading config and enabling all networks 
,07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:01.914  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:01.914   912  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-01 12:11:01.914  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:01.914  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:01.914  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:01.914   912  1149 E WifiConfigStore: Not a HS20
,07-01 12:11:01.914   912  1485 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:01.924  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:01.924   912  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:01.924  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:01.924   912  1149 D WifiNative-HAL: callSECApiInt - ID [65]
07-01 12:11:01.924  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:01.924  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-01 12:11:01.924  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:11:01.924  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.924  1195  1195 D HotspotTile: onReceive : 3, 0
,07-01 12:11:01.934   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-01 12:11:01.934  7899  7899 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-01 12:11:01.934  7899  7899 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-01 12:11:01.934  7899  7899 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 12:11:01.934  7899  7899 I wpa_supplicant: P2P: Current p2p state = IDLE
07-01 12:11:01.934  7899  7899 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-01 12:11:01.934  7899  7899 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-01 12:11:01.934  7899  7899 I wpa_supplicant: First Scan Start
,07-01 12:11:01.934  7982  7982 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:01.934  7982  7982 D ActivityThread: Added TimaKeyStore provider
07-01 12:11:01.934  7922  7922 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:01.934  7899  7899 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 12:11:01.934   912  1149 D WifiNative-HAL: Setting external_sim to 1
07-01 12:11:01.934   912  1149 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:01.934   912  1149 I WifiNative-HAL: startHal
07-01 12:11:01.934   912  1149 E wifi    : getStaticLongField sWifiHalHandle 0x938b086c
07-01 12:11:01.934   912  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601f6a
07-01 12:11:01.934   912  1149 I WifiNative-HAL: Could not start hal
,07-01 12:11:01.944  7953  7953 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-01 12:11:01.944   912  1460 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:01.944  7982  7982 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-01 12:11:01.954  1195  1195 D QSpanel : label top:23
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:01.954  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:01.954   912  1149 E native  : do suspend true
,07-01 12:11:01.964   912  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
07-01 12:11:01.964   912   912 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 12:11:01.964   912   912 D RttService: SCAN_AVAILABLE : 3
,07-01 12:11:01.964   912  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.964   912  1167 I WifiNative-HAL: startHal
07-01 12:11:01.964   912  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9adf399c
07-01 12:11:01.964   912  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x901f1a
07-01 12:11:01.964   912  1167 I WifiNative-HAL: Could not start hal
07-01 12:11:01.964   912  1167 E WifiScanningService: could not start HAL
07-01 12:11:01.964   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-01 12:11:01.964   912  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.964   293  1064 D CommandListener: Setting iface cfg
07-01 12:11:01.964   293  1064 D CommandListener: Trying to bring up p2p0
07-01 12:11:01.964   912  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-01 12:11:01.964   912  1148 D WifiP2pService: P2pEnablingState
07-01 12:11:01.964   912  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
07-01 12:11:01.964   912  1148 D WifiP2pService: P2p socket connection successful
07-01 12:11:01.964   912  1148 D WifiP2pService: P2pEnabledState
,07-01 12:11:01.964   912  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-01 12:11:01.964   912   912 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-01 12:11:01.964   912  1038 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-01 12:11:01.964   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:01.964   912  1038 D WifiDisplayController: disconnect
07-01 12:11:01.964   912  1038 D WifiDisplayController: updateConnection
07-01 12:11:01.964   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:01.964   912  1038 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.964   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:01.964   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-01 12:11:01.964   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.964   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:11:01.964   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:11:01.964   912   912 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 12:11:01.964   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 12:11:01.964   912   912 D RttService: SCAN_AVAILABLE : 1
,07-01 12:11:01.964   912  1167 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.964   912  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:01.964  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 12:11:01.964   912  1094 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.964  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-01 12:11:01.964   912  1149 D WifiStateMachine: DefaultState::Handling CMD_SEC_STRING_API
,07-01 12:11:01.964   912  1148 D WifiNative-HAL: p2pGetDeviceAddress
07-01 12:11:01.964   912  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-01 12:11:01.964   912  1148 D WifiP2pService: DeviceAddress: ea:fd:2b
07-01 12:11:01.964   912  1038 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-01 12:11:01.964   912  1038 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-01 12:11:01.964   912  1038 D WifiDisplayController:  primary type: 10-0050F204-5
07-01 12:11:01.964   912  1038 D WifiDisplayController:  secondary type: null
07-01 12:11:01.964   912  1038 D WifiDisplayController:  wps: 0
07-01 12:11:01.964   912  1038 D WifiDisplayController:  grpcapab: 0
07-01 12:11:01.964   912  1038 D WifiDisplayController:  devcapab: 0
07-01 12:11:01.964   912  1038 D WifiDisplayController:  status: 3
07-01 12:11:01.964   912  1038 D WifiDisplayController:  wfdInfo: null
07-01 12:11:01.964   912  1038 D WifiDisplayController:  groupownerAddress: null
07-01 12:11:01.964   912  1038 D WifiDisplayController:  GOdeviceName: null
07-01 12:11:01.964   912  1038 D WifiDisplayController:  interfaceAddress: 
07-01 12:11:01.964   912  1038 D WifiDisplayController:  SConnectInfo : null
,07-01 12:11:01.984   912  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-01 12:11:01.984   912  1148 D WifiP2pService: InactiveState
07-01 12:11:01.984   912  1148 D WifiP2pService: InactiveState{ what=131204 }
07-01 12:11:01.984   912  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-01 12:11:01.984   912  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-01 12:11:01.984   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.984   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:11:01.984   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:11:01.984   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-01 12:11:01.984   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:01.984   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-01 12:11:01.984   912   912 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-01 12:11:01.984   912  1038 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-01 12:11:01.984   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:01.984   912  1038 D WifiDisplayController: disconnect
07-01 12:11:01.984   912  1038 D WifiDisplayController: updateConnection
07-01 12:11:01.984   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:01.984   912  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-01 12:11:01.984   912  1038 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:01.984   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:11:01.984   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:11:01.984   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:11:01.984   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-01 12:11:01.984  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 12:11:01.984   912  1485 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 12:11:01.984   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:01.984   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-01 12:11:01.984  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-01 12:11:01.984   912  1148 D WifiP2pService: P2pDisablingState
07-01 12:11:01.984   912  1148 D WifiP2pService: P2pDisablingState{ what=143376 }
07-01 12:11:01.984   912  1148 D WifiP2pService: DefaultState{ what=143376 }
,07-01 12:11:01.984   912  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
07-01 12:11:01.984   912  1148 D WifiP2pService: p2p socket connection lost
,07-01 12:11:01.984   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:11:01.994  7899  7899 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-01 12:11:01.994   912  1148 D WifiP2pService: P2pDisabledState
,07-01 12:11:01.994   912  1719 I ActivityManager: Killing 6659:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): emptyCount ##41
,07-01 12:11:01.994   912   912 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 12:11:01.994   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:01.994   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:02.004  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:02.004  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:02.004  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:02.004  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:02.004  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:02.004  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-01 12:11:02.004  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:02.004  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:02.004  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:02.004  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:02.014  1195  1195 D HotspotTile: onReceive : 0, 0
,07-01 12:11:02.014  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:02.034  1195  1195 D QSpanel : label top:23
,07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
,07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:02.034  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:02.034   912  1468 I ActivityManager: Killing 6878:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-01 12:11:02.044   912  1468 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-01 12:11:02.044   912  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.044   912  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.044   912  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.044   912  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:02.084  8004  8004 E Zygote  : MountEmulatedStorage()
07-01 12:11:02.084  8004  8004 E Zygote  : v2
07-01 12:11:02.084  8004  8004 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:11:02.084  8004  8004 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:02.094   912  1468 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=8004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 12:11:02.104  7899  7899 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:11:02.174  7899  7899 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-01 12:11:02.174  7899  7899 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
07-01 12:11:02.174  7899  7899 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-01 12:11:02.174  8004  8004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:02.174  8004  8004 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:02.174  8004  8004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:02.194  8004  8004 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:02.194  8004  8004 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:02.214  8004  8004 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-01 12:11:02.224  7899  7899 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:11:02.234  8004  8004 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-01 12:11:02.254  8004  8004 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-01 12:11:02.364  8004  8004 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-01 12:11:02.374  8004  8004 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-01 12:11:02.374  8004  8004 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:02.374  8004  8004 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-01 12:11:02.394   912  1152 D Tethering: InitialState.processMessage what=4
07-01 12:11:02.394   912  1146 V NetworkStats: performPollLocked(flags=0x1)
07-01 12:11:02.394  7899  7899 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 12:11:02.394   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:02.394  7899  7899 I wpa_supplicant: ELOOP: remaining timeout: 0.040541 eloop_data=0xb6588200 user_data=0x0 handler=0xb6f37af1
07-01 12:11:02.394  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:02.394  7899  7899 I wpa_supplicant: ELOOP: remaining timeout: 0.075019 eloop_data=0xb6588c00 user_data=0x0 handler=0xb6f37af1
07-01 12:11:02.394  1195  1195 D HotspotTile: updateTetherState():false, false
07-01 12:11:02.394   912  1152 E Tethering: No numeric data
07-01 12:11:02.394   912  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 12:11:02.394   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:02.394   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-01 12:11:02.394   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-01 12:11:02.394   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 12:11:02.394   912  1146 V NetworkStats: performPollLocked() took 6ms
,07-01 12:11:02.394   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:02.404  1972  1972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:02.404   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:02.404   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 12:11:02.404  7922  7922 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 12:11:02.404  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:02.404  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:02.404  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:11:02.404  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:02.404  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-01 12:11:02.404  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:02.404  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 12:11:02.404   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:02.404   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:02.404  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:02.404  1195  1195 D HotspotTile: onReceive : 1, 0
07-01 12:11:02.404  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:02.424  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:02.424  1195  1195 D QSpanel : label top:23
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:02.424  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:02.454   912  1456 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-01 12:11:02.454   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.454   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.454   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.454   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:02.474  7717  7774 D BluetoothAdapter: enable()
,07-01 12:11:02.494  8020  8020 E Zygote  : MountEmulatedStorage()
,07-01 12:11:02.494  8020  8020 E Zygote  : v2
07-01 12:11:02.494  8020  8020 I libpersona: KNOX_SDCARD checking this for 10014
07-01 12:11:02.494  8020  8020 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:02.504   912  1456 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=8020 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:02.504   912  1533 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-01 12:11:02.504   912  1533 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:02.504   912  1533 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 12:11:02.504   912  1533 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-01 12:11:02.504   912  1533 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-01 12:11:02.504   912  1533 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-01 12:11:02.504   912  1533 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 12:11:02.504   912  1533 W ActivityManager: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:02.504   912  1533 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 12:11:02.504   912  1533 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 12:11:02.504   912  1533 D SettingsProvider: name = bluetooth_on
,07-01 12:11:02.514   912  1036 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 12:11:02.514   912  1036 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 12:11:02.524  8020  8020 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:02.524  8020  8020 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:02.524  8020  8020 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-01 12:11:02.524   912  1036 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-01 12:11:02.524  3260  3312 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-01 12:11:02.524  3260  3312 D BluetoothAdapterProperties: Setting state to 11
07-01 12:11:02.524  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 12:11:02.524  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:02.524  3260  3312 D BluetoothAdapterService: updateAdapterState state is 11
07-01 12:11:02.524  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:02.524  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-01 12:11:02.524  3260  3312 D BtConfig.SecureMode: isSecureModeOn:false
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:11:02.524  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-01 12:11:02.524   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.524   912   912 I InputMethodManagerService: [BT Setting State] State =11
,07-01 12:11:02.524  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:02.524  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.524   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.524   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@512a825, r.packageName :com.android.bluetooth
,07-01 12:11:02.524  1746  1746 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:11:02.524  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:02.524  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:02.524  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:11:02.534   912  1655 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:11:02.534  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:11:02.534  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-01 12:11:02.534   912  1719 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 12:11:02.534  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 12:11:02.534   912  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.534  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 12:11:02.534   912  1460 D ActivityManager: caller:android.app.ApplicationThreadProxy@13134fab, r.packageName :com.android.bluetooth
,07-01 12:11:02.534  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 12:11:02.534  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:02.534  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-01 12:11:02.534   912  1245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.534   912  1245 D ActivityManager: caller:android.app.ApplicationThreadProxy@4eaa1a1, r.packageName :com.android.bluetooth
,07-01 12:11:02.534  3260  3260 D HeadsetService: Received start request. Starting profile...
07-01 12:11:02.534  3260  3260 D HeadsetStateMachine: make
,07-01 12:11:02.544  3260  3260 E HeadsetStateMachine: # of Max HF connection is 2
,07-01 12:11:02.544  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:11:02.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:11:02.544  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-01 12:11:02.544   912  1336 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.544   912  1336 D ActivityManager: caller:android.app.ApplicationThreadProxy@7353b87, r.packageName :com.android.bluetooth
,07-01 12:11:02.544  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:02.544  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:02.544  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:02.544  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:02.554  1195  1195 D QSpanel : label top:23
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:02.554   912  3696 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:02.554  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:11:02.554   912   928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.554   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@20a00923, r.packageName :com.android.bluetooth
,07-01 12:11:02.554   912  1458 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-01 12:11:02.554   912   928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:02.554  3260  3260 I bluedroid: get_profile_interface handsfree
07-01 12:11:02.554   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@2660147f, r.packageName :com.android.bluetooth
,07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:11:02.554  3260  3260 E DualScoManager: Dual Sco Manager already instantiated
07-01 12:11:02.554  3260  3260 I DualScoManager: Set HeadsetServiceHelper
07-01 12:11:02.554  3260  3260 D BluetoothAtMessage: createCMTIContentObservers
07-01 12:11:02.554   912  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:02.554   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@13f6e495, r.packageName :com.android.bluetooth
07-01 12:11:02.554   912  1468 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-01 12:11:02.554   912  1468 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 12:11:02.554   912  1468 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:11:02.554   912  1468 D SettingsProvider: selectionArgs: false
07-01 12:11:02.554  8020  8020 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:11:02.554   912  1468 D SettingsProvider: selectionArgs: 1002
07-01 12:11:02.554   912  1468 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:11:02.554   912  1468 D SettingsProvider: ret = -1
,07-01 12:11:02.554  8020  8020 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:02.554  3260  8033 D HeadsetStateMachine: Enter Disconnected: -2
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:02.554  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 12:11:02.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:11:02.554  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 12:11:02.554  3260  3312 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-01 12:11:02.554  3260  3260 D A2dpService: Received start request. Starting profile...
07-01 12:11:02.554  3260  3260 V Avrcp   : make
07-01 12:11:02.554  3260  3260 V Avrcp   : Avrcp
07-01 12:11:02.554  3260  3260 I bluedroid: get_profile_interface avrcp
,07-01 12:11:02.554  3260  3260 V Avrcp   : start
,07-01 12:11:02.554  3260  8033 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-01 12:11:02.564  3260  3260 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-01 12:11:02.564  3260  3260 V Avrcp   : ++registerMediaPlayers++
07-01 12:11:02.564  3260  8033 D HeadsetStateMachine: map size, before remove : 0
07-01 12:11:02.564  3260  8033 D HeadsetStateMachine: map size, after remove: 0
07-01 12:11:02.564  3260  8033 D HeadsetStateMachine: mNextConnectingDevice : null
,07-01 12:11:02.564  3260  3260 I Avrcp   : No of Audio players :: 2
07-01 12:11:02.564  3260  3260 I Avrcp   : App Package name is com.google.android.music
,07-01 12:11:02.564  3260  3260 I Avrcp   : App pkg name is Google Play Music
,07-01 12:11:02.564  3260  3260 I Avrcp   : Name::Google Play Music
07-01 12:11:02.564  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-01 12:11:02.564  3260  3260 I Avrcp   : App Package name is com.sec.android.app.music
,07-01 12:11:02.564  3260  3260 I Avrcp   : App pkg name is Music
07-01 12:11:02.564  3260  3260 I Avrcp   : Name::Music
07-01 12:11:02.564  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-01 12:11:02.564  3260  3260 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-01 12:11:02.564  3260  3260 I Avrcp   : No of Video players :: 1
07-01 12:11:02.564  3260  3260 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-01 12:11:02.564  3260  3260 I Avrcp   : Video App pkg name is Video Player
07-01 12:11:02.564  3260  3260 I Avrcp   : Name::Video Player
07-01 12:11:02.564  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-01 12:11:02.564  3260  3260 I Avrcp   : Add tempPlayer
07-01 12:11:02.564  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-01 12:11:02.564  3260  3260 I Avrcp   : Total no of players: 4
07-01 12:11:02.564  3260  3260 V Avrcp   : swapping the samsung player with 1st player
07-01 12:11:02.564  3260  3260 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-01 12:11:02.564  3260  8036 V Avrcp   : handleMessage, msg=207
07-01 12:11:02.564  3260  8036 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-01 12:11:02.574  3260  3260 D A2dpStateMachine: make
,07-01 12:11:02.574  3260  3260 I bluedroid: get_profile_interface a2dp
,07-01 12:11:02.574  3260  8040 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 12:11:02.574  3260  3260 E bt-btif : warning : media task started media_task_refcnt 1 
,07-01 12:11:02.574  3260  8036 D BluetoothMediaBrowser: no now playing list
07-01 12:11:02.574  3260  8036 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-01 12:11:02.574  3260  8036 D Avrcp   :  checkNowPlayingList start
,07-01 12:11:02.574  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:02.574  3260  8038 D A2dpStateMachine: Enter Disconnected: -2
07-01 12:11:02.574  8020  8020 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-01 12:11:02.574  3260  3260 D HidService: Received start request. Starting profile...
07-01 12:11:02.574  3260  3260 I bluedroid: get_profile_interface hidhost
07-01 12:11:02.574  3260  3260 D HidService: setHidService(): set to: null
07-01 12:11:02.574  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:02.574  3260  3260 D HeadsetStateMachine: Try to query the phonestate on bind
,07-01 12:11:02.574  1398  1415 I Telecom : BluetoothPhoneService: queryPhoneState
,07-01 12:11:02.574  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-01 12:11:02.584  3260  3260 D HealthService: Received start request. Starting profile...
,07-01 12:11:02.584  3260  3260 I bluedroid: get_profile_interface health
,07-01 12:11:02.584  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:02.584  3260  3260 D PanService: Received start request. Starting profile...
07-01 12:11:02.584  3260  3260 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 12:11:02.584  3260  3260 I bluedroid: get_profile_interface pan
07-01 12:11:02.584  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:02.584  3260  3260 D HeadsetStateMachine: Proxy object connected
,07-01 12:11:02.584  3260  3260 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-01 12:11:02.584  3260  3260 D HeadsetPhoneState: sendDeviceDataStateChanged
07-01 12:11:02.584  3260  8033 D HeadsetStateMachine: Disconnected process message: 11
07-01 12:11:02.584  3260  8033 D HeadsetStateMachine: Disconnected process message: 18
,07-01 12:11:02.584  3260  3260 D BluetoothMapService: Received start request. Starting profile...
,07-01 12:11:02.584   912  1655 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,07-01 12:11:02.584   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.584   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.584   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.584   912  1655 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:02.614   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-01 12:11:02.624  8044  8044 E Zygote  : MountEmulatedStorage()
07-01 12:11:02.624  8044  8044 E Zygote  : v2
07-01 12:11:02.624  8044  8044 I libpersona: KNOX_SDCARD checking this for 10186
07-01 12:11:02.624  8044  8044 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:02.634   912  1655 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=8044 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-01 12:11:02.664  8044  8044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:02.664  8044  8044 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:02.664  8044  8044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:02.674   912  1458 I ActivityManager: Killing 4211:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,07-01 12:11:02.674  8020  8020 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-01 12:11:02.684  8020  8020 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-01 12:11:02.704  8044  8044 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:02.704  8044  8044 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:02.714  8020  8020 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-01 12:11:02.714  8044  8044 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-01 12:11:02.714  8044  8044 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-01 12:11:02.714  8044  8044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:11:02.714  8044  8044 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-01 12:11:02.724  8044  8044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:11:02.724  8044  8044 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 12:11:02.734   912  1458 I ActivityManager: Killing 7079:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-01 12:11:02.734   912  1719 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 12:11:02.734   912  1719 D ActivityManager: caller:android.app.ApplicationThreadProxy@38797549, r.packageName :com.google.android.gms
,07-01 12:11:02.734  2330  2330 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-01 12:11:02.744  2330  8059 I iu.SyncManager: SYNC; picasa accounts
,07-01 12:11:02.744   912  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:11:02.744   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@ce95e4e, r.packageName :com.google.android.gms
,07-01 12:11:02.754  2330  8059 I iu.UploadsManager: num queued entries: 0
,07-01 12:11:02.764  2330  8059 I iu.UploadsManager: num updated entries: 0
,07-01 12:11:02.764  2330  8059 I iu.SyncManager: NEXT; no task
,07-01 12:11:02.764  2330  2330 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,07-01 12:11:02.764  2330  2330 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-01 12:11:02.764  2330  2330 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-01 12:11:02.764  2330  2330 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-01 12:11:02.774  2619  2619 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 12:11:02.774  2619  2619 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467367862787
,07-01 12:11:02.774  2619  2619 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:02.774   912  1485 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:02.774   912  1719 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:02.774  2619  2619 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-01 12:11:02.784  2619  2619 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-01 12:11:02.784   912  1456 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-01 12:11:02.784   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.784   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.784   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.784   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:02.864  8062  8062 E Zygote  : MountEmulatedStorage()
,07-01 12:11:02.864  8062  8062 E Zygote  : v2
07-01 12:11:02.864  8062  8062 I libpersona: KNOX_SDCARD checking this for 10036
07-01 12:11:02.864  8062  8062 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:02.874   912  1456 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=8062 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 12:11:02.894  8062  8062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:02.894   912  3665 D RCPManagerService: exchangeData() failure , invalid userId
07-01 12:11:02.894  8062  8062 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:02.894  8062  8062 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:02.914  8062  8062 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:02.914  8062  8062 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:02.934  8062  8062 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-01 12:11:02.934   912   929 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 12:11:02.934  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:02.934  3260  3260 D HeadsetPhoneState: Signal level : previous=0 curr=2
07-01 12:11:02.934  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-01 12:11:02.934  3260  3260 D SapService: Received start request. Starting profile...
07-01 12:11:02.934  3260  3260 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-01 12:11:02.934  3260  3260 I bluedroid: get_profile_interface sap
07-01 12:11:02.934  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:02.934  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:11:02.934  3260  8033 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:11:02.934  3260  8033 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-01 12:11:02.934  3260  8033 D HeadsetStateMachine: Disconnected process message: 11
,07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-01 12:11:02.944   912  1468 D RCPManagerService: exchangeData() failure , invalid userId
07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-01 12:11:02.944   912   928 I ActivityManager: Killing 7105:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-01 12:11:02.944  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-01 12:11:02.944  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-01 12:11:02.944  3260  3312 I bluedroid: enable
,07-01 12:11:02.944  8062  8062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:11:02.944  8062  8062 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-01 12:11:02.944  3260  3315 E bt-btif : Calling BTA_HhEnable
07-01 12:11:02.944  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:02.944  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:02.944  3260  3315 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-01 12:11:02.944  3260  3315 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-01 12:11:02.944  3260  3315 E BluetoothServiceJni: populateRssiValuesNative
07-01 12:11:02.944  3260  3315 I bluedroid: getModelRssiValues
07-01 12:11:02.944  3260  3315 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-01 12:11:02.944  3260  3315 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-01 12:11:02.944   912  3696 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-01 12:11:02.954   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.954   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.954   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:02.954   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:02.954  3260  3318 D bt_vendor: op for 7
,07-01 12:11:02.954  3260  3318 D bt_upio : proc btwrite assertion
,07-01 12:11:02.954  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.954  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.954  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.954  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.954  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.954  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.954  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.954  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.964  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.964  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.964  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.964  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.964  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.964  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.964  3260  3318 D bt_vendor: op for 7
07-01 12:11:02.964  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:02.994  8084  8084 E Zygote  : MountEmulatedStorage()
07-01 12:11:02.994  8084  8084 E Zygote  : v2
07-01 12:11:02.994  8084  8084 I libpersona: KNOX_SDCARD checking this for 10092
07-01 12:11:02.994  8084  8084 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:03.004   912  3696 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8084 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-01 12:11:03.004   912   912 D SettingsProvider: name = bluetooth_name
,07-01 12:11:03.004  3260  3315 D BluetoothAdapterProperties: Name is: Galaxy Note3
,07-01 12:11:03.004  8062  8062 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-01 12:11:03.024   912  1336 D RCPManagerService: exchangeData() failure , invalid userId
07-01 12:11:03.024  8084  8084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 12:11:03.024  8084  8084 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:03.024  3260  3315 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:03.024  3260  3315 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-01 12:11:03.024  3260  3315 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-01 12:11:03.024  3260  3315 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-01 12:11:03.024  3260  3315 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
07-01 12:11:03.024  3260  3315 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-01 12:11:03.024  3260  3315 E bt-btif : JVenable fails
07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3315 D bte_conf: Device ID record 1 : primary
07-01 12:11:03.024  3260  3315 D bte_conf:   vendorId            = 0075
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.024  3260  3315 D bte_conf:   vendorIdSource      = 0001
07-01 12:11:03.024  3260  3315 D bte_conf:   product             = 0100
07-01 12:11:03.024  3260  3315 D bte_conf:   version             = 0200
07-01 12:11:03.024  3260  3315 D bte_conf:   clientExecutableURL = 
07-01 12:11:03.024  3260  3315 D bte_conf:   serviceDescription  = 
07-01 12:11:03.024  3260  3315 D bte_conf:   documentationURL    = 
07-01 12:11:03.024  3260  3315 D bte_conf: bte_load_did_conf no section named DID2.
07-01 12:11:03.024  8084  8084 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
07-01 12:11:03.024  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 12:11:03.024  3260  3312 D BluetoothAdapterProperties: ScanMode =  20
07-01 12:11:03.024  3260  3312 D BluetoothAdapterProperties: State =  11
,07-01 12:11:03.024  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:03.024  3260  3315 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.024   912  1460 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 12:11:03.024  3260  3312 D BluetoothAdapterProperties: Setting state to 12
07-01 12:11:03.024  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.024  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:03.024  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.024  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:03.024  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:03.034  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:03.034  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.034  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.034  3260  3315 D BluetoothAdapterProperties: Scan Mode:21
07-01 12:11:03.034  3260  3315 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-01 12:11:03.034   912  1458 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-01 12:11:03.034   912  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 12:11:03.034   912  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:11:03.034   912  1458 D SettingsProvider: selectionArgs: false
07-01 12:11:03.034   912  1458 D SettingsProvider: selectionArgs: 1002
07-01 12:11:03.034   912  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:11:03.034   912  1458 D SettingsProvider: ret = -1
07-01 12:11:03.034  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:03.034  3260  3312 D BluetoothAdapterService: updateAdapterState state is 12
,07-01 12:11:03.034   912  1245 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.034   912  1245 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cd9ff8b, r.packageName :com.android.bluetooth
07-01 12:11:03.034  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.034  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.034  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.034  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.034   912  1719 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:03.034  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:03.034  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:03.034  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-01 12:11:03.034  3260  3312 D BluetoothAdapterService: starting service from this receiver
07-01 12:11:03.034   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:03.034   912  1036 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:03.034   912  1036 D BluetoothPan: Binding service...
07-01 12:11:03.034   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-01 12:11:03.034   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:03.034  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.034   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@2474e7bd, r.packageName :com.android.bluetooth
07-01 12:11:03.034  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.034  3260  3260 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-01 12:11:03.034  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.034  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.044  3260  3312 I BluetoothAdapterState: Entering On State from state = 11
,07-01 12:11:03.044  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.044  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.044   912  1456 I ActivityManager: Killing 7124:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-01 12:11:03.044  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.044  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.044  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.044  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.044   912  1036 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:03.044  3260  3260 I BluetoothPbapService: Handler(): got msg=1
,07-01 12:11:03.044  1428  1443 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:03.044   912  1689 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-01 12:11:03.054  3260  8097 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-01 12:11:03.054   912  1036 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 12:11:03.054   912   912 D BluetoothPan: BluetoothPAN Proxy object connected
,07-01 12:11:03.054  3407  3417 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:03.054  3260  8097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 12:11:03.054  3260  3682 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:03.054  3260  8097 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-01 12:11:03.054  3260  8097 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 12:11:03.054  3260  8097 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 12:11:03.054  3260  8097 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1163095
,07-01 12:11:03.054  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.054  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.054   912  1245 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-01 12:11:03.054  3260  8097 D BluetoothSocket: channel: 19
07-01 12:11:03.054  3260  8097 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-01 12:11:03.054   912  1245 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.054   912  1245 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.054   912  1245 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.054   912  1245 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.064  8084  8084 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:03.064  8084  8084 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:03.094  8102  8102 E Zygote  : MountEmulatedStorage()
,07-01 12:11:03.094  8102  8102 E Zygote  : v2
07-01 12:11:03.094  8102  8102 I libpersona: KNOX_SDCARD checking this for 10042
07-01 12:11:03.094  8102  8102 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:03.104   912  1245 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=8102 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-01 12:11:03.154  8102  8102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 12:11:03.154  8102  8102 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:03.154  8102  8102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:03.154   912  1456 I ActivityManager: Killing 6465:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-01 12:11:03.164   912  1036 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:03.164  3260  3260 D BluetoothA2dp: Proxy object connected
07-01 12:11:03.164  3260  3260 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-01 12:11:03.164  4719  4731 D Bluetoothsap: onBluetoothStateChange: up=true
07-01 12:11:03.164  4719  4731 D Bluetoothsap: Binding service...
,07-01 12:11:03.164  4719  4731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-01 12:11:03.174  8102  8102 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:11:03.174  8102  8102 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:03.184  8084  8084 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-01 12:11:03.204  8084  8084 D BadgeProvider: onCreate
,07-01 12:11:03.204  8084  8084 D BadgeProvider: DatabaseHelper
,07-01 12:11:03.254   912  1036 I art     : Explicit concurrent mark sweep GC freed 52454(2MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 1.421ms total 89.952ms
,07-01 12:11:03.264   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-01 12:11:03.264  4719  4719 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-01 12:11:03.264  4719  4719 D SapProfile: Bluetooth service connected
07-01 12:11:03.264  4719  4719 D Bluetoothsap: getConnectedDevices()
,07-01 12:11:03.274  4719  4731 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-01 12:11:03.274  4719  4735 D BluetoothPbap: onBluetoothStateChange: up=true
,07-01 12:11:03.274   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-01 12:11:03.274  4719  4719 D BluetoothPbap: Proxy object connected
,07-01 12:11:03.274  4719  4719 D PbapServerProfile: Bluetooth service connected
07-01 12:11:03.274   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:03.274  1398  1417 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:03.274  4719  4731 D BluetoothMap: onBluetoothStateChange: up=true
,07-01 12:11:03.274   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-01 12:11:03.274   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:03.274  4719  4719 D HeadsetProfile: Bluetooth service connected
07-01 12:11:03.274  4719  4735 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:03.274  4719  4731 D BluetoothPan: Binding service...
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-01 12:11:03.284  4719  4719 D BluetoothMap: Proxy object connected
07-01 12:11:03.284  4719  4719 D MapProfile: Bluetooth service connected
07-01 12:11:03.284  4719  4719 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:11:03.284  4719  4719 D PanProfile: Bluetooth service connected
07-01 12:11:03.284  4719  4735 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-01 12:11:03.284   912  1036 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:03.284  4719  4731 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 12:11:03.284   912   912 D BluetoothA2dp: Proxy object connected
,07-01 12:11:03.284  8102  8102 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:03.284  4719  4719 D BluetoothInputDevice: Proxy object connected
07-01 12:11:03.284  4719  4719 D HidProfile: Bluetooth service connected
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 12:11:03.284  1398  1417 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:03.284   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:03.284  1398  8117 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:03.284  3407  3421 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 12:11:03.284  8084  8095 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-01 12:11:03.294   912  1036 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:03.294  4719  4719 D BluetoothA2dp: Proxy object connected
07-01 12:11:03.294  4719  4719 D A2dpProfile: Bluetooth service connected
,07-01 12:11:03.294  3407  3407 D BluetoothA2dp: Proxy object connected
,07-01 12:11:03.294   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-01 12:11:03.294   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.294   912   912 I InputMethodManagerService: [BT Setting State] State =12
07-01 12:11:03.294   912   912 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 12:11:03.294  1746  1746 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:11:03.294  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-01 12:11:03.294  1972  1972 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
07-01 12:11:03.294  1972  1972 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
07-01 12:11:03.294  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: Can provide trust state change: true
,07-01 12:11:03.294  1972  1972 D Coffee - GoogleTrustAgent: setManagingTrust
,07-01 12:11:03.294  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.294  1398  1398 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@cf2bd48, true
,07-01 12:11:03.294  1398  1398 D BluetoothHeadset: registerMessageListener
07-01 12:11:03.294  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: setManagingTrust success
,07-01 12:11:03.304  3260  3682 D HeadsetService: registerMessageListener
,07-01 12:11:03.304  3260  3682 D HeadsetService: registerMessageListener
07-01 12:11:03.304  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:03.304  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.304  3260  8033 D HeadsetStateMachine: Disconnected process message: 70
07-01 12:11:03.304  3260  8033 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@779a59b
07-01 12:11:03.304  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-01 12:11:03.304  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-01 12:11:03.304  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.304  3260  8118 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-01 12:11:03.304  3260  8033 D HeadsetStateMachine: Disconnected process message: 9
07-01 12:11:03.304  3260  8033 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-01 12:11:03.304   912  1655 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 12:11:03.304   912  3696 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-01 12:11:03.304  3260  8118 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 12:11:03.314   304   673 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-01 12:11:03.314   304   673 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-01 12:11:03.314   304   673 V voice   : voice_set_parameters: exit with code(-2)
07-01 12:11:03.314   304   673 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-01 12:11:03.314   304   673 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-01 12:11:03.314  1195  1195 D KeyguardViewMediator: onTrustChanged( Showing = true , userId = 0 )
07-01 12:11:03.314   304   673 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-01 12:11:03.314   304   673 V audio_hw_primary: adev_set_parameters: exit
07-01 12:11:03.314  3260  8033 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-01 12:11:03.314  3260  8118 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-01 12:11:03.314  3260  8118 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 12:11:03.314  3260  8118 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 12:11:03.314  3260  8118 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3022ed38
07-01 12:11:03.314  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.314  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.314  3260  8118 D BluetoothSocket: channel: 5
,07-01 12:11:03.314  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:11:03.314  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
07-01 12:11:03.314  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 12:11:03.314  4719  4719 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,07-01 12:11:03.314  4719  4719 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-01 12:11:03.314  1461  1461 D Launcher.Model: reloadBadges entered.
07-01 12:11:03.314  8084  8095 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,07-01 12:11:03.314  8084  8095 D BadgeProvider: sendNotify, [notify] : null
07-01 12:11:03.314  8084  8095 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-01 12:11:03.314  8084  8095 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-01 12:11:03.314  8084  8095 D BadgeProvider: update, [UpdateCount] : 1
,07-01 12:11:03.324  1195  1195 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-01 12:11:03.334  8102  8102 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-01 12:11:03.334   912  1456 I ActivityManager: Killing 6560:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D QSpanel : label top:23
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:03.344   912  3696 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:03.344  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:03.344  3751  8119 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-01 12:11:03.344   912  3665 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:03.354  3751  8119 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
07-01 12:11:03.354  7181  7181 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-01 12:11:03.354  3751  8119 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
07-01 12:11:03.354  3751  8119 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-01 12:11:03.354  3751  8119 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-01 12:11:03.354  7224  7224 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
07-01 12:11:03.354   912  1689 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
07-01 12:11:03.354   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@377059a4, r.packageName :com.sec.spp.push
,07-01 12:11:03.364  7224  7224 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-01 12:11:03.364  7224  7224 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-01 12:11:03.364  7224  7224 I SA      : [SLFUCHKMGR] constructor called
,07-01 12:11:03.374  7224  7224 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-01 12:11:03.374  7224  7224 I SA      : [OR] == isSIMCardReady false ==
,07-01 12:11:03.374  7224  7224 I SA      : [SCU] == networkStateCheck == false
07-01 12:11:03.374  7224  7224 I SA      : [OR] onReceive END
,07-01 12:11:03.374   912  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-01 12:11:03.374  7181  8120 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-01 12:11:03.374   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.374   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.374   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.374   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.414  8123  8123 E Zygote  : MountEmulatedStorage()
,07-01 12:11:03.414  8123  8123 E Zygote  : v2
07-01 12:11:03.414  8123  8123 I libpersona: KNOX_SDCARD checking this for 10074
07-01 12:11:03.414  8123  8123 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:03.424   912  1485 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=8123 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-01 12:11:03.464  8123  8123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:03.464  8123  8123 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:03.464  8123  8123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:03.494  8123  8123 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:03.494  8123  8123 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:03.504   912  1485 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-01 12:11:03.504  8123  8123 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-01 12:11:03.514  7717  7774 D BluetoothAdapter: disable()
,07-01 12:11:03.514   912  3696 D SettingsProvider: name = bluetooth_on
,07-01 12:11:03.514  3260  3312 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-01 12:11:03.514  3260  3312 D BluetoothAdapterProperties: Setting state to 13
07-01 12:11:03.514  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 12:11:03.514  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:03.514  3260  3312 D BluetoothAdapterService: updateAdapterState state is 13
,07-01 12:11:03.514   912  1485 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.514   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@28a582c2, r.packageName :com.android.bluetooth
,07-01 12:11:03.524  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:03.524  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-01 12:11:03.524  3260  3312 D BluetoothAdapterService: terminating service from this receiver
07-01 12:11:03.524  3260  3260 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-01 12:11:03.524  3260  3312 D BluetoothAdapterProperties: onBluetoothDisable()
07-01 12:11:03.524  3260  3260 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@14764111, channel: 19, state: LISTENING
07-01 12:11:03.524  3260  3260 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@14764111, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1163095, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@22531276mSocket: android.net.LocalSocket@2a430077 impl:android.net.LocalSocketImpl@3bb5a4e4 fd:FileDescriptor[78]
,07-01 12:11:03.524   912  1689 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 12:11:03.524  3260  3260 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2a430077 impl:android.net.LocalSocketImpl@3bb5a4e4 fd:FileDescriptor[78]
07-01 12:11:03.524  3260  3312 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.524  3260  3315 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:03.524  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 12:11:03.524  3260  3312 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-01 12:11:03.524  3260  3312 E bt-btif : BTA got event 0x1a12
07-01 12:11:03.524  3260  3316 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.524   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.524  3260  3312 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-01 12:11:03.524   912   912 I InputMethodManagerService: [BT Setting State] State =13
,07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.524  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-01 12:11:03.524  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:03.524  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.524  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.524  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.524  1746  1746 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 12:11:03.534  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
,07-01 12:11:03.534  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.534  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.534   912  1456 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 12:11:03.534   912   929 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 12:11:03.534  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.534  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 12:11:03.534  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:03.534  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
,07-01 12:11:03.534  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.534  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:03.534  3260  3260 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36d5e002, channel: 5, state: LISTENING
,07-01 12:11:03.534  3260  3260 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36d5e002, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3022ed38, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6dd2d13mSocket: android.net.LocalSocket@3f9a2b50 impl:android.net.LocalSocketImpl@1db70149 fd:FileDescriptor[80]
07-01 12:11:03.534  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:03.534  3260  3260 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f9a2b50 impl:android.net.LocalSocketImpl@1db70149 fd:FileDescriptor[80]
,07-01 12:11:03.534  4719  4719 D BluetoothPbap: Proxy object disconnected
07-01 12:11:03.534  4719  4719 D PbapServerProfile: Bluetooth service disconnected
07-01 12:11:03.534  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:03.534  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:11:03.534  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 12:11:03.544  3260  3316 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 12:11:03.544  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.544  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.544  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.544  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.544  3260  3318 D bt_vendor: op for 7
07-01 12:11:03.544  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D QSpanel : label top:23
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:03.564  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:03.574  8123  8123 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-01 12:11:03.574  8123  8123 I SCloudBackupReceiver: Other Intent
,07-01 12:11:03.574   912  3696 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-01 12:11:03.574   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.574   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.574   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.574   912  3696 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.614  8141  8141 E Zygote  : MountEmulatedStorage()
07-01 12:11:03.614  8141  8141 E Zygote  : v2
07-01 12:11:03.614  8141  8141 I libpersona: KNOX_SDCARD checking this for 1000
07-01 12:11:03.614  8141  8141 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:03.624   912  3696 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=8141 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 12:11:03.624   912  3696 I ActivityManager: Killing 5724:com.sec.android.app.shealth/u0a40 (adj 15): emptyCount ##41
,07-01 12:11:03.674  8141  8141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:03.674  8141  8141 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:03.674  8141  8141 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:03.694  8141  8141 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:03.694  8141  8141 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:03.704  8141  8141 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,07-01 12:11:03.714  8141  8141 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 12:11:03.724  8141  8141 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-01 12:11:03.724  8141  8141 I KnoxUsageLogPro: premStatus:2
,07-01 12:11:03.724  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,07-01 12:11:03.724  3260  3312 D BtConfig.SecureMode: isSecureModeOn:false
07-01 12:11:03.724  3260  3312 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-01 12:11:03.724  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
07-01 12:11:03.724  3260  3312 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-01 12:11:03.724  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,07-01 12:11:03.724  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:11:03.724  8141  8141 I KnoxUsageLogPro: isEulaShown : false
07-01 12:11:03.724  8141  8141 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-01 12:11:03.724  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-01 12:11:03.734   912  1456 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:03.734   912  1456 D ActivityManager: caller:android.app.ApplicationThreadProxy@205bf8d3, r.packageName :com.android.bluetooth
,07-01 12:11:03.734   912  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
07-01 12:11:03.734  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 12:11:03.734  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:11:03.734  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-01 12:11:03.734   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.734   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.734  3260  3260 D HeadsetService: Received stop request...Stopping profile...
07-01 12:11:03.734   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.734   912  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.774  8156  8156 E Zygote  : MountEmulatedStorage()
07-01 12:11:03.774  8156  8156 E Zygote  : v2
07-01 12:11:03.774  8156  8156 I libpersona: KNOX_SDCARD checking this for 10104
07-01 12:11:03.774  8156  8156 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:03.784   912  1485 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8156 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:03.784   912  1485 I ActivityManager: Killing 7198:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-01 12:11:03.784   912  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.784  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:03.784   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@132b6c10, r.packageName :com.android.bluetooth
,07-01 12:11:03.784  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 12:11:03.784  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:03.784  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-01 12:11:03.794   331   331 I art     : Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 315us total 14.424ms
,07-01 12:11:03.804   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.557ms
,07-01 12:11:03.814   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 9.705ms
,07-01 12:11:03.824  8156  8156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:03.824  8156  8156 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:11:03.824  8156  8156 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-01 12:11:03.824   912   912 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 12:11:03.824  7883  7883 W BluetoothHeadset: Proxy not attached to service
,07-01 12:11:03.824  4719  4719 D HeadsetProfile: Bluetooth service disconnected
07-01 12:11:03.824   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.824   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@8ca1309, r.packageName :com.android.bluetooth
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-01 12:11:03.824   912  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.824   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@11cd090e, r.packageName :com.android.bluetooth
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:11:03.824   912  1655 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.824   912  1655 D ActivityManager: caller:android.app.ApplicationThreadProxy@1be34f2f, r.packageName :com.android.bluetooth
,07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.824   912  1689 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.824   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@f43393c, r.packageName :com.android.bluetooth
,07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:11:03.824   912   928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:03.824   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b77d6c5, r.packageName :com.android.bluetooth
,07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,07-01 12:11:03.824  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:11:03.824  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 12:11:03.824  3260  3312 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 12:11:03.824  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 12:11:03.824  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:03.824  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-01 12:11:03.834  3260  3260 D A2dpService: Received stop request...Stopping profile...
07-01 12:11:03.834  3260  3260 V Avrcp   : doQuit
,07-01 12:11:03.834  3260  8038 D A2dpStateMachine: Exit Disconnected: -1
07-01 12:11:03.834  3260  3260 D Avrcp   : Unregistering previous receiver
,07-01 12:11:03.834  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:03.834   912   912 D BluetoothA2dp: Proxy object disconnected
07-01 12:11:03.834   912   912 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 12:11:03.834  3407  3407 D BluetoothA2dp: Proxy object disconnected
,07-01 12:11:03.834  4719  4719 D BluetoothA2dp: Proxy object disconnected
07-01 12:11:03.834  4719  4719 D A2dpProfile: Bluetooth service disconnected
,07-01 12:11:03.834  3260  3260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-01 12:11:03.834  3260  3260 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-01 12:11:03.834  3260  3260 D HidService: Received stop request...Stopping profile...
,07-01 12:11:03.834  3260  3260 D HidService: Stopping Bluetooth HidService
07-01 12:11:03.834  3260  3260 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 12:11:03.834  3260  3260 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-01 12:11:03.834  3260  3260 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 12:11:03.834  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:03.834  4719  4719 D BluetoothInputDevice: Proxy object disconnected
,07-01 12:11:03.834  4719  4719 D HidProfile: Bluetooth service disconnected
07-01 12:11:03.844  3260  3260 D HealthService: Received stop request...Stopping profile...
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:03.844  3260  3260 D PanService: Received stop request...Stopping profile...
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:03.844  4719  4719 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 12:11:03.844  4719  4719 D PanProfile: Bluetooth service disconnected
07-01 12:11:03.844   912   912 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-01 12:11:03.844  3260  3260 D BluetoothMapService: Received stop request...Stopping profile...
,07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:03.844  4719  4719 D BluetoothMap: Proxy object disconnected
07-01 12:11:03.844  4719  4719 D MapProfile: Bluetooth service disconnected
,07-01 12:11:03.844  3260  3260 D SapService: Received stop request...Stopping profile...
07-01 12:11:03.844  3260  3260 D SapService: Stopping Bluetooth SapService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:03.844  4719  4719 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-01 12:11:03.844  4719  4719 D SapProfile: Bluetooth service disconnected
07-01 12:11:03.844  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 12:11:03.844  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-01 12:11:03.844  3260  3260 D BluetoothA2dp: Proxy object disconnected
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-01 12:11:03.844  3260  8040 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 12:11:03.844  3260  3260 I GKI_LINUX: GKI_exit_task 2 done
07-01 12:11:03.844  3260  3260 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 12:11:03.844  3260  3260 V Avrcp   : cleanup
,07-01 12:11:03.844  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:11:03.844  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:11:03.844  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 12:11:03.844  3260  3260 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 12:11:03.844  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:11:03.844  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:03.844  3260  3260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 12:11:03.844  3260  3260 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-01 12:11:03.844  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:11:03.844  3260  3260 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:03.844  3260  3260 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,07-01 12:11:03.854  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-01 12:11:03.854  3260  3260 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 12:11:03.854  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-01 12:11:03.854  3260  3312 D BluetoothAdapterProperties: Setting state to 10
07-01 12:11:03.854  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 12:11:03.854  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:03.854  3260  3312 D BluetoothAdapterService: updateAdapterState state is 10
,07-01 12:11:03.854  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:03.854  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-01 12:11:03.854  3260  3312 I BluetoothAdapterState: Entering OffState
07-01 12:11:03.854  3260  3260 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-01 12:11:03.854  3260  3260 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-01 12:11:03.854  3260  3686 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 12:11:03.854  4719  4735 D Bluetoothsap: onBluetoothStateChange: up=false
07-01 12:11:03.854  4719  4735 D Bluetoothsap: Unbinding service...
,07-01 12:11:03.854  4719  4731 D BluetoothPbap: onBluetoothStateChange: up=false
,07-01 12:11:03.854  4719  4729 D BluetoothMap: onBluetoothStateChange: up=false
,07-01 12:11:03.854  4719  4729 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-01 12:11:03.854   912  1036 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 12:11:03.854  4719  4735 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 12:11:03.854  3407  3421 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 12:11:03.854  8156  8156 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:03.854   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:03.854   912   912 I InputMethodManagerService: [BT Setting State] State =10
07-01 12:11:03.854   912   912 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-01 12:11:03.854  8156  8156 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:03.864  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.864  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:03.864  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.864  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: Can provide trust state change: false
07-01 12:11:03.864  1972  1972 D Coffee - GoogleTrustAgent: setManagingTrust
07-01 12:11:03.864  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: setManagingTrust success
07-01 12:11:03.864  1972  1972 I Coffee - BluetoothConnectionTracker: Bluetooth adapter off, revoking trust
07-01 12:11:03.864  1746  1746 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:11:03.864  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:03.864   912  3665 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 12:11:03.864   912  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 12:11:03.864  1195  1195 D KeyguardViewMediator: onTrustChanged( Showing = true , userId = 0 )
07-01 12:11:03.864  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 12:11:03.864  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 12:11:03.874  8156  8156 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D QSpanel : label top:23
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 12:11:03.884  1195  1195 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-01 12:11:03.954   912   928 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-01 12:11:03.954   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.954   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.954   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:03.954   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:03.984  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-01 12:11:03.984  7717  7784 I jxcore-log: 
,07-01 12:11:03.994  8172  8172 E Zygote  : MountEmulatedStorage()
,07-01 12:11:03.994  8172  8172 E Zygote  : v2
07-01 12:11:03.994  8172  8172 I libpersona: KNOX_SDCARD checking this for 10146
07-01 12:11:03.994  8172  8172 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:04.004   912   928 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8172 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:04.004   912   928 I ActivityManager: Killing 7245:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-01 12:11:04.064  8172  8172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:04.064  8172  8172 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:04.064  8172  8172 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 12:11:04.074  8172  8172 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:04.084  8172  8172 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:04.094  8172  8172 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-01 12:11:04.294   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-01 12:11:04.294   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:04.294  8172  8190 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-01 12:11:04.314   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-01 12:11:04.314   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:04.314  8172  8190 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-01 12:11:04.314   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-01 12:11:04.314   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:04.314  8172  8193 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-01 12:11:04.324   264   571 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-01 12:11:04.324   264   571 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 12:11:04.324  8172  8193 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-01 12:11:04.394  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-01 12:11:04.394  7717  7784 I jxcore-log: 
,07-01 12:11:04.414  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-01 12:11:04.414  7717  7784 I jxcore-log: 
,07-01 12:11:04.424  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-01 12:11:04.424  7717  7784 I jxcore-log: 
,07-01 12:11:04.434  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-01 12:11:04.434  7717  7784 I jxcore-log: 
,07-01 12:11:04.444  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-01 12:11:04.444  7717  7784 I jxcore-log: 
,07-01 12:11:04.474  8172  8172 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-01 12:11:04.474  8172  8172 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-01 12:11:04.494  8172  8172 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 188-191)
,07-01 12:11:04.494  8172  8172 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:11:04.494  8172  8172 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3c367fa8}
,07-01 12:11:04.494  8172  8172 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 12:11:04.504  8172  8172 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 12:11:04.514  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:04.514  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-01 12:11:04.524  8172  8172 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 12:11:04.524  8172  8172 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 12:11:04.524  8172  8172 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 12:11:04.544  8172  8172 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 12:11:04.544  8172  8172 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-01 12:11:04.544  8172  8172 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-01 12:11:04.544  8172  8172 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-01 12:11:04.544  8172  8172 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-01 12:11:04.544  8172  8172 I Adreno-EGL: Build Date: 11/19/14 Wed
07-01 12:11:04.544  8172  8172 I Adreno-EGL: Local Branch: mybranch5813579
07-01 12:11:04.544  8172  8172 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-01 12:11:04.544  8172  8172 I Adreno-EGL: Local Patches: NONE
07-01 12:11:04.544  8172  8172 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-01 12:11:04.554   298   298 E SMD     : DCD ON
,07-01 12:11:04.614  8172  8220 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-01 12:11:04.624  8172  8172 I NSApplication: Starting up...
,07-01 12:11:04.644   912  3665 I ActivityManager: Killing 6059:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-01 12:11:04.714   912  1689 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-01 12:11:04.714   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:04.714   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:04.714   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:04.714   912  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:04.794  8228  8228 E Zygote  : MountEmulatedStorage()
07-01 12:11:04.794  8228  8228 E Zygote  : v2
07-01 12:11:04.794  8228  8228 I libpersona: KNOX_SDCARD checking this for 10158
07-01 12:11:04.794  8228  8228 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:04.804   912  1689 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8228 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-01 12:11:04.844  8228  8228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:04.844  8228  8228 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:04.844  8228  8228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 12:11:04.864  8228  8228 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:04.864  8228  8228 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:04.874  8228  8228 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-01 12:11:04.884  8228  8228 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 12:11:04.884  8228  8228 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-01 12:11:04.884  8228  8228 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-01 12:11:04.894  8228  8228 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:04.894  8228  8228 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-01 12:11:04.904  8228  8228 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-01 12:11:04.924   912  1485 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 12:11:04.934   912  1533 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:04.934  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:04.934  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:04.934  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:04.934  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:04.934   912  1458 I ActivityManager: Killing 7266:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-01 12:11:04.934   912  1336 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:04.934   912   928 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
07-01 12:11:04.934   912  1460 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:04.934   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:04.934   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:04.934   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:04.934   912   928 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:04.954  3260  3435 D bt_upio : ..proc_btwrite_timeout..
,07-01 12:11:04.954   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:04.984  8243  8243 E Zygote  : MountEmulatedStorage()
07-01 12:11:04.984  8243  8243 E Zygote  : v2
07-01 12:11:04.984  8243  8243 I libpersona: KNOX_SDCARD checking this for 10200
07-01 12:11:04.984  8243  8243 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:04.984   912   928 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8243 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:05.024  8243  8243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:11:05.024  8243  8243 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:05.024  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 12:11:05.024  8243  8243 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
07-01 12:11:05.024  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:11:05.024   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-01 12:11:05.024   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:11:05.024   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:11:05.024   912  1094 D BatteryService: stay LED for fully charged
,07-01 12:11:05.024   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:11:05.024  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-01 12:11:05.024  1195  1195 I KeyguardEffectViewController: *** don't update sliding image ***
,07-01 12:11:05.034   912   912 I MotionRecognitionService: Plugged
,07-01 12:11:05.034   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:11:05.044  8243  8243 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:05.044  8243  8243 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:05.044  3260  3318 D bt_vendor: op for 7
,07-01 12:11:05.044  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:11:05.054  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:11:05.054  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:05.054  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:11:05.054  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:11:05.054  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:11:05.054  8243  8243 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-01 12:11:05.084   912  1485 I ActivityManager: Killing 7297:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-01 12:11:05.094  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:05.094   912  3696 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.094  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:05.094  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:05.094  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:05.094  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:05.104  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 12:11:05.104  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:05.104  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 12:11:05.104   912  1655 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.104  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:05.104  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:05.104  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:05.104  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:05.114  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:11:05.114  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:11:05.114  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:05.124   912  1719 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:05.124  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:05.124   912  1336 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 12:11:05.124  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:05.124  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:05.124  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 12:11:05.124  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:05.124  6583  6583 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 12:11:05.134  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 12:11:05.134  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-01 12:11:05.134  7907  7907 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 12:11:05.134  7907  7907 D WifiDirectBR: stopServiceTest : false
,07-01 12:11:05.134  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:11:05.144  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:05.144  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-01 12:11:05.144   912  1533 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:05.144  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:05.154   912  1689 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.154  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:05.154  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:05.154  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 12:11:05.154  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:05.154   912  3665 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.154  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:05.164  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:05.174   912  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.174  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:05.174  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:05.174  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:05.174  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:05.184  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:05.184   912  1094 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.184  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:05.184  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:05.184  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:05.184  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:05.194  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.194  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.204  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 12:11:05.204   912  1245 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 12:11:05.204   912  1245 D ActivityManager: caller:android.app.ApplicationThreadProxy@6bc1ba5, r.packageName :com.android.settings
,07-01 12:11:05.204  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.214  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:05.214  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.214  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.214  3260  3260 D BtConfig.SecureMode: isSecureModeOn:false
,07-01 12:11:05.214   912   928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.214   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@80eaf2b, r.packageName :com.android.bluetooth
,07-01 12:11:05.224  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 12:11:05.224   912  1689 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-01 12:11:05.224   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d796c34, r.packageName :com.android.settings
,07-01 12:11:05.234  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.234  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:05.234  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.244  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 12:11:05.244   912   928 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 12:11:05.244   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@36a8bfd2, r.packageName :com.android.settings
,07-01 12:11:05.254  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.254  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:05.254  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.524  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:05.524  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:05.524  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:05.524  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a17a14d removed from the list
,07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4f9113 added. We now have 2 listener(s)
07-01 12:11:05.524  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:11:05.524  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:05.524  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:05.524  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:05.524  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4f9113 removed from the list
,07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:05.524  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16c6bf50 added. We now have 2 listener(s)
07-01 12:11:05.524  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:11:05.524  7717  7774 D BluetoothAdapter: disable()
,07-01 12:11:05.524   912  1458 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-01 12:11:05.524  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:05.524  7717  7774 D BluetoothAdapter: enable()
,07-01 12:11:05.524   912  3696 W ActivityManager: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:05.524   912  3696 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-01 12:11:05.524   912  3696 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:05.524   912  3696 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 12:11:05.524   912  3696 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-01 12:11:05.524   912  3696 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-01 12:11:05.524   912  3696 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-01 12:11:05.524   912  3696 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 12:11:05.524   912  3696 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 12:11:05.524   912  3696 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 12:11:05.534   912  3696 D SettingsProvider: name = bluetooth_on
,07-01 12:11:05.534   912  1036 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 12:11:05.534   912  1036 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 12:11:05.534   912  1036 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-01 12:11:05.534  3260  3312 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-01 12:11:05.534  3260  3312 D BluetoothAdapterProperties: Setting state to 11
07-01 12:11:05.534  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 12:11:05.534  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:05.534  3260  3312 D BluetoothAdapterService: updateAdapterState state is 11
,07-01 12:11:05.534  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:05.534  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-01 12:11:05.534  3260  3312 D BtConfig.SecureMode: isSecureModeOn:false
07-01 12:11:05.534  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 12:11:05.534  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-01 12:11:05.534  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:11:05.534  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-01 12:11:05.534  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:11:05.534  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-01 12:11:05.544   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.544   912   912 I InputMethodManagerService: [BT Setting State] State =11
,07-01 12:11:05.544  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.544  1746  1746 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 12:11:05.544  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.544   912  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.544  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:05.544  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.544   912  1460 D ActivityManager: caller:android.app.ApplicationThreadProxy@95b17a0, r.packageName :com.android.bluetooth
,07-01 12:11:05.544   912   928 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 12:11:05.544   912  1485 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 12:11:05.544  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,07-01 12:11:05.544  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 12:11:05.544  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 12:11:05.554  3260  3260 D HeadsetService: Received start request. Starting profile...
07-01 12:11:05.554  3260  3260 D HeadsetStateMachine: make
07-01 12:11:05.554  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 12:11:05.554  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 12:11:05.554  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.554  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.554   912  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.554   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@29af071e, r.packageName :com.android.bluetooth
,07-01 12:11:05.554  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,07-01 12:11:05.554  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 12:11:05.554  3260  3260 E HeadsetStateMachine: # of Max HF connection is 2
07-01 12:11:05.554  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 12:11:05.554   912  3665 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.554   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@33ea0dcc, r.packageName :com.android.bluetooth
,07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,07-01 12:11:05.564  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-01 12:11:05.564   912   928 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.564   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e40772a, r.packageName :com.android.bluetooth
,07-01 12:11:05.564   912  1094 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 12:11:05.564  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 12:11:05.564   912  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.564   912  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@ac6dbf6, r.packageName :com.android.bluetooth
07-01 12:11:05.564   912  1460 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 12:11:05.564  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 12:11:05.564  3260  3260 I bluedroid: get_profile_interface handsfree
07-01 12:11:05.564   912  1460 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:05.564   912  1460 D ActivityManager: caller:android.app.ApplicationThreadProxy@107cc182, r.packageName :com.android.bluetooth
,07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 12:11:05.564  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 12:11:05.564  3260  3260 E DualScoManager: Dual Sco Manager already instantiated
07-01 12:11:05.564  3260  3312 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 12:11:05.564  3260  3260 I DualScoManager: Set HeadsetServiceHelper
07-01 12:11:05.564  3260  3260 D BluetoothAtMessage: createCMTIContentObservers
07-01 12:11:05.564   912  1689 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 12:11:05.564   912  3696 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-01 12:11:05.564   912  3696 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 12:11:05.564   912  3696 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:11:05.564   912  3696 D SettingsProvider: selectionArgs: false
07-01 12:11:05.564   912  3696 D SettingsProvider: selectionArgs: 1002
07-01 12:11:05.564   912  3696 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:11:05.564   912  3696 D SettingsProvider: ret = -1
07-01 12:11:05.564   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@1bb3a8d0, r.packageName :com.android.bluetooth
,07-01 12:11:05.574  3260  8272 D HeadsetStateMachine: Enter Disconnected: -2
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D QSpanel : label top:23
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:05.574  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:05.574  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:05.574  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 12:11:05.574  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 12:11:05.574  3260  3312 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 12:11:05.574  3260  3312 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 12:11:05.574  3260  3312 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-01 12:11:05.574  3260  8272 E HeadsetStateMachine: set to mRemoteBrsf = 0
07-01 12:11:05.574  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:05.574  3260  8272 D HeadsetStateMachine: map size, before remove : 0
07-01 12:11:05.574  3260  8272 D HeadsetStateMachine: map size, after remove: 0
07-01 12:11:05.574  3260  8272 D HeadsetStateMachine: mNextConnectingDevice : null
07-01 12:11:05.574  3260  3260 D A2dpService: Received start request. Starting profile...
07-01 12:11:05.574  3260  3260 V Avrcp   : make
07-01 12:11:05.574  3260  3260 V Avrcp   : Avrcp
07-01 12:11:05.574  3260  3260 I bluedroid: get_profile_interface avrcp
,07-01 12:11:05.574  3260  3260 V Avrcp   : start
,07-01 12:11:05.574  3260  3260 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-01 12:11:05.584  3260  3260 V Avrcp   : ++registerMediaPlayers++
,07-01 12:11:05.584  3260  3260 I Avrcp   : No of Audio players :: 2
07-01 12:11:05.584  3260  3260 I Avrcp   : App Package name is com.google.android.music
,07-01 12:11:05.584  3260  3260 I Avrcp   : App pkg name is Google Play Music
07-01 12:11:05.584  3260  3260 I Avrcp   : Name::Google Play Music
07-01 12:11:05.584  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-01 12:11:05.584  3260  3260 I Avrcp   : App Package name is com.sec.android.app.music
,07-01 12:11:05.584  3260  3260 I Avrcp   : App pkg name is Music
07-01 12:11:05.584  3260  3260 I Avrcp   : Name::Music
07-01 12:11:05.584  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-01 12:11:05.584  3260  3260 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-01 12:11:05.584  3260  3260 I Avrcp   : No of Video players :: 1
07-01 12:11:05.584  3260  3260 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-01 12:11:05.584  3260  3260 I Avrcp   : Video App pkg name is Video Player
07-01 12:11:05.584  3260  3260 I Avrcp   : Name::Video Player
07-01 12:11:05.584  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-01 12:11:05.584  3260  3260 I Avrcp   : Add tempPlayer
07-01 12:11:05.584  3260  3260 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-01 12:11:05.584  3260  3260 I Avrcp   : Total no of players: 4
07-01 12:11:05.584  3260  3260 V Avrcp   : swapping the samsung player with 1st player
07-01 12:11:05.584  3260  3260 I Avrcp   :  Updating now playing list upon AVRCP Start
07-01 12:11:05.584  3260  8273 V Avrcp   : handleMessage, msg=207
07-01 12:11:05.584  3260  8273 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-01 12:11:05.584  3260  3260 D A2dpStateMachine: make
,07-01 12:11:05.584  3260  3260 I bluedroid: get_profile_interface a2dp
07-01 12:11:05.584  3260  8275 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 12:11:05.584  3260  3260 E bt-btif : warning : media task started media_task_refcnt 1 
,07-01 12:11:05.584  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:05.584  3260  3260 D HidService: Received start request. Starting profile...
07-01 12:11:05.584  3260  3260 I bluedroid: get_profile_interface hidhost
07-01 12:11:05.584  3260  3260 D HidService: setHidService(): set to: null
07-01 12:11:05.584  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.584  3260  3260 D HeadsetStateMachine: Try to query the phonestate on bind
,07-01 12:11:05.584  1398  1417 I Telecom : BluetoothPhoneService: queryPhoneState
07-01 12:11:05.584  3260  8274 D A2dpStateMachine: Enter Disconnected: -2
,07-01 12:11:05.594  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-01 12:11:05.594  3260  8273 D BluetoothMediaBrowser: no now playing list
07-01 12:11:05.594  3260  8273 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-01 12:11:05.594  3260  8273 D Avrcp   :  checkNowPlayingList start
07-01 12:11:05.594  3260  3260 D HealthService: Received start request. Starting profile...
,07-01 12:11:05.594  3260  3260 I bluedroid: get_profile_interface health
,07-01 12:11:05.594  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.594  3260  3260 D HeadsetStateMachine: Proxy object connected
,07-01 12:11:05.594  3260  3260 D PanService: Received start request. Starting profile...
07-01 12:11:05.594  3260  3260 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 12:11:05.594  3260  3260 I bluedroid: get_profile_interface pan
07-01 12:11:05.594  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.594  3260  3260 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-01 12:11:05.594  3260  3260 D HeadsetPhoneState: sendDeviceDataStateChanged
07-01 12:11:05.594  3260  8272 D HeadsetStateMachine: Disconnected process message: 11
07-01 12:11:05.594  3260  8272 D HeadsetStateMachine: Disconnected process message: 18
,07-01 12:11:05.594  3260  3260 D BluetoothMapService: Received start request. Starting profile...
,07-01 12:11:05.604  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
,07-01 12:11:05.604  3260  3260 D HeadsetPhoneState: Signal level : previous=0 curr=2
07-01 12:11:05.604  3260  3260 D SapService: Received start request. Starting profile...
07-01 12:11:05.604  3260  3260 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-01 12:11:05.604  3260  3260 I bluedroid: get_profile_interface sap
07-01 12:11:05.604  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.604  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:11:05.604  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-01 12:11:05.604  3260  8272 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-01 12:11:05.604  3260  8272 D HeadsetStateMachine: Disconnected process message: 11
,07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-01 12:11:05.604  3260  3260 E BluetoothAdapterService(135028719): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-01 12:11:05.604  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-01 12:11:05.604  3260  3312 I bluedroid: enable
,07-01 12:11:05.614  3260  3315 E bt-btif : Calling BTA_HhEnable
07-01 12:11:05.614  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:05.614  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:05.614  3260  3315 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-01 12:11:05.614  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-01 12:11:05.614  3260  3315 E BluetoothServiceJni: populateRssiValuesNative
07-01 12:11:05.614  3260  3315 I bluedroid: getModelRssiValues
07-01 12:11:05.614  3260  3315 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
07-01 12:11:05.614  3260  3318 D bt_upio : proc btwrite assertion
,07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Name is: Galaxy Note3
07-01 12:11:05.614   912   912 D SettingsProvider: name = bluetooth_name
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Scan Mode:20
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-01 12:11:05.614  3260  3315 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-01 12:11:05.614  3260  3315 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,07-01 12:11:05.614  3260  3315 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-01 12:11:05.614  3260  3315 E bt-btif : JVenable fails
07-01 12:11:05.614  3260  3315 D bte_conf: Device ID record 1 : primary
07-01 12:11:05.614  3260  3315 D bte_conf:   vendorId            = 0075
07-01 12:11:05.614  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.614  3260  3315 D bte_conf:   vendorIdSource      = 0001
07-01 12:11:05.614  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.614  3260  3315 D bte_conf:   product             = 0100
07-01 12:11:05.614  3260  3315 D bte_conf:   version             = 0200
07-01 12:11:05.614  3260  3315 D bte_conf:   clientExecutableURL = 
07-01 12:11:05.614  3260  3315 D bte_conf:   serviceDescription  = 
07-01 12:11:05.614  3260  3315 D bte_conf:   documentationURL    = 
07-01 12:11:05.614  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 12:11:05.614  3260  3315 D bte_conf: bte_load_did_conf no section named DID2.
,07-01 12:11:05.614  3260  3315 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 12:11:05.614  3260  3315 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 12:11:05.614  3260  3312 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 12:11:05.614  3260  3312 D BluetoothAdapterProperties: ScanMode =  20
07-01 12:11:05.614  3260  3312 D BluetoothAdapterProperties: State =  11
07-01 12:11:05.614  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.614  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.614   912  1533 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 12:11:05.614  3260  3312 D BluetoothAdapterProperties: Setting state to 12
07-01 12:11:05.614  3260  3312 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Scan Mode:21
07-01 12:11:05.614  3260  3315 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 12:11:05.614   912  1689 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-01 12:11:05.614   912  1689 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 12:11:05.614   912  1689 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 12:11:05.614   912  1689 D SettingsProvider: selectionArgs: false
07-01 12:11:05.614   912  1689 D SettingsProvider: selectionArgs: 1002
07-01 12:11:05.614   912  1689 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 12:11:05.614   912  1689 D SettingsProvider: ret = -1
07-01 12:11:05.614  3260  3312 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 12:11:05.614  3260  3312 D BluetoothAdapterService: updateAdapterState state is 12
,07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624   912  1689 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.624   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@8271494, r.packageName :com.android.bluetooth
,07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:05.624  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.624  3260  3312 D BluetoothAdapterService: Autoconnection is available 
07-01 12:11:05.624  3260  3312 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-01 12:11:05.624  3260  3312 D BluetoothAdapterService: starting service from this receiver
,07-01 12:11:05.624   912  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:05.624   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@1bec8f32, r.packageName :com.android.bluetooth
,07-01 12:11:05.624  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.624  3260  3260 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-01 12:11:05.624  3260  3260 I BluetoothPbapService: Handler(): got msg=1
,07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.624  3260  3312 I BluetoothAdapterState: Entering On State from state = 11
07-01 12:11:05.624   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.624   912  1094 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-01 12:11:05.624   912  1036 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:05.624   912  1036 D BluetoothPan: Binding service...
,07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.624  3260  8280 V BluetoothPbapService: PBAP Service initSocket try: 0
07-01 12:11:05.624   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-01 12:11:05.624  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.624  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634   912  1036 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.634  1428  2103 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:05.634  3260  8280 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.634  3260  8280 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
07-01 12:11:05.634  3260  8280 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 12:11:05.634  3260  8280 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 12:11:05.634  3260  8280 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39933347
07-01 12:11:05.634  3260  8280 D BluetoothSocket: channel: 19
07-01 12:11:05.634  3260  8280 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-01 12:11:05.634   912  1036 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.634  3407  3417 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:05.634  3260  3268 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.634   912   912 D BluetoothPan: BluetoothPAN Proxy object connected
,07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.634   912  1036 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.634  4719  4729 D Bluetoothsap: onBluetoothStateChange: up=true
07-01 12:11:05.634  4719  4729 D Bluetoothsap: Binding service...
07-01 12:11:05.634  3260  3318 D bt_vendor: op for 7
,07-01 12:11:05.634  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.644  3260  3260 D BluetoothA2dp: Proxy object connected
07-01 12:11:05.644  3260  3260 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-01 12:11:05.644  4719  4729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-01 12:11:05.644  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.644  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.644   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-01 12:11:05.644  4719  4729 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-01 12:11:05.644  4719  4735 D BluetoothPbap: onBluetoothStateChange: up=true
,07-01 12:11:05.644  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.644  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.644  4719  4719 D Bluetoothsap: BluetoothSAP Proxy object connected
07-01 12:11:05.644  4719  4719 D SapProfile: Bluetooth service connected
07-01 12:11:05.644  4719  4719 D Bluetoothsap: getConnectedDevices()
,07-01 12:11:05.644   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-01 12:11:05.644  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.644  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.644  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.644  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.644  4719  4719 D BluetoothPbap: Proxy object connected
,07-01 12:11:05.644  4719  4719 D PbapServerProfile: Bluetooth service connected
,07-01 12:11:05.644  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.644  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.644   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.644  1398  8117 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:05.644  4719  4731 D BluetoothMap: onBluetoothStateChange: up=true
,07-01 12:11:05.654  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.654  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.654   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-01 12:11:05.654  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.654  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.654  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.654  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.654  4719  4719 D BluetoothMap: Proxy object connected
07-01 12:11:05.654  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.654  4719  4719 D MapProfile: Bluetooth service connected
07-01 12:11:05.654  3260  3318 D bt_upio : BT_WAKE is asserted already
,07-01 12:11:05.654   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 12:11:05.654  4719  4719 D HeadsetProfile: Bluetooth service connected
,07-01 12:11:05.654  4719  4735 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:05.654   912  1036 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.654  7883  7894 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:05.654  4719  4729 D BluetoothPan: Binding service...
,07-01 12:11:05.654   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-01 12:11:05.664  4719  4719 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 12:11:05.664  4719  4719 D PanProfile: Bluetooth service connected
,07-01 12:11:05.664  4719  4735 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-01 12:11:05.664   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-01 12:11:05.664   912  1036 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:05.664   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-01 12:11:05.664   912   912 D BluetoothA2dp: Proxy object connected
07-01 12:11:05.664  4719  4731 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:05.664  4719  4719 D BluetoothInputDevice: Proxy object connected
07-01 12:11:05.664  4719  4719 D HidProfile: Bluetooth service connected
,07-01 12:11:05.664   912  1036 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:05.664  4719  4719 D BluetoothA2dp: Proxy object connected
07-01 12:11:05.664  4719  4719 D A2dpProfile: Bluetooth service connected
,07-01 12:11:05.664   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.664  1398  1417 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 12:11:05.664   912  1036 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 12:11:05.664  1398  8117 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 12:11:05.664  3407  3421 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 12:11:05.674   912  1036 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 12:11:05.674  3407  3407 D BluetoothA2dp: Proxy object connected
07-01 12:11:05.674   912  1036 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-01 12:11:05.674  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-01 12:11:05.674  1972  1972 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
07-01 12:11:05.674  1972  1972 E Coffee - BluetoothTrustlet: Illegal Bluetooth address.null
07-01 12:11:05.674  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: Can provide trust state change: true
07-01 12:11:05.674  1972  1972 D Coffee - GoogleTrustAgent: setManagingTrust
,07-01 12:11:05.674  1972  1972 I TrustAgentApi - GoogleTrustAgentServiceImpl: setManagingTrust success
,07-01 12:11:05.674   912   912 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 12:11:05.674   912   912 I InputMethodManagerService: [BT Setting State] State =12
07-01 12:11:05.674   912   912 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 12:11:05.674  1746  1746 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 12:11:05.684  7883  7883 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.684  4719  4719 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.684  1398  1398 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@26b6b7e1, true
,07-01 12:11:05.684  1398  1398 D BluetoothHeadset: registerMessageListener
07-01 12:11:05.684  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 12:11:05.684  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 12:11:05.684  3260  3449 D HeadsetService: registerMessageListener
07-01 12:11:05.684  3260  3449 D HeadsetService: registerMessageListener
07-01 12:11:05.684  3260  8272 D HeadsetStateMachine: Disconnected process message: 70
,07-01 12:11:05.684  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-01 12:11:05.684  3260  8272 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@d36a774
07-01 12:11:05.684  1398  1398 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-01 12:11:05.684  1195  1618 D BluetoothTile:  handleUpdatestate:false name:null
07-01 12:11:05.684  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 12:11:05.684  3260  8272 D HeadsetStateMachine: Disconnected process message: 9
07-01 12:11:05.684  3260  8272 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-01 12:11:05.684   304  1557 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-01 12:11:05.684   304  1557 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-01 12:11:05.684   304  1557 V voice   : voice_set_parameters: exit with code(-2)
07-01 12:11:05.684   304  1557 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-01 12:11:05.684   304  1557 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-01 12:11:05.684   304  1557 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-01 12:11:05.684   304  1557 V audio_hw_primary: adev_set_parameters: exit
,07-01 12:11:05.684  3260  8272 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-01 12:11:05.684   912  1689 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:11:05.684  3260  8282 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-01 12:11:05.684  4719  4719 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-01 12:11:05.684  4719  4719 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-01 12:11:05.694   912  1719 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-01 12:11:05.694  1195  1195 D KeyguardViewMediator: onTrustChanged( Showing = true , userId = 0 )
,07-01 12:11:05.694  3260  8282 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 12:11:05.694  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 12:11:05.694  3260  8282 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-01 12:11:05.694  3260  8282 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 12:11:05.694  3260  8282 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 12:11:05.694  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.694  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.694  3260  8282 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f02d49d
07-01 12:11:05.694  3260  8282 D BluetoothSocket: channel: 5
,07-01 12:11:05.694  4719  4719 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 12:11:05.694   912  1689 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 12:11:05.694   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@156e9e8e, r.packageName :com.android.settings
,07-01 12:11:05.694  1643  1643 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 12:11:05.704  4719  4719 D DockEventReceiver: finishStartingService: stopping service
,07-01 12:11:05.704  4719  4719 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 12:11:05.704  3260  3260 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@80c5fef
07-01 12:11:05.704  3260  3260 D BtConfig.SecureMode: isSecureModeOn:false
,07-01 12:11:05.704   912  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 12:11:05.704   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b788abc, r.packageName :com.android.bluetooth
,07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D QSpanel : label top:23
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:05.714  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:05.714  1195  1195 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-01 12:11:05.714   912  1460 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-01 12:11:05.724  3260  8288 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 12:11:05.724  3260  3318 D bt_vendor: op for 7
07-01 12:11:05.724  3260  3318 D bt_upio : BT_WAKE is asserted already
07-01 12:11:05.724  3260  8288 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[84]}
07-01 12:11:05.724  3260  8288 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 12:11:05.724  3260  8288 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 12:11:05.724  3260  8288 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ebd1d99
07-01 12:11:05.724  3260  8288 D BluetoothSocket: channel: 12
07-01 12:11:05.724  3260  8288 I BtOppRfcommListener: Accept thread started.
,07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:05.744  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:05.744  7717  7774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:05.744  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:05.744  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:05.744  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:05.744  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:05.744  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16c6bf50 removed from the list
,07-01 12:11:05.744  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 12:11:05.744  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ca0549 added. We now have 2 listener(s)
07-01 12:11:05.744  7717  7774 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 12:11:05.744  7717  7774 I WifiManager: packageName : com.test.thalitest
07-01 12:11:05.744   912  1533 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 12:11:05.744   912  1533 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 12:11:05.744   912  1533 D SecContentProvider2: mCursor = null
,07-01 12:11:05.744   912  1533 D WifiService: setWifiEnabled: false pid=7717, uid=10079
07-01 12:11:05.744   912  1533 D SettingsProvider: name = wifi_on
,07-01 12:11:05.754  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:05.754  7717  7774 I WifiManager: packageName : com.test.thalitest
07-01 12:11:05.754   912  1460 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 12:11:05.754   912  1460 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 12:11:05.754   912  1460 D SecContentProvider2: mCursor = null
,07-01 12:11:05.754   912  1460 D WifiService: setWifiEnabled: true pid=7717, uid=10079
07-01 12:11:05.754   912  1460 W ActivityManager: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:05.754   912  1460 W WifiService: Failed getting userId using ActivityManagerNative
07-01 12:11:05.754   912  1460 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7717, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 12:11:05.754   912  1460 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 12:11:05.754   912  1460 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-01 12:11:05.754   912  1460 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-01 12:11:05.754   912  1460 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-01 12:11:05.754   912  1460 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 12:11:05.754   912  1460 D SettingsProvider: name = wifi_on
,07-01 12:11:05.754   912  1149 E WifiHW  : ##################### set firmware type 0 #####################
,07-01 12:11:05.754   293  1064 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-01 12:11:05.754   293  1064 I WifiHW  : module is semco
07-01 12:11:05.754   293  1064 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-01 12:11:05.754   293  1064 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-01 12:11:05.754   293  1064 E WifiHW  : TEMP_FAILURE_RETRY complete
07-01 12:11:05.754   293  1064 D SoftapController: Softap fwReload - Ok
,07-01 12:11:05.764   293  1064 D CommandListener: Setting iface cfg
07-01 12:11:05.764   293  1064 D CommandListener: Trying to bring down wlan0
,07-01 12:11:05.764   293  1064 D CommandListener: Clearing all IP addresses on wlan0
,07-01 12:11:05.764   912  1149 E WifiHW  : supplicant_name : p2p_supplicant
,07-01 12:11:05.764  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 12:11:05.764   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:05.764  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:05.774   912  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 12:11:05.784  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:05.784  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:05.784  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 12:11:05.784   912  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 12:11:05.784  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:05.784  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-01 12:11:05.784  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:11:05.784  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:05.784  1195  1195 D HotspotTile: onReceive : 2, 0
,07-01 12:11:05.784  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:05.784   912  1456 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:05.784  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:05.784  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:05.784  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:05.784  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:05.794  8292  8292 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-01 12:11:05.794  8292  8292 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-01 12:11:05.804  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:05.804  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 12:11:05.804   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8292
07-01 12:11:05.804   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 12:11:05.804  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:05.804  8292  8292 I wpa_supplicant: ssSupport state is = 1
,07-01 12:11:05.804  8292  8292 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-01 12:11:05.804  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-01 12:11:05.804   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8292
07-01 12:11:05.804   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-01 12:11:05.804  1195  1195 D QSpanel : label top:23
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
,07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:05.804  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:06.074   347   347 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-01 12:11:06.324  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-01 12:11:06.344  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:06.344  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 12:11:06.344   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8292
07-01 12:11:06.344   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-01 12:11:06.344  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:06.344  8292  8292 I wpa_supplicant: ssSupport state is = 1
07-01 12:11:06.344  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:06.344  8292  8292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:06.344  8292  8292 E wpa_supplicant: SIM READ ERROR
07-01 12:11:06.344  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:06.344  8292  8292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-01 12:11:06.344  8292  8292 E wpa_supplicant: SIM READ ERROR
07-01 12:11:06.344  8292  8292 I wpa_supplicant: Blacklist: Clear (all) 
07-01 12:11:06.344  8292  8292 I wpa_supplicant: wpa_default_ap_write_once
,07-01 12:11:06.344  8292  8292 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 12:11:06.344  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:06.344  8292  8292 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,07-01 12:11:06.344  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:06.344  8292  8292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:06.354  8292  8292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:11:06.564  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-01 12:11:06.564  7717  7784 I jxcore-log: 
,07-01 12:11:06.574  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-01 12:11:06.574  7717  7784 I jxcore-log: 
,07-01 12:11:06.584  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-01 12:11:06.584  7717  7784 I jxcore-log: 
,07-01 12:11:06.734  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-01 12:11:06.734  7717  7784 I jxcore-log: 
,07-01 12:11:06.804   912  3696 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
07-01 12:11:06.804   912  3696 D ActivityManager: caller:android.app.ApplicationThreadProxy@14a485c1, r.packageName :com.google.android.music
,07-01 12:11:06.824   912  1458 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:06.824  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-01 12:11:06.824  7717  7784 I jxcore-log: 
,07-01 12:11:06.824   912   929 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:06.824   912   928 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:06.834   912  1094 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-01 12:11:06.834   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@261ee99f, r.packageName :com.google.android.music
,07-01 12:11:06.844  7953  8295 I MusicLeanback: Conditions not met for autocaching.
07-01 12:11:06.844  7953  8295 I MusicLeanback: Stop autocaching.
,07-01 12:11:06.864   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:06.864   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:06.864   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:06.864   912  1456 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:06.884  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-01 12:11:06.884  7717  7784 I jxcore-log: 
,07-01 12:11:06.894  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-01 12:11:06.894  7717  7784 I jxcore-log: 
,07-01 12:11:06.904   912  1456 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8298 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-01 12:11:06.914  8298  8298 E Zygote  : MountEmulatedStorage()
,07-01 12:11:06.914  8298  8298 E Zygote  : v2
07-01 12:11:06.914  8298  8298 I libpersona: KNOX_SDCARD checking this for 10015
07-01 12:11:06.914  8298  8298 I libpersona: KNOX_SDCARD not a persona
,07-01 12:11:06.974  8298  8298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 12:11:06.974  8298  8298 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:06.974  8298  8298 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-01 12:11:06.974   912  1689 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 12:11:06.994  8298  8298 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:06.994  8298  8298 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:07.014  8298  8298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-01 12:11:07.024   912  1152 E Tethering: No numeric data
,07-01 12:11:07.024   912  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-01 12:11:07.024  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 12:11:07.024  1195  1195 D HotspotTile: updateTetherState():false, false
07-01 12:11:07.024   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:07.024   912  1146 V NetworkStats: performPollLocked(flags=0x1)
,07-01 12:11:07.024   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:11:07.024  8298  8298 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 12:11:07.024   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:07.024  8298  8298 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:11:07.024   912  1146 V NetworkStats: performPollLocked() took 2ms
07-01 12:11:07.024   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:07.024   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:07.024   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:07.044  8292  8292 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-01 12:11:07.044  8298  8298 I MultiDex: VM with version 2.1.0 has multidex support
,07-01 12:11:07.044  8298  8298 I MultiDex: install
07-01 12:11:07.044  8298  8298 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 12:11:07.064  8298  8298 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-01 12:11:07.064   912  1485 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 12:11:07.064   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@31742bf0, r.packageName :com.google.android.gms
,07-01 12:11:07.064  1643  5899 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-01 12:11:07.074  1643  1643 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-01 12:11:07.084  2330  2330 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-01 12:11:07.084   912  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:11:07.084   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f7a0569, r.packageName :com.google.android.gms
,07-01 12:11:07.094  8298  8298 D WearableService: callingUid 10015, callindPid: 8298
,07-01 12:11:07.094  8292  8292 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 12:11:07.094   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8292
07-01 12:11:07.094   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:07.094  8292  8292 I wpa_supplicant: ssSupport state is = 1
,07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 12:11:07.094   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8292
07-01 12:11:07.094   347   347 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-01 12:11:07.094  8292  8292 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 12:11:07.094  8292  8292 I wpa_supplicant: ssSupport state is = 1
,07-01 12:11:07.094  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:07.094  8292  8292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:07.094  8292  8292 E wpa_supplicant: SIM READ ERROR
07-01 12:11:07.094  8292  8292 I wpa_supplicant: wpa_default_ap_write_once
07-01 12:11:07.094  8292  8292 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-01 12:11:07.094  8292  8292 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 12:11:07.104   912  1336 D ActivityManager: caller:android.app.ApplicationThreadProxy@2888171c, r.packageName :com.google.android.gms
,07-01 12:11:07.114   912  1689 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:11:07.114   912  1689 D ActivityManager: caller:android.app.ApplicationThreadProxy@294c68fa, r.packageName :com.google.android.gms
07-01 12:11:07.114  2330  8319 D LocationInitializer: Restart initialization of location
,07-01 12:11:07.124  8292  8292 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-01 12:11:07.124  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-01 12:11:07.124  1972  5828 E MDM     : [196] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-01 12:11:07.124  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-01 12:11:07.124  7717  7784 I jxcore-log: 
,07-01 12:11:07.134   912  3696 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 12:11:07.134   912  3696 D ActivityManager: caller:android.app.ApplicationThreadProxy@8e10eab, r.packageName :com.google.android.gms
,07-01 12:11:07.144  8292  8292 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-01 12:11:07.144  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-01 12:11:07.144  8292  8292 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 12:11:07.144   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-01 12:11:07.144   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 12:11:07.144  8292  8292 I wpa_supplicant: HOTSPOT20_ENABLE called
07-01 12:11:07.144  8292  8292 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 12:11:07.144  8292  8292 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 12:11:07.144  8292  8292 E wpa_supplicant: SIM READ ERROR
07-01 12:11:07.144  8292  8292 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 12:11:07.154  7953  8315 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-01 12:11:07.154  7953  7953 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-01 12:11:07.154  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-01 12:11:07.154  7717  7784 I jxcore-log: 
,07-01 12:11:07.164  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-01 12:11:07.164  7717  7784 I jxcore-log: 
,07-01 12:11:07.164  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-01 12:11:07.164  7717  7784 I jxcore-log: 
,07-01 12:11:07.174  8292  8292 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-01 12:11:07.184  8292  8292 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 12:11:07.184   912  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 12:11:07.184   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:07.184   912  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-01 12:11:07.184   912  1149 D WifiConfigStore: Loading config and enabling all networks 
,07-01 12:11:07.184  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:07.184  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:07.184  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 12:11:07.184  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-01 12:11:07.184  7717  7784 I jxcore-log: 
07-01 12:11:07.184  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:07.194  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:07.194  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:07.194  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:07.194  4719  4719 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:07.194  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 12:11:07.194  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-01 12:11:07.194  1195  1618 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 12:11:07.194   912  1149 E WifiConfigStore: Not a HS20
07-01 12:11:07.194  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 12:11:07.194  1195  1195 D HotspotTile: onReceive : 3, 0
,07-01 12:11:07.204  5842  5842 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 12:11:07.204   912  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-01 12:11:07.204   912  3665 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:07.204  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:07.204  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:07.204  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:07.204  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:07.204   912  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,07-01 12:11:07.214  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-01 12:11:07.214  7717  7784 I jxcore-log: 
,07-01 12:11:07.214   912  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-01 12:11:07.214  8292  8292 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-01 12:11:07.214  8292  8292 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-01 12:11:07.214  8292  8292 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 12:11:07.214  8292  8292 I wpa_supplicant: P2P: Current p2p state = IDLE
07-01 12:11:07.214  8292  8292 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-01 12:11:07.214  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-01 12:11:07.214  8292  8292 I wpa_supplicant: First Scan Start
,07-01 12:11:07.214  8292  8292 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 12:11:07.214  7922  7922 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 12:11:07.214   912  1149 D WifiNative-HAL: Setting external_sim to 1
,07-01 12:11:07.214   912  1149 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 12:11:07.214   912  1149 I WifiNative-HAL: startHal
07-01 12:11:07.214   912  1149 E wifi    : getStaticLongField sWifiHalHandle 0x938b086c
07-01 12:11:07.214   912  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x2025f6
07-01 12:11:07.214   912  1149 I WifiNative-HAL: Could not start hal
,07-01 12:11:07.224  1195  1195 D QSpanel : label top:23
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 12:11:07.224  1195  1195 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 12:11:07.224  3260  3318 D bt_vendor: op for 7
,07-01 12:11:07.234   912  1149 E native  : do suspend true
,07-01 12:11:07.234   912  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-01 12:11:07.234   912   912 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 12:11:07.234   912   912 D RttService: SCAN_AVAILABLE : 3
07-01 12:11:07.234   912  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:07.234   912  1167 I WifiNative-HAL: startHal
07-01 12:11:07.234   912  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9adf399c
07-01 12:11:07.234   912  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x1025fa
07-01 12:11:07.234   912  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-01 12:11:07.234   912  1167 I WifiNative-HAL: Could not start hal
07-01 12:11:07.234   912  1167 E WifiScanningService: could not start HAL
07-01 12:11:07.234   912  1168 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 12:11:07.244   293  1064 D CommandListener: Setting iface cfg
07-01 12:11:07.244   293  1064 D CommandListener: Trying to bring up p2p0
,07-01 12:11:07.244   912  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 12:11:07.244   912  1148 D WifiP2pService: P2pEnablingState
07-01 12:11:07.244   912  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
07-01 12:11:07.244   912  1148 D WifiP2pService: P2p socket connection successful
,07-01 12:11:07.244   912  1148 D WifiP2pService: P2pEnabledState
07-01 12:11:07.244   912  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-01 12:11:07.244   912   912 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:11:07.244   912  1038 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-01 12:11:07.244   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:07.244   912  1038 D WifiDisplayController: disconnect
07-01 12:11:07.244   912  1038 D WifiDisplayController: updateConnection
07-01 12:11:07.244   912  1038 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 12:11:07.244   912  1038 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 12:11:07.244   912  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-01 12:11:07.244   912  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-01 12:11:07.244   912  1149 E WifiNative-HAL: invaild command id : 215
,07-01 12:11:07.244   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:07.244   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-01 12:11:07.244  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 12:11:07.244   912  1038 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:07.244   912  1038 D WifiDisplayAdapter: onP2pDisconnected
07-01 12:11:07.244   912  1038 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 12:11:07.244   912  1038 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-01 12:11:07.244   912  1148 D WifiNative-HAL: p2pGetDeviceAddress
07-01 12:11:07.244  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 12:11:07.244   912  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
07-01 12:11:07.244   912  1719 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 12:11:07.244  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-01 12:11:07.244   912  1148 D WifiP2pService: DeviceAddress: ea:fd:2b
07-01 12:11:07.244   912  1038 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-01 12:11:07.244   912  1038 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-01 12:11:07.244   912  1038 D WifiDisplayController:  primary type: 10-0050F204-5
07-01 12:11:07.244   912  1038 D WifiDisplayController:  secondary type: null
07-01 12:11:07.244   912  1038 D WifiDisplayController:  wps: 0
07-01 12:11:07.244   912  1038 D WifiDisplayController:  grpcapab: 0
07-01 12:11:07.244   912  1038 D WifiDisplayController:  devcapab: 0
07-01 12:11:07.244   912  1038 D WifiDisplayController:  status: 3
07-01 12:11:07.244   912  1038 D WifiDisplayController:  wfdInfo: null
07-01 12:11:07.244   912  1038 D WifiDisplayController:  groupownerAddress: null
07-01 12:11:07.244   912  1038 D WifiDisplayController:  GOdeviceName: null
07-01 12:11:07.244   912  1038 D WifiDisplayController:  interfaceAddress: 
07-01 12:11:07.244   912  1038 D WifiDisplayController:  SConnectInfo : null
,07-01 12:11:07.254  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:11:07.254  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:07.254   912  1245 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:07.254  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:07.254   912  1689 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:07.254  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:07.254  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:07.254  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 12:11:07.254  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:07.254  6583  6583 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 12:11:07.264   912  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-01 12:11:07.264  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 12:11:07.264  7907  7907 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-01 12:11:07.264  7907  7907 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 12:11:07.264  7907  7907 D WifiDirectBR: stopServiceTest : false
07-01 12:11:07.264   912  1148 D WifiP2pService: InactiveState
,07-01 12:11:07.264   912  1148 D WifiP2pService: InactiveState{ what=143376 }
07-01 12:11:07.264   912  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-01 12:11:07.284  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-01 12:11:07.294  8292  8292 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-01 12:11:07.294   912  1148 D WifiP2pService: InactiveState{ what=143376 }
07-01 12:11:07.294   912  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-01 12:11:07.314  8292  8292 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-01 12:11:07.314  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-01 12:11:07.314  7717  7784 I jxcore-log: 
,07-01 12:11:07.314   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:07.314   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:07.324   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:07.324   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:07.324  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-01 12:11:07.324  7717  7784 I jxcore-log: 
,07-01 12:11:07.344  7717  7784 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-01 12:11:07.344  7717  7784 I jxcore-log: 
,07-01 12:11:07.354  7717  7784 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-01 12:11:07.354  7717  7784 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-01 12:11:07.354  7717  7784 I jxcore-log: 
,07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:11:07.374  7717  7774 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 12:11:07.374  7717  7774 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:11:07.374  7717  7774 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 12:11:07.374  7717  7774 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:11:07.374  7717  7774 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:11:07.374  7717  7774 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8ca0549 removed from the list
,07-01 12:11:07.374  7717  7774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 12:11:07.374  7717  7774 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 12:11:07.374  7717  7774 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-01 12:11:07.374  7717  7774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-01 12:11:07.374  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 12:11:07.374  7717  7774 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 12:11:07.384  7717  7774 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-01 12:11:07.384  7717  7774 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-01 12:11:07.384  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@223b22df Bundle[{}]
,07-01 12:11:07.384  7717  7774 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 12:11:07.384  7717  7774 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-01 12:11:07.394  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-01 12:11:07.394  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-01 12:11:07.394  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-01 12:11:07.394  7717  7774 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-01 12:11:07.404  7717  8328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1291, name: My test thread name)
,07-01 12:11:07.404  7717  8328 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1291, thread name: My test thread name)
07-01 12:11:07.404  7717  8328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1291, name: My test thread name)
,07-01 12:11:07.404  7717  8329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1293, name: My test thread name)
07-01 12:11:07.404  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:11:07.404  7717  7784 I jxcore-log: 
07-01 12:11:07.404  7717  8329 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1293, thread name: My test thread name)
07-01 12:11:07.404  7717  8329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1293, name: My test thread name)
,07-01 12:11:07.404  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:11:07.404  7717  7784 I jxcore-log: 
,07-01 12:11:07.404  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.404  7717  7784 I jxcore-log: 
,07-01 12:11:07.404  7717  7774 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 36
07-01 12:11:07.404  7717  7774 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 36
07-01 12:11:07.404  7717  7774 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-01 12:11:07.404  7717  7774 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-01 12:11:07.404  7717  7774 E com.test.thalitest.ThaliTestRunner: Total duration: 7995 ms
07-01 12:11:07.404  7717  7774 I System.out: Tests succeded_00
07-01 12:11:07.404  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.404  7717  7784 I jxcore-log: 
07-01 12:11:07.404  7717  7774 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 8062ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 12:11:07.404  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:07.404  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.414  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 12:11:07.414  7717  7784 I jxcore-log: 
,07-01 12:11:07.554   298   298 E SMD     : DCD ON
,07-01 12:11:07.614  3260  3435 D bt_upio : ..proc_btwrite_timeout..
,07-01 12:11:07.984  8292  8292 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
,07-01 12:11:07.984  8292  8292 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-01 12:11:07.984  8292  8292 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
,07-01 12:11:07.984  8292  8292 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-01 12:11:07.984  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-01 12:11:08.004   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:08.004   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:08.074  8292  8292 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-01 12:11:08.074  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-01 12:11:08.074  8292  8292 I wpa_supplicant: Associated with F4.99.3E
07-01 12:11:08.074  8292  8292 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-01 12:11:08.074  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-01 12:11:08.084   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:08.084   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:08.084   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:08.084   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:08.094  8292  8292 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-01 12:11:08.094  8292  8292 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-01 12:11:08.094  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-01 12:11:08.104  8292  8292 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 12:11:08.104  8292  8292 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-01 12:11:08.104  8292  8292 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,07-01 12:11:08.104  8292  8292 I wpa_supplicant: Blacklist: Clear (temp) 
07-01 12:11:08.104  8292  8292 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-01 12:11:08.104   912  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-01 12:11:08.114   912  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 12:11:08.114   912  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-01 12:11:08.114   912  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-01 12:11:08.114   912  1151 D ConnectivityService: Got NetworkAgent Messenger
07-01 12:11:08.114   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:08.114   912  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:08.114   912  1151 D ConnectivityService: NetworkAgent connected
,07-01 12:11:08.114  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:08.124  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-01 12:11:08.124  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 12:11:08.124   912  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-01 12:11:08.124  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:08.134  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:08.134   293  1064 D CommandListener: Setting iface cfg
,07-01 12:11:08.134   912  1468 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:08.134  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 12:11:08.134   912  3696 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:08.134  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:08.134  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:08.134  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 12:11:08.134   912  1149 E WifiStateMachine: Start Dhcp Watchdog 2
07-01 12:11:08.134  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:08.134   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:08.134   912  1149 D SecContentProvider2: mCursor = null
,07-01 12:11:08.144   912   929 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:08.144  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:08.154   912  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 12:11:08.154  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:08.154  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:08.154  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:08.234   912  1149 E native  : do suspend false
,07-01 12:11:08.244   912  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 12:11:08.244   912  1148 D WifiP2pService: InactiveState{ what=143375 }
07-01 12:11:08.244   912  1149 D SecContentProvider2: mCursor = null
07-01 12:11:08.244   912  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 12:11:08.454  8340  8340 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-01 12:11:08.454  8340  8340 I dhcpcd  : version 5.5.6 starting
,07-01 12:11:08.464  8340  8340 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-01 12:11:08.534  8340  8340 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-01 12:11:08.534  8340  8340 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-01 12:11:08.534  8340  8340 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-01 12:11:08.534  8340  8340 I dhcpcd  : bssid match
07-01 12:11:08.534  8340  8340 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-01 12:11:08.564  8340  8340 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1,
,07-01 12:11:08.564  8340  8340 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-01 12:11:08.564   912  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 12:11:09.024  3260  3313 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 12:11:09.044   912  1149 E native  : do suspend true
,07-01 12:11:09.054   912  1148 D WifiP2pService: InactiveState{ what=143375 }
,07-01 12:11:09.054   912  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 12:11:09.064   912  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 12:11:09.064  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:09.064  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:09.064  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:09.064   912  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-01 12:11:09.064   912  1149 E WifiStateMachine: VerifyingLinkState enter
,07-01 12:11:09.064   912  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 12:11:09.064   912  1151 E ConnectivityService: updateNetworkInfo()
,07-01 12:11:09.074   912  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 12:11:09.074   912  1151 D ConnectivityService: Adding iface wlan0 to network 503
,07-01 12:11:09.084   912  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-01 12:11:09.084   912  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 12:11:09.084   912  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 12:11:09.084   912  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 12:11:09.084   912  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 12:11:09.094  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:09.094  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-01 12:11:09.094  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:09.114   912  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-01 12:11:09.114   912   912 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 12:11:09.124  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 12:11:09.124  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=2 combinedSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:09.124  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 12:11:09.134   912  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-01 12:11:09.134   912   912 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 12:11:09.134   912   912 I WifiTrafficPoller: mBoosterFLAG : 0
,07-01 12:11:09.134   912   912 I WifiTrafficPoller: current booster mode : FullMode
07-01 12:11:09.134   912   912 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-01 12:11:09.134  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-01 12:11:09.134  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-01 12:11:09.134  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:09.144  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.144  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:09.144  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.144  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:09.144  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.154  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:09.154  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.154   912  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,07-01 12:11:09.154   912  3320 D SSRM:n  : SIOP:: AP = 390, PST = 334, CUR = 450
07-01 12:11:09.154   912  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,07-01 12:11:09.154   912  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,07-01 12:11:09.154   912  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-01 12:11:09.154   912  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-01 12:11:09.154   912  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,07-01 12:11:09.154   293  1064 V         : QcRouteController
,07-01 12:11:09.164  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:09.164  4719  4719 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-01 12:11:09.174  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-01 12:11:09.174   912  1689 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.184   293  1064 V         : QcRouteController
,07-01 12:11:09.194  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:09.194  4719  4719 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 12:11:09.194   912  3665 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.194  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-01 12:11:09.194   912  1533 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.194  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 12:11:09.194  4719  4719 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 12:11:09.194  4719  4719 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 12:11:09.194  4719  4777 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 12:11:09.204   293  1064 V         : QcRouteController
,07-01 12:11:09.204   912  1336 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.204  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:09.224   293  1064 V         : QcRouteController
,07-01 12:11:09.224  4719  4719 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 12:11:09.224  4719  4719 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-01 12:11:09.234   912  1460 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-01 12:11:09.244   912  1336 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.244  5842  5842 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:09.254   293  1064 V         : QcRouteController
,07-01 12:11:09.254   265   265 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,07-01 12:11:09.274   293  1064 V         : QcRouteController
,07-01 12:11:09.274   293  1064 V         : QcRouteController
,07-01 12:11:09.274   912  1689 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=912
,07-01 12:11:09.294   293  1064 V         : QcRouteController
,07-01 12:11:09.314   912  1151 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
,07-01 12:11:09.314   912  1151 D ConnectivityService: LTETest block dns file not exists
,07-01 12:11:09.314   912  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-01 12:11:09.314   912  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.314   912  1151 D ConnectivityService: calling update connectivity
,07-01 12:11:09.314   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-01 12:11:09.314   912  1036 D EntConnectivity: Not allowed due to - mEnabled false
,07-01 12:11:09.314   912  1151 E ConnectivityService: updateNetworkInfo()
,07-01 12:11:09.314   912  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-01 12:11:09.314   912  1151 E ConnectivityService: updateNetworkInfo()
07-01 12:11:09.314   912  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:09.314   912  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.314   912  1151 D ConnectivityService: calling update connectivity
,07-01 12:11:09.314   912  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.314   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:09.314   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-01 12:11:09.314   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 12:11:09.314   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-01 12:11:09.314   912  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-01 12:11:09.324   912  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.324   912  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:09.324   912  8333 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 12:11:09.414   912  1485 I art     : Explicit concurrent mark sweep GC freed 61462(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.474ms total 114.399ms
07-01 12:11:09.414   912  1485 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
07-01 12:11:09.414   912  1151 D ConnectivityService: currentScore = 0, newScore = 60
07-01 12:11:09.414   912  1151 D ConnectivityService:    accepting network in place of null
07-01 12:11:09.414   912  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 12:11:09.414  1428  1428 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 12:11:09.414   912  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-01 12:11:09.414   912  8333 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-01 12:11:09.414   912  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-01 12:11:09.414   912  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-01 12:11:09.414  8172  8191 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-01 12:11:09.414   912  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:09.414   912  1152 D Tethering: MasterInitialState.processMessage what=3
07-01 12:11:09.414   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-01 12:11:09.414   912  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 12:11:09.414   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.414   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.414   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.414   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:09.414   912  1146 V NetworkStats: updateIfacesLocked()
07-01 12:11:09.414   912  1146 V NetworkStats: performPollLocked(flags=0x1)
,07-01 12:11:09.414   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:11:09.414   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.414   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:09.414   912  1460 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.414   912  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 12:11:09.414  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 12:11:09.414  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,07-01 12:11:09.414   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:09.414  1195  1195 D StatusBar.NetworkController: updateDataNetType()
07-01 12:11:09.414   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:09.414   912  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-01 12:11:09.414   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:09.424   912  1146 V NetworkStats: performPollLocked() took 3ms
07-01 12:11:09.424   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:11:09.424  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-01 12:11:09.424   912  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-01 12:11:09.424   912   929 D SecContentProvider2: uri = 14 selection = getSealedState
07-01 12:11:09.424   912   929 D SecContentProvider2: mCursor = null
,07-01 12:11:09.424   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:11:09.424   912  1655 I AudioService: getStreamVolume 3 index 70
07-01 12:11:09.424   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 12:11:09.424   912  1036 D EntConnectivity: Not allowed due to - mEnabled false
,07-01 12:11:09.424   912  1468 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 12:11:09.424   912  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
07-01 12:11:09.424   912  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.424   912  1151 D ConnectivityService: calling update connectivity
07-01 12:11:09.424   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:09.424   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.424   912  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-01 12:11:09.424  1195  1612 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
,07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:09.424  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.424  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 12:11:09.434  1195  1195 D StatusBar.NetworkController: applyOpen
07-01 12:11:09.434  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 12:11:09.434  1195  1195 D StatusBar.NetworkController: applyOpen
,07-01 12:11:09.434  1195  1195 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-01 12:11:09.434  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:11:09.434  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:11:09.434  1195  1195 I PhoneStatusBar: Icon Only
07-01 12:11:09.434  1195  1195 I StatusBar: Icon Only
,07-01 12:11:09.434  1195  1195 D PanelView: There is/are notification(s) 
,07-01 12:11:09.434  1195  1195 D PanelView: There is/are notification(s) 
,07-01 12:11:09.474   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 10:11:09 GMT], X-Android-Received-Millis=[1467367869487], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467367869457]}
07-01 12:11:09.474   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 12:11:09.474   912  8333 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-01 12:11:09.474   912  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.474   912  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.474   912  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 12:11:09.474   912  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.474   912  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-01 12:11:09.474   912  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:09.474   912  1151 D ConnectivityService: calling update connectivity
07-01 12:11:09.474   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:09.474   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.474   912  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:09.474   912  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-01 12:11:09.474  1195  1612 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-01 12:11:09.474   912  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.474  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 12:11:09.474  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-01 12:11:09.474  1195  1195 D StatusBar.NetworkController: updateDataNetType()
,07-01 12:11:09.474  1195  1195 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 12:11:09.484  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-01 12:11:09.484   912  1094 D SecContentProvider2: uri = 14 selection = getSealedState
,07-01 12:11:09.484   912  1094 D SecContentProvider2: mCursor = null
,07-01 12:11:09.484   912  1456 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 12:11:09.484   912  1456 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-01 12:11:09.484  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 12:11:09.484  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
,07-01 12:11:09.484  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-01 12:11:09.484  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-01 12:11:09.484  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 12:11:09.484  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 12:11:09.484  1195  1195 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-01 12:11:09.484  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
07-01 12:11:09.484  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
,07-01 12:11:09.484  1195  1195 I PhoneStatusBar: Icon Only
07-01 12:11:09.484  1195  1195 I StatusBar: Icon Only
,07-01 12:11:09.484  1195  1195 D PanelView: There is/are notification(s) 
,07-01 12:11:09.494  1195  1195 D PanelView: There is/are notification(s) 
,07-01 12:11:09.914   912  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:09.924   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.924   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.924   912  1485 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.924   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.924   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.924   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:09.924   912   912 D SmartBondingService: SmartBondingReceiver: wifi is connected
,07-01 12:11:09.924   912   912 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
,07-01 12:11:09.924   912   912 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912  3696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 12:11:09.934   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.934   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.934   912  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-01 12:11:09.934   912  1336 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.934   912  1533 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.934   912  1533 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.934   912  1336 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.934   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.934   912   912 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.934   912  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 12:11:09.934  7953  7953 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 12:11:09.944  7717  7717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 12:11:09.944  7717  7717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-01 12:11:09.944  7717  7784 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 12:11:09.944  7717  7784 I jxcore-log: 
,07-01 12:11:09.944  7148  7148 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-01 12:11:09.944  1496  1496 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-01 12:11:09.944  7148  7148 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 12:11:09.944   912   995 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:09.944   912   995 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.944   912  1485 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.944  7148  7148 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,07-01 12:11:09.954  7148  7148 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
07-01 12:11:09.954   912   995 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:09.954  7953  7953 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-01 12:11:09.964  8004  8004 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:09.974  8004  8004 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-01 12:11:09.974   912  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,07-01 12:11:09.974   912  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-01 12:11:09.974   912  1151 D ConnectivityService: identical MTU - not setting
07-01 12:11:09.974   912  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-01 12:11:09.974   912  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
,07-01 12:11:09.974   293  1064 V         : QcRouteController
,07-01 12:11:09.974   912   912 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,07-01 12:11:09.974   912   912 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:09.974   912  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 12:11:09.974   912  1153 D SmartBondingService: getSBEnabled() enabled =false
07-01 12:11:09.974   912  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-01 12:11:09.974   912  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-01 12:11:09.994   293  1064 V         : QcRouteController
,07-01 12:11:10.014   912  1151 W NetworkManagementService: route cmd failed: 
07-01 12:11:10.014   912  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '98 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 98 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-01 12:11:10.014   912  1151 W NetworkManagementService: '
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:11:10.014   912  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:11:10.014   912  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-01 12:11:10.014   912  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:10.014   912  1151 D ConnectivityService: calling update connectivity
07-01 12:11:10.014   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 12:11:10.014   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 12:11:10.014   912  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:10.014   912  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-01 12:11:10.014   912  1151 D ConnectivityService: calling update connectivity
07-01 12:11:10.014   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 12:11:10.014  1195  1612 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-01 12:11:10.014   912  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 12:11:10.014   912  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 12:11:10.014  1195  1612 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-01 12:11:10.044   912   997 W ProcessCpuTracker: Skipping unknown process pid 8441
,07-01 12:11:10.044   912   997 W ProcessCpuTracker: Skipping unknown process pid 8442
,07-01 12:11:10.074  8020  8020 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-01 12:11:10.074  8020  8020 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-01 12:11:10.074  8020  8020 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-01 12:11:10.084   912  1533 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084   912  1336 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 12:11:10.084   912  1336 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a4c7426, r.packageName :com.google.android.gms
,07-01 12:11:10.084   912  1719 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084   912  3696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084   912  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.084  2330  2330 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-01 12:11:10.094   912  1485 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.094  2330  8059 I iu.UploadsManager: num queued entries: 0
,07-01 12:11:10.094  2330  8059 I iu.UploadsManager: num updated entries: 0
,07-01 12:11:10.094  2330  8059 I iu.SyncManager: NEXT; no task
,07-01 12:11:10.094   912  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:11:10.094   912  1533 D ActivityManager: caller:android.app.ApplicationThreadProxy@9553867, r.packageName :com.google.android.gms
,07-01 12:11:10.104  2330  2330 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,07-01 12:11:10.104  2330  2330 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-01 12:11:10.104  2330  2330 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-01 12:11:10.104  2330  2330 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-01 12:11:10.104   912  3696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.104  2619  2619 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467367870122
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-01 12:11:10.114   912  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.114   912   929 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-01 12:11:10.114  2619  2619 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-01 12:11:10.124   912  1456 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.134   912  1485 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-01 12:11:10.134   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@2aec2ebd, r.packageName :com.samsung.android.app.galaxyfinder
,07-01 12:11:10.144  8102  8102 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-01 12:11:10.164  7181  7181 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-01 12:11:10.164   912   928 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.174  3751  8455 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-01 12:11:10.174  3751  8455 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-01 12:11:10.174  7224  7224 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-01 12:11:10.174  7224  7224 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-01 12:11:10.174  7224  7224 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-01 12:11:10.174  3751  8455 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-01 12:11:10.174  7224  7224 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-01 12:11:10.174  7224  7224 I SA      : [OR] == isSIMCardReady false ==
,07-01 12:11:10.174   912  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.174  7224  7224 I SA      : [SCU] == networkStateCheck == true
,07-01 12:11:10.174  7224  7224 I SA      : [DM] getCountryCodeFromCSC : PL
,07-01 12:11:10.174  7224  7224 I SA      : isChinaCountryCode : false
07-01 12:11:10.174  7224  7224 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-01 12:11:10.174  7224  7224 I SA      : [OR] == networkStateCheck true ==
,07-01 12:11:10.174  7224  7224 I SA      : [OR] GetMyCountryZoneTask
,07-01 12:11:10.174  7224  7224 I SA      : [OR] onReceive END
,07-01 12:11:10.184  7224  8456 I SA      : [SRS] prepareGetMyCountryZone
,07-01 12:11:10.184   912  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.184   912  1468 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-01 12:11:10.184   912  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@1072f403, r.packageName :com.android.providers.downloads
,07-01 12:11:10.184  7224  8456 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-01 12:11:10.184  7224  8456 I SA      : [SSP] query invoked
,07-01 12:11:10.194  8123  8123 I SCloudBackupReceiver: Other Intent
,07-01 12:11:10.194  8141  8141 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-01 12:11:10.194  8141  8141 I KnoxUsageLogPro: premStatus:2
,07-01 12:11:10.194  8141  8141 I KnoxUsageLogPro: isEulaShown : false
07-01 12:11:10.194  8141  8141 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-01 12:11:10.194  7224  8456 I SA      : [TPMU] GetMccFromDB : null
,07-01 12:11:10.204  7224  8456 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-01 12:11:10.204  7224  8456 I SA      : [TPM] isNoProxy(default) : true
,07-01 12:11:10.214   912  1456 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.214  7224  8456 E File    : fail readDirectory() errno=2
,07-01 12:11:10.214   912  3665 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.214   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:10.224   912  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.224  3751  8455 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-01 12:11:10.224  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-01 12:11:10.234   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.234   912  1719 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.234  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-01 12:11:10.234  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-01 12:11:10.244  8228  8228 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-01 12:11:10.244  8228  8228 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
07-01 12:11:10.244  8228  8228 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-01 12:11:10.244  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-01 12:11:10.244  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-01 12:11:10.244  3751  8455 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-01 12:11:10.244   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:11:10.254  3751  8455 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-01 12:11:10.254   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.254   912  1245 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.254   912   928 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 12:11:10.254   912  1485 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.264  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 12:11:10.264  7785  7785 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 12:11:10.264  7785  7785 D SecurityLogAgent: StateMachine : Current State = 1
07-01 12:11:10.264   912  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.264  7785  7785 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 12:11:10.264   912  1655 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.264   912  1460 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.274   912  1468 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
07-01 12:11:10.274   912  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@49293ac, r.packageName :com.sec.android.app.SmartClipService
,07-01 12:11:10.274   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.274  5634  5634 D WaitQueueForNetworkActivate: notifyNetworkActivated
07-01 12:11:10.274   912  1114 V AlarmManager: waitForAlarm result :4
07-01 12:11:10.274   912  1485 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-01 12:11:10.274   912  1485 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e6f7875, r.packageName :com.sec.android.app.samsungapps
,07-01 12:11:10.284  3751  8455 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-01 12:11:10.294  5634  5634 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-01 12:11:10.294  5634  5634 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: exit::IDLE
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-01 12:11:10.294   912  1245 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.294   912  1533 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: entry::SUCCESS
07-01 12:11:10.294  5634  5634 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-01 12:11:10.294  5634  5634 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-01 12:11:10.294  5634  5634 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-01 12:11:10.294   912  1456 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: exit::SUCCESS
07-01 12:11:10.294  5634  5634 D InitializeManagerStateMachine: entry::IDLE
,07-01 12:11:10.304   912  1689 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.304  3751  8455 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-01 12:11:10.394  1643  8460 D GCM     : Connected
,07-01 12:11:10.394   912  1336 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.394   912  1094 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.394   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:10.404   912  1485 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.404   912  1689 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.414   912  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.414  1643  8460 D GCM     : Message class com.google.f.a.a.p
,07-01 12:11:10.414   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:10.414   912  3665 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:11:10.414   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:10.424   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:10.424   912  1151 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-01 12:11:10.554   298   298 E SMD     : DCD ON
,07-01 12:11:10.674  7224  8456 I SA      : [RC New] Execute method=[GET] start
,07-01 12:11:10.704  7224  8456 I SA      : [RC New] Security=[true]
,07-01 12:11:10.704  7224  8456 I System.out: Thread-1195(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-01 12:11:10.714  7224  8456 I System.out: Thread-1195(ApacheHTTPLog):isShipBuild true
,07-01 12:11:10.714  7224  8456 I System.out: Thread-1195(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-01 12:11:10.784   912  1103 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 12:11:10.784   912  1103 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-01 12:11:10.784   912  1102 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 12:11:10.784   912  1103 I TLC_TIMA_PKM_initialize: initializing...
,07-01 12:11:10.784   912  1103 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-01 12:11:10.784   912  1103 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-01 12:11:10.784   912  1103 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-01 12:11:10.784   912  1103 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-01 12:11:10.784   912  1103 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-01 12:11:10.784   912  1103 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-01 12:11:10.784   912  1103 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-01 12:11:10.784   912  1103 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
07-01 12:11:10.784   912  1103 D QSEECOMAPI: : App is not loaded in QSEE
,07-01 12:11:10.804   912  1103 D QSEECOMAPI: : Loaded image: APP id = 2
,07-01 12:11:10.804   912  1103 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-01 12:11:10.804   912  1103 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-01 12:11:11.304  7224  8456 I SA      : [RC New] [v2liruge] api execute + 602
,07-01 12:11:11.304  7224  8456 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-01 12:11:11.314  7224  8456 I System.out: AsyncTask #1 calls detatch()
,07-01 12:11:11.314  7224  8456 I SA      : [TPMU] getNetworkMcc : 260
,07-01 12:11:11.334  7224  8456 I SA      : [SCU] saveMccToPreferece Start
,07-01 12:11:11.334  7224  8456 I SA      : [SCU] RegionMCC : 260
07-01 12:11:11.334  7224  8456 I SA      : [SSP] query invoked
,07-01 12:11:11.334  7224  8456 I SA      : [TPMU] GetMccFromDB : null
,07-01 12:11:11.334  7224  8456 I SA      : [SCU] getMccFromPreferece mcc = 260
07-01 12:11:11.334  7224  8456 I SA      : [SCU] saveMccToPreferece End
,07-01 12:11:11.334  7224  8456 I SA      : [RC New] executeRequest [v2liruge] end. 662
,07-01 12:11:11.334  7224  8456 I SA      : [RC New] Execute end
,07-01 12:11:11.344  7224  7224 I SA      : [OR] GetMyCountryZoneTask mcc = 260
07-01 12:11:11.344  7224  7224 I SA      : [OR] GetMyCountryZoneTask Success
,07-01 12:11:12.164   912  1719 I ActivityManager: Killing 7317:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-01 12:11:12.494   912  1149 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,07-01 12:11:12.764   265   976 I SurfaceFlinger: id=15 Removed Uoast (8/9)
,07-01 12:11:12.764   265   403 I SurfaceFlinger: id=15 Removed Uoast (-2/9)
,07-01 12:11:12.764   912  1460 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=912 (0x0)
,07-01 12:11:12.764   912  1460 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=912, ws=WorkSource{10067}) (elapsedTime=3493)
,07-01 12:11:12.794   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 12:11:12.794   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 12:11:12.794   912  1103 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:11:12.804   912  1103 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:11:12.874  8340  8340 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-01 12:11:12.954   912  1339 E Watchdog: !@Sync 10
,07-01 12:11:13.174   912  1094 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-01 12:11:13.174   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@2214e07b, r.packageName :com.sec.spp.push
,07-01 12:11:13.204   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:13.554   298   298 E SMD     : DCD ON
,07-01 12:11:13.934   912  3696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:14.424   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:14.464   912  1114 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,07-01 12:11:14.474  1496  8481 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,07-01 12:11:14.484   912   928 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 12:11:14.484   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@2221ac44, r.packageName :com.google.android.gms
,07-01 12:11:14.544  1643  1663 I art     : Explicit concurrent mark sweep GC freed 11128(578KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 408us total 22.441ms
,07-01 12:11:14.554  2330  8484 I EventLogService: Aggregate from 1467366034054 (log), 1467366034054 (data)
,07-01 12:11:14.954  7148  7148 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,07-01 12:11:14.954   912   928 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 12:11:14.954  7148  8492 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,07-01 12:11:14.984  7148  8492 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,07-01 12:11:14.984  7148  8492 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-01 12:11:14.984  7148  8492 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-01 12:11:14.984  7148  8492 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,07-01 12:11:14.984  7148  8492 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-01 12:11:14.984  7148  8492 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-01 12:11:14.984  7148  8492 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 12:11:14.984  7148  8492 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,07-01 12:11:15.034   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:11:15.034   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:11:15.034   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:11:15.034   912  1336 D BatteryService: stay LED for fully charged
07-01 12:11:15.034   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:11:15.044  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:11:15.044  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:11:15.044   912   912 I MotionRecognitionService: Plugged
07-01 12:11:15.044   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:11:15.044  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:11:15.044  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:15.044  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:11:15.044  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:15.054  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:11:15.054  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:11:16.554   298   298 E SMD     : DCD ON
,07-01 12:11:16.874  8340  8340 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-01 12:11:18.884   340   340 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-01 12:11:18.884   340   340 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-01 12:11:19.214   912  3320 D SSRM:n  : SIOP:: AP = 350, PST = 336, CUR = 450
,07-01 12:11:19.554   298   298 E SMD     : DCD ON
,07-01 12:11:20.284   912   928 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-01 12:11:20.284   912   928 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ae7c329, r.packageName :com.sec.android.app.samsungapps
,07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: exit::IDLE
07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-01 12:11:20.294  5634  5634 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-01 12:11:20.294  5634  5634 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-01 12:11:20.884  8340  8340 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-01 12:11:20.884  8340  8340 I dhcpcd  : wlan0: no IPv6 Routers available
,07-01 12:11:22.554   298   298 E SMD     : DCD ON
,07-01 12:11:23.564   912  1042 I PowerManagerService: [PWL] Off : 105s ago
,07-01 12:11:25.554   298   298 E SMD     : DCD ON
,07-01 12:11:28.554   298   298 E SMD     : DCD ON
,07-01 12:11:29.274   912  3320 D SSRM:n  : SIOP:: AP = 330, PST = 336, CUR = 450
,07-01 12:11:29.354   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:29.364   912   997 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-01 12:11:29.364   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:29.364   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:29.364   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:11:29.364   912   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 12:11:29.414   912  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:11:29.414   912  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:11:29.414   912  1485 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:11:29.414   912  1485 D BatteryService: stay LED for fully charged
07-01 12:11:29.414   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:11:29.424   912   997 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8496 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 12:11:29.434   912   912 I MotionRecognitionService: Plugged
07-01 12:11:29.434   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:11:29.434  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:11:29.434  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:11:29.434  8496  8496 E Zygote  : MountEmulatedStorage()
,07-01 12:11:29.444  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:11:29.444  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:11:29.444  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:11:29.444  8496  8496 E Zygote  : v2
07-01 12:11:29.444  8496  8496 I libpersona: KNOX_SDCARD checking this for 10096
07-01 12:11:29.444  8496  8496 I libpersona: KNOX_SDCARD not a persona
07-01 12:11:29.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:11:29.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:29.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:29.464  8496  8496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 12:11:29.464  8496  8496 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 12:11:29.464  8496  8496 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-01 12:11:29.484  8496  8496 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 12:11:29.484  8496  8496 D ActivityThread: Added TimaKeyStore provider
,07-01 12:11:29.494  8496  8496 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-01 12:11:29.504   912  3665 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-01 12:11:29.504   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b383fdc, r.packageName :com.blurb.checkout
,07-01 12:11:29.534   912  3696 I ActivityManager: Killing 7332:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-01 12:11:30.254   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:11:31.554   298   298 E SMD     : DCD ON
,07-01 12:11:33.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:34.554   298   298 E SMD     : DCD ON
,07-01 12:11:34.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:35.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:36.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:37.554   298   298 E SMD     : DCD ON
,07-01 12:11:37.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:38.294   912  1114 V AlarmManager: waitForAlarm result :4
,07-01 12:11:38.894   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-01 12:11:39.324   912  3320 D SSRM:n  : SIOP:: AP = 330, PST = 337, CUR = 450
,07-01 12:11:39.474   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:11:40.554   298   298 E SMD     : DCD ON
,07-01 12:11:42.954   912  1339 E Watchdog: !@Sync 11
,07-01 12:11:43.564   298   298 E SMD     : DCD ON
,07-01 12:11:43.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:44.894   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:45.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:46.564   298   298 E SMD     : DCD ON
,07-01 12:11:46.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:47.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:48.904   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-01 12:11:49.374   912  3320 D SSRM:n  : SIOP:: AP = 330, PST = 338, CUR = 450
,07-01 12:11:49.534   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:11:49.534   912  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:11:49.534   912  1719 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:11:49.544   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:11:49.544   912   912 I MotionRecognitionService: Plugged
,07-01 12:11:49.544  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:11:49.554  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:11:49.554   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:11:49.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:49.554   912  1719 D BatteryService: stay LED for fully charged
07-01 12:11:49.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:49.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:11:49.554  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:11:49.554  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:11:49.554  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:11:49.564   298   298 E SMD     : DCD ON
,07-01 12:11:50.254   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:11:52.564   298   298 E SMD     : DCD ON
,07-01 12:11:55.564   298   298 E SMD     : DCD ON
,07-01 12:11:58.564   298   298 E SMD     : DCD ON
,07-01 12:11:58.574   912  1042 I PowerManagerService: [PWL] Off : 140s ago
,07-01 12:11:58.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:11:59.424   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 338, CUR = 450
,07-01 12:11:59.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:00.004   912  1114 V AlarmManager: waitForAlarm result :8
,07-01 12:12:00.044   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:00.044   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:12:00.044   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:12:00.044   912  3665 D BatteryService: stay LED for fully charged
07-01 12:12:00.044   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:12:00.044  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:12:00.044  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:12:00.044   912   912 I MotionRecognitionService: Plugged
07-01 12:12:00.044   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:12:00.054  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:12:00.054  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:00.054  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:12:00.054  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:12:00.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:00.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:00.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:01.564   298   298 E SMD     : DCD ON
,07-01 12:12:01.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:02.904   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:03.904   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-01 12:12:04.564   298   298 E SMD     : DCD ON
,07-01 12:12:07.564   298   298 E SMD     : DCD ON
,07-01 12:12:09.464   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 338, CUR = 450
,07-01 12:12:10.114   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:10.114   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:12:10.114   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:12:10.114   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:12:10.124  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:12:10.124   912   912 I MotionRecognitionService: Plugged
,07-01 12:12:10.124   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:12:10.124  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:12:10.124  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:12:10.124   912  1245 D BatteryService: stay LED for fully charged
07-01 12:12:10.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:10.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:10.134  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:12:10.134  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:12:10.144  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:10.254   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:12:10.564   298   298 E SMD     : DCD ON
,07-01 12:12:12.964   912  1339 E Watchdog: !@Sync 12
,07-01 12:12:13.564   298   298 E SMD     : DCD ON
,07-01 12:12:16.574   298   298 E SMD     : DCD ON
,07-01 12:12:18.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:19.514   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 338, CUR = 450
,07-01 12:12:19.574   298   298 E SMD     : DCD ON
,07-01 12:12:19.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:20.154   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:20.154   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:12:20.164   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:12:20.164   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:12:20.164  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:12:20.174  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:12:20.174   912   912 I MotionRecognitionService: Plugged
,07-01 12:12:20.174   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:12:20.174   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:12:20.174  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:20.184  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:20.184  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:12:20.184  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:12:20.184  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:12:20.194  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:20.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:21.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:22.574   298   298 E SMD     : DCD ON
,07-01 12:12:22.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:23.914   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-01 12:12:25.574   298   298 E SMD     : DCD ON
,07-01 12:12:28.574   298   298 E SMD     : DCD ON
,07-01 12:12:29.564   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 337, CUR = 450
,07-01 12:12:30.214   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:30.254   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:12:31.574   298   298 E SMD     : DCD ON
,07-01 12:12:34.574   298   298 E SMD     : DCD ON
,07-01 12:12:37.574   298   298 E SMD     : DCD ON
,07-01 12:12:38.574   912  1042 I PowerManagerService: [PWL] Off : 180s ago
,07-01 12:12:39.614   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 333, CUR = 450
,07-01 12:12:40.284   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:40.284   912   928 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:12:40.284   912   928 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:12:40.284   912   928 D BatteryService: stay LED for fully charged
07-01 12:12:40.284   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:12:40.284  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:12:40.284  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:12:40.284   912   912 I MotionRecognitionService: Plugged
07-01 12:12:40.284   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:12:40.284  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:12:40.294  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:12:40.294  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:12:40.294  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:40.294  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:12:40.294  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:40.574   298   298 E SMD     : DCD ON
,07-01 12:12:42.964   912  1339 E Watchdog: !@Sync 13
,07-01 12:12:43.574   298   298 E SMD     : DCD ON
,07-01 12:12:43.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:44.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:45.914   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:46.574   298   298 E SMD     : DCD ON
,07-01 12:12:46.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:47.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:12:48.924   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-01 12:12:49.574   298   298 E SMD     : DCD ON
,07-01 12:12:49.664   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 450
,07-01 12:12:50.264   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:12:50.344   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:12:50.344   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:12:50.344   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:12:50.344   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:12:50.344   912   912 I MotionRecognitionService: Plugged
,07-01 12:12:50.344   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:12:50.344  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:12:50.344  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:12:50.354  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:12:50.354  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:12:50.354   912  1245 D BatteryService: stay LED for fully charged
07-01 12:12:50.354  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:12:50.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:12:50.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:50.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:12:52.574   298   298 E SMD     : DCD ON
,07-01 12:12:55.584   298   298 E SMD     : DCD ON
,07-01 12:12:58.584   298   298 E SMD     : DCD ON
,07-01 12:12:59.714   912  3320 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450
,07-01 12:13:00.384   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:00.384   912   929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:13:00.384   912   929 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:13:00.384   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:13:00.394  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:13:00.394  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:13:00.394   912   912 I MotionRecognitionService: Plugged
,07-01 12:13:00.404   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:13:00.404   912   929 D BatteryService: stay LED for fully charged
,07-01 12:13:00.404  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:13:00.414  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:13:00.414  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:13:00.424  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:00.424  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:00.424  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:01.584   298   298 E SMD     : DCD ON
,07-01 12:13:04.584   298   298 E SMD     : DCD ON
,07-01 12:13:07.584   298   298 E SMD     : DCD ON
,07-01 12:13:09.764   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 321, CUR = 450
,07-01 12:13:10.264   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:13:10.444   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:10.584   298   298 E SMD     : DCD ON
,07-01 12:13:12.964   912  1339 E Watchdog: !@Sync 14
,07-01 12:13:13.584   298   298 E SMD     : DCD ON
,07-01 12:13:13.924   340   340 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-01 12:13:13.924   340   340 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-01 12:13:16.584   298   298 E SMD     : DCD ON
,07-01 12:13:19.584   298   298 E SMD     : DCD ON
,07-01 12:13:19.814   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-01 12:13:20.514   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:20.514   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:13:20.514   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:13:20.514   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:13:20.514  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:13:20.524   912   912 I MotionRecognitionService: Plugged
,07-01 12:13:20.524   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:13:20.524  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:13:20.524   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:13:20.524  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:20.524  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:13:20.524  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:13:20.534  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:13:20.534  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:13:20.544  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:22.584   298   298 E SMD     : DCD ON
,07-01 12:13:23.574   912  1042 I PowerManagerService: [PWL] Off : 225s ago
,07-01 12:13:25.584   298   298 E SMD     : DCD ON
,07-01 12:13:28.584   298   298 E SMD     : DCD ON
,07-01 12:13:29.854   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-01 12:13:30.264   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:13:30.554   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:31.584   298   298 E SMD     : DCD ON
,07-01 12:13:33.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:34.594   298   298 E SMD     : DCD ON
,07-01 12:13:34.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:35.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:36.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:37.594   298   298 E SMD     : DCD ON
,07-01 12:13:37.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:38.924   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-01 12:13:39.904   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-01 12:13:40.594   298   298 E SMD     : DCD ON
,07-01 12:13:40.624   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:40.624   912   928 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:13:40.624   912   928 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:13:40.624   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:13:40.624  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:13:40.624  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:13:40.624   912   912 I MotionRecognitionService: Plugged
07-01 12:13:40.624   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:13:40.624  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:13:40.634   912   928 D BatteryService: stay LED for fully charged
,07-01 12:13:40.634  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:40.634  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:13:40.634  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:13:40.634  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:40.634  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:42.964   912  1339 E Watchdog: !@Sync 15
,07-01 12:13:43.594   298   298 E SMD     : DCD ON
,07-01 12:13:43.924   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:44.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:45.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:46.594   298   298 E SMD     : DCD ON
,07-01 12:13:46.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:47.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:48.934   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-01 12:13:49.594   298   298 E SMD     : DCD ON
,07-01 12:13:49.954   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 450
,07-01 12:13:50.274   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:13:50.684   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:13:50.684   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:13:50.684   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:13:50.684   912  1245 D BatteryService: stay LED for fully charged
07-01 12:13:50.684   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:13:50.684  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:13:50.684  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:13:50.684   912   912 I MotionRecognitionService: Plugged
07-01 12:13:50.684   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:13:50.694  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:13:50.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:50.694  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:13:50.694  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:13:50.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:13:50.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:13:52.594   298   298 E SMD     : DCD ON
,07-01 12:13:55.594   298   298 E SMD     : DCD ON
,07-01 12:13:58.594   298   298 E SMD     : DCD ON
,07-01 12:13:58.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:13:59.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:00.004   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-01 12:14:00.734   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:00.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:01.094   336   336 I bootchecker: bootchecker wake up!!
,07-01 12:14:01.594   298   298 E SMD     : DCD ON
,07-01 12:14:01.934   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:02.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:03.944   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-01 12:14:04.594   298   298 E SMD     : DCD ON
,07-01 12:14:07.594   298   298 E SMD     : DCD ON
,07-01 12:14:10.054   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-01 12:14:10.274   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:14:10.594   298   298 E SMD     : DCD ON
,07-01 12:14:10.804   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:10.804   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:14:10.804   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:14:10.804   912  1533 D BatteryService: stay LED for fully charged
07-01 12:14:10.804   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:14:10.804  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:14:10.804  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:14:10.804   912   912 I MotionRecognitionService: Plugged
07-01 12:14:10.804   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:14:10.814  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:14:10.814  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:10.814  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:10.814  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:10.814  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:14:10.814  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:14:12.974   912  1339 E Watchdog: !@Sync 16
,07-01 12:14:13.584   912  1042 I PowerManagerService: [PWL] Off : 275s ago
,07-01 12:14:13.604   298   298 E SMD     : DCD ON
,07-01 12:14:16.604   298   298 E SMD     : DCD ON
,07-01 12:14:18.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:19.604   298   298 E SMD     : DCD ON
,07-01 12:14:19.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:20.114   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-01 12:14:20.864   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:20.864   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:14:20.864   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:14:20.864   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:14:20.864  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:14:20.864  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:14:20.864   912   912 I MotionRecognitionService: Plugged
,07-01 12:14:20.864   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:14:20.874  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:14:20.874   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:14:20.874  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:14:20.874  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:14:20.874  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:20.874  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:14:20.874  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:20.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:21.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:22.604   298   298 E SMD     : DCD ON
,07-01 12:14:22.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:23.944   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-01 12:14:25.604   298   298 E SMD     : DCD ON
,07-01 12:14:28.604   298   298 E SMD     : DCD ON
,07-01 12:14:30.164   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-01 12:14:30.274   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:14:30.904   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:30.904   912  1460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:14:30.914   912  1460 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:14:30.914   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:14:30.924  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:14:30.924  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:14:30.924   912   912 I MotionRecognitionService: Plugged
,07-01 12:14:30.924   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:14:30.924   912  1460 D BatteryService: stay LED for fully charged
,07-01 12:14:30.934  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:14:30.934  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:14:30.934  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:14:30.944  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:30.944  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:14:30.944  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:31.604   298   298 E SMD     : DCD ON
,07-01 12:14:34.604   298   298 E SMD     : DCD ON
,07-01 12:14:37.604   298   298 E SMD     : DCD ON
,07-01 12:14:40.224   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:14:40.604   298   298 E SMD     : DCD ON
,07-01 12:14:40.974   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:40.974   912   929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:14:40.974   912   929 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:14:40.974   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:14:40.984  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:14:40.984  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:14:40.984   912   912 I MotionRecognitionService: Plugged
,07-01 12:14:40.984   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:14:40.984   912   929 D BatteryService: stay LED for fully charged
,07-01 12:14:40.984  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:14:40.994  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:14:40.994  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:14:40.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:40.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:14:40.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:42.974   912  1339 E Watchdog: !@Sync 17
,07-01 12:14:43.604   298   298 E SMD     : DCD ON
,07-01 12:14:43.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:44.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:45.944   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:46.604   298   298 E SMD     : DCD ON
,07-01 12:14:46.954   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:47.954   340   340 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 12:14:48.954   340   340 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-01 12:14:49.614   298   298 E SMD     : DCD ON
,07-01 12:14:50.274   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:14:50.284   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:14:51.024   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:14:51.024   912  1456 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:14:51.024   912  1456 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:14:51.024   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:14:51.034  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:14:51.034  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:14:51.034   912   912 I MotionRecognitionService: Plugged
,07-01 12:14:51.044   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:14:51.044   912  1456 D BatteryService: stay LED for fully charged
,07-01 12:14:51.044  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:14:51.054  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:14:51.054  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:14:51.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:51.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:14:51.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:14:52.614   298   298 E SMD     : DCD ON
,07-01 12:14:55.614   298   298 E SMD     : DCD ON
,07-01 12:14:58.614   298   298 E SMD     : DCD ON
,07-01 12:15:00.004   912  1114 V AlarmManager: waitForAlarm result :8
,07-01 12:15:00.024  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 12:15:00.024  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
,07-01 12:15:00.034  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-01 12:15:00.034  1195  1195 I KeyguardEffectViewController: *** don't update sliding image ***
,07-01 12:15:00.104  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 12:15:00.104  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 12:15:00.324   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:01.074   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:01.084   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:15:01.084   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:15:01.084   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:15:01.094  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:15:01.094  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:15:01.094   912   912 I MotionRecognitionService: Plugged
,07-01 12:15:01.104   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:15:01.104   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:15:01.104  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:15:01.114  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:15:01.114  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:15:01.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:01.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:15:01.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:01.614   298   298 E SMD     : DCD ON
,07-01 12:15:04.614   298   298 E SMD     : DCD ON
,07-01 12:15:07.614   298   298 E SMD     : DCD ON
,07-01 12:15:08.584   912  1042 I PowerManagerService: [PWL] Off : 330s ago
,07-01 12:15:10.284   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:15:10.364   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:10.614   298   298 E SMD     : DCD ON
,07-01 12:15:11.134   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:11.144   912  1460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:15:11.144   912  1460 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:15:11.144   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:15:11.154  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:15:11.154   912   912 I MotionRecognitionService: Plugged
,07-01 12:15:11.154  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:15:11.154   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:15:11.164   912  1460 D BatteryService: stay LED for fully charged
,07-01 12:15:11.164  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:15:11.164  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:15:11.164  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:15:11.174  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:11.174  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:15:11.174  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:12.974   912  1339 E Watchdog: !@Sync 18
,07-01 12:15:13.614   298   298 E SMD     : DCD ON
,07-01 12:15:13.954   340   340 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-01 12:15:13.954   340   340 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-01 12:15:16.614   298   298 E SMD     : DCD ON
,07-01 12:15:19.614   298   298 E SMD     : DCD ON
,07-01 12:15:20.414   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:21.194   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:22.614   298   298 E SMD     : DCD ON
,07-01 12:15:25.624   298   298 E SMD     : DCD ON
,07-01 12:15:28.624   298   298 E SMD     : DCD ON
,07-01 12:15:30.284   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:15:30.464   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:31.264   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:31.264   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:15:31.264   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:15:31.264   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:15:31.264  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:15:31.264  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:15:31.264   912   912 I MotionRecognitionService: Plugged
,07-01 12:15:31.264   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:15:31.274   912  1245 D BatteryService: stay LED for fully charged
,07-01 12:15:31.274  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:15:31.274  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:15:31.274  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:31.274  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:31.274  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:15:31.274  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:15:31.624   298   298 E SMD     : DCD ON
,07-01 12:15:34.624   298   298 E SMD     : DCD ON
,07-01 12:15:37.624   298   298 E SMD     : DCD ON
,07-01 12:15:38.964   340   340 I Atfwd_Daemon: Stop the daemon....
,07-01 12:15:40.514   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:40.624   298   298 E SMD     : DCD ON
,07-01 12:15:41.324   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:41.324   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:15:41.324   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:15:41.324   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:15:41.324  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:15:41.324  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:15:41.324   912   912 I MotionRecognitionService: Plugged
07-01 12:15:41.324   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:15:41.334  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:15:41.334  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:15:41.334  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:15:41.334   912  1458 D BatteryService: stay LED for fully charged
,07-01 12:15:41.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:41.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:15:41.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:42.984   912  1339 E Watchdog: !@Sync 19
,07-01 12:15:43.624   298   298 E SMD     : DCD ON
,07-01 12:15:46.624   298   298 E SMD     : DCD ON
,07-01 12:15:49.624   298   298 E SMD     : DCD ON
,07-01 12:15:50.294   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:15:50.554   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:15:51.384   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:15:51.384   912  1460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:15:51.384   912  1460 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:15:51.384   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:15:51.384  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:15:51.384  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:15:51.384   912   912 I MotionRecognitionService: Plugged
,07-01 12:15:51.384   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:15:51.394   912  1460 D BatteryService: stay LED for fully charged
,07-01 12:15:51.394  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:15:51.394  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:15:51.394  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:15:51.394  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:51.394  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:15:51.394  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:15:52.624   298   298 E SMD     : DCD ON
,07-01 12:15:55.624   298   298 E SMD     : DCD ON
,07-01 12:15:58.624   298   298 E SMD     : DCD ON
,07-01 12:15:59.984   912  1114 V AlarmManager: waitForAlarm result :8
,07-01 12:16:00.604   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:01.444   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:01.444   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:16:01.444   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:16:01.444   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:16:01.444  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:16:01.444  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:16:01.444   912   912 I MotionRecognitionService: Plugged
07-01 12:16:01.444   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:16:01.444  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:16:01.454   912  1336 D BatteryService: stay LED for fully charged
,07-01 12:16:01.454  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:16:01.454  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:16:01.454  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:01.454  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:16:01.454  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:01.634   298   298 E SMD     : DCD ON
,07-01 12:16:04.634   298   298 E SMD     : DCD ON
,07-01 12:16:07.634   298   298 E SMD     : DCD ON
,07-01 12:16:08.584   912  1042 I PowerManagerService: [PWL] Off : 390s ago
,07-01 12:16:10.294   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:16:10.634   298   298 E SMD     : DCD ON
,07-01 12:16:10.654   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:10.784   912  1103 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 12:16:10.784   912  1103 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 12:16:10.784   912  1102 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 12:16:11.504   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:11.504   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:16:11.504   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:16:11.504   912  1094 D BatteryService: stay LED for fully charged
07-01 12:16:11.504   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:16:11.504  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:16:11.504  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:16:11.504   912   912 I MotionRecognitionService: Plugged
07-01 12:16:11.504   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:16:11.514  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:16:11.514  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:16:11.514  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:16:11.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:11.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:16:11.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:12.964   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 12:16:12.964   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 12:16:12.974   912  1103 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:16:12.974   912  1103 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:16:12.984   912  1339 E Watchdog: !@Sync 20
,07-01 12:16:13.634   298   298 E SMD     : DCD ON
,07-01 12:16:16.634   298   298 E SMD     : DCD ON
,07-01 12:16:19.634   298   298 E SMD     : DCD ON
,07-01 12:16:20.704   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:21.564   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:21.564   912  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:16:21.564   912  1719 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:16:21.564   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:16:21.564  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:16:21.564  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:16:21.564   912   912 I MotionRecognitionService: Plugged
,07-01 12:16:21.564   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:16:21.574   912  1719 D BatteryService: stay LED for fully charged
,07-01 12:16:21.574  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:16:21.574  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:16:21.574  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:16:21.574  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:21.574  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:16:21.574  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:22.634   298   298 E SMD     : DCD ON
,07-01 12:16:25.634   298   298 E SMD     : DCD ON
,07-01 12:16:28.634   298   298 E SMD     : DCD ON
,07-01 12:16:30.294   912  3333 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 12:16:30.744   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:31.624   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:31.624   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:16:31.624   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:16:31.624   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:16:31.624  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:16:31.624  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:16:31.624   912   912 I MotionRecognitionService: Plugged
,07-01 12:16:31.624   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:16:31.634  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:16:31.634  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:16:31.634   912  3665 D BatteryService: stay LED for fully charged
,07-01 12:16:31.634  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:16:31.634  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:31.634   298   298 E SMD     : DCD ON
,07-01 12:16:31.654  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:31.654  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:34.634   298   298 E SMD     : DCD ON
,07-01 12:16:37.634   298   298 E SMD     : DCD ON
,07-01 12:16:40.644   298   298 E SMD     : DCD ON
,07-01 12:16:40.794   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:41.674   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:41.674   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:16:41.674   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:16:41.674   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:16:41.684   912   912 I MotionRecognitionService: Plugged
,07-01 12:16:41.684  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:16:41.684  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:16:41.684   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:16:41.684   912  1533 D BatteryService: stay LED for fully charged
,07-01 12:16:41.684  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:16:41.694  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:16:41.694  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:16:41.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:41.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:41.694  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:16:42.984   912  1339 E Watchdog: !@Sync 21
,07-01 12:16:43.644   298   298 E SMD     : DCD ON
,07-01 12:16:46.644   298   298 E SMD     : DCD ON
,07-01 12:16:49.644   298   298 E SMD     : DCD ON
,07-01 12:16:50.844   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:16:51.724   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:16:52.644   298   298 E SMD     : DCD ON
,07-01 12:16:55.644   298   298 E SMD     : DCD ON
,07-01 12:16:58.644   298   298 E SMD     : DCD ON
,07-01 12:17:00.884   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:01.644   298   298 E SMD     : DCD ON
,07-01 12:17:01.794   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:01.794   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:17:01.794   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:17:01.794   912  1655 D BatteryService: stay LED for fully charged
,07-01 12:17:01.794   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:17:01.804  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:17:01.804  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:17:01.804  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:17:01.814  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:17:01.814  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:17:01.814   912   912 I MotionRecognitionService: Plugged
,07-01 12:17:01.814   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:17:01.824  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:01.824  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:01.824  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:04.644   298   298 E SMD     : DCD ON
,07-01 12:17:07.644   298   298 E SMD     : DCD ON
,07-01 12:17:10.644   298   298 E SMD     : DCD ON
,07-01 12:17:10.934   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:11.844   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:11.844   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:17:11.844   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:17:11.844   912  1689 D BatteryService: stay LED for fully charged
07-01 12:17:11.844   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:17:11.854  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:17:11.854  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:17:11.854   912   912 I MotionRecognitionService: Plugged
,07-01 12:17:11.864   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:17:11.864  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:17:11.864  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:11.864  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:11.874  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:17:11.874  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:17:11.884  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:12.984   912  1339 E Watchdog: !@Sync 22
,07-01 12:17:13.594   912  1042 I PowerManagerService: [PWL] Off : 455s ago
,07-01 12:17:13.644   298   298 E SMD     : DCD ON
,07-01 12:17:16.644   298   298 E SMD     : DCD ON
,07-01 12:17:19.654   298   298 E SMD     : DCD ON
,07-01 12:17:20.984   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:21.904   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:21.904   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:17:21.904   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:17:21.904   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:17:21.914  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:17:21.914  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:17:21.914   912   912 I MotionRecognitionService: Plugged
,07-01 12:17:21.924   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:17:21.924   912  1533 D BatteryService: stay LED for fully charged
,07-01 12:17:21.934  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:17:21.934  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:17:21.934  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:17:21.934  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:17:21.934  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:21.934  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:22.654   298   298 E SMD     : DCD ON
,07-01 12:17:25.654   298   298 E SMD     : DCD ON
,07-01 12:17:28.654   298   298 E SMD     : DCD ON
,07-01 12:17:31.034   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:31.654   298   298 E SMD     : DCD ON
,07-01 12:17:31.964   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:31.964   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:17:31.964   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:17:31.964   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:17:31.974   912   912 I MotionRecognitionService: Plugged
,07-01 12:17:31.974   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:17:31.974   912  1458 D BatteryService: stay LED for fully charged
,07-01 12:17:31.974  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:17:31.984  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:17:31.994  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:17:31.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:31.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:17:31.994  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:31.994  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:17:31.994  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:17:34.654   298   298 E SMD     : DCD ON
,07-01 12:17:37.654   298   298 E SMD     : DCD ON
,07-01 12:17:40.654   298   298 E SMD     : DCD ON
,07-01 12:17:41.074   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:42.024   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:42.024   912  1456 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:17:42.024   912  1456 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:17:42.024   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:17:42.034  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:17:42.034   912   912 I MotionRecognitionService: Plugged
,07-01 12:17:42.044  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:17:42.044   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:17:42.044   912  1456 D BatteryService: stay LED for fully charged
,07-01 12:17:42.044  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:17:42.054  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:17:42.054  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:17:42.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:42.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:42.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:17:42.994   912  1339 E Watchdog: !@Sync 23
,07-01 12:17:43.654   298   298 E SMD     : DCD ON
,07-01 12:17:46.654   298   298 E SMD     : DCD ON
,07-01 12:17:49.654   298   298 E SMD     : DCD ON
,07-01 12:17:51.124   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:17:52.084   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:17:52.654   298   298 E SMD     : DCD ON
,07-01 12:17:55.664   298   298 E SMD     : DCD ON
,07-01 12:17:58.664   298   298 E SMD     : DCD ON
,07-01 12:18:01.174   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:18:01.664   298   298 E SMD     : DCD ON
,07-01 12:18:02.134   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:04.664   298   298 E SMD     : DCD ON
,07-01 12:18:07.664   298   298 E SMD     : DCD ON
,07-01 12:18:10.664   298   298 E SMD     : DCD ON
,07-01 12:18:11.224   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:18:12.204   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:12.994   912  1339 E Watchdog: !@Sync 24
,07-01 12:18:13.664   298   298 E SMD     : DCD ON
,07-01 12:18:16.664   298   298 E SMD     : DCD ON
,07-01 12:18:19.664   298   298 E SMD     : DCD ON
,07-01 12:18:21.274   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:18:22.264   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:22.664   298   298 E SMD     : DCD ON
,07-01 12:18:23.594   912  1042 I PowerManagerService: [PWL] Off : 525s ago
,07-01 12:18:25.664   298   298 E SMD     : DCD ON
,07-01 12:18:28.664   298   298 E SMD     : DCD ON
,07-01 12:18:31.324   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-01 12:18:31.664   298   298 E SMD     : DCD ON
,07-01 12:18:32.314   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:32.314   912  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:18:32.324   912  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:18:32.324   912  1468 D BatteryService: stay LED for fully charged
07-01 12:18:32.324   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:18:32.324  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:18:32.324  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:18:32.324   912   912 I MotionRecognitionService: Plugged
07-01 12:18:32.324   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:18:32.324  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:18:32.334  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:18:32.334  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:18:32.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:32.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:18:32.334  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:34.674   298   298 E SMD     : DCD ON
,07-01 12:18:37.674   298   298 E SMD     : DCD ON
,07-01 12:18:40.674   298   298 E SMD     : DCD ON
,07-01 12:18:41.374   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-01 12:18:42.374   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:42.374   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:18:42.374   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:18:42.374   912  3696 D BatteryService: stay LED for fully charged
07-01 12:18:42.374   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:18:42.374  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:18:42.374  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:18:42.374   912   912 I MotionRecognitionService: Plugged
07-01 12:18:42.374   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:18:42.374  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:18:42.384  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:42.384  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:18:42.384  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:18:42.384  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:18:42.384  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:42.994   912  1339 E Watchdog: !@Sync 25
,07-01 12:18:43.674   298   298 E SMD     : DCD ON
,07-01 12:18:46.674   298   298 E SMD     : DCD ON
,07-01 12:18:49.674   298   298 E SMD     : DCD ON
,07-01 12:18:51.424   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-01 12:18:52.434   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:18:52.434   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:18:52.434   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:18:52.434   912  3665 D BatteryService: stay LED for fully charged
07-01 12:18:52.434   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:18:52.434  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:18:52.434  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:18:52.434   912   912 I MotionRecognitionService: Plugged
07-01 12:18:52.434   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:18:52.434  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:18:52.434  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:52.444  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:18:52.444  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:18:52.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:18:52.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:18:52.674   298   298 E SMD     : DCD ON
,07-01 12:18:55.674   298   298 E SMD     : DCD ON
,07-01 12:18:58.674   298   298 E SMD     : DCD ON
,07-01 12:19:01.484   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-01 12:19:01.674   298   298 E SMD     : DCD ON
,07-01 12:19:02.484   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:02.484   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:02.484   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:02.484   912  1245 D BatteryService: stay LED for fully charged
07-01 12:19:02.484   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:02.494   912   912 I MotionRecognitionService: Plugged
,07-01 12:19:02.494   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:02.494  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:02.494  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:02.504  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:02.504  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:02.504  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:19:02.504  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:02.504  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:19:02.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:04.674   298   298 E SMD     : DCD ON
,07-01 12:19:07.674   298   298 E SMD     : DCD ON
,07-01 12:19:10.684   298   298 E SMD     : DCD ON
,07-01 12:19:11.534   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-01 12:19:12.554   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:12.554   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:12.554   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:12.554   912  3696 D BatteryService: stay LED for fully charged
07-01 12:19:12.554   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:12.554  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:12.554  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:19:12.554   912   912 I MotionRecognitionService: Plugged
07-01 12:19:12.554   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:12.564  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:12.564  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:12.564  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:12.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:19:12.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:12.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:12.994   912  1339 E Watchdog: !@Sync 26
,07-01 12:19:13.684   298   298 E SMD     : DCD ON
,07-01 12:19:16.684   298   298 E SMD     : DCD ON
,07-01 12:19:19.684   298   298 E SMD     : DCD ON
,07-01 12:19:21.584   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-01 12:19:22.604   912  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:22.604   912  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:22.614   912  1485 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:22.614   912  1485 D BatteryService: stay LED for fully charged
,07-01 12:19:22.614   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:22.614   912   912 I MotionRecognitionService: Plugged
,07-01 12:19:22.614  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:22.614  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:19:22.614   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:22.614  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:22.614  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:22.624  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:22.624  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:22.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:19:22.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:22.684   298   298 E SMD     : DCD ON
,07-01 12:19:25.684   298   298 E SMD     : DCD ON
,07-01 12:19:28.684   298   298 E SMD     : DCD ON
,07-01 12:19:31.634   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-01 12:19:31.684   298   298 E SMD     : DCD ON
,07-01 12:19:32.664   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:32.664   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:32.664   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:32.664   912  1655 D BatteryService: stay LED for fully charged
07-01 12:19:32.664   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:32.674  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:32.674  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:19:32.674   912   912 I MotionRecognitionService: Plugged
07-01 12:19:32.674   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:32.674  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:32.674  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:32.674  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:32.684  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:32.684  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:19:32.684  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:34.684   298   298 E SMD     : DCD ON
,07-01 12:19:37.684   298   298 E SMD     : DCD ON
,07-01 12:19:38.594   912  1042 I PowerManagerService: [PWL] Off : 600s ago
,07-01 12:19:38.644   912  1114 V AlarmManager: waitForAlarm result :8
,07-01 12:19:40.684   298   298 E SMD     : DCD ON
,07-01 12:19:41.684   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-01 12:19:42.724   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:42.724   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:42.724   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:42.724   912  1689 D BatteryService: stay LED for fully charged
07-01 12:19:42.724   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:42.724  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:42.724  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:19:42.724   912   912 I MotionRecognitionService: Plugged
07-01 12:19:42.724   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:42.734  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:42.734  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:42.734  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:42.734  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:42.744  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:42.744  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:43.004   912  1339 E Watchdog: !@Sync 27
,07-01 12:19:43.684   298   298 E SMD     : DCD ON
,07-01 12:19:46.684   298   298 E SMD     : DCD ON
,07-01 12:19:49.684   298   298 E SMD     : DCD ON
,07-01 12:19:51.734   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:19:52.694   298   298 E SMD     : DCD ON
,07-01 12:19:52.784   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:19:52.784   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:19:52.784   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:19:52.784   912  1533 D BatteryService: stay LED for fully charged
,07-01 12:19:52.784   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:19:52.784   912   912 I MotionRecognitionService: Plugged
,07-01 12:19:52.784  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:19:52.784  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:19:52.784   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:19:52.794  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:19:52.794  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:19:52.794  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:19:52.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:52.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:19:52.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:19:55.694   298   298 E SMD     : DCD ON
,07-01 12:19:58.694   298   298 E SMD     : DCD ON
,07-01 12:20:01.694   298   298 E SMD     : DCD ON
,07-01 12:20:01.784   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:20:02.844   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:02.844   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:20:02.844   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:20:02.844   912  1458 D BatteryService: stay LED for fully charged
07-01 12:20:02.844   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:20:02.844  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:20:02.844  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:20:02.844   912   912 I MotionRecognitionService: Plugged
07-01 12:20:02.844   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:20:02.854  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:20:02.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:20:02.854  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:20:02.854  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:20:02.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:20:02.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:20:04.694   298   298 E SMD     : DCD ON
,07-01 12:20:07.694   298   298 E SMD     : DCD ON
,07-01 12:20:10.694   298   298 E SMD     : DCD ON
,07-01 12:20:11.834   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:20:12.894   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:12.904   912  1456 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:20:12.904   912  1456 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:20:12.904   912  1456 D BatteryService: stay LED for fully charged
07-01 12:20:12.904   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:20:12.904  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:20:12.904  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:20:12.904   912   912 I MotionRecognitionService: Plugged
07-01 12:20:12.904   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:20:12.914  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:20:12.914  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:20:12.914  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:20:12.914  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:20:12.914  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:20:12.914  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:20:13.004   912  1339 E Watchdog: !@Sync 28
,07-01 12:20:13.694   298   298 E SMD     : DCD ON
,07-01 12:20:16.694   298   298 E SMD     : DCD ON
,07-01 12:20:19.694   298   298 E SMD     : DCD ON
,07-01 12:20:21.904   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:20:22.694   298   298 E SMD     : DCD ON
,07-01 12:20:22.954   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:22.954   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:20:22.954   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:20:22.954   912  1336 D BatteryService: stay LED for fully charged
07-01 12:20:22.954   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:20:22.964   912   912 I MotionRecognitionService: Plugged
,07-01 12:20:22.964  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:20:22.964   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:20:22.964  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:20:22.964  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:20:22.974  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:20:22.974  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:20:22.974  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:20:22.974  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:20:22.974  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:20:25.694   298   298 E SMD     : DCD ON
,07-01 12:20:28.704   298   298 E SMD     : DCD ON
,07-01 12:20:31.704   298   298 E SMD     : DCD ON
,07-01 12:20:31.954   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:20:33.024   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:34.704   298   298 E SMD     : DCD ON
,07-01 12:20:37.704   298   298 E SMD     : DCD ON
,07-01 12:20:40.704   298   298 E SMD     : DCD ON
,07-01 12:20:41.994   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:20:43.004   912  1339 E Watchdog: !@Sync 29
,07-01 12:20:43.074   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:43.704   298   298 E SMD     : DCD ON
,07-01 12:20:46.704   298   298 E SMD     : DCD ON
,07-01 12:20:49.704   298   298 E SMD     : DCD ON
,07-01 12:20:52.044   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:20:52.704   298   298 E SMD     : DCD ON
,07-01 12:20:53.144   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:20:55.704   298   298 E SMD     : DCD ON
,07-01 12:20:58.594   912  1042 I PowerManagerService: [PWL] Off : 680s ago
,07-01 12:20:58.704   298   298 E SMD     : DCD ON
,07-01 12:21:01.704   298   298 E SMD     : DCD ON
,07-01 12:21:02.094   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:21:03.194   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:03.194   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:21:03.194   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:21:03.194   912  3665 D BatteryService: stay LED for fully charged
07-01 12:21:03.194   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:21:03.204  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:21:03.204  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:21:03.204   912   912 I MotionRecognitionService: Plugged
07-01 12:21:03.204   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:21:03.204  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:21:03.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:03.214  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:21:03.214  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:21:03.214  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:21:03.214  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:04.714   298   298 E SMD     : DCD ON
,07-01 12:21:07.714   298   298 E SMD     : DCD ON
,07-01 12:21:10.714   298   298 E SMD     : DCD ON
,07-01 12:21:10.784   912  1103 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 12:21:10.784   912  1103 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 12:21:10.784   912  1102 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 12:21:12.154   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,07-01 12:21:12.994   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 12:21:12.994   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 12:21:13.004   912  1103 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:21:13.004   912  1103 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:21:13.004   912  1339 E Watchdog: !@Sync 30
,07-01 12:21:13.254   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:13.254   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:21:13.254   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:21:13.254   912  1094 D BatteryService: stay LED for fully charged
07-01 12:21:13.254   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:21:13.254   912   912 I MotionRecognitionService: Plugged
,07-01 12:21:13.264  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:21:13.264  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:21:13.264   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:21:13.264  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:21:13.264  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:13.264  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:21:13.264  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:21:13.274  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:13.274  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:13.714   298   298 E SMD     : DCD ON
,07-01 12:21:16.714   298   298 E SMD     : DCD ON
,07-01 12:21:19.714   298   298 E SMD     : DCD ON
,07-01 12:21:22.204   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 450
,07-01 12:21:22.714   298   298 E SMD     : DCD ON
,07-01 12:21:23.314   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:25.714   298   298 E SMD     : DCD ON
,07-01 12:21:28.714   298   298 E SMD     : DCD ON
,07-01 12:21:31.714   298   298 E SMD     : DCD ON
,07-01 12:21:32.254   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:21:33.364   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:34.714   298   298 E SMD     : DCD ON
,07-01 12:21:37.714   298   298 E SMD     : DCD ON
,07-01 12:21:40.724   298   298 E SMD     : DCD ON
,07-01 12:21:42.294   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:21:43.004   912  1339 E Watchdog: !@Sync 31
,07-01 12:21:43.424   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:43.424   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:21:43.424   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:21:43.424   912  1458 D BatteryService: stay LED for fully charged
07-01 12:21:43.424   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:21:43.424   912   912 I MotionRecognitionService: Plugged
,07-01 12:21:43.424   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:21:43.434  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:21:43.434  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:21:43.434  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:21:43.434  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:43.434  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:21:43.434  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:21:43.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:21:43.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:43.724   298   298 E SMD     : DCD ON
,07-01 12:21:46.724   298   298 E SMD     : DCD ON
,07-01 12:21:49.724   298   298 E SMD     : DCD ON
,07-01 12:21:52.344   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:21:52.724   298   298 E SMD     : DCD ON
,07-01 12:21:53.484   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:21:53.484   912  1456 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:21:53.484   912  1456 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:21:53.484   912  1456 D BatteryService: stay LED for fully charged
07-01 12:21:53.484   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:21:53.484  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:21:53.484  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:21:53.484   912   912 I MotionRecognitionService: Plugged
07-01 12:21:53.484   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:21:53.494  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:21:53.494  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:53.494  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:53.494  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:21:53.494  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:21:53.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:21:55.724   298   298 E SMD     : DCD ON
,07-01 12:21:58.724   298   298 E SMD     : DCD ON
,07-01 12:22:01.724   298   298 E SMD     : DCD ON
,07-01 12:22:02.394   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:22:03.544   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:03.544   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:22:03.544   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:22:03.544   912  1336 D BatteryService: stay LED for fully charged
07-01 12:22:03.544   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:22:03.554  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:22:03.554  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:22:03.554   912   912 I MotionRecognitionService: Plugged
07-01 12:22:03.554   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:22:03.554  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:22:03.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:03.554  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:22:03.564  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:22:03.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:22:03.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:04.724   298   298 E SMD     : DCD ON
,07-01 12:22:07.724   298   298 E SMD     : DCD ON
,07-01 12:22:10.724   298   298 E SMD     : DCD ON
,07-01 12:22:12.434   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:22:13.014   912  1339 E Watchdog: !@Sync 32
,07-01 12:22:13.604   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:13.614   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:22:13.614   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:22:13.614   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:22:13.614  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:22:13.624   912   912 I MotionRecognitionService: Plugged
,07-01 12:22:13.624   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:22:13.624   912  1094 D BatteryService: stay LED for fully charged
,07-01 12:22:13.624  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:22:13.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:13.624  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:22:13.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:13.634  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:22:13.634  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:22:13.644  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:13.724   298   298 E SMD     : DCD ON
,07-01 12:22:16.724   298   298 E SMD     : DCD ON
,07-01 12:22:19.734   298   298 E SMD     : DCD ON
,07-01 12:22:22.484   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:22:22.734   298   298 E SMD     : DCD ON
,07-01 12:22:23.604   912  1042 I PowerManagerService: [PWL] Off : 765s ago
,07-01 12:22:23.664   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:25.734   298   298 E SMD     : DCD ON
,07-01 12:22:28.734   298   298 E SMD     : DCD ON
,07-01 12:22:31.734   298   298 E SMD     : DCD ON
,07-01 12:22:32.534   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:22:33.724   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:33.724   912  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:22:33.724   912  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:22:33.724   912  1468 D BatteryService: stay LED for fully charged
07-01 12:22:33.724   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:22:33.724  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:22:33.724  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:22:33.724   912   912 I MotionRecognitionService: Plugged
07-01 12:22:33.724   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:22:33.724  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:22:33.734  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:22:33.734  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:22:33.734  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:33.734  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:22:33.734  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:34.734   298   298 E SMD     : DCD ON
,07-01 12:22:37.734   298   298 E SMD     : DCD ON
,07-01 12:22:40.734   298   298 E SMD     : DCD ON
,07-01 12:22:42.584   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-01 12:22:43.014   912  1339 E Watchdog: !@Sync 33
,07-01 12:22:43.734   298   298 E SMD     : DCD ON
,07-01 12:22:43.784   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:43.784   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:22:43.784   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:22:43.784   912  3696 D BatteryService: stay LED for fully charged
07-01 12:22:43.784   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:22:43.784  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:22:43.784  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:22:43.784   912   912 I MotionRecognitionService: Plugged
07-01 12:22:43.784   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:22:43.784  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:22:43.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:43.794  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:22:43.794  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:22:43.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:43.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:46.734   298   298 E SMD     : DCD ON
,07-01 12:22:49.734   298   298 E SMD     : DCD ON
,07-01 12:22:52.624   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:22:52.734   298   298 E SMD     : DCD ON
,07-01 12:22:53.834   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:22:53.834   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:22:53.834   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:22:53.834   912  1094 D BatteryService: stay LED for fully charged
07-01 12:22:53.834   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:22:53.834  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:22:53.834  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:22:53.834   912   912 I MotionRecognitionService: Plugged
07-01 12:22:53.834   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:22:53.834  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:22:53.844  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:53.844  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:22:53.844  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:22:53.844  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:53.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:22:55.734   298   298 E SMD     : DCD ON
,07-01 12:22:58.744   298   298 E SMD     : DCD ON
,07-01 12:23:01.744   298   298 E SMD     : DCD ON
,07-01 12:23:02.674   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:03.884   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:03.884   912  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:23:03.884   912  1719 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:23:03.884   912  1719 D BatteryService: stay LED for fully charged
07-01 12:23:03.884   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:23:03.894  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:23:03.894  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:23:03.894   912   912 I MotionRecognitionService: Plugged
07-01 12:23:03.894   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:23:03.894  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:23:03.894  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:03.904  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:03.904  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:03.904  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:23:03.904  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:23:04.744   298   298 E SMD     : DCD ON
,07-01 12:23:07.744   298   298 E SMD     : DCD ON
,07-01 12:23:10.744   298   298 E SMD     : DCD ON
,07-01 12:23:12.724   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:13.014   912  1339 E Watchdog: !@Sync 34
,07-01 12:23:13.744   298   298 E SMD     : DCD ON
,07-01 12:23:13.954   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:16.744   298   298 E SMD     : DCD ON
,07-01 12:23:19.744   298   298 E SMD     : DCD ON
,07-01 12:23:22.744   298   298 E SMD     : DCD ON
,07-01 12:23:22.794   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:24.014   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:24.014   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:23:24.014   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:23:24.014   912  1655 D BatteryService: stay LED for fully charged
07-01 12:23:24.014   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:23:24.014   912   912 I MotionRecognitionService: Plugged
,07-01 12:23:24.014   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:23:24.014  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:23:24.014  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:23:24.014  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:23:24.024  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:24.024  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:24.024  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:24.024  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:23:24.024  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:23:25.744   298   298 E SMD     : DCD ON
,07-01 12:23:28.744   298   298 E SMD     : DCD ON
,07-01 12:23:31.744   298   298 E SMD     : DCD ON
,07-01 12:23:32.844   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:34.074   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:34.754   298   298 E SMD     : DCD ON
,07-01 12:23:37.754   298   298 E SMD     : DCD ON
,07-01 12:23:40.754   298   298 E SMD     : DCD ON
,07-01 12:23:42.884   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:43.024   912  1339 E Watchdog: !@Sync 35
,07-01 12:23:43.754   298   298 E SMD     : DCD ON
,07-01 12:23:44.134   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:46.754   298   298 E SMD     : DCD ON
,07-01 12:23:49.754   298   298 E SMD     : DCD ON
,07-01 12:23:52.754   298   298 E SMD     : DCD ON
,07-01 12:23:52.934   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:23:53.634   912  1042 I PowerManagerService: [PWL] Off : 855s ago
,07-01 12:23:54.184   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:23:54.194   912  1456 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:23:54.194   912  1456 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:23:54.194   912  1456 D BatteryService: stay LED for fully charged
07-01 12:23:54.194   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:23:54.194  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:23:54.194  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:23:54.194   912   912 I MotionRecognitionService: Plugged
07-01 12:23:54.194   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:23:54.194  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:23:54.194  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:54.204  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:23:54.204  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:23:54.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:23:54.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:23:55.754   298   298 E SMD     : DCD ON
,07-01 12:23:58.754   298   298 E SMD     : DCD ON
,07-01 12:24:01.754   298   298 E SMD     : DCD ON
,07-01 12:24:02.984   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:04.254   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:04.254   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:24:04.254   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:24:04.254   912  1336 D BatteryService: stay LED for fully charged
07-01 12:24:04.254   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:24:04.254  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:24:04.254  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:24:04.254   912   912 I MotionRecognitionService: Plugged
07-01 12:24:04.254   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:24:04.254  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:24:04.264  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:04.264  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:24:04.264  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:24:04.264  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:24:04.264  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:04.754   298   298 E SMD     : DCD ON
,07-01 12:24:07.754   298   298 E SMD     : DCD ON
,07-01 12:24:10.754   298   298 E SMD     : DCD ON
,07-01 12:24:13.024   912  1339 E Watchdog: !@Sync 36
,07-01 12:24:13.034   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:13.764   298   298 E SMD     : DCD ON
,07-01 12:24:14.314   912  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:14.314   912  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:24:14.314   912  1485 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:24:14.314   912  1485 D BatteryService: stay LED for fully charged
07-01 12:24:14.314   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:24:14.314   912   912 I MotionRecognitionService: Plugged
,07-01 12:24:14.314   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:24:14.314  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:24:14.314  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:24:14.314  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:24:14.324  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:24:14.324  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:24:14.324  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:14.324  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:24:14.324  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:16.764   298   298 E SMD     : DCD ON
,07-01 12:24:19.764   298   298 E SMD     : DCD ON
,07-01 12:24:22.764   298   298 E SMD     : DCD ON
,07-01 12:24:23.084   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:24.354   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:24.354   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:24:24.354   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:24:24.354   912  1655 D BatteryService: stay LED for fully charged
07-01 12:24:24.354   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:24:24.354  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:24:24.354  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:24:24.364   912   912 I MotionRecognitionService: Plugged
07-01 12:24:24.364   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:24:24.364  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:24:24.364  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:24.364  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:24:24.364  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:24:24.374  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:24:24.374  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:25.764   298   298 E SMD     : DCD ON
,07-01 12:24:28.764   298   298 E SMD     : DCD ON
,07-01 12:24:31.764   298   298 E SMD     : DCD ON
,07-01 12:24:33.134   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:34.414   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:34.414   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:24:34.414   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:24:34.414   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:24:34.424  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:24:34.424   912   912 I MotionRecognitionService: Plugged
,07-01 12:24:34.424  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-01 12:24:34.424   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:24:34.424   912  3665 D BatteryService: stay LED for fully charged
,07-01 12:24:34.424  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:24:34.424  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:24:34.434  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:24:34.434  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:24:34.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:34.444  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:34.764   298   298 E SMD     : DCD ON
,07-01 12:24:37.764   298   298 E SMD     : DCD ON
,07-01 12:24:40.764   298   298 E SMD     : DCD ON
,07-01 12:24:43.024   912  1339 E Watchdog: !@Sync 37
,07-01 12:24:43.174   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:43.764   298   298 E SMD     : DCD ON
,07-01 12:24:44.454   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:46.764   298   298 E SMD     : DCD ON
,07-01 12:24:49.774   298   298 E SMD     : DCD ON
,07-01 12:24:52.774   298   298 E SMD     : DCD ON
,07-01 12:24:53.224   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:24:54.494   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:24:54.494   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:24:54.494   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:24:54.494   912  1094 D BatteryService: stay LED for fully charged
07-01 12:24:54.494   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:24:54.504   912   912 I MotionRecognitionService: Plugged
,07-01 12:24:54.504   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:24:54.504  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:24:54.504  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:24:54.504  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:24:54.504  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:54.504  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:54.514  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:24:54.514  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:24:54.514  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:24:55.774   298   298 E SMD     : DCD ON
,07-01 12:24:58.774   298   298 E SMD     : DCD ON
,07-01 12:25:01.774   298   298 E SMD     : DCD ON
,07-01 12:25:03.274   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:04.554   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:04.554   912  1719 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:25:04.554   912  1719 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:25:04.554   912  1719 D BatteryService: stay LED for fully charged
07-01 12:25:04.554   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:25:04.554  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:25:04.554  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:25:04.554   912   912 I MotionRecognitionService: Plugged
07-01 12:25:04.554   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:25:04.564  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:25:04.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:25:04.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:25:04.564  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:25:04.564  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:25:04.564  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:25:04.774   298   298 E SMD     : DCD ON
,07-01 12:25:07.774   298   298 E SMD     : DCD ON
,07-01 12:25:10.774   298   298 E SMD     : DCD ON
,07-01 12:25:13.034   912  1339 E Watchdog: !@Sync 38
,07-01 12:25:13.344   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:13.774   298   298 E SMD     : DCD ON
,07-01 12:25:14.604   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:16.774   298   298 E SMD     : DCD ON
,07-01 12:25:19.774   298   298 E SMD     : DCD ON
,07-01 12:25:22.774   298   298 E SMD     : DCD ON
,07-01 12:25:23.404   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:24.654   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:25.784   298   298 E SMD     : DCD ON
,07-01 12:25:28.634   912  1042 I PowerManagerService: [PWL] Off : 950s ago
,07-01 12:25:28.784   298   298 E SMD     : DCD ON
,07-01 12:25:31.784   298   298 E SMD     : DCD ON
,07-01 12:25:33.454   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:34.694   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:34.784   298   298 E SMD     : DCD ON
,07-01 12:25:37.784   298   298 E SMD     : DCD ON
,07-01 12:25:40.784   298   298 E SMD     : DCD ON
,07-01 12:25:43.034   912  1339 E Watchdog: !@Sync 39
,07-01 12:25:43.504   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:43.784   298   298 E SMD     : DCD ON
,07-01 12:25:44.744   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:46.784   298   298 E SMD     : DCD ON
,07-01 12:25:49.784   298   298 E SMD     : DCD ON
,07-01 12:25:52.784   298   298 E SMD     : DCD ON
,07-01 12:25:53.554   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:25:54.794   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:25:55.784   298   298 E SMD     : DCD ON
,07-01 12:25:58.784   298   298 E SMD     : DCD ON
,07-01 12:26:01.784   298   298 E SMD     : DCD ON
,07-01 12:26:03.594   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:26:04.784   298   298 E SMD     : DCD ON
,07-01 12:26:04.844   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:04.844   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:26:04.844   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:26:04.844   912  1094 D BatteryService: stay LED for fully charged
07-01 12:26:04.844   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:26:04.844  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:26:04.844  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:26:04.844   912   912 I MotionRecognitionService: Plugged
07-01 12:26:04.844   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:26:04.844  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:26:04.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:04.854  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:26:04.854  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:26:04.854  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:04.864  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:07.794   298   298 E SMD     : DCD ON
,07-01 12:26:10.784   912  1103 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 12:26:10.784   912  1103 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 12:26:10.784   912  1102 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 12:26:10.794   298   298 E SMD     : DCD ON
,07-01 12:26:10.944   912   995 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 12:26:10.984   912  1126 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-01 12:26:10.984   912  1126 I ApplicationUsage: Updating Usage Statistics in DB @ 1467368771001
,07-01 12:26:10.994   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:10.994   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:10.994   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:10.994   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:10.994   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:10.994   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-01 12:26:10.994   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:10.994   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:10.994   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:10.994   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.004   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.004   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.004   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.004   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.004   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.004   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.004   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.004   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.004   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.004   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.014   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.014   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.014   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.014   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.014   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.014   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.014   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.014   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.014   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.014   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.014   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.014   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.014   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.014   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.024   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:11.024   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.024   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.024   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.024   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.024   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.024   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.024   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.024   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.024   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.034   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.034   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.034   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.034   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.034   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.034   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.034   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.034   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.034   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.034   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.034   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.034   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.034   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.044   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.044   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.044   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.044   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.044   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.044   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.044   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.044   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.044   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.044   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.054   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.054   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.054   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.054   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.054   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.054   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.054   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:11.054   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.054   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.054   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.054   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.054   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.054   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.064   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.064   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.064   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.064   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.064   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.064   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.064   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.064   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.064   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.064   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.064   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.064   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.074   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.074   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.074   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.074   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.074   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.074   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.074   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.074   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.074   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.074   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.074   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.074   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.084   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:11.084   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.084   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.084   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.084   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.084   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.084   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-01 12:26:11.084   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.084   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.084   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.084   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.084   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.084   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.084   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.094   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.094   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.094   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.094   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:11.094   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.094   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.094   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.094   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.094   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:26:11.104   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.104   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.104   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.104   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.114   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.114   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.114   912  1126 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-01 12:26:11.114   912  1126 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-01 12:26:11.114   912  1126 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-01 12:26:11.114   912  1126 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:26:11.114   912  1126 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:26:11.114   912  1126 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467368771125
,07-01 12:26:12.934   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 12:26:12.934   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 12:26:12.944   912  1103 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:26:12.944   912  1103 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:26:13.034   912  1339 E Watchdog: !@Sync 40
,07-01 12:26:13.644   912  3320 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 450
,07-01 12:26:13.794   298   298 E SMD     : DCD ON
,07-01 12:26:14.884   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:16.794   298   298 E SMD     : DCD ON
,07-01 12:26:19.794   298   298 E SMD     : DCD ON
,07-01 12:26:22.794   298   298 E SMD     : DCD ON
,07-01 12:26:23.694   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:26:24.934   912  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:24.934   912  1485 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:26:24.934   912  1485 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:26:24.934   912  1485 D BatteryService: stay LED for fully charged
07-01 12:26:24.934   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:26:24.944  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:26:24.944  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:26:24.944   912   912 I MotionRecognitionService: Plugged
07-01 12:26:24.944   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:26:24.944  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:26:24.944  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:24.954  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:26:24.954  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:26:24.954  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:24.954  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:25.794   298   298 E SMD     : DCD ON
,07-01 12:26:28.794   298   298 E SMD     : DCD ON
,07-01 12:26:31.794   298   298 E SMD     : DCD ON
,07-01 12:26:33.744   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:26:34.794   298   298 E SMD     : DCD ON
,07-01 12:26:34.994   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:34.994   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:26:35.004   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:26:35.004   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:26:35.004   912   912 I MotionRecognitionService: Plugged
,07-01 12:26:35.004   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:26:35.014  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:26:35.014  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:26:35.014   912  1655 D BatteryService: stay LED for fully charged
,07-01 12:26:35.014  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:26:35.014  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:35.024  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:26:35.024  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:26:35.034  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:35.034  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:37.794   298   298 E SMD     : DCD ON
,07-01 12:26:40.794   298   298 E SMD     : DCD ON
,07-01 12:26:43.034   912  1339 E Watchdog: !@Sync 41
,07-01 12:26:43.804   298   298 E SMD     : DCD ON
,07-01 12:26:43.804   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:26:45.054   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:45.054   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:26:45.054   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:26:45.064   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:26:45.064   912   912 I MotionRecognitionService: Plugged
,07-01 12:26:45.064   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:26:45.064  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:26:45.074  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:26:45.074   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:26:45.074  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:45.074  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:26:45.084  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:26:45.084  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:45.084  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:26:45.084  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:26:46.804   298   298 E SMD     : DCD ON
,07-01 12:26:49.804   298   298 E SMD     : DCD ON
,07-01 12:26:52.804   298   298 E SMD     : DCD ON
,07-01 12:26:53.854   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:26:55.114   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:26:55.804   298   298 E SMD     : DCD ON
,07-01 12:26:58.804   298   298 E SMD     : DCD ON
,07-01 12:27:01.804   298   298 E SMD     : DCD ON
,07-01 12:27:03.904   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:27:04.804   298   298 E SMD     : DCD ON
,07-01 12:27:05.184   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:05.184   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:27:05.184   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:27:05.184   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:27:05.194  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:27:05.194   912   912 I MotionRecognitionService: Plugged
,07-01 12:27:05.194   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:27:05.194   912  3665 D BatteryService: stay LED for fully charged
,07-01 12:27:05.204  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:27:05.204  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:27:05.204  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:27:05.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:05.204  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:27:05.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:27:05.204  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:07.804   298   298 E SMD     : DCD ON
,07-01 12:27:08.634   912  1042 I PowerManagerService: [PWL] Off : 1050s ago
,07-01 12:27:10.804   298   298 E SMD     : DCD ON
,07-01 12:27:13.044   912  1339 E Watchdog: !@Sync 42
,07-01 12:27:13.804   298   298 E SMD     : DCD ON
,07-01 12:27:13.964   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:27:15.234   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:16.804   298   298 E SMD     : DCD ON
,07-01 12:27:19.814   298   298 E SMD     : DCD ON
,07-01 12:27:22.814   298   298 E SMD     : DCD ON
,07-01 12:27:24.024   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:27:25.294   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:25.294   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:27:25.304   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:27:25.304   912  1094 D BatteryService: stay LED for fully charged
07-01 12:27:25.304   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:27:25.304  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:27:25.314  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:27:25.314   912   912 I MotionRecognitionService: Plugged
07-01 12:27:25.314   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:27:25.314  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:25.324  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:25.324  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:25.324  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:27:25.324  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:27:25.324  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:27:25.814   298   298 E SMD     : DCD ON
,07-01 12:27:28.814   298   298 E SMD     : DCD ON
,07-01 12:27:31.814   298   298 E SMD     : DCD ON
,07-01 12:27:34.084   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:27:34.814   298   298 E SMD     : DCD ON
,07-01 12:27:35.354   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:35.354   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:27:35.364   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:27:35.364   912  1655 D BatteryService: stay LED for fully charged
07-01 12:27:35.364   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:27:35.364  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:27:35.374  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:27:35.374   912   912 I MotionRecognitionService: Plugged
,07-01 12:27:35.374   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:27:35.374  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:35.384  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:27:35.384  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:27:35.384  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:27:35.384  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:27:35.384  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:27:37.814   298   298 E SMD     : DCD ON
,07-01 12:27:40.814   298   298 E SMD     : DCD ON
,07-01 12:27:43.044   912  1339 E Watchdog: !@Sync 43
,07-01 12:27:43.814   298   298 E SMD     : DCD ON
,07-01 12:27:44.124   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-01 12:27:45.424   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:46.814   298   298 E SMD     : DCD ON
,07-01 12:27:49.814   298   298 E SMD     : DCD ON
,07-01 12:27:52.814   298   298 E SMD     : DCD ON
,07-01 12:27:54.174   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:27:55.474   912  1719 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:27:55.824   298   298 E SMD     : DCD ON
,07-01 12:27:58.824   298   298 E SMD     : DCD ON
,07-01 12:28:01.824   298   298 E SMD     : DCD ON
,07-01 12:28:04.254   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:04.824   298   298 E SMD     : DCD ON
,07-01 12:28:05.534   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:05.534   912  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:28:05.534   912  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:28:05.534   912  1468 D BatteryService: stay LED for fully charged
07-01 12:28:05.534   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:05.534  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:05.534  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:28:05.534   912   912 I MotionRecognitionService: Plugged
07-01 12:28:05.534   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:05.544  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:05.544  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:05.544  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:05.544  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:05.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:28:05.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:07.824   298   298 E SMD     : DCD ON
,07-01 12:28:10.824   298   298 E SMD     : DCD ON
,07-01 12:28:13.044   912  1339 E Watchdog: !@Sync 44
,07-01 12:28:13.824   298   298 E SMD     : DCD ON
,07-01 12:28:14.294   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:15.604   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:15.604   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:28:15.604   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:28:15.604   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:15.614  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:15.614   912   912 I MotionRecognitionService: Plugged
,07-01 12:28:15.614  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:28:15.614   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:15.624   912  3696 D BatteryService: stay LED for fully charged
,07-01 12:28:15.624  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:15.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:15.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:15.634  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:15.634  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:15.644  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:16.824   298   298 E SMD     : DCD ON
,07-01 12:28:19.824   298   298 E SMD     : DCD ON
,07-01 12:28:22.824   298   298 E SMD     : DCD ON
,07-01 12:28:24.354   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:25.654   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:25.654   912  1094 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:28:25.654   912  1094 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:28:25.654   912  1094 D BatteryService: stay LED for fully charged
07-01 12:28:25.654   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:25.654  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:25.654  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:28:25.654   912   912 I MotionRecognitionService: Plugged
07-01 12:28:25.654   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:25.664  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:25.664  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:25.664  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:25.664  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:25.664  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:25.664  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:25.824   298   298 E SMD     : DCD ON
,07-01 12:28:28.824   298   298 E SMD     : DCD ON
,07-01 12:28:31.834   298   298 E SMD     : DCD ON
,07-01 12:28:34.424   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:34.834   298   298 E SMD     : DCD ON
,07-01 12:28:35.704   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:35.704   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:28:35.704   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:28:35.704   912  1655 D BatteryService: stay LED for fully charged
07-01 12:28:35.704   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:35.714  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:35.714  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:28:35.714   912   912 I MotionRecognitionService: Plugged
07-01 12:28:35.714   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:35.714  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:35.714  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:35.724  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:35.724  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:28:35.724  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:35.724  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:37.834   298   298 E SMD     : DCD ON
,07-01 12:28:40.834   298   298 E SMD     : DCD ON
,07-01 12:28:43.044   912  1339 E Watchdog: !@Sync 45
,07-01 12:28:43.834   298   298 E SMD     : DCD ON
,07-01 12:28:44.464   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:45.764   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:45.764   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:28:45.764   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:28:45.764   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:45.774  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:45.774  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:45.774   912   912 I MotionRecognitionService: Plugged
,07-01 12:28:45.774   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:45.774   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:28:45.784  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:45.784  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:45.784  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:45.784  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:28:45.784  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:28:45.794  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:46.834   298   298 E SMD     : DCD ON
,07-01 12:28:49.834   298   298 E SMD     : DCD ON
,07-01 12:28:52.834   298   298 E SMD     : DCD ON
,07-01 12:28:53.644   912  1042 I PowerManagerService: [PWL] Off : 1155s ago
,07-01 12:28:54.514   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:28:55.804   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:28:55.804   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:28:55.804   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:28:55.804   912  1533 D BatteryService: stay LED for fully charged
07-01 12:28:55.804   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:28:55.804  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:28:55.814  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:28:55.814   912   912 I MotionRecognitionService: Plugged
07-01 12:28:55.814   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:28:55.814  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:28:55.814  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:55.814  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:28:55.814  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:28:55.824  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:28:55.824  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:28:55.834   298   298 E SMD     : DCD ON
,07-01 12:28:58.834   298   298 E SMD     : DCD ON
,07-01 12:29:01.834   298   298 E SMD     : DCD ON
,07-01 12:29:04.564   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:04.834   298   298 E SMD     : DCD ON
,07-01 12:29:05.854   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:05.854   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:29:05.854   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:29:05.864   912  1458 D BatteryService: stay LED for fully charged
,07-01 12:29:05.864   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:29:05.864  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:29:05.864  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:29:05.864   912   912 I MotionRecognitionService: Plugged
,07-01 12:29:05.864   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:29:05.874  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:29:05.874  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:29:05.874  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:29:05.884  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:05.884  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:05.884  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:07.834   298   298 E SMD     : DCD ON
,07-01 12:29:10.834   298   298 E SMD     : DCD ON
,07-01 12:29:13.054   912  1339 E Watchdog: !@Sync 46
,07-01 12:29:13.844   298   298 E SMD     : DCD ON
,07-01 12:29:14.614   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:15.904   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:16.844   298   298 E SMD     : DCD ON
,07-01 12:29:19.844   298   298 E SMD     : DCD ON
,07-01 12:29:22.844   298   298 E SMD     : DCD ON
,07-01 12:29:24.654   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:25.844   298   298 E SMD     : DCD ON
,07-01 12:29:25.944   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:25.944   912   928 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:29:25.944   912   928 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:29:25.944   912   928 D BatteryService: stay LED for fully charged
07-01 12:29:25.944   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:29:25.954  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:29:25.954  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:29:25.954   912   912 I MotionRecognitionService: Plugged
07-01 12:29:25.954   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:29:25.954  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:29:25.954  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:25.964  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:25.964  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:25.964  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:29:25.964  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:29:28.844   298   298 E SMD     : DCD ON
,07-01 12:29:31.844   298   298 E SMD     : DCD ON
,07-01 12:29:34.734   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:34.844   298   298 E SMD     : DCD ON
,07-01 12:29:35.994   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:35.994   912  1460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:29:35.994   912  1460 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:29:35.994   912  1460 D BatteryService: stay LED for fully charged
07-01 12:29:36.004   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:29:36.004  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:29:36.004  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:29:36.004   912   912 I MotionRecognitionService: Plugged
07-01 12:29:36.004   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:29:36.004  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:29:36.004  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:36.014  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:29:36.014  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:29:36.014  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:29:36.014  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:37.844   298   298 E SMD     : DCD ON
,07-01 12:29:40.844   298   298 E SMD     : DCD ON
,07-01 12:29:43.054   912  1339 E Watchdog: !@Sync 47
,07-01 12:29:43.844   298   298 E SMD     : DCD ON
,07-01 12:29:44.804   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:46.044   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:46.044   912   929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:29:46.044   912   929 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:29:46.044   912   929 D BatteryService: stay LED for fully charged
07-01 12:29:46.044   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:29:46.054  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:29:46.054  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:29:46.054   912   912 I MotionRecognitionService: Plugged
07-01 12:29:46.054   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:29:46.054  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:29:46.054  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:46.064  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:29:46.064  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:29:46.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:29:46.064  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:46.854   298   298 E SMD     : DCD ON
,07-01 12:29:49.854   298   298 E SMD     : DCD ON
,07-01 12:29:52.854   298   298 E SMD     : DCD ON
,07-01 12:29:54.844   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:29:55.854   298   298 E SMD     : DCD ON
,07-01 12:29:56.094   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:29:56.094   912  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:29:56.094   912  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:29:56.094   912  1468 D BatteryService: stay LED for fully charged
07-01 12:29:56.094   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:29:56.104  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:29:56.104  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:29:56.104   912   912 I MotionRecognitionService: Plugged
07-01 12:29:56.104   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:29:56.104  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:29:56.104  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:56.114  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:29:56.114  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:29:56.114  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:29:56.114  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:29:58.854   298   298 E SMD     : DCD ON
,07-01 12:30:01.854   298   298 E SMD     : DCD ON
,07-01 12:30:04.854   298   298 E SMD     : DCD ON
,07-01 12:30:04.904   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:06.144   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:06.144   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:30:06.144   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:30:06.144   912  3696 D BatteryService: stay LED for fully charged
07-01 12:30:06.144   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:30:06.154  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:30:06.154  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:30:06.154   912   912 I MotionRecognitionService: Plugged
07-01 12:30:06.154   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:30:06.154  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:30:06.154  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:06.164  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:30:06.164  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:30:06.164  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:06.164  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:07.854   298   298 E SMD     : DCD ON
,07-01 12:30:10.854   298   298 E SMD     : DCD ON
,07-01 12:30:13.054   912  1339 E Watchdog: !@Sync 48
,07-01 12:30:13.854   298   298 E SMD     : DCD ON
,07-01 12:30:14.954   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:16.194   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:16.854   298   298 E SMD     : DCD ON
,07-01 12:30:19.854   298   298 E SMD     : DCD ON
,07-01 12:30:22.854   298   298 E SMD     : DCD ON
,07-01 12:30:24.994   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:25.864   298   298 E SMD     : DCD ON
,07-01 12:30:26.244   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:28.864   298   298 E SMD     : DCD ON
,07-01 12:30:31.864   298   298 E SMD     : DCD ON
,07-01 12:30:34.864   298   298 E SMD     : DCD ON
,07-01 12:30:35.044   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:36.294   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:37.864   298   298 E SMD     : DCD ON
,07-01 12:30:40.864   298   298 E SMD     : DCD ON
,07-01 12:30:43.064   912  1339 E Watchdog: !@Sync 49
,07-01 12:30:43.644   912  1042 I PowerManagerService: [PWL] Off : 1265s ago
,07-01 12:30:43.864   298   298 E SMD     : DCD ON
,07-01 12:30:45.094   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:46.344   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:46.344   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:30:46.344   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:30:46.344   912  1689 D BatteryService: stay LED for fully charged
07-01 12:30:46.344   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:30:46.354  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:30:46.354  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:30:46.354   912   912 I MotionRecognitionService: Plugged
,07-01 12:30:46.354   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:30:46.354  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:30:46.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:46.364  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:46.364  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:46.364  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:30:46.364  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:30:46.864   298   298 E SMD     : DCD ON
,07-01 12:30:49.864   298   298 E SMD     : DCD ON
,07-01 12:30:52.864   298   298 E SMD     : DCD ON
,07-01 12:30:55.144   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:30:55.864   298   298 E SMD     : DCD ON
,07-01 12:30:56.394   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:30:56.394   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:30:56.394   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:30:56.394   912  1533 D BatteryService: stay LED for fully charged
07-01 12:30:56.394   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:30:56.394   912   912 I MotionRecognitionService: Plugged
07-01 12:30:56.394   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:30:56.404  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:30:56.404  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:30:56.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:30:56.404  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:30:56.404  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:30:56.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:30:56.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:30:56.404  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:30:58.874   298   298 E SMD     : DCD ON
,07-01 12:31:01.874   298   298 E SMD     : DCD ON
,07-01 12:31:04.874   298   298 E SMD     : DCD ON
,07-01 12:31:05.184   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:06.444   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:06.444   912  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 12:31:06.454   912  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:31:06.454   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:31:06.454  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:31:06.464  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:31:06.464   912   912 I MotionRecognitionService: Plugged
,07-01 12:31:06.464   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:31:06.464   912  1458 D BatteryService: stay LED for fully charged
,07-01 12:31:06.464  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:31:06.474  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:31:06.474  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:31:06.484  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:06.484  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:06.484  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:07.874   298   298 E SMD     : DCD ON
,07-01 12:31:10.784   912  1103 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 12:31:10.784   912  1102 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 12:31:10.794   912  1103 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-01 12:31:10.874   298   298 E SMD     : DCD ON
,07-01 12:31:13.014   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 12:31:13.024   912  1103 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 12:31:13.024   912  1103 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:31:13.034   912  1103 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 12:31:13.064   912  1339 E Watchdog: !@Sync 50
,07-01 12:31:13.874   298   298 E SMD     : DCD ON
,07-01 12:31:15.234   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:16.494   912  1456 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:16.874   298   298 E SMD     : DCD ON
,07-01 12:31:19.874   298   298 E SMD     : DCD ON
,07-01 12:31:22.874   298   298 E SMD     : DCD ON
,07-01 12:31:25.284   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:25.874   298   298 E SMD     : DCD ON
,07-01 12:31:26.544   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:26.544   912   928 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:31:26.544   912   928 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:31:26.544   912   928 D BatteryService: stay LED for fully charged
07-01 12:31:26.544   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:31:26.544   912   912 I MotionRecognitionService: Plugged
,07-01 12:31:26.544   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:31:26.544  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:31:26.544  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:31:26.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:26.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:26.554  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:31:26.554  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:31:26.554  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:26.554  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:31:28.874   298   298 E SMD     : DCD ON
,07-01 12:31:31.874   298   298 E SMD     : DCD ON
,07-01 12:31:34.884   298   298 E SMD     : DCD ON
,07-01 12:31:35.344   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:36.594   912  1460 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:36.594   912  1460 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:31:36.594   912  1460 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:31:36.594   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:31:36.604  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:31:36.604  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:31:36.604   912   912 I MotionRecognitionService: Plugged
07-01 12:31:36.604   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:31:36.604   912  1460 D BatteryService: stay LED for fully charged
,07-01 12:31:36.604  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:31:36.614  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:31:36.614  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:31:36.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:36.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:31:36.624  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:37.884   298   298 E SMD     : DCD ON
,07-01 12:31:40.884   298   298 E SMD     : DCD ON
,07-01 12:31:43.064   912  1339 E Watchdog: !@Sync 51
,07-01 12:31:43.884   298   298 E SMD     : DCD ON
,07-01 12:31:45.394   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:46.634   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:46.634   912   929 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:31:46.634   912   929 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:31:46.634   912   929 D BatteryService: stay LED for fully charged
07-01 12:31:46.634   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:31:46.644  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:31:46.644  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:31:46.644   912   912 I MotionRecognitionService: Plugged
07-01 12:31:46.644   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:31:46.644  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:31:46.644  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:46.654  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:46.654  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:31:46.654  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:31:46.654  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:46.884   298   298 E SMD     : DCD ON
,07-01 12:31:49.884   298   298 E SMD     : DCD ON
,07-01 12:31:52.884   298   298 E SMD     : DCD ON
,07-01 12:31:55.434   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:31:55.884   298   298 E SMD     : DCD ON
,07-01 12:31:56.704   912  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:31:56.704   912  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:31:56.704   912  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:31:56.704   912  1468 D BatteryService: stay LED for fully charged
07-01 12:31:56.704   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:31:56.704  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:31:56.704  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:31:56.704   912   912 I MotionRecognitionService: Plugged
07-01 12:31:56.704   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:31:56.714  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:31:56.714  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:31:56.714  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:31:56.714  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:56.714  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:56.724  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:31:58.884   298   298 E SMD     : DCD ON
,07-01 12:32:01.884   298   298 E SMD     : DCD ON
,07-01 12:32:04.884   298   298 E SMD     : DCD ON
,07-01 12:32:05.484   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:06.764   912  3696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:06.764   912  3696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:32:06.764   912  3696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:32:06.764   912  3696 D BatteryService: stay LED for fully charged
07-01 12:32:06.764   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:32:06.764   912   912 I MotionRecognitionService: Plugged
,07-01 12:32:06.764   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:32:06.764  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:32:06.764  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:32:06.774  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:32:06.774  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:32:06.774  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:32:06.774  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:32:06.774  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:32:06.784  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:32:07.884   298   298 E SMD     : DCD ON
,07-01 12:32:10.894   298   298 E SMD     : DCD ON
,07-01 12:32:13.064   912  1339 E Watchdog: !@Sync 52
,07-01 12:32:13.894   298   298 E SMD     : DCD ON
,07-01 12:32:15.534   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:16.824   912  1094 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:16.894   298   298 E SMD     : DCD ON
,07-01 12:32:19.894   298   298 E SMD     : DCD ON
,07-01 12:32:22.894   298   298 E SMD     : DCD ON
,07-01 12:32:25.584   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:25.894   298   298 E SMD     : DCD ON
,07-01 12:32:26.884   912  1336 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:26.894   912  1336 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:32:26.894   912  1336 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:32:26.894   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:32:26.894  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:32:26.904   912   912 I MotionRecognitionService: Plugged
,07-01 12:32:26.904   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:32:26.904   912  1336 D BatteryService: stay LED for fully charged
,07-01 12:32:26.904  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:32:26.904  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:32:26.904  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:32:26.904  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:32:26.914  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:32:26.914  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:32:26.924  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:32:28.894   298   298 E SMD     : DCD ON
,07-01 12:32:31.894   298   298 E SMD     : DCD ON
,07-01 12:32:34.894   298   298 E SMD     : DCD ON
,07-01 12:32:35.624   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:36.944   912  1485 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:37.894   298   298 E SMD     : DCD ON
,07-01 12:32:38.644   912  1042 I PowerManagerService: [PWL] Off : 1380s ago
,07-01 12:32:40.894   298   298 E SMD     : DCD ON
,07-01 12:32:43.074   912  1339 E Watchdog: !@Sync 53
,07-01 12:32:43.894   298   298 E SMD     : DCD ON
,07-01 12:32:45.674   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:46.894   298   298 E SMD     : DCD ON
,07-01 12:32:47.004   912   929 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:49.904   298   298 E SMD     : DCD ON
,07-01 12:32:52.904   298   298 E SMD     : DCD ON
,07-01 12:32:55.724   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:32:55.904   298   298 E SMD     : DCD ON
,07-01 12:32:57.054   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:32:58.904   298   298 E SMD     : DCD ON
,07-01 12:33:01.904   298   298 E SMD     : DCD ON
,07-01 12:33:04.904   298   298 E SMD     : DCD ON
,07-01 12:33:05.774   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:07.114   912  3665 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:07.124   912  3665 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:33:07.124   912  3665 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:33:07.124   912  3665 D BatteryService: stay LED for fully charged
07-01 12:33:07.124   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:33:07.124  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:33:07.124  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:33:07.124   912   912 I MotionRecognitionService: Plugged
07-01 12:33:07.124   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:33:07.124  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:33:07.124  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:07.134  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:33:07.134  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:33:07.134  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:33:07.134  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:07.904   298   298 E SMD     : DCD ON
,07-01 12:33:10.904   298   298 E SMD     : DCD ON
,07-01 12:33:13.074   912  1339 E Watchdog: !@Sync 54
,07-01 12:33:13.904   298   298 E SMD     : DCD ON
,07-01 12:33:15.824   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:16.904   298   298 E SMD     : DCD ON
,07-01 12:33:17.174   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:17.184   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:33:17.184   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:33:17.184   912  1245 D BatteryService: stay LED for fully charged
07-01 12:33:17.184   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:33:17.184  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:33:17.184  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:33:17.184   912   912 I MotionRecognitionService: Plugged
07-01 12:33:17.184   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:33:17.194  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:33:17.194  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:33:17.194  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:33:17.194  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:33:17.194  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:17.194  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:19.904   298   298 E SMD     : DCD ON
,07-01 12:33:22.904   298   298 E SMD     : DCD ON
,07-01 12:33:25.864   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:25.914   298   298 E SMD     : DCD ON
,07-01 12:33:27.234   912   928 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:28.914   298   298 E SMD     : DCD ON
,07-01 12:33:31.914   298   298 E SMD     : DCD ON
,07-01 12:33:34.914   298   298 E SMD     : DCD ON
,07-01 12:33:35.914   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:37.284   912  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:37.284   912  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:33:37.284   912  1655 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:33:37.294   912  1655 D BatteryService: stay LED for fully charged
07-01 12:33:37.294   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:33:37.294  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:33:37.294  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:33:37.294   912   912 I MotionRecognitionService: Plugged
07-01 12:33:37.294   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:33:37.294  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:33:37.294  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:37.304  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:33:37.304  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:33:37.304  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:33:37.304  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:37.914   298   298 E SMD     : DCD ON
,07-01 12:33:40.914   298   298 E SMD     : DCD ON
,07-01 12:33:43.074   912  1339 E Watchdog: !@Sync 55
,07-01 12:33:43.914   298   298 E SMD     : DCD ON
,07-01 12:33:45.964   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:46.914   298   298 E SMD     : DCD ON
,07-01 12:33:47.344   912  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:47.344   912  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:33:47.344   912  1689 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 12:33:47.344   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:33:47.354  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:33:47.354  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 12:33:47.354  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:33:47.354   912   912 I MotionRecognitionService: Plugged
07-01 12:33:47.354   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:33:47.354   912  1689 D BatteryService: stay LED for fully charged
,07-01 12:33:47.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:33:47.354  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:47.364  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:33:47.364  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
,07-01 12:33:47.374  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:49.914   298   298 E SMD     : DCD ON
,07-01 12:33:52.914   298   298 E SMD     : DCD ON
,07-01 12:33:55.914   298   298 E SMD     : DCD ON
,07-01 12:33:56.004   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:33:57.394   912  1533 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:33:57.394   912  1533 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:33:57.394   912  1533 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:33:57.394   912  1533 D BatteryService: stay LED for fully charged
07-01 12:33:57.394   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 12:33:57.394  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 12:33:57.394  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:33:57.394   912   912 I MotionRecognitionService: Plugged
07-01 12:33:57.394   912   912 I MotionRecognitionService: setPowerConnected  = true
,07-01 12:33:57.394  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 12:33:57.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:57.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:57.404  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 12:33:57.404  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:33:57.404  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 12:33:58.914   298   298 E SMD     : DCD ON
,07-01 12:34:01.914   298   298 E SMD     : DCD ON
,07-01 12:34:04.924   298   298 E SMD     : DCD ON
,07-01 12:34:06.054   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:34:07.434   912  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 12:34:07.924   298   298 E SMD     : DCD ON
,07-01 12:34:10.924   298   298 E SMD     : DCD ON
,07-01 12:34:13.084   912  1339 E Watchdog: !@Sync 56
,07-01 12:34:13.924   298   298 E SMD     : DCD ON
,07-01 12:34:16.104   912  3320 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-01 12:34:16.924   298   298 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-01 12:34:17.484   912  1245 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-01 12:34:17.484   912  1245 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 12:34:17.484   912  1245 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 12:34:17.484   912  1245 D BatteryService: stay LED for fully charged
07-01 12:34:17.484   912   912 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-01 12:34:17.504  3260  3260 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 12:34:17.504  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-01 12:34:17.504  3260  8272 D HeadsetStateMachine: Disconnected process message: 10
07-01 12:34:17.504   912   912 I MotionRecognitionService: Plugged
07-01 12:34:17.504   912   912 I MotionRecognitionService: setPowerConnected  = true
07-01 12:34:17.504  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-01 12:34:17.504  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:34:17.504  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-01 12:34:17.524  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:34:17.524  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 12:34:17.624  8608  8608 D AndroidRuntime: 
07-01 12:34:17.624  8608  8608 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 12:34:17.634  8608  8608 D AndroidRuntime: CheckJNI is OFF
07-01 12:34:17.634  8608  8608 D AndroidRuntime: readGMSProperty: start
07-01 12:34:17.634  8608  8608 D AndroidRuntime: readGMSProperty: already setted!!
07-01 12:34:17.634  8608  8608 D AndroidRuntime: readGMSProperty: end
07-01 12:34:17.634  8608  8608 D AndroidRuntime: addProductProperty: start
07-01 12:34:17.764  8608  8608 E AffinityControl: AffinityControl: registerfunction enter
07-01 12:34:17.784  8608  8608 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-01 12:34:17.794   912  1485 D PackageManager: START PACKAGE DELETE: observer{871857608}
07-01 12:34:17.794   912  1485 D PackageManager: pkg{<packageName>}
07-01 12:34:17.794   912  1485 D PackageManager: user{0}
07-01 12:34:17.794   912  1485 D PackageManager: caller{2000}
07-01 12:34:17.794   912  1485 D PackageManager: flags{2}
07-01 12:34:17.794   912  1485 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-01 12:34:17.794   912  1485 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-01 12:34:17.794   912  1485 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-01 12:34:17.794   912  1485 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:34:17.794   912  1485 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-01 12:34:17.794   912  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-01 12:34:17.794   912  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-01 12:34:17.794   912  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-01 12:34:17.794   912  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
07-01 12:34:17.794   912  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-01 12:34:17.794   912  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-01 12:34:17.804   912   997 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-01 12:34:17.804   912   997 I ActivityManager: Killing 7717:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-01 12:34:17.804   912   997 I ActivityManager:   Force finishing activity ActivityRecord{798d435 u0 com.test.thalitest/.MainActivity t23}
07-01 12:34:17.804   912   997 D FocusedStackFrame: Set to : 0
07-01 12:34:17.814   265  2010 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
07-01 12:34:17.814   265  1877 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
07-01 12:34:17.954   912  3320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:34:17.964   912  3320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:34:17.964   912  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-01 12:34:17.994  5370  5370 I art     : Explicit concurrent mark sweep GC freed 34755(1912KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 384us total 26.618ms
07-01 12:34:18.004  5285  5285 I art     : Explicit concurrent mark sweep GC freed 360(29KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 310us total 24.580ms
07-01 12:34:18.014  1496  1496 I art     : Explicit concurrent mark sweep GC freed 2058(105KB) AllocSpace objects, 2(40KB) LOS objects, 40% free, 20MB/33MB, paused 398us total 28.227ms
07-01 12:34:18.024  5842  5842 I art     : Explicit concurrent mark sweep GC freed 13676(739KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 8.463ms total 40.333ms
07-01 12:34:18.024   912  3211 E libprocessgroup: failed to kill 1 processes for processgroup 7717
07-01 12:34:18.034   912  1038 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-01 12:34:18.034  1746  1746 E SamsungIME: mOCRHelper is null
07-01 12:34:18.044   912  1123 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-01 12:34:18.044  1972  2401 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-01 12:34:18.044  1461  1461 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-01 12:34:18.044  1461  1461 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:34:18.044  1461  1461 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-01 12:34:18.044  1461  1461 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-01 12:34:18.054  1461  1461 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:34:18.054  1461  1461 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:34:18.054  1461  1461 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-01 12:34:18.054  1461  1461 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-01 12:34:18.054  1422  1422 D RegisteredServicesCache: empty dynamic service
07-01 12:34:18.064  1461  1461 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:34:18.064  1461  1461 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-01 12:34:18.074  2619  2619 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-01 12:34:18.084  2619  2619 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467369258092
07-01 12:34:18.084   912  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-01 12:34:18.084   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:34:18.084   912  1146 V NetworkStats: performPollLocked(flags=0x3)
07-01 12:34:18.094   912  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-01 12:34:18.094   912  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:34:18.094   912  1146 V NetworkStats: performPollLocked() took 8ms
07-01 12:34:18.094   912  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:34:18.114  2619  2619 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-01 12:34:18.114   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:34:18.114   912  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 12:34:18.124  6506  6506 I art     : Explicit concurrent mark sweep GC freed 20229(2MB) AllocSpace objects, 2(40KB) LOS objects, 31% free, 17MB/25MB, paused 13.996ms total 97.186ms
07-01 12:34:18.124   912  1456 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-01 12:34:18.124   912  1456 D SecContentProvider2: mCursor = null
07-01 12:34:18.124  2619  2619 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-01 12:34:18.154   912   912 I art     : Explicit concurrent mark sweep GC freed 38865(3MB) AllocSpace objects, 69(1104KB) LOS objects, 30% free, 36MB/52MB, paused 2.574ms total 146.543ms
07-01 12:34:18.164   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-01 12:34:18.164   912  1065 I art     : WaitForGcToComplete blocked for 72.001ms for cause Explicit
07-01 12:34:18.184   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-01 12:34:18.184   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-01 12:34:18.184   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-01 12:34:18.204   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-01 12:34:18.224   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-01 12:34:18.224   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-01 12:34:18.224   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-01 12:34:18.224   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-01 12:34:18.244   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-01 12:34:18.244   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-01 12:34:18.254   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-01 12:34:18.284   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-01 12:34:18.284   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-01 12:34:18.294   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-01 12:34:18.294   912   912 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-01 12:34:18.294   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-01 12:34:18.294  2619  2619 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-01 12:34:18.294   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-01 12:34:18.304   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-01 12:34:18.304   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-01 12:34:18.304   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-01 12:34:18.304   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-01 12:34:18.304  2619  2619 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-01 12:34:18.314   912  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-01 12:34:18.314   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-01 12:34:18.314   912  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.314   912  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.314   912  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.314   912  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.314   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-01 12:34:18.324   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-01 12:34:18.324   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-01 12:34:18.324   912   912 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-01 12:34:18.334   912   912 D RCPManagerService: PackageReceiver onReceive()
07-01 12:34:18.334   912   912 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-01 12:34:18.334   912   912 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-01 12:34:18.334   912   912 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-01 12:34:18.334   912   912 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicy: uID is 10079
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicy: Removed Packageuid is0
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-01 12:34:18.334   912   912 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-01 12:34:18.354  8634  8634 E Zygote  : MountEmulatedStorage()
07-01 12:34:18.354  8634  8634 E Zygote  : v2
07-01 12:34:18.354  8634  8634 I libpersona: KNOX_SDCARD checking this for 10116
07-01 12:34:18.354  8634  8634 I libpersona: KNOX_SDCARD not a persona
07-01 12:34:18.354   912  1533 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8634 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
07-01 12:34:18.364   912   912 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-01 12:34:18.364   912  1179 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
07-01 12:34:18.384  8634  8634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:34:18.384  8634  8634 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:34:18.384  8634  8634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:34:18.394   912  1065 I art     : Explicit concurrent mark sweep GC freed 13642(659KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 1.702ms total 229.593ms
07-01 12:34:18.414  8634  8634 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:34:18.414  8634  8634 D ActivityThread: Added TimaKeyStore provider
07-01 12:34:18.424   912  3320 I SQLiteConnectionPool: exportDB...
07-01 12:34:18.434  8634  8634 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
07-01 12:34:18.444  1461  1461 D SurfaceWidgetView: destroyHardwareResources():1021209394
07-01 12:34:18.444  1461  1461 D Launcher: onRestart, Launcher: 879299595
07-01 12:34:18.444  1461  1461 D Launcher: onStart, Launcher: 879299595
07-01 12:34:18.444  1461  1461 D Launcher.HomeView: onStart
07-01 12:34:18.444  1461  1461 V ActivityThread: updateVisibility : ActivityRecord{3d86f952 token=android.os.BinderProxy@b1dfc72 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-01 12:34:18.444  1787  1956 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-01 12:34:18.444  8634  8634 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-01 12:34:18.454  1787  2105 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-01 12:34:18.454  1787  2105 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-01 12:34:18.454  8634  8634 D elm:14491: ELMEngine.ELMEngine( context ).
07-01 12:34:18.454  8634  8634 D elm:14491: MDMBridge.setEnterpriseBridge()
07-01 12:34:18.454   912  1094 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-01 12:34:18.454   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@209491ef, r.packageName :com.sec.esdk.elm
07-01 12:34:18.454  8634  8634 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-01 12:34:18.464  3871  3871 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-01 12:34:18.464  3871  3871 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-01 12:34:18.464  3871  3871 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-01 12:34:18.464  3871  3871 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-01 12:34:18.464  3871  3871 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 12:34:18.464  3871  3871 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:34:18.464  3871  3871 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:34:18.464  3871  3871 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 12:34:18.464  3871  3871 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 12:34:18.464   265   265 I SurfaceFlinger: id=16 createSurf (1080x1920),1 flag=4, Mauncher
07-01 12:34:18.464  8634  8634 D elm:14491: ElmAgentService : onCreate()
07-01 12:34:18.464  8634  8651 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-01 12:34:18.464  8634  8651 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-01 12:34:18.464  8634  8651 D elm:14491: MDMBridge.getInstance()
07-01 12:34:18.464  8634  8651 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-01 12:34:18.464  8634  8651 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-01 12:34:18.474  1461  1461 D SurfaceWidgetView: getHardwareLayer being called directly
07-01 12:34:18.474  1643  1643 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-01 12:34:18.474  1643  1643 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-01 12:34:18.474  8634  8634 D elm:14491: ElmAgentService : onDestroy().
07-01 12:34:18.474   912  1245 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 12:34:18.484   912  1456 I ActivityManager: Killing 6644:com.sec.android.app.controlpanel/u0a134 (adj 15): emptyCount ##41
07-01 12:34:18.484   912  3320 I SQLiteConnectionPool: ...exportDB
07-01 12:34:18.484   912  1114 V AlarmManager: waitForAlarm result :4
07-01 12:34:18.484   912  3320 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-01 12:34:18.494   912  1065 D PackageManager: delete codoeFile: 
07-01 12:34:18.494  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-01 12:34:18.494  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 12:34:18.494  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-01 12:34:18.494  1195  1195 I KeyguardEffectViewController: *** don't update sliding image ***
07-01 12:34:18.504   912  3665 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-01 12:34:18.504   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@169d4701, r.packageName :com.google.android.gms
07-01 12:34:18.504   912  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-01 12:34:18.504   912  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-01 12:34:18.504  2330  8656 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-01 12:34:18.504  2330  8656 D AccountUtils: Clearing selected account for com.test.thalitest
07-01 12:34:18.514  2330  2330 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-01 12:34:18.514  2330  2330 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-01 12:34:18.514  2330  2330 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 12:34:18.514  2330  2330 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 12:34:18.514   912  1065 D PackageManager: result of delete: 1{871857608}
07-01 12:34:18.514   912  3665 D ActivityManager: caller:android.app.ApplicationThreadProxy@3516523d, r.packageName :com.google.android.gms
07-01 12:34:18.514  8608  8608 D AndroidRuntime: Shutting down VM
07-01 12:34:18.514   912  1038 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a157d6d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t20} time:1704215
07-01 12:34:18.514   912  1038 D MultiWindowConverter: MultiWindow Gesture is not supported with launcher
07-01 12:34:18.524  2330  2330 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-01 12:34:18.524  2330  2330 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-01 12:34:18.524  2330  2330 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-01 12:34:18.524  2330  2330 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-01 12:34:18.524   912  1719 D ActivityManager: caller:android.app.ApplicationThreadProxy@c168383, r.packageName :com.google.android.gms
07-01 12:34:18.524   912  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.524   912  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@131ad539, r.packageName :com.google.android.gms
07-01 12:34:18.534  2330  8656 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-01 12:34:18.534   912  1460 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-01 12:34:18.544   912  1336 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
07-01 12:34:18.544   912  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.544   912  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.544   912  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.544   912  1336 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-01 12:34:18.564  2330  8662 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-01 12:34:18.564  2330  8662 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-01 12:34:18.574  2330  8662 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-01 12:34:18.574  2330  8662 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-01 12:34:18.574  2330  8662 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-01 12:34:18.584  8663  8663 E Zygote  : MountEmulatedStorage()
07-01 12:34:18.584  8663  8663 E Zygote  : v2
07-01 12:34:18.584  8663  8663 I libpersona: KNOX_SDCARD checking this for 10021
07-01 12:34:18.584  8663  8663 I libpersona: KNOX_SDCARD not a persona
07-01 12:34:18.594   912  1336 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8663 uid=10021 gids={50021, 9997} abi=armeabi-v7a
07-01 12:34:18.594   912  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@39220818, r.packageName :com.google.android.gms
07-01 12:34:18.624  8663  8663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:34:18.624  8663  8663 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:34:18.624  8663  8663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:34:18.624   912  1456 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.624   912  1456 D ActivityManager: caller:android.app.ApplicationThreadProxy@adfd856, r.packageName :com.google.android.gms
07-01 12:34:18.634  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-01 12:34:18.644  8663  8663 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:34:18.644  8663  8663 D ActivityThread: Added TimaKeyStore provider
07-01 12:34:18.644  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
07-01 12:34:18.664  2330  8679 E SQLiteLog: (539) recovered 2 pages from /data/data/com.google.android.gms/databases/DocList.db-journal
07-01 12:34:18.664   912  1094 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.664   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@43b8dc4, r.packageName :com.google.android.gms
07-01 12:34:18.664  8663  8663 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
07-01 12:34:18.674  1643  1643 I ConfigService: onCreate
07-01 12:34:18.674  1643  1643 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-01 12:34:18.674   912  1094 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.674   912  1094 D ActivityManager: caller:android.app.ApplicationThreadProxy@23fe7ea9, r.packageName :com.google.android.gms
07-01 12:34:18.674  2330  2330 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-01 12:34:18.684   912  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.684   912  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@11175c65, r.packageName :com.google.android.gms
07-01 12:34:18.684  1643  1643 I ConfigService: onBind returning update interface
07-01 12:34:18.684  1643  1643 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-01 12:34:18.684  1643  1643 I ConfigService: onBind returning service broker
07-01 12:34:18.684  2330  8670 W BaseAppContext: Using Auth Proxy for data requests.
07-01 12:34:18.694   912  1655 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.694   912  1655 D ActivityManager: caller:android.app.ApplicationThreadProxy@25efbdeb, r.packageName :com.google.android.gms
07-01 12:34:18.694  2330  8682 I PeopleContactsSync: CP2 sync disabled
07-01 12:34:18.694   912   929 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 12:34:18.694   912   929 D ActivityManager: caller:android.app.ApplicationThreadProxy@202659e1, r.packageName :com.google.android.gms
07-01 12:34:18.694  2330  8670 W BaseAppContext: Using Auth Proxy for data requests.
07-01 12:34:18.704  2330  4419 I Icing   : doRemovePackageData com.test.thalitest
07-01 12:34:18.704  8663  8663 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-01 12:34:18.704  8663  8663 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-01 12:34:18.704  8663  8663 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-01 12:34:18.704   912  1094 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
07-01 12:34:18.704   912  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.704   912  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.704   912  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.704   912  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.734   912  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-01 12:34:18.734   912  1065 D PackageManager: userId{-1}
07-01 12:34:18.734   912  1065 D PackageManager: andCode{true}
07-01 12:34:18.744  8684  8684 E Zygote  : MountEmulatedStorage()
07-01 12:34:18.744  8684  8684 E Zygote  : v2
07-01 12:34:18.744  8684  8684 I libpersona: KNOX_SDCARD checking this for 10025
07-01 12:34:18.744  8684  8684 I libpersona: KNOX_SDCARD not a persona
07-01 12:34:18.754   912  1094 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8684 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
07-01 12:34:18.764   912  1065 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
07-01 12:34:18.764   912  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.764   912  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.764   912  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.764   912  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 12:34:18.764  2330  8679 W FieldDefinition: Ignoring isIndexed constraint as field also has uniqueness constraint (on just this field, and therefore SQLite will have to create an index on that. For field: com.google.android.gms.drive.database.model.ax@19a0754a
07-01 12:34:18.794  8684  8684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:34:18.794  8684  8684 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:34:18.794  8684  8684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:34:18.804   912  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8693 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-01 12:34:18.804  8693  8693 E Zygote  : MountEmulatedStorage()
07-01 12:34:18.804  8693  8693 E Zygote  : v2
07-01 12:34:18.804  8693  8693 I libpersona: KNOX_SDCARD checking this for 10007
07-01 12:34:18.804  8693  8693 I libpersona: KNOX_SDCARD not a persona
07-01 12:34:18.854  8684  8684 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:34:18.854  8684  8684 D ActivityThread: Added TimaKeyStore provider
07-01 12:34:18.854  8693  8693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 12:34:18.854  8693  8693 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 12:34:18.854  8693  8693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 12:34:18.874  8684  8684 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
07-01 12:34:18.874  8684  8684 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 12:34:18.884  8693  8693 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 12:34:18.884  8693  8693 D ActivityThread: Added TimaKeyStore provider
07-01 12:34:18.894  8693  8693 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
07-01 12:34:18.904   912  1123 I EventHub: Removing device '/dev/input/event6' due to inotify event
07-01 12:34:18.904   912   995 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-01 12:34:18.914  8684  8684 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
07-01 12:34:18.914  8684  8684 D MVFD_interface: <<<  caMVFace_FaceInit
07-01 12:34:18.914   912   995 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-01 12:34:18.924   912  3665 I ActivityManager: Killing 7349:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
07-01 12:34:18.934  2330  8679 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/drive.shared_prefs.xml
07-01 12:34:18.934  2330  8679 E SQLiteLog: (10) unixWrite() File Descriptor : 107 gets errno : 9
07-01 12:34:18.944  2330  8679 E SQLiteLog: (10) unixWrite() File Descriptor : 107 gets errno : 9
07-01 12:34:18.944  2330  8661 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)
07-01 12:34:18.944   912   995 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-01 12:34:18.944  2330  8661 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e3e2d8b in tid 8661 (AsyncOperationS)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: FATAL EXCEPTION: Open database in background
07-01 12:34:18.944  2330  8679 E AndroidRuntime: Process: com.google.android.gms, PID: 2330
07-01 12:34:18.944  2330  8679 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:262)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at com.google.android.gms.drive.database.a.getWritableDatabase(SourceFile:226)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.b(SourceFile:610)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:604)
07-01 12:34:18.944  2330  8679 E AndroidRuntime: 	at com.google.android.gms.drive.database.m.run(SourceFile:625)
07-01 12:34:18.944  8684  8684 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
07-01 12:34:18.944   912  1655 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
07-01 12:34:18.954   912  1123 I EventHub: Removing device '/dev/input/event7' due to inotify event
07-01 12:34:18.954   912  8721 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
07-01 12:34:18.954   912  8721 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-01 12:34:18.954   912  8721 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-01 12:34:18.954   912  8721 E AndroidRuntime: 	... 5 more
07-01 12:34:18.964   912   995 D EnterpriseDeviceManagerService: Package has changed for user 0
07-01 12:34:18.964   912   995 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-01 12:34:18.964   912   995 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-01 12:34:18.964  2330  8679 I Process : Sending signal. PID: 2330 SIG: 9
07-01 12:34:18.974  8684  8684 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
07-01 12:34:18.974  8684  8684 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml
07-01 12:34:18.974  8684  8684 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/uid-prefs.xml

```
