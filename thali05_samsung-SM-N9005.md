#### Test 72145431744cc2c_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-12 11:36:18.844   318   318 E SMD     : DCD ON
,07-12 11:36:19.934  6395  6395 D AndroidRuntime: 
07-12 11:36:19.934  6395  6395 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 11:36:19.934  6395  6395 D AndroidRuntime: CheckJNI is OFF
07-12 11:36:19.934  6395  6395 D AndroidRuntime: readGMSProperty: start
07-12 11:36:19.934  6395  6395 D AndroidRuntime: readGMSProperty: already setted!!
07-12 11:36:19.934  6395  6395 D AndroidRuntime: readGMSProperty: end
07-12 11:36:19.934  6395  6395 D AndroidRuntime: addProductProperty: start
07-12 11:36:20.114  6395  6395 E AffinityControl: AffinityControl: registerfunction enter
07-12 11:36:20.134  6395  6395 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:36:20.144   924  1225 E PersonaManagerService: inState():  stateMachine is null !!
07-12 11:36:20.144   924  1225 I PersonaManagerService: PersonaId don't exist
07-12 11:36:20.144   924  1225 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-12 11:36:20.154   924  1225 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-12 11:36:20.154   924  1225 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:36:20.154   924  1225 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-12 11:36:20.164   924  1225 W ActivityManager: mDVFSHelper.acquire()
07-12 11:36:20.164   924  1225 D FocusedStackFrame: Set to : 0
07-12 11:36:20.164   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:20.164   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:20.164   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:20.164   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:20.264  6410  6410 E Zygote  : MountEmulatedStorage()
07-12 11:36:20.264  6410  6410 E Zygote  : v2
07-12 11:36:20.264  6410  6410 I libpersona: KNOX_SDCARD checking this for 10079
07-12 11:36:20.264  6410  6410 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:20.274   924  1225 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6410 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-12 11:36:20.284  6410  6410 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:20.284  6410  6410 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:20.284  6410  6410 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-12 11:36:20.284  6395  6395 D AndroidRuntime: Shutting down VM
07-12 11:36:20.314  6410  6410 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:36:20.314  6410  6410 D ActivityThread: Added TimaKeyStore provider
07-12 11:36:20.324   924   924 V ActivityManager: Display changed displayId=0
07-12 11:36:20.334  1459  1459 V ActivityThread: updateVisibility : ActivityRecord{2736e940 token=android.os.BinderProxy@70c4392 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-12 11:36:20.334  1805  1819 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-12 11:36:20.354   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:20.354  1459  1459 D SurfaceWidgetView: destroyHardwareResources():257142304
07-12 11:36:20.364  6410  6410 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-12 11:36:20.404   265   304 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-12 11:36:20.404   265  1944 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-12 11:36:20.414  1459  1459 D Launcher: onTrimMemory. Level: 20
,07-12 11:36:20.544  6410  6410 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-12 11:36:20.544  6410  6410 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-12 11:36:20.564  6410  6410 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5015-5018)
,07-12 11:36:20.564  6410  6410 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:20.594  6410  6410 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8cdf125}
,07-12 11:36:20.594  6410  6410 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:20.594  6410  6410 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:20.624  6410  6410 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:20.634  6410  6410 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:20.634  6410  6410 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:36:20.654  6410  6439 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,07-12 11:36:20.664  6410  6410 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-12 11:36:20.664  6410  6410 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,07-12 11:36:20.664  6410  6410 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-12 11:36:20.674  6410  6410 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-12 11:36:20.674  6410  6410 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-12 11:36:20.674  6410  6410 I Adreno-EGL: Build Date: 11/19/14 Wed
07-12 11:36:20.674  6410  6410 I Adreno-EGL: Local Branch: mybranch5813579
07-12 11:36:20.674  6410  6410 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-12 11:36:20.674  6410  6410 I Adreno-EGL: Local Patches: NONE
07-12 11:36:20.674  6410  6410 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-12 11:36:20.854   924  1018 W ActivityManager: Activity pause timeout for ActivityRecord{4b34c81 u0 com.test.thalitest/.MainActivity t36}
,07-12 11:36:20.914  6410  6454 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-12 11:36:20.974  6410  6410 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:20.994  6410  6410 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:36:21.014  6410  6410 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-12 11:36:21.014  6410  6410 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:21.024  6410  6410 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:21.084  6410  6410 D Activity: performCreate Call secproduct feature valuefalse
07-12 11:36:21.094  6410  6410 D Activity: performCreate Call debug elastic valuetrue
,07-12 11:36:21.124  6410  6471 D OpenGLRenderer: Render dirty regions requested: true
,07-12 11:36:21.144   924  1595 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,07-12 11:36:21.144   924  1595 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 11:36:21.144   924  1595 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-12 11:36:21.144   924   924 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 11:36:21.144   924   924 D PersonaManagerService: getPersonasForUser(): returning null!
,07-12 11:36:21.164  6410  6410 V ActivityThread: updateVisibility : ActivityRecord{3bb95577 token=android.os.BinderProxy@1d3d4e11 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-12 11:36:21.204   265   265 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,07-12 11:36:21.244  6410  6471 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 11:36:21.264  6410  6471 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cbe3a8 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-12 11:36:21.274  6410  6471 D OpenGLRenderer: Enabling debug mode 0
,07-12 11:36:21.364  6410  6410 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d3d4e11 time:105816
,07-12 11:36:21.364   924  1058 W ActivityManager: mDVFSHelper.release()
07-12 11:36:21.364   924  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4b34c81 u0 com.test.thalitest/.MainActivity t36} time:105819
,07-12 11:36:21.494  6410  6410 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6410
,07-12 11:36:21.714  6410  6410 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:36:21.834   318   318 E SMD     : DCD ON
,07-12 11:36:21.974  6410  6476 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1360032640
,07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 11:36:21.994  6410  6476 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f748a67 added. We now have 1 listener(s)
,07-12 11:36:22.004  6410  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-12 11:36:22.004  6410  6476 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-12 11:36:22.004  6410  6476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-12 11:36:22.014  6410  6476 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-12 11:36:22.014  6410  6476 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e58a6b2 added. We now have 1 listener(s)
07-12 11:36:22.024  6410  6476 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-12 11:36:22.034  6410  6476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:22.034  6410  6476 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 11:36:22.044  6410  6476 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-12 11:36:22.054  6410  6476 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:22.054  6410  6476 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:22.054  6410  6476 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-12 11:36:22.054  6410  6476 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-12 11:36:22.064  6410  6476 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:22.104  6410  6410 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:23.104  6410  6484 W jxcore-log: Initializing JXcore engine
,07-12 11:36:23.104  6410  6484 W jxcore-log: JXcore engine is ready
,07-12 11:36:23.154  1969  1969 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-12 11:36:23.154  1969  1969 E audit   : type=1400 msg=audit(1468316183.154:201): avc:  denied  { ioctl } for  pid=6484 comm="Thread-1068" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-12 11:36:23.154  1969  1969 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-12 11:36:23.154  1969  1969 E audit   : 
,07-12 11:36:23.154   924  1054 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-12 11:36:23.154   924  1054 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-12 11:36:23.154   924  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
07-12 11:36:23.154   924  1054 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-12 11:36:23.154  1969  1969 E audit   : type=1300 msg=audit(1468316183.154:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ac008d8 items=0 ppid=351 ppcomm=main pid=6484 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1068" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-12 11:36:23.154  1969  1969 E audit   : type=1320 msg=audit(1468316183.154:201): 
,07-12 11:36:23.164   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:23.164   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:23.164   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:23.164   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:23.174  6410  6484 W jxcore-log: Starting JXcore engine
,07-12 11:36:23.214   924  1018 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6485 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-12 11:36:23.214  6485  6485 E Zygote  : MountEmulatedStorage()
07-12 11:36:23.214  6485  6485 E Zygote  : v2
07-12 11:36:23.214  6485  6485 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:23.214  6485  6485 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:23.234   351   351 I art     : Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 295us total 26.432ms
,07-12 11:36:23.244   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.715ms
,07-12 11:36:23.254  6485  6485 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:23.254  6485  6485 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:23.254  6485  6485 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:23.274   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 391us total 27.547ms
,07-12 11:36:23.284  6485  6485 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:23.284  6485  6485 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:23.304  6485  6485 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-12 11:36:23.314  6485  6485 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-12 11:36:23.314  6485  6485 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-12 11:36:23.324   924  1713 I ActivityManager: Killing 5648:com.samsung.android.app.FileShareServer/u0a88 (adj 15): emptyCount ##41
,07-12 11:36:23.334  6410  6484 W jxcore-log: Platform android
07-12 11:36:23.334  6410  6484 W jxcore-log: 
07-12 11:36:23.334  6410  6484 W jxcore-log: Process ARCH arm
07-12 11:36:23.334  6410  6484 W jxcore-log: 
,07-12 11:36:23.534  6410  6484 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:23.534  6410  6484 I jxcore-log: 
,07-12 11:36:23.534  6410  6484 W jxcore-log: JXcore engine is started
,07-12 11:36:23.544  6410  6476 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:23.544  6410  6410 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:24.294   924  1342 E Watchdog: !@Sync 3
,07-12 11:36:24.834   318   318 E SMD     : DCD ON
,07-12 11:36:26.054   370   370 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-12 11:36:26.054   370   370 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-12 11:36:26.284   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:36:26.284   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:36:26.284   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:36:26.284   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:36:26.284   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,07-12 11:36:26.294  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-12 11:36:26.294  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:36:26.294   924   924 I MotionRecognitionService: Plugged
,07-12 11:36:26.294   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:36:26.304  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:36:26.314  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:36:26.314  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:36:26.314  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:27.194  5560  5560 D FactoryTest: Not factory mode
07-12 11:36:27.194  5560  5560 D FactoryTest: Not factory mode. isFactoryMode() returend false
,07-12 11:36:27.194  5560  5560 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,07-12 11:36:27.194  5560  5560 D MTPRx   : still no open session command from host, so toast
07-12 11:36:27.194  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,07-12 11:36:27.194  5560  5560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
07-12 11:36:27.194  5560  5560 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:111645
,07-12 11:36:27.204   924   941 E PersonaManagerService: inState():  stateMachine is null !!
,07-12 11:36:27.204   924   941 I PersonaManagerService: PersonaId don't exist
07-12 11:36:27.204   924   941 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,07-12 11:36:27.214   924   941 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,07-12 11:36:27.214   924   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,07-12 11:36:27.214   924   941 W ActivityManager: mDVFSHelper.acquire()
,07-12 11:36:27.234  5560  5560 E MTPRx   : started activity for popup
,07-12 11:36:27.234   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:27.254   924  1064 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,07-12 11:36:27.254  5560  5560 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:36:27.264  5560  5560 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-12 11:36:27.264   924  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-12 11:36:27.264   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-12 11:36:27.284   924  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 11:36:27.284   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-12 11:36:27.294  3466  3466 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.sec.enterprise.knox.cloudmdm.smdms, uid = -1
,07-12 11:36:27.294   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-12 11:36:27.304   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-12 11:36:27.314   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-12 11:36:27.314   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-12 11:36:27.314  5560  5560 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,07-12 11:36:27.324   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-12 11:36:27.324   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-12 11:36:27.324   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-12 11:36:27.334   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-12 11:36:27.334  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-12 11:36:27.334  1421  1421 D RegisteredServicesCache: empty dynamic service
,07-12 11:36:27.344   924  1458 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-12 11:36:27.344   924  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@a7360a3, r.packageName :com.google.android.gms
,07-12 11:36:27.354   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-12 11:36:27.354  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:36:27.354  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-12 11:36:27.364   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-12 11:36:27.364   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-12 11:36:27.364  1740  6534 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,07-12 11:36:27.374  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-12 11:36:27.374   924   940 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:36:27.374   924   940 D ActivityManager: caller:android.app.ApplicationThreadProxy@60690d0, r.packageName :com.google.android.gms
,07-12 11:36:27.384  5560  5560 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,07-12 11:36:27.384   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-12 11:36:27.384  1459  1459 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:27.384  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:36:27.384  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-12 11:36:27.384   924  1521 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:36:27.384   924  1521 D ActivityManager: caller:android.app.ApplicationThreadProxy@38be9fc, r.packageName :com.google.android.gms
,07-12 11:36:27.394  1459  1459 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-12 11:36:27.394  1740  6536 I PeopleContactsSync: CP2 sync disabled
,07-12 11:36:27.394   924  1240 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:36:27.394   924  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c78a6da, r.packageName :com.google.android.gms
,07-12 11:36:27.394  5560  5560 D Activity: performCreate Call secproduct feature valuefalse
07-12 11:36:27.394  5560  5560 D Activity: performCreate Call debug elastic valuetrue
07-12 11:36:27.394  1459  1459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:36:27.394  1459  1459 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-12 11:36:27.404   924   924 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-12 11:36:27.444  6410  6410 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-12 11:36:27.444   924   940 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-12 11:36:27.444   924   940 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-12 11:36:27.444   924   940 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-12 11:36:27.444   924   924 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-12 11:36:27.444   924   924 D PersonaManagerService: getPersonasForUser(): returning null!
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-12 11:36:27.444  6410  6410 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e15a94c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3f712158, 16908290=android.view.AbsSavedState$1@3f712158}, android:focusedViewId=100}]}]
07-12 11:36:27.444  6410  6410 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-12 11:36:27.444  6410  6410 V ActivityThread: updateVisibility : ActivityRecord{3bb95577 token=android.os.BinderProxy@1d3d4e11 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-12 11:36:27.444  6410  6410 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-12 11:36:27.444  6410  6410 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-12 11:36:27.444  6410  6410 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d3d4e11 time:111898
,07-12 11:36:27.524   924  1660 I art     : Explicit concurrent mark sweep GC freed 158702(9MB) AllocSpace objects, 17(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.434ms total 106.151ms
,07-12 11:36:27.524   924  1660 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-12 11:36:27.524   924  1660 D SecContentProvider2: mCursor = null
,07-12 11:36:27.584   924   940 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-12 11:36:27.584   924   940 D ActivityManager: caller:android.app.ApplicationThreadProxy@3faba9e8, r.packageName :com.google.android.googlequicksearchbox
,07-12 11:36:27.594   924  1713 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,07-12 11:36:27.594   924  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:27.594   924  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:27.594   924  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:27.594   924  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:27.594  1515  6537 I UpdateIcingCorporaServi: Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,07-12 11:36:27.634  6538  6538 E Zygote  : MountEmulatedStorage()
07-12 11:36:27.634  6538  6538 E Zygote  : v2
07-12 11:36:27.634  6538  6538 I libpersona: KNOX_SDCARD checking this for 10088
07-12 11:36:27.634  6538  6538 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:27.644   924  1713 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6538 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:27.654  1515  6537 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 65 ms] updated apps [took 65 ms] 
,07-12 11:36:27.674  6538  6538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:27.674  6538  6538 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:27.674  6538  6538 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:27.694  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:27.694  6538  6538 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:27.714  6538  6538 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,07-12 11:36:27.724  6538  6538 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,07-12 11:36:27.744   924  1562 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-12 11:36:27.744   924  1562 D ActivityManager: caller:android.app.ApplicationThreadProxy@a4a56a6, r.packageName :com.samsung.android.app.galaxyfinder
,07-12 11:36:27.744  5725  5725 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,07-12 11:36:27.754   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:27.754   924  1521 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,07-12 11:36:27.754   924  1521 D ActivityManager: caller:android.app.ApplicationThreadProxy@3271a8e7, r.packageName :com.google.android.apps.plus
,07-12 11:36:27.764   924  1713 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,07-12 11:36:27.764   924  1713 D ActivityManager: caller:android.app.ApplicationThreadProxy@1443533d, r.packageName :com.google.android.apps.plus
,07-12 11:36:27.774   924  1488 I ActivityManager: Killing 5240:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,07-12 11:36:27.834   318   318 E SMD     : DCD ON
,07-12 11:36:27.844   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-12 11:36:27.854   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-12 11:36:27.854   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.854   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-12 11:36:27.854   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-12 11:36:27.864   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-12 11:36:27.864   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.864   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-12 11:36:27.864   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-12 11:36:27.874   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.874   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-12 11:36:27.874   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:36:27.874   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-12 11:36:27.874   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.874   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.874   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-12 11:36:27.884   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.884   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-12 11:36:27.884   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-12 11:36:27.884   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-12 11:36:27.894   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-12 11:36:27.894   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.894   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-12 11:36:27.904   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-12 11:36:27.904   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,07-12 11:36:27.904   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-12 11:36:27.914   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.914   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.914   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-12 11:36:27.914   924  1014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 11:36:27.914   924  1014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:27.914   924  1014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:36:27.914   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.914   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-12 11:36:27.924   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-12 11:36:27.924   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.924   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-12 11:36:27.924   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.924   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-12 11:36:27.934   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.934   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:36:27.934   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-12 11:36:27.934   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.934   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-12 11:36:27.934   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.934   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:36:27.934   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-12 11:36:27.944   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:27.944   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:36:27.944   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-12 11:36:27.944   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-12 11:36:28.474   924  2963 D SSRM:n  : SIOP:: AP = 380, PST = 393, CUR = 450
,07-12 11:36:30.194   924  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-12 11:36:30.214   924  1018 W ActivityManager: mDVFSHelper.release()
,07-12 11:36:30.834   318   318 E SMD     : DCD ON
,07-12 11:36:30.874   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:36:31.054   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:32.054   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:32.124   924  1060 I PowerManagerService: [PWL] Off : 75s ago
,07-12 11:36:33.054   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:33.824  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:36:33.824  6410  6484 I jxcore-log: 
,07-12 11:36:33.824  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:36:33.824  6410  6484 I jxcore-log: 
07-12 11:36:33.824  6410  6484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:33.824  6410  6484 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:33.834  6410  6484 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:36:33.834  6410  6484 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:36:33.834  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:36:33.834  6410  6484 I jxcore-log: 
07-12 11:36:33.834   318   318 E SMD     : DCD ON
07-12 11:36:33.834  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:36:33.834  6410  6484 I jxcore-log: 
,07-12 11:36:34.054   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:34.184  6410  6484 I jxcore-log: Unit Test app is loaded
07-12 11:36:34.184  6410  6484 I jxcore-log: 
,07-12 11:36:34.194  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:36:34.194  6410  6484 I jxcore-log: 
,07-12 11:36:34.194  6410  6410 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-12 11:36:34.204  6410  6484 I WifiManager: packageName : com.test.thalitest
,07-12 11:36:34.204   924  1458 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-12 11:36:34.204   924  1458 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-12 11:36:34.204   924  1458 D SecContentProvider2: mCursor = null
,07-12 11:36:34.204   924  1458 D WifiService: setWifiEnabled: true pid=6410, uid=10079
,07-12 11:36:34.204   924  1458 W ActivityManager: Permission Denial: getCurrentUser() from pid=6410, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:36:34.204   924  1458 W WifiService: Failed getting userId using ActivityManagerNative
07-12 11:36:34.204   924  1458 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6410, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:36:34.204   924  1458 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-12 11:36:34.204   924  1458 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-12 11:36:34.204   924  1458 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-12 11:36:34.204   924  1458 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-12 11:36:34.204   924  1458 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-12 11:36:34.204   924  1458 D SettingsProvider: name = wifi_on
,07-12 11:36:34.214   924  1595 I WifiService: disconnect: pid=6410, uid=10079
,07-12 11:36:34.214   924  1146 E WifiHW  : ##################### set firmware type 0 #####################
,07-12 11:36:34.214   308  1053 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-12 11:36:34.214   308  1053 I WifiHW  : module is semco
07-12 11:36:34.214   308  1053 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-12 11:36:34.214   308  1053 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-12 11:36:34.214   308  1053 E WifiHW  : TEMP_FAILURE_RETRY complete
07-12 11:36:34.214   308  1053 D SoftapController: Softap fwReload - Ok
,07-12 11:36:34.214  6410  6484 D BluetoothAdapter: enable()
,07-12 11:36:34.224   924  1562 W ActivityManager: Permission Denial: getCurrentUser() from pid=6410, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-12 11:36:34.224   924  1562 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-12 11:36:34.224   924  1562 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6410, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-12 11:36:34.224   924  1562 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-12 11:36:34.224   924  1562 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-12 11:36:34.224   924  1562 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-12 11:36:34.224   924  1562 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-12 11:36:34.224   924  1562 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-12 11:36:34.224   308  1053 D CommandListener: Setting iface cfg
07-12 11:36:34.224   924  1562 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-12 11:36:34.224   308  1053 D CommandListener: Trying to bring down wlan0
07-12 11:36:34.224   924  1562 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-12 11:36:34.224   924  1562 D SettingsProvider: name = bluetooth_on
,07-12 11:36:34.224   308  1053 D CommandListener: Clearing all IP addresses on wlan0
,07-12 11:36:34.224   924  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-12 11:36:34.224   924  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-12 11:36:34.224   924  1057 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-12 11:36:34.234  2898  2955 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-12 11:36:34.234  6410  6484 I jxcore-log: My device name is: samsung-SM-N9005
07-12 11:36:34.234  6410  6484 I jxcore-log: 
07-12 11:36:34.234  2898  2955 D BluetoothAdapterProperties: Setting state to 11
07-12 11:36:34.234  2898  2955 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-12 11:36:34.234  2898  2955 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:36:34.234  2898  2955 D BluetoothAdapterService: updateAdapterState state is 11
,07-12 11:36:34.234  2898  2955 D BluetoothAdapterService: Autoconnection is available 
07-12 11:36:34.234  2898  2955 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-12 11:36:34.234  2898  2955 D BtConfig.SecureMode: isSecureModeOn:false
,07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-12 11:36:34.234   924   924 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:34.234   924   924 I InputMethodManagerService: [BT Setting State] State =11
,07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-12 11:36:34.234  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-12 11:36:34.234  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:36:34.244  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-12 11:36:34.244  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,07-12 11:36:34.244  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-12 11:36:34.244  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-12 11:36:34.244   924  1521 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-12 11:36:34.244   924  1660 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-12 11:36:34.244   924  1240 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-12 11:36:34.244   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@3725a6c7, r.packageName :com.android.bluetooth
07-12 11:36:34.244  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-12 11:36:34.244  1189  1617 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,07-12 11:36:34.254  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-12 11:36:34.254   924  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-12 11:36:34.254   924  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@308f341d, r.packageName :com.android.bluetooth
,07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-12 11:36:34.254  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-12 11:36:34.254   924  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-12 11:36:34.254   924  1713 D ActivityManager: caller:android.app.ApplicationThreadProxy@184be863, r.packageName :com.android.bluetooth
,07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,07-12 11:36:34.254  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-12 11:36:34.254   924  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-12 11:36:34.254  1766  1766 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-12 11:36:34.254   924  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@96ff519, r.packageName :com.android.bluetooth
,07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,07-12 11:36:34.254  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-12 11:36:34.254  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-12 11:36:34.254   924  1686 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-12 11:36:34.264   924  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@180aa7bf, r.packageName :com.android.bluetooth
,07-12 11:36:34.264  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,07-12 11:36:34.264  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-12 11:36:34.264  2898  2955 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-12 11:36:34.264   924  1447 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-12 11:36:34.264   924  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e01c9d5, r.packageName :com.android.bluetooth
,07-12 11:36:34.264  2898  2898 D HeadsetService: Received start request. Starting profile...
,07-12 11:36:34.264  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,07-12 11:36:34.264  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-12 11:36:34.264  2898  2955 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-12 11:36:34.264   924  1315 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-12 11:36:34.264   924  1315 D ActivityManager: caller:android.app.ApplicationThreadProxy@38cc00db, r.packageName :com.android.bluetooth
,07-12 11:36:34.274  2898  2898 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:36:34.274  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:36:34.274  2898  2898 D HeadsetStateMachine: make
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:36:34.274  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-12 11:36:34.274  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-12 11:36:34.274  2898  2955 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-12 11:36:34.274  2898  2955 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-12 11:36:34.274  2898  2955 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D QSpanel : label top:23
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:36:34.274  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:36:34.274  2898  2898 E HeadsetStateMachine: # of Max HF connection is 2
,07-12 11:36:34.284  1578  1578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:34.284   924  1713 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-12 11:36:34.284   924  1686 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-12 11:36:34.284  2898  2898 I bluedroid: get_profile_interface handsfree
,07-12 11:36:34.284  4145  4145 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:36:34.314  2898  2898 I DualScoManager: Instantiating Dual Sco Manager
07-12 11:36:34.314  2898  2898 I DualScoManager: Set HeadsetServiceHelper
,07-12 11:36:34.314  2898  2898 D BluetoothAtMessage: createCMTIContentObservers
,07-12 11:36:34.314   924  3435 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-12 11:36:34.314   924  3435 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:36:34.314   924  3435 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:36:34.314   924  3435 D SettingsProvider: selectionArgs: false
07-12 11:36:34.314   924  3435 D SettingsProvider: selectionArgs: 1002
07-12 11:36:34.314   924  3435 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-12 11:36:34.314   924  3435 D SettingsProvider: ret = -1
,07-12 11:36:34.324   924  3435 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,07-12 11:36:34.324  2898  6586 D HeadsetStateMachine: Enter Disconnected: -2
,07-12 11:36:34.324  2898  6586 E HeadsetStateMachine: set to mRemoteBrsf = 0
07-12 11:36:34.324  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.324  2898  6586 D HeadsetStateMachine: map size, before remove : 0
,07-12 11:36:34.324  2898  6586 D HeadsetStateMachine: map size, after remove: 0
07-12 11:36:34.324   924   924 D BluetoothA2dp: Proxy object connected
07-12 11:36:34.324  2898  6586 D HeadsetStateMachine: mNextConnectingDevice : null
07-12 11:36:34.324  2898  2898 D A2dpService: Received start request. Starting profile...
,07-12 11:36:34.324  3072  3072 D BluetoothA2dp: Proxy object connected
,07-12 11:36:34.324  2898  2898 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-12 11:36:34.324  2898  2898 V Avrcp   : make
,07-12 11:36:34.334  2898  2898 V Avrcp   : Avrcp
,07-12 11:36:34.334  2898  2898 I bluedroid: get_profile_interface avrcp
,07-12 11:36:34.334  2898  2898 V Avrcp   : start
,07-12 11:36:34.334   924  1146 E WifiHW  : supplicant_name : p2p_supplicant
,07-12 11:36:34.334   924  1146 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-12 11:36:34.334   924   924 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:34.344   924  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-12 11:36:34.344  2898  2898 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 11:36:34.344  4145  4145 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:34.344  2898  2898 V Avrcp   : ++registerMediaPlayers++
,07-12 11:36:34.344  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-12 11:36:34.344  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:34.344  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-12 11:36:34.344  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:34.344  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-12 11:36:34.344  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:34.344  1189  1617 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-12 11:36:34.344  2898  2898 I Avrcp   : No of Audio players :: 2
07-12 11:36:34.344  2898  2898 I Avrcp   : App Package name is com.google.android.music
,07-12 11:36:34.344  1189  1189 D HotspotTile: onReceive : 2, 0
,07-12 11:36:34.344  2898  2898 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-12 11:36:34.354  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:36:34.354  2898  2898 I Avrcp   : App pkg name is Google Play Music
,07-12 11:36:34.354  2898  2898 I Avrcp   : Name::Google Play Music
,07-12 11:36:34.354  2898  2898 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-12 11:36:34.354  2898  2898 I Avrcp   : App Package name is com.sec.android.app.music
,07-12 11:36:34.354  2898  2898 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-12 11:36:34.354  2898  2898 I Avrcp   : App pkg name is Music
,07-12 11:36:34.354  2898  2898 I Avrcp   : Name::Music
07-12 11:36:34.354  2898  2898 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-12 11:36:34.354  2898  2898 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-12 11:36:34.354  1189  1189 D QSpanel : label top:23
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:36:34.354  2898  2898 I Avrcp   : No of Video players :: 1
,07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:36:34.354  2898  2898 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
,07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:36:34.354  2898  2898 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-12 11:36:34.354  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:36:34.364  2898  2898 I Avrcp   : Video App pkg name is Video Player
,07-12 11:36:34.364  2898  2898 I Avrcp   : Name::Video Player
07-12 11:36:34.364  2898  2898 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-12 11:36:34.364  2898  2898 I Avrcp   : Add tempPlayer
07-12 11:36:34.364  2898  2898 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-12 11:36:34.364  2898  2898 I Avrcp   : Total no of players: 4
,07-12 11:36:34.364  2898  2898 V Avrcp   : swapping the samsung player with 1st player
07-12 11:36:34.364  2898  2898 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-12 11:36:34.364  2898  6592 V Avrcp   : handleMessage, msg=207
07-12 11:36:34.364  2898  6592 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-12 11:36:34.364  2898  2898 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:36:34.364  2898  2898 D A2dpStateMachine: make
,07-12 11:36:34.364  2898  2898 I bluedroid: get_profile_interface a2dp
,07-12 11:36:34.364  2898  6596 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-12 11:36:34.364  2898  2898 E bt-btif : warning : media task started media_task_refcnt 1 
,07-12 11:36:34.374  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.374  2898  2898 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:36:34.374  2898  2898 D HidService: Received start request. Starting profile...
07-12 11:36:34.374  2898  2898 I bluedroid: get_profile_interface hidhost
,07-12 11:36:34.374  2898  2898 D HidService: setHidService(): set to: null
07-12 11:36:34.374  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
07-12 11:36:34.374  2898  6592 D BluetoothMediaBrowser: no now playing list
07-12 11:36:34.374  2898  6592 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,07-12 11:36:34.374  2898  2898 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-12 11:36:34.374  2898  2898 D HealthService: Received start request. Starting profile...
,07-12 11:36:34.374  2898  6592 D Avrcp   :  checkNowPlayingList start
07-12 11:36:34.374  2898  6595 D A2dpStateMachine: Enter Disconnected: -2
,07-12 11:36:34.374  6593  6593 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-12 11:36:34.374  6593  6593 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-12 11:36:34.374  2898  2898 I bluedroid: get_profile_interface health
,07-12 11:36:34.374  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.384  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-12 11:36:34.384  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-12 11:36:34.384  2898  2898 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-12 11:36:34.384   424   424 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6593
07-12 11:36:34.384   424   424 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
07-12 11:36:34.384  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:36:34.384  6593  6593 I wpa_supplicant: ssSupport state is = 1
,07-12 11:36:34.384  6593  6593 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-12 11:36:34.384   924   924 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:36:34.384  2898  2898 D PanService: Received start request. Starting profile...
,07-12 11:36:34.384  2898  2898 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:36:34.384  2898  2898 I bluedroid: get_profile_interface pan
,07-12 11:36:34.384  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
07-12 11:36:34.384   424   424 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6593
07-12 11:36:34.384   424   424 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,07-12 11:36:34.384  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.384  2898  2898 D BluetoothMapService: Received start request. Starting profile...
,07-12 11:36:34.394   924  1686 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,07-12 11:36:34.394   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:34.394   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.394   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.394   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:34.434  6601  6601 E Zygote  : MountEmulatedStorage()
07-12 11:36:34.434  6601  6601 I libpersona: KNOX_SDCARD checking this for 10186
07-12 11:36:34.434  6601  6601 E Zygote  : v2
07-12 11:36:34.434  6601  6601 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:34.444   924  1686 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6601 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-12 11:36:34.474  6601  6601 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:34.474  6601  6601 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:34.474  6601  6601 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:34.504  6601  6601 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:34.504  6601  6601 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:34.514  6601  6601 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-12 11:36:34.514  6601  6601 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-12 11:36:34.514  6601  6601 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:36:34.514  6601  6601 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-12 11:36:34.514  6601  6601 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:36:34.514  6601  6601 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-12 11:36:34.604   924  1315 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:36:34.634  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.634  2898  2898 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-12 11:36:34.644  2898  2898 D SapService: Received start request. Starting profile...
07-12 11:36:34.644  2898  2898 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-12 11:36:34.644  2898  2898 I bluedroid: get_profile_interface sap
07-12 11:36:34.644  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
,07-12 11:36:34.644  2898  2898 D HeadsetStateMachine: Try to query the phonestate on bind
,07-12 11:36:34.644  1406  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,07-12 11:36:34.644  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-12 11:36:34.644   924  1315 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:36:34.654   924  1660 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-12 11:36:34.654   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:34.654   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.654   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.654   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:34.654  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-12 11:36:34.654  1406  1406 W BluetoothHeadset: Proxy not attached to service
,07-12 11:36:34.654  2898  2898 D HeadsetStateMachine: Proxy object connected
,07-12 11:36:34.654  2898  2898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-12 11:36:34.654  2898  2898 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-12 11:36:34.654  2898  6586 D HeadsetStateMachine: Disconnected process message: 11
07-12 11:36:34.654  2898  2898 D HeadsetPhoneState: Signal level : previous=0 curr=1
07-12 11:36:34.654  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:36:34.654  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-12 11:36:34.654  2898  2898 D BluetoothA2dp: Proxy object connected
07-12 11:36:34.654  2898  2898 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-12 11:36:34.654  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-12 11:36:34.654  2898  6586 D HeadsetStateMachine: Disconnected process message: 18
07-12 11:36:34.654  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
07-12 11:36:34.654  2898  6586 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:36:34.654  2898  6586 D HeadsetStateMachine: Disconnected process message: 11
,07-12 11:36:34.674   424   424 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,07-12 11:36:34.694  6622  6622 E Zygote  : MountEmulatedStorage()
07-12 11:36:34.694  6622  6622 E Zygote  : v2
07-12 11:36:34.694  6622  6622 I libpersona: KNOX_SDCARD checking this for 10092
07-12 11:36:34.694  6622  6622 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:34.704   924  1660 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6622 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-12 11:36:34.704   924  1225 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-12 11:36:34.704   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.704   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.704   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:34.704   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:34.724   924  1595 D RCPManagerService: exchangeData() failure , invalid userId
07-12 11:36:34.724  6622  6622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:34.724  6622  6622 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:34.724  6622  6622 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-12 11:36:34.744  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:34.744  6622  6622 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:34.754  6638  6638 E Zygote  : MountEmulatedStorage()
07-12 11:36:34.754   924  1225 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6638 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-12 11:36:34.754  6638  6638 E Zygote  : v2
07-12 11:36:34.754  6638  6638 I libpersona: KNOX_SDCARD checking this for 10140
07-12 11:36:34.754  6638  6638 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:34.784  6638  6638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:34.784   924  1458 D RCPManagerService: exchangeData() failure , invalid userId
07-12 11:36:34.784  6638  6638 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:34.784  6638  6638 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:34.784  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-12 11:36:34.784  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-12 11:36:34.784  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-12 11:36:34.784   924  1562 I ActivityManager: Killing 5533:com.sec.providers.settingsearch/u0a191 (adj 15): emptyCount ##41
,07-12 11:36:34.794   924  1562 I ActivityManager: Killing 5255:com.android.calendar/u0a172 (adj 15): emptyCount ##42
,07-12 11:36:34.794  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-12 11:36:34.794  2898  2898 E BluetoothAdapterService(735166748): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-12 11:36:34.794  2898  2955 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-12 11:36:34.794  2898  2955 I bluedroid: enable
,07-12 11:36:34.794  2898  2958 E bt-btif : Calling BTA_HhEnable
07-12 11:36:34.794  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.794  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.794  2898  2958 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-12 11:36:34.794  2898  2958 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-12 11:36:34.794  2898  2958 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-12 11:36:34.794  2898  2958 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-12 11:36:34.794  2898  2958 E BluetoothServiceJni: populateRssiValuesNative
07-12 11:36:34.794  2898  2958 I bluedroid: getModelRssiValues
07-12 11:36:34.794  2898  2958 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-12 11:36:34.794  2898  2958 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-12 11:36:34.794   924   924 D SettingsProvider: name = bluetooth_name
07-12 11:36:34.794  2898  2958 D BluetoothAdapterProperties: Name is: Galaxy Note3
,07-12 11:36:34.794  2898  2958 D BluetoothAdapterProperties: Scan Mode:20
07-12 11:36:34.794  2898  2958 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:36:34.804  2898  2958 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-12 11:36:34.804  2898  2958 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-12 11:36:34.804  2898  2958 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
07-12 11:36:34.804  2898  2958 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-12 11:36:34.804  2898  2958 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-12 11:36:34.804  2898  2961 D bt_upio : proc btwrite assertion
,07-12 11:36:34.804  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:36:34.804  2898  2958 D IOP_DB_BT: db_open: db_open : handle 3026165776l, read 14063 bytes onto local cache
07-12 11:36:34.804  2898  2958 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-12 11:36:34.804  2898  2958 D IOP_DB_BT: db_query: result 1
07-12 11:36:34.804  2898  2958 I         : iop_db_open: iop_db_open status 0
,07-12 11:36:34.804  2898  2958 D bte_conf: Device ID record 1 : primary
07-12 11:36:34.804  2898  2958 D bte_conf:   vendorId            = 0075
07-12 11:36:34.804  2898  2958 D bte_conf:   vendorIdSource      = 0001
07-12 11:36:34.804  2898  2958 D bte_conf:   product             = 0100
07-12 11:36:34.804  2898  2958 D bte_conf:   version             = 0200
07-12 11:36:34.804  2898  2958 D bte_conf:   clientExecutableURL = 
07-12 11:36:34.804  2898  2958 D bte_conf:   serviceDescription  = 
07-12 11:36:34.804  2898  2958 D bte_conf:   documentationURL    = 
07-12 11:36:34.804  2898  2958 D bte_conf: bte_load_did_conf no section named DID2.
07-12 11:36:34.804  6622  6622 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
07-12 11:36:34.804  2898  2958 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-12 11:36:34.804  2898  2958 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-12 11:36:34.804  2898  2955 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-12 11:36:34.804  2898  2955 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:36:34.804  2898  2955 D BluetoothAdapterProperties: State =  11
,07-12 11:36:34.804   924   940 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-12 11:36:34.804  2898  2955 D BluetoothAdapterProperties: Setting state to 12
07-12 11:36:34.804  2898  2955 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 11:36:34.804  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.804  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.814  2898  2958 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:36:34.814  2898  2958 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:36:34.814  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.814  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.814   924   941 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-12 11:36:34.814   924   941 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:36:34.814   924   941 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:36:34.814   924   941 D SettingsProvider: selectionArgs: false
07-12 11:36:34.814   924   941 D SettingsProvider: selectionArgs: 1002
07-12 11:36:34.814   924   941 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-12 11:36:34.814   924   941 D SettingsProvider: ret = -1
,07-12 11:36:34.814  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.814  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.814   924   941 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,07-12 11:36:34.814  2898  2955 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-12 11:36:34.814  2898  2955 D BluetoothAdapterService: updateAdapterState state is 12
,07-12 11:36:34.814  6410  6410 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
07-12 11:36:34.814  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.814  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.814   924  1225 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-12 11:36:34.814   924  1225 D ActivityManager: caller:android.app.ApplicationThreadProxy@23ee14a7, r.packageName :com.android.bluetooth
07-12 11:36:34.814  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.814  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.814  6638  6638 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:34.814  6638  6638 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:34.814  2898  2961 D bt_vendor: op for 7
,07-12 11:36:34.814  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.824  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.824  2898  2955 D BluetoothAdapterService: Autoconnection is available 
07-12 11:36:34.824  2898  2907 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:34.824  2898  2955 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-12 11:36:34.824  2898  2955 D BluetoothAdapterService: starting service from this receiver
,07-12 11:36:34.834   924   941 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-12 11:36:34.834   924   941 D ActivityManager: caller:android.app.ApplicationThreadProxy@289d04fd, r.packageName :com.android.bluetooth
,07-12 11:36:34.834  2898  2955 I BluetoothAdapterState: Entering On State from state = 11
,07-12 11:36:34.834  3072  3092 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:36:34.834   924  1057 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:34.834  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-12 11:36:34.834  6410  6410 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:34.834  2898  2898 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-12 11:36:34.844   924  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-12 11:36:34.844   924   924 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-12 11:36:34.844   924   924 I InputMethodManagerService: [BT Setting State] State =12
07-12 11:36:34.844   924   924 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-12 11:36:34.844  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.844  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.844  1406  1406 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@4c97568, true
07-12 11:36:34.844  1406  1406 D BluetoothHeadset: registerMessageListener
07-12 11:36:34.844  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.844  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.844  2898  2907 D HeadsetService: registerMessageListener
07-12 11:36:34.844  1766  1766 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-12 11:36:34.844  2898  2907 D HeadsetService: registerMessageListener
07-12 11:36:34.844  2898  6586 D HeadsetStateMachine: Disconnected process message: 70
07-12 11:36:34.844  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.844  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.844  2898  6586 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3d4e5a75
07-12 11:36:34.844  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-12 11:36:34.844  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-12 11:36:34.844  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,07-12 11:36:34.854  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.854  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.854  2898  2898 I BluetoothPbapService: Handler(): got msg=1
07-12 11:36:34.854  2898  6586 D HeadsetStateMachine: Disconnected process message: 9
07-12 11:36:34.854  2898  6586 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-12 11:36:34.854  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.854  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.854  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-12 11:36:34.854  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:36:34.854   924   941 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-12 11:36:34.854  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.854  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.854  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.854  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.854   324  1548 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-12 11:36:34.854   324  1548 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-12 11:36:34.854   324  1548 V voice   : voice_set_parameters: exit with code(-2)
07-12 11:36:34.854   324  1548 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-12 11:36:34.854   324  1548 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-12 11:36:34.854   324  1548 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-12 11:36:34.854   324  1548 V audio_hw_primary: adev_set_parameters: exit
07-12 11:36:34.854  2898  6586 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-12 11:36:34.854  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.854  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.864  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.864  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.864   924  1057 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-12 11:36:34.864  2898  6655 V BluetoothPbapService: PBAP Service initSocket try: 0
07-12 11:36:34.864  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.864  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.864   924  1225 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-12 11:36:34.864  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.864  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.864   924  1240 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-12 11:36:34.864  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.864  2898  2961 D bt_upio : BT_WAKE is asserted already
,07-12 11:36:34.864  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-12 11:36:34.864  2898  6655 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:34.864  2898  6655 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-12 11:36:34.864  2898  6655 D BluetoothSocket: bindListen(), new LocalSocket 
07-12 11:36:34.864  2898  6655 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-12 11:36:34.864  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.864  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.864  2898  6655 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d5c0cd6
07-12 11:36:34.864  2898  6655 D BluetoothSocket: channel: 19
07-12 11:36:34.864  2898  6655 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-12 11:36:34.874  1189  1617 D BluetoothTile:  handleUpdatestate:false name:null
07-12 11:36:34.874  1189  1617 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-12 11:36:34.874  6622  6622 D BadgeProvider: onCreate
,07-12 11:36:34.874  6622  6622 D BadgeProvider: DatabaseHelper
,07-12 11:36:34.874  2898  6656 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-12 11:36:34.874  6638  6638 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-12 11:36:34.884  2898  6656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-12 11:36:34.884  6622  6630 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D QSpanel : label top:23
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:36:34.884  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:36:34.894  2898  2961 D bt_vendor: op for 7
07-12 11:36:34.894  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:34.894  2898  6656 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-12 11:36:34.894  2898  6656 D BluetoothSocket: bindListen(), new LocalSocket 
07-12 11:36:34.894  2898  6656 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-12 11:36:34.894  2898  6656 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f9edb57
07-12 11:36:34.894  2898  6656 D BluetoothSocket: channel: 5
,07-12 11:36:34.894  6622  6644 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,07-12 11:36:34.894  1459  1459 D Launcher.Model: reloadBadges entered.
07-12 11:36:34.894  6622  6644 D BadgeProvider: sendNotify, [notify] : null
07-12 11:36:34.894  6622  6644 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-12 11:36:34.894  6622  6644 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-12 11:36:34.894  6622  6644 D BadgeProvider: update, [UpdateCount] : 1
,07-12 11:36:34.924  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-12 11:36:34.944  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-12 11:36:34.944  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-12 11:36:34.944   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6593
07-12 11:36:34.944   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-12 11:36:34.944  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:36:34.944  6593  6593 I wpa_supplicant: ssSupport state is = 1
,07-12 11:36:34.944  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:34.954  6593  6593 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:36:34.954  6593  6593 E wpa_supplicant: SIM READ ERROR
07-12 11:36:34.954  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:34.954  6593  6593 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:36:34.954  6593  6593 E wpa_supplicant: SIM READ ERROR
07-12 11:36:34.954  6593  6593 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:36:34.954  6593  6593 I wpa_supplicant: wpa_default_ap_write_once
07-12 11:36:34.954  6593  6593 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-12 11:36:34.954  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:34.954  6593  6593 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-12 11:36:34.954  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:34.954  6593  6593 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:36:34.954  6593  6593 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:35.054   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:35.074   924  1660 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.File.exists(File.java:363)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164   924  1686 D ActivityManager: startProcessLocked calleePkgName: tv.peel.samsung.app, hostingType: broadcast
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=161 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.k.c(PG:583)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:35.164  6638  6638 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.io.File.exists(File.java:363)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:36:35.164  6638  6638 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:36:35.164   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:35.164   924  1686 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:35.194  6638  6658 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 11:36:35.204  6668  6668 E Zygote  : MountEmulatedStorage()
07-12 11:36:35.204  6668  6668 E Zygote  : v2
07-12 11:36:35.204  6668  6668 I libpersona: KNOX_SDCARD checking this for 10152
07-12 11:36:35.204  6668  6668 I libpersona: KNOX_SDCARD not a persona
07-12 11:36:35.204   924  1686 I ActivityManager: Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6668 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
07-12 11:36:35.204   924  1686 I ActivityManager: Killing 5350:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,07-12 11:36:35.244  6668  6668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:35.244  6668  6668 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:35.244  6668  6668 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:35.274  6668  6668 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:35.274  6668  6668 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:35.284  6668  6668 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-12 11:36:35.294  1480  1505 I art     : Explicit concurrent mark sweep GC freed 16276(980KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 19MB/32MB, paused 500us total 30.098ms
,07-12 11:36:35.354  6668  6668 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-12 11:36:35.354  6668  6668 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-12 11:36:35.364  6668  6668 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9815-9818)
,07-12 11:36:35.364  6668  6668 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:35.394  6668  6668 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8cdf125}
,07-12 11:36:35.394  6668  6668 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:35.394  6668  6668 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:35.414  6668  6668 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:35.414  6668  6668 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:35.424  6668  6668 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:36:35.644  6593  6593 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-12 11:36:35.644   924  1149 E Tethering: No numeric data
,07-12 11:36:35.644   924  1149 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-12 11:36:35.654  6668  6684 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-12 11:36:35.654   924  1143 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 11:36:35.654  1189  1189 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-12 11:36:35.654  1189  1189 D HotspotTile: updateTetherState():false, false
,07-12 11:36:35.654   924  1143 D NtpTrustedTime: forceRefresh Fail.
,07-12 11:36:35.654   924  1143 V NetworkStats: performPollLocked(flags=0x1)
,07-12 11:36:35.654   924  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-12 11:36:35.654  6668  6668 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-12 11:36:35.654  6668  6668 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
07-12 11:36:35.654   924  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:35.654  6668  6668 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,07-12 11:36:35.654   924  1143 V NetworkStats: performPollLocked() took 3ms
,07-12 11:36:35.654   924  1144 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 11:36:35.654   924  1144 D NtpTrustedTime: forceRefresh Fail.
,07-12 11:36:35.664  6668  6668 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-12 11:36:35.664  6668  6668 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-12 11:36:35.664  6668  6668 I Adreno-EGL: Build Date: 11/19/14 Wed
07-12 11:36:35.664  6668  6668 I Adreno-EGL: Local Branch: mybranch5813579
07-12 11:36:35.664  6668  6668 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-12 11:36:35.664  6668  6668 I Adreno-EGL: Local Patches: NONE
07-12 11:36:35.664  6668  6668 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-12 11:36:35.694  6593  6593 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-12 11:36:35.694  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-12 11:36:35.694  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-12 11:36:35.694   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6593
07-12 11:36:35.694   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,07-12 11:36:35.694  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:36:35.694  6593  6593 I wpa_supplicant: ssSupport state is = 1
,07-12 11:36:35.704  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-12 11:36:35.704  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-12 11:36:35.704   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6593
07-12 11:36:35.704   424   424 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,07-12 11:36:35.704  6593  6593 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-12 11:36:35.704  6593  6593 I wpa_supplicant: ssSupport state is = 1
07-12 11:36:35.704  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:35.704  6593  6593 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-12 11:36:35.704  6593  6593 E wpa_supplicant: SIM READ ERROR
07-12 11:36:35.704  6593  6593 I wpa_supplicant: wpa_default_ap_write_once
07-12 11:36:35.704  6593  6593 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-12 11:36:35.704  6593  6593 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-12 11:36:35.754  6593  6593 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-12 11:36:35.754  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-12 11:36:35.764  6668  6695 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-12 11:36:35.794  6668  6668 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:35.804  6668  6668 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:36:35.814  6593  6593 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-12 11:36:35.814  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-12 11:36:35.814  6593  6593 I wpa_supplicant: Skip scan - bUseNetwork false
,07-12 11:36:35.814   924  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-12 11:36:35.814   924  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-12 11:36:35.814  6593  6593 I wpa_supplicant: HOTSPOT20_ENABLE called
07-12 11:36:35.814  6593  6593 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-12 11:36:35.814  6593  6593 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-12 11:36:35.814  6593  6593 E wpa_supplicant: SIM READ ERROR
07-12 11:36:35.814  6593  6593 I wpa_supplicant: Blacklist: Clear (all) 
,07-12 11:36:35.824  6593  6593 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-12 11:36:35.834  6593  6593 I wpa_supplicant: Skip scan - bUseNetwork false
,07-12 11:36:35.834   924  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-12 11:36:35.834  4145  4145 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:35.834   924   924 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:35.844   924  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-12 11:36:35.844  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:36:35.844  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:35.844   924  1146 D WifiConfigStore: Loading config and enabling all networks 
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: applyOpen
07-12 11:36:35.844  6410  6410 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:35.844  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:35.844  1189  1189 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:35.844  1189  1189 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-12 11:36:35.844  1189  1617 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-12 11:36:35.844  1189  1189 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-12 11:36:35.844  1189  1189 D HotspotTile: onReceive : 3, 0
,07-12 11:36:35.854   924  1146 E WifiConfigStore: Not a HS20
,07-12 11:36:35.864   924  1146 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-12 11:36:35.864   924  1146 D WifiNative-HAL: callSECApiInt - ID [65]
,07-12 11:36:35.874  1189  1189 D QSpanel : label top:23
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
,07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:36:35.874  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:36:35.874   924  1146 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-12 11:36:35.874  6593  6593 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-12 11:36:35.874  6593  6593 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-12 11:36:35.874  6593  6593 I wpa_supplicant: reset timer : RESET_TIMER 0
07-12 11:36:35.874  6593  6593 I wpa_supplicant: P2P: Current p2p state = IDLE
07-12 11:36:35.874  6593  6593 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-12 11:36:35.874  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-12 11:36:35.874  6593  6593 I wpa_supplicant: First Scan Start
,07-12 11:36:35.874  6593  6593 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:36:35.874   924  1146 D WifiNative-HAL: Setting external_sim to 1
,07-12 11:36:35.874   924  1146 D WifiStateMachine: Setting OUI to DA-A1-19
07-12 11:36:35.874   924  1146 I WifiNative-HAL: startHal
07-12 11:36:35.884   924  1146 E wifi    : getStaticLongField sWifiHalHandle 0x935a686c
07-12 11:36:35.884   924  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xb018b6
07-12 11:36:35.884   924  1146 I WifiNative-HAL: Could not start hal
,07-12 11:36:35.884   924  1146 E native  : do suspend true
,07-12 11:36:35.884   924  1145 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-12 11:36:35.884   924  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-12 11:36:35.884   924   924 D WifiScanningService: SCAN_AVAILABLE : 3
07-12 11:36:35.884   924   924 D RttService: SCAN_AVAILABLE : 3
07-12 11:36:35.894   924  1164 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:35.894   924  1164 I WifiNative-HAL: startHal
07-12 11:36:35.894   924  1164 E wifi    : getStaticLongField sWifiHalHandle 0x9c4ce99c
07-12 11:36:35.894   924  1164 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x40144a
07-12 11:36:35.894   924  1164 I WifiNative-HAL: Could not start hal
07-12 11:36:35.894   924  1164 E WifiScanningService: could not start HAL
,07-12 11:36:35.894   924  1165 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 11:36:35.894   308  1053 D CommandListener: Setting iface cfg
07-12 11:36:35.894   308  1053 D CommandListener: Trying to bring up p2p0
07-12 11:36:35.894   924  1145 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 11:36:35.894   924  1145 D WifiP2pService: P2pEnablingState
,07-12 11:36:35.894   924  1146 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-12 11:36:35.894   924  1145 D WifiP2pService: P2pEnablingState{ what=147457 }
07-12 11:36:35.894   924  1146 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-12 11:36:35.894   924  1145 D WifiP2pService: P2p socket connection successful
,07-12 11:36:35.894   924  1146 E WifiNative-HAL: invaild command id : 215
07-12 11:36:35.894   924  1145 D WifiP2pService: P2pEnabledState
,07-12 11:36:35.894   924  1145 D WifiP2pService: sending p2p connection changed broadcast: IDLE
,07-12 11:36:35.894   924  1058 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-12 11:36:35.894   924  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-12 11:36:35.894   924  1058 D WifiDisplayController: disconnect
07-12 11:36:35.894   924  1058 D WifiDisplayController: updateConnection
07-12 11:36:35.894   924  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-12 11:36:35.894   924  1058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:36:35.894   924   924 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-12 11:36:35.894  1189  1189 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-12 11:36:35.894   924  1240 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-12 11:36:35.894  1189  1189 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-12 11:36:35.904   924  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:35.904   924  1145 D WifiP2pService: create mNetworkAgent
,07-12 11:36:35.914   924  1145 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-12 11:36:35.914   924  1148 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:36:35.914   924  1148 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-12 11:36:35.914   924  1148 E ConnectivityService: updateNetworkInfo()
07-12 11:36:35.914   924  1148 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:35.914   924  1148 D ConnectivityService: NetworkAgent connected
,07-12 11:36:35.914   924  1148 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,07-12 11:36:35.924  6593  6593 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-12 11:36:35.954  6593  6593 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-12 11:36:35.954  4983  4983 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-12 11:36:35.954   924  1145 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 11:36:35.954   924  1145 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-12 11:36:35.964   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:35.964   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:35.964   924  1145 D WifiP2pService: DeviceAddress: ea:fd:2b
07-12 11:36:35.964   924  1058 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-12 11:36:35.964   924  1058 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-12 11:36:35.964   924  1058 D WifiDisplayController:  primary type: 10-0050F204-5
07-12 11:36:35.964   924  1058 D WifiDisplayController:  secondary type: null
07-12 11:36:35.964   924  1058 D WifiDisplayController:  wps: 0
07-12 11:36:35.964   924  1058 D WifiDisplayController:  grpcapab: 0
07-12 11:36:35.964   924  1058 D WifiDisplayController:  devcapab: 0
07-12 11:36:35.964   924  1058 D WifiDisplayController:  status: 3
07-12 11:36:35.964   924  1058 D WifiDisplayController:  wfdInfo: null
07-12 11:36:35.964   924  1058 D WifiDisplayController:  groupownerAddress: null
07-12 11:36:35.964   924  1058 D WifiDisplayController:  GOdeviceName: null
07-12 11:36:35.964   924  1058 D WifiDisplayController:  interfaceAddress: 
07-12 11:36:35.964   924  1058 D WifiDisplayController:  SConnectInfo : null
,07-12 11:36:35.964   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:35.964   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:35.974   924  1315 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:35.974  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-12 11:36:35.974  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,07-12 11:36:35.974  6485  6485 D SecurityLogAgent: StateMachine : Current State = 1
,07-12 11:36:35.984   924  1145 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-12 11:36:35.984   924  1145 D WifiP2pService: InactiveState
07-12 11:36:35.984   924  1148 E ConnectivityService: updateNetworkInfo()
07-12 11:36:35.984   924  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
07-12 11:36:35.984   924  1145 D WifiP2pService: InactiveState{ what=143376 }
07-12 11:36:35.984   924  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-12 11:36:35.984  6593  6593 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
07-12 11:36:35.984  6485  6485 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:36:35.984   924  1145 D WifiP2pService: InactiveState{ what=143376 }
07-12 11:36:35.984   924  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-12 11:36:35.984   924  3435 I ActivityManager: Killing 5387:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,07-12 11:36:35.994  4145  4145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-12 11:36:35.994   924  1225 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-12 11:36:35.994   924  1225 D ActivityManager: caller:android.app.ApplicationThreadProxy@26aa9c26, r.packageName :com.android.settings
,07-12 11:36:36.004  1578  1578 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 11:36:36.024  4145  4145 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:36:36.024   924  1686 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-12 11:36:36.034  4145  4145 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:36:36.034  4145  4145 E BluetoothHeadset: BTStateChangeCB is registed
,07-12 11:36:36.034   924  1660 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-12 11:36:36.034  4145  4145 E BluetoothHeadset: BluetoothHeadset service is binded
,07-12 11:36:36.054  4145  4145 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,07-12 11:36:36.054   924   940 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-12 11:36:36.054  4145  4145 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-12 11:36:36.054   924   941 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-12 11:36:36.054   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-12 11:36:36.064   924  1686 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-12 11:36:36.064  4145  4145 D LocalBluetoothProfileManager: PANU : true
07-12 11:36:36.064  4145  4145 D LocalBluetoothProfileManager: Adding local MAP profile
,07-12 11:36:36.064  4145  4145 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:36:36.064   924  1240 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-12 11:36:36.064   924  1315 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-12 11:36:36.064  4145  4145 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
07-12 11:36:36.064  4145  4145 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 11:36:36.074  4145  4145 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:36:36.074  4145  4145 D BluetoothNotiBroadcastReceiver: onReceive
,07-12 11:36:36.074  4145  4145 D BluetoothA2dp: Proxy object connected
,07-12 11:36:36.074  4145  4145 D A2dpProfile: Bluetooth service connected
07-12 11:36:36.074  2898  2898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2bd1c11c
07-12 11:36:36.074  2898  2898 D BtConfig.SecureMode: isSecureModeOn:false
,07-12 11:36:36.074   924  1225 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-12 11:36:36.074   924  1225 D ActivityManager: caller:android.app.ApplicationThreadProxy@252b2586, r.packageName :com.android.bluetooth
,07-12 11:36:36.084  4145  4145 D HeadsetProfile: Bluetooth service connected
,07-12 11:36:36.084  4145  4145 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-12 11:36:36.084  4145  4145 D SapProfile: Bluetooth service connected
07-12 11:36:36.084  4145  4145 D Bluetoothsap: getConnectedDevices()
,07-12 11:36:36.094  4145  4145 D BluetoothInputDevice: Proxy object connected
,07-12 11:36:36.094  4145  4145 D HidProfile: Bluetooth service connected
07-12 11:36:36.094  4983  4983 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-12 11:36:36.094   924  1240 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:36.094  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:36:36.094  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:36:36.094  6485  6485 D SecurityLogAgent: StateMachine : Current State = 1
07-12 11:36:36.094  6485  6485 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:36:36.104   924  3435 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-12 11:36:36.104   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:36.104   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:36.104   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:36.104   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:36.144  6722  6722 E Zygote  : MountEmulatedStorage()
07-12 11:36:36.144  6722  6722 E Zygote  : v2
07-12 11:36:36.144  6722  6722 I libpersona: KNOX_SDCARD checking this for 10192
07-12 11:36:36.144  6722  6722 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:36.154   924  3435 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6722 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:36.204  6722  6722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:36.204  6722  6722 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:36.204  4145  4145 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:36:36.204  6722  6722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 11:36:36.204  4145  4145 D PanProfile: Bluetooth service connected
,07-12 11:36:36.204  4145  4145 D BluetoothMap: Proxy object connected
,07-12 11:36:36.204  4145  4145 D MapProfile: Bluetooth service connected
07-12 11:36:36.204  4145  4145 D BluetoothPbap: Proxy object connected
,07-12 11:36:36.204  4145  4145 D PbapServerProfile: Bluetooth service connected
,07-12 11:36:36.214   924  1660 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-12 11:36:36.224  2898  6733 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:36:36.224  6722  6722 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:36.224  6722  6722 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:36.224  2898  6733 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-12 11:36:36.224  2898  6733 D BluetoothSocket: bindListen(), new LocalSocket 
07-12 11:36:36.224  2898  6733 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-12 11:36:36.224  2898  6733 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3f10529
,07-12 11:36:36.224  2898  2961 D bt_vendor: op for 7
07-12 11:36:36.224  2898  2961 D bt_upio : BT_WAKE is asserted already
07-12 11:36:36.224  2898  6733 D BluetoothSocket: channel: 12
,07-12 11:36:36.224  2898  6733 I BtOppRfcommListener: Accept thread started.
,07-12 11:36:36.244  6722  6722 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-12 11:36:36.264  6722  6722 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-12 11:36:36.264   924   941 I ActivityManager: Killing 5277:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,07-12 11:36:36.264  4145  4145 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-12 11:36:36.264  4145  4145 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-12 11:36:36.264   924  1584 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.264  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-12 11:36:36.274   924  1225 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:36.274  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,07-12 11:36:36.274  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:36:36.274  4145  4145 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-12 11:36:36.274  4145  4294 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:36:36.274  6538  6538 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-12 11:36:36.284  6722  6722 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-12 11:36:36.284  6722  6722 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-12 11:36:36.284  6722  6722 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
07-12 11:36:36.284  6722  6722 D WifiDirectBR: stopServiceTest : false
,07-12 11:36:36.324   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:36:36.324   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:36:36.324   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:36:36.324   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-12 11:36:36.324   924   940 D BatteryService: stay LED for fully charged
,07-12 11:36:36.324  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:36:36.324  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:36:36.324  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
07-12 11:36:36.324   924   924 I MotionRecognitionService: Plugged
07-12 11:36:36.324  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:36:36.324   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:36:36.324  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-12 11:36:36.324  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:36.324  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:36:36.334  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:36.664  6593  6593 I wpa_supplicant: nl80211: Received scan results (9 BSSes)
,07-12 11:36:36.664  6593  6593 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-12 11:36:36.664  6593  6593 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-12 11:36:36.664  6593  6593 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-12 11:36:36.664  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-12 11:36:36.674   924  1146 I WifiNative-HAL: startHal
,07-12 11:36:36.674   924  1146 E wifi    : getStaticLongField sWifiHalHandle 0x935a688c
07-12 11:36:36.674   924  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x302296
,07-12 11:36:36.674   924  1146 I WifiNative-HAL: Could not start hal
,07-12 11:36:36.694   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:36.694   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:36.744  6593  6593 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-12 11:36:36.744  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-12 11:36:36.754  6593  6593 I wpa_supplicant: Associated with F4.99.3E
07-12 11:36:36.754  6593  6593 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-12 11:36:36.754  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-12 11:36:36.754   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:36.754   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:36.754   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:36.754   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:36.764  6593  6593 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-12 11:36:36.764  6593  6593 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-12 11:36:36.764  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-12 11:36:36.774  6593  6593 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:36:36.774  6593  6593 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-12 11:36:36.774  6593  6593 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
07-12 11:36:36.774  6593  6593 I wpa_supplicant: Blacklist: Clear (temp) 
07-12 11:36:36.774  6593  6593 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-12 11:36:36.774   924  1146 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-12 11:36:36.774   924  1018 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,07-12 11:36:36.774   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:36.774   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:36.774   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:36.774   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:36.784  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-12 11:36:36.784  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:36.784  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-12 11:36:36.784   924  1146 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-12 11:36:36.784   924  1148 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-12 11:36:36.784   924  1148 D ConnectivityService: Got NetworkAgent Messenger
07-12 11:36:36.784   924  1148 E ConnectivityService: updateNetworkInfo()
07-12 11:36:36.784   924  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:36.784   924  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:36:36.784   924  1148 D ConnectivityService: NetworkAgent connected
,07-12 11:36:36.794   924  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:36:36.804  2898  3086 D bt_upio : ..proc_btwrite_timeout..
,07-12 11:36:36.804   308  1053 D CommandListener: Setting iface cfg
,07-12 11:36:36.834   318   318 E SMD     : DCD ON
,07-12 11:36:36.834  6742  6742 E Zygote  : MountEmulatedStorage()
07-12 11:36:36.834  6742  6742 E Zygote  : v2
,07-12 11:36:36.834  6742  6742 I libpersona: KNOX_SDCARD checking this for 10038
07-12 11:36:36.834  6742  6742 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:36.834   924  1018 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6742 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-12 11:36:36.834   924  1146 E WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:36:36.844   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:36.844   924  1146 D SecContentProvider2: mCursor = null
,07-12 11:36:36.854   924  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:36:36.894  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-12 11:36:36.894  6742  6742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:36.894  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:36.894  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-12 11:36:36.894  6742  6742 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:36.894  6742  6742 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:36.934  6742  6742 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:36.934  6742  6742 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:36.944   924  1146 E native  : do suspend false
,07-12 11:36:36.944   924  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-12 11:36:36.944   924  1145 D WifiP2pService: InactiveState{ what=143375 }
07-12 11:36:36.944   924  1146 D SecContentProvider2: mCursor = null
07-12 11:36:36.944   924  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-12 11:36:36.964  6742  6742 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-12 11:36:36.964  6742  6742 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-12 11:36:37.084  6742  6742 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-12 11:36:37.164  6759  6759 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:36:37.164  6759  6759 I dhcpcd  : version 5.5.6 starting
,07-12 11:36:37.164  6759  6759 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-12 11:36:37.214  6742  6742 E BluetoothHeadset: BTStateChangeCB is registed
07-12 11:36:37.214   924  1447 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-12 11:36:37.214  6742  6742 E BluetoothHeadset: BluetoothHeadset service is binded
,07-12 11:36:37.224   924   941 I ActivityManager: Killing 5809:flipboard.app/u0a125 (adj 15): emptyCount ##41
,07-12 11:36:37.224  6742  6742 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-12 11:36:37.234  4145  4145 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.234  4145  4145 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-12 11:36:37.234   924  1660 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.234  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-12 11:36:37.234   924  1458 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.234  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:36:37.234  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:36:37.234  4145  4145 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-12 11:36:37.234  4145  4294 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:36:37.234  6759  6759 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-12 11:36:37.234  6759  6759 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-12 11:36:37.234  6759  6759 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-12 11:36:37.244  6759  6759 I dhcpcd  : bssid match
,07-12 11:36:37.244  6759  6759 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-12 11:36:37.244   924  1447 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.244  4983  4983 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:37.344  6759  6759 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,07-12 11:36:37.394  6759  6759 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-12 11:36:37.394   924  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:36:37.734  2898  2961 D bt_vendor: op for 7
,07-12 11:36:37.754   924  1146 E native  : do suspend true
,07-12 11:36:37.764   924  1145 D WifiP2pService: InactiveState{ what=143375 }
,07-12 11:36:37.764   924  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-12 11:36:37.764   924  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,07-12 11:36:37.764   924  1146 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-12 11:36:37.764   924  1146 E WifiStateMachine: VerifyingLinkState enter
,07-12 11:36:37.774   924  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-12 11:36:37.774  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-12 11:36:37.774   924  1148 E ConnectivityService: updateNetworkInfo()
,07-12 11:36:37.774  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:37.774  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-12 11:36:37.774   924  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:36:37.774   924  1148 D ConnectivityService: Adding iface wlan0 to network 502
,07-12 11:36:37.774   924  1159 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-12 11:36:37.774   924  1159 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:36:37.774   924  1159 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:36:37.784   924  1159 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:36:37.784   924  1159 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-12 11:36:37.784  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-12 11:36:37.784  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:37.784  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-12 11:36:37.784   924  1146 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-12 11:36:37.794   924   924 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-12 11:36:37.794  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-12 11:36:37.794  1189  1189 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:37.794  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-12 11:36:37.794  4145  4145 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.794   924   924 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-12 11:36:37.794   924   924 I WifiTrafficPoller: mBoosterFLAG : 0
07-12 11:36:37.794   924   924 I WifiTrafficPoller: current booster mode : FullMode
07-12 11:36:37.794   924   924 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-12 11:36:37.794   924  1146 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:37.804  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:37.804  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:37.814  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:37.814  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:37.814   924  1148 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,07-12 11:36:37.814   924  1148 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,07-12 11:36:37.814   924  1148 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,07-12 11:36:37.824  4145  4145 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-12 11:36:37.824   924  1148 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:36:37.824   924  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
,07-12 11:36:37.824   924  1148 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,07-12 11:36:37.824   308  1053 V         : QcRouteController
,07-12 11:36:37.834   924  1595 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.834  4983  4983 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:37.844   308  1053 V         : QcRouteController
,07-12 11:36:37.854  4145  4145 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.854  4145  4145 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-12 11:36:37.854   924  1315 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.854  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-12 11:36:37.854   924  1225 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.864  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
07-12 11:36:37.864  4145  4145 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-12 11:36:37.864  4145  4145 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-12 11:36:37.864  4145  4294 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-12 11:36:37.864   308  1053 V         : QcRouteController
,07-12 11:36:37.864   308  1053 V         : QcRouteController
,07-12 11:36:37.864   924  1240 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.874  4983  4983 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:37.884  4145  4145 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-12 11:36:37.884  4145  4145 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-12 11:36:37.884   308  1053 V         : QcRouteController
,07-12 11:36:37.884   924   941 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-12 11:36:37.894   924  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.894   308  1053 V         : QcRouteController
,07-12 11:36:37.904  4983  4983 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:37.914   265   265 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,07-12 11:36:37.914   308  1053 V         : QcRouteController
,07-12 11:36:37.914   308  1053 V         : QcRouteController
,07-12 11:36:37.924   924  1488 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=924
,07-12 11:36:37.934   308  1053 V         : QcRouteController
,07-12 11:36:37.954   924  1148 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
,07-12 11:36:37.954   924  1148 D ConnectivityService: LTETest block dns file not exists
,07-12 11:36:37.954   924  1148 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-12 11:36:37.954   924  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,07-12 11:36:37.964   924  1148 D ConnectivityService: calling update connectivity
,07-12 11:36:37.964   924  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,07-12 11:36:37.964   924  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-12 11:36:37.964   924  1148 E ConnectivityService: updateNetworkInfo()
07-12 11:36:37.964   924  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-12 11:36:37.964   924  1148 E ConnectivityService: updateNetworkInfo()
07-12 11:36:37.964   924  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:36:37.964   924  1148 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
07-12 11:36:37.964   924  1148 D ConnectivityService: calling update connectivity
07-12 11:36:37.964   924  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,07-12 11:36:37.964   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-12 11:36:37.964   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-12 11:36:37.964   924  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-12 11:36:37.964   924  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.964   924  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:37.964   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,07-12 11:36:37.964   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-12 11:36:37.964   924  6740 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:36:37.964   924  6740 I System.out: (HTTPLog)-Static: isShipBuild true
07-12 11:36:37.964   924  6740 I System.out: (HTTPLog)-Thread-178-406685755: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
07-12 11:36:37.974   924  6740 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-12 11:36:37.974   924  1148 D ConnectivityService: currentScore = 0, newScore = 60
07-12 11:36:37.974   924  1148 D ConnectivityService:    accepting network in place of null
,07-12 11:36:37.974   924  1148 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:37.974  1431  1431 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:37.974   924  1148 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,07-12 11:36:37.984   924  1148 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,07-12 11:36:37.984   924  1148 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,07-12 11:36:37.984   924  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-12 11:36:37.984   924  1148 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:37.984   924  1143 V NetworkStats: updateIfacesLocked()
07-12 11:36:37.984   924   924 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-12 11:36:37.984   924  1144 D NtpTrustedTime: forceRefresh() from cache miss
07-12 11:36:37.984   924  1143 V NetworkStats: performPollLocked(flags=0x1)
07-12 11:36:37.984   924  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-12 11:36:37.984   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:37.984   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:37.984   924  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-12 11:36:37.984   924  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-12 11:36:37.984   924  1149 D Tethering: MasterInitialState.processMessage what=3
,07-12 11:36:37.984   924  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-12 11:36:37.984   924  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.984   924  1447 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:37.984   924   941 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:37.984  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:36:37.984  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-12 11:36:37.984  1189  1189 D StatusBar.NetworkController: updateDataNetType()
,07-12 11:36:37.984   924  1143 V NetworkStats: performPollLocked() took 4ms
,07-12 11:36:37.994   924  1148 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-12 11:36:37.994   924  1144 D NtpTrustedTime: forceRefresh Fail.
,07-12 11:36:37.994  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-12 11:36:37.994  1189  1189 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-12 11:36:37.994   924  1144 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 11:36:37.994   924  1144 D NtpTrustedTime: forceRefresh Fail.
,07-12 11:36:37.994   924  1057 D EntConnectivity: Not allowed due to - mEnabled false
,07-12 11:36:37.994   924  1144 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-12 11:36:37.994   924  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
07-12 11:36:37.994   924  1148 D ConnectivityService: calling update connectivity
,07-12 11:36:37.994   924  3435 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:36:37.994   924  3435 D SecContentProvider2: mCursor = null
07-12 11:36:37.994   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:36:37.994   924  1240 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-12 11:36:37.994   924  1240 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-12 11:36:37.994   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:36:37.994   924  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:37.994  1189  1189 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-12 11:36:37.994  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
,07-12 11:36:38.004  1189  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:38.004  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:36:38.004  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:36:38.004  1189  1189 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-12 11:36:38.004  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-12 11:36:38.004  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-12 11:36:38.004  1189  1189 I PhoneStatusBar: Icon Only
07-12 11:36:38.004  1189  1189 I StatusBar: Icon Only
,07-12 11:36:38.004  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:36:38.004  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:36:38.054   924  6740 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-12 11:36:38.104   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:36:38 GMT], X-Android-Received-Millis=[1468316198122], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1468316198097]}
,07-12 11:36:38.104   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-12 11:36:38.104   924  6740 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-12 11:36:38.104   924  1148 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
07-12 11:36:38.104   924  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:36:38.104   924  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:36:38.114   924  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:38.114   924  1148 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-12 11:36:38.114   924  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,07-12 11:36:38.114   924  1148 D ConnectivityService: calling update connectivity
07-12 11:36:38.114   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:38.114   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:36:38.114   924  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:38.114   924  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-12 11:36:38.114  1189  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-12 11:36:38.114   924   941 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: updateDataNetType()
,07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-12 11:36:38.114  1189  1189 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-12 11:36:38.114   924  3435 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:36:38.114   924  3435 D SecContentProvider2: mCursor = null
,07-12 11:36:38.114   924  1240 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-12 11:36:38.114   924  1240 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-12 11:36:38.114  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:36:38.114  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:36:38.124  1189  1189 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-12 11:36:38.124  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-12 11:36:38.124  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-12 11:36:38.124  1189  1189 I PhoneStatusBar: Icon Only
07-12 11:36:38.124  1189  1189 I StatusBar: Icon Only
,07-12 11:36:38.124  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:36:38.124  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:36:38.484   924  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:38.494   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:38.494   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.494   924  1014 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:38.494   924   924 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:36:38.494   924   924 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-12 11:36:38.494   924   924 D SmartBondingService: SmartBondingReceiver: wifi ap is changed, init speed ratio
07-12 11:36:38.494   924   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:38.494   924  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-12 11:36:38.494   924  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-12 11:36:38.494   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:38.494   924  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-12 11:36:38.494   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:38.494   924  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-12 11:36:38.504   924  1488 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.504   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.504   924  1401 D NtpTrustedTime: forceRefresh() from cache miss
07-12 11:36:38.504   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.504   924   941 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:38.504   924   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:36:38.504  6410  6410 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 11:36:38.504  6410  6410 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:36:38.504   924  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.514   924  1401 D NtpTrustedTime: forceRefresh Fail.
,07-12 11:36:38.514   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:36:38.514   924  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.514   924  1488 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:38.514   924   940 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.514   924  1521 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.524  6013  6013 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-12 11:36:38.524  6013  6013 I PCWCLIENTTRACE_PushUtil: sales region : global
07-12 11:36:38.524  6013  6013 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-12 11:36:38.524  6013  6013 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:38.524   924  1660 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-12 11:36:38.524   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:38.524   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:38.524   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:38.524   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:38.524   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.534   924  1014 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.534   924  1014 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.534   924  2963 D SSRM:n  : SIOP:: AP = 400, PST = 390, CUR = 450
,07-12 11:36:38.534   924  1240 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:38.564  6823  6823 E Zygote  : MountEmulatedStorage()
,07-12 11:36:38.564  6823  6823 E Zygote  : v2
07-12 11:36:38.564  6823  6823 I libpersona: KNOX_SDCARD checking this for 10144
07-12 11:36:38.564  6823  6823 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:38.574   924  1660 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6823 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:38.604  6823  6823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:38.604  6823  6823 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:38.604  6823  6823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:38.604   924  1014 E GpsLocationProvider: No APN found to select.
,07-12 11:36:38.624  6823  6823 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:38.624  6823  6823 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:38.634  6823  6823 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-12 11:36:38.744  6823  6823 I MusicStore: Database version: 108
,07-12 11:36:38.764   924  1713 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:38.814  6823  6823 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-12 11:36:38.824  6823  6823 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-12 11:36:38.824  6823  6823 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 11:36:38.844  6823  6823 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-12 11:36:38.904  6823  6823 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:36:38.904  6823  6823 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b8bc7c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-12 11:36:38.904  6823  6823 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-12 11:36:38.904  6823  6823 D AndroidMusic: GMSCore installation verified
,07-12 11:36:38.914   924  1447 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:38.924  6823  6823 I ConfigStore: Config Database version: 1
,07-12 11:36:38.954   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-12 11:36:38.954   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:38.954  6823  6823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-12 11:36:38.964   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-12 11:36:38.964   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:38.964  6823  6823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-12 11:36:38.964   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-12 11:36:38.964   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:38.964  6823  6823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-12 11:36:38.964  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:36:38.964  6410  6484 I jxcore-log: 
,07-12 11:36:38.974   924  3435 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-12 11:36:38.974   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@34c4c846, r.packageName :com.google.android.music
,07-12 11:36:38.984   924  1562 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:39.004   924  1225 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:36:39.004   924  1595 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:36:39.014   924  1488 I AudioService: getStreamVolume 3 index 0
,07-12 11:36:39.014  6823  6823 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-12 11:36:39.024  6823  6823 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-12 11:36:39.024   924  1447 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.024  6823  6823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:36:39.054   924  1458 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:39.064   924  1488 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:39.064   924  1584 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:39.074   924  1447 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-12 11:36:39.074   924  1240 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-12 11:36:39.074   924  1660 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:39.074   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.074   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.074   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.074   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.074  6823  6823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:36:39.124  6850  6850 E Zygote  : MountEmulatedStorage()
07-12 11:36:39.124  6850  6850 E Zygote  : v2
07-12 11:36:39.124  6850  6850 I libpersona: KNOX_SDCARD checking this for 10004
07-12 11:36:39.124  6850  6850 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:39.134   924  1240 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6850 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:39.174  6850  6850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:39.174  6850  6850 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:39.174  6850  6850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:39.174   924   941 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-12 11:36:39.184  6823  6823 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-12 11:36:39.184   924  1713 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:39.204  6850  6850 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:39.204  6850  6850 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:39.214   924  1447 I ActivityManager: Killing 5897:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-12 11:36:39.214  6850  6850 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-12 11:36:39.264   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.274   924  1225 I ActivityManager: Killing 4823:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,07-12 11:36:39.274   924  1660 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-12 11:36:39.274   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.274   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.274   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.274   924  1660 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:39.314  6869  6869 E Zygote  : MountEmulatedStorage()
,07-12 11:36:39.314  6869  6869 E Zygote  : v2
07-12 11:36:39.314  6869  6869 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:39.314  6869  6869 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:39.324   924  1660 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-12 11:36:39.344  6869  6869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:39.344  6869  6869 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:39.344  6869  6869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:39.364  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:39.364  6869  6869 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:39.374  6869  6869 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-12 11:36:39.384  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:36:39.384  6410  6484 I jxcore-log: 
,07-12 11:36:39.404  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-12 11:36:39.414  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:36:39.414  6410  6484 I jxcore-log: 
,07-12 11:36:39.414  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:36:39.414  6410  6484 I jxcore-log: 
,07-12 11:36:39.424  6869  6869 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-12 11:36:39.434  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:36:39.434  6410  6484 I jxcore-log: 
,07-12 11:36:39.434  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:36:39.434  6410  6484 I jxcore-log: 
,07-12 11:36:39.534  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-12 11:36:39.544  6869  6869 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-12 11:36:39.544  6869  6869 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:39.544  6869  6869 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-12 11:36:39.604   924  1584 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-12 11:36:39.604   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.604   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.604   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.604   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:39.644  6885  6885 E Zygote  : MountEmulatedStorage()
07-12 11:36:39.644  6885  6885 E Zygote  : v2
07-12 11:36:39.644  6885  6885 I libpersona: KNOX_SDCARD checking this for 10014
07-12 11:36:39.644  6885  6885 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:39.654   924  1584 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6885 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:39.664   351   351 I art     : Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 302us total 13ms
,07-12 11:36:39.674   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 268us total 9.408ms
,07-12 11:36:39.684  6885  6885 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:39.684  6885  6885 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:39.684  6885  6885 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-12 11:36:39.684   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 265us total 10.532ms
,07-12 11:36:39.704  6885  6885 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:39.704  6885  6885 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:39.714  6885  6885 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-12 11:36:39.764   924   941 I ActivityManager: Killing 5947:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-12 11:36:39.764  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-12 11:36:39.774  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-12 11:36:39.794  6885  6885 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-12 11:36:39.804   924  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.824   924  1488 I ActivityManager: Killing 5972:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-12 11:36:39.834   924   940 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 11:36:39.834   924   940 D ActivityManager: caller:android.app.ApplicationThreadProxy@348b0f01, r.packageName :com.google.android.gms
,07-12 11:36:39.834   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.834   924  1447 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.834   924  1225 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.834   318   318 E SMD     : DCD ON
,07-12 11:36:39.834   924  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.834  1740  1740 I iu.Environment: update battery state; isPlugged? true*
,07-12 11:36:39.844  1740  1740 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,07-12 11:36:39.854   924  1660 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.854   924   940 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.854  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:36:39.854   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.864   924  1447 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.864  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,07-12 11:36:39.874   924  3435 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:36:39.874   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@198de1a6, r.packageName :com.google.android.gms
,07-12 11:36:39.884  1740  1740 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,07-12 11:36:39.884  1740  1740 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-12 11:36:39.884  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 11:36:39.894  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-12 11:36:39.894  3975  3975 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-12 11:36:39.894   924  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.894  3975  3975 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1468316199913
,07-12 11:36:39.904  3975  3975 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-12 11:36:39.904   924  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.904   924  1240 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.904  3975  3975 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-12 11:36:39.904  3975  3975 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-12 11:36:39.904  3975  3975 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-12 11:36:39.914  3975  3975 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-12 11:36:39.914   924  3435 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-12 11:36:39.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:39.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:39.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:39.964  1578  6903 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-12 11:36:39.984   924  1225 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.984   924  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:39.994   924  1315 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.004  6909  6909 E Zygote  : MountEmulatedStorage()
,07-12 11:36:40.004  6909  6909 E Zygote  : v2
07-12 11:36:40.004  6909  6909 I libpersona: KNOX_SDCARD checking this for 10036
07-12 11:36:40.004  6909  6909 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:40.014   924  3435 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6909 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:36:40.054  6909  6909 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:40.054  6909  6909 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:40.054  6909  6909 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:40.074   924  3435 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 11:36:40.074   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fd77f94, r.packageName :com.google.android.gms
,07-12 11:36:40.074  6909  6909 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:40.074  6909  6909 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:40.094   924   941 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-12 11:36:40.094   924   941 D ActivityManager: caller:android.app.ApplicationThreadProxy@9a67232, r.packageName :com.google.android.gms
,07-12 11:36:40.104  1578  6908 D GCM     : Connected
,07-12 11:36:40.104   924  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.104  6909  6909 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-12 11:36:40.104   924  1562 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.104   924  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.104   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.114  6909  6909 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:36:40.114  6909  6909 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-12 11:36:40.124   924  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.124  1578  6908 D GCM     : Message class com.google.f.a.a.p
,07-12 11:36:40.124   924  1447 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.134   924  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.134   924  1315 D ActivityManager: bindService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms, action: null
,07-12 11:36:40.134  1578  1578 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:36:40.154  6909  6909 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-12 11:36:40.174   924  1595 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.174   924  1595 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-12 11:36:40.174   924  1595 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.174   924  1595 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.174   924  1595 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.174   924  1595 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:40.214  6927  6927 E Zygote  : MountEmulatedStorage()
,07-12 11:36:40.214  6927  6927 E Zygote  : v2
07-12 11:36:40.214  6927  6927 I libpersona: KNOX_SDCARD checking this for 10042
07-12 11:36:40.214  6927  6927 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:40.224   924  1595 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6927 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-12 11:36:40.274  6927  6927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:40.274  6927  6927 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:40.274  6927  6927 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:40.274   924  1240 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-12 11:36:40.274   924  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@266688d7, r.packageName :com.samsung.android.app.galaxyfinder
,07-12 11:36:40.304  6927  6927 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:40.304  6927  6927 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:40.304   924  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.324  6927  6927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-12 11:36:40.344  6927  6927 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-12 11:36:40.364   924  1562 I ActivityManager: Killing 5995:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-12 11:36:40.374   924  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.374  3303  6946 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-12 11:36:40.374  3303  6946 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-12 11:36:40.374  3303  6946 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-12 11:36:40.374  5187  5187 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-12 11:36:40.384  3303  6946 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,07-12 11:36:40.384  3303  6946 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,07-12 11:36:40.384  3303  3472 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,07-12 11:36:40.384  3303  3472 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,07-12 11:36:40.384   924  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.384  3303  3472 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-12 11:36:40.384  6083  6083 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-12 11:36:40.384  6083  6083 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,07-12 11:36:40.384  6083  6083 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-12 11:36:40.384  6083  6083 I SA      : [SLFUCHKMGR] constructor called
,07-12 11:36:40.394  3303  3472 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 9
,07-12 11:36:40.394  3303  3472 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 9
,07-12 11:36:40.394  6083  6083 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-12 11:36:40.394  6083  6083 I SA      : [OR] == isSIMCardReady false ==
,07-12 11:36:40.394  3303  3472 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 9
07-12 11:36:40.394   924  1584 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:40.394  6083  6083 I SA      : [SCU] == networkStateCheck == true
,07-12 11:36:40.404  6083  6083 I SA      : [DM] getCountryCodeFromCSC : PL
07-12 11:36:40.404  6083  6083 I SA      : isChinaCountryCode : false
,07-12 11:36:40.404  6083  6083 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-12 11:36:40.404  6083  6083 I SA      : [OR] == networkStateCheck true ==
,07-12 11:36:40.404  6083  6083 I SA      : [OR] GetMyCountryZoneTask
,07-12 11:36:40.404  6083  6083 I SA      : [OR] onReceive END
,07-12 11:36:40.414   924   941 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.414   924   940 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-12 11:36:40.414   924   940 D ActivityManager: caller:android.app.ApplicationThreadProxy@8498cad, r.packageName :com.android.providers.downloads
,07-12 11:36:40.414   924  1240 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-12 11:36:40.414   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.414   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.414   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.414   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:40.414  6083  6949 I SA      : [SRS] prepareGetMyCountryZone
,07-12 11:36:40.424  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,07-12 11:36:40.434  6083  6949 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-12 11:36:40.434  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,07-12 11:36:40.434  6083  6949 I SA      : [SSP] query invoked
,07-12 11:36:40.434  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,07-12 11:36:40.444  3303  3473 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,07-12 11:36:40.444   924  1584 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.444  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
07-12 11:36:40.444  3303  3473 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-12 11:36:40.444  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,07-12 11:36:40.444  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,07-12 11:36:40.454  6953  6953 E Zygote  : MountEmulatedStorage()
07-12 11:36:40.454  6953  6953 E Zygote  : v2
07-12 11:36:40.454  6953  6953 I libpersona: KNOX_SDCARD checking this for 10074
07-12 11:36:40.454  6953  6953 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,07-12 11:36:40.464  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,07-12 11:36:40.474  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/07/15/11:03:49
,07-12 11:36:40.474   924  1240 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=6953 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-12 11:36:40.474  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/07/12/11:36:40
,07-12 11:36:40.484  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
,07-12 11:36:40.484  3303  3472 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,07-12 11:36:40.484  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,07-12 11:36:40.494  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:40.494  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:40.494  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:40.514  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:40.514  6953  6953 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:40.524  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,07-12 11:36:40.534  3303  3472 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,07-12 11:36:40.544   924  1488 I art     : Explicit concurrent mark sweep GC freed 84676(4MB) AllocSpace objects, 11(176KB) LOS objects, 30% free, 36MB/52MB, paused 1.571ms total 105.387ms
,07-12 11:36:40.564  6083  6949 I SA      : [TPMU] GetMccFromDB : null
,07-12 11:36:40.564  6953  6953 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-12 11:36:40.574  6083  6949 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-12 11:36:40.574  6083  6949 I SA      : [TPM] isNoProxy(default) : true
,07-12 11:36:40.594  6083  6949 E File    : fail readDirectory() errno=2
,07-12 11:36:40.594  3303  3472 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,07-12 11:36:40.594  3303  3472 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,07-12 11:36:40.624  6953  6953 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-12 11:36:40.624  6953  6953 I SCloudBackupReceiver: Other Intent
,07-12 11:36:40.624  5674  5674 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-12 11:36:40.624  5674  5674 I KnoxUsageLogPro: premStatus:2
,07-12 11:36:40.634  5674  5674 I KnoxUsageLogPro: isEulaShown : false
,07-12 11:36:40.634  5674  5674 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-12 11:36:40.644   924  1521 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-12 11:36:40.644   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.644   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.644   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.644   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:40.654  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,07-12 11:36:40.674  3303  3473 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,07-12 11:36:40.684  6971  6971 E Zygote  : MountEmulatedStorage()
07-12 11:36:40.684  6971  6971 E Zygote  : v2
07-12 11:36:40.684  6971  6971 I libpersona: KNOX_SDCARD checking this for 10104
07-12 11:36:40.684  6971  6971 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:40.684   924  1521 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6971 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 11:36:40.684   924  1521 I ActivityManager: Killing 6049:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-12 11:36:40.724  6971  6971 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:40.724  6971  6971 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:40.724  6971  6971 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-12 11:36:40.744  6971  6971 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:40.744  6971  6971 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:40.754  6971  6971 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-12 11:36:40.804  2898  2956 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-12 11:36:40.854   924  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
07-12 11:36:40.854   924   924 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-12 11:36:40.854   924  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-12 11:36:40.854   924   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:40.854   924  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-12 11:36:40.854   924  1148 D ConnectivityService: identical MTU - not setting
07-12 11:36:40.854   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:40.854   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:40.854   924  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-12 11:36:40.854   924  1150 D SmartBondingService: getSBEnabled() enabled =false
07-12 11:36:40.854   924  1148 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
07-12 11:36:40.854   308  1053 V         : QcRouteController
,07-12 11:36:40.874   308  1053 V         : QcRouteController
,07-12 11:36:40.874   924  1148 W NetworkManagementService: route cmd failed: 
07-12 11:36:40.874   924  1148 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-12 11:36:40.874   924  1148 W NetworkManagementService: '
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:36:40.874   924  1148 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:36:40.874   924  1148 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-12 11:36:40.874   924  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:36:40.874   924  1148 D ConnectivityService: calling update connectivity
07-12 11:36:40.874   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:40.874   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:36:40.874   924  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:40.874   924  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
07-12 11:36:40.874   924  1148 D ConnectivityService: calling update connectivity
07-12 11:36:40.874   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:36:40.874   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:36:40.874  1189  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-12 11:36:40.874   924  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:36:40.874  1189  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-12 11:36:40.914   924  3435 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-12 11:36:40.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:40.914   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:40.954  6989  6989 E Zygote  : MountEmulatedStorage()
07-12 11:36:40.954  6989  6989 E Zygote  : v2
07-12 11:36:40.954  6989  6989 I libpersona: KNOX_SDCARD checking this for 10131
07-12 11:36:40.954  6989  6989 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:40.964   924  3435 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6989 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-12 11:36:40.964   924  3435 I ActivityManager: Killing 3779:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-12 11:36:40.994  6989  6989 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:40.994  6989  6989 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:40.994  6989  6989 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:41.014   924  1562 D CountryDetector: No listener is left
,07-12 11:36:41.024  6989  6989 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:41.024  6989  6989 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:41.034  6989  6989 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-12 11:36:41.044  6989  6989 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:36:41.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:41.254  6083  6949 I SA      : [RC New] Execute method=[GET] start
,07-12 11:36:41.254   924  1146 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,07-12 11:36:41.254  6989  7012 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-12 11:36:41.254  6989  7012 I Babel   : MmsConfig.loadMmsSettings
07-12 11:36:41.264  6989  7012 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-12 11:36:41.264  6989  6989 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-12 11:36:41.264  6989  7012 I Babel   : MmsConfig.loadFromDatabase
,07-12 11:36:41.274  6989  7012 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,07-12 11:36:41.274  6989  7012 I Babel   : MmsConfig.loadFromResources
,07-12 11:36:41.274  6989  7012 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-12 11:36:41.274  6989  7012 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-12 11:36:41.284   924  1488 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-12 11:36:41.284  6989  6989 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:36:41.304  6083  6949 I SA      : [RC New] Security=[true]
,07-12 11:36:41.304  6083  6949 I System.out: Thread-1005(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-12 11:36:41.314  6989  6989 I Babel_StickerModule: App launched.
,07-12 11:36:41.314  6989  6989 I Babel_StickerModule: Trying first logged in account.
,07-12 11:36:41.314  6083  6949 I System.out: Thread-1005(ApacheHTTPLog):isShipBuild true
,07-12 11:36:41.314  6083  6949 I System.out: Thread-1005(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-12 11:36:41.314  6989  6989 W Babel_StickerModule: Unable to load, account not configured.
,07-12 11:36:41.314   924  1562 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-12 11:36:41.314   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:41.314   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:41.314   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:41.314   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:41.354  7015  7015 E Zygote  : MountEmulatedStorage()
07-12 11:36:41.354  7015  7015 E Zygote  : v2
07-12 11:36:41.354  7015  7015 I libpersona: KNOX_SDCARD checking this for 10146
07-12 11:36:41.354  7015  7015 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:41.364   924  1562 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7015 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:36:41.404  7015  7015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:41.404  7015  7015 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:41.404  7015  7015 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:41.404   324   324 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-12 11:36:41.404   324   324 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-12 11:36:41.404   324   324 W QCamera2Factory: getCameraInfo: X
,07-12 11:36:41.414   324  1548 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-12 11:36:41.414   324  1548 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-12 11:36:41.414   324  1548 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-12 11:36:41.414   324  1548 W QCamera2Factory: getCameraInfo: X
07-12 11:36:41.414   265   985 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,07-12 11:36:41.414   265  1489 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,07-12 11:36:41.414   924  1660 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=924 (0x0)
,07-12 11:36:41.414   924  1660 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=924, ws=WorkSource{10067}) (elapsedTime=3488)
,07-12 11:36:41.424  7015  7015 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:41.424  7015  7015 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:41.434  6989  6989 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:36:41.444  6989  6989 W AudioCapabilities: Unsupported mime audio/qcelp
,07-12 11:36:41.454  6989  6989 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-12 11:36:41.464  7015  7015 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-12 11:36:41.474  6989  6989 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-12 11:36:41.474  6989  6989 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-12 11:36:41.474  6989  6989 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-12 11:36:41.484  6989  6989 W AudioCapabilities: Unsupported mime audio/x-ima
,07-12 11:36:41.484  6989  6989 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-12 11:36:41.484  6989  6989 W AudioCapabilities: Unsupported mime audio/qcelp
,07-12 11:36:41.484  6989  6989 W AudioCapabilities: Unsupported mime audio/evrc
,07-12 11:36:41.484  6989  6989 W VideoCapabilities: Unsupported mime video/wvc1
,07-12 11:36:41.494  6759  6759 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:36:41.504  6989  6989 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-12 11:36:41.514  6989  6989 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-12 11:36:41.514  6989  6989 W VideoCapabilities: Unsupported mime video/wvc1
,07-12 11:36:41.514  6989  6989 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-12 11:36:41.514  6989  6989 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-12 11:36:41.524  6989  6989 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-12 11:36:41.524  6989  6989 W VideoCapabilities: Unsupported mime video/mp43
,07-12 11:36:41.524  6989  6989 W VideoCapabilities: Unsupported mime video/sorenson
,07-12 11:36:41.544  6989  6989 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-12 11:36:41.554  6989  6989 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-12 11:36:41.584   924   940 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-12 11:36:41.594   924  1488 I ActivityManager: Killing 6110:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-12 11:36:41.634  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:36:41.634  6410  6484 I jxcore-log: 
,07-12 11:36:41.644  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:36:41.644  6410  6484 I jxcore-log: 
,07-12 11:36:41.654  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:36:41.654  6410  6484 I jxcore-log: 
,07-12 11:36:41.694   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-12 11:36:41.694   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:41.694  7015  7034 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-12 11:36:41.694   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-12 11:36:41.694   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:41.694  7015  7034 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-12 11:36:41.704   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-12 11:36:41.704   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:41.704  7015  7036 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-12 11:36:41.714   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-12 11:36:41.714   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
,07-12 11:36:41.714  7015  7036 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-12 11:36:41.754   924   940 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:41.824  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:36:41.824  6410  6484 I jxcore-log: 
,07-12 11:36:41.864  7015  7015 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-12 11:36:41.864  7015  7015 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-12 11:36:41.874  6083  6949 I SA      : [RC New] [v2liruge] api execute + 572
,07-12 11:36:41.874  6083  6949 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,07-12 11:36:41.874  6083  6949 I System.out: AsyncTask #1 calls detatch()
,07-12 11:36:41.884  7015  7015 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6328-6330)
,07-12 11:36:41.884  7015  7015 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:41.884  6083  6949 I SA      : [TPMU] getNetworkMcc : 260
,07-12 11:36:41.884  7015  7015 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14374847}
,07-12 11:36:41.884  7015  7015 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:36:41.884  7015  7015 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:36:41.894  6083  6949 I SA      : [SCU] saveMccToPreferece Start
,07-12 11:36:41.894  6083  6949 I SA      : [SCU] RegionMCC : 260
07-12 11:36:41.894  6083  6949 I SA      : [SSP] query invoked
,07-12 11:36:41.894  6083  6949 I SA      : [TPMU] GetMccFromDB : null
,07-12 11:36:41.894  6083  6949 I SA      : [SCU] getMccFromPreferece mcc = 260
07-12 11:36:41.894  6083  6949 I SA      : [SCU] saveMccToPreferece End
,07-12 11:36:41.894  6083  6949 I SA      : [RC New] executeRequest [v2liruge] end. 647
07-12 11:36:41.894  6083  6949 I SA      : [RC New] Execute end
07-12 11:36:41.904  6083  6083 I SA      : [OR] GetMyCountryZoneTask mcc = 260
07-12 11:36:41.904  6083  6083 I SA      : [OR] GetMyCountryZoneTask Success
,07-12 11:36:41.904  7015  7015 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:36:41.914  7015  7015 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:41.914  7015  7015 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:36:41.924  7015  7015 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-12 11:36:41.924  7015  7015 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-12 11:36:41.924  7015  7015 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-12 11:36:41.934  7015  7015 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-12 11:36:41.934  7015  7015 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-12 11:36:41.934  7015  7015 I Adreno-EGL: Build Date: 11/19/14 Wed
07-12 11:36:41.934  7015  7015 I Adreno-EGL: Local Branch: mybranch5813579
07-12 11:36:41.934  7015  7015 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-12 11:36:41.934  7015  7015 I Adreno-EGL: Local Patches: NONE
07-12 11:36:41.934  7015  7015 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-12 11:36:42.004  7015  7064 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 11:36:42.014  7015  7015 I NSApplication: Starting up...
,07-12 11:36:42.024   924   941 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.024   924  1713 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.024   924  1686 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:42.074   924  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.074   924  1562 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.074   924  1315 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.074   924  1488 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.074   924  1240 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-12 11:36:42.084   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:42.084   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:42.084   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:42.084   924  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:42.124  7071  7071 E Zygote  : MountEmulatedStorage()
,07-12 11:36:42.124  7071  7071 E Zygote  : v2
07-12 11:36:42.124  7071  7071 I libpersona: KNOX_SDCARD checking this for 10158
07-12 11:36:42.124  7071  7071 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:42.124   924  1240 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7071 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-12 11:36:42.124   924  1240 I ActivityManager: Killing 4720:com.samsung.android.sm/1000 (adj 15): emptyCount ##41
,07-12 11:36:42.174  7071  7071 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:42.174  7071  7071 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:42.174  7071  7071 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:42.194  7071  7071 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:42.194  7071  7071 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:42.204  7071  7071 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-12 11:36:42.204  7071  7071 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:36:42.204  7071  7071 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-12 11:36:42.204  7071  7071 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-12 11:36:42.214  7071  7071 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-12 11:36:42.214  7071  7071 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-12 11:36:42.224  7071  7071 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-12 11:36:42.224   924  1713 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.234   924   941 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.234   924  1686 D RCPManagerService: exchangeData() failure , invalid userId
,07-12 11:36:42.234   924  3435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.234  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-12 11:36:42.234  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:36:42.234  6485  6485 D SecurityLogAgent: StateMachine : Current State = 1
07-12 11:36:42.234   924  1447 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.234  6485  6485 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-12 11:36:42.234   924   940 I ActivityManager: Killing 5171:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-12 11:36:42.244   924   940 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-12 11:36:42.244   924   940 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:42.244   924   940 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:42.244   924   940 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:42.244   924   940 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:42.254   924  1315 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.254   924  1488 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.284  7086  7086 E Zygote  : MountEmulatedStorage()
07-12 11:36:42.284  7086  7086 E Zygote  : v2
07-12 11:36:42.284  7086  7086 I libpersona: KNOX_SDCARD checking this for 10200
07-12 11:36:42.284  7086  7086 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:42.294   924   940 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7086 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-12 11:36:42.294   924  1562 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
07-12 11:36:42.294   924  1562 D ActivityManager: caller:android.app.ApplicationThreadProxy@4f83945, r.packageName :com.sec.android.app.SmartClipService
,07-12 11:36:42.334  7086  7086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:36:42.334  7086  7086 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:42.334  7086  7086 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-12 11:36:42.354  7086  7086 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:42.354  7086  7086 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:42.364  7086  7086 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-12 11:36:42.394   924  1488 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.394  6266  6266 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-12 11:36:42.534   924  1458 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-12 11:36:42.534   924  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@f81989a, r.packageName :com.sec.android.app.samsungapps
,07-12 11:36:42.544  6266  6266 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-12 11:36:42.544  6266  6266 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-12 11:36:42.544  6266  6266 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:36:42.544  6266  6266 D InitializeManagerStateMachine: exit::IDLE
07-12 11:36:42.544  6266  6266 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-12 11:36:42.544   924  1521 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.544   924  1713 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: entry::SUCCESS
07-12 11:36:42.554  6266  6266 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-12 11:36:42.554  6266  6266 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,07-12 11:36:42.554  6266  6266 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-12 11:36:42.554  6266  6266 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-12 11:36:42.554   924  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: exit::SUCCESS
07-12 11:36:42.554  6266  6266 D InitializeManagerStateMachine: entry::IDLE
,07-12 11:36:42.584   924   940 I ActivityManager: Killing 6132:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-12 11:36:42.614  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:36:42.614  6410  6484 I jxcore-log: 
,07-12 11:36:42.664  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:36:42.664  6410  6484 I jxcore-log: 
,07-12 11:36:42.674  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:36:42.674  6410  6484 I jxcore-log: 
,07-12 11:36:42.834   318   318 E SMD     : DCD ON
,07-12 11:36:42.874  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:36:42.874  6410  6484 I jxcore-log: 
,07-12 11:36:42.894  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:36:42.894  6410  6484 I jxcore-log: 
,07-12 11:36:42.894  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:36:42.894  6410  6484 I jxcore-log: 
,07-12 11:36:42.904  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:36:42.904  6410  6484 I jxcore-log: 
,07-12 11:36:42.914  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:36:42.914  6410  6484 I jxcore-log: 
,07-12 11:36:42.934  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
07-12 11:36:42.934  6410  6484 I jxcore-log: 
,07-12 11:36:43.024  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
07-12 11:36:43.024  6410  6484 I jxcore-log: 
,07-12 11:36:43.024  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
07-12 11:36:43.024  6410  6484 I jxcore-log: 
,07-12 11:36:43.054  6410  6484 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
07-12 11:36:43.054  6410  6484 I jxcore-log: 
,07-12 11:36:43.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...,
07-12 11:36:43.064  6410  6484 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED,
,07-12 11:36:43.064  6410  6484 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-12 11:36:43.064  6410  6484 I jxcore-log: 
,07-12 11:36:43.104  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
07-12 11:36:43.104  6410  6484 I jxcore-log: 
07-12 11:36:43.114  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
07-12 11:36:43.114  6410  6484 I jxcore-log: 
,07-12 11:36:43.114  6410  6484 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:36:43.114  6410  6484 I jxcore-log: 
,07-12 11:36:43.384   924  1713 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-12 11:36:43.384   924  1713 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b4451a8, r.packageName :com.sec.spp.push
,07-12 11:36:43.404   924  1562 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:43.544  6013  6013 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,07-12 11:36:43.564   924  3435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:36:43.564  6013  7112 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,07-12 11:36:43.614  6013  7112 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
07-12 11:36:43.614  6013  7112 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-12 11:36:43.614  6013  7112 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-12 11:36:43.614  6013  7112 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,07-12 11:36:43.614  6013  7112 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-12 11:36:43.614  6013  7112 I PCWCLIENTTRACE_PushUtil: sales region : global
07-12 11:36:43.614  6013  7112 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,07-12 11:36:43.614  6013  7112 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,07-12 11:36:43.644  3303  3472 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-12 11:36:43.644  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-12 11:36:43.654  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-12 11:36:43.654  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-12 11:36:43.654  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-12 11:36:43.654  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-12 11:36:43.654  3303  3472 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-12 11:36:43.664  3303  3472 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-12 11:36:43.674  3303  3472 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-12 11:36:43.684   924  1686 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:36:43.684  3303  3472 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-12 11:36:44.034   924  1660 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-12 11:36:44.034   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@2850a466, r.packageName :com.google.android.music
,07-12 11:36:44.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:44.074   924   940 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:44.084   924  1315 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:44.084   924  1595 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:44.094   924  1686 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-12 11:36:44.094   924  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@587e5ec, r.packageName :com.google.android.music
,07-12 11:36:44.134   924  1315 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:44.134   924  1315 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:44.134   924  1315 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:44.134   924  1315 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:44.204  7129  7129 E Zygote  : MountEmulatedStorage()
,07-12 11:36:44.204  7129  7129 E Zygote  : v2
,07-12 11:36:44.204  7129  7129 I libpersona: KNOX_SDCARD checking this for 10015
,07-12 11:36:44.214  7129  7129 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:44.224  7129  7129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:44.224  7129  7129 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:36:44.224  7129  7129 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-12 11:36:44.234   924  1315 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7129 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-12 11:36:44.244  6823  7117 I MusicLeanback: Conditions not met for autocaching.
,07-12 11:36:44.244  6823  7117 I MusicLeanback: Stop autocaching.
,07-12 11:36:44.254   924  1595 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-12 11:36:44.274  7129  7129 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:44.274  7129  7129 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:44.304  7129  7129 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-12 11:36:44.304  7129  7129 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-12 11:36:44.304  7129  7129 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-12 11:36:44.344  7129  7129 I MultiDex: VM with version 2.1.0 has multidex support
,07-12 11:36:44.344  7129  7129 I MultiDex: install
07-12 11:36:44.344  7129  7129 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-12 11:36:44.364  7129  7129 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-12 11:36:44.384   924  1595 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 11:36:44.384   924  1595 D ActivityManager: caller:android.app.ApplicationThreadProxy@27bc6497, r.packageName :com.google.android.gms
,07-12 11:36:44.384  1578  4820 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-12 11:36:44.394  1578  1578 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-12 11:36:44.404  1740  1740 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-12 11:36:44.404   924  1595 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:36:44.404   924  1595 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a70684, r.packageName :com.google.android.gms
,07-12 11:36:44.424  7129  7129 D WearableService: callingUid 10015, callindPid: 7129
,07-12 11:36:44.434   924  1686 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d58b333, r.packageName :com.google.android.gms
,07-12 11:36:44.454   924  1315 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:36:44.454   924  1315 D ActivityManager: caller:android.app.ApplicationThreadProxy@15504469, r.packageName :com.google.android.gms
,07-12 11:36:44.454  1740  7150 D LocationInitializer: Restart initialization of location
,07-12 11:36:44.474  1480  2794 E MDM     : [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-12 11:36:44.484   924  1240 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-12 11:36:44.484   924  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a3b4eee, r.packageName :com.google.android.gms
,07-12 11:36:44.494  6823  6823 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-12 11:36:44.494  6823  7146 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-12 11:36:44.924   924  1018 W ProcessCpuTracker: Skipping unknown process pid 7121
,07-12 11:36:44.924   924  1018 W ProcessCpuTracker: Skipping unknown process pid 7122
,07-12 11:36:44.924   924  1018 W ProcessCpuTracker: Skipping unknown process pid 7128
,07-12 11:36:44.924   924  1018 W ProcessCpuTracker: Skipping unknown process pid 7162
,07-12 11:36:45.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:45.504  6759  6759 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:36:45.834   318   318 E SMD     : DCD ON
,07-12 11:36:46.064   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-12 11:36:46.394   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:36:46.404   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:36:46.404   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:36:46.404   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:36:46.414   924   924 I MotionRecognitionService: Plugged
,07-12 11:36:46.414   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:36:46.414  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:36:46.414  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:36:46.414   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:36:46.424  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:36:46.424  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:36:46.424  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:46.424  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:36:46.424  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:36:46.434  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:46.724   924  1488 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-12 11:36:46.744  7015  7035 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:36:48.574   924  2963 D SSRM:n  : SIOP:: AP = 370, PST = 383, CUR = 450,
,07-12 11:36:48.834   318   318 E SMD     : DCD ON
,07-12 11:36:49.504  6759  6759 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-12 11:36:49.504  6759  6759 I dhcpcd  : wlan0: no IPv6 Routers available
,07-12 11:36:49.504   924  1315 I ActivityManager: Killing 6174:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-12 11:36:49.524   924  1521 I ActivityManager: Killing 6202:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-12 11:36:50.884   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:36:51.834   318   318 E SMD     : DCD ON
,07-12 11:36:52.554   924  1521 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-12 11:36:52.554   924  1521 D ActivityManager: caller:android.app.ApplicationThreadProxy@2db317a1, r.packageName :com.sec.android.app.samsungapps
,07-12 11:36:52.574  6266  6266 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-12 11:36:52.584  6266  6266 D PreloadUpdateManagerStateMachine: exit::IDLE
,07-12 11:36:52.584  6266  6266 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:36:52.584  6266  6266 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:86400000
,07-12 11:36:52.584  6266  6266 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-12 11:36:52.584  6266  6266 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-12 11:36:52.594  6266  6266 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-12 11:36:52.594  6266  6266 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-12 11:36:54.314   924  1342 E Watchdog: !@Sync 4
,07-12 11:36:54.834   318   318 E SMD     : DCD ON
,07-12 11:36:56.064   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:56.454   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:36:56.454   924  1488 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:36:56.464   924  1488 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:36:56.464   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:36:56.464   924   924 I MotionRecognitionService: Plugged
,07-12 11:36:56.464  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:36:56.474  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:36:56.474   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:36:56.474  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:56.474   924  1488 D BatteryService: stay LED for fully charged
,07-12 11:36:56.484  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:36:56.484  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:36:56.484  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:56.484  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:36:56.484  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:36:57.074   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:57.704   924  1991 V SAMP_SPCM_test: CSC File load.. 
,07-12 11:36:57.724   924  1991 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,07-12 11:36:57.744   924  1991 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-12 11:36:57.744   924  1991 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-12 11:36:57.754   924  1991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-12 11:36:57.784   924  1991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-12 11:36:57.804   924  1991 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,07-12 11:36:57.804   924  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:57.804   924  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:36:57.804   924  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:57.804   924  1991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:36:57.844   318   318 E SMD     : DCD ON
,07-12 11:36:57.854   924  1991 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-12 11:36:57.864  7184  7184 E Zygote  : MountEmulatedStorage()
,07-12 11:36:57.864  7184  7184 E Zygote  : v2
07-12 11:36:57.864  7184  7184 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:36:57.864  7184  7184 I libpersona: KNOX_SDCARD not a persona
,07-12 11:36:57.874  7184  7184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:36:57.874  7184  7184 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:36:57.874  7184  7184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:36:57.914  7184  7184 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:36:57.914  7184  7184 D ActivityThread: Added TimaKeyStore provider
,07-12 11:36:57.924  7184  7184 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SmartManager_OSUP/SmartManager_OSUP.apk
,07-12 11:36:57.934  7184  7184 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:36:57.974   924   924 I ActivityManager: Killing 6217:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-12 11:36:57.974   924  1991 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-12 11:36:58.074   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:58.634   924  2963 D SSRM:n  : SIOP:: AP = 350, PST = 374, CUR = 450
,07-12 11:36:59.074   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:36:59.994   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:37:00.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:00.844   318   318 E SMD     : DCD ON
,07-12 11:37:01.074   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-12 11:37:02.124   924  1060 I PowerManagerService: [PWL] Off : 105s ago
,07-12 11:37:03.844   318   318 E SMD     : DCD ON
,07-12 11:37:06.514   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:06.524   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:37:06.524   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:37:06.524   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:06.534   924   924 I MotionRecognitionService: Plugged
,07-12 11:37:06.534   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:37:06.534  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:06.534  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:06.534   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:37:06.534  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:37:06.544  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:06.544  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:06.544  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:06.544  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:06.544  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:37:06.844   318   318 E SMD     : DCD ON
,07-12 11:37:08.684   924  2963 D SSRM:n  : SIOP:: AP = 340, PST = 366, CUR = 450
,07-12 11:37:09.844   318   318 E SMD     : DCD ON
,07-12 11:37:10.884   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:12.854   318   318 E SMD     : DCD ON
,07-12 11:37:15.844   318   318 E SMD     : DCD ON
,07-12 11:37:16.074   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:16.574   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:17.074   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:18.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:18.734   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 362, CUR = 450
,07-12 11:37:18.854   318   318 E SMD     : DCD ON
,07-12 11:37:19.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:20.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:21.084   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-12 11:37:21.854   318   318 E SMD     : DCD ON
,07-12 11:37:24.304   924  1342 E Watchdog: !@Sync 5
,07-12 11:37:24.844   318   318 E SMD     : DCD ON
,07-12 11:37:26.634   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:26.644   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:37:26.644   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:37:26.644   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:26.644   924   924 I MotionRecognitionService: Plugged
,07-12 11:37:26.644  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:26.654   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:37:26.654  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:26.654  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:37:26.654  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:26.654   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:37:26.654  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:26.664  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:37:26.664  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:26.664  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:27.844   318   318 E SMD     : DCD ON
,07-12 11:37:28.784   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 358, CUR = 450
,07-12 11:37:30.854   318   318 E SMD     : DCD ON
,07-12 11:37:30.884   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:33.854   318   318 E SMD     : DCD ON
,07-12 11:37:36.694   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:36.694   924  1660 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:37:36.704   924  1660 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:37:36.704   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:36.704   924   924 I MotionRecognitionService: Plugged
,07-12 11:37:36.704  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:36.704   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:37:36.714  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:36.714  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:37:36.714  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:37:36.714  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:37:36.714   924  1660 D BatteryService: stay LED for fully charged
,07-12 11:37:36.724  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:36.724  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
07-12 11:37:36.724  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:36.864   318   318 E SMD     : DCD ON
,07-12 11:37:37.124   924  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-12 11:37:38.824   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 352, CUR = 450
,07-12 11:37:39.864   318   318 E SMD     : DCD ON
,07-12 11:37:41.094   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:42.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:42.864   318   318 E SMD     : DCD ON
,07-12 11:37:43.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:44.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:45.084   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:37:45.854   318   318 E SMD     : DCD ON
,07-12 11:37:46.084   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-12 11:37:48.854   318   318 E SMD     : DCD ON
,07-12 11:37:48.884   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 350, CUR = 450
,07-12 11:37:50.894   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:37:51.864   318   318 E SMD     : DCD ON
,07-12 11:37:54.304   924  1342 E Watchdog: !@Sync 6
,07-12 11:37:54.854   318   318 E SMD     : DCD ON
,07-12 11:37:56.064   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:37:56.084  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:37:56.084  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:56.084   924  1401 D NtpTrustedTime: forceRefresh() from cache miss
,07-12 11:37:56.094  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-12 11:37:56.094  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:37:56.114   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:37:56.114   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:37:56.114   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:37:56.114   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:37:56.124   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:37:56.124  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:37:56.124  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:37:56.134   924   924 I MotionRecognitionService: Plugged
,07-12 11:37:56.134   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:37:56.134  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:37:56.144  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:37:56.144  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:56.144  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:37:56.144  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:37:56.144  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:37:56.154   924  1401 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1468316276215 mCachedNtpElapsedRealtime : 200592 mCachedNtpCertainty : 6
,07-12 11:37:56.154   924  1401 D NtpTrustedTime: currentTimeMillis() cache hit
,07-12 11:37:56.154   924  1401 D AlarmManagerService: Setting time of day to sec=1468316276
,07-12 11:37:56.154   924  1401 D AlarmManagerService: Trying to open a file
,07-12 11:37:56.164   924  1401 D AlarmManagerService: File Open Success
,07-12 11:37:56.164   924  1401 D AlarmManagerService: File Close Success
,07-12 11:37:56.164   924  1401 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
07-12 11:37:56.216   924  1401 W AlarmManagerService: Unable to set rtc to 1468316276: Invalid argument
07-12 11:37:56.216   924  1111 V AlarmManager: waitForAlarm result :65536
,07-12 11:37:56.226   924   924 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,07-12 11:37:56.226   924   924 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,07-12 11:37:56.226  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,07-12 11:37:56.226  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,07-12 11:37:56.236  1189  1189 D StatusBar-DoNotDistrub: Received intent with android.intent.action.TIME_SET action
,07-12 11:37:56.236  1189  1189 D StatusBar-DoNotDistrub: Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,07-12 11:37:56.236   924   924 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-12 11:37:56.256  1189  1189 D StatusBar-DoNotDistrub: sendBroadcast android.intent.action.DORMANT_MODE_OFF
,07-12 11:37:56.256  1805  1805 D accuweather: [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,07-12 11:37:56.256   924   924 I DrmEventService:  no response from SecureClock 
07-12 11:37:56.256   324  1548 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
07-12 11:37:56.266   924  1488 I AudioService: getStreamVolume 5 index 110
07-12 11:37:56.266  1805  1805 D accuweather: [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,07-12 11:37:56.266  1189  1189 D StatusBar-DoNotDistrub: The STREAM NOTIFICATION volume is 11
07-12 11:37:56.266   924   940 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
07-12 11:37:56.266  1805  1805 D accuweather: [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,07-12 11:37:56.266  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:37:56.266  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:37:56.276  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:37:56.286  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:37:56.296  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:37:56.336  6885  6885 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-12 11:37:56.346  6885  6885 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,07-12 11:37:56.356   924  1584 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:37:56.356   924  1584 D ActivityManager: caller:android.app.ApplicationThreadProxy@3612ff9b, r.packageName :com.google.android.gms
,07-12 11:37:56.376   924  1595 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:37:56.376   924  1595 D ActivityManager: caller:android.app.ApplicationThreadProxy@25802b11, r.packageName :com.google.android.gms
,07-12 11:37:56.386  3975  3975 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-12 11:37:56.386  3975  3975 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1468316276401
,07-12 11:37:56.386  3975  3975 I KLMS-2.4.511: : MainReciver(): TIME_CHANGED
,07-12 11:37:56.396  3975  3975 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().START : Tue Jul 12 11:37:56 GMT+02:00 2016
,07-12 11:37:56.396  3975  3975 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().END
,07-12 11:37:56.416  6033  6033 W System.err: android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,07-12 11:37:56.416  6033  6033 W System.err: 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.provider.Settings$System.getLong(Settings.java:1669)
07-12 11:37:56.416  6033  6033 W System.err: 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
07-12 11:37:56.416  6033  6033 W System.err: 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:37:56.416  6033  6033 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:37:56.416  6033  6033 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:56.416  6033  6033 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:37:56.416  6033  6033 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:37:56.416  6033  6033 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-12 11:37:56.446  6927  6927 I SO_AGENT: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,07-12 11:37:56.456  6083  6083 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,07-12 11:37:56.476   924  1562 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,07-12 11:37:56.476   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.476   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.476   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.476   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:56.546  7242  7242 E Zygote  : MountEmulatedStorage()
,07-12 11:37:56.546  7242  7242 E Zygote  : v2
07-12 11:37:56.546  7242  7242 I libpersona: KNOX_SDCARD checking this for 10055
07-12 11:37:56.546  7242  7242 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:56.556  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:56.556  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:56.556  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-12 11:37:56.556   924  1562 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=7242 uid=10055 gids={50055, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,07-12 11:37:56.576  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:56.586  7242  7242 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:56.586   351   351 I art     : Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 526us total 19.379ms
,07-12 11:37:56.596  7242  7242 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-12 11:37:56.596   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 380us total 15.006ms
,07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-12 11:37:56.606  7242  7242 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-12 11:37:56.616   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 442us total 13.289ms
,07-12 11:37:56.646  7242  7242 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,07-12 11:37:56.646  7242  7242 D Mms/TelephonyPermission: start operation mode monitor
,07-12 11:37:56.646  7242  7242 D Mms/TelephonyPermission: User ID is null set current User Id
,07-12 11:37:56.656  7242  7242 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-12 11:37:56.656  7242  7242 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-12 11:37:56.656  7242  7242 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,07-12 11:37:56.656  7242  7242 D Mms/TelephonyPermission: isDefault true
07-12 11:37:56.656  7242  7242 D Mms/MmsApp: onCreate() com.android.mms
,07-12 11:37:56.696  7242  7242 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 53.508125
,07-12 11:37:56.706  7242  7242 D Mms/MmsConfig: before partial update
,07-12 11:37:56.726  7242  7242 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
07-12 11:37:56.726  7242  7242 D EasySignUpManager: serviceId : 1, features : -1
,07-12 11:37:56.726  7242  7242 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
07-12 11:37:56.726  7242  7242 D EasySignUpManager: isAuth is false
,07-12 11:37:56.726  7242  7242 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,07-12 11:37:56.736  1431  1451 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7242
,07-12 11:37:56.736  1431  1451 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.598 ms
,07-12 11:37:56.736  7242  7242 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup
07-12 11:37:56.736  7242  7242 D EasySignUpManager: getServiceStatus : serviceId (1) is OFF
,07-12 11:37:56.746  7242  7242 D Mms/MmsConfig: Load Resize quality : 80
,07-12 11:37:56.756  7242  7242 D Mms/MmsConfig:  enable multiwindow = true
,07-12 11:37:56.756  7242  7242 E Mms/MessageUtils: setCountryDetector : update country detector info 
,07-12 11:37:56.766  7242  7242 E Mms/MessageUtils: updateCountryIso : update country iso info 
,07-12 11:37:56.766  7242  7242 D Mms/PackageInfo: com.sec.imsservice is not installed
,07-12 11:37:56.766  7242  7242 D Mms/MmsConfig: [end]    init() consume time = 71.180208
07-12 11:37:56.766  7242  7242 D Mms/MmsApp: [start]    initCountryIso consume time = 0.322761
,07-12 11:37:56.766   924  1447 D CountryDetector: The first listener is added
,07-12 11:37:56.776  7242  7242 D Mms/MmsApp: [end]    initCountryIso consume time = 3.352708
,07-12 11:37:56.776  7242  7242 D Mms/Contact: [start]    init() consume time = 1.960104
,07-12 11:37:56.776  1431  3046 D TP/MmsSmsProvider: query,matched:13, calling pid = 7242
,07-12 11:37:56.786  1431  3046 D TP/MmsSmsProvider: match 13:Elapsed time : 0.884 ms
,07-12 11:37:56.786  7242  7242 D Mms/Contact: [end]    init consume time = 12.959011
,07-12 11:37:56.786  7242  7261 D Mms/DraftCache: [start]    rebuildCache consume time = 3.838906
,07-12 11:37:56.796  1431  1451 D TP/MmsSmsProvider: query,matched:12, calling pid = 7242
,07-12 11:37:56.796  1431  1451 D TP/MmsSmsProvider: match 12:Elapsed time : 1.270 ms
,07-12 11:37:56.796  7242  7242 D Mms/Conversation: [start]    init() consume time = 3.809167
,07-12 11:37:56.796  1431  2116 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,07-12 11:37:56.796  7242  7261 D Mms/DraftCache: [end]    rebuildCache consume time = 2.192447
,07-12 11:37:56.796  1431  2116 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
07-12 11:37:56.796  1431  2116 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,07-12 11:37:56.806  1431  2116 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
07-12 11:37:56.806  1431  2116 D TP/MmsSmsProvider: need read changed broadcast:false
,07-12 11:37:56.806  7242  7242 D Mms/Conversation: [end]    init consume time = 7.675938
,07-12 11:37:56.816  7242  7242 D Mms/TelephonyUtils: getSubId from simSlot 0, return Value = -1
,07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: auto download without roaming -> true
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,07-12 11:37:56.816  7242  7242 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
07-12 11:37:56.816  7242  7242 D Mms/TelephonyUtils: getSubId from simSlot 1, return Value = 9223372036854775807
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: roaming -> false (slotId = 1)
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: auto download without roaming -> true
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: auto download during roaming secondary -> false
07-12 11:37:56.816  7242  7242 D Mms/DownloadManager: mAutoDownload ------> true
,07-12 11:37:56.826  7242  7242 D Mms/MessagingNotification: [start]    init() consume time = 24.115833
,07-12 11:37:56.826  7242  7242 D Mms/MessagingNotification: [end]    init consume time = 1.163646,
,07-12 11:37:56.836  7242  7262 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 4.403386
,07-12 11:37:56.836  7242  7242 D Mms/MmsApp: [end]    onCreate() consume time = 4.315781
,07-12 11:37:56.836   924  3435 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,07-12 11:37:56.836  1431  1452 D TP/MmsSmsProvider: query,matched:400, calling pid = 7242
,07-12 11:37:56.846   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=708]
07-12 11:37:56.846   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
07-12 11:37:56.846   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.846   924  3435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:56.846  7242  7242 D Mms/TelephonyUtils: getSubId from simSlot 0, return Value = -1
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: roaming -> false (slotId = 0)
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: auto download without roaming -> true
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
07-12 11:37:56.846  7242  7242 D Mms/DownloadManager: mAutoDownload ------> true
,07-12 11:37:56.846  1431  1762 D TP/MmsSmsProvider: query,matched:0, calling pid = 7242
07-12 11:37:56.846  1431  1762 V TP/MmsSmsProvider: getSimpleConversations entered.
07-12 11:37:56.856  7242  7264 D Mms/Synchronizer: [start]    doSync consume time = 11.762604
,07-12 11:37:56.856  1431  1762 D TP/MmsSmsProvider: match 0:Elapsed time : 0.967 ms
,07-12 11:37:56.886  7265  7265 E Zygote  : MountEmulatedStorage()
07-12 11:37:56.886  7265  7265 E Zygote  : v2
07-12 11:37:56.886  7265  7265 I libpersona: KNOX_SDCARD checking this for 10076
07-12 11:37:56.886  7265  7265 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:56.896  7265  7265 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:56.896  7265  7265 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:56.896  7265  7265 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:56.906   924  3435 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7265 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:56.916   924  3435 I ActivityManager: Killing 6239:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-12 11:37:56.916  7265  7265 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:56.916  7265  7265 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:56.926  7242  7262 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 78.623281
,07-12 11:37:56.936  1431  1452 D TP/MmsSmsProvider: update uri: content://mms-sms/db_synchronization
07-12 11:37:56.936  1431  1452 V TP/MmsSmsProvider: syncDBData start
,07-12 11:37:56.936  1431  1452 V TP/MmsSmsProvider: syncDBData sms end
,07-12 11:37:56.936  1431  1452 V TP/MmsSmsProvider: syncDBData mms end
07-12 11:37:56.936  1431  1452 V TP/MmsSmsProvider: syncDBData end
,07-12 11:37:56.936  7242  7264 D Mms/Synchronizer: [end]    doSync consume time = 5.159427
,07-12 11:37:56.936  7265  7265 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,07-12 11:37:56.946  7242  7263 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,07-12 11:37:56.946  1431  3046 D TP/SmsProvider: query,matched:26, calling pid = 7242
,07-12 11:37:56.946  1431  3046 D TP/SmsProvider: match 26:Elapsed time : 1.167 ms
,07-12 11:37:56.956  1431  1451 D TP/MmsSmsProvider: query,matched:6, calling pid = 7242
,07-12 11:37:56.956  1431  1451 D TP/MmsSmsProvider: match 6:Elapsed time : 1.218 ms
,07-12 11:37:56.966  7242  7263 I Mms/ReservationManager: ReservationManager()
,07-12 11:37:56.966  7242  7263 I Mms/ReservationManager: resetAfterConnected()
,07-12 11:37:56.996   924  1521 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,07-12 11:37:56.996   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.996   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.996   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:56.996   924  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:56.996  7265  7281 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,07-12 11:37:57.046  7282  7282 E Zygote  : MountEmulatedStorage()
07-12 11:37:57.046  7282  7282 E Zygote  : v2
,07-12 11:37:57.046  7282  7282 I libpersona: KNOX_SDCARD checking this for 10106
07-12 11:37:57.046  7282  7282 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.056   924  1521 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7282 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,07-12 11:37:57.056   924  1447 I art     : Explicit concurrent mark sweep GC freed 44548(2MB) AllocSpace objects, 23(368KB) LOS objects, 30% free, 36MB/52MB, paused 1.385ms total 89.172ms
,07-12 11:37:57.076  7282  7282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:37:57.076  7282  7282 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:37:57.076  1431  1451 D TP/MmsSmsProvider: query,matched:7, calling pid = 7242
,07-12 11:37:57.076  1431  1451 D TP/MmsSmsProvider: match 7:Elapsed time : 1.943 ms
,07-12 11:37:57.076  7282  7282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.076   924  1521 I ActivityManager: Killing 6345:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-12 11:37:57.086  7242  7263 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,07-12 11:37:57.106  7282  7282 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.106  7282  7282 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.126  7282  7282 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,07-12 11:37:57.126   924  1488 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,07-12 11:37:57.126  7282  7282 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-12 11:37:57.126   924  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.126   924  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.126   924  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.126   924  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:57.126  7282  7282 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-12 11:37:57.126  7282  7282 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:37:57.186  7302  7302 E Zygote  : MountEmulatedStorage()
,07-12 11:37:57.186  7302  7302 E Zygote  : v2
07-12 11:37:57.186  7302  7302 I libpersona: KNOX_SDCARD checking this for 10029
07-12 11:37:57.186  7302  7302 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.186   924  1488 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7302 uid=10029 gids={50029, 9997} abi=armeabi-v7a
,07-12 11:37:57.196  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:57.196  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:57.196  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.216   924   941 D SettingsProvider: name = next_alarm_formatted
07-12 11:37:57.216   924   941 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-12 11:37:57.216   924   941 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-12 11:37:57.216   924   941 D SettingsProvider: selectionArgs: false
07-12 11:37:57.216   924   941 D SettingsProvider: selectionArgs: 10106
07-12 11:37:57.216   924   941 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-12 11:37:57.216   924   941 D SettingsProvider: ret = -1
,07-12 11:37:57.226  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.226  7302  7302 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.236   924  1713 I ActivityManager: Killing 5585:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-12 11:37:57.246  7302  7302 D ResourcesManager: creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,07-12 11:37:57.246  7302  7302 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-12 11:37:57.296  7242  7263 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,07-12 11:37:57.346   924  1562 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-12 11:37:57.346   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.346   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.346   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.346   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:57.396  7317  7317 E Zygote  : MountEmulatedStorage()
07-12 11:37:57.396  7317  7317 E Zygote  : v2
07-12 11:37:57.396  7317  7317 I libpersona: KNOX_SDCARD checking this for 10116
07-12 11:37:57.396  7317  7317 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.406   924  1562 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7317 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-12 11:37:57.436  7317  7317 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:57.436  7317  7317 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:57.436   924  1562 I ActivityManager: Killing 4244:com.android.vending/u0a33 (adj 15): emptyCount ##41
07-12 11:37:57.436  7317  7317 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.456  7317  7317 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.456  7317  7317 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.466  7317  7317 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-12 11:37:57.476  7317  7317 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,07-12 11:37:57.476  7317  7317 D elm:14491: ELMEngine.ELMEngine( context ).
,07-12 11:37:57.486  7317  7317 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-12 11:37:57.486   924  1562 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-12 11:37:57.486   924  1562 D ActivityManager: caller:android.app.ApplicationThreadProxy@39f7e668, r.packageName :com.sec.esdk.elm
,07-12 11:37:57.486  7317  7317 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,07-12 11:37:57.486   924  1458 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,07-12 11:37:57.486   924  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.486   924  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.486   924  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.486   924  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:57.496  7317  7317 D elm:14491: ElmAgentService : onCreate()
,07-12 11:37:57.496  7317  7332 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,07-12 11:37:57.506  7317  7332 D elm:14491: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,07-12 11:37:57.506  7317  7317 D elm:14491: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,07-12 11:37:57.506  7317  7317 D elm:14491: ModuleBase.ModifySetAlarm()
07-12 11:37:57.506  7317  7317 D elm:14491: MDMBridge.getInstance()
07-12 11:37:57.506  7317  7317 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-12 11:37:57.586  7335  7335 E Zygote  : MountEmulatedStorage()
07-12 11:37:57.586  7335  7335 E Zygote  : v2
07-12 11:37:57.586  7335  7335 I libpersona: KNOX_SDCARD checking this for 10172
07-12 11:37:57.586  7335  7335 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.596   924  1458 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7335 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-12 11:37:57.616  7242  7341 D Mms/PerformanceUtils: link cahcing start
,07-12 11:37:57.626  7335  7335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:57.626  7335  7335 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:57.626  7335  7335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.626  7317  7317 D elm:14491: ElmAgentService : onDestroy().
,07-12 11:37:57.626   924  1458 I ActivityManager: Killing 5625:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-12 11:37:57.646  7242  7341 D Mms/PerformanceUtils: link cahcing done
,07-12 11:37:57.656  7335  7335 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.656  7335  7335 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.666  7335  7335 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-12 11:37:57.676  7335  7335 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-12 11:37:57.676  7335  7335 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:37:57.676  7335  7335 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:37:57.726   924  1447 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-12 11:37:57.726   924  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@18f42726, r.packageName :com.android.calendar
,07-12 11:37:57.736   924  1562 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,07-12 11:37:57.736   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.736   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.736   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.736   924  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:57.806   924  1562 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7359 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:37:57.806   924  1458 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-12 11:37:57.806   924  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@1990114, r.packageName :com.android.calendar
,07-12 11:37:57.806  7359  7359 E Zygote  : MountEmulatedStorage()
07-12 11:37:57.806  7359  7359 I libpersona: KNOX_SDCARD checking this for 10051
07-12 11:37:57.806  7359  7359 E Zygote  : v2
07-12 11:37:57.806  7359  7359 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.826  7359  7359 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:37:57.826  7359  7359 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:57.826  7359  7359 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.826  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-12 11:37:57.836  6485  6485 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-12 11:37:57.836  6485  6485 D SecurityLogAgent: StateMachine : Current State = 1
07-12 11:37:57.836   924  1315 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:37:57.836   924  1225 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:37:57.836   924  1584 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,07-12 11:37:57.836   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.836   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.836   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:57.836   924  1584 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:57.866  7359  7359 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.866  7359  7359 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.876  7375  7375 E Zygote  : MountEmulatedStorage()
07-12 11:37:57.876  7375  7375 I libpersona: KNOX_SDCARD checking this for 1000
07-12 11:37:57.876  7375  7375 E Zygote  : v2
07-12 11:37:57.876  7375  7375 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:57.886   924  1584 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7375 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-12 11:37:57.896  7375  7375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:37:57.896  7375  7375 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:57.896  7375  7375 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-12 11:37:57.896   318   318 E SMD     : DCD ON
,07-12 11:37:57.906  7359  7359 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,07-12 11:37:57.906  7359  7359 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-12 11:37:57.936  7375  7375 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:57.936  7375  7375 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:57.946  7375  7375 D ResourcesManager: creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,07-12 11:37:57.956  7375  7375 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316277973
,07-12 11:37:57.966  7375  7375 D         : TimeServiceNative: User Time to be set is 1468316277973
07-12 11:37:57.966  7375  7375 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:37:57.966  7375  7375 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
07-12 11:37:57.966  7375  7375 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316277973
,07-12 11:37:57.966  7375  7375 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-12 11:37:57.966   411   817 D QC-time-services: Daemon: Connection accepted:time_genoff
,07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316277973
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316277973, operation = 0
,07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/17/70 11:12:48
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:Value read from RTC seconds = 27688368000
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:new time 1468316277973 
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon: delta 1440627909973 genoff 1440627909973 
,07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627909973 to memory
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-12 11:37:57.966   411  7390 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:57.976   411  7390 D QC-time-services: Updating the TOD offset
,07-12 11:37:57.976   411  7390 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440627909973 to memory
07-12 11:37:57.976   411  7390 D QC-time-services: Daemon:Opening File: /data/time/ats_1
07-12 11:37:57.976   411  7390 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:57.976  7375  7375 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,07-12 11:37:57.976   924  1686 I ActivityManager: Killing 5365:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-12 11:37:57.976   411  7390 E QC-time-services: Daemon:Update to modem bit set
07-12 11:37:57.976   411  7390 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
07-12 11:37:57.976   411  7390 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124663109973
,07-12 11:37:57.976   411   817 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
07-12 11:37:57.976  4610  4610 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
07-12 11:37:57.976  4610  4610 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
,07-12 11:37:57.976   411   814 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
07-12 11:37:57.976  4610  4610 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
07-12 11:37:57.986  4610  4610 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,07-12 11:37:57.986  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,07-12 11:37:57.986  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-12 11:37:57.986  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-12 11:37:57.986  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:37:57.986  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-12 11:37:57.986  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:57.986  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
07-12 11:37:57.986  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo,
,07-12 11:37:57.996  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:37:57.996  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:37:57.996  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:37:57.996  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
07-12 11:37:57.996  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:58.006  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
07-12 11:37:58.006  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:37:58.006  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-12 11:37:58.016  7359  7359 I CalendarProvider2: CalendarProvider2.onCreate() called
,07-12 11:37:58.146   924  3435 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,07-12 11:37:58.146   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@240b5eac, r.packageName :com.android.providers.calendar
,07-12 11:37:58.176   924  1584 I ActivityManager: Killing 5725:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): emptyCount ##41
,07-12 11:37:58.836  7242  7242 I Mms/MmsApp:  start initViewCache mms
,07-12 11:37:58.866  7242  7242 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1929.294427
,07-12 11:37:58.866  7242  7242 D Mms/ComposeMessageFragment: fillCache, easy = false
,07-12 11:37:58.956   924  2963 D SSRM:n  : SIOP:: AP = 340, PST = 350, CUR = 450
,07-12 11:37:58.996  7242  7242 D AbsListView: Get MotionRecognitionManager
,07-12 11:37:58.996   924  1225 D MotionRecognitionService:  ssp status : true
,07-12 11:37:59.006  7242  7242 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 138.152657
,07-12 11:37:59.156  7359  7359 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,07-12 11:37:59.156   924  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,07-12 11:37:59.156   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:59.156   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:37:59.156   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:59.156   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:37:59.196   924  1018 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7410 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,07-12 11:37:59.196  7410  7410 E Zygote  : MountEmulatedStorage()
07-12 11:37:59.196  7410  7410 E Zygote  : v2
07-12 11:37:59.196  7410  7410 I libpersona: KNOX_SDCARD checking this for 10171
07-12 11:37:59.196  7410  7410 I libpersona: KNOX_SDCARD not a persona
,07-12 11:37:59.236  7410  7410 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:37:59.236  7410  7410 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:37:59.236  7410  7410 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-12 11:37:59.236   924  1458 I ActivityManager: Killing 6622:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,07-12 11:37:59.266  7410  7410 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:37:59.266  7410  7410 D ActivityThread: Added TimaKeyStore provider
,07-12 11:37:59.286  7410  7410 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-12 11:37:59.286  7410  7410 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-12 11:37:59.286  7410  7410 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-12 11:37:59.306   924  1562 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-12 11:37:59.306   924  1562 D ActivityManager: caller:android.app.ApplicationThreadProxy@3690677b, r.packageName :com.android.calendar
,07-12 11:37:59.315   924  1660 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,07-12 11:37:59.315   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@52c85f1, r.packageName :com.android.calendar
,07-12 11:37:59.325   924  1562 I ActivityManager: Killing 6638:com.google.android.apps.maps/u0a140 (adj 15): emptyCount ##41
,07-12 11:37:59.406  7242  7242 D Mms/BubbleViewCache: fillCache bubble = 8
,07-12 11:37:59.986   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:38:00.896   318   318 E SMD     : DCD ON
,07-12 11:38:03.895   318   318 E SMD     : DCD ON
,07-12 11:38:06.225   924  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:06.225   924  1686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:38:06.225   924  1686 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:38:06.235   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:06.235   924   924 I MotionRecognitionService: Plugged
,07-12 11:38:06.235   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:38:06.235  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:06.245  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:06.245  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:06.245  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:38:06.245  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:38:06.245   924  1686 D BatteryService: stay LED for fully charged
,07-12 11:38:06.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:06.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:38:06.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:06.905   318   318 E SMD     : DCD ON
,07-12 11:38:09.005   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 345, CUR = 450
,07-12 11:38:09.905   318   318 E SMD     : DCD ON
,07-12 11:38:10.935   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:11.125   370   370 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-12 11:38:11.125   370   370 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-12 11:38:12.905   318   318 E SMD     : DCD ON
,07-12 11:38:15.905   318   318 E SMD     : DCD ON
,07-12 11:38:16.285   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:16.285   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:38:16.295   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:38:16.295   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:16.295  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:16.305   924   924 I MotionRecognitionService: Plugged
,07-12 11:38:16.305  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:38:16.305   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:38:16.305  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:16.305   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:38:16.305  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:16.305  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:16.315  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-12 11:38:16.315  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:38:16.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:17.165   924  1060 I PowerManagerService: [PWL] Off : 180s ago
,07-12 11:38:18.905   318   318 E SMD     : DCD ON
,07-12 11:38:19.055   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 337, CUR = 450
,07-12 11:38:21.125   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:21.905   318   318 E SMD     : DCD ON
,07-12 11:38:22.125   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:23.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:24.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:24.355   924  1342 E Watchdog: !@Sync 7
,07-12 11:38:24.905   318   318 E SMD     : DCD ON
,07-12 11:38:25.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:26.135   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-12 11:38:26.345   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:26.355   924  1488 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:38:26.355   924  1488 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:38:26.355   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:26.355   924   924 I MotionRecognitionService: Plugged
,07-12 11:38:26.355   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:38:26.365  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:26.365  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:26.365  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:38:26.365   924  1488 D BatteryService: stay LED for fully charged
,07-12 11:38:26.365  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:26.365  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:26.375  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:38:26.375  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:26.375  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:27.905   318   318 E SMD     : DCD ON
,07-12 11:38:29.095   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 332, CUR = 450
,07-12 11:38:30.905   318   318 E SMD     : DCD ON
,07-12 11:38:30.935   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:31.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:32.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:33.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:33.905   318   318 E SMD     : DCD ON
,07-12 11:38:34.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:35.135   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:36.135   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-12 11:38:36.405   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:36.405   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:38:36.405   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:38:36.415   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:36.415   924   924 I MotionRecognitionService: Plugged
,07-12 11:38:36.415   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:38:36.415  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:36.425  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:38:36.425  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:36.425  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:36.425  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:36.425  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:38:36.435   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:38:36.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:36.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:36.905   318   318 E SMD     : DCD ON
,07-12 11:38:39.145   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 450
,07-12 11:38:39.905   318   318 E SMD     : DCD ON
,07-12 11:38:42.915   318   318 E SMD     : DCD ON
,07-12 11:38:45.915   318   318 E SMD     : DCD ON
,07-12 11:38:46.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:46.465   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:47.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:48.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:48.915   318   318 E SMD     : DCD ON
,07-12 11:38:49.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:49.195   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 327, CUR = 450
,07-12 11:38:50.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:38:50.945   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:38:51.145   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-12 11:38:51.915   318   318 E SMD     : DCD ON
,07-12 11:38:54.355   924  1342 E Watchdog: !@Sync 8
,07-12 11:38:54.915   318   318 E SMD     : DCD ON
,07-12 11:38:56.525   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:38:56.525   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:38:56.535   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:38:56.535   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:38:56.535   924   924 I MotionRecognitionService: Plugged
,07-12 11:38:56.535  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:38:56.535   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:38:56.545  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:38:56.545  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:38:56.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:56.555  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:38:56.555  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:38:56.555   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:38:56.555  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:56.565  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:38:57.915   318   318 E SMD     : DCD ON
,07-12 11:38:59.245   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 450
,07-12 11:39:00.915   318   318 E SMD     : DCD ON
,07-12 11:39:02.165   924  1060 I PowerManagerService: [PWL] Off : 225s ago
,07-12 11:39:03.915   318   318 E SMD     : DCD ON
,07-12 11:39:06.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:06.585   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:06.915   318   318 E SMD     : DCD ON
,07-12 11:39:07.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:08.145   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:09.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:09.285   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 450
,07-12 11:39:09.915   318   318 E SMD     : DCD ON
,07-12 11:39:10.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:10.945   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:11.155   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-12 11:39:12.915   318   318 E SMD     : DCD ON
,07-12 11:39:15.915   318   318 E SMD     : DCD ON
,07-12 11:39:16.645   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:18.925   318   318 E SMD     : DCD ON
,07-12 11:39:19.335   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 450
,07-12 11:39:21.925   318   318 E SMD     : DCD ON
,07-12 11:39:24.355   924  1342 E Watchdog: !@Sync 9
,07-12 11:39:24.925   318   318 E SMD     : DCD ON
,07-12 11:39:26.705   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:26.705   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:39:26.705   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:39:26.715   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:26.725  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:26.725  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:39:26.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:26.725   924  1562 D BatteryService: stay LED for fully charged
07-12 11:39:26.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:26.725   924   924 I MotionRecognitionService: Plugged
,07-12 11:39:26.725  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:26.735  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
07-12 11:39:26.735   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:39:26.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:26.735  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:27.925   318   318 E SMD     : DCD ON
,07-12 11:39:28.655   300   300 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6b01090
07-12 11:39:28.655   300   300 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
07-12 11:39:28.655   300   300 I rmt_storage: wakelock acquired: 1, error no: 42
,07-12 11:39:28.655   300   650 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,07-12 11:39:28.715   300   650 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
,07-12 11:39:28.715   300   650 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
07-12 11:39:28.715   300   650 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 0
07-12 11:39:28.715   300   650 I rmt_storage: 
,07-12 11:39:28.715   300   300 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6b01090
,07-12 11:39:29.385   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 450
,07-12 11:39:30.925   318   318 E SMD     : DCD ON
,07-12 11:39:30.955   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:31.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:32.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:33.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:33.925   318   318 E SMD     : DCD ON
,07-12 11:39:34.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:35.155   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:39:36.155   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-12 11:39:36.775   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:36.775   924  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:39:36.775   924  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:39:36.775   924  1584 D BatteryService: stay LED for fully charged
,07-12 11:39:36.775   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:36.775  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:36.775  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:36.775   924   924 I MotionRecognitionService: Plugged
07-12 11:39:36.775   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:39:36.785  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:39:36.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:36.795  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:36.795  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:39:36.795  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:36.795  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:36.925   318   318 E SMD     : DCD ON
,07-12 11:39:39.425   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-12 11:39:39.925   318   318 E SMD     : DCD ON
,07-12 11:39:42.925   318   318 E SMD     : DCD ON
,07-12 11:39:45.925   318   318 E SMD     : DCD ON
,07-12 11:39:46.835   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:46.835   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:39:46.835   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:39:46.835   924   940 D BatteryService: stay LED for fully charged
,07-12 11:39:46.835   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:46.835  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:46.835  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:39:46.835   924   924 I MotionRecognitionService: Plugged
07-12 11:39:46.835   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:39:46.845  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:39:46.845  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:46.855  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:46.855  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:39:46.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:46.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:48.925   318   318 E SMD     : DCD ON
,07-12 11:39:49.055   924  1120 D InputReader: Input event: value=1
,07-12 11:39:49.055   924  1120 D InputReader: !@notifyKey(172), action=0
,07-12 11:39:49.055   924  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0
,07-12 11:39:49.055   924  1120 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 924  pkgName : WAKEUP_BOOSTER@32
,07-12 11:39:49.055   924  1120 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-12 11:39:49.055   924  1120 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 924) eventTime = 313460 event = 1
,07-12 11:39:49.055   924  1120 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 924)
07-12 11:39:49.055   924  1120 I PowerManagerService: Waking up from sleep (uid 1000)...
,07-12 11:39:49.065   924  1120 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-12 11:39:49.065   924  1120 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-12 11:39:49.065   924  1169 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@2604a307)
07-12 11:39:49.065   924  1120 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-12 11:39:49.065   924  1120 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-12 11:39:49.065   924  1120 D InputManager-JNI: Disable repeat for home key when device wake up
,07-12 11:39:49.065  1189  1207 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
07-12 11:39:49.065  1189  1207 D KeyguardViewMediator: notifyScreenOnLocked
07-12 11:39:49.065  1189  1189 D KeyguardViewMediator: handleNotifyScreenOn
07-12 11:39:49.065  1189  1189 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-12 11:39:49.065   924  1060 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-12 11:39:49.065   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-12 11:39:49.065   924  1060 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-12 11:39:49.065  1189  1189 D KeyguardViewBase: screen on, instance bae4987
07-12 11:39:49.065   924  1056 D SContextService: 	.registerCallback : 1, client=
,07-12 11:39:49.065   924  1056 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-12 11:39:49.065   924  1056 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
07-12 11:39:49.065  1189  1189 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-12 11:39:49.065  1189  1189 D KeyguardSecurityView: showSecurityScreen(None)
07-12 11:39:49.065  1189  1189 D KeyguardUnlockView: outRect: Rect(0, 99 - 1080, 1920)
07-12 11:39:49.065  1189  1189 D KeyguardUnlockView: isValidRect: true
07-12 11:39:49.065  1189  1189 I WaterColor Keyguard: showUnlockAffordance
,07-12 11:39:49.065  1189  1539 D TEST    : run!!!
07-12 11:39:49.065  1189  1539 I WaterColorEffect_View: showAffordanceEffect
07-12 11:39:49.065   924  1056 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
07-12 11:39:49.065   924  1056 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-12 11:39:49.065   924  1056 D SContextService: sendAttribute() : service = Auto Rotation
,07-12 11:39:49.065   924  1056 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
07-12 11:39:49.065   924  1174 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
07-12 11:39:49.065   924  1174 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-12 11:39:49.065   924  1174 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-12 11:39:49.065   924  1174 I QCOM PowerHAL: Got set_interactive hint
07-12 11:39:49.065   924  1056 V CAE     : start(ContextProvider.java:126)
,07-12 11:39:49.065   924  1056 V CAE     : clear(AutoRotationRunner.java:182)
07-12 11:39:49.065   924  1056 V CAE     : enable(AutoRotationRunner.java:158)
07-12 11:39:49.065  1189  1189 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOn
07-12 11:39:49.065  1189  1189 I WaterColor Keyguard: screenTurnedOn
07-12 11:39:49.065  1189  1189 D SecKeyguardCircleView: onScreenTurnedOn
07-12 11:39:49.065  1189  1539 I WaterColor_Renderer: clearEffect()
,07-12 11:39:49.065   924  1056 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
07-12 11:39:49.065   924  1056 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
07-12 11:39:49.075   331  4702 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-12 11:39:49.075   924  1713 E Sensors : Acc old sensor_state 0, new sensor_state : 1 en : 1
,07-12 11:39:49.075   265   265 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
07-12 11:39:49.075   265   265 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-12 11:39:49.085   924  1169 D InputManager-JNI: setDeviceInteractive: 1
,07-12 11:39:49.085   924  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-12 11:39:49.085  1189  1539 I WaterColor_Renderer: dirty mode
,07-12 11:39:49.085   924   924 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 924) 
,07-12 11:39:49.095   924  7455 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-12 11:39:49.095   924   924 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
07-12 11:39:49.095   924  1091 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-12 11:39:49.095   924  7456 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-12 11:39:49.095   924  7457 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-12 11:39:49.095   924   924 D BatteryService: turn off LED
,07-12 11:39:49.095   924  1056 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-12 11:39:49.095   924  1056 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
07-12 11:39:49.095   924  1091 D lights  : led_pattern : 0 +
07-12 11:39:49.095   924  1091 D lights  : led_pattern : 0 -
,07-12 11:39:49.095   924  7456 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
07-12 11:39:49.095  1189  1189 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,07-12 11:39:49.095   924   924 V ActivityManager: Display changed displayId=0
,07-12 11:39:49.105   924  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
07-12 11:39:49.105  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-12 11:39:49.105  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-12 11:39:49.115   924  1595 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,07-12 11:39:49.115  1189  1189 D StatusBarKeyguardViewManager: callback.onShown()
07-12 11:39:49.115  1189  1189 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-12 11:39:49.135   924   924 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-12 11:39:49.135   924   924 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,07-12 11:39:49.145  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
07-12 11:39:49.145  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-12 11:39:49.145   924   924 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-12 11:39:49.145   924   924 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-12 11:39:49.145   331   331 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-12 11:39:49.145   924  1056 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-12 11:39:49.145   924  1056 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-12 11:39:49.145   924  1056 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-12 11:39:49.145   924  1056 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2888d744, Service : AUTO_ROTATION(1)
07-12 11:39:49.145   924  1056 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-12 11:39:49.145   924  1056 D SContextService: addSContextService() : service = Auto Rotation
07-12 11:39:49.145   924  1056 D SContextService: ===== SContext Service List =====
07-12 11:39:49.145   924  1056 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@3672902d, Service : Auto Rotation
07-12 11:39:49.145   924  1056 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@380fbc34, service=Auto Rotation
,07-12 11:39:49.155   924   924 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-12 11:39:49.155  1189  1189 D QSpanel : label top:23
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:23
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:23
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:23
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:39:49.155  1189  1189 D QSpanel : label top:0
07-12 11:39:49.155  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:39:49.165   924   924 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-12 11:39:49.165   924  1124 E MotionRecognitionService:  handler : SCREEN_ON end
,07-12 11:39:49.165   924  1146 I WifiNative-HAL: startHal
,07-12 11:39:49.165   924  1146 E wifi    : getStaticLongField sWifiHalHandle 0x935a680c
07-12 11:39:49.165   924  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xa01c5a
07-12 11:39:49.165   924  1146 I WifiNative-HAL: Could not start hal
,07-12 11:39:49.175   924   924 D NotificationService: ACTION_SCREEN_ON
,07-12 11:39:49.175   924   924 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 924) 
07-12 11:39:49.175   924   924 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
07-12 11:39:49.175   924  1091 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-12 11:39:49.175   924  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-12 11:39:49.175   324   678 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-12 11:39:49.175   324   678 V voice   : voice_set_parameters: enter: screen_state=on
07-12 11:39:49.175   324   678 V voice   : voice_set_parameters: exit with code(-2)
07-12 11:39:49.175   324   678 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-12 11:39:49.175   324   678 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-12 11:39:49.175   324   678 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-12 11:39:49.175   324   678 V audio_hw_primary: adev_set_parameters: exit
,07-12 11:39:49.175   924   924 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,07-12 11:39:49.185   924  1146 E native  : do suspend false
,07-12 11:39:49.185  6593  6593 I wpa_supplicant: reset timer : RESET_TIMER 1
07-12 11:39:49.185  6593  6593 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-12 11:39:49.195  6593  6593 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-12 11:39:49.195  6593  6593 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-12 11:39:49.205   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-12 11:39:49.205   924  7455 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
07-12 11:39:49.205   924  1060 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-12 11:39:49.245   924  1120 D InputReader: Input event: value=0
07-12 11:39:49.245   924  1120 D InputReader: !@notifyKey(172), action=1
07-12 11:39:49.245   924  1120 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1
,07-12 11:39:49.245   924  1120 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 924  tag : WAKEUP_BOOSTER@32
,07-12 11:39:49.245   924  1120 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 924  pkgName : WAKEUP_BOOSTER@32
07-12 11:39:49.245   924  1120 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-12 11:39:49.245   924  1120 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 924) eventTime = 313650 event = 1
07-12 11:39:49.245   924  1120 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-12 11:39:49.255   924  1119 D VoIPInterfaceManager: isVoIPRinging()...
07-12 11:39:49.255   924  1119 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-12 11:39:49.255   924  1119 D VoIPInterfaceManager: Not exist call session
,07-12 11:39:49.255   924  1119 D PersonaManager: isKioskContainerExistOnDevice
,07-12 11:39:49.315   265   505 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-12 11:39:49.315   265   265 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-12 11:39:49.315   265   265 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-12 11:39:49.315   924  1174 D SurfaceControl: Excessive delay in setPowerMode(): 245ms
07-12 11:39:49.315   924  1174 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 251ms
,07-12 11:39:49.315   924  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,07-12 11:39:49.325   924  1058 D IpRemoteDisplayController: Bridge Server is not available
07-12 11:39:49.325  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:39:49.325  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-12 11:39:49.325  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: applyOpen
07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte level=2
,07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x2 gsm|lte
07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=2
07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_2 mContentDescriptionPhoneSignal = Two bars of phone signal
07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:49.335  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-12 11:39:49.335   924  1056 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,07-12 11:39:49.335   924  1060 I DisplayPowerController: Unblocked screen on after 273 ms
07-12 11:39:49.335   924  1060 D DisplayPowerState: !@ ColorFade exit
,07-12 11:39:49.335  1189  1189 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:39:49.335  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:49.335  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:39:49.335  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-12 11:39:49.335  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:39:49.335  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-12 11:39:49.335  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:39:49.345   265  1944 I SurfaceFlinger: id=10 Removed DolorFade (8/8)
07-12 11:39:49.345   924  1060 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-12 11:39:49.345   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-12 11:39:49.345   924  1060 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-12 11:39:49.345   924  1173 D lights  : lcd : 255 +
,07-12 11:39:49.355   265  1489 I SurfaceFlinger: id=10 Removed DolorFade (-2/8)
,07-12 11:39:49.375   924  1173 D lights  : lcd : 255 -
07-12 11:39:49.375   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 255
07-12 11:39:49.375   924  1060 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-12 11:39:49.375   924  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-12 11:39:49.375   924  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
,07-12 11:39:49.375   924  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-12 11:39:49.375   924  1170 D PowerManagerService: [input device light] handleInputDeviceLightOn
07-12 11:39:49.375   924  1170 D lights  : button : 1 +
,07-12 11:39:49.415   924  1170 D lights  : button : 1 -
,07-12 11:39:49.425  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:39:49.435   924  7457 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-12 11:39:49.465  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:39:49.475   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-12 11:39:49.485   924  1014 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-12 11:39:49.485   924   924 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-12 11:39:49.485   924  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-12 11:39:49.485  1421  1421 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_LOCKED by isKeyguardLocked()
07-12 11:39:49.485  1421  1421 D NativeNfcManager: power state=3
,07-12 11:39:49.505  1421  7473 D NfcService: call the applyRouting
,07-12 11:39:49.505  1805  1805 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,07-12 11:39:49.505  1805  1805 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,07-12 11:39:49.515   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@6834962, r.packageName :com.google.android.gms
,07-12 11:39:49.525  1766  1766 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-12 11:39:49.545  1421  7473 D NfcService: index : 0
,07-12 11:39:49.545  1421  7473 D NfcService: index : 1
07-12 11:39:49.545  1421  7473 D NfcService: index : 2
,07-12 11:39:49.545   924  2963 D SSRM:a  : DeviceInfo:: 000100100000
07-12 11:39:49.545   924  2963 D SSRM:a  : SettingsAirViewInfo:: 010100000
07-12 11:39:49.545   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:39:49.545  4610  4610 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
07-12 11:39:49.545  4610  4610 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-12 11:39:49.545  4610  4610 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25612860k
,07-12 11:39:49.545  4610  4610 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,07-12 11:39:49.545  4610  4610 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,07-12 11:39:49.545  4610  4610 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
07-12 11:39:49.545  4610  4610 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
07-12 11:39:49.545  4610  4610 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1468316389563
,07-12 11:39:49.555   924  1169 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-12 11:39:49.565  1189  1189 I WaterColorEffect_View: showAffordanceEffect Renderer.handleTouchEvent(0, 540, 1009
07-12 11:39:49.565  1189  1189 I WaterColor_Renderer: Renderer handleTouchEvent action = 0
,07-12 11:39:49.575   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 450
,07-12 11:39:49.585  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-12 11:39:49.585  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-12 11:39:49.585  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-12 11:39:49.585  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-12 11:39:49.585  4610  4610 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-12 11:39:49.585  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:39:49.585  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-12 11:39:49.585  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:39:49.595  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:39:49.595  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:39:49.595  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-12 11:39:49.595  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-12 11:39:49.595  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/12/2016 04:19 PM
,07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/12/2016 11:39 AM
07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-12 11:39:49.605  4610  4610 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-12 11:39:49.645   924  7475 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-12 11:39:49.645   924  7475 D NetworkStatsFactory: UpdateStatsForKnox
,07-12 11:39:49.675   924  7475 D NetworkStatsFactory: UpdateStatsForKnox
,07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Screen bin #0: time=515 power=0.0032616666666666666
07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Screen bin #3: time=0 power=0.0
07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Screen bin #4: time=42561 power=2.4259769999999996
07-12 11:39:49.715   924  7475 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-12 11:39:49.885   924  7475 I BatteryStatsDumper: Writing to database completed
,07-12 11:39:50.245   924   924 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 924  tag : WAKEUP_BOOSTER@32
,07-12 11:39:50.575  1189  1539 I WaterColor_Renderer: fps 60.396038
,07-12 11:39:50.725  1189  1539 I WaterColor_Renderer: dirty mode
07-12 11:39:50.725  1189  1539 I WaterColor_Renderer: fps 60.150375
,07-12 11:39:50.875   924  1170 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-12 11:39:50.875   924  1170 D lights  : button : 0 +
,07-12 11:39:50.915   924  1170 D lights  : button : 0 -
,07-12 11:39:50.955   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:39:51.605   924  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:39:51.605   924  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:39:51.605   924  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:39:51.605   924  1100 I TLC_TIMA_PKM_initialize: initializing...
,07-12 11:39:51.605   924  1100 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-12 11:39:51.605   924  1100 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-12 11:39:51.615   924  1100 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-12 11:39:51.615   924  1100 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-12 11:39:51.615   924  1100 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-12 11:39:51.615   924  1100 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-12 11:39:51.615   924  1100 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-12 11:39:51.615   924  1100 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-12 11:39:51.615   924  1100 D QSEECOMAPI: : App is not loaded in QSEE
,07-12 11:39:51.645   924  1100 D QSEECOMAPI: : Loaded image: APP id = 2
,07-12 11:39:51.645   924  1100 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-12 11:39:51.655   924  1100 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-12 11:39:51.925   318   318 E SMD     : DCD ON
,07-12 11:39:52.225   924  1148 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 502] to 60
,07-12 11:39:52.225   924  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-12 11:39:52.225   924  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-12 11:39:52.225   924  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-12 11:39:52.225   924  1148 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,07-12 11:39:52.225   924  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
07-12 11:39:52.225   924  1148 D ConnectivityService: calling update connectivity
,07-12 11:39:52.225   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-12 11:39:52.225   924  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:39:52.225   924  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-12 11:39:52.235  1189  1606 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-12 11:39:52.235   924  1148 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:39:53.185  6593  6593 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
,07-12 11:39:53.195   924  1145 D WifiP2pService: InactiveState{ what=147461 }
,07-12 11:39:53.195   924  1145 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-12 11:39:53.195   924  1145 D WifiP2pService: DefaultState{ what=147461 }
,07-12 11:39:54.085  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-12 11:39:54.085  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-12 11:39:54.145  1189  1189 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-12 11:39:54.255   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:39:54.255   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:39:54.265   924  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:39:54.265   924  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:39:54.355   924  1342 E Watchdog: !@Sync 10
,07-12 11:39:54.865  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:54.865  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:54.875  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:54.875  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:54.885  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:54.885  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:54.885  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:54.895  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:54.895  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:54.895  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:54.935   318   318 E SMD     : DCD ON
,07-12 11:39:55.895  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=2 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mQSPhoneSignalIconId=0x7f020133/com.android.systemui:drawable/ic_qs_signal_2 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020477/com.android.systemui:drawable/stat_sys_signal_2 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:55.895  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:55.905  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:55.915  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:55.915  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:55.925  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:55.925  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:55.925  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:55.925  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:55.925  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:56.735  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
,07-12 11:39:56.735  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
,07-12 11:39:56.735  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:56.745  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:56.745  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:56.755  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:56.755  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:56.755  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:56.755  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:56.875   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:39:56.875   924  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:39:56.875   924  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:39:56.875   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:39:56.875   924   924 I MotionRecognitionService: Plugged
,07-12 11:39:56.875   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:39:56.895  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:39:56.895  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:39:56.905  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:39:56.905  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:39:56.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:39:56.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:56.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:39:56.905  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:39:57.925  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:57.925  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:57.935  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:57.935   318   318 E SMD     : DCD ON
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:57.945  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:57.955  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:58.955  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-12 11:39:58.955  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:58.955  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:58.965  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:58.975  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:58.975  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:58.985  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:58.985  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:58.985  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-12 11:39:58.995  1189  1189 D StatusBar.NetworkController: applyOpen
,07-12 11:39:59.055   924  1060 D PowerManagerService: [s] UserActivityState : 1 -> 4
,07-12 11:39:59.055   924  1060 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
07-12 11:39:59.055   924  1060 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-12 11:39:59.055   924  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
07-12 11:39:59.055   924  1169 D InputManager-JNI: setDeviceInteractive: 0
,07-12 11:39:59.055   924  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-12 11:39:59.055   924  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-12 11:39:59.055   924  1060 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-12 11:39:59.055   924  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-12 11:39:59.065   924  1060 D PowerManagerService: handleSandman : startDream()
,07-12 11:39:59.065   924  1060 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
,07-12 11:39:59.065   924  1060 I PowerManagerService: Sleeping (uid 1000)...
07-12 11:39:59.065   924  1060 D PowerManagerService: [s] UserActivityState : 4 -> 0
,07-12 11:39:59.065   924  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0
,07-12 11:39:59.065   924  1170 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-12 11:39:59.065   265   265 I SurfaceFlinger: id=13 createSurf (1080x1920),2 flag=404, DolorFade
,07-12 11:39:59.075   924  7497 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,07-12 11:39:59.075   924  7498 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
,07-12 11:39:59.075   924  7497 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,07-12 11:39:59.085   924  7496 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
,07-12 11:39:59.085   924  7496 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0,
07-12 11:39:59.085   924  7498 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-12 11:39:59.085   924  1169 D SContextService: 	.unregisterCallback : 1, client=
07-12 11:39:59.085   924  1169 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3672902d, Service = Auto Rotation, used = 1
,07-12 11:39:59.095   924  1169 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-12 11:39:59.095   924  1169 V CAE     : stop(ContextProvider.java:149)
,07-12 11:39:59.105   924  1169 V CAE     : clear(AutoRotationRunner.java:182)
,07-12 11:39:59.105   924  1169 V CAE     : disable(AutoRotationRunner.java:171)
,07-12 11:39:59.105   924  1169 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
07-12 11:39:59.105   924  1169 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0,
,07-12 11:39:59.115   331  4703 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-12 11:39:59.125   924  1169 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-12 11:39:59.125   924  1169 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-12 11:39:59.145   924  1060 D DisplayPowerController: ColorFade: onAnimationStart
,07-12 11:39:59.145   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-12 11:39:59.145   924  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-12 11:39:59.175   924  1173 D lights  : lcd : 95 +
,07-12 11:39:59.175   924  1169 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-12 11:39:59.175   924  1169 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-12 11:39:59.175   924  1169 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-12 11:39:59.185   924  1169 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-12 11:39:59.185   924  1169 D SContextService: removeSContextService() : service = Auto Rotation
07-12 11:39:59.185   924  1169 D SContextService: ===== SContext Service List =====
,07-12 11:39:59.185   924  1169 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@380fbc34, service=Auto Rotation
07-12 11:39:59.185  1189  2954 D KeyguardViewMediator: onScreenTurnedOff(3)
,07-12 11:39:59.185  1189  2954 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
07-12 11:39:59.185  1189  2954 D KeyguardEffectViewController: changeWallpaperByScreenOff()
07-12 11:39:59.185  1189  2954 D KeyguardViewMediator: notifyScreenOffLocked
07-12 11:39:59.185  1189  2954 E KeyguardViewMediator: resetStateLocked
,07-12 11:39:59.185  1189  1189 D KeyguardViewMediator: handleNotifyScreenOff
07-12 11:39:59.185  1189  1189 D KeyguardViewBase: screen off, instance bae4987 at 323594
,07-12 11:39:59.195  1189  1189 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=true)
,07-12 11:39:59.195  1189  1189 D KeyguardSecurityView: showSecurityScreen(None)
,07-12 11:39:59.195  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-12 11:39:59.195  1189  1189 D KeyguardViewMediator: Kiosk container not exists on device.
07-12 11:39:59.195  1189  1189 D KeyguardViewMediator: handleReset
,07-12 11:39:59.205   924   924 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 924) 
,07-12 11:39:59.205   924   924 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
07-12 11:39:59.205   924  1173 D lights  : lcd : 95 -
,07-12 11:39:59.205   924   924 E LightSensor: Light old sensor_state 1, new sensor_state : 513 en : 1
,07-12 11:39:59.205  1189  1189 D KeyguardEffectViewUtil: wallpaperType :1
,07-12 11:39:59.205  1189  1189 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-12 11:39:59.205  1189  1189 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-12 11:39:59.215  1189  1189 D PhoneStatusBar: updateKeyguardState :1
,07-12 11:39:59.215   924   924 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-12 11:39:59.215   924   924 D BatteryService: turn on LED for fully charged
,07-12 11:39:59.215  1189  1189 D StatusBar: LSSN:1
,07-12 11:39:59.225   924   924 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-12 11:39:59.225  1189  1189 D StatusBar: fullBouncer=false
07-12 11:39:59.225   924   924 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
07-12 11:39:59.225  1189  1189 D StatusBar: SLN:S
07-12 11:39:59.225   924   924 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
07-12 11:39:59.225   924   924 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
,07-12 11:39:59.225   331   553 D Sensorhubs: sendContextData: -76, 13, -46, 0
07-12 11:39:59.225  1189  1189 E LSO     : LSO Service is not yet ready!!!
,07-12 11:39:59.225  1189  1189 D StatusBar-QSPanel: setSingleLine:true
,07-12 11:39:59.225  1189  1189 D StatusBar-QSPanel: updateButtonInfo mButtonWidth : 206 mColumns:5 orien: 1 displayWidth:1032
,07-12 11:39:59.225   924  1173 D lights  : lcd : 0 +
07-12 11:39:59.225   924  1060 D DisplayPowerController: getFinalBrightness : 255 -> 0
07-12 11:39:59.225   924  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-12 11:39:59.225  1189  1189 D StatusBar-QSPanel: setSingleLine height:0
,07-12 11:39:59.225  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:39:59.235   924   924 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 9, 39, 59,
07-12 11:39:59.235   924   924 D SensorHubManager: SendSensorHubData: send data = -63, 14, 9, 39, 59
,07-12 11:39:59.235   331  4702 D Sensorhubs: sendContextData: -63, 14, 9, 39, 59
,07-12 11:39:59.235  1189  1189 D STATUSBAR-PhoneStatusBar: showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
07-12 11:39:59.235  1189  1189 I PhoneStatusBar: Icon Only
,07-12 11:39:59.235  1189  1189 I StatusBar: Icon Only
,07-12 11:39:59.245  1189  1189 D PanelView: There is/are notification(s) 
07-12 11:39:59.245  1189  1189 D PhoneStatusBar: updateQSpanelHeight: 279 height:591
,07-12 11:39:59.245  1189  1189 D PanelView: setQsHeight mQsMin:0 mQsMax:705 mQsEx:0.0mQsPeek:591
07-12 11:39:59.245  1189  1189 I KeyguardEffectViewController: setKeyguardShowing = true
07-12 11:39:59.245  1189  1189 D KeyguardEffectViewController: reset()
07-12 11:39:59.245  1189  1189 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : reset
07-12 11:39:59.245  1189  1189 I WaterColor Keyguard: reset
,07-12 11:39:59.245   924   924 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
07-12 11:39:59.245  1189  1539 I WaterColor_Renderer: clearEffect()
07-12 11:39:59.245   924  1124 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-12 11:39:59.245  1189  1539 I WaterColor_Renderer: dirty mode
,07-12 11:39:59.245  1189  1189 D KeyguardEffectViewController: isFestivalActivated()false
07-12 11:39:59.245  1189  1189 I KeyguardEffectViewController: setFestivalKeyguardShowing = true ,:false
,07-12 11:39:59.245  1189  1189 D KeyguardEffectViewController: isFestivalActivated()false
07-12 11:39:59.245  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-12 11:39:59.245  1189  1189 I PhoneStatusBar: Icon Only
07-12 11:39:59.245  1189  1189 I StatusBar: Icon Only
,07-12 11:39:59.245   924   924 D NotificationService: ACTION_SCREEN_OFF
07-12 11:39:59.245   924   924 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 924) 
07-12 11:39:59.245   924   924 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,07-12 11:39:59.255  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:39:59.255   924  1173 D lights  : lcd : 0 -
,07-12 11:39:59.255   924  1146 E native  : do suspend true
,07-12 11:39:59.255   324   667 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-12 11:39:59.255   324   667 V voice   : voice_set_parameters: enter: screen_state=off
07-12 11:39:59.255   324   667 V voice   : voice_set_parameters: exit with code(-2)
07-12 11:39:59.255   324   667 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-12 11:39:59.255   324   667 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-12 11:39:59.255   324   667 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-12 11:39:59.255   324   667 V audio_hw_primary: adev_set_parameters: exit
,07-12 11:39:59.265  1189  1189 D PanelView: There is/are notification(s) 
,07-12 11:39:59.265  1189  1189 D PhoneStatusBar: updateKeyguardPreviousState :1
07-12 11:39:59.265  1189  1189 D PhoneStatusBar: makeExpandedVisible:true
,07-12 11:39:59.265  1189  1189 D KeyguardEffectViewUtil: wallpaperType :1
07-12 11:39:59.265  1189  1189 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-12 11:39:59.265  1189  1189 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-12 11:39:59.265   924  1562 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:39:59.265   924  1562 D SecContentProvider2: mCursor = null
,07-12 11:39:59.265  1189  1189 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME recent clock search >
07-12 11:39:59.265   924  1713 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:39:59.265   924  1713 D SecContentProvider2: mCursor = null
,07-12 11:39:59.275   924  1225 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:39:59.275   924  1225 D SecContentProvider2: mCursor = null
,07-12 11:39:59.275   924  1240 D SecContentProvider2: uri = 14 selection = getSealedState
07-12 11:39:59.275   924  1240 D SecContentProvider2: mCursor = null
07-12 11:39:59.275  1189  1189 D StatusBar-DoNotDistrub: isDisableAlert isDormantModeOn:false isNotificationDisabled:true
,07-12 11:39:59.275   924   924 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-12 11:39:59.275   924   924 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-12 11:39:59.285  1189  1189 D KeyguardProperties: isIgnoreNationalRoaming() = false
,07-12 11:39:59.285  1189  1189 D PhoneStatusBar: HomeCitySettingsDialog available = false, show = true
07-12 11:39:59.285  1189  1189 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.sec.SecKeyguardCircleView$1@31ed3b16
,07-12 11:39:59.285   924  1458 E Sensors : Acc old sensor_state 513, new sensor_state : 512 en : 0
,07-12 11:39:59.285  1189  1189 D SensorManager: unregisterListener ::   
,07-12 11:39:59.295  1189  1189 D KeyguardUnlockEventHandler: cleanUp()
,07-12 11:39:59.295  1189  1189 I SecAttributionInfoView: onDetachedFromWindow
,07-12 11:39:59.295  1189  1189 V KeyguardUpdateMonitor: *** unregister callback for com.android.keyguard.KeyguardSimpleHostView$1@20eea89f
,07-12 11:39:59.295  1189  1189 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardSimpleHostView$1@ea581d9
07-12 11:39:59.295  1189  1189 V KeyguardUpdateMonitor: *** unregister callback for null
,07-12 11:39:59.305  1189  1189 D KeyguardSecurityView: AUTO_WIPE = false , IT Policy = false
07-12 11:39:59.305  1189  1189 I KeyguardSecurityView: addAttributionInfoViewIfNecessary
,07-12 11:39:59.315  1189  1189 V KeyguardSecurityView: showPrimarySecurityScreen(turningOff=false)
07-12 11:39:59.315  1189  1189 D KeyguardSecurityView: showSecurityScreen(None)
07-12 11:39:59.315  1189  1189 V KeyguardSecurityView: inflating id = 2130968634
,07-12 11:39:59.315  1189  1189 D SecKeyguardBottomAreaView: mUseBackUp= falsemUseCenteredMessageArea= false
,07-12 11:39:59.315  1189  1189 D SecKeyguardBottomAreaView: shortcut value[0-off / 1-camera] = 1
07-12 11:39:59.315  1189  1189 D SecKeyguardBottomAreaView: mKidsModeEnabled= false
,07-12 11:39:59.315   924  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
07-12 11:39:59.315   924  1058 D IpRemoteDisplayController: Bridge Server is not available
,07-12 11:39:59.325  1189  1189 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.KeyguardMessageArea$2@33e36295
07-12 11:39:59.325  1189  1189 V KeyguardUpdateMonitor: *** unregister callback for null
,07-12 11:39:59.325  1189  1189 D KeyguardUnlockView: mIsHelpTextEnabled= true
,07-12 11:39:59.325  1189  1189 D KeyguardUnlockView: hideBouncer mBouncerHelpText != null
,07-12 11:39:59.325  1189  1189 D KeyguardEffectViewUtil: wallpaperType :1
07-12 11:39:59.325  1189  1189 D StatusBar-Window: fnf=false sanc=true, kni=false, sbf=true
07-12 11:39:59.325  1189  1189 D CoverUI : applyFocusableFlag() : Remove SAMSUNG_FLAG_SVIEW_COVER
,07-12 11:39:59.325  1189  1189 V KeyguardUpdateMonitor: *** register callback for com.android.keyguard.sec.SecKeyguardCircleView$1@35ef4738
07-12 11:39:59.325  1189  1189 V KeyguardUpdateMonitor: *** unregister callback for null
,07-12 11:39:59.325  1189  1189 I SecAttributionInfoView: onAttachedToWindow
,07-12 11:39:59.335  1189  1189 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
07-12 11:39:59.335  1189  1189 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-12 11:39:59.335  1189  1189 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-12 11:39:59.335  1189  1189 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,07-12 11:39:59.335  1189  1189 D VisualEffectCircleUnlockEffect: KeyguardEffectViewNone : screenTurnedOff
07-12 11:39:59.335  1189  1189 I WaterColor Keyguard: screenTurnedOff
,07-12 11:39:59.335  1189  1539 I WaterColor_Renderer: clearEffect()
07-12 11:39:59.335  1189  1189 D SecKeyguardCircleView: onScreenTurnedOff
,07-12 11:39:59.335  1189  1539 I WaterColor_Renderer: dirty mode
07-12 11:39:59.345  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-12 11:39:59.345  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-12 11:39:59.345  1189  1189 D QSpanel : label top:23
,07-12 11:39:59.345  1189  1189 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-12 11:39:59.345  1189  1189 D QSpanel : label top:23
07-12 11:39:59.345  1189  1189 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-12 11:39:59.345  1189  1189 D QSpanel : label top:23
07-12 11:39:59.345  1189  1189 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-12 11:39:59.345  1189  1189 D QSpanel : label top:0
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:23
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:0
,07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:0
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:0
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:0
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-12 11:39:59.355  1189  1189 D QSpanel : label top:0
07-12 11:39:59.355  1189  1189 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-12 11:39:59.355  1189  1189 D ScrimController: updateScrimKeyguard() mDozing=false, mBouncerShowing=false
,07-12 11:39:59.355   924  1060 D DisplayPowerState: !@ ColorFade entry
,07-12 11:39:59.355   924  1060 D DisplayPowerController: ColorFade: onAnimationEnd
,07-12 11:39:59.355  1189  1189 D VolumePanel.09748014: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-12 11:39:59.355  1189  1189 D KeyguardViewMediator: handleKeyguardDoneDrawing
,07-12 11:39:59.375  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-12 11:39:59.375  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-12 11:39:59.375  1189  1189 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
07-12 11:39:59.375  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
07-12 11:39:59.375  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-12 11:39:59.375   924  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-12 11:39:59.375   924  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-12 11:39:59.375   924  1014 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
07-12 11:39:59.375   924  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-12 11:39:59.375   924  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-12 11:39:59.375   924  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-12 11:39:59.375   924  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-12 11:39:59.375   924  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-12 11:39:59.375   924  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-12 11:39:59.375   924  1060 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-12 11:39:59.375   924   924 V ActivityManager: Display changed displayId=0
,07-12 11:39:59.375   924   924 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
07-12 11:39:59.375   924  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-12 11:39:59.385   265   265 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6962000
07-12 11:39:59.385   265   265 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-12 11:39:59.395  1421  1421 D NativeNfcManager: power state=2
,07-12 11:39:59.395  1189  1189 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-12 11:39:59.395  1421  7519 D NfcService: call the applyRouting
,07-12 11:39:59.405  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte level=1
,07-12 11:39:59.405  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 5 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
,07-12 11:39:59.405  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-12 11:39:59.405  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-12 11:39:59.405  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-12 11:39:59.405  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-12 11:39:59.405  1805  1805 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-12 11:39:59.415   924  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@1890a2ba, r.packageName :com.google.android.gms
,07-12 11:39:59.425  1421  7519 D NfcService: index : 0
07-12 11:39:59.425  1421  7519 D NfcService: index : 1
07-12 11:39:59.425  1421  7519 D NfcService: index : 2
,07-12 11:39:59.435   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:39:59.445   924   924 W BroadcastQueue: Skipping deliver [sec] BroadcastRecord{1d06256b u-1 android.intent.action.SCREEN_OFF} to ReceiverList{115d433e 1189 com.android.systemui/10067/u0 remote:2ecb17f9}: filter unregistered
,07-12 11:39:59.455   924   940 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-12 11:39:59.455   924   941 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-12 11:39:59.455   924  1169 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-12 11:39:59.475   924  2963 D SSRM:n  : SIOP:: AP = 330, PST = 321, CUR = 450
,07-12 11:39:59.515   924  1091 D LightsService: [SvcLED]  onSensorChanged::light value = 22
,07-12 11:39:59.515   924  1091 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-12 11:39:59.525   924  1091 D SensorManager: unregisterListener ::   
,07-12 11:39:59.525   924  1091 D lights  : led_pattern : 5 +
07-12 11:39:59.525   924  1091 D lights  : led_pattern : 5 -
,07-12 11:39:59.525   924  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-12 11:39:59.645   265   265 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-12 11:39:59.645   265   505 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-12 11:39:59.655   924  1174 D SurfaceControl: Excessive delay in setPowerMode(): 274ms
07-12 11:39:59.655   924  1174 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
07-12 11:39:59.655   924  1174 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-12 11:39:59.655   924  1174 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-12 11:39:59.655   924  1174 I QCOM PowerHAL: Got set_interactive hint
,07-12 11:39:59.655   924  1060 I PowerManagerService: [PWL] Off : 0s ago
,07-12 11:39:59.655   924  1174 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 279ms
,07-12 11:39:59.985   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:40:00.935   318   318 E SMD     : DCD ON
,07-12 11:40:01.155   370   370 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-12 11:40:01.155   370   370 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-12 11:40:03.935   318   318 E SMD     : DCD ON
,07-12 11:40:04.355  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: widthSpec MeasureSpec: EXACTLY 1080 should be AT_MOST
,07-12 11:40:04.355  1189  1189 W KeyguardSecurityViewFlipper: onMeasure: heightSpec MeasureSpec: EXACTLY 1845 should be AT_MOST
,07-12 11:40:04.655   924  1060 I PowerManagerService: [PWL] Off : 5s ago
,07-12 11:40:06.945   318   318 E SMD     : DCD ON
,07-12 11:40:09.295   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:40:09.355  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:40:09.355  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:40:09.355  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-12 11:40:09.365  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:40:09.395   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:09.435   924  1240 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-12 11:40:09.435   924  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@2adfad47, r.packageName :com.google.android.gms
,07-12 11:40:09.465  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:40:09.475  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:40:09.505  1740  7532 I EventLogService: Aggregate from 1468314570715 (log), 1468314570715 (data)
,07-12 11:40:09.525   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-12 11:40:09.535   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:40:09.535   924  1018 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-12 11:40:09.535   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:40:09.535   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:40:09.545   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:40:09.545   924  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-12 11:40:09.595   924  1018 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7539 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-12 11:40:09.595  7539  7539 E Zygote  : MountEmulatedStorage()
07-12 11:40:09.595  7539  7539 I libpersona: KNOX_SDCARD checking this for 10096
07-12 11:40:09.595  7539  7539 E Zygote  : v2
07-12 11:40:09.595  7539  7539 I libpersona: KNOX_SDCARD not a persona
,07-12 11:40:09.645  7539  7539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-12 11:40:09.645  7539  7539 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-12 11:40:09.645  7539  7539 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-12 11:40:09.715  7539  7539 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-12 11:40:09.715  7539  7539 D ActivityThread: Added TimaKeyStore provider
,07-12 11:40:09.745  7539  7539 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-12 11:40:09.785   924  1660 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-12 11:40:09.785   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@2795c799, r.packageName :com.blurb.checkout
,07-12 11:40:09.895   924   941 I ActivityManager: Killing 6538:com.samsung.android.app.FileShareServer/u0a88 (adj 15): emptyCount ##41
,07-12 11:40:09.945   318   318 E SMD     : DCD ON
,07-12 11:40:10.955   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:12.275   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:40:12.945   318   318 E SMD     : DCD ON
,07-12 11:40:14.655   924  1060 I PowerManagerService: [PWL] Off : 15s ago
,07-12 11:40:15.945   318   318 E SMD     : DCD ON
,07-12 11:40:16.165   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:17.165   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:18.165   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:18.945   318   318 E SMD     : DCD ON
,07-12 11:40:19.165   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:19.405   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:19.565   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-12 11:40:20.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:21.175   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-12 11:40:21.945   318   318 E SMD     : DCD ON
,07-12 11:40:24.365   924  1342 E Watchdog: !@Sync 11
,07-12 11:40:24.945   318   318 E SMD     : DCD ON
,07-12 11:40:26.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:27.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:27.945   318   318 E SMD     : DCD ON
,07-12 11:40:28.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:29.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:29.445   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:29.615   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-12 11:40:29.665   924  1060 I PowerManagerService: [PWL] Off : 30s ago
,07-12 11:40:30.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:30.945   318   318 E SMD     : DCD ON
,07-12 11:40:30.955   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:31.175   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-12 11:40:33.945   318   318 E SMD     : DCD ON
,07-12 11:40:36.945   318   318 E SMD     : DCD ON
,07-12 11:40:39.515   924  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:39.515   924  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:40:39.515   924  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:40:39.515   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:40:39.535  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:40:39.535  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:40:39.535   924   924 I MotionRecognitionService: Plugged
,07-12 11:40:39.535   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:40:39.545   924  1458 D BatteryService: stay LED for fully charged
,07-12 11:40:39.565  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:40:39.565  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:39.575  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:39.585  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:40:39.585  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:40:39.585  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:40:39.665   924  2963 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 450
,07-12 11:40:39.955   318   318 E SMD     : DCD ON
,07-12 11:40:41.175   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:42.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:42.955   318   318 E SMD     : DCD ON
,07-12 11:40:43.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:44.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:45.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:40:45.955   318   318 E SMD     : DCD ON
,07-12 11:40:46.185   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-12 11:40:48.955   318   318 E SMD     : DCD ON
,07-12 11:40:49.575   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:40:49.665   924  1060 I PowerManagerService: [PWL] Off : 50s ago
,07-12 11:40:49.715   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 320, CUR = 450
,07-12 11:40:50.965   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:40:51.955   318   318 E SMD     : DCD ON
,07-12 11:40:54.365   924  1342 E Watchdog: !@Sync 12
,07-12 11:40:54.955   318   318 E SMD     : DCD ON
,07-12 11:40:57.955   318   318 E SMD     : DCD ON
,07-12 11:40:59.765   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 450
,07-12 11:40:59.995   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:41:00.055   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:00.955   318   318 E SMD     : DCD ON
,07-12 11:41:01.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:02.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:03.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:03.955   318   318 E SMD     : DCD ON
,07-12 11:41:04.185   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:05.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:06.195   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-12 11:41:06.955   318   318 E SMD     : DCD ON
,07-12 11:41:09.805   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 450
,07-12 11:41:09.955   318   318 E SMD     : DCD ON
,07-12 11:41:10.115   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:10.115   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:41:10.115   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:41:10.125   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:41:10.135  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:41:10.135  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:10.135   924   924 I MotionRecognitionService: Plugged
,07-12 11:41:10.135   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:41:10.145   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:41:10.165  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:41:10.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:10.185  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:41:10.185  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:41:10.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:10.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:10.965   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:12.955   318   318 E SMD     : DCD ON
,07-12 11:41:14.665   924  1060 I PowerManagerService: [PWL] Off : 75s ago
,07-12 11:41:15.955   318   318 E SMD     : DCD ON
,07-12 11:41:18.965   318   318 E SMD     : DCD ON
,07-12 11:41:19.855   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 450
,07-12 11:41:20.175   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:20.185   924  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:41:20.185   924  1521 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:41:20.185   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:41:20.195  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:41:20.195  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:20.205   924   924 I MotionRecognitionService: Plugged
,07-12 11:41:20.205   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:41:20.215   924  1521 D BatteryService: stay LED for fully charged
,07-12 11:41:20.225  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:41:20.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:20.235  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:41:20.235  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:41:20.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:20.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:21.965   318   318 E SMD     : DCD ON
,07-12 11:41:24.365   924  1342 E Watchdog: !@Sync 13
,07-12 11:41:24.965   318   318 E SMD     : DCD ON
,07-12 11:41:26.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:27.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:27.965   318   318 E SMD     : DCD ON
,07-12 11:41:28.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:29.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:29.905   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 450
,07-12 11:41:30.195   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:41:30.235   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:30.235   924  1488 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:41:30.245   924  1488 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:41:30.245   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:41:30.255  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:41:30.255  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:41:30.265   924   924 I MotionRecognitionService: Plugged
,07-12 11:41:30.265   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:41:30.275   924  1488 D BatteryService: stay LED for fully charged
,07-12 11:41:30.285  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:41:30.285  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:41:30.295  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:41:30.305  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:30.305  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:30.305  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:41:30.965   318   318 E SMD     : DCD ON
,07-12 11:41:30.965   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:31.195   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-12 11:41:33.965   318   318 E SMD     : DCD ON
,07-12 11:41:36.965   318   318 E SMD     : DCD ON
,07-12 11:41:39.955   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 450
,07-12 11:41:39.965   318   318 E SMD     : DCD ON
,07-12 11:41:40.295   924  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:42.965   318   318 E SMD     : DCD ON
,07-12 11:41:44.675   924  1060 I PowerManagerService: [PWL] Off : 105s ago
,07-12 11:41:45.965   318   318 E SMD     : DCD ON
,07-12 11:41:48.965   318   318 E SMD     : DCD ON
,07-12 11:41:49.995   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 450
,07-12 11:41:50.975   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:41:51.965   318   318 E SMD     : DCD ON
,07-12 11:41:54.375   924  1342 E Watchdog: !@Sync 14
,07-12 11:41:54.975   318   318 E SMD     : DCD ON
,07-12 11:41:56.195   370   370 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-12 11:41:56.195   370   370 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-12 11:41:57.975   318   318 E SMD     : DCD ON
,07-12 11:41:59.295   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:41:59.335   924   924 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-12 11:41:59.365   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:41:59.365  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:41:59.365  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:41:59.375  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-12 11:41:59.375  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:41:59.405   924   924 I BackgroundCompactionService: onStart. jobID=801
,07-12 11:41:59.405   924   924 I BackgroundCompactionService: onStart done. jobID=801
,07-12 11:41:59.445   924  7578 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-12 11:41:59.445   924  7578 I BackgroundCompactionService: compact_memory command done
,07-12 11:41:59.495  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:41:59.515  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:41:59.985   924  1111 V AlarmManager: waitForAlarm result :8,
,07-12 11:42:00.045   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 450
,07-12 11:42:00.975   318   318 E SMD     : DCD ON
,07-12 11:42:03.975   318   318 E SMD     : DCD ON
,07-12 11:42:06.975   318   318 E SMD     : DCD ON
,07-12 11:42:09.415   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:09.415   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:42:09.425   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:42:09.425   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:09.435  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:09.435  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:09.445   924   924 I MotionRecognitionService: Plugged
,07-12 11:42:09.445   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:42:09.445   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:42:09.465  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:42:09.485  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:09.485  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:09.485  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:09.485  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:42:09.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:09.975   318   318 E SMD     : DCD ON
,07-12 11:42:10.095   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 450
,07-12 11:42:10.975   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:12.975   318   318 E SMD     : DCD ON
,07-12 11:42:15.975   318   318 E SMD     : DCD ON
,07-12 11:42:16.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:17.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:18.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:18.975   318   318 E SMD     : DCD ON
,07-12 11:42:19.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:19.475   924  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:19.485   924  1686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:42:19.485   924  1686 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:42:19.485   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:19.495  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:19.495  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:19.505   924   924 I MotionRecognitionService: Plugged
,07-12 11:42:19.505   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:42:19.515   924  1686 D BatteryService: stay LED for fully charged
,07-12 11:42:19.525  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:42:19.535  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:19.535  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:42:19.535  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:19.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:19.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:19.675   924  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-12 11:42:20.135   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:42:20.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:21.205   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-12 11:42:21.975   318   318 E SMD     : DCD ON
,07-12 11:42:24.375   924  1342 E Watchdog: !@Sync 15
,07-12 11:42:24.975   318   318 E SMD     : DCD ON
,07-12 11:42:26.205   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:27.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:27.975   318   318 E SMD     : DCD ON
,07-12 11:42:28.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:29.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:29.535   924   941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:30.185   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:42:30.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:30.985   318   318 E SMD     : DCD ON
,07-12 11:42:30.985   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:31.215   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-12 11:42:33.985   318   318 E SMD     : DCD ON
,07-12 11:42:36.985   318   318 E SMD     : DCD ON
,07-12 11:42:39.595   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:39.985   318   318 E SMD     : DCD ON
,07-12 11:42:40.235   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:42:41.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:42.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:42.425   366   366 I bootchecker: bootchecker wake up!!
,07-12 11:42:42.985   318   318 E SMD     : DCD ON
,07-12 11:42:43.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:44.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:45.215   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:42:45.985   318   318 E SMD     : DCD ON
,07-12 11:42:46.225   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-12 11:42:48.985   318   318 E SMD     : DCD ON
,07-12 11:42:49.655   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:49.655   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:42:49.655   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:42:49.665   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:49.675  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:49.675  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:49.675   924   924 I MotionRecognitionService: Plugged
,07-12 11:42:49.685   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:42:49.685   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:42:49.705  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:42:49.715  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:49.725  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:49.725  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:42:49.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:49.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:50.285   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:42:50.985   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:42:51.985   318   318 E SMD     : DCD ON
,07-12 11:42:54.375   924  1342 E Watchdog: !@Sync 16
,07-12 11:42:54.985   318   318 E SMD     : DCD ON
,07-12 11:42:57.985   318   318 E SMD     : DCD ON
,07-12 11:42:59.685   924  1060 I PowerManagerService: [PWL] Off : 180s ago
,07-12 11:42:59.715   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:42:59.715   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:42:59.725   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:42:59.725   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:42:59.735  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:42:59.735  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:42:59.745   924   924 I MotionRecognitionService: Plugged
07-12 11:42:59.745   924   924 I MotionRecognitionService: setPowerConnected  = true
07-12 11:42:59.745   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:42:59.755  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:42:59.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:59.775  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:42:59.785  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:42:59.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:42:59.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:00.325   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:00.985   318   318 E SMD     : DCD ON
,07-12 11:43:01.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:02.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:03.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:03.995   318   318 E SMD     : DCD ON
,07-12 11:43:04.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:05.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:06.225   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-12 11:43:06.995   318   318 E SMD     : DCD ON
,07-12 11:43:09.775   924   941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:09.995   318   318 E SMD     : DCD ON
,07-12 11:43:10.375   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:10.995   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:12.995   318   318 E SMD     : DCD ON
,07-12 11:43:15.995   318   318 E SMD     : DCD ON
,07-12 11:43:18.995   318   318 E SMD     : DCD ON
,07-12 11:43:19.835   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:19.835   924  1660 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:43:19.845   924  1660 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:43:19.845   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:19.855  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:19.855  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:19.855   924   924 I MotionRecognitionService: Plugged
,07-12 11:43:19.865   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:43:19.865   924  1660 D BatteryService: stay LED for fully charged
,07-12 11:43:19.885  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:43:19.895  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:19.895  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:43:19.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:19.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:19.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:20.425   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:21.995   318   318 E SMD     : DCD ON
,07-12 11:43:24.385   924  1342 E Watchdog: !@Sync 17
,07-12 11:43:24.995   318   318 E SMD     : DCD ON
,07-12 11:43:26.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:27.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:27.995   318   318 E SMD     : DCD ON
,07-12 11:43:28.225   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:29.235   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:29.895   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:30.235   370   370 I ServiceManager: Waiting for service AtCmdFwd...
,07-12 11:43:30.475   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:30.995   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:30.995   318   318 E SMD     : DCD ON
,07-12 11:43:31.235   370   370 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-12 11:43:33.995   318   318 E SMD     : DCD ON
,07-12 11:43:36.995   318   318 E SMD     : DCD ON
,07-12 11:43:39.955   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:39.955   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:43:39.955   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:43:39.965   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:39.975  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:39.975  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:39.975   924   924 I MotionRecognitionService: Plugged
,07-12 11:43:39.975   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:43:39.985   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:43:40.005   318   318 E SMD     : DCD ON
,07-12 11:43:40.005  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:43:40.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:40.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:40.025  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:40.025  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:43:40.035  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:40.515   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:43.005   318   318 E SMD     : DCD ON
,07-12 11:43:44.685   924  1060 I PowerManagerService: [PWL] Off : 225s ago
,07-12 11:43:46.005   318   318 E SMD     : DCD ON
,07-12 11:43:49.005   318   318 E SMD     : DCD ON
,07-12 11:43:50.015   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:43:50.015   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:43:50.015   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:43:50.025   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:43:50.035   924   924 I MotionRecognitionService: Plugged
,07-12 11:43:50.035  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:43:50.035  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:43:50.045   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:43:50.045   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:43:50.075  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:43:50.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:50.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:50.085  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:43:50.085  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:43:50.095  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:43:50.565   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:43:50.995   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:43:52.005   318   318 E SMD     : DCD ON
,07-12 11:43:54.385   924  1342 E Watchdog: !@Sync 18
,07-12 11:43:55.005   318   318 E SMD     : DCD ON
,07-12 11:43:56.235   370   370 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-12 11:43:56.235   370   370 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-12 11:43:58.005   318   318 E SMD     : DCD ON
,07-12 11:44:00.065   924  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:00.605   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:01.005   318   318 E SMD     : DCD ON
,07-12 11:44:04.005   318   318 E SMD     : DCD ON
,07-12 11:44:07.005   318   318 E SMD     : DCD ON
,07-12 11:44:10.005   318   318 E SMD     : DCD ON
,07-12 11:44:10.135   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:10.135   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:44:10.135   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:44:10.145   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:44:10.145  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:44:10.155  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:44:10.155   924   924 I MotionRecognitionService: Plugged
,07-12 11:44:10.165   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:44:10.165   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:44:10.185  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:44:10.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:10.195  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:44:10.195  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:44:10.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:10.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:10.655   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:11.005   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:13.005   318   318 E SMD     : DCD ON
,07-12 11:44:16.005   318   318 E SMD     : DCD ON
,07-12 11:44:19.015   318   318 E SMD     : DCD ON
,07-12 11:44:20.195   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:20.195   924  1660 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:44:20.195   924  1660 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:44:20.205   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:44:20.215  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:44:20.215  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:44:20.215   924   924 I MotionRecognitionService: Plugged
,07-12 11:44:20.215   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:44:20.225   924  1660 D BatteryService: stay LED for fully charged
,07-12 11:44:20.235  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:44:20.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:20.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:20.245  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:44:20.245  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:44:20.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:20.705   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:21.245   370   370 I Atfwd_Daemon: Stop the daemon....
,07-12 11:44:22.015   318   318 E SMD     : DCD ON
,07-12 11:44:24.385   924  1342 E Watchdog: !@Sync 19
,07-12 11:44:25.015   318   318 E SMD     : DCD ON
,07-12 11:44:28.015   318   318 E SMD     : DCD ON
,07-12 11:44:30.255   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:30.755   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:31.005   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:31.015   318   318 E SMD     : DCD ON
,07-12 11:44:34.015   318   318 E SMD     : DCD ON
,07-12 11:44:34.685   924  1060 I PowerManagerService: [PWL] Off : 275s ago
,07-12 11:44:37.015   318   318 E SMD     : DCD ON
,07-12 11:44:40.015   318   318 E SMD     : DCD ON
,07-12 11:44:40.315   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:40.315   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:44:40.315   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:44:40.325   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:44:40.335   924   924 I MotionRecognitionService: Plugged
,07-12 11:44:40.335   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:44:40.345   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:44:40.355  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:44:40.355  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:44:40.365  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:44:40.375  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:40.385  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:40.385  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:44:40.385  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:44:40.395  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:44:40.805   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:43.015   318   318 E SMD     : DCD ON
,07-12 11:44:46.015   318   318 E SMD     : DCD ON
,07-12 11:44:49.015   318   318 E SMD     : DCD ON
,07-12 11:44:50.375   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:44:50.855   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:44:51.005   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:44:51.605   924  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:44:51.605   924  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:44:51.605   924  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:44:52.015   318   318 E SMD     : DCD ON
,07-12 11:44:54.395   924  1342 E Watchdog: !@Sync 20
,07-12 11:44:54.595   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:44:54.595   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:44:54.605   924  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:44:54.615   924  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:44:55.025   318   318 E SMD     : DCD ON
,07-12 11:44:58.025   318   318 E SMD     : DCD ON
,07-12 11:44:59.985   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:45:00.005  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-12 11:45:00.005  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:45:00.015  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-12 11:45:00.015  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:45:00.155  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:45:00.155  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:45:00.435   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:00.895   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:45:01.025   318   318 E SMD     : DCD ON
,07-12 11:45:04.025   318   318 E SMD     : DCD ON
,07-12 11:45:07.025   318   318 E SMD     : DCD ON
,07-12 11:45:10.025   318   318 E SMD     : DCD ON
,07-12 11:45:10.495   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:10.945   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:45:11.015   924  2996 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-12 11:45:13.025   318   318 E SMD     : DCD ON
,07-12 11:45:16.025   318   318 E SMD     : DCD ON
,07-12 11:45:19.025   318   318 E SMD     : DCD ON
,07-12 11:45:20.555   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:20.555   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:45:20.555   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:45:20.565   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:20.575  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:20.585  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:20.585   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:45:20.605   924   924 I MotionRecognitionService: Plugged
,07-12 11:45:20.605   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:45:20.605  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:45:20.615  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:20.625  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:20.625  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:45:20.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:20.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:20.995   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:45:22.025   318   318 E SMD     : DCD ON
,07-12 11:45:24.395   924  1342 E Watchdog: !@Sync 21
,07-12 11:45:25.025   318   318 E SMD     : DCD ON
,07-12 11:45:28.025   318   318 E SMD     : DCD ON
,07-12 11:45:29.685   924  1060 I PowerManagerService: [PWL] Off : 330s ago
,07-12 11:45:30.615   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:30.615   924  1488 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:45:30.615   924  1488 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:45:30.625   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:30.635  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:30.635  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:30.645   924  1488 D BatteryService: stay LED for fully charged
,07-12 11:45:30.655   924   924 I MotionRecognitionService: Plugged
,07-12 11:45:30.665  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:45:30.675   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:45:30.685  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:30.685  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:30.685  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:45:30.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:30.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:31.035   318   318 E SMD     : DCD ON
,07-12 11:45:31.065   924  2963 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
,07-12 11:45:34.035   318   318 E SMD     : DCD ON
,07-12 11:45:37.035   318   318 E SMD     : DCD ON
,07-12 11:45:40.035   318   318 E SMD     : DCD ON
,07-12 11:45:40.675   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:40.675   924  1595 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:45:40.675   924  1595 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:45:40.685   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:45:40.695   924   924 I MotionRecognitionService: Plugged
,07-12 11:45:40.695   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:45:40.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:45:40.705  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:45:40.705   924  1595 D BatteryService: stay LED for fully charged
,07-12 11:45:40.735  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:45:40.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:40.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:45:40.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:45:40.745  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:45:40.745  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:45:41.115   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 450
,07-12 11:45:43.035   318   318 E SMD     : DCD ON
,07-12 11:45:46.035   318   318 E SMD     : DCD ON
,07-12 11:45:49.035   318   318 E SMD     : DCD ON
,07-12 11:45:50.735   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:45:51.155   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-12 11:45:52.035   318   318 E SMD     : DCD ON
,07-12 11:45:54.395   924  1342 E Watchdog: !@Sync 22
,07-12 11:45:55.035   318   318 E SMD     : DCD ON
,07-12 11:45:58.035   318   318 E SMD     : DCD ON
,07-12 11:45:59.985   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:46:00.795   924   941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:00.795   924   941 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:46:00.795   924   941 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:46:00.805   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:00.815  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:00.815  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:00.835   924   941 D BatteryService: stay LED for fully charged
,07-12 11:46:00.835   924   924 I MotionRecognitionService: Plugged
,07-12 11:46:00.835   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:46:00.835  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:46:00.845  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:00.845  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:46:00.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:00.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:00.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:01.035   318   318 E SMD     : DCD ON
,07-12 11:46:01.215   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 450
,07-12 11:46:04.045   318   318 E SMD     : DCD ON
,07-12 11:46:07.045   318   318 E SMD     : DCD ON
,07-12 11:46:10.045   318   318 E SMD     : DCD ON
,07-12 11:46:10.855   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:10.855   924  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:46:10.855   924  1521 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:46:10.865   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:10.865  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:10.875  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:10.875   924   924 I MotionRecognitionService: Plugged
,07-12 11:46:10.885   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:46:10.885   924  1521 D BatteryService: stay LED for fully charged
,07-12 11:46:10.885  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:46:10.895  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:10.895  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:46:10.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:10.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:10.915  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:11.255   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 450
,07-12 11:46:13.045   318   318 E SMD     : DCD ON
,07-12 11:46:16.045   318   318 E SMD     : DCD ON
,07-12 11:46:19.045   318   318 E SMD     : DCD ON
,07-12 11:46:20.915   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:20.915   924  1315 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:46:20.915   924  1315 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:46:20.925   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:20.935  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:20.935  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:20.935   924   924 I MotionRecognitionService: Plugged
,07-12 11:46:20.945   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:46:20.955   924  1315 D BatteryService: stay LED for fully charged
,07-12 11:46:20.975  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:46:20.985  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:20.985  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:20.985  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:20.985  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:46:20.995  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:21.305   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 450
,07-12 11:46:22.045   318   318 E SMD     : DCD ON
,07-12 11:46:24.405   924  1342 E Watchdog: !@Sync 23
,07-12 11:46:25.045   318   318 E SMD     : DCD ON
,07-12 11:46:28.045   318   318 E SMD     : DCD ON
,07-12 11:46:29.695   924  1060 I PowerManagerService: [PWL] Off : 390s ago
,07-12 11:46:30.975   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:31.045   318   318 E SMD     : DCD ON
,07-12 11:46:31.355   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 450
,07-12 11:46:34.045   318   318 E SMD     : DCD ON
,07-12 11:46:37.045   318   318 E SMD     : DCD ON
,07-12 11:46:40.055   318   318 E SMD     : DCD ON
,07-12 11:46:41.035   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:41.035   924  1595 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:46:41.035   924  1595 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:46:41.045   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:41.055  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:41.055  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:41.065   924   924 I MotionRecognitionService: Plugged
,07-12 11:46:41.065   924  1595 D BatteryService: stay LED for fully charged
,07-12 11:46:41.085  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:46:41.085   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:46:41.095  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:41.095  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:46:41.105  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:41.105  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:41.105  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:41.415   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 450
,07-12 11:46:43.055   318   318 E SMD     : DCD ON
,07-12 11:46:46.055   318   318 E SMD     : DCD ON
,07-12 11:46:49.055   318   318 E SMD     : DCD ON
,07-12 11:46:51.095   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:46:51.095   924  1447 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:46:51.095   924  1447 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:46:51.105   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:46:51.115  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:46:51.115  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:46:51.125   924  1447 D BatteryService: stay LED for fully charged
,07-12 11:46:51.135   924   924 I MotionRecognitionService: Plugged
,07-12 11:46:51.135   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:46:51.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:46:51.145  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:46:51.145  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:46:51.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:51.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:51.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:46:51.465   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 450
,07-12 11:46:52.055   318   318 E SMD     : DCD ON
,07-12 11:46:54.405   924  1342 E Watchdog: !@Sync 24
,07-12 11:46:55.055   318   318 E SMD     : DCD ON
,07-12 11:46:58.055   318   318 E SMD     : DCD ON
,07-12 11:47:01.055   318   318 E SMD     : DCD ON
,07-12 11:47:01.155   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:01.155   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:47:01.155   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:47:01.165   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:47:01.165  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:01.175  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:01.175   924   924 I MotionRecognitionService: Plugged
,07-12 11:47:01.185   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:47:01.185   924   940 D BatteryService: stay LED for fully charged
,07-12 11:47:01.195  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:47:01.195  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:47:01.195  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:47:01.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:01.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:01.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:01.505   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 450
,07-12 11:47:04.055   318   318 E SMD     : DCD ON
,07-12 11:47:07.055   318   318 E SMD     : DCD ON
,07-12 11:47:10.055   318   318 E SMD     : DCD ON
,07-12 11:47:11.215   924  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:11.215   924  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:47:11.215   924  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:47:11.215   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:47:11.225  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:11.235  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:11.235   924   924 I MotionRecognitionService: Plugged
,07-12 11:47:11.235   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:47:11.245   924  1458 D BatteryService: stay LED for fully charged
,07-12 11:47:11.265  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:47:11.275  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:11.285  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:47:11.285  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:47:11.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:11.295  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:11.555   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:47:13.055   318   318 E SMD     : DCD ON
,07-12 11:47:16.055   318   318 E SMD     : DCD ON
,07-12 11:47:19.065   318   318 E SMD     : DCD ON
,07-12 11:47:21.275   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:21.615   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:47:22.065   318   318 E SMD     : DCD ON
,07-12 11:47:24.405   924  1342 E Watchdog: !@Sync 25
,07-12 11:47:25.065   318   318 E SMD     : DCD ON
,07-12 11:47:28.065   318   318 E SMD     : DCD ON
,07-12 11:47:31.065   318   318 E SMD     : DCD ON
,07-12 11:47:31.335   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:31.335   924  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:47:31.335   924  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:47:31.345   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:47:31.345  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:47:31.355  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:47:31.365   924   924 I MotionRecognitionService: Plugged
,07-12 11:47:31.375   924  1584 D BatteryService: stay LED for fully charged
,07-12 11:47:31.385  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:47:31.385   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:47:31.385  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:31.395  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:47:31.395  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:47:31.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:31.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:47:31.665   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:47:34.065   318   318 E SMD     : DCD ON
,07-12 11:47:34.695   924  1060 I PowerManagerService: [PWL] Off : 455s ago
,07-12 11:47:37.065   318   318 E SMD     : DCD ON
,07-12 11:47:40.065   318   318 E SMD     : DCD ON
,07-12 11:47:41.395   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:41.725   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:47:43.065   318   318 E SMD     : DCD ON
,07-12 11:47:46.065   318   318 E SMD     : DCD ON
,07-12 11:47:49.065   318   318 E SMD     : DCD ON
,07-12 11:47:51.455   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:47:51.785   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:47:52.065   318   318 E SMD     : DCD ON
,07-12 11:47:54.405   924  1342 E Watchdog: !@Sync 26
,07-12 11:47:55.075   318   318 E SMD     : DCD ON
,07-12 11:47:58.075   318   318 E SMD     : DCD ON
,07-12 11:48:01.075   318   318 E SMD     : DCD ON
,07-12 11:48:01.515   924   941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:01.845   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:04.075   318   318 E SMD     : DCD ON
,07-12 11:48:07.075   318   318 E SMD     : DCD ON
,07-12 11:48:10.075   318   318 E SMD     : DCD ON
,07-12 11:48:11.575   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:11.905   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:13.075   318   318 E SMD     : DCD ON
,07-12 11:48:16.075   318   318 E SMD     : DCD ON
,07-12 11:48:19.075   318   318 E SMD     : DCD ON
,07-12 11:48:21.635   924  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:21.635   924  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:48:21.645   924  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:48:21.645   924  1458 D BatteryService: stay LED for fully charged
,07-12 11:48:21.655   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:48:21.665  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:48:21.665  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:21.685   924   924 I MotionRecognitionService: Plugged
,07-12 11:48:21.685   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:48:21.685  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:48:21.695  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:48:21.695  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:48:21.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:21.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:21.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:21.955   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:22.075   318   318 E SMD     : DCD ON
,07-12 11:48:24.415   924  1342 E Watchdog: !@Sync 27
,07-12 11:48:25.075   318   318 E SMD     : DCD ON
,07-12 11:48:28.075   318   318 E SMD     : DCD ON
,07-12 11:48:31.085   318   318 E SMD     : DCD ON
,07-12 11:48:31.715   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:31.725   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:48:31.725   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:48:31.725   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:48:31.735  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:48:31.745  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:31.745   924   924 I MotionRecognitionService: Plugged
,07-12 11:48:31.745   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:48:31.755   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:48:31.765  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:48:31.775  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:31.775  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:31.785  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:48:31.785  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:48:31.795  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:32.005   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:34.085   318   318 E SMD     : DCD ON
,07-12 11:48:37.085   318   318 E SMD     : DCD ON
,07-12 11:48:40.085   318   318 E SMD     : DCD ON
,07-12 11:48:41.765   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:41.765   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:48:41.775   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:48:41.785   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:48:41.785   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:48:41.795  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:48:41.795  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:48:41.805   924   924 I MotionRecognitionService: Plugged
,07-12 11:48:41.815   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:48:41.825  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:48:41.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:41.835  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:48:41.835  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:48:41.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:41.855  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:48:42.065   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:43.085   318   318 E SMD     : DCD ON
,07-12 11:48:44.695   924  1060 I PowerManagerService: [PWL] Off : 525s ago
,07-12 11:48:46.085   318   318 E SMD     : DCD ON
,07-12 11:48:49.085   318   318 E SMD     : DCD ON
,07-12 11:48:51.825   924  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:48:52.085   318   318 E SMD     : DCD ON
,07-12 11:48:52.135   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:48:54.415   924  1342 E Watchdog: !@Sync 28
,07-12 11:48:55.085   318   318 E SMD     : DCD ON
,07-12 11:48:58.085   318   318 E SMD     : DCD ON
,07-12 11:49:01.085   318   318 E SMD     : DCD ON
,07-12 11:49:01.885   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:02.185   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:04.085   318   318 E SMD     : DCD ON
,07-12 11:49:07.095   318   318 E SMD     : DCD ON
,07-12 11:49:10.095   318   318 E SMD     : DCD ON
,07-12 11:49:11.945   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:12.245   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:13.095   318   318 E SMD     : DCD ON
,07-12 11:49:16.095   318   318 E SMD     : DCD ON
,07-12 11:49:19.095   318   318 E SMD     : DCD ON
,07-12 11:49:22.015   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:22.015   924  1447 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:49:22.015   924  1447 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:49:22.015   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:22.025  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:22.035  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:22.035   924   924 I MotionRecognitionService: Plugged
,07-12 11:49:22.035   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:49:22.045   924  1447 D BatteryService: stay LED for fully charged
,07-12 11:49:22.055  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:49:22.065  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:22.075  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:49:22.075  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:49:22.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:22.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:22.095   318   318 E SMD     : DCD ON
,07-12 11:49:22.295   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:24.415   924  1342 E Watchdog: !@Sync 29
,07-12 11:49:25.095   318   318 E SMD     : DCD ON
,07-12 11:49:28.095   318   318 E SMD     : DCD ON
,07-12 11:49:31.095   318   318 E SMD     : DCD ON
,07-12 11:49:32.065   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:32.065   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:49:32.075   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:49:32.075   924   940 D BatteryService: stay LED for fully charged
,07-12 11:49:32.085   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:32.095  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:32.095  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:32.105   924   924 I MotionRecognitionService: Plugged
,07-12 11:49:32.105   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:49:32.125  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:49:32.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:32.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:32.135  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:49:32.135  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:49:32.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:32.365   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:34.095   318   318 E SMD     : DCD ON
,07-12 11:49:37.095   318   318 E SMD     : DCD ON
,07-12 11:49:40.095   318   318 E SMD     : DCD ON
,07-12 11:49:42.125   924  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:42.125   924  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:49:42.125   924  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:49:42.135   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:42.145  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:42.145  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:42.155   924  1458 D BatteryService: stay LED for fully charged
,07-12 11:49:42.165   924   924 I MotionRecognitionService: Plugged
,07-12 11:49:42.175   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:49:42.185  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:49:42.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:42.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:42.195  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:49:42.195  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:49:42.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:42.425   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:43.095   318   318 E SMD     : DCD ON
,07-12 11:49:46.105   318   318 E SMD     : DCD ON
,07-12 11:49:49.105   318   318 E SMD     : DCD ON
,07-12 11:49:51.605   924  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:49:51.605   924  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:49:51.605   924  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:49:52.105   318   318 E SMD     : DCD ON
,07-12 11:49:52.185   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:49:52.195   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:49:52.195   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:49:52.195   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:49:52.205   924   924 I MotionRecognitionService: Plugged
,07-12 11:49:52.205  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:49:52.215  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:49:52.215   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:49:52.215   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:49:52.235  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:49:52.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:52.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:52.245  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:49:52.255  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:49:52.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:49:52.475   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:49:54.425   924  1342 E Watchdog: !@Sync 30
,07-12 11:49:54.625   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:49:54.625   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:49:54.635   924  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:49:54.645   924  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:49:55.105   318   318 E SMD     : DCD ON
,07-12 11:49:58.105   318   318 E SMD     : DCD ON
,07-12 11:49:59.705   924  1060 I PowerManagerService: [PWL] Off : 600s ago
,07-12 11:50:01.105   318   318 E SMD     : DCD ON
,07-12 11:50:02.235   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:02.525   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:04.105   318   318 E SMD     : DCD ON
,07-12 11:50:07.105   318   318 E SMD     : DCD ON
,07-12 11:50:10.105   318   318 E SMD     : DCD ON
,07-12 11:50:12.295   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:12.295   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:50:12.295   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:50:12.305   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:12.315  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:12.315  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:12.325   924   924 I MotionRecognitionService: Plugged
,07-12 11:50:12.325   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:50:12.335   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:50:12.335  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:50:12.345  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:12.345  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:50:12.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:12.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:12.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:12.575   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:13.105   318   318 E SMD     : DCD ON
,07-12 11:50:16.105   318   318 E SMD     : DCD ON
,07-12 11:50:19.105   318   318 E SMD     : DCD ON
,07-12 11:50:22.115   318   318 E SMD     : DCD ON
,07-12 11:50:22.355   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:22.355   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:50:22.355   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:50:22.365   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:22.375  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:22.375  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:22.375   924   924 I MotionRecognitionService: Plugged
,07-12 11:50:22.375   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:50:22.385   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:50:22.405  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:50:22.415  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:22.425  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:22.425  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:22.425  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:50:22.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:22.615   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:24.425   924  1342 E Watchdog: !@Sync 31
,07-12 11:50:25.115   318   318 E SMD     : DCD ON
,07-12 11:50:28.115   318   318 E SMD     : DCD ON
,07-12 11:50:31.115   318   318 E SMD     : DCD ON
,07-12 11:50:32.415   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:32.415   924  1660 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:50:32.415   924  1660 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:50:32.425   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:32.435  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:32.435  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:32.435   924   924 I MotionRecognitionService: Plugged
,07-12 11:50:32.435   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:50:32.445   924  1660 D BatteryService: stay LED for fully charged
,07-12 11:50:32.475  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:50:32.485  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:32.485  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:32.485  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:32.485  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:50:32.505  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:32.685   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:34.115   318   318 E SMD     : DCD ON
,07-12 11:50:37.115   318   318 E SMD     : DCD ON
,07-12 11:50:40.115   318   318 E SMD     : DCD ON
,07-12 11:50:42.475   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:42.475   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:50:42.475   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:50:42.485   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:50:42.485  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:50:42.495  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:50:42.495   924   924 I MotionRecognitionService: Plugged
,07-12 11:50:42.495   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:50:42.505   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:50:42.525  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:50:42.535  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:50:42.535  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:50:42.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:42.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:42.545  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:50:42.735   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:43.115   318   318 E SMD     : DCD ON
,07-12 11:50:46.115   318   318 E SMD     : DCD ON
,07-12 11:50:49.115   318   318 E SMD     : DCD ON
,07-12 11:50:52.115   318   318 E SMD     : DCD ON
,07-12 11:50:52.535   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:50:52.785   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:50:54.425   924  1342 E Watchdog: !@Sync 32
,07-12 11:50:55.115   318   318 E SMD     : DCD ON
,07-12 11:50:58.125   318   318 E SMD     : DCD ON
,07-12 11:51:01.125   318   318 E SMD     : DCD ON
,07-12 11:51:02.595   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:02.835   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:04.125   318   318 E SMD     : DCD ON
,07-12 11:51:07.125   318   318 E SMD     : DCD ON
,07-12 11:51:10.125   318   318 E SMD     : DCD ON
,07-12 11:51:12.655   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:12.655   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:51:12.655   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:51:12.655   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:51:12.665  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:51:12.675  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:12.675   924   924 I MotionRecognitionService: Plugged
,07-12 11:51:12.675   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:51:12.685   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:51:12.685  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:51:12.695  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:51:12.695  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:51:12.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:12.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:12.715  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:12.875   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:13.125   318   318 E SMD     : DCD ON
,07-12 11:51:16.125   318   318 E SMD     : DCD ON
,07-12 11:51:19.125   318   318 E SMD     : DCD ON
,07-12 11:51:19.705   924  1060 I PowerManagerService: [PWL] Off : 680s ago
,07-12 11:51:22.125   318   318 E SMD     : DCD ON
,07-12 11:51:22.715   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:22.715   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:51:22.715   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:51:22.725   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:51:22.725  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:51:22.735  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:22.735   924   924 I MotionRecognitionService: Plugged
,07-12 11:51:22.735   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:51:22.745   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:51:22.765  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:51:22.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:22.785  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:51:22.785  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:51:22.805  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:22.805  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:22.925   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:24.435   924  1342 E Watchdog: !@Sync 33
,07-12 11:51:25.125   318   318 E SMD     : DCD ON
,07-12 11:51:28.125   318   318 E SMD     : DCD ON
,07-12 11:51:31.125   318   318 E SMD     : DCD ON
,07-12 11:51:32.975   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:34.135   318   318 E SMD     : DCD ON
,07-12 11:51:37.135   318   318 E SMD     : DCD ON
,07-12 11:51:40.135   318   318 E SMD     : DCD ON
,07-12 11:51:40.185   924  1111 V AlarmManager: waitForAlarm result :4
,07-12 11:51:40.235   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-12 11:51:40.235   924  1447 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:51:40.235   924  1447 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:51:40.235   924  1447 D BatteryService: stay LED for fully charged
,07-12 11:51:40.235  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-12 11:51:40.235  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-12 11:51:40.245   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:51:40.245  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-12 11:51:40.245  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-12 11:51:40.265  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:51:40.265  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:51:40.275  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:51:40.275   924   924 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,07-12 11:51:40.275  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:51:40.275   924   924 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-12 11:51:40.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:40.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:40.295  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:51:40.295  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:51:40.305   924   924 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-12 11:51:40.315   924   924 I MotionRecognitionService: Plugged
07-12 11:51:40.315   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:51:40.355  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:51:40.365  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-12 11:51:40.455  1578  6908 D GCM     : Message class com.google.f.a.a.i
,07-12 11:51:40.455   924  1562 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:51:40.455   924  1595 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-12 11:51:40.665   924  1091 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-12 11:51:40.665   924  1091 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-12 11:51:40.665   924  1091 D SensorManager: unregisterListener ::   
,07-12 11:51:40.675   924  1091 D lights  : led_pattern : 5 +
,07-12 11:51:40.675   924  1091 D lights  : led_pattern : 5 -
,07-12 11:51:40.675   924  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,07-12 11:51:43.025   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:43.135   318   318 E SMD     : DCD ON
,07-12 11:51:46.135   318   318 E SMD     : DCD ON
,07-12 11:51:49.135   318   318 E SMD     : DCD ON
,07-12 11:51:50.295   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:51:52.135   318   318 E SMD     : DCD ON
,07-12 11:51:53.075   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:51:54.435   924  1342 E Watchdog: !@Sync 34
,07-12 11:51:55.135   318   318 E SMD     : DCD ON
,07-12 11:51:58.135   318   318 E SMD     : DCD ON
,07-12 11:51:59.985   924  1111 V AlarmManager: waitForAlarm result :8
,07-12 11:52:00.355   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:01.135   318   318 E SMD     : DCD ON
,07-12 11:52:03.125   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:04.135   318   318 E SMD     : DCD ON
,07-12 11:52:07.135   318   318 E SMD     : DCD ON
,07-12 11:52:10.145   318   318 E SMD     : DCD ON
,07-12 11:52:10.415   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:13.145   318   318 E SMD     : DCD ON
,07-12 11:52:13.185   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:16.145   318   318 E SMD     : DCD ON
,07-12 11:52:19.145   318   318 E SMD     : DCD ON
,07-12 11:52:20.475   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:22.145   318   318 E SMD     : DCD ON
,07-12 11:52:23.235   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:24.435   924  1342 E Watchdog: !@Sync 35
,07-12 11:52:25.145   318   318 E SMD     : DCD ON
,07-12 11:52:28.145   318   318 E SMD     : DCD ON
,07-12 11:52:30.535   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:30.535   924  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:52:30.545   924  1521 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:52:30.545   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:52:30.555   924   924 I MotionRecognitionService: Plugged
,07-12 11:52:30.555   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:52:30.565   924  1521 D BatteryService: stay LED for fully charged
,07-12 11:52:30.565  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:30.565  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:52:30.585  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:52:30.595  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:52:30.595  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:52:30.605  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:30.605  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:52:30.605  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:31.145   318   318 E SMD     : DCD ON
,07-12 11:52:33.285   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:34.145   318   318 E SMD     : DCD ON
,07-12 11:52:37.145   318   318 E SMD     : DCD ON
,07-12 11:52:40.145   318   318 E SMD     : DCD ON
,07-12 11:52:40.595   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:40.595   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:52:40.605   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:52:40.605   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:52:40.615   924   924 I MotionRecognitionService: Plugged
,07-12 11:52:40.615  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:40.615  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:52:40.625   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:52:40.625   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:52:40.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:52:40.645  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:52:40.645  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:52:40.655  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:40.655  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:40.655  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:43.145   318   318 E SMD     : DCD ON
,07-12 11:52:43.335   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:44.705   924  1060 I PowerManagerService: [PWL] Off : 765s ago
,07-12 11:52:46.155   318   318 E SMD     : DCD ON
,07-12 11:52:49.155   318   318 E SMD     : DCD ON
,07-12 11:52:50.655   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:52:50.655   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:52:50.665   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:52:50.665   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:52:50.675  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:52:50.675  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:52:50.675   924   924 I MotionRecognitionService: Plugged
,07-12 11:52:50.685   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:52:50.685   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:52:50.695  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:52:50.715  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:52:50.715  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:52:50.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:50.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:50.735  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:52:52.155   318   318 E SMD     : DCD ON
,07-12 11:52:53.375   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:52:54.445   924  1342 E Watchdog: !@Sync 36
,07-12 11:52:55.155   318   318 E SMD     : DCD ON
,07-12 11:52:58.155   318   318 E SMD     : DCD ON
,07-12 11:53:00.715   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:00.715   924  1447 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:53:00.715   924  1447 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:53:00.725   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:00.735  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:00.735  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:00.735   924   924 I MotionRecognitionService: Plugged
,07-12 11:53:00.735   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:53:00.745   924  1447 D BatteryService: stay LED for fully charged
,07-12 11:53:00.765  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:53:00.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:00.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:00.785  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:00.785  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:53:00.795  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:01.155   318   318 E SMD     : DCD ON
,07-12 11:53:03.425   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:04.155   318   318 E SMD     : DCD ON
,07-12 11:53:07.155   318   318 E SMD     : DCD ON
,07-12 11:53:10.155   318   318 E SMD     : DCD ON
,07-12 11:53:10.775   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:13.155   318   318 E SMD     : DCD ON
,07-12 11:53:13.475   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:16.155   318   318 E SMD     : DCD ON
,07-12 11:53:19.155   318   318 E SMD     : DCD ON
,07-12 11:53:20.835   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:20.835   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:53:20.835   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:53:20.845   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:20.855  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:20.855  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:20.855   924   924 I MotionRecognitionService: Plugged
,07-12 11:53:20.865   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:53:20.865   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:53:20.875  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:53:20.885  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:20.885  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:20.885  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:53:20.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:20.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:22.165   318   318 E SMD     : DCD ON
,07-12 11:53:23.515   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:24.445   924  1342 E Watchdog: !@Sync 37
,07-12 11:53:25.165   318   318 E SMD     : DCD ON
,07-12 11:53:28.165   318   318 E SMD     : DCD ON
,07-12 11:53:30.895   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:30.895   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:53:30.895   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:53:30.905   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:30.915  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:30.915  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:30.915   924   924 I MotionRecognitionService: Plugged
,07-12 11:53:30.915   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:53:30.925   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:53:30.935  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:53:30.945  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:30.945  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:53:30.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:30.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:53:30.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:31.165   318   318 E SMD     : DCD ON
,07-12 11:53:33.565   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:34.165   318   318 E SMD     : DCD ON
,07-12 11:53:37.165   318   318 E SMD     : DCD ON
,07-12 11:53:40.165   318   318 E SMD     : DCD ON
,07-12 11:53:40.955   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:40.955   924  1595 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:53:40.955   924  1595 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:53:40.965   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:40.975   924   924 I MotionRecognitionService: Plugged
,07-12 11:53:40.975  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:40.975  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:40.985   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:53:40.985   924  1595 D BatteryService: stay LED for fully charged
,07-12 11:53:41.005  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:53:41.005  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:41.015  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:41.025  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:53:41.035  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:41.035  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:43.165   318   318 E SMD     : DCD ON
,07-12 11:53:43.615   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:46.165   318   318 E SMD     : DCD ON
,07-12 11:53:49.165   318   318 E SMD     : DCD ON
,07-12 11:53:51.015   924   941 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:53:51.015   924   941 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:53:51.015   924   941 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:53:51.015   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:53:51.025  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:53:51.035  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:53:51.035   924   924 I MotionRecognitionService: Plugged
,07-12 11:53:51.035   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:53:51.045   924   941 D BatteryService: stay LED for fully charged
,07-12 11:53:51.055  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:53:51.075  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:53:51.075  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:53:51.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:51.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:51.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:53:52.165   318   318 E SMD     : DCD ON
,07-12 11:53:53.665   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:53:54.445   924  1342 E Watchdog: !@Sync 38
,07-12 11:53:55.165   318   318 E SMD     : DCD ON
,07-12 11:53:58.175   318   318 E SMD     : DCD ON
,07-12 11:54:01.075   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:01.075   924  1584 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:54:01.075   924  1584 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:54:01.085   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:54:01.095  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:54:01.095  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:54:01.095   924   924 I MotionRecognitionService: Plugged
,07-12 11:54:01.095   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:54:01.105   924  1584 D BatteryService: stay LED for fully charged
,07-12 11:54:01.125  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:54:01.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:01.135  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:54:01.135  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:54:01.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:01.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:01.175   318   318 E SMD     : DCD ON
,07-12 11:54:03.715   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:04.175   318   318 E SMD     : DCD ON
,07-12 11:54:07.175   318   318 E SMD     : DCD ON
,07-12 11:54:10.175   318   318 E SMD     : DCD ON
,07-12 11:54:11.135   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:11.135   924  1660 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:54:11.135   924  1660 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:54:11.145   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:54:11.155  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:54:11.155  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:54:11.155   924   924 I MotionRecognitionService: Plugged
,07-12 11:54:11.165   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:54:11.165   924  1660 D BatteryService: stay LED for fully charged
,07-12 11:54:11.185  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:54:11.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:11.185  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:54:11.195  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:54:11.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:11.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:13.175   318   318 E SMD     : DCD ON
,07-12 11:54:13.755   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:14.715   924  1060 I PowerManagerService: [PWL] Off : 855s ago
,07-12 11:54:16.175   318   318 E SMD     : DCD ON
,07-12 11:54:19.175   318   318 E SMD     : DCD ON
,07-12 11:54:21.195   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:21.195   924  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:54:21.195   924  1521 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:54:21.205   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:54:21.215  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:54:21.215  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:54:21.215   924   924 I MotionRecognitionService: Plugged
,07-12 11:54:21.215   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:54:21.225   924  1521 D BatteryService: stay LED for fully charged
,07-12 11:54:21.235  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:54:21.245  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:54:21.245  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:54:21.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:21.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:21.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:22.175   318   318 E SMD     : DCD ON
,07-12 11:54:23.815   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:24.455   924  1342 E Watchdog: !@Sync 39
,07-12 11:54:25.175   318   318 E SMD     : DCD ON
,07-12 11:54:28.175   318   318 E SMD     : DCD ON
,07-12 11:54:31.175   318   318 E SMD     : DCD ON
,07-12 11:54:31.255   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:31.255   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:54:31.255   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:54:31.265   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:54:31.275  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:54:31.275  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:54:31.275   924   924 I MotionRecognitionService: Plugged
,07-12 11:54:31.285   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:54:31.285   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:54:31.305  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:54:31.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:31.315  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:54:31.325  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:54:31.325  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:31.335  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:54:33.875   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:34.185   318   318 E SMD     : DCD ON
,07-12 11:54:37.185   318   318 E SMD     : DCD ON
,07-12 11:54:40.185   318   318 E SMD     : DCD ON
,07-12 11:54:41.315   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:43.185   318   318 E SMD     : DCD ON
,07-12 11:54:43.945   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:46.185   318   318 E SMD     : DCD ON
,07-12 11:54:49.185   318   318 E SMD     : DCD ON
,07-12 11:54:51.375   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:54:51.595   924  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-12 11:54:51.605   924  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-12 11:54:51.605   924  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,07-12 11:54:51.785   924   936 I art     : Background sticky concurrent mark sweep GC freed 108153(9MB) AllocSpace objects, 311(5MB) LOS objects, 17% free, 37MB/45MB, paused 2.423ms total 166.826ms
,07-12 11:54:52.185   318   318 E SMD     : DCD ON
,07-12 11:54:52.245   924  1014 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:54:52.335   924  1123 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-12 11:54:52.335   924  1123 I ApplicationUsage: Updating Usage Statistics in DB @ 1468317292352
,07-12 11:54:52.345   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.345   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.345   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.345   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.345   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.345   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.345   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
07-12 11:54:52.345   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.355   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.355   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.355   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.355   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.355   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-12 11:54:52.355   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.355   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.355   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.355   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.355   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.355   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.365   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.365   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.365   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.365   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.365   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.365   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.365   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.365   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.365   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.365   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.365   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.375   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.375   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.375   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.375   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.375   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.375   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.375   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.375   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.375   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.375   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.375   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.385   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.385   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.385   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.385   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.385   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.385   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.385   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.385   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.385   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.395   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.395   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.395   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.395   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.395   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.395   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.395   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.395   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.395   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.395   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.395   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.395   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.405   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.405   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.405   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.405   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.405   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.405   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.405   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.405   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.405   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.415   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.415   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.415   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.415   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.415   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.415   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.415   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.415   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.425   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.425   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.425   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.425   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.425   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.425   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.435   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.435   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.435   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.435   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.435   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.435   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.445   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.445   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.445   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.445   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.445   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.445   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.445   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.455   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.455   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.455   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.455   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.455   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.455   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.455   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.465   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.465   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.465   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.465   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.465   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.465   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.475   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.475   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.475   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.475   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.475   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.475   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.475   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.485   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.485   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.485   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.485   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.485   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.485   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.485   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.485   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-12 11:54:52.485   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.485   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.485   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.485   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.495   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.495   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.495   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.495   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.495   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.495   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.495   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.495   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerT,hread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	,at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134),
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304),
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	,at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253),
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: ,	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	,at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.505   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.505   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.505   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.505   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.505   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-12 11:54:52.515   924  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-12 11:54:52.515   924  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:54:52.515   924  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 11:54:52.515   924  1123 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1468317292533
,07-12 11:54:54.015   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:54:54.335   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-12 11:54:54.335   924  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-12 11:54:54.345   924  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:54:54.355   924  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-12 11:54:54.455   924  1342 E Watchdog: !@Sync 40
,07-12 11:54:55.185   318   318 E SMD     : DCD ON
,07-12 11:54:58.185   318   318 E SMD     : DCD ON
,07-12 11:55:01.185   318   318 E SMD     : DCD ON
,07-12 11:55:01.435   924  1584 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:04.075   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:04.185   318   318 E SMD     : DCD ON
,07-12 11:55:07.185   318   318 E SMD     : DCD ON
,07-12 11:55:10.185   318   318 E SMD     : DCD ON
,07-12 11:55:11.495   924  1315 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:13.195   318   318 E SMD     : DCD ON
,07-12 11:55:14.115   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:16.195   318   318 E SMD     : DCD ON
,07-12 11:55:19.195   318   318 E SMD     : DCD ON
,07-12 11:55:21.555   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:21.555   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:55:21.555   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:55:21.565   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:55:21.565  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:55:21.575  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:55:21.575   924   924 I MotionRecognitionService: Plugged
,07-12 11:55:21.585   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:55:21.585   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:55:21.605  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:55:21.605  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:21.605  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:55:21.615  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:55:21.625  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:21.625  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:22.195   318   318 E SMD     : DCD ON
,07-12 11:55:24.165   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:24.455   924  1342 E Watchdog: !@Sync 41
,07-12 11:55:25.195   318   318 E SMD     : DCD ON
,07-12 11:55:28.195   318   318 E SMD     : DCD ON
,07-12 11:55:31.195   318   318 E SMD     : DCD ON
,07-12 11:55:31.615   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:34.195   318   318 E SMD     : DCD ON
,07-12 11:55:34.245   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:37.195   318   318 E SMD     : DCD ON
,07-12 11:55:40.195   318   318 E SMD     : DCD ON
,07-12 11:55:41.675   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:41.675   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:55:41.675   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:55:41.685   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:55:41.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:55:41.695  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:55:41.695   924   924 I MotionRecognitionService: Plugged
,07-12 11:55:41.695   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:55:41.705   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:55:41.715  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:55:41.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:41.735  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:55:41.745  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:55:41.745  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:41.755  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:55:43.195   318   318 E SMD     : DCD ON
,07-12 11:55:44.285   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:46.205   318   318 E SMD     : DCD ON
,07-12 11:55:49.205   318   318 E SMD     : DCD ON
,07-12 11:55:49.715   924  1060 I PowerManagerService: [PWL] Off : 950s ago
,07-12 11:55:51.735   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:55:52.205   318   318 E SMD     : DCD ON
,07-12 11:55:54.335   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:55:54.465   924  1342 E Watchdog: !@Sync 42
,07-12 11:55:55.205   318   318 E SMD     : DCD ON
,07-12 11:55:58.205   318   318 E SMD     : DCD ON
,07-12 11:56:01.205   318   318 E SMD     : DCD ON
,07-12 11:56:01.815   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:01.815   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-12 11:56:01.815   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-12 11:56:01.815   924   940 D BatteryService: stay LED for fully charged
,07-12 11:56:01.815   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:56:01.815  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:56:01.815  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-12 11:56:01.815   924   924 I MotionRecognitionService: Plugged
,07-12 11:56:01.815   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:56:01.825  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:56:01.825  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:56:01.825  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:56:01.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:01.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:01.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:04.205   318   318 E SMD     : DCD ON
,07-12 11:56:04.385   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:07.205   318   318 E SMD     : DCD ON
,07-12 11:56:10.205   318   318 E SMD     : DCD ON
,07-12 11:56:11.875   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:13.205   318   318 E SMD     : DCD ON
,07-12 11:56:14.425   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:16.205   318   318 E SMD     : DCD ON
,07-12 11:56:19.205   318   318 E SMD     : DCD ON
,07-12 11:56:21.935   924  1660 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:22.205   318   318 E SMD     : DCD ON
,07-12 11:56:24.465   924  1342 E Watchdog: !@Sync 43
,07-12 11:56:24.475   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:25.215   318   318 E SMD     : DCD ON
,07-12 11:56:28.215   318   318 E SMD     : DCD ON
,07-12 11:56:31.215   318   318 E SMD     : DCD ON
,07-12 11:56:31.995   924  1686 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:31.995   924  1686 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:56:31.995   924  1686 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:56:32.005   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:56:32.015  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:56:32.015  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:56:32.015   924   924 I MotionRecognitionService: Plugged
,07-12 11:56:32.025   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:56:32.025   924  1686 D BatteryService: stay LED for fully charged
,07-12 11:56:32.045  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:56:32.055  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:32.055  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:32.055  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:56:32.055  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:56:32.065  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:56:34.215   318   318 E SMD     : DCD ON
,07-12 11:56:34.575   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:37.215   318   318 E SMD     : DCD ON
,07-12 11:56:40.215   318   318 E SMD     : DCD ON
,07-12 11:56:42.055   924  1488 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:43.215   318   318 E SMD     : DCD ON
,07-12 11:56:44.645   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:46.215   318   318 E SMD     : DCD ON
,07-12 11:56:49.215   318   318 E SMD     : DCD ON
,07-12 11:56:52.115   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:56:52.215   318   318 E SMD     : DCD ON
,07-12 11:56:54.465   924  1342 E Watchdog: !@Sync 44
,07-12 11:56:54.695   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:56:55.215   318   318 E SMD     : DCD ON
,07-12 11:56:58.215   318   318 E SMD     : DCD ON
,07-12 11:57:01.225   318   318 E SMD     : DCD ON
,07-12 11:57:02.175   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:02.175   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:57:02.175   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:57:02.185   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:02.195  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:02.195  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:02.195   924   924 I MotionRecognitionService: Plugged
,07-12 11:57:02.205   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:57:02.205   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:57:02.225  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:57:02.225  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:02.235  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:57:02.235  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:57:02.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:02.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:04.225   318   318 E SMD     : DCD ON
,07-12 11:57:04.745   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:07.225   318   318 E SMD     : DCD ON
,07-12 11:57:10.225   318   318 E SMD     : DCD ON
,07-12 11:57:12.235   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:13.225   318   318 E SMD     : DCD ON
,07-12 11:57:14.785   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:16.225   318   318 E SMD     : DCD ON
,07-12 11:57:19.225   318   318 E SMD     : DCD ON
,07-12 11:57:22.225   318   318 E SMD     : DCD ON
,07-12 11:57:22.295   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:22.295   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:57:22.295   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:57:22.305   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:22.315  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:22.315  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:22.315   924   924 I MotionRecognitionService: Plugged
,07-12 11:57:22.325   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:57:22.325   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:57:22.345  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:57:22.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:22.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:22.355  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:57:22.355  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:57:22.375  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:24.475   924  1342 E Watchdog: !@Sync 45
,07-12 11:57:24.835   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:25.225   318   318 E SMD     : DCD ON
,07-12 11:57:28.225   318   318 E SMD     : DCD ON
,07-12 11:57:29.715   924  1060 I PowerManagerService: [PWL] Off : 1050s ago
,07-12 11:57:31.225   318   318 E SMD     : DCD ON
,07-12 11:57:32.355   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:32.355   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:57:32.355   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:57:32.365   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:32.375  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:32.375  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:32.375   924   924 I MotionRecognitionService: Plugged
,07-12 11:57:32.385   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:57:32.395   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:57:32.405  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:57:32.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:32.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:32.415  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:57:32.415  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:57:32.425  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:34.225   318   318 E SMD     : DCD ON
,07-12 11:57:34.885   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:37.235   318   318 E SMD     : DCD ON
,07-12 11:57:40.235   318   318 E SMD     : DCD ON
,07-12 11:57:42.415   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:42.415   924  1225 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:57:42.415   924  1225 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:57:42.425   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:57:42.425  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:57:42.435  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:57:42.435   924   924 I MotionRecognitionService: Plugged
,07-12 11:57:42.445   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:57:42.445   924  1225 D BatteryService: stay LED for fully charged
,07-12 11:57:42.455  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:57:42.465  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:57:42.465  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:57:42.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:42.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:42.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:57:43.235   318   318 E SMD     : DCD ON
,07-12 11:57:44.935   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:46.235   318   318 E SMD     : DCD ON
,07-12 11:57:49.235   318   318 E SMD     : DCD ON
,07-12 11:57:52.235   318   318 E SMD     : DCD ON
,07-12 11:57:52.475   924  1595 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:57:54.475   924  1342 E Watchdog: !@Sync 46
,07-12 11:57:54.975   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:57:55.235   318   318 E SMD     : DCD ON
,07-12 11:57:58.235   318   318 E SMD     : DCD ON
,07-12 11:58:01.235   318   318 E SMD     : DCD ON
,07-12 11:58:02.535   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:04.235   318   318 E SMD     : DCD ON
,07-12 11:58:05.025   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:07.235   318   318 E SMD     : DCD ON
,07-12 11:58:10.235   318   318 E SMD     : DCD ON
,07-12 11:58:12.595   924   940 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:12.595   924   940 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:58:12.595   924   940 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:58:12.605   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:58:12.615  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:58:12.615  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:58:12.615   924   924 I MotionRecognitionService: Plugged
,07-12 11:58:12.625   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:58:12.635   924   940 D BatteryService: stay LED for fully charged
,07-12 11:58:12.645  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:58:12.655  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:12.655  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:58:12.655  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:58:12.675  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:12.675  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:13.235   318   318 E SMD     : DCD ON
,07-12 11:58:15.075   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:16.245   318   318 E SMD     : DCD ON
,07-12 11:58:19.245   318   318 E SMD     : DCD ON
,07-12 11:58:22.245   318   318 E SMD     : DCD ON
,07-12 11:58:22.655   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:22.655   924  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:58:22.655   924  1240 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:58:22.665   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:58:22.675  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:58:22.675  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:58:22.675   924   924 I MotionRecognitionService: Plugged
,07-12 11:58:22.685   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:58:22.685   924  1240 D BatteryService: stay LED for fully charged
,07-12 11:58:22.705  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:58:22.705  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:58:22.705  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:58:22.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:22.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:22.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:24.475   924  1342 E Watchdog: !@Sync 47
,07-12 11:58:25.115   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:25.245   318   318 E SMD     : DCD ON
,07-12 11:58:28.245   318   318 E SMD     : DCD ON
,07-12 11:58:31.245   318   318 E SMD     : DCD ON
,07-12 11:58:32.715   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:32.715   924  1562 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:58:32.715   924  1562 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:58:32.725   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:58:32.735  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:58:32.735  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:58:32.735   924   924 I MotionRecognitionService: Plugged
,07-12 11:58:32.745   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:58:32.745   924  1562 D BatteryService: stay LED for fully charged
,07-12 11:58:32.755  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:58:32.765  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:58:32.765  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:58:32.775  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:32.775  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:32.775  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:58:34.245   318   318 E SMD     : DCD ON
,07-12 11:58:35.165   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:37.245   318   318 E SMD     : DCD ON
,07-12 11:58:40.245   318   318 E SMD     : DCD ON
,07-12 11:58:42.775   924  1225 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:43.245   318   318 E SMD     : DCD ON
,07-12 11:58:45.235   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:46.245   318   318 E SMD     : DCD ON
,07-12 11:58:49.245   318   318 E SMD     : DCD ON
,07-12 11:58:52.255   318   318 E SMD     : DCD ON
,07-12 11:58:52.835   924  1562 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:58:54.475   924  1342 E Watchdog: !@Sync 48
,07-12 11:58:55.255   318   318 E SMD     : DCD ON
,07-12 11:58:55.295   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:58:58.255   318   318 E SMD     : DCD ON
,07-12 11:59:01.255   318   318 E SMD     : DCD ON
,07-12 11:59:02.895   924  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:02.895   924  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:59:02.895   924  1521 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:59:02.905   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:59:02.915  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:59:02.915  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:59:02.925   924   924 I MotionRecognitionService: Plugged
,07-12 11:59:02.925   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:59:02.925   924  1521 D BatteryService: stay LED for fully charged
,07-12 11:59:02.945  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:59:02.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:02.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:02.955  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:59:02.955  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:59:02.975  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:04.255   318   318 E SMD     : DCD ON
,07-12 11:59:05.345   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:59:07.255   318   318 E SMD     : DCD ON
,07-12 11:59:10.255   318   318 E SMD     : DCD ON
,07-12 11:59:12.955   924  1713 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:12.955   924  1713 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:59:12.955   924  1713 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:59:12.965   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:59:12.975  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:59:12.975  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:59:12.975   924   924 I MotionRecognitionService: Plugged
,07-12 11:59:12.985   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:59:12.985   924  1713 D BatteryService: stay LED for fully charged
,07-12 11:59:13.005  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:59:13.005  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:59:13.005  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:59:13.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:13.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:59:13.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:13.255   318   318 E SMD     : DCD ON
,07-12 11:59:14.715   924  1060 I PowerManagerService: [PWL] Off : 1155s ago
,07-12 11:59:15.395   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:59:16.255   318   318 E SMD     : DCD ON
,07-12 11:59:19.255   318   318 E SMD     : DCD ON
,07-12 11:59:22.255   318   318 E SMD     : DCD ON
,07-12 11:59:23.015   924  3435 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:23.015   924  3435 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-12 11:59:23.015   924  3435 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-12 11:59:23.025   924   924 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-12 11:59:23.035  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-12 11:59:23.035  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-12 11:59:23.045   924   924 I MotionRecognitionService: Plugged
,07-12 11:59:23.045   924   924 I MotionRecognitionService: setPowerConnected  = true
,07-12 11:59:23.045   924  3435 D BatteryService: stay LED for fully charged
,07-12 11:59:23.055  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-12 11:59:23.065  2898  2898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-12 11:59:23.065  2898  6586 D HeadsetStateMachine: Disconnected process message: 10
,07-12 11:59:23.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:23.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-12 11:59:23.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-12 11:59:24.485   924  1342 E Watchdog: !@Sync 49
,07-12 11:59:25.255   318   318 E SMD     : DCD ON
,07-12 11:59:25.435   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:59:28.265   318   318 E SMD     : DCD ON
,07-12 11:59:31.265   318   318 E SMD     : DCD ON
,07-12 11:59:33.075   924  1447 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:34.265   318   318 E SMD     : DCD ON
,07-12 11:59:35.485   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:59:37.265   318   318 E SMD     : DCD ON
,07-12 11:59:40.265   318   318 E SMD     : DCD ON
,07-12 11:59:43.135   924  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-12 11:59:43.265   318   318 E SMD     : DCD ON
,07-12 11:59:45.545   924  2963 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 450
,07-12 11:59:46.265   318   318 E SMD     : DCD ON
,07-12 11:59:49.265   318   318 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-12 11:59:50.995  7661  7661 D AndroidRuntime: 
07-12 11:59:50.995  7661  7661 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-12 11:59:50.995  7661  7661 D AndroidRuntime: CheckJNI is OFF
07-12 11:59:50.995  7661  7661 D AndroidRuntime: readGMSProperty: start
07-12 11:59:50.995  7661  7661 D AndroidRuntime: readGMSProperty: already setted!!
07-12 11:59:50.995  7661  7661 D AndroidRuntime: readGMSProperty: end
07-12 11:59:50.995  7661  7661 D AndroidRuntime: addProductProperty: start
07-12 11:59:51.225  7661  7661 E AffinityControl: AffinityControl: registerfunction enter
07-12 11:59:51.255  7661  7661 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 11:59:51.275   924  1660 D PackageManager: START PACKAGE DELETE: observer{467943123}
07-12 11:59:51.275   924  1660 D PackageManager: pkg{<packageName>}
07-12 11:59:51.275   924  1660 D PackageManager: user{0}
07-12 11:59:51.275   924  1660 D PackageManager: caller{2000}
07-12 11:59:51.275   924  1660 D PackageManager: flags{2}
07-12 11:59:51.275   924  1660 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-12 11:59:51.275   924  1660 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-12 11:59:51.275   924  1660 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-12 11:59:51.275   924  1660 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 11:59:51.275   924  1660 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-12 11:59:51.285   924  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-12 11:59:51.285   924  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-12 11:59:51.285   924  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-12 11:59:51.285   924  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-12 11:59:51.285   924  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-12 11:59:51.285   924  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-12 11:59:51.285   924  1018 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-12 11:59:51.285   924  1018 I ActivityManager: Killing 6410:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-12 11:59:51.285   924  1018 I ActivityManager:   Force finishing activity ActivityRecord{4b34c81 u0 com.test.thalitest/.MainActivity t36}
07-12 11:59:51.295   924  1018 D FocusedStackFrame: Set to : 0
07-12 11:59:51.295   265   304 I SurfaceFlinger: id=11 Removed NainActivit (6/8)
07-12 11:59:51.295   265   985 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
07-12 11:59:51.305   924  2963 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:59:51.505   924  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-12 11:59:51.575   924  3212 E libprocessgroup: failed to kill 1 processes for processgroup 6410
07-12 11:59:51.575  1515  1515 I art     : Explicit concurrent mark sweep GC freed 11011(665KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/32MB, paused 702us total 55.170ms
07-12 11:59:51.585   924  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-12 11:59:51.585  5326  5326 I art     : Explicit concurrent mark sweep GC freed 35366(1936KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 560us total 52.304ms
07-12 11:59:51.595   924  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 11:59:51.595  1480  1841 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 11:59:51.595   924  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
07-12 11:59:51.595   924  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-12 11:59:51.605   924  1099 D TimaService: TimaServiceHandler.handleMessage what =1
07-12 11:59:51.605  1421  1421 D RegisteredServicesCache: empty dynamic service
07-12 11:59:51.605  1766  1766 E SamsungIME: mOCRHelper is null
07-12 11:59:51.605  3975  3975 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-12 11:59:51.625  4983  4983 I art     : Explicit concurrent mark sweep GC freed 5031(363KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 319us total 79.022ms
07-12 11:59:51.635  3975  3975 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1468317591644
07-12 11:59:51.635  3975  3975 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-12 11:59:51.645   924  1143 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-12 11:59:51.645   924  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:59:51.645   924  1143 V NetworkStats: performPollLocked(flags=0x3)
07-12 11:59:51.645   924  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-12 11:59:51.645   924  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:59:51.645  3975  3975 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-12 11:59:51.645   924  1143 V NetworkStats: performPollLocked() took 5ms
07-12 11:59:51.645   924  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:59:51.695   924  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:59:51.695   924  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-12 11:59:51.705   924   924 I art     : Explicit concurrent mark sweep GC freed 61273(4MB) AllocSpace objects, 100(1601KB) LOS objects, 30% free, 36MB/52MB, paused 4.801ms total 176.919ms
07-12 11:59:51.705   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-12 11:59:51.715   924  1064 I art     : WaitForGcToComplete blocked for 70.705ms for cause Explicit
07-12 11:59:51.725   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-12 11:59:51.745   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-12 11:59:51.755   924  1488 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-12 11:59:51.755   924  1488 D SecContentProvider2: mCursor = null
07-12 11:59:51.755   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-12 11:59:51.765   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-12 11:59:51.775   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-12 11:59:51.795   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-12 11:59:51.805   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-12 11:59:51.805  3975  3975 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-12 11:59:51.805   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-12 11:59:51.815  3975  3975 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-12 11:59:51.815   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-12 11:59:51.825   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-12 11:59:51.825   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-12 11:59:51.835  7317  7317 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-12 11:59:51.835   924  3435 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-12 11:59:51.835   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@1dad7fe9, r.packageName :com.sec.esdk.elm
07-12 11:59:51.845  7317  7317 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-12 11:59:51.845  3466  3466 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-12 11:59:51.845   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-12 11:59:51.845  7317  7317 D elm:14491: ElmAgentService : onCreate()
07-12 11:59:51.845  7317  7690 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-12 11:59:51.845  7317  7690 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-12 11:59:51.845  7317  7690 D elm:14491: MDMBridge.getInstance()
07-12 11:59:51.845  3466  3466 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-12 11:59:51.845  7317  7690 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-12 11:59:51.845   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-12 11:59:51.845  3466  3466 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-12 11:59:51.845  3466  3466 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-12 11:59:51.855  3466  3466 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-12 11:59:51.855  3466  3466 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:59:51.855  3466  3466 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:59:51.855  7317  7690 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-12 11:59:51.855  3466  3466 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-12 11:59:51.855  3466  3466 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-12 11:59:51.855   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-12 11:59:51.855   924   924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-12 11:59:51.855   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-12 11:59:51.855  7317  7317 D elm:14491: ElmAgentService : onDestroy().
07-12 11:59:51.855   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-12 11:59:51.865   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-12 11:59:51.865   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-12 11:59:51.865   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-12 11:59:51.865  1578  1578 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-12 11:59:51.875  1578  1578 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
07-12 11:59:51.875   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-12 11:59:51.875   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-12 11:59:51.875   924  1488 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-12 11:59:51.885   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-12 11:59:51.885   924  3435 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-12 11:59:51.885   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@38206685, r.packageName :com.google.android.gms
07-12 11:59:51.895   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-12 11:59:51.895  1740  7692 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
07-12 11:59:51.895   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-12 11:59:51.905  1740  1740 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-12 11:59:51.905  1740  7692 D AccountUtils: Clearing selected account for com.test.thalitest
07-12 11:59:51.905  1740  1740 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-12 11:59:51.905  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 11:59:51.905  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-12 11:59:51.905   924   924 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-12 11:59:51.905   924   924 D RCPManagerService: PackageReceiver onReceive()
07-12 11:59:51.905   924   924 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-12 11:59:51.905   924  3435 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b66902c, r.packageName :com.google.android.gms
07-12 11:59:51.915   924   924 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-12 11:59:51.915   924   924 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 11:59:51.915   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicy: uID is 10079
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicy: Removed Packageuid is0
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-12 11:59:51.915   924   924 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-12 11:59:51.915  1740  1740 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-12 11:59:51.915  1740  1740 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
07-12 11:59:51.915  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-12 11:59:51.915  1740  1740 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-12 11:59:51.915   924  2963 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-12 11:59:51.915   924  1176 D TaskPersister: removeObsoleteFile: deleting file=36_task.xml
07-12 11:59:51.915   924   924 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-12 11:59:51.935   924  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@22c28318, r.packageName :com.google.android.gms
07-12 11:59:51.945   924  1713 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:51.945   924  1713 D ActivityManager: caller:android.app.ApplicationThreadProxy@3db04b56, r.packageName :com.google.android.gms
07-12 11:59:51.945  1740  7692 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-12 11:59:51.945   924  1240 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
07-12 11:59:51.955   924  1660 D ActivityManager: caller:android.app.ApplicationThreadProxy@659bda9, r.packageName :com.google.android.gms
07-12 11:59:51.955   924  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:51.955   924  1488 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b48acf, r.packageName :com.google.android.gms
07-12 11:59:51.975   924  1225 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
07-12 11:59:51.975   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:51.975   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:51.975   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:51.975   924  1225 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:52.025  7699  7699 E Zygote  : MountEmulatedStorage()
07-12 11:59:52.025  7699  7699 E Zygote  : v2
07-12 11:59:52.025  7699  7699 I libpersona: KNOX_SDCARD checking this for 10021
07-12 11:59:52.025  7699  7699 I libpersona: KNOX_SDCARD not a persona
07-12 11:59:52.025  1740  7698 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-12 11:59:52.025  1740  7698 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
07-12 11:59:52.025  1740  7698 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-12 11:59:52.035  1740  7698 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
07-12 11:59:52.035   924  1225 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7699 uid=10021 gids={50021, 9997} abi=armeabi-v7a
07-12 11:59:52.045  1740  7698 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-12 11:59:52.045  1740  7698 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
07-12 11:59:52.045  1740  7698 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
07-12 11:59:52.045   924  1064 I art     : Explicit concurrent mark sweep GC freed 19841(1138KB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 2.929ms total 336.326ms
07-12 11:59:52.055  7699  7699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:59:52.055  7699  7699 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:59:52.055  7699  7699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 11:59:52.055  1740  7698 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-12 11:59:52.055  1740  7698 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
07-12 11:59:52.055  1740  7698 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-12 11:59:52.065   924  1562 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:52.065   924  1562 D ActivityManager: caller:android.app.ApplicationThreadProxy@371904eb, r.packageName :com.google.android.gms
07-12 11:59:52.085   924  1521 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:52.085   924  1521 D ActivityManager: caller:android.app.ApplicationThreadProxy@514c21d, r.packageName :com.google.android.gms
07-12 11:59:52.085  1578  1578 I ConfigService: onCreate
07-12 11:59:52.085  7699  7699 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:59:52.085  1578  1578 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-12 11:59:52.085  7699  7699 D ActivityThread: Added TimaKeyStore provider
07-12 11:59:52.095   924   941 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:52.095   924   941 D ActivityManager: caller:android.app.ApplicationThreadProxy@d71ffde, r.packageName :com.google.android.gms
07-12 11:59:52.095  1740  1740 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-12 11:59:52.095  1578  1578 I ConfigService: onBind returning update interface
07-12 11:59:52.105  1578  1578 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-12 11:59:52.105  1578  1578 I ConfigService: onBind returning service broker
07-12 11:59:52.105   924  1713 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:52.105   924  1713 D ActivityManager: caller:android.app.ApplicationThreadProxy@1205948c, r.packageName :com.google.android.gms
07-12 11:59:52.115   924  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-12 11:59:52.115   924  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c1a3bea, r.packageName :com.google.android.gms
07-12 11:59:52.115  1740  7705 W BaseAppContext: Using Auth Proxy for data requests.
07-12 11:59:52.115  1740  7716 I PeopleContactsSync: CP2 sync disabled
07-12 11:59:52.115  7699  7699 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
07-12 11:59:52.115  1740  3880 I Icing   : doRemovePackageData com.test.thalitest
07-12 11:59:52.125  1459  1459 D SurfaceWidgetView: destroyHardwareResources():257142304
07-12 11:59:52.125  1740  7705 W BaseAppContext: Using Auth Proxy for data requests.
07-12 11:59:52.125  1459  1459 D Launcher: onRestart, Launcher: 482857736
07-12 11:59:52.125  1459  1459 D Launcher: onStart, Launcher: 482857736
07-12 11:59:52.125  1459  1459 D Launcher.HomeView: onStart
07-12 11:59:52.125  1805  6426 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-12 11:59:52.125  1805  1963 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-12 11:59:52.125  1805  1963 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-12 11:59:52.125  1459  1459 V ActivityThread: updateVisibility : ActivityRecord{2736e940 token=android.os.BinderProxy@70c4392 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-12 11:59:52.145   265   265 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
07-12 11:59:52.155  7699  7699 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-12 11:59:52.155  7699  7699 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-12 11:59:52.155  7699  7699 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-12 11:59:52.155   924   941 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
07-12 11:59:52.155   924   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:52.155   924   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:52.155   924   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:52.155   924   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-12 11:59:52.185  1578  1604 I art     : Explicit concurrent mark sweep GC freed 13395(811KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/31MB, paused 443us total 36.342ms
07-12 11:59:52.205  7720  7720 E Zygote  : MountEmulatedStorage()
07-12 11:59:52.205  7720  7720 E Zygote  : v2
07-12 11:59:52.205  7720  7720 I libpersona: KNOX_SDCARD checking this for 10025
07-12 11:59:52.205  7720  7720 I libpersona: KNOX_SDCARD not a persona
07-12 11:59:52.205   924   941 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7720 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
07-12 11:59:52.215   924  1064 D PackageManager: delete codoeFile: 
07-12 11:59:52.215   924  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-12 11:59:52.215   924  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-12 11:59:52.215   924  1064 D PackageManager: result of delete: 1{467943123}
07-12 11:59:52.225   351   351 I art     : Explicit concurrent mark sweep GC freed 8718(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 313us total 14.468ms
07-12 11:59:52.235  7720  7720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-12 11:59:52.235  7720  7720 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-12 11:59:52.235   924  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2419550d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t35} time:1516640
07-12 11:59:52.235  7720  7720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-12 11:59:52.235   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 10.095ms
07-12 11:59:52.235  7661  7661 D AndroidRuntime: Shutting down VM
07-12 11:59:52.235   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-12 11:59:52.245   351   351 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 10.610ms
07-12 11:59:52.255   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-12 11:59:52.255  7720  7720 D TimaKeyStoreProvider: TimaSignature is unavailable
07-12 11:59:52.255  7720  7720 D ActivityThread: Added TimaKeyStore provider
07-12 11:59:52.265  7720  7720 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
07-12 11:59:52.265   318   318 E SMD     : DCD ON
07-12 11:59:52.275  7720  7720 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:59:52.275   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-12 11:59:52.275   924  1014 D EnterpriseDeviceManagerService: Package has changed for user 0
07-12 11:59:52.275   924  1014 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-12 11:59:52.285   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-12 11:59:52.295   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
07-12 11:59:52.295  7720  7720 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
07-12 11:59:52.295   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.295   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-12 11:59:52.295  7720  7720 D MVFD_interface: <<<  caMVFace_FaceInit
07-12 11:59:52.305   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-12 11:59:52.305   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-12 11:59:52.315   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.315   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-12 11:59:52.315   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-12 11:59:52.325   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.325   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
07-12 11:59:52.325   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.325   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
07-12 11:59:52.325   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.325   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.325   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-12 11:59:52.335   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.335   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-12 11:59:52.335   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-12 11:59:52.335   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
07-12 11:59:52.335   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:59:52.345  7720  7720 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
07-12 11:59:52.345   264   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
07-12 11:59:52.345   264   541 W Vold    : Returning OperationFailed - no handler for errno 0
07-12 11:59:52.345  7720  7720 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
07-12 11:59:52.345   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-12 11:59:52.355   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
07-12 11:59:52.355   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.355   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-12 11:59:52.355   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-12 11:59:52.365   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
07-12 11:59:52.375   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-12 11:59:52.385   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.385   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.385   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
07-12 11:59:52.385   924  1014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-12 11:59:52.385   924  1014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-12 11:59:52.385   924  1014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-12 11:59:52.385   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.385   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-12 11:59:52.395   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.395   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
07-12 11:59:52.395  1740  7697 W DriveInitializer: Awaiting to be initialized
07-12 11:59:52.395  1740  7746 W DriveInitializer: Background init thread started
07-12 11:59:52.395   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.395   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-12 11:59:52.405   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.405   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:59:52.405   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
07-12 11:59:52.405   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.405   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-12 11:59:52.405   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.405   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:59:52.405   924  1014 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
07-12 11:59:52.415   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.415   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-12 11:59:52.415   924  1014 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-12 11:59:52.415   924  1014 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-12 11:59:52.415   924  1014 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-12 11:59:52.415   924  1014 I CrashAnrDetector: onPackageRemoved : com.test.thalitest

```
