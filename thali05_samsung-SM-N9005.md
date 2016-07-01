#### Test 757892686fd65a6_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-01 09:01:04.558   296   296 E SMD     : DCD ON
,07-01 09:01:05.508  7608  7608 D AndroidRuntime: 
07-01 09:01:05.508  7608  7608 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-01 09:01:05.518  7608  7608 D AndroidRuntime: CheckJNI is OFF
07-01 09:01:05.518  7608  7608 D AndroidRuntime: readGMSProperty: start
07-01 09:01:05.518  7608  7608 D AndroidRuntime: readGMSProperty: already setted!!
07-01 09:01:05.518  7608  7608 D AndroidRuntime: readGMSProperty: end
07-01 09:01:05.518  7608  7608 D AndroidRuntime: addProductProperty: start
07-01 09:01:05.648  7608  7608 E AffinityControl: AffinityControl: registerfunction enter
07-01 09:01:05.668  7608  7608 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-01 09:01:05.678   764  1740 E PersonaManagerService: inState():  stateMachine is null !!
07-01 09:01:05.678   764  1740 I PersonaManagerService: PersonaId don't exist
07-01 09:01:05.678   764  1740 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-01 09:01:05.678   764  1740 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-01 09:01:05.678   764  1740 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 09:01:05.678   764  1740 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-01 09:01:05.688   764  1740 W ActivityManager: mDVFSHelper.acquire()
07-01 09:01:05.688   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:05.688   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:05.688   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:05.688   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:05.728  7622  7622 E Zygote  : MountEmulatedStorage()
07-01 09:01:05.728  7622  7622 I libpersona: KNOX_SDCARD checking this for 10079
07-01 09:01:05.728  7622  7622 E Zygote  : v2
07-01 09:01:05.728  7622  7622 I libpersona: KNOX_SDCARD not a persona
07-01 09:01:05.728   764  1740 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7622 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-01 09:01:05.738  7622  7622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:05.738  7622  7622 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:05.738  7622  7622 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-01 09:01:05.738  7608  7608 D AndroidRuntime: Shutting down VM
07-01 09:01:05.758  7622  7622 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:01:05.758  7622  7622 D ActivityThread: Added TimaKeyStore provider
07-01 09:01:05.768  1455  1455 V ActivityThread: updateVisibility : ActivityRecord{1ad0fa23 token=android.os.BinderProxy@32639b7d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-01 09:01:05.768  1764  1773 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-01 09:01:05.778   764  3084 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:05.788  7622  7622 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-01 09:01:05.788   764  3084 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:05.808  1455  1455 D SurfaceWidgetView: destroyHardwareResources():882751107
07-01 09:01:05.848   266   373 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-01 09:01:05.848   266  1678 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-01 09:01:05.858  1455  1455 D Launcher: onTrimMemory. Level: 20
07-01 09:01:05.878  7622  7622 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-01 09:01:05.878  7622  7622 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-01 09:01:05.888  7622  7622 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3554-3557)
07-01 09:01:05.888  7622  7622 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:05.908  7622  7622 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ce12b85}
07-01 09:01:05.908  7622  7622 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 09:01:05.908  7622  7622 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 09:01:05.938  7622  7622 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 09:01:05.938  7622  7622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 09:01:05.938  7622  7622 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 09:01:05.968  7622  7622 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 09:01:05.968  7622  7622 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-01 09:01:05.968  7622  7622 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-01 09:01:05.968  7622  7622 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-01 09:01:05.968  7622  7622 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-01 09:01:05.968  7622  7622 I Adreno-EGL: Build Date: 11/19/14 Wed
07-01 09:01:05.968  7622  7622 I Adreno-EGL: Local Branch: mybranch5813579
07-01 09:01:05.968  7622  7622 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-01 09:01:05.968  7622  7622 I Adreno-EGL: Local Patches: NONE
07-01 09:01:05.968  7622  7622 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-01 09:01:06.088  7622  7656 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-01 09:01:06.118  7622  7622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 09:01:06.128  7622  7622 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-01 09:01:06.138  7622  7622 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-01 09:01:06.148  7622  7622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 09:01:06.148  7622  7622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 09:01:06.198  7622  7622 D Activity: performCreate Call secproduct feature valuefalse
07-01 09:01:06.198  7622  7622 D Activity: performCreate Call debug elastic valuetrue
,07-01 09:01:06.218  7622  7669 D OpenGLRenderer: Render dirty regions requested: true
,07-01 09:01:06.218   764   779 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-01 09:01:06.218   764   779 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-01 09:01:06.218   764   779 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-01 09:01:06.218   764   764 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-01 09:01:06.218   764   764 D PersonaManagerService: getPersonasForUser(): returning null!
,07-01 09:01:06.238   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-01 09:01:06.258  7622  7669 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 09:01:06.268  7622  7669 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3de0420 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-01 09:01:06.278  7622  7669 D OpenGLRenderer: Enabling debug mode 0
,07-01 09:01:06.298  7622  7622 V ActivityThread: updateVisibility : ActivityRecord{85c54d7 token=android.os.BinderProxy@2e8aa671 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-01 09:01:06.338   764  1056 W ActivityManager: mDVFSHelper.release()
07-01 09:01:06.338   764  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b925597 u0 com.test.thalitest/.MainActivity t23} time:294003
,07-01 09:01:06.338  7622  7622 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e8aa671 time:294005
,07-01 09:01:06.348   764  1056 D MultiWindowConverter: This application or window do not support multiwindow
,07-01 09:01:06.378  7622  7622 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7622
,07-01 09:01:06.458  7622  7622 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-01 09:01:06.558  7622  7674 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1360697728
,07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-01 09:01:06.568  7622  7674 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@220621c7 added. We now have 1 listener(s)
,07-01 09:01:06.568  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-01 09:01:06.578  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-01 09:01:06.578  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-01 09:01:06.578  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 09:01:06.578  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34532d92 added. We now have 1 listener(s)
,07-01 09:01:06.578  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:06.588  7622  7674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-01 09:01:06.588  7622  7674 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-01 09:01:06.588  7622  7674 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-01 09:01:06.588  7622  7674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 09:01:06.598  7622  7674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
,07-01 09:01:06.598   764  3348 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:06.608  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 09:01:06.608  7622  7674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 09:01:06.608  7622  7674 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-01 09:01:06.608   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:06.608  7622  7674 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 09:01:06.608  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:06.608   764  1740 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:06.608  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:06.628  7622  7622 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-01 09:01:07.338  7622  7682 W jxcore-log: Initializing JXcore engine
,07-01 09:01:07.338  7622  7682 W jxcore-log: JXcore engine is ready
,07-01 09:01:07.388  1891  1891 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-01 09:01:07.388  1891  1891 E audit   : type=1400 msg=audit(1467356467.378:203): avc:  denied  { ioctl } for  pid=7682 comm="Thread-1283" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-01 09:01:07.388  1891  1891 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-01 09:01:07.388  1891  1891 E audit   : 
07-01 09:01:07.388  1891  1891 E audit   : type=1300 msg=audit(1467356467.378:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=985e08d8 items=0 ppid=338 ppcomm=main pid=7682 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1283" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,07-01 09:01:07.388  1891  1891 E audit   : type=1320 msg=audit(1467356467.378:203): 
07-01 09:01:07.388   764  1028 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-01 09:01:07.388   764  1028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-01 09:01:07.388   764  1028 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-01 09:01:07.398  7098  7098 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-01 09:01:07.398  7098  7098 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-01 09:01:07.398  7622  7682 W jxcore-log: Starting JXcore engine
,07-01 09:01:07.478  7622  7682 W jxcore-log: Platform android
07-01 09:01:07.478  7622  7682 W jxcore-log: 
,07-01 09:01:07.478  7622  7682 W jxcore-log: Process ARCH arm
07-01 09:01:07.478  7622  7682 W jxcore-log: 
,07-01 09:01:07.548   296   296 E SMD     : DCD ON
,07-01 09:01:07.678  7622  7682 I jxcore-log: JXcore Cordova bridge is ready!
07-01 09:01:07.678  7622  7682 I jxcore-log: 
,07-01 09:01:07.678  7622  7682 W jxcore-log: JXcore engine is started
,07-01 09:01:07.688  7622  7674 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-01 09:01:07.688  7622  7622 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 09:01:07.938   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:08.118   764  3084 D SSRM:n  : SIOP:: AP = 320, PST = 307, CUR = 450
,07-01 09:01:08.658   764  1573 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:08.938   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:09.028   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:09.938   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:10.548   296   296 E SMD     : DCD ON
,07-01 09:01:10.938   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:11.938   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:12.938   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-01 09:01:13.548   296   296 E SMD     : DCD ON
,07-01 09:01:15.738   764  1062 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-01 09:01:16.548   296   296 E SMD     : DCD ON
,07-01 09:01:17.488  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-01 09:01:17.488  7622  7682 I jxcore-log: 
,07-01 09:01:17.488  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-01 09:01:17.488  7622  7682 I jxcore-log: 
,07-01 09:01:17.488   764  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:17.498  7622  7682 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 09:01:17.498  7622  7682 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-01 09:01:17.498  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-01 09:01:17.498  7622  7682 I jxcore-log: 
,07-01 09:01:17.498  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-01 09:01:17.498  7622  7682 I jxcore-log: 
,07-01 09:01:17.828  7622  7682 I jxcore-log: Unit Test app is loaded
07-01 09:01:17.828  7622  7682 I jxcore-log: 
,07-01 09:01:17.838  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 09:01:17.838  7622  7682 I jxcore-log: 
,07-01 09:01:17.838  7622  7682 I jxcore-log: My device name is: samsung-SM-N9005
07-01 09:01:17.838  7622  7682 I jxcore-log: 
,07-01 09:01:17.838  7622  7682 I jxcore-log: WARN testUtils: myNameCallback not set!
07-01 09:01:17.838  7622  7682 I jxcore-log: 
,07-01 09:01:17.848  7622  7622 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-01 09:01:17.898  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-01 09:01:17.898  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a546e4 added. We now have 2 listener(s)
07-01 09:01:17.898  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:17.898  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
,07-01 09:01:17.898  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:17.898  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:17.908  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a546e4 removed from the list
,07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1450d74d added. We now have 2 listener(s)
07-01 09:01:17.908  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:17.908  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:17.908  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:17.908  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:17.908  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1450d74d removed from the list
,07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:17.908  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a935202 added. We now have 2 listener(s)
07-01 09:01:17.908  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 09:01:17.908  7622  7674 I WifiManager: packageName : com.test.thalitest
07-01 09:01:17.908   764   779 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-01 09:01:17.908   764   779 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 09:01:17.908   764   779 D SecContentProvider2: mCursor = null
07-01 09:01:17.908   764   779 D WifiService: setWifiEnabled: false pid=7622, uid=10079
07-01 09:01:17.908   764   779 D SettingsProvider: name = wifi_on
07-01 09:01:17.918  7622  7674 D BluetoothAdapter: disable()
07-01 09:01:17.918   764  1543 D SettingsProvider: name = bluetooth_on
07-01 09:01:17.918   764  1146 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-01 09:01:17.918  1281  1281 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 09:01:17.918  1281  1281 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-01 09:01:17.918  1281  1281 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-01 09:01:17.928  3021  3076 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-01 09:01:17.928  3021  3076 D BluetoothAdapterProperties: Setting state to 13
07-01 09:01:17.928  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 09:01:17.928  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:17.928  3021  3076 D BluetoothAdapterService: updateAdapterState state is 13
,07-01 09:01:17.928   764  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:17.928   764  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:17.928   764  1356 D ActivityManager: caller:android.app.ApplicationThreadProxy@28cc114e, r.packageName :com.android.bluetooth
07-01 09:01:17.928  3021  3021 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-01 09:01:17.928  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:17.928  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-01 09:01:17.928  3021  3076 D BluetoothAdapterService: terminating service from this receiver
07-01 09:01:17.928  3021  3021 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@260499af, channel: 19, state: LISTENING
07-01 09:01:17.928  3021  3021 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@260499af, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cf50ab7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2322f1bcmSocket: android.net.LocalSocket@ef06545 impl:android.net.LocalSocketImpl@3394549a fd:FileDescriptor[78]
07-01 09:01:17.928  3021  3021 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ef06545 impl:android.net.LocalSocketImpl@3394549a fd:FileDescriptor[78]
,07-01 09:01:17.928  3021  3076 D BluetoothAdapterProperties: onBluetoothDisable()
,07-01 09:01:17.938  1281  1281 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 09:01:17.938   764  1474 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-01 09:01:17.938  3021  3076 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-01 09:01:17.938  4217  4217 D BluetoothPbap: Proxy object disconnected
07-01 09:01:17.938  4217  4217 D PbapServerProfile: Bluetooth service disconnected
,07-01 09:01:17.938  3021  3079 D BluetoothAdapterProperties: Scan Mode:20
,07-01 09:01:17.938  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-01 09:01:17.938  3021  3082 D bt_vendor: op for 7
,07-01 09:01:17.938  3021  3076 E bt-btif : btif_dm_generic_evt: event=33036andle:6, rfc_init:1, vhci_init:1
07-01 09:01:17.938  3021  3076 E bt-btif : cmd socket is not created
,07-01 09:01:17.948  3021  5810 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-01 09:01:17.948  3021  3080 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,07-01 09:01:17.948   764  1146 E native  : do suspend true
,07-01 09:01:17.948  3021  3076 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 09:01:17.948  3021  3082 D bt_upio : proc btwrite assertion
,07-01 09:01:17.958   764  1145 D WifiP2pService: InactiveState{ what=143375 }
,07-01 09:01:17.958  7622  7674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-01 09:01:17.958   764  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 09:01:17.958   290  1043 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:17.958  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:17.958   764  1244 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:17.958  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:17.958  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:17.958   764  1543 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:17.958  7622  7674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:17.958  7622  7674 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 09:01:17.958   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:17.968  3021  3080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:17.968  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.968  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.968  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.968  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.968  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:17.968   764  1356 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:17.968  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.968  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.978  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.978  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.988  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.988  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.998   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:17.998   764   764 I InputMethodManagerService: [BT Setting State] State =13
07-01 09:01:17.998  3021  3021 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@340b6da8, channel: 5, state: LISTENING
07-01 09:01:17.998  3021  3021 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@340b6da8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2e238224, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1c3710c1mSocket: android.net.LocalSocket@d32066 impl:android.net.LocalSocketImpl@22a80fa7 fd:FileDescriptor[80]
07-01 09:01:17.998  3021  3021 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d32066 impl:android.net.LocalSocketImpl@22a80fa7 fd:FileDescriptor[80]
07-01 09:01:17.998  3021  3021 I BtOppRfcommListener: stopping Accept Thread
07-01 09:01:17.998  3021  3021 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@387dbc54, channel: 12, state: LISTENING
07-01 09:01:17.998  3021  3021 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@387dbc54, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36d2ed8e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19e2f7fdmSocket: android.net.LocalSocket@37e0dcf2 impl:android.net.LocalSocketImpl@233bff43 fd:FileDescriptor[85]
07-01 09:01:17.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.998  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.998  3021  3021 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@37e0dcf2 impl:android.net.LocalSocketImpl@233bff43 fd:FileDescriptor[85]
07-01 09:01:17.998  3021  5810 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-01 09:01:17.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:17.998  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:17.998  1188  1188 D BluetoothTile:  onBluetoothStateChange:
07-01 09:01:18.008   764  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:18.008   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:18.008   764  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:18.008   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:18.008   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-01 09:01:18.008   764  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
07-01 09:01:18.008  3021  3082 D bt_vendor: op for 7
07-01 09:01:18.008  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:18.018  3021  3082 D bt_vendor: op for 7
07-01 09:01:18.018  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:18.018  3021  3082 D bt_vendor: op for 7
07-01 09:01:18.018  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:18.018   764   764 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-01 09:01:18.028  1696  1696 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 09:01:18.028  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:18.028  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:18.028  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:18.028  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
07-01 09:01:18.028  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
07-01 09:01:18.038  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 09:01:18.038  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:18.038   764   778 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:18.038  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:18.038  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:18.038   764  3372 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 09:01:18.038   764  1244 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 09:01:18.038   764  1145 D WifiP2pService: InactiveState{ what=131204 }
07-01 09:01:18.038   764  1145 D WifiP2pService: P2pEnabledState{ what=131204 }
07-01 09:01:18.038   764   764 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 09:01:18.038   764   764 D RttService: SCAN_AVAILABLE : 1
07-01 09:01:18.038   764  1164 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.048   764  1145 D WifiP2pService: sending p2p connection changed broadcast: FAILED
07-01 09:01:18.048   764  1165 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.048   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.048   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:18.048   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:18.048   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.048   764   764 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-01 09:01:18.048   764  1056 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-01 09:01:18.048   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:18.048   764  1056 D WifiDisplayController: disconnect
07-01 09:01:18.048   764  1056 D WifiDisplayController: updateConnection
07-01 09:01:18.048   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:18.048   764  1056 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 09:01:18.048   764  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.048  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:18.048   764  1223 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
07-01 09:01:18.048   764  1145 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-01 09:01:18.048   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.048   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.048   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.048   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.048   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
07-01 09:01:18.048   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.048   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:18.048   764  1759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 09:01:18.048   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:18.048   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:18.048   764  1759 I qtaguid : Tagging socket 284 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 764, getuid(): 1000
07-01 09:01:18.048   764  1145 D WifiP2pService: P2pDisablingState
07-01 09:01:18.048   764  1145 D WifiP2pService: P2pDisablingState{ what=147458 }
07-01 09:01:18.048   764  1145 D WifiP2pService: p2p socket connection lost
07-01 09:01:18.048   764  1145 D WifiP2pService: P2pDisabledState
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.048   764  1146 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.048  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.058  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.058   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.058   764  1759 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:18.058  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-01 09:01:18.058  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.058  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.058  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 09:01:18.058  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 09:01:18.058   764  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 09:01:18.058  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-01 09:01:18.058  7622  7637 I art     : Background partial concurrent mark sweep GC freed 52618(2MB) AllocSpace objects, 10(3MB) LOS objects, 44% free, 19MB/35MB, paused 7.094ms total 168.670ms
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:18.068   764   779 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D QSpanel : label top:23
07-01 09:01:18.068   764  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:18.068  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 09:01:18.078   764  1146 E native  : do suspend true
07-01 09:01:18.078   764  1145 D WifiP2pService: P2pDisabledState{ what=143375 }
07-01 09:01:18.078   764  1145 D WifiP2pService: DefaultState{ what=143375 }
,07-01 09:01:18.088   290  1043 D CommandListener: Clearing all IP addresses on wlan0
07-01 09:01:18.088   764  1148 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-01 09:01:18.088   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:18.088   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:18.088   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:18.088   764  1148 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:18.088   764  1148 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-01 09:01:18.088   764  1148 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:18.088   764  1148 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:18.088  1433  1433 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:18.088   764  1148 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fed7:fd2b/64,192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-01 09:01:18.088   764  1148 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
07-01 09:01:18.088   764  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:18.088   764  1055 D EntConnectivity: Not allowed due to - mEnabled false
07-01 09:01:18.088   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-01 09:01:18.088   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-01 09:01:18.088  1188  1583 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-01 09:01:18.088   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.088   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:18.088   764  1148 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:18.088   764  1759 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-01 09:01:18.088   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:18.088   764  1149 D Tethering: MasterInitialState.processMessage what=3
07-01 09:01:18.088   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:18.088   764  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 09:01:18.088   764  1148 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:18.088   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:18.088   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-01 09:01:18.088   764  1148 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ea50:8bff:fed7:fd2b/64,192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-01 09:01:18.088   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.088   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.088   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.088   764   764 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-01 09:01:18.088   764  1143 V NetworkStats: updateIfacesLocked()
07-01 09:01:18.088   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:18.088   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.088  1281  1281 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-01 09:01:18.088   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-01 09:01:18.088   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.098   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.098   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.098   764  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 09:01:18.098   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 09:01:18.098   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.098   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.098   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.098   764  1144 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:18.098  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.098  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: updateDataNetType()
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:18.098  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:18.098  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:18.098   764  1143 V NetworkStats: performPollLocked() took 11ms
07-01 09:01:18.098  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.098  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-01 09:01:18.098   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.108   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:18.108   764  1146 D SecContentProvider2: mCursor = null
07-01 09:01:18.108   764  1677 D SecContentProvider2: uri = 14 selection = getSealedState
07-01 09:01:18.108   764  1677 D SecContentProvider2: mCursor = null
07-01 09:01:18.108   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.108   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.108   764  1740 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 09:01:18.108   764  1344 I AudioService: getStreamVolume 3 index 70
07-01 09:01:18.108   764  1740 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.108  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.108  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.118  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.118  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-01 09:01:18.118   764   778 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 09:01:18.118   764   778 D ActivityManager: caller:android.app.ApplicationThreadProxy@345bf45a, r.packageName :com.android.settings
07-01 09:01:18.118  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:18.118  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.118  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:18.128  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.128  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:18.128  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:18.128  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.128  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-01 09:01:18.128  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.128  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 09:01:18.128  1188  1188 D HotspotTile: onReceive : 0, 0
07-01 09:01:18.128  1188  1188 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
07-01 09:01:18.138  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
07-01 09:01:18.138  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
07-01 09:01:18.138  1188  1188 I PhoneStatusBar: Icon Only
07-01 09:01:18.138  1188  1188 I StatusBar: Icon Only
07-01 09:01:18.138  1188  1188 D PanelView: There is/are notification(s) 
07-01 09:01:18.138  1188  1188 D PanelView: There is/are notification(s) 
07-01 09:01:18.138  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.148  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.148  1188  1188 D QSpanel : label top:23
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:18.148  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 09:01:18.148  3021  3076 D BtConfig.SecureMode: isSecureModeOn:false
07-01 09:01:18.148  3021  3076 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 09:01:18.148  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:18.148  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 09:01:18.148  4217  4217 D DockEventReceiver: finishStartingService: stopping service
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:18.148   764   779 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:18.148   764   779 D ActivityManager: caller:android.app.ApplicationThreadProxy@33857368, r.packageName :com.android.bluetooth
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:18.148  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 09:01:18.148  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:18.148  3021  3021 D HeadsetService: Received stop request...Stopping profile...
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 09:01:18.148  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:18.148   764  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.148   764  1344 D ActivityManager: caller:android.app.ApplicationThreadProxy@36c0381, r.packageName :com.android.bluetooth
07-01 09:01:18.148   764   764 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 09:01:18.148  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 09:01:18.148   764  3084 D SSRM:n  : SIOP:: AP = 350, PST = 311, CUR = 450
07-01 09:01:18.148   764  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.148  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
07-01 09:01:18.148   764  1543 D ActivityManager: caller:android.app.ApplicationThreadProxy@14d4fc26, r.packageName :com.android.bluetooth
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 09:01:18.148  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:18.148  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-01 09:01:18.148   764   779 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.148   764   779 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ee72067, r.packageName :com.android.bluetooth
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 09:01:18.158   764  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.158   764  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@1af25e14, r.packageName :com.android.bluetooth
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.158  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.158   764  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.158   764  1344 D ActivityManager: caller:android.app.ApplicationThreadProxy@295456bd, r.packageName :com.android.bluetooth
07-01 09:01:18.158  4217  4217 D HeadsetProfile: Bluetooth service disconnected
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 09:01:18.158   764  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:18.158   764  1484 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e84b4b2, r.packageName :com.android.bluetooth
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSink,Service
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:18.158  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 09:01:18.158  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:18.158  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 09:01:18.158  3021  3076 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 09:01:18.158  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 09:01:18.158  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:18.158  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-01 09:01:18.158  3021  3021 D A2dpService: Received stop request...Stopping profile...
07-01 09:01:18.158  3021  3021 V Avrcp   : doQuit
07-01 09:01:18.158  3021  3242 D A2dpStateMachine: Exit Disconnected: -1
07-01 09:01:18.158  3021  3021 D Avrcp   : Unregistering previous receiver
07-01 09:01:18.158  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-01 09:01:18.158  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:18.158   764   764 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:18.158   764   764 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-01 09:01:18.168  4217  4217 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:18.168  4217  4217 D A2dpProfile: Bluetooth service disconnected
07-01 09:01:18.168  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
07-01 09:01:18.168  3192  3192 D BluetoothA2dp: Proxy object disconnected
,07-01 09:01:18.168  3021  3021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 09:01:18.168  3021  3021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-01 09:01:18.168  3021  3021 D HidService: Received stop request...Stopping profile...
07-01 09:01:18.168  3021  3021 D HidService: Stopping Bluetooth HidService
07-01 09:01:18.168  3021  3021 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 09:01:18.168  3021  3021 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-01 09:01:18.168  3021  3021 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 09:01:18.168  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:18.168  4217  4217 D BluetoothInputDevice: Proxy object disconnected
07-01 09:01:18.168  4217  4217 D HidProfile: Bluetooth service disconnected
,07-01 09:01:18.168   764  1244 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
07-01 09:01:18.168  3021  3021 D HealthService: Received stop request...Stopping profile...
07-01 09:01:18.168  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:18.168   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.168   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.168   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.168   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:18.168  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.178  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.178  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.178  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.178  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.188  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.188  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.198  1433  1433 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-01 09:01:18.208  1281  1281 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-01 09:01:18.208  1281  1281 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-01 09:01:18.208  1281  1281 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-01 09:01:18.208  1281  1281 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
07-01 09:01:18.208  1281  1281 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-01 09:01:18.208  7735  7735 E Zygote  : MountEmulatedStorage()
,07-01 09:01:18.208  7735  7735 E Zygote  : v2
07-01 09:01:18.208  7735  7735 I libpersona: KNOX_SDCARD checking this for 10140
07-01 09:01:18.208  7735  7735 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:18.228   764  1244 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7735 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-01 09:01:18.248  3021  3021 D PanService: Received stop request...Stopping profile...
07-01 09:01:18.248  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:18.248  7735  7735 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 09:01:18.248  7735  7735 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:18.248  7735  7735 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-01 09:01:18.248   764   764 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-01 09:01:18.248  4217  4217 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-01 09:01:18.248  4217  4217 D PanProfile: Bluetooth service disconnected
,07-01 09:01:18.248  3021  3021 D BluetoothMapService: Received stop request...Stopping profile...
,07-01 09:01:18.248  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:18.248  4217  4217 D BluetoothMap: Proxy object disconnected
,07-01 09:01:18.248  4217  4217 D MapProfile: Bluetooth service disconnected
07-01 09:01:18.248  3021  3021 D SapService: Received stop request...Stopping profile...
07-01 09:01:18.248  3021  3021 D SapService: Stopping Bluetooth SapService
07-01 09:01:18.248  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:18.248  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 09:01:18.248  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:18.248  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-01 09:01:18.248  3021  3021 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:18.248  3021  3021 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-01 09:01:18.248  4217  4217 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-01 09:01:18.248  3021  3243 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 09:01:18.248  3021  3021 I GKI_LINUX: GKI_exit_task 2 done
07-01 09:01:18.248  3021  3021 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 09:01:18.248  3021  3021 V Avrcp   : cleanup
,07-01 09:01:18.258  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:18.258  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  4217  4217 D SapProfile: Bluetooth service disconnected
07-01 09:01:18.258  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:18.258  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  3021  3021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 09:01:18.258  3021  3021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:18.258  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:18.258  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:18.258  3021  3021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 09:01:18.258  3021  3021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-01 09:01:18.258  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:18.258  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-01 09:01:18.258  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-01 09:01:18.258  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,07-01 09:01:18.258  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-01 09:01:18.258  3021  3076 D BluetoothAdapterProperties: Setting state to 10
07-01 09:01:18.258  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 09:01:18.258  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:18.258  3021  3076 D BluetoothAdapterService: updateAdapterState state is 10
,07-01 09:01:18.258  3021  3021 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-01 09:01:18.258  3021  3021 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-01 09:01:18.258  4217  4226 D Bluetoothsap: onBluetoothStateChange: up=false
07-01 09:01:18.258  4217  4226 D Bluetoothsap: Unbinding service...
07-01 09:01:18.258  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:18.258  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-01 09:01:18.258  3021  3076 I BluetoothAdapterState: Entering OffState
,07-01 09:01:18.258   764  1055 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:18.258  4217  4226 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 09:01:18.258  3021  3032 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:18.258  3192  3206 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:18.258  4217  4229 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-01 09:01:18.258  4217  4226 D BluetoothMap: onBluetoothStateChange: up=false
,07-01 09:01:18.268  4217  4226 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:18.268   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:18.268   764   764 I InputMethodManagerService: [BT Setting State] State =10
07-01 09:01:18.268   764   764 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 09:01:18.268  1696  1696 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 09:01:18.268  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:18.268  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:18.268  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:18.268   764  1740 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:18.268   764  1484 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 09:01:18.268  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 09:01:18.268  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 09:01:18.278  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D QSpanel : label top:23
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:18.278  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:18.278  7735  7735 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:18.278  7735  7735 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:18.298  7735  7735 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-01 09:01:18.428  1281  1281 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-01 09:01:18.428   764  1149 D Tethering: InitialState.processMessage what=4
07-01 09:01:18.428   764  1149 E Tethering: No numeric data
07-01 09:01:18.428   764  1149 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-01 09:01:18.428   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:18.428   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.428   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-01 09:01:18.428  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:18.428  1188  1188 D HotspotTile: updateTetherState():false, false
07-01 09:01:18.428   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.428   764  1143 V NetworkStats: performPollLocked() took 2ms
07-01 09:01:18.428   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.428   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:18.428   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:18.428   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-01 09:01:18.428   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 09:01:18.438   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:18.438  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.438  1903  1903 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-01 09:01:18.438  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:18.438  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.438  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 09:01:18.438  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.438  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-01 09:01:18.438  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:18.438  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-01 09:01:18.438  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.438  1188  1188 D HotspotTile: onReceive : 1, 0
07-01 09:01:18.438  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.438   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 09:01:18.448  1188  1188 D QSpanel : label top:23
,07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
,07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:18.448  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.File.exists(File.java:363)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 09:01:18.528  7735  7735 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.e.b(PG:170)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.k.c(PG:583)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.e.b(PG:170)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.528  7735  7735 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.io.File.exists(File.java:363)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-01 09:01:18.528  7735  7735 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-01 09:01:18.538   764  1740 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-01 09:01:18.538   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.538   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.538   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.538   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:18.568  7735  7752 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-01 09:01:18.578  7759  7759 E Zygote  : MountEmulatedStorage()
07-01 09:01:18.578  7759  7759 E Zygote  : v2
07-01 09:01:18.578  7759  7759 I libpersona: KNOX_SDCARD checking this for 10038
07-01 09:01:18.578  7759  7759 I libpersona: KNOX_SDCARD not a persona
07-01 09:01:18.588   764  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:18.598   764  1740 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7759 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-01 09:01:18.598   338   338 I art     : Explicit concurrent mark sweep GC freed 8748(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 12.610ms
07-01 09:01:18.598   764  1740 I ActivityManager: Killing 7028:com.samsung.android.scloud.sync/u0a76 (adj 15): emptyCount ##41
07-01 09:01:18.598   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:18.598   764   764 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:18.598   764   764 I ApplicationPolicy: updateDataUsageMap
07-01 09:01:18.608   764  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 09:01:18.608   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.608   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.608   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:18.608   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 309us total 9.630ms
07-01 09:01:18.608   764   917 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:18.608   764   917 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:18.618  7759  7759 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:18.618  7759  7759 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:18.618   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 10.614ms
07-01 09:01:18.618  7759  7759 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 09:01:18.618   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:18.618   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 09:01:18.618  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.618  1592  1592 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-01 09:01:18.628   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:18.628  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.638   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-01 09:01:18.648  7759  7759 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:18.648  7759  7759 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:18.768   764  1244 I art     : Explicit concurrent mark sweep GC freed 191170(11MB) AllocSpace objects, 68(15MB) LOS objects, 30% free, 36MB/52MB, paused 1.401ms total 115.194ms
,07-01 09:01:18.788  7759  7759 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-01 09:01:18.788  7759  7759 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-01 09:01:18.908  7759  7759 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-01 09:01:18.958  7622  7674 I WifiManager: packageName : com.test.thalitest
,07-01 09:01:18.968   764  1356 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 09:01:18.968   764  1356 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 09:01:18.968   764  1356 D SecContentProvider2: mCursor = null
,07-01 09:01:18.968   764  1356 D WifiService: setWifiEnabled: true pid=7622, uid=10079
07-01 09:01:18.968   764  1356 W ActivityManager: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-01 09:01:18.968   764  1356 W WifiService: Failed getting userId using ActivityManagerNative
07-01 09:01:18.968   764  1356 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 09:01:18.968   764  1356 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 09:01:18.968   764  1356 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-01 09:01:18.968   764  1356 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-01 09:01:18.968   764  1356 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-01 09:01:18.968   764  1356 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-01 09:01:18.968   764  1356 D SettingsProvider: name = wifi_on
,07-01 09:01:18.968   764  1146 E WifiHW  : ##################### set firmware type 0 #####################
,07-01 09:01:18.968   290  1043 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-01 09:01:18.968   290  1043 I WifiHW  : module is semco
07-01 09:01:18.968   290  1043 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-01 09:01:18.968   290  1043 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-01 09:01:18.968   290  1043 E WifiHW  : TEMP_FAILURE_RETRY complete
07-01 09:01:18.968   290  1043 D SoftapController: Softap fwReload - Ok
,07-01 09:01:18.968   290  1043 D CommandListener: Setting iface cfg
07-01 09:01:18.968   290  1043 D CommandListener: Trying to bring down wlan0
,07-01 09:01:18.968   290  1043 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:18.968   764  1146 E WifiHW  : supplicant_name : p2p_supplicant
,07-01 09:01:18.978   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:18.978  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.978   764  1146 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 09:01:18.978  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:18.978  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:18.978   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 09:01:18.978  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:18.978  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:18.978  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-01 09:01:18.978  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.978  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-01 09:01:18.978  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:18.978  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:18.988  1188  1188 D HotspotTile: onReceive : 2, 0
,07-01 09:01:19.008  1188  1188 D QSpanel : label top:23
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:19.008  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:19.008  7777  7777 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-01 09:01:19.008  7777  7777 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-01 09:01:19.008  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:19.008  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 09:01:19.018   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7777
07-01 09:01:19.018   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-01 09:01:19.018  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:19.018  7777  7777 I wpa_supplicant: ssSupport state is = 1
07-01 09:01:19.018  7777  7777 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-01 09:01:19.018  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-01 09:01:19.018   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7777
07-01 09:01:19.018   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-01 09:01:19.038  7759  7759 E BluetoothHeadset: BTStateChangeCB is registed
,07-01 09:01:19.038   764  1376 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:19.038  7759  7759 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:19.048   764  1484 I ActivityManager: Killing 7059:com.sec.android.app.clockpackage/u0a106 (adj 15): emptyCount ##41
,07-01 09:01:19.058  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-01 09:01:19.058  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:19.058   764   778 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.058  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:19.058   764  1223 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.058  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:19.058  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:19.058  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 09:01:19.058  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:19.068   764  1344 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.068  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:19.078  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 09:01:19.088  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:19.088   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:19.088  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:19.088   764  1244 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:19.088  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:19.088  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:19.088  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 09:01:19.088  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:19.088  6503  6503 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 09:01:19.098  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-01 09:01:19.098   764  3372 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
07-01 09:01:19.098   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.098   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.098   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.098   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:19.178   764  3372 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7784 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:19.178  7784  7784 E Zygote  : MountEmulatedStorage()
07-01 09:01:19.178  7784  7784 E Zygote  : v2
07-01 09:01:19.188  7784  7784 I libpersona: KNOX_SDCARD checking this for 10192
07-01 09:01:19.188  7784  7784 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:19.248  7784  7784 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 09:01:19.248  7784  7784 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:19.248  7784  7784 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:19.268  7784  7784 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:19.268  7784  7784 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:19.288   363   363 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-01 09:01:19.288  7784  7784 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-01 09:01:19.298  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 09:01:19.308  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-01 09:01:19.308  7784  7784 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 09:01:19.308  7784  7784 D WifiDirectBR: stopServiceTest : false
,07-01 09:01:19.308  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 09:01:19.308   764  1376 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-01 09:01:19.308   764  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.308   764  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.308   764  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.308   764  1376 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:19.348  7799  7799 E Zygote  : MountEmulatedStorage()
,07-01 09:01:19.348  7799  7799 E Zygote  : v2
07-01 09:01:19.348  7799  7799 I libpersona: KNOX_SDCARD checking this for 10131
07-01 09:01:19.348  7799  7799 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:19.358   764  1376 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7799 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 09:01:19.358   764  1376 I ActivityManager: Killing 7074:com.sec.esdk.elm/u0a116 (adj 15): emptyCount ##41
,07-01 09:01:19.418  7799  7799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:19.418  7799  7799 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:19.418  7799  7799 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 09:01:19.438  7799  7799 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:19.438  7799  7799 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:19.448  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-01 09:01:19.448  7799  7799 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-01 09:01:19.518  3021  3082 D bt_vendor: op for 7
,07-01 09:01:19.538  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-01 09:01:19.548   296   296 E SMD     : DCD ON
,07-01 09:01:19.558  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:19.558  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 09:01:19.558   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7777
07-01 09:01:19.558   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 09:01:19.558  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:19.558  7777  7777 I wpa_supplicant: ssSupport state is = 1
07-01 09:01:19.558  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:19.558  7777  7777 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:19.558  7777  7777 E wpa_supplicant: SIM READ ERROR
07-01 09:01:19.558  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:19.558  7777  7777 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:19.558  7777  7777 E wpa_supplicant: SIM READ ERROR
07-01 09:01:19.558  7777  7777 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:19.558  7777  7777 I wpa_supplicant: wpa_default_ap_write_once
07-01 09:01:19.558  7777  7777 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 09:01:19.558  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:19.558  7777  7777 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-01 09:01:19.558  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:19.558  7777  7777 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-01 09:01:19.558  7777  7777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:19.628  7799  7822 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-01 09:01:19.628  7799  7822 I Babel   : MmsConfig.loadMmsSettings
,07-01 09:01:19.628  7799  7822 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-01 09:01:19.628  7799  7822 I Babel   : MmsConfig.loadFromDatabase
,07-01 09:01:19.628  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-01 09:01:19.658  7799  7822 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-01 09:01:19.658  7799  7822 I Babel   : MmsConfig.loadFromResources
,07-01 09:01:19.658   764  1740 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-01 09:01:19.658  7799  7822 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-01 09:01:19.658  7799  7822 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-01 09:01:19.658  7799  7799 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:19.688  7799  7799 I Babel_StickerModule: App launched.
,07-01 09:01:19.688  7799  7799 I Babel_StickerModule: Trying first logged in account.
,07-01 09:01:19.698  7799  7799 W Babel_StickerModule: Unable to load, account not configured.
,07-01 09:01:19.708  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-01 09:01:19.708  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:19.708   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:19.708  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:19.708   764  1484 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.708  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:19.708  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:19.708  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 09:01:19.708  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:19.718   764  1244 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.718  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:19.718   307  1378 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,07-01 09:01:19.718   307  1378 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-01 09:01:19.718   307  1378 W QCamera2Factory: getCameraInfo: X
,07-01 09:01:19.728   307   689 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,07-01 09:01:19.728   307   689 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-01 09:01:19.728   307   689 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-01 09:01:19.728   307   689 W QCamera2Factory: getCameraInfo: X
,07-01 09:01:19.728  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:19.728   764  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.728  7799  7799 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 09:01:19.738  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:19.738  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:19.738  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
,07-01 09:01:19.738  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-01 09:01:19.738  7799  7799 W AudioCapabilities: Unsupported mime audio/qcelp
,07-01 09:01:19.738  7799  7799 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-01 09:01:19.748  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 09:01:19.748   764  1740 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 09:01:19.748   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@177e200c, r.packageName :com.android.settings
,07-01 09:01:19.758  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:19.758  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:19.758  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:19.778  7799  7799 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-01 09:01:19.778  7799  7799 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-01 09:01:19.778  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:19.778  7799  7799 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-01 09:01:19.778  7799  7799 W AudioCapabilities: Unsupported mime audio/x-ima
,07-01 09:01:19.788   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:19.788  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:19.788  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:19.788  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:19.788  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:19.788  7799  7799 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-01 09:01:19.788  7799  7799 W AudioCapabilities: Unsupported mime audio/qcelp
,07-01 09:01:19.788  7799  7799 W AudioCapabilities: Unsupported mime audio/evrc
,07-01 09:01:19.798  7273  7273 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-01 09:01:19.798  7273  7273 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-01 09:01:19.798  7273  7273 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 09:01:19.798  7273  7273 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:19.798  7273  7273 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-01 09:01:19.798  7799  7799 W VideoCapabilities: Unsupported mime video/wvc1
,07-01 09:01:19.798  7799  7799 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-01 09:01:19.808   764  1223 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-01 09:01:19.808   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.808   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.808   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:19.808   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:19.808  7799  7799 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-01 09:01:19.818  7799  7799 W VideoCapabilities: Unsupported mime video/wvc1
,07-01 09:01:19.818  7799  7799 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-01 09:01:19.818  7799  7799 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-01 09:01:19.818  7799  7799 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-01 09:01:19.818  7799  7799 W VideoCapabilities: Unsupported mime video/mp43
,07-01 09:01:19.828  7799  7799 W VideoCapabilities: Unsupported mime video/sorenson
,07-01 09:01:19.828  7799  7799 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-01 09:01:19.838  7799  7799 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-01 09:01:19.848  7829  7829 E Zygote  : MountEmulatedStorage()
07-01 09:01:19.848  7829  7829 I libpersona: KNOX_SDCARD checking this for 10144
07-01 09:01:19.848  7829  7829 E Zygote  : v2
07-01 09:01:19.848  7829  7829 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:19.858   764  1223 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7829 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:19.918  7829  7829 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:19.918  7829  7829 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:19.918  7829  7829 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 09:01:19.938  7829  7829 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:19.938  7829  7829 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:19.938   764  1573 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-01 09:01:19.948  3021  3199 D bt_upio : ..proc_btwrite_timeout..
,07-01 09:01:19.958  7829  7829 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-01 09:01:19.958   764   778 I ActivityManager: Killing 6016:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,07-01 09:01:19.968  7622  7674 I WifiManager: packageName : com.test.thalitest
,07-01 09:01:19.968   764  1677 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 09:01:19.968   764  1677 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 09:01:19.968   764  1677 D SecContentProvider2: mCursor = null
,07-01 09:01:19.968   764  1677 D WifiService: setWifiEnabled: false pid=7622, uid=10079
,07-01 09:01:19.968   764  1677 D SettingsProvider: name = wifi_on
,07-01 09:01:20.068  7829  7829 I MusicStore: Database version: 108
,07-01 09:01:20.078   764   779 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.138  7829  7829 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-01 09:01:20.138  7829  7829 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-01 09:01:20.138  7829  7829 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 09:01:20.158  7829  7829 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-01 09:01:20.218  7829  7829 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-01 09:01:20.218  7829  7829 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@340b6da8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-01 09:01:20.218  7829  7829 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-01 09:01:20.218  7829  7829 D AndroidMusic: GMSCore installation verified
,07-01 09:01:20.218   764  1149 E Tethering: No numeric data
,07-01 09:01:20.218   764  1149 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-01 09:01:20.218   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:20.218   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:20.218  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-01 09:01:20.218   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-01 09:01:20.218   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.218  1188  1188 D HotspotTile: updateTetherState():false, false
,07-01 09:01:20.228   764  1143 V NetworkStats: performPollLocked() took 2ms
07-01 09:01:20.228   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.228   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:20.228   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.228   764  3348 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.238  7829  7829 I ConfigStore: Config Database version: 1
,07-01 09:01:20.258  7777  7777 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-01 09:01:20.268   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 09:01:20.268   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:20.268  7829  7829 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 09:01:20.268   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 09:01:20.268   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:20.268  7829  7829 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 09:01:20.268   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-01 09:01:20.268   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:20.268  7829  7829 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-01 09:01:20.278   764  1376 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-01 09:01:20.278   764  1376 D ActivityManager: caller:android.app.ApplicationThreadProxy@e670c27, r.packageName :com.google.android.music
,07-01 09:01:20.288   764   779 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.298   764  3372 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.298   764  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.308   764   778 I AudioService: getStreamVolume 3 index 70
,07-01 09:01:20.308  7829  7829 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-01 09:01:20.318  7829  7829 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-01 09:01:20.318  7777  7777 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 09:01:20.318   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7777
07-01 09:01:20.318   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:20.318  7777  7777 I wpa_supplicant: ssSupport state is = 1
,07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 09:01:20.318   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7777
07-01 09:01:20.318   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 09:01:20.318  7777  7777 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:20.318  7777  7777 I wpa_supplicant: ssSupport state is = 1
07-01 09:01:20.318  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:20.318  7777  7777 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:20.318  7777  7777 E wpa_supplicant: SIM READ ERROR
07-01 09:01:20.318  7777  7777 I wpa_supplicant: wpa_default_ap_write_once
07-01 09:01:20.318  7777  7777 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 09:01:20.318  7777  7777 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:20.338   764   779 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.338   764  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.338   764  1740 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.348   764  1474 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.348   764  1441 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-01 09:01:20.348   764  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.348   764  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:20.348   764  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.348   764  1441 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:20.368  7777  7777 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-01 09:01:20.368  7777  7777 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-01 09:01:20.388  7858  7858 E Zygote  : MountEmulatedStorage()
,07-01 09:01:20.388  7858  7858 E Zygote  : v2
07-01 09:01:20.388  7858  7858 I libpersona: KNOX_SDCARD checking this for 10004
07-01 09:01:20.388  7858  7858 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:20.398   764  1441 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7858 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:20.428  7777  7777 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-01 09:01:20.428  7777  7777 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-01 09:01:20.428  7777  7777 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 09:01:20.428   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-01 09:01:20.428   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 09:01:20.428  7777  7777 I wpa_supplicant: HOTSPOT20_ENABLE called
07-01 09:01:20.428  7777  7777 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:20.428  7777  7777 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:20.428  7777  7777 E wpa_supplicant: SIM READ ERROR
07-01 09:01:20.428  7777  7777 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:20.438  7777  7777 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-01 09:01:20.448  7858  7858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:20.448  7858  7858 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:20.448  7858  7858 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:20.448  7777  7777 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 09:01:20.448   764  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 09:01:20.448   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:20.448   764  1146 D WifiConfigStore: Loading config and enabling all networks 
,07-01 09:01:20.458  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.458   764  1146 E WifiConfigStore: Not a HS20
,07-01 09:01:20.458   764  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.458  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:20.458  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:20.458  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:20.458  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:20.458  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:20.468   764  1146 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:20.468   764  1146 D WifiNative-HAL: callSECApiInt - ID [65]
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.468  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:20.468  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:20.468  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:20.468  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.468  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-01 09:01:20.468  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:20.468  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:20.478  1188  1188 D HotspotTile: onReceive : 3, 0
,07-01 09:01:20.478   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-01 09:01:20.478  7777  7777 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-01 09:01:20.478  7777  7777 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-01 09:01:20.478  7777  7777 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 09:01:20.478  7777  7777 I wpa_supplicant: P2P: Current p2p state = IDLE
07-01 09:01:20.478  7777  7777 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-01 09:01:20.478  7777  7777 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-01 09:01:20.478  7777  7777 I wpa_supplicant: First Scan Start
,07-01 09:01:20.478  7777  7777 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 09:01:20.478   764  1146 D WifiNative-HAL: Setting external_sim to 1
07-01 09:01:20.478   764  1146 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:20.478   764  1146 I WifiNative-HAL: startHal
07-01 09:01:20.478   764  1146 E wifi    : getStaticLongField sWifiHalHandle 0x93ea686c
07-01 09:01:20.478   764  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xb01a3a
07-01 09:01:20.478   764  1146 I WifiNative-HAL: Could not start hal
,07-01 09:01:20.478  7799  7799 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:20.478   764  1573 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-01 09:01:20.478  7858  7858 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:20.478  7858  7858 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:20.488  7829  7829 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-01 09:01:20.488   764  1223 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:20.498  1188  1188 D QSpanel : label top:23
,07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
,07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:20.498  7858  7858 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:20.498   764  1146 E native  : do suspend true
07-01 09:01:20.498  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:20.498   764  1145 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-01 09:01:20.498   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-01 09:01:20.508   764   764 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 09:01:20.508   764   764 D RttService: SCAN_AVAILABLE : 3
07-01 09:01:20.508   764  1164 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.508   764  1164 I WifiNative-HAL: startHal
07-01 09:01:20.508   764  1164 E wifi    : getStaticLongField sWifiHalHandle 0x9b70d99c
07-01 09:01:20.508   764  1164 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xa0199e
07-01 09:01:20.508   764  1164 I WifiNative-HAL: Could not start hal
07-01 09:01:20.508   764  1164 E WifiScanningService: could not start HAL
07-01 09:01:20.508   290  1043 D CommandListener: Setting iface cfg
07-01 09:01:20.508   290  1043 D CommandListener: Trying to bring up p2p0
,07-01 09:01:20.508   764  1165 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.508   764  1145 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 09:01:20.508   764  1145 D WifiP2pService: P2pEnablingState
,07-01 09:01:20.508   764  1145 D WifiP2pService: P2pEnablingState{ what=147457 }
07-01 09:01:20.508   764  1145 D WifiP2pService: P2p socket connection successful
07-01 09:01:20.508   764  1145 D WifiP2pService: P2pEnabledState
,07-01 09:01:20.508   764  1145 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-01 09:01:20.508   764   764 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-01 09:01:20.508   764  1056 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-01 09:01:20.508   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:20.508   764  1056 D WifiDisplayController: disconnect
07-01 09:01:20.508   764  1056 D WifiDisplayController: updateConnection
07-01 09:01:20.508   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:20.508   764  1056 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.508   764   764 D WifiScanningService: SCAN_AVAILABLE : 1
07-01 09:01:20.508   764   764 D RttService: SCAN_AVAILABLE : 1
07-01 09:01:20.508   764  1164 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:20.508   764  1165 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:20.508   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:20.508   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-01 09:01:20.508  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 09:01:20.508   764  1740 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 09:01:20.508   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.508   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:20.508   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:20.508   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:20.508  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-01 09:01:20.508   764  1145 D WifiNative-HAL: p2pGetDeviceAddress
07-01 09:01:20.508   764  1145 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-01 09:01:20.508   764  1146 D WifiStateMachine: DefaultState::Handling CMD_SEC_STRING_API
07-01 09:01:20.508   764  1145 D WifiP2pService: DeviceAddress: ea:fd:2b
,07-01 09:01:20.518   764  1056 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-01 09:01:20.518   764  1056 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-01 09:01:20.518   764  1056 D WifiDisplayController:  primary type: 10-0050F204-5
07-01 09:01:20.518   764  1056 D WifiDisplayController:  secondary type: null
07-01 09:01:20.518   764  1056 D WifiDisplayController:  wps: 0
07-01 09:01:20.518   764  1056 D WifiDisplayController:  grpcapab: 0
07-01 09:01:20.518   764  1056 D WifiDisplayController:  devcapab: 0
07-01 09:01:20.518   764  1056 D WifiDisplayController:  status: 3
07-01 09:01:20.518   764  1056 D WifiDisplayController:  wfdInfo: null
07-01 09:01:20.518   764  1056 D WifiDisplayController:  groupownerAddress: null
07-01 09:01:20.518   764  1056 D WifiDisplayController:  GOdeviceName: null
07-01 09:01:20.518   764  1056 D WifiDisplayController:  interfaceAddress: 
07-01 09:01:20.518   764  1056 D WifiDisplayController:  SConnectInfo : null
,07-01 09:01:20.528   764  1145 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-01 09:01:20.528   764  1145 D WifiP2pService: InactiveState
07-01 09:01:20.528   764  1145 D WifiP2pService: InactiveState{ what=131204 }
07-01 09:01:20.528   764  1145 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-01 09:01:20.528   764  1145 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-01 09:01:20.528   764  1740 I ActivityManager: Killing 7118:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,07-01 09:01:20.528   764  1148 E ConnectivityService: updateNetworkInfo()
,07-01 09:01:20.528   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-01 09:01:20.528   764  1145 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-01 09:01:20.528   764   764 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-01 09:01:20.528   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.528   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:20.528   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:20.528   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:20.528   764  1056 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-01 09:01:20.528   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:20.528   764  1056 D WifiDisplayController: disconnect
07-01 09:01:20.528   764  1056 D WifiDisplayController: updateConnection
07-01 09:01:20.528   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:20.528   764  1056 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.528   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:20.528   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-01 09:01:20.528   764  1145 D WifiP2pService: P2pDisablingState
07-01 09:01:20.528   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:20.528   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:20.528   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:20.528   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:20.528   764  1145 D WifiP2pService: P2pDisablingState{ what=143376 }
,07-01 09:01:20.528  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 09:01:20.528   764  1484 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-01 09:01:20.528  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-01 09:01:20.528   764  1145 D WifiP2pService: DefaultState{ what=143376 }
07-01 09:01:20.528   764  1145 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-01 09:01:20.538   764  1145 D WifiP2pService: p2p socket connection lost
07-01 09:01:20.538   764  1145 D WifiP2pService: P2pDisabledState
,07-01 09:01:20.538   290  1043 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:20.538  7777  7777 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-01 09:01:20.538   764   764 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 09:01:20.538   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.538  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:20.538   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-01 09:01:20.538  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:20.538  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 09:01:20.538  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.538  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:20.548  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:20.548  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:20.548  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:20.548  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:20.548  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-01 09:01:20.548  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:20.548  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:20.548  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:20.548  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:20.548  1188  1188 D HotspotTile: onReceive : 0, 0
,07-01 09:01:20.548  1188  1188 D QSpanel : label top:23
07-01 09:01:20.548  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:20.548  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:20.548  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:20.548  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:20.558  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:20.578   764  1474 I ActivityManager: Killing 6162:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-01 09:01:20.588   764  1244 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-01 09:01:20.588   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:20.588   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.588   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.588   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:20.658  7777  7777 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:20.668  7882  7882 E Zygote  : MountEmulatedStorage()
07-01 09:01:20.668  7882  7882 E Zygote  : v2
07-01 09:01:20.668  7882  7882 I libpersona: KNOX_SDCARD checking this for 1000
07-01 09:01:20.668  7882  7882 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:20.678   764  1244 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 09:01:20.688  7777  7777 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-01 09:01:20.688  7777  7777 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
07-01 09:01:20.688  7777  7777 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-01 09:01:20.718  7882  7882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:20.718  7882  7882 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:20.718  7882  7882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:20.738  7882  7882 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:20.738  7882  7882 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:20.748  7882  7882 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-01 09:01:20.778  7777  7777 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:20.778  7882  7882 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-01 09:01:20.798  7882  7882 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-01 09:01:20.908  7882  7882 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-01 09:01:20.918  7882  7882 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-01 09:01:20.918  7882  7882 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:20.918  7882  7882 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-01 09:01:20.928  7777  7777 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-01 09:01:20.928   764  1149 D Tethering: InitialState.processMessage what=4
07-01 09:01:20.928  7777  7777 I wpa_supplicant: ELOOP: remaining timeout: 0.048726 eloop_data=0xb6588200 user_data=0x0 handler=0xb6efbaf1
07-01 09:01:20.928  7777  7777 I wpa_supplicant: ELOOP: remaining timeout: 0.085450 eloop_data=0xb6588c00 user_data=0x0 handler=0xb6efbaf1
,07-01 09:01:20.928   764  1149 E Tethering: No numeric data
07-01 09:01:20.928   764  1149 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-01 09:01:20.928   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:20.928   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.928   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-01 09:01:20.928   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:20.928  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:20.928  1188  1188 D HotspotTile: updateTetherState():false, false
,07-01 09:01:20.928   764  1143 V NetworkStats: performPollLocked() took 2ms
07-01 09:01:20.928   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.928   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.928   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:20.978  7622  7674 D BluetoothAdapter: enable()
,07-01 09:01:20.978   764  3372 W ActivityManager: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-01 09:01:20.978   764  3372 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-01 09:01:20.978   764  3372 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 09:01:20.978   764  3372 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 09:01:20.978   764  3372 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-01 09:01:20.978   764  3372 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-01 09:01:20.978   764  3372 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-01 09:01:20.978   764  3372 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 09:01:20.978   764  3372 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 09:01:20.978   764  3372 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 09:01:20.978   764  3372 D SettingsProvider: name = bluetooth_on
,07-01 09:01:20.988   764  1055 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 09:01:20.988   764  1055 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 09:01:20.988   764  1055 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-01 09:01:20.988  3021  3076 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-01 09:01:20.988  3021  3076 D BluetoothAdapterProperties: Setting state to 11
07-01 09:01:20.988  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 09:01:20.988  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:20.988  3021  3076 D BluetoothAdapterService: updateAdapterState state is 11
,07-01 09:01:20.988  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:20.988  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-01 09:01:20.988  3021  3076 D BtConfig.SecureMode: isSecureModeOn:false
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 09:01:20.988  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:20.988  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-01 09:01:20.988   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:20.988   764   764 I InputMethodManagerService: [BT Setting State] State =11
,07-01 09:01:20.988  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-01 09:01:20.988  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:20.998  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:20.998  1696  1696 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 09:01:20.998  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 09:01:20.998   764  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:20.998   764  1484 D ActivityManager: caller:android.app.ApplicationThreadProxy@18ff2846, r.packageName :com.android.bluetooth
,07-01 09:01:20.998  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:20.998   764  1356 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:20.998   764  1677 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 09:01:20.998   764   779 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-01 09:01:20.998  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 09:01:20.998  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:20.998  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-01 09:01:20.998  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 09:01:20.998   764   779 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.998   764   779 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.998   764   779 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:20.998   764   779 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D QSpanel : label top:23
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:21.018  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:21.038  7899  7899 E Zygote  : MountEmulatedStorage()
07-01 09:01:21.038  7899  7899 E Zygote  : v2
07-01 09:01:21.038  7899  7899 I libpersona: KNOX_SDCARD checking this for 10014
07-01 09:01:21.038  7899  7899 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:21.048   764   779 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7899 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:21.048   764  1740 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:21.048   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b09b734, r.packageName :com.android.bluetooth
,07-01 09:01:21.048  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 09:01:21.048  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:21.048   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-01 09:01:21.048  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 09:01:21.048   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 09:01:21.048   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:21.078  7899  7899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:21.078  7899  7899 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:21.078  3021  3021 D HeadsetService: Received start request. Starting profile...
07-01 09:01:21.078  3021  3021 D HeadsetStateMachine: make
07-01 09:01:21.078   764  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.078   764  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@19f582d2, r.packageName :com.android.bluetooth
07-01 09:01:21.078  7899  7899 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 09:01:21.078  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-01 09:01:21.078   764  1344 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.078   764  1344 D ActivityManager: caller:android.app.ApplicationThreadProxy@172512a0, r.packageName :com.android.bluetooth
07-01 09:01:21.078  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:21.078  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,07-01 09:01:21.078  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 09:01:21.078   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 09:01:21.078  1903  1903 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:21.078   764  1740 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.078   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@2884fa1e, r.packageName :com.android.bluetooth
,07-01 09:01:21.078  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:21.078  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:21.078  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:21.078  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 09:01:21.078  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:21.078  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 09:01:21.078  3021  3021 E HeadsetStateMachine: # of Max HF connection is 2
,07-01 09:01:21.078   764  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:21.078   764  1356 D ActivityManager: caller:android.app.ApplicationThreadProxy@33d8b8cc, r.packageName :com.android.bluetooth
,07-01 09:01:21.088  7799  7799 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:21.088  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 09:01:21.088  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-01 09:01:21.088  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-01 09:01:21.088  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:21.088   764  1344 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
07-01 09:01:21.088   764  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.088   764  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@83e95b8, r.packageName :com.android.bluetooth
,07-01 09:01:21.088  1188  1188 D HotspotTile: onReceive : 1, 0
,07-01 09:01:21.088  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:21.088  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:21.088  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 09:01:21.088  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 09:01:21.088   764  1376 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-01 09:01:21.088  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:21.088  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 09:01:21.088  3021  3076 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-01 09:01:21.088  3021  3021 I bluedroid: get_profile_interface handsfree
,07-01 09:01:21.088  3021  3021 E DualScoManager: Dual Sco Manager already instantiated
07-01 09:01:21.088  3021  3021 I DualScoManager: Set HeadsetServiceHelper
07-01 09:01:21.088  3021  3021 D BluetoothAtMessage: createCMTIContentObservers
,07-01 09:01:21.088   764  1677 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-01 09:01:21.088   764  1677 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 09:01:21.088   764  1677 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 09:01:21.088   764  1677 D SettingsProvider: selectionArgs: false
07-01 09:01:21.088   764  1677 D SettingsProvider: selectionArgs: 1002
07-01 09:01:21.088   764  1677 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 09:01:21.088   764  1677 D SettingsProvider: ret = -1
,07-01 09:01:21.088  3021  7905 D HeadsetStateMachine: Enter Disconnected: -2
07-01 09:01:21.088  3021  7905 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-01 09:01:21.088  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:21.088  3021  3021 D A2dpService: Received start request. Starting profile...
07-01 09:01:21.088  3021  3021 V Avrcp   : make
07-01 09:01:21.088  3021  3021 V Avrcp   : Avrcp
07-01 09:01:21.088  3021  3021 I bluedroid: get_profile_interface avrcp
,07-01 09:01:21.098  3021  3021 V Avrcp   : start
07-01 09:01:21.098  3021  7905 D HeadsetStateMachine: map size, before remove : 0
07-01 09:01:21.098  3021  7905 D HeadsetStateMachine: map size, after remove: 0
07-01 09:01:21.098  3021  7905 D HeadsetStateMachine: mNextConnectingDevice : null
,07-01 09:01:21.098  3021  3021 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-01 09:01:21.098  3021  3021 V Avrcp   : ++registerMediaPlayers++
,07-01 09:01:21.098  1188  1188 D QSpanel : label top:23
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:21.098  3021  3021 I Avrcp   : No of Audio players :: 2
07-01 09:01:21.098  3021  3021 I Avrcp   : App Package name is com.google.android.music
,07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:21.098  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 09:01:21.098  3021  3021 I Avrcp   : App pkg name is Google Play Music
07-01 09:01:21.098  3021  3021 I Avrcp   : Name::Google Play Music
07-01 09:01:21.098  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-01 09:01:21.098  3021  3021 I Avrcp   : App Package name is com.sec.android.app.music
,07-01 09:01:21.098  3021  3021 I Avrcp   : App pkg name is Music
07-01 09:01:21.098  3021  3021 I Avrcp   : Name::Music
07-01 09:01:21.098  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-01 09:01:21.098  3021  3021 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-01 09:01:21.098  3021  3021 I Avrcp   : No of Video players :: 1
07-01 09:01:21.098  3021  3021 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-01 09:01:21.098  3021  3021 I Avrcp   : Video App pkg name is Video Player
07-01 09:01:21.098  3021  3021 I Avrcp   : Name::Video Player
07-01 09:01:21.098  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-01 09:01:21.098  3021  3021 I Avrcp   : Add tempPlayer
07-01 09:01:21.098  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-01 09:01:21.098  3021  3021 I Avrcp   : Total no of players: 4
07-01 09:01:21.098  3021  3021 V Avrcp   : swapping the samsung player with 1st player
07-01 09:01:21.098  3021  3021 I Avrcp   :  Updating now playing list upon AVRCP Start
07-01 09:01:21.098  3021  7909 V Avrcp   : handleMessage, msg=207
07-01 09:01:21.098  3021  7909 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-01 09:01:21.108  3021  3021 D A2dpStateMachine: make
,07-01 09:01:21.108  3021  3021 I bluedroid: get_profile_interface a2dp
,07-01 09:01:21.108  3021  7913 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 09:01:21.108  3021  3021 E bt-btif : warning : media task started media_task_refcnt 1 
,07-01 09:01:21.108  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:21.108  3021  7910 D A2dpStateMachine: Enter Disconnected: -2
,07-01 09:01:21.108  3021  3021 D HidService: Received start request. Starting profile...
07-01 09:01:21.108  3021  3021 I bluedroid: get_profile_interface hidhost
07-01 09:01:21.108  3021  3021 D HidService: setHidService(): set to: null
07-01 09:01:21.108  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:21.108  3021  3021 D HealthService: Received start request. Starting profile...
,07-01 09:01:21.108  3021  3021 I bluedroid: get_profile_interface health
,07-01 09:01:21.108  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:21.108  3021  7909 D BluetoothMediaBrowser: no now playing list
07-01 09:01:21.108  3021  7909 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-01 09:01:21.108  3021  7909 D Avrcp   :  checkNowPlayingList start
07-01 09:01:21.108  3021  3021 D PanService: Received start request. Starting profile...
07-01 09:01:21.108  3021  3021 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 09:01:21.108  3021  3021 I bluedroid: get_profile_interface pan
07-01 09:01:21.108  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:21.108  3021  3021 D BluetoothMapService: Received start request. Starting profile...
,07-01 09:01:21.118   764  1356 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
,07-01 09:01:21.118   764  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.118   764  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.118   764  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.118   764  1356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:21.128  7899  7899 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:21.128  7899  7899 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:21.158  7921  7921 E Zygote  : MountEmulatedStorage()
07-01 09:01:21.158  7921  7921 E Zygote  : v2
07-01 09:01:21.158  7921  7921 I libpersona: KNOX_SDCARD checking this for 10186
07-01 09:01:21.158  7921  7921 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:21.158   764  1356 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=7921 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-01 09:01:21.208  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:21.208  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:21.208  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:21.218  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:21.218  7921  7921 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:21.228  7899  7899 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-01 09:01:21.238  7921  7921 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-01 09:01:21.238  7921  7921 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-01 09:01:21.238  7921  7921 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 09:01:21.238  7921  7921 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-01 09:01:21.238  7921  7921 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-01 09:01:21.238  7921  7921 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 09:01:21.248   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-01 09:01:21.298   764  1244 I ActivityManager: Killing 6518:com.sec.knox.bridge/1000 (adj 15): emptyCount ##41
,07-01 09:01:21.308  7899  7899 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-01 09:01:21.308  7899  7899 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-01 09:01:21.328  7899  7899 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-01 09:01:21.338   764  1677 I ActivityManager: Killing 6578:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): emptyCount ##41
,07-01 09:01:21.338   764  1740 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 09:01:21.338   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@290de1da, r.packageName :com.google.android.gms
,07-01 09:01:21.348   764  1376 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 09:01:21.358  2138  2138 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-01 09:01:21.358  2138  7937 I iu.SyncManager: SYNC; picasa accounts
,07-01 09:01:21.368   764  1484 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 09:01:21.368   764  1484 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e55c60b, r.packageName :com.google.android.gms
,07-01 09:01:21.378  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:21.378  3021  3021 D HeadsetStateMachine: Try to query the phonestate on bind
,07-01 09:01:21.378  1409  1440 I Telecom : BluetoothPhoneService: queryPhoneState
,07-01 09:01:21.378  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-01 09:01:21.378  3021  3021 D HeadsetStateMachine: Proxy object connected
,07-01 09:01:21.378  3021  3021 D SapService: Received start request. Starting profile...
07-01 09:01:21.378  3021  3021 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-01 09:01:21.378  3021  3021 I bluedroid: get_profile_interface sap
07-01 09:01:21.378  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:21.378  3021  3021 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-01 09:01:21.378  3021  3021 D HeadsetPhoneState: sendDeviceDataStateChanged
07-01 09:01:21.378  3021  3021 D HeadsetPhoneState: Signal level : previous=0 curr=1
07-01 09:01:21.378  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-01 09:01:21.378  3021  7905 D HeadsetStateMachine: Disconnected process message: 11
07-01 09:01:21.378  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 09:01:21.378  3021  7905 D HeadsetStateMachine: Disconnected process message: 18
07-01 09:01:21.378  3021  7905 D HeadsetStateMachine: Disconnected process message: 10
07-01 09:01:21.378  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-01 09:01:21.378  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-01 09:01:21.378  3021  7905 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 09:01:21.378  3021  7905 D HeadsetStateMachine: Disconnected process message: 11
07-01 09:01:21.378  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,07-01 09:01:21.378  2138  7937 I iu.UploadsManager: num queued entries: 0
,07-01 09:01:21.378  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-01 09:01:21.388  2138  2138 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
07-01 09:01:21.388  2138  2138 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-01 09:01:21.388  2138  2138 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-01 09:01:21.388  2138  2138 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-01 09:01:21.388  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-01 09:01:21.388  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-01 09:01:21.388  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-01 09:01:21.388  3021  3076 I bluedroid: enable
,07-01 09:01:21.388  4197  4197 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 09:01:21.388  3021  3079 E bt-btif : Calling BTA_HhEnable
07-01 09:01:21.388  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:21.388  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:21.388  3021  3079 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-01 09:01:21.388  3021  3079 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-01 09:01:21.388  3021  3079 E BluetoothServiceJni: populateRssiValuesNative
07-01 09:01:21.388  3021  3079 I bluedroid: getModelRssiValues
07-01 09:01:21.388  3021  3079 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-01 09:01:21.388  3021  3079 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-01 09:01:21.388  3021  3082 D bt_vendor: op for 7
,07-01 09:01:21.398   764   764 D SettingsProvider: name = bluetooth_name
07-01 09:01:21.398  3021  3082 D bt_upio : proc btwrite assertion
07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: Name is: Galaxy Note3
,07-01 09:01:21.398  4197  4197 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467356481406
07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-01 09:01:21.398  3021  3079 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-01 09:01:21.398  3021  3079 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
07-01 09:01:21.398  3021  3079 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-01 09:01:21.398  3021  3079 E bt-btif : JVenable fails
07-01 09:01:21.398  3021  3079 D bte_conf: Device ID record 1 : primary
07-01 09:01:21.398  3021  3079 D bte_conf:   vendorId            = 0075
07-01 09:01:21.398  3021  3079 D bte_conf:   vendorIdSource      = 0001
07-01 09:01:21.398  3021  3079 D bte_conf:   product             = 0100
07-01 09:01:21.398  3021  3079 D bte_conf:   version             = 0200
07-01 09:01:21.398  3021  3079 D bte_conf:   clientExecutableURL = 
07-01 09:01:21.398  3021  3079 D bte_conf:   serviceDescription  = 
07-01 09:01:21.398  3021  3079 D bte_conf:   documentationURL    = 
07-01 09:01:21.398  3021  3079 D bte_conf: bte_load_did_conf no section named DID2.
07-01 09:01:21.398  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:21.398  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 09:01:21.398  3021  3076 D BluetoothAdapterProperties: ScanMode =  20
07-01 09:01:21.398  3021  3076 D BluetoothAdapterProperties: State =  11
07-01 09:01:21.398  3021  3079 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-01 09:01:21.398  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.398  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.398   764  3372 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 09:01:21.398  3021  3076 D BluetoothAdapterProperties: Setting state to 12
07-01 09:01:21.398  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: Scan Mode:21
07-01 09:01:21.398  3021  3079 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:21.398  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.398  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.398  4197  4197 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:21.398   764   778 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-01 09:01:21.398   764   778 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 09:01:21.398   764   778 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 09:01:21.398   764   778 D SettingsProvider: selectionArgs: false
07-01 09:01:21.398   764   778 D SettingsProvider: selectionArgs: 1002
07-01 09:01:21.398   764   778 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 09:01:21.398   764   778 D SettingsProvider: ret = -1
,07-01 09:01:21.398  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.398  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.398  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:21.398  3021  3076 D BluetoothAdapterService: updateAdapterState state is 12
,07-01 09:01:21.398   764   778 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.398   764   778 D ActivityManager: caller:android.app.ApplicationThreadProxy@2722ef01, r.packageName :com.android.bluetooth
07-01 09:01:21.398  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.398  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:21.398  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:21.398   764  1740 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:21.398  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:21.398  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-01 09:01:21.398  3021  3076 D BluetoothAdapterService: starting service from this receiver
07-01 09:01:21.398  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.398  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.398  4217  4226 D Bluetoothsap: onBluetoothStateChange: up=true
07-01 09:01:21.398  4217  4226 D Bluetoothsap: Binding service...
07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.408  3021  3021 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-01 09:01:21.408  3021  3021 I BluetoothPbapService: Handler(): got msg=1
,07-01 09:01:21.408  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:21.408   764  1573 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.408   764  1573 D ActivityManager: caller:android.app.ApplicationThreadProxy@2598b7e7, r.packageName :com.android.bluetooth
,07-01 09:01:21.408  4217  4226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.408  3021  3076 I BluetoothAdapterState: Entering On State from state = 11
07-01 09:01:21.408   764  1223 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:21.408   764  1223 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-01 09:01:21.408   764  1740 I ActivityManager: Killing 6837:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-01 09:01:21.408  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.408  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:21.418  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.418   764  1244 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.418   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.418   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.418   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:21.418  4197  4197 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.418  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:21.418  3021  7944 V BluetoothPbapService: PBAP Service initSocket try: 0
07-01 09:01:21.418  4197  4197 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-01 09:01:21.418  2138  7937 I iu.UploadsManager: num updated entries: 0
07-01 09:01:21.418  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.418  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.428  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:21.428  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:21.428  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.428  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.428  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.428  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.428  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.428   764   779 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 09:01:21.438   764  1114 V AlarmManager: waitForAlarm result :4
,07-01 09:01:21.448  2138  7937 I iu.SyncManager: NEXT; no task
,07-01 09:01:21.478   764  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:21.478   764  1740 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4288, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 09:01:21.478   764  1740 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-01 09:01:21.478   764  1740 D BatteryService: stay LED for fully charged
07-01 09:01:21.478   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:01:21.508  7948  7948 E Zygote  : MountEmulatedStorage()
07-01 09:01:21.508  7948  7948 E Zygote  : v2
07-01 09:01:21.508  7948  7948 I libpersona: KNOX_SDCARD checking this for 10092
07-01 09:01:21.508  7948  7948 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:21.518   764  1244 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7948 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-01 09:01:21.518   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-01 09:01:21.518  4217  4226 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-01 09:01:21.518   764  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-01 09:01:21.518   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.518   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.518   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.518   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:21.548  7948  7948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:21.548  7948  7948 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:21.548  4217  4229 D BluetoothPan: Binding service...
,07-01 09:01:21.548  3021  7944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:21.548  7948  7948 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-01 09:01:21.558  7958  7958 E Zygote  : MountEmulatedStorage()
07-01 09:01:21.558  7958  7958 E Zygote  : v2
07-01 09:01:21.558  7958  7958 I libpersona: KNOX_SDCARD checking this for 10036
07-01 09:01:21.558  7958  7958 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:21.568   764  1223 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7958 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-01 09:01:21.578   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-01 09:01:21.578   764   764 I MotionRecognitionService: Plugged
07-01 09:01:21.578   764   764 I MotionRecognitionService: setPowerConnected  = true
,07-01 09:01:21.588  7958  7958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 09:01:21.588  7958  7958 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:21.588  7948  7948 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:21.588  7958  7958 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-01 09:01:21.588   764  1677 D RCPManagerService: exchangeData() failure , invalid userId
07-01 09:01:21.588  7948  7948 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:21.588  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-01 09:01:21.588  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:01:21.588  3021  7944 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-01 09:01:21.588  3021  7944 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 09:01:21.588  3021  7944 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 09:01:21.588  3021  7944 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@176483aa
07-01 09:01:21.588  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.588  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.588  3021  7944 D BluetoothSocket: channel: 19
07-01 09:01:21.588  3021  7944 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-01 09:01:21.588  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 09:01:21.588  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:01:21.588  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:01:21.588  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:01:21.588  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-01 09:01:21.598  4217  4217 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-01 09:01:21.598  4217  4217 D SapProfile: Bluetooth service connected
,07-01 09:01:21.598  4217  4217 D Bluetoothsap: getConnectedDevices()
,07-01 09:01:21.598   764  1344 I ActivityManager: Killing 3902:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,07-01 09:01:21.598   764  1055 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.598  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 09:01:21.598  1433  1453 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:21.598  3021  7905 D HeadsetStateMachine: Disconnected process message: 10
07-01 09:01:21.598   764  1055 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 09:01:21.598   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-01 09:01:21.598  4217  4229 D BluetoothPbap: onBluetoothStateChange: up=true
,07-01 09:01:21.608   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-01 09:01:21.608  3021  3035 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 09:01:21.608   764  1055 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:21.608  3021  3021 D BluetoothA2dp: Proxy object connected
07-01 09:01:21.608  3192  3204 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:21.608  3021  3021 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-01 09:01:21.608   764  1055 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:21.608   764   764 D BluetoothA2dp: Proxy object connected
,07-01 09:01:21.608  3192  3192 D BluetoothA2dp: Proxy object connected
,07-01 09:01:21.608  4217  7954 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-01 09:01:21.608  4217  4217 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 09:01:21.608  4217  4217 D PanProfile: Bluetooth service connected
,07-01 09:01:21.608   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-01 09:01:21.638  4217  4229 D BluetoothMap: onBluetoothStateChange: up=true
,07-01 09:01:21.638  1188  1188 D KeyguardUpdateMonitor: handleTimeUpdate
07-01 09:01:21.638  1188  1188 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-01 09:01:21.638  1188  1188 I KeyguardEffectViewController: *** don't update sliding image ***
,07-01 09:01:21.638  7958  7958 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:21.638  7958  7958 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:21.648   764  3348 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 09:01:21.648  4217  4217 D BluetoothPbap: Proxy object connected
07-01 09:01:21.648  4217  4217 D PbapServerProfile: Bluetooth service connected
07-01 09:01:21.648  4217  4217 D BluetoothInputDevice: Proxy object connected
07-01 09:01:21.648  4217  4217 D HidProfile: Bluetooth service connected
,07-01 09:01:21.648  7948  7948 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-01 09:01:21.658  7948  7948 D BadgeProvider: onCreate
,07-01 09:01:21.668  7948  7948 D BadgeProvider: DatabaseHelper
,07-01 09:01:21.728   764  1055 I art     : Explicit concurrent mark sweep GC freed 42590(2MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 35MB/51MB, paused 1.481ms total 90.491ms
,07-01 09:01:21.738   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-01 09:01:21.738   764  1055 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.748  4217  4217 D BluetoothMap: Proxy object connected
,07-01 09:01:21.748  4217  4217 D MapProfile: Bluetooth service connected
,07-01 09:01:21.758  3192  3206 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:21.758  7948  7957 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-01 09:01:21.758  7958  7958 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-01 09:01:21.758   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.758  4217  7954 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:21.758  4217  4217 D HeadsetProfile: Bluetooth service connected
07-01 09:01:21.758   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 09:01:21.758   764  1055 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:21.768  7958  7958 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 09:01:21.768  7958  7958 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-01 09:01:21.768   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.768  1409  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:21.768   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.768  1409  1440 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:21.768   764  1055 D BluetoothPan: Binding service...
,07-01 09:01:21.768   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-01 09:01:21.768   764   764 D BluetoothPan: BluetoothPAN Proxy object connected
,07-01 09:01:21.768   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:21.768  1409  1421 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:21.768  4217  4229 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 09:01:21.778   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:21.778  4217  4217 D BluetoothA2dp: Proxy object connected
07-01 09:01:21.778  4217  4217 D A2dpProfile: Bluetooth service connected
,07-01 09:01:21.778   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-01 09:01:21.778  7948  7957 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-01 09:01:21.778  7948  7957 D BadgeProvider: sendNotify, [notify] : null
,07-01 09:01:21.778  7948  7957 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-01 09:01:21.778   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.778  7948  7957 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-01 09:01:21.778   764   764 I InputMethodManagerService: [BT Setting State] State =12
07-01 09:01:21.778  7948  7957 D BadgeProvider: update, [UpdateCount] : 1
07-01 09:01:21.778   764   764 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 09:01:21.778  1455  1455 D Launcher.Model: reloadBadges entered.
,07-01 09:01:21.778  1409  1409 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@39010de1, true
,07-01 09:01:21.778  1409  1409 D BluetoothHeadset: registerMessageListener
,07-01 09:01:21.778  1696  1696 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 09:01:21.778  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:21.788  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:21.788  3021  3035 D HeadsetService: registerMessageListener
07-01 09:01:21.788  3021  3035 D HeadsetService: registerMessageListener
07-01 09:01:21.788  3021  7905 D HeadsetStateMachine: Disconnected process message: 70
07-01 09:01:21.788  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-01 09:01:21.788  3021  7905 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@8de5b38
,07-01 09:01:21.788  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-01 09:01:21.788  4217  4217 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-01 09:01:21.788  4217  4217 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-01 09:01:21.788  3021  7905 D HeadsetStateMachine: Disconnected process message: 9
07-01 09:01:21.788  3021  7905 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-01 09:01:21.788  3021  7982 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-01 09:01:21.788   307  1570 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-01 09:01:21.788   307  1570 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-01 09:01:21.788   307  1570 V voice   : voice_set_parameters: exit with code(-2)
07-01 09:01:21.788   307  1570 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-01 09:01:21.788   307  1570 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-01 09:01:21.788   307  1570 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-01 09:01:21.788   307  1570 V audio_hw_primary: adev_set_parameters: exit
07-01 09:01:21.788  3021  7905 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-01 09:01:21.788  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 09:01:21.788  1188  1188 D BluetoothTile:  onBluetoothStateChange:
,07-01 09:01:21.788  3021  7982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 09:01:21.798  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-01 09:01:21.798  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.798  3021  7982 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-01 09:01:21.798  3021  7982 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 09:01:21.798  3021  7982 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 09:01:21.798  3021  7982 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bc81711
07-01 09:01:21.798  3021  7982 D BluetoothSocket: channel: 5
07-01 09:01:21.798  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.798  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.798   764  1441 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:21.798   764   779 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-01 09:01:21.808  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-01 09:01:21.808  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:21.808  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
07-01 09:01:21.808  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 09:01:21.828  7958  7958 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D QSpanel : label top:23
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:21.828  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:21.838   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:21.838   764  1677 I ActivityManager: Killing 7233:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-01 09:01:21.848   764   778 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-01 09:01:21.848   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.848   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.848   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:21.848   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:21.888  7983  7983 E Zygote  : MountEmulatedStorage()
07-01 09:01:21.888  7983  7983 E Zygote  : v2
07-01 09:01:21.888  7983  7983 I libpersona: KNOX_SDCARD checking this for 10042
07-01 09:01:21.888  7983  7983 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:21.888   764   778 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7983 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-01 09:01:21.928  7983  7983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:21.928  7983  7983 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:21.928  7983  7983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:21.958  7983  7983 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:21.958  7983  7983 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:21.968  7983  7983 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-01 09:01:21.988  7622  7674 D BluetoothAdapter: disable()
,07-01 09:01:21.988   764  1344 D SettingsProvider: name = bluetooth_on
07-01 09:01:21.988   764  3372 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-01 09:01:21.998  3021  3076 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-01 09:01:21.998  3021  3076 D BluetoothAdapterProperties: Setting state to 13
07-01 09:01:21.998  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-01 09:01:21.998  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:21.998  3021  3076 D BluetoothAdapterService: updateAdapterState state is 13
,07-01 09:01:21.998   764   779 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:21.998   764   779 D ActivityManager: caller:android.app.ApplicationThreadProxy@10fa2daf, r.packageName :com.android.bluetooth
07-01 09:01:21.998  3021  3021 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-01 09:01:21.998  3021  3021 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@235f3076, channel: 19, state: LISTENING
07-01 09:01:21.998  3021  3021 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@235f3076, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@176483aa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18fc677mSocket: android.net.LocalSocket@2fb9f2e4 impl:android.net.LocalSocketImpl@3a86134d fd:FileDescriptor[78]
07-01 09:01:21.998  3021  3021 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fb9f2e4 impl:android.net.LocalSocketImpl@3a86134d fd:FileDescriptor[78]
07-01 09:01:21.998  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:21.998  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-01 09:01:21.998  3021  3076 D BluetoothAdapterService: terminating service from this receiver
,07-01 09:01:21.998  3021  3076 D BluetoothAdapterProperties: onBluetoothDisable()
,07-01 09:01:21.998  7983  7983 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
07-01 09:01:21.998   764  1356 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 09:01:21.998  3021  3076 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-01 09:01:21.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.998  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.998   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.998   764   764 I InputMethodManagerService: [BT Setting State] State =13
,07-01 09:01:21.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.998  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:21.998  4217  4217 D BluetoothPbap: Proxy object disconnected
07-01 09:01:21.998  4217  4217 D PbapServerProfile: Bluetooth service disconnected
,07-01 09:01:21.998  1188  1188 D BluetoothTile:  onBluetoothStateChange:
07-01 09:01:21.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.998  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.998  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:21.998  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:21.998  3021  3079 D BluetoothAdapterProperties: Scan Mode:20
,07-01 09:01:21.998  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-01 09:01:21.998  3021  3076 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-01 09:01:21.998  3021  3076 E bt-btif : BTA got event 0x1a12
07-01 09:01:21.998  3021  3080 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-01 09:01:21.998  3021  3082 D bt_vendor: op for 7
07-01 09:01:21.998  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:21.998  3021  3076 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 09:01:22.008   764  1344 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:22.008  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.008  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.008  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.008  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
,07-01 09:01:22.008   764  1441 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 09:01:22.008   764  1376 I ActivityManager: Killing 7254:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
07-01 09:01:22.008  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.008  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 09:01:22.008  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
07-01 09:01:22.008  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:22.008  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 09:01:22.008  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-01 09:01:22.008  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.008  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.008  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.008  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:22.008  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:22.008  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:22.008  1696  1696 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 09:01:22.008  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-01 09:01:22.018  3021  3080 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-01 09:01:22.018  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.018  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.018  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.018  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.018  3021  3082 D bt_vendor: op for 7
07-01 09:01:22.018  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:22.028  3021  3021 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@d305313, channel: 5, state: LISTENING
,07-01 09:01:22.028  3021  3021 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@d305313, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@bc81711, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a955950mSocket: android.net.LocalSocket@6ad9749 impl:android.net.LocalSocketImpl@777d84e fd:FileDescriptor[80]
07-01 09:01:22.028  3021  3021 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6ad9749 impl:android.net.LocalSocketImpl@777d84e fd:FileDescriptor[80]
,07-01 09:01:22.028   764  3348 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:22.028  7291  7291 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,07-01 09:01:22.028  1188  1188 D QSpanel : label top:23
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:22.028  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 09:01:22.028  3511  8000 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-01 09:01:22.038   764  1474 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:22.038   764  1573 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-01 09:01:22.038   764  1573 D ActivityManager: caller:android.app.ApplicationThreadProxy@38caf5bc, r.packageName :com.sec.spp.push
,07-01 09:01:22.038  7009  7009 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-01 09:01:22.038  7009  7009 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-01 09:01:22.038  7009  7009 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-01 09:01:22.038  3511  8000 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-01 09:01:22.038  3511  8000 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-01 09:01:22.038  3511  8000 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-01 09:01:22.038  7009  7009 I SA      : [SLFUCHKMGR] constructor called
,07-01 09:01:22.038  3511  8000 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-01 09:01:22.048  7291  8001 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-01 09:01:22.048  7009  7009 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-01 09:01:22.048  7009  7009 I SA      : [OR] == isSIMCardReady false ==
07-01 09:01:22.048  7009  7009 I SA      : [SCU] == networkStateCheck == false
07-01 09:01:22.048  7009  7009 I SA      : [OR] onReceive END
,07-01 09:01:22.058   764  3372 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-01 09:01:22.058   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.058   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.058   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.058   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.138  8005  8005 E Zygote  : MountEmulatedStorage()
,07-01 09:01:22.138  8005  8005 E Zygote  : v2
07-01 09:01:22.138  8005  8005 I libpersona: KNOX_SDCARD checking this for 10074
07-01 09:01:22.138  8005  8005 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:22.148   764  3372 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=8005 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-01 09:01:22.158   338   338 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 297us total 12.713ms
,07-01 09:01:22.168  8005  8005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:22.168  8005  8005 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:22.168  8005  8005 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:22.178   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 283us total 9.968ms
,07-01 09:01:22.188  8005  8005 D TimaKeyStoreProvider: TimaSignature is unavailable
07-01 09:01:22.188   338   338 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.543ms
,07-01 09:01:22.188  8005  8005 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:22.198  8005  8005 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-01 09:01:22.198  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-01 09:01:22.198  3021  3076 D BtConfig.SecureMode: isSecureModeOn:false
07-01 09:01:22.198  3021  3076 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-01 09:01:22.198  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
07-01 09:01:22.198  3021  3076 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-01 09:01:22.198  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 09:01:22.198  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:22.198  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-01 09:01:22.198   764  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208   764  1484 D ActivityManager: caller:android.app.ApplicationThreadProxy@2fe5f89a, r.packageName :com.android.bluetooth
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-01 09:01:22.208  3021  3021 D HeadsetService: Received stop request...Stopping profile...
07-01 09:01:22.208   764  3372 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208   764  3372 D ActivityManager: caller:android.app.ApplicationThreadProxy@17c5f5cb, r.packageName :com.android.bluetooth
,07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 09:01:22.208  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:22.208  4217  4217 D HeadsetProfile: Bluetooth service disconnected
,07-01 09:01:22.208   764  1223 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208  7759  7759 W BluetoothHeadset: Proxy not attached to service
,07-01 09:01:22.208   764  1223 D ActivityManager: caller:android.app.ApplicationThreadProxy@162fb1a8, r.packageName :com.android.bluetooth
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:22.208   764   764 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-01 09:01:22.208   764  1484 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208   764  1484 D ActivityManager: caller:android.app.ApplicationThreadProxy@a6004c1, r.packageName :com.android.bluetooth
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:22.208  3021  3021 D A2dpService: Received stop request...Stopping profile...
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-01 09:01:22.208  3021  3021 V Avrcp   : doQuit
07-01 09:01:22.208  3021  7910 D A2dpStateMachine: Exit Disconnected: -1
,07-01 09:01:22.208   764  1441 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208   764  1441 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a9b0466, r.packageName :com.android.bluetooth
,07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.208  3021  3021 D Avrcp   : Unregistering previous receiver
07-01 09:01:22.208   764  3348 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:22.208   764  3348 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c3c23a7, r.packageName :com.android.bluetooth
,07-01 09:01:22.208  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-01 09:01:22.208   764  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:22.208   764  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@12a24054, r.packageName :com.android.bluetooth
,07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 09:01:22.208   764   764 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 09:01:22.208   764   764 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-01 09:01:22.208  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:22.208  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 09:01:22.208  3021  3076 D BluetoothAdapterState: Stopping profile services that were post enabled
07-01 09:01:22.208  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-01 09:01:22.208  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:22.208  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-01 09:01:22.218  3021  3021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-01 09:01:22.218  3021  3021 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-01 09:01:22.218  3021  3021 D HidService: Received stop request...Stopping profile...
07-01 09:01:22.218  3021  3021 D HidService: Stopping Bluetooth HidService
07-01 09:01:22.218  3021  3021 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-01 09:01:22.218  3021  3021 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-01 09:01:22.218  3021  3021 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:22.218  3021  3021 D HealthService: Received stop request...Stopping profile...
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-01 09:01:22.218  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-01 09:01:22.218  3021  3021 D PanService: Received stop request...Stopping profile...
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:22.218   764   764 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-01 09:01:22.218  3021  3021 D BluetoothMapService: Received stop request...Stopping profile...
,07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:22.218  3021  3021 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-01 09:01:22.218  3021  7913 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-01 09:01:22.218  3021  3021 I GKI_LINUX: GKI_exit_task 2 done
07-01 09:01:22.218  3021  3021 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-01 09:01:22.218  3021  3021 V Avrcp   : cleanup
,07-01 09:01:22.218  3021  3021 D SapService: Received stop request...Stopping profile...
07-01 09:01:22.218  3021  3021 D SapService: Stopping Bluetooth SapService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:22.218  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:22.218  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.218  3021  3021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-01 09:01:22.218  3021  3021 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:22.218  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:22.218  3021  3021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-01 09:01:22.218  3021  3021 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:22.218  3021  3021 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-01 09:01:22.218  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-01 09:01:22.218  3021  3021 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-01 09:01:22.218  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-01 09:01:22.218  3021  3076 D BluetoothAdapterProperties: Setting state to 10
07-01 09:01:22.218  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-01 09:01:22.218  3021  3021 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-01 09:01:22.218  3021  3021 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-01 09:01:22.218  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-01 09:01:22.218  3021  3076 D BluetoothAdapterService: updateAdapterState state is 10
07-01 09:01:22.228  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:22.228  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-01 09:01:22.228  3021  3076 I BluetoothAdapterState: Entering OffState
07-01 09:01:22.228  4217  4229 D Bluetoothsap: onBluetoothStateChange: up=false
07-01 09:01:22.228  4217  4229 D Bluetoothsap: Unbinding service...
07-01 09:01:22.228  3192  3192 D BluetoothA2dp: Proxy object disconnected
,07-01 09:01:22.228  4217  4217 D BluetoothA2dp: Proxy object disconnected
07-01 09:01:22.228  4217  4217 D A2dpProfile: Bluetooth service disconnected
,07-01 09:01:22.228   764  1055 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 09:01:22.228  4217  4217 D BluetoothInputDevice: Proxy object disconnected
07-01 09:01:22.228  4217  4217 D HidProfile: Bluetooth service disconnected
07-01 09:01:22.228  4217  7954 D BluetoothPbap: onBluetoothStateChange: up=false
07-01 09:01:22.228  4217  4217 D BluetoothMap: Proxy object disconnected
07-01 09:01:22.228  4217  4217 D MapProfile: Bluetooth service disconnected
07-01 09:01:22.228  3021  3035 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:22.228  3192  3451 D BluetoothA2dp: onBluetoothStateChange: up=false
07-01 09:01:22.228  4217  4229 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-01 09:01:22.228  4217  4226 D BluetoothMap: onBluetoothStateChange: up=false
,07-01 09:01:22.228  4217  4229 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-01 09:01:22.228   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.228   764   764 I InputMethodManagerService: [BT Setting State] State =10
07-01 09:01:22.228   764   764 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 09:01:22.228  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:22.228  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:22.228  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:22.228  1696  1696 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-01 09:01:22.228  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:22.238   764  1484 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:22.238   764  1356 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-01 09:01:22.238  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-01 09:01:22.238  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D QSpanel : label top:23
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:22.248  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:22.268  8005  8005 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-01 09:01:22.268  8005  8005 I SCloudBackupReceiver: Other Intent
,07-01 09:01:22.268   764  3348 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-01 09:01:22.268   764  3348 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.268   764  3348 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.268   764  3348 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.268   764  3348 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.308  8021  8021 E Zygote  : MountEmulatedStorage()
,07-01 09:01:22.308  8021  8021 E Zygote  : v2
07-01 09:01:22.308  8021  8021 I libpersona: KNOX_SDCARD checking this for 1000
07-01 09:01:22.308  8021  8021 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:22.318   764  3348 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=8021 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-01 09:01:22.318   764  3348 I ActivityManager: Killing 6270:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-01 09:01:22.348  8021  8021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:22.348  8021  8021 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:22.348  8021  8021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:22.368  8021  8021 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:22.368  8021  8021 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:22.378  8021  8021 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,07-01 09:01:22.378  8021  8021 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-01 09:01:22.388  8021  8021 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-01 09:01:22.388  8021  8021 I KnoxUsageLogPro: premStatus:2
,07-01 09:01:22.398  8021  8021 I KnoxUsageLogPro: isEulaShown : false
07-01 09:01:22.398  8021  8021 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-01 09:01:22.398   764  1244 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-01 09:01:22.398   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.398   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.398   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.398   764  1244 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.438  8036  8036 E Zygote  : MountEmulatedStorage()
07-01 09:01:22.438  8036  8036 E Zygote  : v2
07-01 09:01:22.438  8036  8036 I libpersona: KNOX_SDCARD checking this for 10104
07-01 09:01:22.438  8036  8036 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:22.448   764  1244 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8036 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:22.448   764  1244 I ActivityManager: Killing 6386:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-01 09:01:22.478  8036  8036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:22.478  8036  8036 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:22.478  8036  8036 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-01 09:01:22.498  8036  8036 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:22.498  8036  8036 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:22.518  8036  8036 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-01 09:01:22.548   296   296 E SMD     : DCD ON
,07-01 09:01:22.588   764  3372 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-01 09:01:22.588   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.588   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.588   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:22.588   764  3372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:22.628  8052  8052 E Zygote  : MountEmulatedStorage()
07-01 09:01:22.628  8052  8052 E Zygote  : v2
07-01 09:01:22.628  8052  8052 I libpersona: KNOX_SDCARD checking this for 10146
07-01 09:01:22.628  8052  8052 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:22.638   764  3372 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8052 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:22.638   764  3372 I ActivityManager: Killing 6479:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-01 09:01:22.658  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-01 09:01:22.658  7622  7682 I jxcore-log: 
,07-01 09:01:22.668  8052  8052 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:22.668  8052  8052 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:22.668  8052  8052 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-01 09:01:22.688  8052  8052 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:22.688  8052  8052 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:22.698  8052  8052 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-01 09:01:22.888   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-01 09:01:22.888   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:22.888  8052  8070 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-01 09:01:22.908   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-01 09:01:22.908   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:22.908  8052  8070 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-01 09:01:22.918   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-01 09:01:22.918   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:22.918  8052  8073 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-01 09:01:22.918   265   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-01 09:01:22.918   265   547 W Vold    : Returning OperationFailed - no handler for errno 0
,07-01 09:01:22.918  8052  8073 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-01 09:01:22.998  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:22.998  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-01 09:01:23.068  8052  8052 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-01 09:01:23.068  8052  8052 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-01 09:01:23.078  8052  8052 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 744-747)
,07-01 09:01:23.078  8052  8052 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 09:01:23.088  8052  8052 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c3710c1}
,07-01 09:01:23.088  8052  8052 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-01 09:01:23.088  8052  8052 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-01 09:01:23.088  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-01 09:01:23.088  7622  7682 I jxcore-log: 
,07-01 09:01:23.108  8052  8052 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-01 09:01:23.108  8052  8052 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-01 09:01:23.108  8052  8052 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 09:01:23.118  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-01 09:01:23.118  7622  7682 I jxcore-log: 
,07-01 09:01:23.118  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-01 09:01:23.118  7622  7682 I jxcore-log: 
,07-01 09:01:23.128  8052  8052 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-01 09:01:23.128  8052  8052 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-01 09:01:23.128  8052  8052 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-01 09:01:23.138  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-01 09:01:23.138  7622  7682 I jxcore-log: 
,07-01 09:01:23.138  8052  8052 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-01 09:01:23.138  8052  8052 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-01 09:01:23.138  8052  8052 I Adreno-EGL: Build Date: 11/19/14 Wed
07-01 09:01:23.138  8052  8052 I Adreno-EGL: Local Branch: mybranch5813579
07-01 09:01:23.138  8052  8052 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-01 09:01:23.138  8052  8052 I Adreno-EGL: Local Patches: NONE
07-01 09:01:23.138  8052  8052 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-01 09:01:23.138  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-01 09:01:23.138  7622  7682 I jxcore-log: 
,07-01 09:01:23.218  8052  8052 I NSApplication: Starting up...
,07-01 09:01:23.218  8052  8100 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-01 09:01:23.228   764  1543 I ActivityManager: Killing 6249:com.sec.android.app.shealth/u0a40 (adj 15): emptyCount ##41
,07-01 09:01:23.288   764  1223 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-01 09:01:23.288   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:23.288   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:23.288   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:23.288   764  1223 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:23.328  8107  8107 E Zygote  : MountEmulatedStorage()
,07-01 09:01:23.328  8107  8107 E Zygote  : v2
07-01 09:01:23.328  8107  8107 I libpersona: KNOX_SDCARD checking this for 10158
07-01 09:01:23.328  8107  8107 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:23.338   764  1223 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8107 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-01 09:01:23.378  8107  8107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:23.378  8107  8107 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:23.378  8107  8107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-01 09:01:23.398  3021  3199 D bt_upio : ..proc_btwrite_timeout..
,07-01 09:01:23.398  8107  8107 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:23.398  8107  8107 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:23.408  8107  8107 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-01 09:01:23.408  8107  8107 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-01 09:01:23.408  8107  8107 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-01 09:01:23.408  8107  8107 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-01 09:01:23.428  8107  8107 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:23.428  8107  8107 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-01 09:01:23.428  8107  8107 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-01 09:01:23.448   764  1474 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 09:01:23.458   764  1740 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.458  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:23.458  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:23.458  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:23.458  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:23.458   764  1441 I ActivityManager: Killing 7315:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-01 09:01:23.458   764   778 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-01 09:01:23.468   764  1344 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.468   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:23.468   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:23.468   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:23.468   764   778 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:23.468   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.508  8122  8122 E Zygote  : MountEmulatedStorage()
,07-01 09:01:23.508  8122  8122 E Zygote  : v2
07-01 09:01:23.508  8122  8122 I libpersona: KNOX_SDCARD checking this for 10200
07-01 09:01:23.508  8122  8122 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:23.518   764   778 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8122 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:23.518  3021  3082 D bt_vendor: op for 7
,07-01 09:01:23.548  8122  8122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:23.548  8122  8122 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:23.548  8122  8122 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-01 09:01:23.568  8122  8122 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:23.568  8122  8122 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:23.578  8122  8122 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-01 09:01:23.608   764  1376 I ActivityManager: Killing 5953:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-01 09:01:23.618  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:23.618   764  3348 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.618  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:23.618  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:23.618  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:23.618  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:23.628  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:23.628   764  1223 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:23.628  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:23.628  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:23.628  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:23.628  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:23.638  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 09:01:23.638  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 09:01:23.638  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:23.638   764  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:23.638  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:23.638  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:23.638   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:23.638  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:23.638  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 09:01:23.638  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:23.648  6503  6503 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 09:01:23.648  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 09:01:23.648  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-01 09:01:23.648  7784  7784 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 09:01:23.648  7784  7784 D WifiDirectBR: stopServiceTest : false
,07-01 09:01:23.648  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 09:01:23.658  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 09:01:23.658  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-01 09:01:23.658   764  1344 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.658  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:23.668   764  1484 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-01 09:01:23.668  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:23.668  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:23.668  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 09:01:23.668  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:23.668   764  1441 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.668  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:23.678  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:23.678  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:23.678   764  1543 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:23.678  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:23.678  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:23.678  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:23.688  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:23.698  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:23.708  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:23.708   764  1740 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:23.708  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:23.708  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:23.708  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:23.708  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:23.718  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 09:01:23.718   764  1474 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-01 09:01:23.718   764  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@14f4adc6, r.packageName :com.android.settings
,07-01 09:01:23.728  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:23.728  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:23.728  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:23.738  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:23.738  3021  3021 D BtConfig.SecureMode: isSecureModeOn:false
,07-01 09:01:23.738   764  3372 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:23.738   764  3372 D ActivityManager: caller:android.app.ApplicationThreadProxy@200c78b4, r.packageName :com.android.bluetooth
,07-01 09:01:23.748  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 09:01:23.748   764  1244 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-01 09:01:23.748   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@17c9f9d9, r.packageName :com.android.settings
,07-01 09:01:23.748  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:23.758  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:23.758  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:23.768  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 09:01:23.768   764  1740 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-01 09:01:23.768   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@23521a7f, r.packageName :com.android.settings
,07-01 09:01:23.768  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:23.768  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:23.778  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:23.998  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:23.998  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:23.998  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:23.998  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a935202 removed from the list
,07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e1ed50 added. We now have 2 listener(s)
07-01 09:01:23.998  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:23.998  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:23.998  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:23.998  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:23.998  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e1ed50 removed from the list
,07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:23.998  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c609b49 added. We now have 2 listener(s)
07-01 09:01:23.998  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:23.998  7622  7674 D BluetoothAdapter: disable()
,07-01 09:01:23.998   764  1474 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-01 09:01:23.998  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:23.998  7622  7674 D BluetoothAdapter: enable()
,07-01 09:01:23.998   764  1376 W ActivityManager: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 09:01:23.998   764  1376 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-01 09:01:23.998   764  1376 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 09:01:23.998   764  1376 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 09:01:23.998   764  1376 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-01 09:01:23.998   764  1376 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-01 09:01:23.998   764  1376 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-01 09:01:23.998   764  1376 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 09:01:23.998   764  1376 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 09:01:23.998   764  1376 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 09:01:24.008   764  1376 D SettingsProvider: name = bluetooth_on
,07-01 09:01:24.008   764  1055 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-01 09:01:24.008   764  1055 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-01 09:01:24.008   764  1055 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-01 09:01:24.008  3021  3076 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-01 09:01:24.008  3021  3076 D BluetoothAdapterProperties: Setting state to 11
07-01 09:01:24.008  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-01 09:01:24.008  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:24.008  3021  3076 D BluetoothAdapterService: updateAdapterState state is 11
,07-01 09:01:24.008  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:24.008  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-01 09:01:24.008  3021  3076 D BtConfig.SecureMode: isSecureModeOn:false
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-01 09:01:24.018   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.008  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-01 09:01:24.018   764   764 I InputMethodManagerService: [BT Setting S,tate] State =11
07-01 09:01:24.008  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-01 09:01:24.018  1696  1696 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 09:01:24.018  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:24.018  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:24.018  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:24.018  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:24.018   764  1474 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 09:01:24.018   764  3348 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-01 09:01:24.018  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-01 09:01:24.018  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 09:01:24.018   764  3372 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:24.018   764  3372 D ActivityManager: caller:android.app.ApplicationThreadProxy@36d75a95, r.packageName :com.android.bluetooth
,07-01 09:01:24.018  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-01 09:01:24.018  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-01 09:01:24.018  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-01 09:01:24.028  3021  3021 D HeadsetService: Received start request. Starting profile...
07-01 09:01:24.028  3021  3021 D HeadsetStateMachine: make
,07-01 09:01:24.028  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:24.028   764  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:24.028   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@1af7df9b, r.packageName :com.android.bluetooth
,07-01 09:01:24.028  3021  3021 E HeadsetStateMachine: # of Max HF connection is 2
,07-01 09:01:24.028  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-01 09:01:24.028  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-01 09:01:24.028  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-01 09:01:24.028   764  1740 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:24.028   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@36200b11, r.packageName :com.android.bluetooth
,07-01 09:01:24.028  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:24.028  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-01 09:01:24.028  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-01 09:01:24.028  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-01 09:01:24.038   764  1474 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-01 09:01:24.038   764  1356 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:24.038   764  1356 D ActivityManager: caller:android.app.ApplicationThreadProxy@2469474d, r.packageName :com.android.bluetooth
,07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,07-01 09:01:24.038  1188  1188 D QSpanel : label top:23
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:24.038  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-01 09:01:24.038  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-01 09:01:24.038  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:24.038   764   779 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:24.038  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-01 09:01:24.038  3021  3021 I bluedroid: get_profile_interface handsfree
,07-01 09:01:24.048   764  3372 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:24.048   764  3372 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d900b49, r.packageName :com.android.bluetooth
,07-01 09:01:24.048  3021  3021 E DualScoManager: Dual Sco Manager already instantiated
07-01 09:01:24.048  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-01 09:01:24.048  3021  3021 I DualScoManager: Set HeadsetServiceHelper
07-01 09:01:24.048  3021  3021 D BluetoothAtMessage: createCMTIContentObservers
07-01 09:01:24.048  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-01 09:01:24.048  3021  3076 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-01 09:01:24.048   764  1543 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-01 09:01:24.048   764  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 09:01:24.048   764  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 09:01:24.048   764  1543 D SettingsProvider: selectionArgs: false
07-01 09:01:24.048   764  1543 D SettingsProvider: selectionArgs: 1002
07-01 09:01:24.048   764  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 09:01:24.048   764  1543 D SettingsProvider: ret = -1
07-01 09:01:24.048  3021  8151 D HeadsetStateMachine: Enter Disconnected: -2
07-01 09:01:24.048   764  1376 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:24.048   764  1376 D ActivityManager: caller:android.app.ApplicationThreadProxy@30eca16f, r.packageName :com.android.bluetooth
,07-01 09:01:24.048  3021  8151 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-01 09:01:24.048  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-01 09:01:24.048  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-01 09:01:24.048  3021  3076 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-01 09:01:24.048  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:24.048   764  1740 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:24.048   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f434668, r.packageName :com.android.bluetooth
07-01 09:01:24.048  3021  3021 D A2dpService: Received start request. Starting profile...
07-01 09:01:24.048  3021  3021 V Avrcp   : make
07-01 09:01:24.048  3021  3021 V Avrcp   : Avrcp
07-01 09:01:24.048  3021  3021 I bluedroid: get_profile_interface avrcp
,07-01 09:01:24.048  3021  3021 V Avrcp   : start
,07-01 09:01:24.058  3021  8151 D HeadsetStateMachine: map size, before remove : 0
07-01 09:01:24.058  3021  8151 D HeadsetStateMachine: map size, after remove: 0
07-01 09:01:24.058  3021  8151 D HeadsetStateMachine: mNextConnectingDevice : null
,07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:24.058  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:24.058  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-01 09:01:24.058  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-01 09:01:24.058  3021  3076 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-01 09:01:24.058  3021  3076 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-01 09:01:24.058  3021  3076 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-01 09:01:24.058  3021  3021 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-01 09:01:24.058  3021  3021 V Avrcp   : ++registerMediaPlayers++
,07-01 09:01:24.058  3021  3021 I Avrcp   : No of Audio players :: 2
07-01 09:01:24.058  3021  3021 I Avrcp   : App Package name is com.google.android.music
,07-01 09:01:24.058  3021  3021 I Avrcp   : App pkg name is Google Play Music
,07-01 09:01:24.058  3021  3021 I Avrcp   : Name::Google Play Music
07-01 09:01:24.058  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-01 09:01:24.058  3021  3021 I Avrcp   : App Package name is com.sec.android.app.music
,07-01 09:01:24.058  3021  3021 I Avrcp   : App pkg name is Music
07-01 09:01:24.058  3021  3021 I Avrcp   : Name::Music
07-01 09:01:24.058  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-01 09:01:24.058  3021  3021 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-01 09:01:24.058  3021  3021 I Avrcp   : No of Video players :: 1
07-01 09:01:24.058  3021  3021 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-01 09:01:24.058  3021  3021 I Avrcp   : Video App pkg name is Video Player
07-01 09:01:24.058  3021  3021 I Avrcp   : Name::Video Player
07-01 09:01:24.058  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-01 09:01:24.058  3021  3021 I Avrcp   : Add tempPlayer
07-01 09:01:24.058  3021  3021 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-01 09:01:24.058  3021  3021 I Avrcp   : Total no of players: 4
07-01 09:01:24.058  3021  3021 V Avrcp   : swapping the samsung player with 1st player
07-01 09:01:24.058  3021  3021 I Avrcp   :  Updating now playing list upon AVRCP Start
07-01 09:01:24.058  3021  8152 V Avrcp   : handleMessage, msg=207
,07-01 09:01:24.058  3021  8152 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
07-01 09:01:24.058  3021  3021 D A2dpStateMachine: make
,07-01 09:01:24.068  3021  3021 I bluedroid: get_profile_interface a2dp
,07-01 09:01:24.068  3021  8154 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-01 09:01:24.068  3021  3021 E bt-btif : warning : media task started media_task_refcnt 1 
07-01 09:01:24.068  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:24.068  3021  8153 D A2dpStateMachine: Enter Disconnected: -2
,07-01 09:01:24.068  3021  3021 D HidService: Received start request. Starting profile...
07-01 09:01:24.068  3021  3021 I bluedroid: get_profile_interface hidhost
07-01 09:01:24.068  3021  3021 D HidService: setHidService(): set to: null
07-01 09:01:24.068  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:24.068  3021  3021 D HeadsetStateMachine: Try to query the phonestate on bind
,07-01 09:01:24.068  1409  1421 I Telecom : BluetoothPhoneService: queryPhoneState
,07-01 09:01:24.068  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-01 09:01:24.068  3021  3021 D HealthService: Received start request. Starting profile...
,07-01 09:01:24.068  3021  8152 D BluetoothMediaBrowser: no now playing list
,07-01 09:01:24.068  3021  8152 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-01 09:01:24.068  3021  8152 D Avrcp   :  checkNowPlayingList start
,07-01 09:01:24.068  3021  3021 I bluedroid: get_profile_interface health
07-01 09:01:24.068  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:24.068  3021  3021 D HeadsetStateMachine: Proxy object connected
07-01 09:01:24.068  3021  3021 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-01 09:01:24.068  3021  3021 D HeadsetPhoneState: sendDeviceDataStateChanged
07-01 09:01:24.068  3021  3021 D HeadsetPhoneState: Signal level : previous=0 curr=1
,07-01 09:01:24.078  3021  8151 D HeadsetStateMachine: Disconnected process message: 11
07-01 09:01:24.078  3021  3021 D PanService: Received start request. Starting profile...
07-01 09:01:24.078  3021  3021 D BluetoothPanServiceJni: initializeNative(L110): pan
07-01 09:01:24.078  3021  8151 D HeadsetStateMachine: Disconnected process message: 18
07-01 09:01:24.078  3021  3021 I bluedroid: get_profile_interface pan
07-01 09:01:24.078  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:24.078  3021  3021 D BluetoothMapService: Received start request. Starting profile...
,07-01 09:01:24.088  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
,07-01 09:01:24.088  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-01 09:01:24.088  3021  8151 D HeadsetStateMachine: Disconnected process message: 10
07-01 09:01:24.088  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-01 09:01:24.088  3021  8151 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-01 09:01:24.088  3021  8151 D HeadsetStateMachine: Disconnected process message: 11
,07-01 09:01:24.088  3021  3021 D SapService: Received start request. Starting profile...
07-01 09:01:24.088  3021  3021 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-01 09:01:24.088  3021  3021 I bluedroid: get_profile_interface sap
07-01 09:01:24.088  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:24.088  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-01 09:01:24.098  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,07-01 09:01:24.098  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-01 09:01:24.098  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-01 09:01:24.098  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-01 09:01:24.098  3021  3021 E BluetoothAdapterService(492693756): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-01 09:01:24.098  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-01 09:01:24.098  3021  3076 I bluedroid: enable
,07-01 09:01:24.098  3021  3079 E bt-btif : Calling BTA_HhEnable
07-01 09:01:24.098  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:24.098  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:24.098  3021  3079 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-01 09:01:24.098  3021  3079 E BluetoothServiceJni: populateRssiValuesNative
07-01 09:01:24.098  3021  3079 I bluedroid: getModelRssiValues
07-01 09:01:24.098  3021  3079 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: Name is: Galaxy Note3
07-01 09:01:24.098  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: Scan Mode:20
07-01 09:01:24.098  3021  3082 D bt_upio : proc btwrite assertion
,07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:24.098  3021  3079 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-01 09:01:24.098   764   764 D SettingsProvider: name = bluetooth_name
07-01 09:01:24.098  3021  3079 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-01 09:01:24.098  3021  3079 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,07-01 09:01:24.108  3021  3079 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-01 09:01:24.108  3021  3079 E bt-btif : JVenable fails
07-01 09:01:24.108  3021  3079 D bte_conf: Device ID record 1 : primary
07-01 09:01:24.108  3021  3079 D bte_conf:   vendorId            = 0075
07-01 09:01:24.108  3021  3079 D bte_conf:   vendorIdSource      = 0001
07-01 09:01:24.108  3021  3079 D bte_conf:   product             = 0100
07-01 09:01:24.108  3021  3079 D bte_conf:   version             = 0200
07-01 09:01:24.108  3021  3079 D bte_conf:   clientExecutableURL = 
07-01 09:01:24.108  3021  3079 D bte_conf:   serviceDescription  = 
07-01 09:01:24.108  3021  3079 D bte_conf:   documentationURL    = 
07-01 09:01:24.108  3021  3079 D bte_conf: bte_load_did_conf no section named DID2.
07-01 09:01:24.108  3021  3076 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-01 09:01:24.108  3021  3076 D BluetoothAdapterProperties: ScanMode =  20
07-01 09:01:24.108  3021  3076 D BluetoothAdapterProperties: State =  11
07-01 09:01:24.108  3021  3079 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-01 09:01:24.108  3021  3079 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-01 09:01:24.108   764  1543 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-01 09:01:24.108  3021  3076 D BluetoothAdapterProperties: Setting state to 12
07-01 09:01:24.108  3021  3076 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:24.108  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.108  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.108  3021  3079 D BluetoothAdapterProperties: Scan Mode:21
,07-01 09:01:24.108  3021  3079 D BluetoothAdapterProperties: Discoverable Timeout:120
07-01 09:01:24.108   764  1474 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-01 09:01:24.108   764  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-01 09:01:24.108   764  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-01 09:01:24.108   764  1474 D SettingsProvider: selectionArgs: false
,07-01 09:01:24.108   764  1474 D SettingsProvider: selectionArgs: 1002
07-01 09:01:24.108   764  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-01 09:01:24.108   764  1474 D SettingsProvider: ret = -1
07-01 09:01:24.108  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.108  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.108  3021  3076 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-01 09:01:24.108  3021  3076 D BluetoothAdapterService: updateAdapterState state is 12
07-01 09:01:24.108   764  1740 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:24.108   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@207558b9, r.packageName :com.android.bluetooth
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:24.108  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:24.108  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.108  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.108  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-01 09:01:24.108  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.108  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.108  3021  3076 D BluetoothAdapterService: Autoconnection is available 
07-01 09:01:24.108  4217  4226 D Bluetoothsap: onBluetoothStateChange: up=true
07-01 09:01:24.108  3021  3076 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,07-01 09:01:24.108  3021  3076 D BluetoothAdapterService: starting service from this receiver
07-01 09:01:24.108  4217  4226 D Bluetoothsap: Binding service...
07-01 09:01:24.108   764  1244 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-01 09:01:24.108   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@126ec45f, r.packageName :com.android.bluetooth
,07-01 09:01:24.108  3021  3021 I BluetoothPbapService: Handler(): got msg=1
,07-01 09:01:24.108  4217  4226 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
07-01 09:01:24.108  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.108  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.108   764  3348 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-01 09:01:24.108  3021  3076 I BluetoothAdapterState: Entering On State from state = 11
07-01 09:01:24.108   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.118  4217  4226 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-01 09:01:24.118  4217  4229 D BluetoothPan: Binding service...
,07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.118   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-01 09:01:24.118  3021  3021 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.118   764  1055 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 09:01:24.118  3021  8159 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-01 09:01:24.118  1433  2284 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:24.118   764  1055 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:24.118   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:24.118  4217  7954 D BluetoothPbap: onBluetoothStateChange: up=true
07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.118   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.118  3021  3032 D BluetoothA2dp: onBluetoothStateChange: up=true
07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.118  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.118  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.128   764  1055 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.128  3192  3204 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.128  4217  4217 D Bluetoothsap: BluetoothSAP Proxy object connected
07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.128  4217  4217 D SapProfile: Bluetooth service connected
07-01 09:01:24.128  4217  4217 D Bluetoothsap: getConnectedDevices()
,07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  8159 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.128   764   764 D BluetoothA2dp: Proxy object connected
07-01 09:01:24.128  4217  4217 D BluetoothPan: BluetoothPAN Proxy object connected
07-01 09:01:24.128  4217  4217 D PanProfile: Bluetooth service connected
07-01 09:01:24.128   764  1055 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-01 09:01:24.128  3021  3021 D BluetoothA2dp: Proxy object connected
07-01 09:01:24.128  3021  3021 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-01 09:01:24.128  3192  3192 D BluetoothA2dp: Proxy object connected
07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.128  4217  4229 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-01 09:01:24.128  3021  8159 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-01 09:01:24.128  3021  8159 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 09:01:24.128  3021  8159 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 09:01:24.128  3021  8159 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33e97574
07-01 09:01:24.128  3021  8159 D BluetoothSocket: channel: 19
07-01 09:01:24.128  3021  8159 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-01 09:01:24.128   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
07-01 09:01:24.128  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.128  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.138  4217  4226 D BluetoothMap: onBluetoothStateChange: up=true
07-01 09:01:24.138  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.138  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.138   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
07-01 09:01:24.138  4217  4217 D BluetoothPbap: Proxy object connected
07-01 09:01:24.138  4217  4217 D PbapServerProfile: Bluetooth service connected
07-01 09:01:24.138  4217  4217 D BluetoothInputDevice: Proxy object connected
07-01 09:01:24.138  4217  4217 D HidProfile: Bluetooth service connected
07-01 09:01:24.138  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.138  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.138  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.138  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.138  4217  4217 D BluetoothMap: Proxy object connected
07-01 09:01:24.138   764  1055 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 09:01:24.138  4217  4217 D MapProfile: Bluetooth service connected
07-01 09:01:24.138  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.138  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.138  3192  3206 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:24.138   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:24.138  4217  7954 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:24.138   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-01 09:01:24.138   764  1055 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:24.138   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:24.148  1409  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,07-01 09:01:24.148  4217  4217 D HeadsetProfile: Bluetooth service connected
,07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:24.148  1409  1421 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:24.148   764  1055 D BluetoothPan: Binding service...
,07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-01 09:01:24.148   764   764 D BluetoothPan: BluetoothPAN Proxy object connected
,07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:24.148  1409  1440 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:24.148  4217  7954 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-01 09:01:24.148  4217  4217 D BluetoothA2dp: Proxy object connected
07-01 09:01:24.148  4217  4217 D A2dpProfile: Bluetooth service connected
,07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-01 09:01:24.148  7759  7768 E BluetoothHeadset: BluetoothHeadset service is binded
07-01 09:01:24.148   764  1055 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-01 09:01:24.158   764   764 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:24.158   764   764 I InputMethodManagerService: [BT Setting State] State =12
07-01 09:01:24.158   764   764 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-01 09:01:24.158  1409  1409 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34b3a706, true
,07-01 09:01:24.158  1188  1188 D BluetoothTile:  onBluetoothStateChange:
,07-01 09:01:24.158  1409  1409 D BluetoothHeadset: registerMessageListener
07-01 09:01:24.158  1696  1696 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-01 09:01:24.158  7759  7759 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.158  4217  4217 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-01 09:01:24.158  3021  3454 D HeadsetService: registerMessageListener
,07-01 09:01:24.158  3021  3454 D HeadsetService: registerMessageListener
07-01 09:01:24.158  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-01 09:01:24.158  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-01 09:01:24.158  3021  8151 D HeadsetStateMachine: Disconnected process message: 70
07-01 09:01:24.158  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-01 09:01:24.158  3021  8151 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@7e88a9d
07-01 09:01:24.158  1409  1409 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-01 09:01:24.158  3021  8151 D HeadsetStateMachine: Disconnected process message: 9
,07-01 09:01:24.158  3021  8151 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-01 09:01:24.158   764  1543 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-01 09:01:24.168   764  1441 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-01 09:01:24.168  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-01 09:01:24.168  4217  4217 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,07-01 09:01:24.168  4217  4217 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-01 09:01:24.168   307  1570 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-01 09:01:24.168   307  1570 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-01 09:01:24.168   307  1570 V voice   : voice_set_parameters: exit with code(-2)
07-01 09:01:24.168   307  1570 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-01 09:01:24.168   307  1570 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-01 09:01:24.168   307  1570 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-01 09:01:24.168   307  1570 V audio_hw_primary: adev_set_parameters: exit
,07-01 09:01:24.168  3021  8151 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-01 09:01:24.168  3021  8163 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-01 09:01:24.168  1188  1587 D BluetoothTile:  handleUpdatestate:false name:null
,07-01 09:01:24.168  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-01 09:01:24.168  3021  8163 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 09:01:24.168  3021  8163 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-01 09:01:24.168  3021  8163 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 09:01:24.168  3021  8163 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 09:01:24.168  3021  8163 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@aad0b12
,07-01 09:01:24.168  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.168  3021  3082 D bt_upio : BT_WAKE is asserted already
07-01 09:01:24.168  3021  8163 D BluetoothSocket: channel: 5
,07-01 09:01:24.168  4217  4217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-01 09:01:24.168   764  1244 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-01 09:01:24.168   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@127954b, r.packageName :com.android.settings
,07-01 09:01:24.178  1724  1724 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-01 09:01:24.178  4217  4217 D DockEventReceiver: finishStartingService: stopping service
,07-01 09:01:24.178  4217  4217 D BluetoothNotiBroadcastReceiver: onReceive
,07-01 09:01:24.188  3021  3021 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1d5de8fc
07-01 09:01:24.188  3021  3021 D BtConfig.SecureMode: isSecureModeOn:false
,07-01 09:01:24.188   764  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-01 09:01:24.188   764  1543 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c5d7041, r.packageName :com.android.bluetooth
,07-01 09:01:24.198   764  1376 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D QSpanel : label top:23
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:24.198  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:24.208  3021  8168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-01 09:01:24.208  3021  3082 D bt_vendor: op for 7
07-01 09:01:24.208  3021  3082 D bt_upio : BT_WAKE is asserted already
,07-01 09:01:24.208  3021  8168 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[84]}
07-01 09:01:24.208  3021  8168 D BluetoothSocket: bindListen(), new LocalSocket 
07-01 09:01:24.208  3021  8168 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-01 09:01:24.208  3021  8168 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22ccc65e
,07-01 09:01:24.208  3021  8168 D BluetoothSocket: channel: 12
07-01 09:01:24.208  3021  8168 I BtOppRfcommListener: Accept thread started.
,07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:24.218  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:24.218  7622  7674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:24.218  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:24.218  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:24.218  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:24.218  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 09:01:24.218  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c609b49 removed from the list
,07-01 09:01:24.218  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-01 09:01:24.218  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e88c4e added. We now have 2 listener(s)
07-01 09:01:24.218  7622  7674 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-01 09:01:24.218  7622  7674 I WifiManager: packageName : com.test.thalitest
,07-01 09:01:24.218   764  1740 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 09:01:24.218   764  1740 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 09:01:24.218   764  1740 D SecContentProvider2: mCursor = null
,07-01 09:01:24.228   764  1740 D WifiService: setWifiEnabled: false pid=7622, uid=10079
07-01 09:01:24.228   764  1740 D SettingsProvider: name = wifi_on
,07-01 09:01:24.228  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-01 09:01:24.228  7622  7674 I WifiManager: packageName : com.test.thalitest
07-01 09:01:24.228   764  3372 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-01 09:01:24.228   764  3372 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-01 09:01:24.228   764  3372 D SecContentProvider2: mCursor = null
,07-01 09:01:24.228   764  3372 D WifiService: setWifiEnabled: true pid=7622, uid=10079
07-01 09:01:24.228   764  3372 W ActivityManager: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-01 09:01:24.228   764  3372 W WifiService: Failed getting userId using ActivityManagerNative
07-01 09:01:24.228   764  3372 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7622, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-01 09:01:24.228   764  3372 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-01 09:01:24.228   764  3372 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-01 09:01:24.228   764  3372 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-01 09:01:24.228   764  3372 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-01 09:01:24.228   764  3372 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-01 09:01:24.228   764  3372 D SettingsProvider: name = wifi_on
,07-01 09:01:24.238   764  1146 E WifiHW  : ##################### set firmware type 0 #####################
,07-01 09:01:24.238   290  1043 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-01 09:01:24.238   290  1043 I WifiHW  : module is semco
07-01 09:01:24.238   290  1043 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-01 09:01:24.238   290  1043 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-01 09:01:24.238   290  1043 E WifiHW  : TEMP_FAILURE_RETRY complete
07-01 09:01:24.238   290  1043 D SoftapController: Softap fwReload - Ok
,07-01 09:01:24.238   290  1043 D CommandListener: Setting iface cfg
07-01 09:01:24.238   290  1043 D CommandListener: Trying to bring down wlan0
,07-01 09:01:24.238   290  1043 D CommandListener: Clearing all IP addresses on wlan0
,07-01 09:01:24.238   764  1146 E WifiHW  : supplicant_name : p2p_supplicant
,07-01 09:01:24.278  8172  8172 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-01 09:01:24.278  8172  8172 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-01 09:01:24.278  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:24.278  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 09:01:24.278   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8172
07-01 09:01:24.278   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-01 09:01:24.278  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:24.278  8172  8172 I wpa_supplicant: ssSupport state is = 1
,07-01 09:01:24.278  8172  8172 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-01 09:01:24.278  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-01 09:01:24.278   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8172
07-01 09:01:24.278   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-01 09:01:24.338   764  1146 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-01 09:01:24.348   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:24.348  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:24.358  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:24.358   764  1150 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-01 09:01:24.358  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 09:01:24.358  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:24.358  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-01 09:01:24.358  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:24.358  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-01 09:01:24.358  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:24.358  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:24.358  1188  1188 D HotspotTile: onReceive : 2, 0
,07-01 09:01:24.358  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:24.358   764  1740 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:24.358  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-01 09:01:24.358  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:24.358  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:24.358  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:24.378  1188  1188 D QSpanel : label top:23
,07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
,07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:24.378  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:24.548   363   363 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-01 09:01:24.798  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-01 09:01:24.818  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:24.818  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-01 09:01:24.818   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8172
07-01 09:01:24.818   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-01 09:01:24.818  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:24.818  8172  8172 I wpa_supplicant: ssSupport state is = 1
07-01 09:01:24.818  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:24.818  8172  8172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:24.818  8172  8172 E wpa_supplicant: SIM READ ERROR
07-01 09:01:24.818  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:24.818  8172  8172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:24.818  8172  8172 E wpa_supplicant: SIM READ ERROR
07-01 09:01:24.818  8172  8172 I wpa_supplicant: Blacklist: Clear (all) 
07-01 09:01:24.818  8172  8172 I wpa_supplicant: wpa_default_ap_write_once
07-01 09:01:24.818  8172  8172 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 09:01:24.818  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:24.818  8172  8172 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-01 09:01:24.818  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:24.818  8172  8172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:24.818  8172  8172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:25.288  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-01 09:01:25.288  7622  7682 I jxcore-log: 
,07-01 09:01:25.298  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-01 09:01:25.298  7622  7682 I jxcore-log: 
,07-01 09:01:25.308  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-01 09:01:25.308  7622  7682 I jxcore-log: 
,07-01 09:01:25.328   764  1244 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-01 09:01:25.328   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b619e72, r.packageName :com.google.android.music
,07-01 09:01:25.358   764  1677 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:25.358   764  1376 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:25.368   764  1441 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:25.378   764  1543 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-01 09:01:25.378   764  1543 D ActivityManager: caller:android.app.ApplicationThreadProxy@32be1e58, r.packageName :com.google.android.music
,07-01 09:01:25.398  7829  8176 I MusicLeanback: Conditions not met for autocaching.
,07-01 09:01:25.398  7829  8176 I MusicLeanback: Stop autocaching.
,07-01 09:01:25.408   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:25.408   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:25.408   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:25.408   764  1740 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:25.448  8179  8179 E Zygote  : MountEmulatedStorage()
07-01 09:01:25.448  8179  8179 E Zygote  : v2
07-01 09:01:25.448  8179  8179 I libpersona: KNOX_SDCARD checking this for 10015
07-01 09:01:25.448  8179  8179 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:25.458   764  1740 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=8179 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-01 09:01:25.468  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-01 09:01:25.468  7622  7682 I jxcore-log: 
,07-01 09:01:25.508  8179  8179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-01 09:01:25.508  8179  8179 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-01 09:01:25.508   764  1149 E Tethering: No numeric data
,07-01 09:01:25.508   764  1149 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-01 09:01:25.508   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:25.508   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:25.508  8179  8179 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-01 09:01:25.508   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:25.508   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
,07-01 09:01:25.508  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-01 09:01:25.508  1188  1188 D HotspotTile: updateTetherState():false, false
,07-01 09:01:25.508   764  1143 V NetworkStats: performPollLocked() took 3ms
,07-01 09:01:25.508   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:25.508   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:25.508   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:25.518  8172  8172 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-01 09:01:25.518   764  3348 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-01 09:01:25.528  8179  8179 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:25.538  8179  8179 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:25.548   296   296 E SMD     : DCD ON
,07-01 09:01:25.548  8172  8172 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 09:01:25.548   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8172
07-01 09:01:25.548   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-01 09:01:25.548  8172  8172 I wpa_supplicant: ssSupport state is = 1
,07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-01 09:01:25.548   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8172
07-01 09:01:25.548   363   363 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-01 09:01:25.548  8179  8179 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
07-01 09:01:25.548  8172  8172 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,07-01 09:01:25.548  8172  8172 I wpa_supplicant: ssSupport state is = 1
07-01 09:01:25.558  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:25.558  8172  8172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-01 09:01:25.558  8172  8172 E wpa_supplicant: SIM READ ERROR
07-01 09:01:25.558  8172  8172 I wpa_supplicant: wpa_default_ap_write_once
07-01 09:01:25.558  8172  8172 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-01 09:01:25.558  8172  8172 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-01 09:01:25.558  8179  8179 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-01 09:01:25.558  8179  8179 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 09:01:25.578  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-01 09:01:25.578  7622  7682 I jxcore-log: 
,07-01 09:01:25.578  8179  8179 I MultiDex: VM with version 2.1.0 has multidex support
,07-01 09:01:25.578  8179  8179 I MultiDex: install
07-01 09:01:25.578  8179  8179 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 09:01:25.598  8172  8172 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-01 09:01:25.598  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-01 09:01:25.598  8179  8179 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-01 09:01:25.598   764  3348 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 09:01:25.598   764  3348 D ActivityManager: caller:android.app.ApplicationThreadProxy@26bf11a5, r.packageName :com.google.android.gms
,07-01 09:01:25.598  1724  2757 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-01 09:01:25.608  1724  1724 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-01 09:01:25.618  2138  2138 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-01 09:01:25.618   764  3348 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-01 09:01:25.618   764  3348 D ActivityManager: caller:android.app.ApplicationThreadProxy@158f97a, r.packageName :com.google.android.gms
,07-01 09:01:25.618  8179  8179 D WearableService: callingUid 10015, callindPid: 8179
,07-01 09:01:25.628  8172  8172 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-01 09:01:25.628  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
07-01 09:01:25.628  8172  8172 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 09:01:25.628   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-01 09:01:25.628   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-01 09:01:25.628  8172  8172 I wpa_supplicant: HOTSPOT20_ENABLE called
07-01 09:01:25.628  8172  8172 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-01 09:01:25.628  8172  8172 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-01 09:01:25.628  8172  8172 E wpa_supplicant: SIM READ ERROR
07-01 09:01:25.628  8172  8172 I wpa_supplicant: Blacklist: Clear (all) 
,07-01 09:01:25.638  8172  8172 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,07-01 09:01:25.648   764   778 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b42321, r.packageName :com.google.android.gms
,07-01 09:01:25.648  8172  8172 I wpa_supplicant: Skip scan - bUseNetwork false
,07-01 09:01:25.648   764  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 09:01:25.648   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:25.658   764  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 09:01:25.658   764  1376 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 09:01:25.658   764  1376 D ActivityManager: caller:android.app.ApplicationThreadProxy@9c25907, r.packageName :com.google.android.gms
,07-01 09:01:25.658  4217  4217 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:25.658   764  1146 D WifiConfigStore: Loading config and enabling all networks 
,07-01 09:01:25.658  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-01 09:01:25.658  7622  7682 I jxcore-log: 
,07-01 09:01:25.658  2138  8201 D LocationInitializer: Restart initialization of location
,07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:25.658  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:25.658  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:25.658  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:25.658  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:25.658  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-01 09:01:25.658  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-01 09:01:25.668  1188  1587 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-01 09:01:25.668  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-01 09:01:25.668  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-01 09:01:25.668  7622  7682 I jxcore-log: 
,07-01 09:01:25.668   764  1146 E WifiConfigStore: Not a HS20
,07-01 09:01:25.668   764  1146 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-01 09:01:25.678  1188  1188 D HotspotTile: onReceive : 3, 0
07-01 09:01:25.678   764  1146 D WifiNative-HAL: callSECApiInt - ID [65]
,07-01 09:01:25.678  1903  5169 E MDM     : [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-01 09:01:25.678   764  1146 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-01 09:01:25.678  8172  8172 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-01 09:01:25.678  8172  8172 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-01 09:01:25.678  8172  8172 I wpa_supplicant: reset timer : RESET_TIMER 0
07-01 09:01:25.678  8172  8172 I wpa_supplicant: P2P: Current p2p state = IDLE
07-01 09:01:25.678  8172  8172 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-01 09:01:25.678  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-01 09:01:25.678  8172  8172 I wpa_supplicant: First Scan Start
,07-01 09:01:25.688  7799  7799 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-01 09:01:25.688  8172  8172 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-01 09:01:25.688   764  1146 D WifiNative-HAL: Setting external_sim to 1
,07-01 09:01:25.688   764  1146 D WifiStateMachine: Setting OUI to DA-A1-19
07-01 09:01:25.688   764  1146 I WifiNative-HAL: startHal
07-01 09:01:25.688   764  1146 E wifi    : getStaticLongField sWifiHalHandle 0x93ea686c
07-01 09:01:25.688   764  1146 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x202552
07-01 09:01:25.688   764  1146 I WifiNative-HAL: Could not start hal
,07-01 09:01:25.688  7466  7466 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-01 09:01:25.698   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:25.698  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:25.698  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:25.698  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
07-01 09:01:25.698  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:25.698  7829  8195 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
07-01 09:01:25.698  1188  1188 D QSpanel : label top:23
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-01 09:01:25.698  7829  7829 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
,07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-01 09:01:25.698  1188  1188 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-01 09:01:25.708   764  1146 E native  : do suspend true
,07-01 09:01:25.708   764  1145 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-01 09:01:25.708  3021  3082 D bt_vendor: op for 7
07-01 09:01:25.708   290  1043 D CommandListener: Setting iface cfg
07-01 09:01:25.708   290  1043 D CommandListener: Trying to bring up p2p0
,07-01 09:01:25.708   764  1145 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-01 09:01:25.708   764  1145 D WifiP2pService: P2pEnablingState
,07-01 09:01:25.708   764  1145 D WifiP2pService: P2pEnablingState{ what=147457 }
07-01 09:01:25.708   764  1145 D WifiP2pService: P2p socket connection successful
07-01 09:01:25.708   764  1145 D WifiP2pService: P2pEnabledState
,07-01 09:01:25.718   764   764 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-01 09:01:25.718   764  1056 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-01 09:01:25.718   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:25.718   764  1056 D WifiDisplayController: disconnect
07-01 09:01:25.718   764  1146 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-01 09:01:25.718   764  1056 D WifiDisplayController: updateConnection
07-01 09:01:25.718   764  1056 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-01 09:01:25.718   764  1056 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 09:01:25.718   764  1740 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 09:01:25.718   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@14a3a34, r.packageName :com.google.android.gms
,07-01 09:01:25.718   764  1145 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-01 09:01:25.718   764   764 D WifiScanningService: SCAN_AVAILABLE : 3
07-01 09:01:25.718   764   764 D RttService: SCAN_AVAILABLE : 3
07-01 09:01:25.718   764  1164 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:25.718   764  1164 I WifiNative-HAL: startHal
07-01 09:01:25.718   764  1164 E wifi    : getStaticLongField sWifiHalHandle 0x9b70d99c
07-01 09:01:25.718   764  1164 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x10255a
07-01 09:01:25.718   764  1164 I WifiNative-HAL: Could not start hal
07-01 09:01:25.718   764  1164 E WifiScanningService: could not start HAL
07-01 09:01:25.718   764  1165 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-01 09:01:25.718  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-01 09:01:25.718   764  3372 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-01 09:01:25.718  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-01 09:01:25.718   764  1146 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-01 09:01:25.718   764  1146 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-01 09:01:25.718   764  1146 E WifiNative-HAL: invaild command id : 215
,07-01 09:01:25.718  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-01 09:01:25.728   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:25.728   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-01 09:01:25.728   764  1056 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:25.738   764  1056 D WifiDisplayAdapter: onP2pDisconnected
07-01 09:01:25.738   764  1056 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-01 09:01:25.738  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-01 09:01:25.738  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-01 09:01:25.738   764  1056 D IpRemoteDisplayController: WfdBridgeServer is already null
07-01 09:01:25.738   764  1223 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:25.738  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:25.738   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:25.738  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:25.738  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:25.738  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 09:01:25.738  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:25.738  6503  6503 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-01 09:01:25.748  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-01 09:01:25.748  7784  7784 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-01 09:01:25.748  7784  7784 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-01 09:01:25.748  7784  7784 D WifiDirectBR: stopServiceTest : false
,07-01 09:01:25.758  8172  8172 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-01 09:01:25.788  8172  8172 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-01 09:01:25.788   764  1145 D WifiNative-HAL: p2pGetDeviceAddress
,07-01 09:01:25.788   764  1145 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-01 09:01:25.788   764  1056 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-01 09:01:25.788   764  1056 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-01 09:01:25.788   764  1056 D WifiDisplayController:  primary type: 10-0050F204-5
07-01 09:01:25.788   764  1056 D WifiDisplayController:  secondary type: null
07-01 09:01:25.788   764  1056 D WifiDisplayController:  wps: 0
07-01 09:01:25.788   764  1056 D WifiDisplayController:  grpcapab: 0
07-01 09:01:25.788   764  1056 D WifiDisplayController:  devcapab: 0
07-01 09:01:25.788   764  1056 D WifiDisplayController:  status: 3
07-01 09:01:25.788   764  1056 D WifiDisplayController:  wfdInfo: null
07-01 09:01:25.788   764  1056 D WifiDisplayController:  groupownerAddress: null
07-01 09:01:25.788   764  1056 D WifiDisplayController:  GOdeviceName: null
07-01 09:01:25.788   764  1056 D WifiDisplayController:  interfaceAddress: 
07-01 09:01:25.788   764  1056 D WifiDisplayController:  SConnectInfo : null
,07-01 09:01:25.788   764  1145 D WifiP2pService: DeviceAddress: ea:fd:2b
,07-01 09:01:25.788   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:25.788   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:25.788   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:25.788   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:25.798   764  1145 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-01 09:01:25.798   764  1145 D WifiP2pService: InactiveState
07-01 09:01:25.798   764  1145 D WifiP2pService: InactiveState{ what=143376 }
07-01 09:01:25.798   764  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-01 09:01:25.808  8172  8172 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-01 09:01:25.808   764  1145 D WifiP2pService: InactiveState{ what=143376 }
,07-01 09:01:25.808   764  1145 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 09:01:25.848  7622  7674 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectivityMonitor: stop
07-01 09:01:25.848  7622  7674 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 09:01:25.848  7622  7674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 09:01:25.848  7622  7674 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-01 09:01:25.848  7622  7674 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e88c4e removed from the list
,07-01 09:01:25.848  7622  7674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-01 09:01:25.848  7622  7674 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,07-01 09:01:25.848  7622  7674 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-01 09:01:25.848  7622  7674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-01 09:01:25.848  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 09:01:25.858  7622  7674 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-01 09:01:25.858  7622  7674 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@206b892c Bundle[{}]
,07-01 09:01:25.858  7622  7674 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-01 09:01:25.858  7622  7674 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 09:01:25.858  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-01 09:01:25.868  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-01 09:01:25.868  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-01 09:01:25.868  7622  7674 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-01 09:01:25.878  7622  8209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1306, name: My test thread name)
,07-01 09:01:25.878  7622  8209 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1306, thread name: My test thread name)
07-01 09:01:25.878  7622  8209 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1306, name: My test thread name)
,07-01 09:01:25.878  7622  8210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1308, name: My test thread name)
07-01 09:01:25.878  7622  8210 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1308, thread name: My test thread name)
07-01 09:01:25.878  7622  8210 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1308, name: My test thread name)
,07-01 09:01:25.878  7622  7674 E com.test.thalitest.ThaliTestRunner: Total number of executed tests: 36
07-01 09:01:25.878  7622  7674 E com.test.thalitest.ThaliTestRunner: Number of passed tests: 36
,07-01 09:01:25.878  7622  7674 E com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-01 09:01:25.878  7622  7674 E com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-01 09:01:25.878  7622  7674 E com.test.thalitest.ThaliTestRunner: Total duration: 7985 ms
07-01 09:01:25.878  7622  7674 I System.out: Tests succeded_00
07-01 09:01:25.878  7622  7674 W PluginManager: THREAD WARNING: exec() call to JXcore.Test blocked the main thread for 8036ms. Plugin should use CordovaInterface.getThreadPool().
,07-01 09:01:25.888  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-01 09:01:25.888  7622  7682 I jxcore-log: 
,07-01 09:01:25.908  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-01 09:01:25.908  7622  7682 I jxcore-log: 
,07-01 09:01:25.908  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-01 09:01:25.908  7622  7682 I jxcore-log: 
,07-01 09:01:25.918  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-01 09:01:25.918  7622  7682 I jxcore-log: 
,07-01 09:01:25.928  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-01 09:01:25.928  7622  7682 I jxcore-log: 
,07-01 09:01:25.948  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-01 09:01:25.948  7622  7682 I jxcore-log: 
,07-01 09:01:26.038  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-01 09:01:26.038  7622  7682 I jxcore-log: 
,07-01 09:01:26.048  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-01 09:01:26.048  7622  7682 I jxcore-log: 
,07-01 09:01:26.068  7622  7682 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-01 09:01:26.068  7622  7682 I jxcore-log: 
,07-01 09:01:26.078  7622  7682 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-01 09:01:26.078  7622  7682 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-01 09:01:26.078  7622  7682 I jxcore-log: 
,07-01 09:01:26.098  3021  3199 D bt_upio : ..proc_btwrite_timeout..
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.128  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.128  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.138  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-01 09:01:26.138  7622  7682 I jxcore-log: 
,07-01 09:01:26.438  8172  8172 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
07-01 09:01:26.438  8172  8172 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-01 09:01:26.438  8172  8172 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-01 09:01:26.438  8172  8172 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-01 09:01:26.438  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-01 09:01:26.468   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:26.468   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:26.518  8172  8172 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-01 09:01:26.518  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-01 09:01:26.528  8172  8172 I wpa_supplicant: Associated with F4.99.3E
07-01 09:01:26.528  8172  8172 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-01 09:01:26.528  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-01 09:01:26.528   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:26.528   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:26.538   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:26.538   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:26.538  8172  8172 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-01 09:01:26.548  8172  8172 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,07-01 09:01:26.548  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-01 09:01:26.548  8172  8172 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-01 09:01:26.548  8172  8172 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,07-01 09:01:26.548  8172  8172 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,07-01 09:01:26.548  8172  8172 I wpa_supplicant: Blacklist: Clear (temp) 
07-01 09:01:26.548  8172  8172 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-01 09:01:26.548   764  1146 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-01 09:01:26.558  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:26.558  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 09:01:26.568  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:26.568  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 09:01:26.568   764  1146 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-01 09:01:26.568   764  1148 D ConnectivityService: Got NetworkAgent Messenger
07-01 09:01:26.568   764  1148 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-01 09:01:26.568   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:26.568   764  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-01 09:01:26.568   764  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:26.568   764  1148 D ConnectivityService: NetworkAgent connected
,07-01 09:01:26.568  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:26.568   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:26.568  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:26.568   764  1677 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:26.568  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:26.568  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:26.568  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-01 09:01:26.568  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:26.578   764  1146 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-01 09:01:26.578   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:26.578  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:26.588   290  1043 D CommandListener: Setting iface cfg
,07-01 09:01:26.588   764  1146 E WifiStateMachine: Start Dhcp Watchdog 2
,07-01 09:01:26.588   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:26.588   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:26.598  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:26.598  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:26.598  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 09:01:26.598   764  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 09:01:26.678   764  1146 E native  : do suspend false
,07-01 09:01:26.688   764  1146 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-01 09:01:26.688   764  1146 D SecContentProvider2: mCursor = null
,07-01 09:01:26.688   764  1145 D WifiP2pService: InactiveState{ what=143375 }
,07-01 09:01:26.688   764  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 09:01:26.938  8215  8215 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-01 09:01:26.938  8215  8215 I dhcpcd  : version 5.5.6 starting
,07-01 09:01:26.938  8215  8215 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-01 09:01:27.038  8215  8215 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-01 09:01:27.038  8215  8215 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-01 09:01:27.038  8215  8215 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,07-01 09:01:27.038  8215  8215 I dhcpcd  : bssid match
07-01 09:01:27.038  8215  8215 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-01 09:01:27.068  8215  8215 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,07-01 09:01:27.078  8215  8215 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-01 09:01:27.078   764  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 09:01:27.398  3021  3077 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-01 09:01:27.498   764  1146 E native  : do suspend true
,07-01 09:01:27.518   764  1145 D WifiP2pService: InactiveState{ what=143375 }
07-01 09:01:27.518   764  1145 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-01 09:01:27.528   764  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-01 09:01:27.528  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:27.528   764  1146 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-01 09:01:27.538  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.538  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:27.538   764  1146 E WifiStateMachine: VerifyingLinkState enter
07-01 09:01:27.538   764  1146 D WifiNative-HAL: callSECApiInt - ID [210]
,07-01 09:01:27.538   764  1148 E ConnectivityService: updateNetworkInfo()
,07-01 09:01:27.538   764  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-01 09:01:27.538   764  1148 D ConnectivityService: Adding iface wlan0 to network 503
,07-01 09:01:27.548  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:27.548  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.548  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-01 09:01:27.548   764  1159 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-01 09:01:27.548   764  1159 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-01 09:01:27.548   764  1159 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-01 09:01:27.548   764  1159 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 09:01:27.548   764  1159 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 09:01:27.558   764  1146 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-01 09:01:27.558  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-01 09:01:27.558  4217  4217 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-01 09:01:27.558   764   764 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 09:01:27.558  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-01 09:01:27.558  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.558  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-01 09:01:27.558  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.558  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 09:01:27.558  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:27.558   764   764 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-01 09:01:27.558   764   764 I WifiTrafficPoller: mBoosterFLAG : 0
07-01 09:01:27.558   764   764 I WifiTrafficPoller: current booster mode : FullMode
07-01 09:01:27.568   764   764 D WifiNative-HAL: callSECApiVoid - ID [212]
07-01 09:01:27.568   764  1146 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:27.568  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.578   764  3372 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.588  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:27.588   764  1148 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,07-01 09:01:27.588   764  1148 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,07-01 09:01:27.588   764  1148 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,07-01 09:01:27.588   764  1148 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-01 09:01:27.588   764  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-01 09:01:27.588   764  1148 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,07-01 09:01:27.588   290  1043 V         : QcRouteController
,07-01 09:01:27.598  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.598  4217  4217 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-01 09:01:27.598   764  3348 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.598  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-01 09:01:27.598   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.598  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-01 09:01:27.598  4217  4217 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-01 09:01:27.598  4217  4217 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-01 09:01:27.598  4217  4343 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-01 09:01:27.608   764  1740 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.608  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:27.608   290  1043 V         : QcRouteController
,07-01 09:01:27.618  4217  4217 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-01 09:01:27.618  4217  4217 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-01 09:01:27.628   764  1356 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-01 09:01:27.628   290  1043 V         : QcRouteController
,07-01 09:01:27.638   764  1484 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.638   266   266 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,07-01 09:01:27.638  7466  7466 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:27.648   764  3372 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=764
,07-01 09:01:27.648   290  1043 V         : QcRouteController
,07-01 09:01:27.668   290  1043 V         : QcRouteController
,07-01 09:01:27.688   290  1043 V         : QcRouteController
,07-01 09:01:27.688   290  1043 V         : QcRouteController
,07-01 09:01:27.708   290  1043 V         : QcRouteController
,07-01 09:01:27.728   764  1148 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
07-01 09:01:27.728   764  1148 D ConnectivityService: LTETest block dns file not exists
,07-01 09:01:27.728   764  1148 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-01 09:01:27.728   764  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.728   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:27.728   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:27.728   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-01 09:01:27.728   764  1148 E ConnectivityService: updateNetworkInfo()
07-01 09:01:27.728   764  1148 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-01 09:01:27.728   764  1148 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.728   764  1148 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.728   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:27.728   764  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.728   764  1055 D EntConnectivity: Not allowed due to - mEnabled false
07-01 09:01:27.728   764  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.728   764  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.728   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.728   764  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.728   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-01 09:01:27.728   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-01 09:01:27.728   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-01 09:01:27.728   764  8211 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-01 09:01:27.728   764  1148 D ConnectivityService: currentScore = 0, newScore = 60
,07-01 09:01:27.728   764  1148 D ConnectivityService:    accepting network in place of null
07-01 09:01:27.728   764  1148 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 09:01:27.738  1433  1433 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-01 09:01:27.738   764  1148 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,07-01 09:01:27.738   764  1148 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-01 09:01:27.738   764  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:27.738   764  1148 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:27.738   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-01 09:01:27.738   764  1143 V NetworkStats: updateIfacesLocked()
07-01 09:01:27.738   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.738   764  1143 V NetworkStats: performPollLocked(flags=0x1)
07-01 09:01:27.738   764  1149 D Tethering: MasterInitialState.processMessage what=3
07-01 09:01:27.738   764  1148 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-01 09:01:27.738   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.738   764  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 09:01:27.738   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:27.738   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:27.738   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:27.738   764  1143 D NetworkStatsFactory: UpdateStatsForKnox
07-01 09:01:27.738   764  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.738   764  1055 D EntConnectivity: Not allowed due to - mEnabled false
07-01 09:01:27.738   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:27.738   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.738   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.738   764  1143 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.738   764  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:27.738   764  3372 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:27.738  1188  1583 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-01 09:01:27.738  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 09:01:27.738  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-01 09:01:27.738  1188  1188 D StatusBar.NetworkController: updateDataNetType()
,07-01 09:01:27.738   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.738   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.738   764  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-01 09:01:27.738   764  1144 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-01 09:01:27.738   764  1143 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.738   764  1143 V NetworkStats: performPollLocked() took 4ms
,07-01 09:01:27.738   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:27.738  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:27.738  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-01 09:01:27.748   764  1356 I AudioService: getStreamVolume 3 index 70
,07-01 09:01:27.748   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
07-01 09:01:27.748   764  1144 D NtpTrustedTime: currentTimeMillis() cache hit
,07-01 09:01:27.748   764  1223 D SecContentProvider2: uri = 14 selection = getSealedState
07-01 09:01:27.748   764  1223 D SecContentProvider2: mCursor = null
,07-01 09:01:27.758   764  1244 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 09:01:27.758   764  1244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.758  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: applyOpen
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-01 09:01:27.758  1188  1188 D StatusBar.NetworkController: applyOpen
,07-01 09:01:27.758  1188  1188 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-01 09:01:27.758  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
07-01 09:01:27.758  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
,07-01 09:01:27.758  1188  1188 I PhoneStatusBar: Icon Only
07-01 09:01:27.758  1188  1188 I StatusBar: Icon Only
,07-01 09:01:27.768  1188  1188 D PanelView: There is/are notification(s) 
,07-01 09:01:27.768  1188  1188 D PanelView: There is/are notification(s) 
,07-01 09:01:27.828   764  8211 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-01 09:01:27.838   764  1543 I art     : Explicit concurrent mark sweep GC freed 63891(3MB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.475ms total 91.851ms
,07-01 09:01:27.888   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 01 Jul 2016 07:01:27 GMT], X-Android-Received-Millis=[1467356487905], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1467356487871]}
,07-01 09:01:27.888   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-01 09:01:27.888   764  8211 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-01 09:01:27.888   764  1148 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.888   764  1148 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.888   764  1148 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-01 09:01:27.888   764  1148 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.888   764  1148 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-01 09:01:27.888   764  1148 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
07-01 09:01:27.888   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:27.888   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:27.888   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:27.888   764  1148 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-01 09:01:27.888   764  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-01 09:01:27.888  1188  1583 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-01 09:01:27.898   764  1356 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: updateDataNetType()
,07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-01 09:01:27.898  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-01 09:01:27.898   764  1223 D SecContentProvider2: uri = 14 selection = getSealedState
07-01 09:01:27.898   764  1223 D SecContentProvider2: mCursor = null
,07-01 09:01:27.898   764   779 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-01 09:01:27.898   764  1244 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-01 09:01:27.898   764  1244 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-01 09:01:27.898  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-01 09:01:27.898  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-01 09:01:27.898  8052  8071 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-01 09:01:27.898  1188  1188 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-01 09:01:27.908  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
07-01 09:01:27.908  1188  1188 D PersonaManager: isKioskContainerExistOnDevice
07-01 09:01:27.908  1188  1188 I PhoneStatusBar: Icon Only
07-01 09:01:27.908  1188  1188 I StatusBar: Icon Only
,07-01 09:01:27.908  1188  1188 D PanelView: There is/are notification(s) 
,07-01 09:01:27.908  1188  1188 D PanelView: There is/are notification(s) 
,07-01 09:01:28.198   764  3084 D SSRM:n  : SIOP:: AP = 380, PST = 318, CUR = 450
,07-01 09:01:28.238   764  1148 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:28.248   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.248   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.248   764   917 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.248   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:28.248   764   764 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-01 09:01:28.248   764   764 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
07-01 09:01:28.248   764   764 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.248   764   917 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-01 09:01:28.248   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.248   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.248   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.248   764  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-01 09:01:28.248   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:28.248   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:28.248   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:28.248   764   917 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.258   764  1150 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-01 09:01:28.258   764   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.258   764  3348 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.258   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.258   764  1740 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.258   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.268   764  1484 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.268   764  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.268   764  1344 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.268   764  1543 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.268   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.268   764  3348 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.268   764  1356 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.268  7829  7829 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-01 09:01:28.268   764  1244 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-01 09:01:28.278  7622  7622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-01 09:01:28.278  7622  7622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-01 09:01:28.278  7622  7682 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-01 09:01:28.278  7622  7682 I jxcore-log: 
,07-01 09:01:28.278  1592  1592 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-01 09:01:28.278  7273  7273 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-01 09:01:28.278  7273  7273 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 09:01:28.278  7273  7273 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-01 09:01:28.278  7273  7273 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:28.288  7829  7829 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-01 09:01:28.298  7882  7882 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:28.298  7882  7882 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-01 09:01:28.368  7899  7899 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-01 09:01:28.378  7899  7899 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-01 09:01:28.378  7899  7899 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-01 09:01:28.378   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.388   764  1474 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-01 09:01:28.388   764  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a940d32, r.packageName :com.google.android.gms
,07-01 09:01:28.388   764  1223 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.388   764  1376 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.388   764  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.388   764   778 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.388   764  3348 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.388  2138  2138 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-01 09:01:28.388   764  1244 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.398  2138  7937 I iu.UploadsManager: num queued entries: 0
,07-01 09:01:28.398  2138  7937 I iu.UploadsManager: num updated entries: 0
,07-01 09:01:28.398  2138  7937 I iu.SyncManager: NEXT; no task
,07-01 09:01:28.398   764   778 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-01 09:01:28.398   764   778 D ActivityManager: caller:android.app.ApplicationThreadProxy@13bb0a83, r.packageName :com.google.android.gms
,07-01 09:01:28.408   764  1099 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-01 09:01:28.408   764  1099 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
07-01 09:01:28.408   764  1098 D TimaService: TimaServiceHandler.handleMessage what =1
,07-01 09:01:28.408  2138  2138 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
07-01 09:01:28.408  2138  2138 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-01 09:01:28.408  2138  2138 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-01 09:01:28.418  2138  2138 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
07-01 09:01:28.418   764  1099 I TLC_TIMA_PKM_initialize: initializing...
07-01 09:01:28.418   764  1099 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
07-01 09:01:28.418   764  1099 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
07-01 09:01:28.418   764  1099 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-01 09:01:28.418   764  1099 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
07-01 09:01:28.418   764  1099 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
07-01 09:01:28.418   764  1099 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
07-01 09:01:28.418   764  1099 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
07-01 09:01:28.418   764  1099 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
07-01 09:01:28.418   764  1099 D QSEECOMAPI: : App is not loaded in QSEE
,07-01 09:01:28.418   764  1344 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.418  4197  4197 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-01 09:01:28.418  4197  4197 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1467356488434
,07-01 09:01:28.418  4197  4197 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-01 09:01:28.418   764  1356 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.418   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.428  4197  4197 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-01 09:01:28.428  4197  4197 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-01 09:01:28.428  4197  4197 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-01 09:01:28.428   764  1099 D QSEECOMAPI: : Loaded image: APP id = 2
,07-01 09:01:28.428  4197  4197 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-01 09:01:28.438   764  1099 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-01 09:01:28.438   764   779 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.438   764  1099 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-01 09:01:28.458  7983  7983 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-01 09:01:28.458   764  1740 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-01 09:01:28.458   764  1740 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ccc3439, r.packageName :com.samsung.android.app.galaxyfinder
,07-01 09:01:28.488   764  3348 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.488  7291  7291 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
07-01 09:01:28.488  3511  8290 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-01 09:01:28.488  3511  8290 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-01 09:01:28.488  3511  8290 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-01 09:01:28.488  7009  7009 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-01 09:01:28.488  7009  7009 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-01 09:01:28.488  7009  7009 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-01 09:01:28.488  7009  7009 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-01 09:01:28.488  7009  7009 I SA      : [OR] == isSIMCardReady false ==
07-01 09:01:28.488   764  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.488  7009  7009 I SA      : [SCU] == networkStateCheck == true
,07-01 09:01:28.488  7009  7009 I SA      : [DM] getCountryCodeFromCSC : PL
,07-01 09:01:28.488  7009  7009 I SA      : isChinaCountryCode : false
07-01 09:01:28.488  7009  7009 I SA      : [SCU] is ChinestModel Data Restricted   : false
07-01 09:01:28.488  7009  7009 I SA      : [OR] == networkStateCheck true ==
,07-01 09:01:28.498  7009  7009 I SA      : [OR] GetMyCountryZoneTask
,07-01 09:01:28.498  7009  7009 I SA      : [OR] onReceive END
,07-01 09:01:28.498   764  1484 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.498   764  1573 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-01 09:01:28.498   764  1573 D ActivityManager: caller:android.app.ApplicationThreadProxy@3919cbdf, r.packageName :com.android.providers.downloads
,07-01 09:01:28.508  8005  8005 I SCloudBackupReceiver: Other Intent
,07-01 09:01:28.508  8021  8021 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-01 09:01:28.508  8021  8021 I KnoxUsageLogPro: premStatus:2
,07-01 09:01:28.508  8021  8021 I KnoxUsageLogPro: isEulaShown : false
07-01 09:01:28.508  8021  8021 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-01 09:01:28.508  3511  8290 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-01 09:01:28.518  7009  8291 I SA      : [SRS] prepareGetMyCountryZone
,07-01 09:01:28.518  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-01 09:01:28.518  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-01 09:01:28.518  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-01 09:01:28.518   764  1223 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.518   764  1543 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.518  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-01 09:01:28.528  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-01 09:01:28.528  3511  8290 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-01 09:01:28.528  7009  8291 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-01 09:01:28.528  3511  8290 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-01 09:01:28.528   764  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.528  7009  8291 I SA      : [SSP] query invoked
,07-01 09:01:28.538  3511  8290 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-01 09:01:28.548   764   778 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.548   764  1223 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.548  7009  8291 I SA      : [TPMU] GetMccFromDB : null
07-01 09:01:28.548  7009  8291 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-01 09:01:28.548  7009  8291 I SA      : [TPM] isNoProxy(default) : true
,07-01 09:01:28.548   296   296 E SMD     : DCD ON
,07-01 09:01:28.558   764  1244 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.558  8107  8107 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-01 09:01:28.558  3511  8290 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-01 09:01:28.558  8107  8107 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
07-01 09:01:28.558  8107  8107 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-01 09:01:28.558  7009  8291 E File    : fail readDirectory() errno=2
,07-01 09:01:28.558   764  1740 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.558   764  1376 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.568   764  1441 D RCPManagerService: exchangeData() failure , invalid userId
,07-01 09:01:28.568   764   778 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.568  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-01 09:01:28.568  7098  7098 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-01 09:01:28.568  7098  7098 D SecurityLogAgent: StateMachine : Current State = 1
,07-01 09:01:28.568   764  1484 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.568  7098  7098 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-01 09:01:28.568   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.568   764  1543 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.578   764  1344 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,07-01 09:01:28.578   764  1344 D ActivityManager: caller:android.app.ApplicationThreadProxy@1665e318, r.packageName :com.sec.android.app.SmartClipService
,07-01 09:01:28.578   764   779 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.578  7520  7520 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-01 09:01:28.658  1724  8293 D GCM     : Connected
07-01 09:01:28.658   764  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.658   764  1344 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.658   764   778 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.668   764  3372 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.668   764   779 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.678  1724  8293 D GCM     : Message class com.google.f.a.a.p
,07-01 09:01:28.678   764  1441 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.678   764  1484 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.738   764  1474 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-01 09:01:28.738   764  1474 D ActivityManager: caller:android.app.ApplicationThreadProxy@11233171, r.packageName :com.sec.android.app.samsungapps
,07-01 09:01:28.738   764  1148 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-01 09:01:28.748  7520  7520 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-01 09:01:28.748  7520  7520 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-01 09:01:28.748  7520  7520 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-01 09:01:28.748  7520  7520 D InitializeManagerStateMachine: exit::IDLE
07-01 09:01:28.748  7520  7520 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-01 09:01:28.758   764  1573 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.758   764  1223 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-01 09:01:28.758  7520  7520 D InitializeManagerStateMachine: entry::SUCCESS
,07-01 09:01:28.758  7520  7520 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-01 09:01:28.768  7520  7520 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-01 09:01:28.768  7520  7520 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-01 09:01:28.768   764  1244 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:28.768  7520  7520 D InitializeManagerStateMachine: exit::SUCCESS
07-01 09:01:28.768  7520  7520 D InitializeManagerStateMachine: entry::IDLE
,07-01 09:01:29.018  7009  8291 I SA      : [RC New] Execute method=[GET] start
,07-01 09:01:29.028   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:29.048  7009  8291 I SA      : [RC New] Security=[true]
,07-01 09:01:29.058  7009  8291 I System.out: Thread-1156(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-01 09:01:29.058  7009  8291 I System.out: Thread-1156(ApacheHTTPLog):isShipBuild true
,07-01 09:01:29.058  7009  8291 I System.out: Thread-1156(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-01 09:01:29.378   764  1058 I PowerManagerService: [PWL] Off : 275s ago
07-01 09:01:29.378   764  1058 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-01 09:01:29.378   764  1058 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-01 09:01:29.378   764  1058 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=764, ws=null) (elapsedTime=963)
,07-01 09:01:29.658  7009  8291 I SA      : [RC New] [v2liruge] api execute + 609
,07-01 09:01:29.658  7009  8291 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
07-01 09:01:29.658  7009  8291 I System.out: AsyncTask #1 calls detatch()
,07-01 09:01:29.668  7009  8291 I SA      : [TPMU] getNetworkMcc : 260
,07-01 09:01:29.678  7009  8291 I SA      : [SCU] saveMccToPreferece Start
,07-01 09:01:29.678  7009  8291 I SA      : [SCU] RegionMCC : 260
07-01 09:01:29.678  7009  8291 I SA      : [SSP] query invoked
,07-01 09:01:29.678  7009  8291 I SA      : [TPMU] GetMccFromDB : null
,07-01 09:01:29.678  7009  8291 I SA      : [SCU] getMccFromPreferece mcc = 260
07-01 09:01:29.688  7009  8291 I SA      : [SCU] saveMccToPreferece End
07-01 09:01:29.688  7009  8291 I SA      : [RC New] executeRequest [v2liruge] end. 663
07-01 09:01:29.688  7009  8291 I SA      : [RC New] Execute end
,07-01 09:01:29.688  7009  7009 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-01 09:01:29.688  7009  7009 I SA      : [OR] GetMyCountryZoneTask Success
,07-01 09:01:30.168   764  1148 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
,07-01 09:01:30.168   764  1148 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-01 09:01:30.168   764  1148 D ConnectivityService: identical MTU - not setting
,07-01 09:01:30.168   764  1148 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-01 09:01:30.168   764  1148 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
,07-01 09:01:30.168   290  1043 V         : QcRouteController
,07-01 09:01:30.168   764   764 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,07-01 09:01:30.168   764   764 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:30.178   764  1150 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,07-01 09:01:30.178   764  1150 D SmartBondingService: getSBEnabled() enabled =false
07-01 09:01:30.178   764  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-01 09:01:30.178   764  1150 D SmartBondingService: getSBEnabled() enabled =false
,07-01 09:01:30.198   290  1043 V         : QcRouteController
,07-01 09:01:30.198   764  1148 W NetworkManagementService: route cmd failed: 
07-01 09:01:30.198   764  1148 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '98 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 98 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-01 09:01:30.198   764  1148 W NetworkManagementService: '
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-01 09:01:30.198   764  1148 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 09:01:30.198   764  1148 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-01 09:01:30.198   764  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-01 09:01:30.198   764  1148 D ConnectivityService: calling update connectivity
,07-01 09:01:30.198   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:30.198   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:30.198   764  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:30.208  1188  1583 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-01 09:01:30.208   764  1148 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,07-01 09:01:30.208   764  1148 D ConnectivityService: calling update connectivity
07-01 09:01:30.208   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-01 09:01:30.208   764  1148 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:30.208   764  1148 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-01 09:01:30.208  1188  1583 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-01 09:01:30.438   764  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-01 09:01:30.438   764  1099 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-01 09:01:30.438   764  1099 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:01:30.438   764  1099 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-01 09:01:30.758   764  1376 I ActivityManager: Killing 6073:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-01 09:01:30.828   764  1474 D CountryDetector: No listener is left
,07-01 09:01:30.948   764  1146 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,07-01 09:01:31.138   266  1333 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,07-01 09:01:31.138   266   371 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,07-01 09:01:31.138   764   778 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=764 (0x0)
,07-01 09:01:31.138   764   778 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=764, ws=WorkSource{10067}) (elapsedTime=3493)
,07-01 09:01:31.278   764  1336 E Watchdog: !@Sync 10
,07-01 09:01:31.418  8215  8215 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-01 09:01:31.488   764  1244 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-01 09:01:31.488   764  1244 D ActivityManager: caller:android.app.ApplicationThreadProxy@328b57d7, r.packageName :com.sec.spp.push
,07-01 09:01:31.508   764  1356 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:31.548   296   296 E SMD     : DCD ON
,07-01 09:01:32.278   764  1474 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:32.758   764  1114 V AlarmManager: waitForAlarm result :4
,07-01 09:01:32.758   764  1114 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,07-01 09:01:32.778  1592  8320 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,07-01 09:01:32.798   764  1244 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:32.798   764  1244 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-01 09:01:32.798   764  1244 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 09:01:32.808   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:01:32.808   764   764 I MotionRecognitionService: Plugged
,07-01 09:01:32.808   764   764 I MotionRecognitionService: setPowerConnected  = true
,07-01 09:01:32.808   764  1244 D BatteryService: stay LED for fully charged
,07-01 09:01:32.808  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:01:32.808  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 09:01:32.808  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:32.818  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 09:01:32.818  3021  8151 D HeadsetStateMachine: Disconnected process message: 10
07-01 09:01:32.818  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:01:32.828  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:32.828  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:33.288  7273  7273 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,07-01 09:01:33.288   764  1344 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-01 09:01:33.298  7273  8330 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,07-01 09:01:33.318  7273  8330 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,07-01 09:01:33.318  7273  8330 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-01 09:01:33.318  7273  8330 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
07-01 09:01:33.318  7273  8330 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,07-01 09:01:33.318  7273  8330 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-01 09:01:33.318  7273  8330 I PCWCLIENTTRACE_PushUtil: sales region : global
07-01 09:01:33.318  7273  8330 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,07-01 09:01:33.318  7273  8330 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,07-01 09:01:34.548   296   296 E SMD     : DCD ON
,07-01 09:01:35.418  8215  8215 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,07-01 09:01:37.548   296   296 E SMD     : DCD ON
,07-01 09:01:37.938   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-01 09:01:37.938   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-01 09:01:38.248   764  3084 D SSRM:n  : SIOP:: AP = 340, PST = 321, CUR = 450
,07-01 09:01:38.748   764  1344 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-01 09:01:38.748   764  1344 D ActivityManager: caller:android.app.ApplicationThreadProxy@3439a73, r.packageName :com.sec.android.app.samsungapps
,07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: exit::IDLE
07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,07-01 09:01:38.778  7520  7520 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,07-01 09:01:38.778  7520  7520 D PreloadUpdateManagerStateMachine: entry::IDLE
,07-01 09:01:39.428  8215  8215 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-01 09:01:39.428  8215  8215 I dhcpcd  : wlan0: no IPv6 Routers available
,07-01 09:01:40.548   296   296 E SMD     : DCD ON
,07-01 09:01:43.548   296   296 E SMD     : DCD ON
,07-01 09:01:46.558   296   296 E SMD     : DCD ON
,07-01 09:01:47.918   764  1114 V AlarmManager: waitForAlarm result :4
,07-01 09:01:47.928   764   929 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-01 09:01:47.928   764   929 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:47.928   764   929 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:47.928   764   929 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-01 09:01:47.928   764   929 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-01 09:01:47.958   764  1356 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:47.988   764   929 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8334 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-01 09:01:47.998  8334  8334 E Zygote  : MountEmulatedStorage()
,07-01 09:01:47.998  8334  8334 E Zygote  : v2
07-01 09:01:47.998  8334  8334 I libpersona: KNOX_SDCARD checking this for 10096
07-01 09:01:47.998  8334  8334 I libpersona: KNOX_SDCARD not a persona
,07-01 09:01:48.008  8334  8334 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-01 09:01:48.008  8334  8334 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-01 09:01:48.008  8334  8334 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-01 09:01:48.038  8334  8334 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-01 09:01:48.038  8334  8334 D ActivityThread: Added TimaKeyStore provider
,07-01 09:01:48.058  8334  8334 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-01 09:01:48.088   764  3348 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-01 09:01:48.088   764  3348 D ActivityManager: caller:android.app.ApplicationThreadProxy@563cf2e, r.packageName :com.blurb.checkout
,07-01 09:01:48.128   764  1474 I ActivityManager: Killing 7345:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-01 09:01:48.298   764  3084 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 450
,07-01 09:01:49.028   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:01:49.558   296   296 E SMD     : DCD ON
,07-01 09:01:52.558   296   296 E SMD     : DCD ON
,07-01 09:01:52.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:53.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:54.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:55.558   296   296 E SMD     : DCD ON
,07-01 09:01:55.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:56.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:01:57.948   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-01 09:01:58.028   764  1244 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:01:58.028   764  1244 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 09:01:58.028   764  1244 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 09:01:58.028   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:01:58.038  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:01:58.038  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:01:58.038   764   764 I MotionRecognitionService: Plugged
07-01 09:01:58.038   764   764 I MotionRecognitionService: setPowerConnected  = true
,07-01 09:01:58.038   764  1244 D BatteryService: stay LED for fully charged
,07-01 09:01:58.048  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 09:01:58.048  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 09:01:58.058  3021  8151 D HeadsetStateMachine: Disconnected process message: 10
,07-01 09:01:58.058  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:58.058  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:58.068  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:01:58.328   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 322, CUR = 450
,07-01 09:01:58.568   296   296 E SMD     : DCD ON
,07-01 09:01:59.988   764  1114 V AlarmManager: waitForAlarm result :8
,07-01 09:02:01.288   764  1336 E Watchdog: !@Sync 11
,07-01 09:02:01.558   296   296 E SMD     : DCD ON
,07-01 09:02:02.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:03.948   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:04.568   296   296 E SMD     : DCD ON
,07-01 09:02:04.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:05.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:06.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:07.558   296   296 E SMD     : DCD ON
,07-01 09:02:07.958   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-01 09:02:08.088   764  1740 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:08.378   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 323, CUR = 450
,07-01 09:02:09.028   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:10.558   296   296 E SMD     : DCD ON
,07-01 09:02:13.558   296   296 E SMD     : DCD ON
,07-01 09:02:16.558   296   296 E SMD     : DCD ON
,07-01 09:02:17.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:18.138   764  1244 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:18.148   764  1244 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-01 09:02:18.148   764  1244 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-01 09:02:18.148   764   764 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-01 09:02:18.148   764   764 I MotionRecognitionService: Plugged
,07-01 09:02:18.148   764   764 I MotionRecognitionService: setPowerConnected  = true
,07-01 09:02:18.148   764  1244 D BatteryService: stay LED for fully charged
,07-01 09:02:18.158  3021  3021 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-01 09:02:18.158  3021  8151 D HeadsetStateMachine: Disconnected process message: 10
,07-01 09:02:18.158  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-01 09:02:18.158  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-01 09:02:18.158  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:02:18.158  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-01 09:02:18.158  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-01 09:02:18.158  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-01 09:02:18.418   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 450
,07-01 09:02:18.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:19.558   296   296 E SMD     : DCD ON
,07-01 09:02:19.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:20.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:21.958   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:22.558   296   296 E SMD     : DCD ON
,07-01 09:02:22.958   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-01 09:02:24.378   764  1058 I PowerManagerService: [PWL] Off : 330s ago
,07-01 09:02:25.568   296   296 E SMD     : DCD ON
,07-01 09:02:28.198   764  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:28.458   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450
,07-01 09:02:28.568   296   296 E SMD     : DCD ON
,07-01 09:02:29.038   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:31.288   764  1336 E Watchdog: !@Sync 12
,07-01 09:02:31.578   296   296 E SMD     : DCD ON
,07-01 09:02:34.568   296   296 E SMD     : DCD ON
,07-01 09:02:37.568   296   296 E SMD     : DCD ON
,07-01 09:02:37.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:38.258   764  1223 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:38.508   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 326, CUR = 450
,07-01 09:02:38.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:39.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:40.568   296   296 E SMD     : DCD ON
,07-01 09:02:40.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:41.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:02:42.968   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-01 09:02:43.568   296   296 E SMD     : DCD ON
,07-01 09:02:46.578   296   296 E SMD     : DCD ON
,07-01 09:02:48.308   764  1376 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:48.558   764  3084 D SSRM:n  : SIOP:: AP = 310, PST = 325, CUR = 450
,07-01 09:02:49.038   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:02:49.568   296   296 E SMD     : DCD ON
,07-01 09:02:52.568   296   296 E SMD     : DCD ON
,07-01 09:02:55.578   296   296 E SMD     : DCD ON
,07-01 09:02:58.368   764  1484 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:02:58.568   296   296 E SMD     : DCD ON
,07-01 09:02:58.618   764  3084 D SSRM:n  : SIOP:: AP = 300, PST = 320, CUR = 450
,07-01 09:03:01.288   764  1336 E Watchdog: !@Sync 13
,07-01 09:03:01.578   296   296 E SMD     : DCD ON
,07-01 09:03:02.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:03:03.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:03:04.578   296   296 E SMD     : DCD ON
,07-01 09:03:04.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:03:05.968   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:03:06.978   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-01 09:03:07.578   296   296 E SMD     : DCD ON
,07-01 09:03:07.978   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-01 09:03:08.418   764  3348 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:03:08.668   764  3084 D SSRM:n  : SIOP:: AP = 300, PST = 312, CUR = 450
,07-01 09:03:09.048   764  3116 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-01 09:03:10.578   296   296 E SMD     : DCD ON
,07-01 09:03:13.578   296   296 E SMD     : DCD ON
,07-01 09:03:16.578   296   296 E SMD     : DCD ON
,07-01 09:03:18.478   764   779 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-01 09:03:18.718   764  3084 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 450
,07-01 09:03:19.578   296   296 E SMD     : DCD ON
,07-01 09:03:22.578   296   296 E SMD     : DCD ON
,07-01 09:03:24.398   764  1058 I PowerManagerService: [PWL] Off : 390s ago
,07-01 09:03:25.578   296   296 E SMD     : DCD ON

```
