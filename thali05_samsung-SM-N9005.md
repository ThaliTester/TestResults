#### Test 757892686f45c73_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
07-26 15:20:56.923   767  3050 D SSRM:n  : SIOP:: AP = 350, PST = 362, CUR = 450
,--------- beginning of main
07-26 15:20:57.213  7207  7207 D AndroidRuntime: 
07-26 15:20:57.213  7207  7207 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-26 15:20:57.223  7207  7207 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:57.223  7207  7207 D AndroidRuntime: readGMSProperty: start
07-26 15:20:57.223  7207  7207 D AndroidRuntime: readGMSProperty: already setted!!
07-26 15:20:57.223  7207  7207 D AndroidRuntime: readGMSProperty: end
07-26 15:20:57.223  7207  7207 D AndroidRuntime: addProductProperty: start
07-26 15:20:57.353  7207  7207 E AffinityControl: AffinityControl: registerfunction enter
07-26 15:20:57.373  7207  7207 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:57.383   767  1260 E PersonaManagerService: inState():  stateMachine is null !!
07-26 15:20:57.383   767  1260 I PersonaManagerService: PersonaId don't exist
07-26 15:20:57.383   767  1260 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-26 15:20:57.383   767  1260 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-26 15:20:57.383   767  1260 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:57.383   767  1260 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-26 15:20:57.393   767  1260 W ActivityManager: mDVFSHelper.acquire()
07-26 15:20:57.393   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:57.393   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:57.393   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:57.393   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:20:57.433  7221  7221 E Zygote  : MountEmulatedStorage()
07-26 15:20:57.433  7221  7221 E Zygote  : v2
07-26 15:20:57.433  7221  7221 I libpersona: KNOX_SDCARD checking this for 10079
07-26 15:20:57.433  7221  7221 I libpersona: KNOX_SDCARD not a persona
07-26 15:20:57.433   767  1260 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7221 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-26 15:20:57.443  7207  7207 D AndroidRuntime: Shutting down VM
07-26 15:20:57.443  7221  7221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:20:57.443  7221  7221 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:20:57.453  7221  7221 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-26 15:20:57.473  7221  7221 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:20:57.473  7221  7221 D ActivityThread: Added TimaKeyStore provider
07-26 15:20:57.493   767  3050 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:20:57.493  7221  7221 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-26 15:20:57.503   767  3050 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:20:57.503  1444  1444 D SurfaceWidgetView: destroyHardwareResources():481099062
07-26 15:20:57.563   265  1570 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-26 15:20:57.563   265   347 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-26 15:20:57.563  1444  1444 V ActivityThread: updateVisibility : ActivityRecord{2e5e9f71 token=android.os.BinderProxy@3473f877 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-26 15:20:57.563  1759  1787 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-26 15:20:57.563  1444  1444 D Launcher: onTrimMemory. Level: 20
07-26 15:20:57.593  7221  7221 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-26 15:20:57.593  7221  7221 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-26 15:20:57.603  7221  7221 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3616-3618)
07-26 15:20:57.603  7221  7221 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:57.623  7221  7221 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {39401e99}
07-26 15:20:57.633  7221  7221 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:57.633  7221  7221 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:20:57.663  7221  7221 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:20:57.663  7221  7221 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:57.663  7221  7221 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:20:57.683  7221  7221 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-26 15:20:57.683  7221  7221 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-26 15:20:57.683  7221  7221 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-26 15:20:57.683  7221  7221 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-26 15:20:57.683  7221  7221 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-26 15:20:57.683  7221  7221 I Adreno-EGL: Build Date: 11/19/14 Wed
07-26 15:20:57.683  7221  7221 I Adreno-EGL: Local Branch: mybranch5813579
07-26 15:20:57.683  7221  7221 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-26 15:20:57.683  7221  7221 I Adreno-EGL: Local Patches: NONE
07-26 15:20:57.683  7221  7221 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-26 15:20:57.783  7221  7254 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-26 15:20:57.813  7221  7221 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:57.823  7221  7221 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:57.833  7221  7221 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-26 15:20:57.843  7221  7221 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:57.843  7221  7221 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:20:57.893  7221  7221 D Activity: performCreate Call secproduct feature valuefalse
,07-26 15:20:57.893  7221  7221 D Activity: performCreate Call debug elastic valuetrue
,07-26 15:20:57.903  7221  7270 D OpenGLRenderer: Render dirty regions requested: true
,07-26 15:20:57.913   767  1569 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-26 15:20:57.913   767  1569 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-26 15:20:57.913   767  1569 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-26 15:20:57.913   767   767 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-26 15:20:57.913   767   767 D PersonaManagerService: getPersonasForUser(): returning null!
,07-26 15:20:57.933   265   265 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,07-26 15:20:57.943  7221  7270 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:57.943  7221  7270 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cfb218 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-26 15:20:57.953  7221  7270 D OpenGLRenderer: Enabling debug mode 0
,07-26 15:20:57.963  7221  7221 V ActivityThread: updateVisibility : ActivityRecord{1250144b token=android.os.BinderProxy@318673c5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-26 15:20:57.993  7221  7221 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@318673c5 time:154002
,07-26 15:20:58.013   767  1058 W ActivityManager: mDVFSHelper.release()
,07-26 15:20:58.013   767  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14ae7840 u0 com.test.thalitest/.MainActivity t38} time:154022
,07-26 15:20:58.053  7221  7221 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7221
,07-26 15:20:58.133  7221  7221 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:58.203   304   304 E SMD     : DCD ON
,07-26 15:20:58.223  7221  7274 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258382720
,07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:20:58.233  7221  7274 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb2a63b added. We now have 1 listener(s)
,07-26 15:20:58.233  7221  7274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:2A:28:2D
,07-26 15:20:58.243  7221  7274 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:20:58.243  7221  7274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:20:58.243  7221  7274 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:2A:28:2D
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-26 15:20:58.243  7221  7274 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e360396 added. We now have 1 listener(s)
07-26 15:20:58.243  7221  7274 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:20:58.253  7221  7274 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:2A:28:2D
07-26 15:20:58.263   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:20:58.263  7221  7274 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:58.263  7221  7274 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:58.263  7221  7274 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:58.263  7221  7274 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:58.263   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:20:58.263  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.273   767  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:20:58.273  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:58.273  7221  7274 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:20:58.293  7221  7221 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:58.953  7221  7279 W jxcore-log: Initializing JXcore engine
,07-26 15:20:58.953  7221  7279 W jxcore-log: JXcore engine is ready
,07-26 15:20:59.003  1901  1901 E auditd  : In denial and Property audit_ondenial is set to 1 
07-26 15:20:59.003  1901  1901 E audit   : type=1400 msg=audit(1469539259.003:203): avc:  denied  { ioctl } for  pid=7279 comm="Thread-1218" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-26 15:20:59.003  1901  1901 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-26 15:20:59.003  1901  1901 E audit   : 
07-26 15:20:59.003  1901  1901 E audit   : type=1300 msg=audit(1469539259.003:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=987e08d8 items=0 ppid=359 ppcomm=main pid=7279 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1218" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-26 15:20:59.003  1901  1901 E audit   : type=1320 msg=audit(1469539259.003:203): 
07-26 15:20:59.003   767  1040 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-26 15:20:59.003   767  1040 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-26 15:20:59.003   767  1040 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-26 15:20:59.013  7112  7112 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-26 15:20:59.013  7112  7112 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-26 15:20:59.013  7221  7279 W jxcore-log: Starting JXcore engine
,07-26 15:20:59.103  7221  7279 W jxcore-log: Platform android
07-26 15:20:59.103  7221  7279 W jxcore-log: 
,07-26 15:20:59.103  7221  7279 W jxcore-log: Process ARCH arm
07-26 15:20:59.103  7221  7279 W jxcore-log: 
,07-26 15:20:59.283  7221  7279 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:59.283  7221  7279 I jxcore-log: 
,07-26 15:20:59.283  7221  7279 W jxcore-log: JXcore engine is started
,07-26 15:20:59.293  7221  7274 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:59.293  7221  7221 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:21:00.003   767  1115 V AlarmManager: waitForAlarm result :8
,07-26 15:21:00.043   767  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 15:21:00.043   767  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-26 15:21:00.043   767  3837 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-26 15:21:00.043   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 15:21:00.053   767   767 I MotionRecognitionService: Plugged
,07-26 15:21:00.053   767   767 I MotionRecognitionService: setPowerConnected  = true
07-26 15:21:00.053  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 15:21:00.053   767  3837 D BatteryService: stay LED for fully charged
,07-26 15:21:00.053  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-26 15:21:00.053  2987  3214 D HeadsetStateMachine: Disconnected process message: 10
,07-26 15:21:00.053  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 15:21:00.053  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-26 15:21:00.063  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:00.063  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:00.063  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:00.983   767  3083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-26 15:21:01.203   304   304 E SMD     : DCD ON
,07-26 15:21:04.203   304   304 E SMD     : DCD ON
,07-26 15:21:04.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:05.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:06.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:06.973   767  3050 D SSRM:n  : SIOP:: AP = 380, PST = 360, CUR = 450
,07-26 15:21:07.203   304   304 E SMD     : DCD ON
,07-26 15:21:07.453   767  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-26 15:21:07.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:08.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:09.333  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-26 15:21:09.333  7221  7279 I jxcore-log: 
,07-26 15:21:09.333  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-26 15:21:09.333  7221  7279 I jxcore-log: 
,07-26 15:21:09.333   767  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.343  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:09.343  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:21:09.343  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-26 15:21:09.343  7221  7279 I jxcore-log: 
,07-26 15:21:09.343  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-26 15:21:09.343  7221  7279 I jxcore-log: 
,07-26 15:21:09.493   372   372 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,07-26 15:21:09.673  7221  7279 D ExecuteNativeTests: Running unit tests,
,07-26 15:21:09.773  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
07-26 15:21:09.773  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd added. We now have 2 listener(s),
07-26 15:21:09.773  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D",
07-26 15:21:09.773  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
07-26 15:21:09.773  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,07-26 15:21:09.783   767  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.773  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:09.773  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 added. We now have 2 listener(s)
,07-26 15:21:09.783   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.773  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,07-26 15:21:09.783   767  1523 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
07-26 15:21:09.783  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:09.783  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.783  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:09.783  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:21:09.783  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:09.783  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.783  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.783  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:09.793  7221  7279 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-26 15:21:09.793  7221  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:09.793  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.793  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:21:09.793  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:21:09.793  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd removed from the list
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:09.793  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 removed from the list
07-26 15:21:09.793  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.793  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.803   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.793  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.793  7221  7279 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-26 15:21:09.793  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.793  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.793  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:21:09.793  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.793  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.813   767  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.793  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.793  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.793  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.793  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.793  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.793  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.813   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.803  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:21:09.803  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:21:09.803  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.803  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.803  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.803  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.803  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.803  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.803  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.803  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:09.803  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.803  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.803  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.803  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.803  7221  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:21:09.803  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.813  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:09.813  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.813  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:09.813  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.813  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.813  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:09.813  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:09.813  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:09.813  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:21:09.813  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:09.813  7221  7279 E BluetoothAdapter: bluetooth le advertising not supported
07-26 15:21:09.823  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:09.823  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:21:09.823  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-26 15:21:09.823  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-26 15:21:09.823  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:21:09.823  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:09.823  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-26 15:21:09.823  7221  7279 I io.jxcore.node.ConnectionHelper: start: OK
,07-26 15:21:09.833  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
07-26 15:21:09.833  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.833  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.833  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.833  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:09.833  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.833  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.833  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.833  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.833  7221  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.833   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
,07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.833  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:09.833  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.833  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:09.833   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.833  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:09.833   767  1260 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.833  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-26 15:21:09.833  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.833  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
07-26 15:21:09.843  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:09.843  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
07-26 15:21:09.843  7221  7279 I io.jxcore.node.ConnectionHelper: start: OK
,07-26 15:21:09.843  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections,
07-26 15:21:09.843  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.843  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.843  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.843  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:09.843  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.843  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.843  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.843  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.843  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.843  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.843  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.843  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.843  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.843  7221  7279 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:21:09.843  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:09.843   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.853  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:09.853  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:21:09.853   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.853  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:09.853  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:21:09.853  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:09.853  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.853  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:21:09.853  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.853   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:09.853  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:09.853  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:21:09.853  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:09.853  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-26 15:21:09.863  7221  7279 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:21:09.863  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:09.863  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.863  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:09.863  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.863  7221  7279 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-26 15:21:09.863  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.863  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.863  7221  7279 D BluetoothLeScanner: could not find callback wrapper
,07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.863  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.863  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:21:09.863  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.863  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.863  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.863  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.863  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.873  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:09.873  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.873  7221  7279 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-26 15:21:09.873  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.873  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:21:09.873  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.873  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:21:09.873  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.873  7221  7279 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-26 15:21:09.873  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.873  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.873  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.873  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.873  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.873  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.873  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:21:09.873  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.873  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-26 15:21:09.883  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:21:09.883  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:21:09.883  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:21:09.883  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.883  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.883  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.883  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.883  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.883  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.883  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.883  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.883  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.883  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.883  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.883  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.883  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.883  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.883  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.883  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
,07-26 15:21:09.883  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:09.883  7221  7279 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,07-26 15:21:09.883  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:09.883  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:09.883  7221  7279 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:21:09.893  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 15:21:09.893  7221  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:09.893  7221  7279 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:09.893  7221  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:09.893  7221  7279 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:09.893  7221  7279 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:21:09.893  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-26 15:21:09.893  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,07-26 15:21:09.893  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-26 15:21:09.893  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 15:21:09.893  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-26 15:21:09.893  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:21:09.893  7221  7279 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-26 15:21:09.893  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.893  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.893  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.903  7221  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1282)
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.903  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.903  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.903  7221  7279 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-26 15:21:09.903  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.903  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.903  7221  7295 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-26 15:21:09.903  7221  7295 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:09.903  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.903  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.903  2987  3381 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.903  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.903  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.903  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.903  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.903  7221  7279 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-26 15:21:09.913  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.913  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.913  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.913  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.913  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.913  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.913  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.913  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.913  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.913  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.913  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.913  2987  3048 D bt_vendor: op for 7
07-26 15:21:09.913  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.913  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.913  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.913  2987  3048 D bt_upio : proc btwrite assertion
07-26 15:21:09.913  7221  7295 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
07-26 15:21:09.913  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.913  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.913  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.913  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.913  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.913  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.913  7221  7296 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1282
07-26 15:21:09.913  7221  7296 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1282)
07-26 15:21:09.913  7221  7296 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c966c0b, channel: -1, state: INIT
07-26 15:21:09.913  7221  7296 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c966c0b, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c798ae8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f830501mSocket: android.net.LocalSocket@6159fa6 impl:android.net.LocalSocketImpl@e3dbde7 fd:FileDescriptor[109]
07-26 15:21:09.913  7221  7296 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@6159fa6 impl:android.net.LocalSocketImpl@e3dbde7 fd:FileDescriptor[109]
07-26 15:21:09.913  7221  7295 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c966c0b, channel: -1, state: CLOSED
07-26 15:21:09.913  7221  7295 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1282)
07-26 15:21:09.913  2987  3153 E bt-btif : SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:4, channel:-1
07-26 15:21:09.913  7221  7296 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1282)
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-26 15:21:09.923  7221  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:09.923  7221  7279 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:21:09.923  7221  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:09.923  7221  7279 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:21:09.923  7221  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:09.923  7221  7279 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-26 15:21:09.923  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.923  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.923  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.923  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.923  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.923  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.923  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.923  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.923  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.923  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.923  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.923  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.933  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.933  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 15:21:09.933  7221  7221 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 15:21:09.933  7221  7221 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 15:21:09.933  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:21:09.933  7221  7297 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 15:21:09.933  7221  7297 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:21:09.933  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:21:09.933  7221  7221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:21:09.933  7221  7221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:21:09.933  7221  7221 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 15:21:09.933  7221  7221 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:21:09.933  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.933  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.933  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.933  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.933  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.933  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.933  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.933  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.933  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.943  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.943  7221  7279 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-26 15:21:09.943  7221  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:21:09.943  7221  7279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:21:09.943  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.943  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.943  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.943  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.943  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.943  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.943  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.943  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.943  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.943  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.943  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.943  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.943  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.943  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.943  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.943  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.943  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.943  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.943  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.943  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.953  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.953  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.953  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.953  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.953  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.953  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.953  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:09.953  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:09.953  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:09.953  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.953  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.953  7221  7279 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d49f9cd not in the list
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.953  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:09.953  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.953  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.953  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:09.953  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:09.953  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:09.953  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@242a0282 not in the list
07-26 15:21:09.953  7221  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:09.953  7221  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:21:09.953  7221  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-26 15:21:09.953  7221  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:21:09.953  7221  7279 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:21:09.953  7221  7279 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 15:21:09.953  7221  7279 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-26 15:21:09.963  7221  7279 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-26 15:21:09.963  7221  7279 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 15:21:09.963  7221  7279 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-26 15:21:09.963  7221  7279 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-26 15:21:09.963  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.963  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27d06d94 added. We now have 2 listener(s)
07-26 15:21:09.963  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.963  7221  7279 D BluetoothAdapter: enable()
07-26 15:21:09.963  7221  7279 D BluetoothAdapter: enable(): BT is already enabled..!
07-26 15:21:09.963  7221  7279 I WifiManager: packageName : com.test.thalitest
07-26 15:21:09.963   767  3013 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-26 15:21:09.963   767  3013 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:09.963   767  3013 D SecContentProvider2: mCursor = null
07-26 15:21:09.963   767  3013 D WifiService: setWifiEnabled: true pid=7221, uid=10079
07-26 15:21:09.963   767  3013 W ActivityManager: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:09.963   767  3013 W WifiService: Failed getting userId using ActivityManagerNative
07-26 15:21:09.963   767  3013 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:09.963   767  3013 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-26 15:21:09.963   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-26 15:21:09.963   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-26 15:21:09.963   767  3013 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-26 15:21:09.963   767  3013 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:21:09.963   767  3013 D SettingsProvider: name = wifi_on
07-26 15:21:09.963  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.963  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999f03d added. We now have 3 listener(s)
07-26 15:21:09.963  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.973  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.973  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ec1032 added. We now have 4 listener(s)
07-26 15:21:09.973  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.973  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:09.973  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f1e5183 added. We now have 5 listener(s)
07-26 15:21:09.973  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:09.973  7221  7279 I WifiManager: packageName : com.test.thalitest
07-26 15:21:09.973   767  1473 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-26 15:21:09.973   767  1473 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:09.973   767  1473 D SecContentProvider2: mCursor = null
07-26 15:21:09.973   767  1473 D WifiService: setWifiEnabled: false pid=7221, uid=10079
07-26 15:21:09.973   767  1473 D SettingsProvider: name = wifi_on
,07-26 15:21:09.973  7221  7279 D BluetoothAdapter: disable()
07-26 15:21:09.973   767  3013 D SettingsProvider: name = bluetooth_on
07-26 15:21:09.983   767  1148 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:21:09.983  1303  1303 I wpa_supplicant: reset timer : RESET_TIMER 0
07-26 15:21:09.983  1303  1303 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 15:21:09.983  1303  1303 I wpa_supplicant: P2P: Current p2p state = IDLE
07-26 15:21:09.983   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:09.983  2987  3042 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-26 15:21:09.983   767   787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:09.983  2987  3042 D BluetoothAdapterProperties: Setting state to 13
07-26 15:21:09.983  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:21:09.983   767   787 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a322301, r.packageName :com.android.bluetooth
07-26 15:21:09.983  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:09.983  2987  3042 D BluetoothAdapterService: updateAdapterState state is 13
07-26 15:21:09.983  2987  2987 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-26 15:21:09.983  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@18965da3, channel: 19, state: LISTENING
07-26 15:21:09.983  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@18965da3, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3e95942b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@179fb8a0mSocket: android.net.LocalSocket@25028c59 impl:android.net.LocalSocketImpl@2eaf101e fd:FileDescriptor[78]
07-26 15:21:09.983  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25028c59 impl:android.net.LocalSocketImpl@2eaf101e fd:FileDescriptor[78]
07-26 15:21:09.983  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:09.983  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:09.983  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-26 15:21:09.983  2987  3042 D BluetoothAdapterService: terminating service from this receiver
07-26 15:21:09.983   767  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.993  1303  1303 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-26 15:21:09.993  2987  3042 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:21:09.993   767  1320 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-26 15:21:09.993  2987  3042 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-26 15:21:09.993  2987  3048 D bt_vendor: op for 7
07-26 15:21:09.993  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:09.993  2987  3048 D bt_vendor: op for 7
07-26 15:21:09.993  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:09.993  2987  3045 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:09.993  2987  3048 D bt_vendor: op for 7
07-26 15:21:09.993  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:09.993  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-26 15:21:09.993  2987  3042 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-26 15:21:09.993  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:09.993  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:09.993  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:09.993  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:09.993  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:09.993   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:09.993  2987  3042 E bt-btif : cmd socket is not created
07-26 15:21:10.003  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.003  2987  5718 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:10.003  2987  3046 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
07-26 15:21:10.003   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.003  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.003  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.003  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.003   767  1148 E native  : do suspend true
07-26 15:21:10.003  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.003  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.003  2987  3042 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-26 15:21:10.003  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.003  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.003   767  1147 D WifiP2pService: InactiveState{ what=143375 }
07-26 15:21:10.003   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-26 15:21:10.003  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.003  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.013  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.013  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.013  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.013  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:10.013   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:10.013  1197  1197 D BluetoothTile:  onBluetoothStateChange:
07-26 15:21:10.013   767   767 I InputMethodManagerService: [BT Setting State] State =13
07-26 15:21:10.013  2987  3046 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
07-26 15:21:10.013  2987  3046 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
07-26 15:21:10.013  2987  3046 W bt-btif : invalid rfc slot id: 4
,07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:10.023  2987  3046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:10.023  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.023  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:10.023  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.023  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:10.023  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-26 15:21:10.023  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
,07-26 15:21:10.023  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:10.023  2987  3048 D bt_vendor: op for 7
07-26 15:21:10.023  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:10.023   767  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.023  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
,07-26 15:21:10.023   767  3013 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:10.023  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:10.023  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:21:10.023  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:21:10.023  1694  1694 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-26 15:21:10.023   767  1260 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-26 15:21:10.023   296  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:10.033  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:10.033  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:21:10.033   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.033  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-26 15:21:10.043  4295  4295 D BluetoothPbap: Proxy object disconnected
07-26 15:21:10.043  4295  4295 D PbapServerProfile: Bluetooth service disconnected
,07-26 15:21:10.043  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:10.053   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.053  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3857becc, channel: 5, state: LISTENING
,07-26 15:21:10.053  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3857becc, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d176088, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@17469515mSocket: android.net.LocalSocket@db8102a impl:android.net.LocalSocketImpl@16c7de1b fd:FileDescriptor[80]
,07-26 15:21:10.053  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@db8102a impl:android.net.LocalSocketImpl@16c7de1b fd:FileDescriptor[80]
07-26 15:21:10.053  2987  2987 I BtOppRfcommListener: stopping Accept Thread
07-26 15:21:10.053  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3ca7fbb8, channel: 12, state: LISTENING
07-26 15:21:10.053  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3ca7fbb8, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c8a38d2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a886d91mSocket: android.net.LocalSocket@3c9f04f6 impl:android.net.LocalSocketImpl@f7c40f7 fd:FileDescriptor[83]
,07-26 15:21:10.053  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3c9f04f6 impl:android.net.LocalSocketImpl@f7c40f7 fd:FileDescriptor[83]
07-26 15:21:10.053  2987  5718 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:21:10.053  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.053   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.063  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.063   767  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.063  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.063   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:10.063   767  1150 E ConnectivityService: updateNetworkInfo()
,07-26 15:21:10.063   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-26 15:21:10.063   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:10.063   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:10.063   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-26 15:21:10.063   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,07-26 15:21:10.073   767  1569 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D QSpanel : label top:23
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:10.073  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:10.083   767   767 D WifiScanningService: SCAN_AVAILABLE : 1
,07-26 15:21:10.083   767  1166 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.083   767   767 D RttService: SCAN_AVAILABLE : 1
,07-26 15:21:10.083   767  1167 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:10.093   767  1147 D WifiP2pService: InactiveState{ what=131204 }
,07-26 15:21:10.093   767  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-26 15:21:10.093   767  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-26 15:21:10.093   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.093   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:10.093   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
,07-26 15:21:10.093   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-26 15:21:10.093   767  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-26 15:21:10.103  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.103  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-26 15:21:10.103   767  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-26 15:21:10.103   767  1147 D WifiP2pService: P2pDisablingState
07-26 15:21:10.103   767  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
07-26 15:21:10.103   767   767 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-26 15:21:10.103   767  1058 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-26 15:21:10.103   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:10.103   767  1058 D WifiDisplayController: disconnect
07-26 15:21:10.103   767  1058 D WifiDisplayController: updateConnection
07-26 15:21:10.103   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:10.103   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.103   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:10.103   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-26 15:21:10.103   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
07-26 15:21:10.103   767  1523 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.103   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.103   767  1058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 15:21:10.103   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.103   767  1569 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
07-26 15:21:10.103   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-26 15:21:10.103   767  1147 D WifiP2pService: p2p socket connection lost
07-26 15:21:10.103   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.113   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
07-26 15:21:10.113   767  1148 E native  : do suspend true
07-26 15:21:10.113   767  1729 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 15:21:10.113   767  1147 D WifiP2pService: P2pDisabledState
,07-26 15:21:10.113   767  1729 I qtaguid : Tagging socket 403 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 767, getuid(): 1000
07-26 15:21:10.113  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:10.113   767  1569 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-26 15:21:10.113   767  1569 D ActivityManager: caller:android.app.ApplicationThreadProxy@ef3139, r.packageName :com.android.settings
,07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.113  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.113  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:10.123  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.123  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.123   767  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-26 15:21:10.123   767  1147 D WifiP2pService: DefaultState{ what=143375 }
,07-26 15:21:10.123  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-26 15:21:10.123   767  3837 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:10.123   767  1471 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 15:21:10.123   767  1471 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-26 15:21:10.123  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-26 15:21:10.123   767  1471 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-26 15:21:10.123   767  1471 D BatteryService: stay LED for fully charged
07-26 15:21:10.123   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 15:21:10.123   767   767 I MotionRecognitionService: Plugged
07-26 15:21:10.123   767   767 I MotionRecognitionService: setPowerConnected  = true
,07-26 15:21:10.133  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 15:21:10.133  2987  3214 D HeadsetStateMachine: Disconnected process message: 10
,07-26 15:21:10.133  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:10.133  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.133  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:10.133  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 15:21:10.133   767  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.133   767  1729 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 15:21:10.133  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-26 15:21:10.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-26 15:21:10.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-26 15:21:10.133  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-26 15:21:10.133  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 15:21:10.133   296  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:10.143   767  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-26 15:21:10.143   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:10.143   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.143   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:10.143   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.143   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:10.143   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:10.143   767  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:10.143   767  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-26 15:21:10.143  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-26 15:21:10.143   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 15:21:10.143  1303  1303 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-26 15:21:10.143   767  1150 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:10.143   767  1150 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:21:10.143   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-26 15:21:10.143   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-26 15:21:10.143   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.143   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:10.143   767  1729 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-26 15:21:10.143  1428  1428 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:10.143   767  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-26 15:21:10.143   767  1150 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
07-26 15:21:10.143   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-26 15:21:10.143   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:10.143   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:10.143   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:10.153   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.153   767  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:10.153  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:10.153   767  1320 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.153   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:10.153   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:10.153   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:10.153   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-26 15:21:10.153  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:10.153   767  1145 V NetworkStats: updateIfacesLocked()
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:10.153   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:10.153   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.153  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.153  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.153  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.153   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-26 15:21:10.153   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.153   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.153  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:10.153  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.153   767  1150 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,07-26 15:21:10.153   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.153   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:10.153   767  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-26 15:21:10.153   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.153  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.153  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:10.153   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.153   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:10.153   767  1151 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:10.153   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:10.153  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.153   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:10.153   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:10.153   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:10.153  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.153  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-26 15:21:10.153  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:10.153  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.163   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:10.163  1197  1197 D HotspotTile: onReceive : 0, 0
07-26 15:21:10.163  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-26 15:21:10.163  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-26 15:21:10.163  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-26 15:21:10.163   767  1145 V NetworkStats: performPollLocked() took 10ms
07-26 15:21:10.163   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:10.163  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:10.163  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-26 15:21:10.163  4295  4295 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:10.163   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.163   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:10.163   767  3783 I AudioService: getStreamVolume 3 index 0
07-26 15:21:10.163  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:10.173   767   788 D SecContentProvider2: uri = 14 selection = getSealedState
07-26 15:21:10.173   767   788 D SecContentProvider2: mCursor = null
,07-26 15:21:10.173   767  1143 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:10.173   767  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@3508a7f5, r.packageName :com.google.android.gms
,07-26 15:21:10.173   767  3783 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-26 15:21:10.173   767  3783 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:10.173  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.183  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:10.183  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:10.183  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:10.193  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:10.193  1197  1197 D QSpanel : label top:23
,07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:10.193  1723  7319 I VacuumService: Vacuum at: now=1469539270197 tag=VacuumService
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
,07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:10.193   767  1633 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:10.193  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:10.193   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.193   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.193   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.193   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.193  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:21:10.193  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:21:10.193  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:10.193  1197  1197 I PhoneStatusBar: Icon Only
07-26 15:21:10.193  1197  1197 I StatusBar: Icon Only
,07-26 15:21:10.193  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:10.203  1303  1303 I wpa_supplicant: Blacklist: Clear (all) 
07-26 15:21:10.203  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:10.203  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-26 15:21:10.203  2987  3042 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 15:21:10.203  2987  3042 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-26 15:21:10.203  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
07-26 15:21:10.203  2987  3042 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-26 15:21:10.203  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-26 15:21:10.203  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:10.203  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:10.203   304   304 E SMD     : DCD ON
,07-26 15:21:10.233  1303  1303 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-26 15:21:10.233  7320  7320 E Zygote  : MountEmulatedStorage()
07-26 15:21:10.233  7320  7320 E Zygote  : v2
07-26 15:21:10.233  7320  7320 I libpersona: KNOX_SDCARD checking this for 10140
07-26 15:21:10.233  7320  7320 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:10.243   767  1633 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7320 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-26 15:21:10.243  1303  1303 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,07-26 15:21:10.243  1303  1303 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-26 15:21:10.243   767  3783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:10.243  1303  1303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
07-26 15:21:10.243  1303  1303 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-26 15:21:10.243   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c7c5bfb, r.packageName :com.android.bluetooth
,07-26 15:21:10.243  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-26 15:21:10.243  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-26 15:21:10.263  7320  7320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:10.263   767  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:10.263  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-26 15:21:10.263   767  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@41bd418, r.packageName :com.android.bluetooth
07-26 15:21:10.263  7320  7320 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:10.263  2987  2987 D HeadsetService: Received stop request...Stopping profile...
07-26 15:21:10.263  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-26 15:21:10.263  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:10.263  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:10.263  7320  7320 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:10.263  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-26 15:21:10.263   767   767 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-26 15:21:10.263   767   787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:10.263   767   787 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d08ce71, r.packageName :com.android.bluetooth
,07-26 15:21:10.263  4295  4295 D HeadsetProfile: Bluetooth service disconnected
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-26 15:21:10.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-26 15:21:10.273   767  3013 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:10.273   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@280c8456, r.packageName :com.android.bluetooth
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-26 15:21:10.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-26 15:21:10.273   767  1633 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:10.273   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@e2abcd7, r.packageName :com.android.bluetooth
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:10.273   767  3783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:10.273   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@330619c4, r.packageName :com.android.bluetooth
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-26 15:21:10.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-26 15:21:10.273  2987  3042 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-26 15:21:10.283   767  3837 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:10.283   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@70ae0ad, r.packageName :com.android.bluetooth
,07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:10.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:10.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-26 15:21:10.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-26 15:21:10.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 15:21:10.283  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-26 15:21:10.283  2987  3042 D BluetoothAdapterState: Stopping profile services that were post enabled
,07-26 15:21:10.283  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-26 15:21:10.283  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:10.283  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-26 15:21:10.283  2987  2987 D A2dpService: Received stop request...Stopping profile...
07-26 15:21:10.283  2987  2987 V Avrcp   : doQuit
,07-26 15:21:10.283  2987  3226 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:21:10.283  2987  2987 D Avrcp   : Unregistering previous receiver
,07-26 15:21:10.283  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.283  4295  4295 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:10.283  4295  4295 D A2dpProfile: Bluetooth service disconnected
,07-26 15:21:10.283   767   767 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:10.283   767   767 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-26 15:21:10.283  3182  3182 D BluetoothA2dp: Proxy object disconnected
,07-26 15:21:10.283  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.283  2987  2987 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:21:10.283  2987  2987 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-26 15:21:10.293  2987  2987 D HidService: Received stop request...Stopping profile...
07-26 15:21:10.293  2987  2987 D HidService: Stopping Bluetooth HidService
07-26 15:21:10.293  2987  2987 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:21:10.293  2987  2987 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-26 15:21:10.293  2987  2987 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:21:10.293  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.293  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.293  2987  2987 D HealthService: Received stop request...Stopping profile...
07-26 15:21:10.293  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.293  2987  2987 D PanService: Received stop request...Stopping profile...
07-26 15:21:10.293  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.293  4295  4295 D BluetoothInputDevice: Proxy object disconnected
,07-26 15:21:10.293  4295  4295 D HidProfile: Bluetooth service disconnected
07-26 15:21:10.293   767   767 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:21:10.293  7320  7320 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:10.293  2987  2987 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:21:10.293  4295  4295 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:21:10.293  7320  7320 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:10.293  4295  4295 D PanProfile: Bluetooth service disconnected
07-26 15:21:10.293  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.293  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.293  2987  2987 D SapService: Received stop request...Stopping profile...
07-26 15:21:10.293  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.293  2987  2987 D SapService: Stopping Bluetooth SapService
07-26 15:21:10.293  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:10.293  4295  4295 D BluetoothMap: Proxy object disconnected
07-26 15:21:10.293  4295  4295 D MapProfile: Bluetooth service disconnected
,07-26 15:21:10.303  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.303  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-26 15:21:10.303  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:10.303  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-26 15:21:10.303  2987  2987 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:10.303  2987  2987 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-26 15:21:10.313  2987  3227 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,07-26 15:21:10.313  2987  2987 I GKI_LINUX: GKI_exit_task 2 done
07-26 15:21:10.313  2987  2987 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-26 15:21:10.313  2987  2987 V Avrcp   : cleanup
07-26 15:21:10.313  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.313  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:10.313  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:10.313  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:21:10.313  2987  2987 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:21:10.313  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:10.313  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:10.313  2987  2987 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:21:10.313  2987  2987 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-26 15:21:10.313  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:10.313  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-26 15:21:10.313  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-26 15:21:10.313  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:10.313  2987  2987 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-26 15:21:10.313  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-26 15:21:10.313  2987  2987 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-26 15:21:10.313  2987  3042 D BluetoothAdapterProperties: Setting state to 10
07-26 15:21:10.313  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-26 15:21:10.313  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:10.313  2987  3042 D BluetoothAdapterService: updateAdapterState state is 10
07-26 15:21:10.313  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:10.313  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-26 15:21:10.313  2987  3042 I BluetoothAdapterState: Entering OffState
,07-26 15:21:10.313  4295  4306 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:10.313  4295  4295 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-26 15:21:10.313  4295  4295 D SapProfile: Bluetooth service disconnected
07-26 15:21:10.313  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.313  1303  1303 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:10.313   767  1057 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:21:10.313  4295  4304 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:10.313  2987  3381 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:10.313  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.313  4295  4306 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:21:10.313  4295  4304 D Bluetoothsap: onBluetoothStateChange: up=false
07-26 15:21:10.313  4295  4304 D Bluetoothsap: Unbinding service...
,07-26 15:21:10.323  3182  3191 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:10.323  4295  4306 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-26 15:21:10.323  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.323   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:10.323   767   767 I InputMethodManagerService: [BT Setting State] State =10
07-26 15:21:10.323   767   767 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-26 15:21:10.323  7320  7320 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
07-26 15:21:10.323  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.323  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:10.323  1694  1694 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-26 15:21:10.333  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-26 15:21:10.333  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:10.333  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:10.333  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.333  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.333   767  1260 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:10.333   767  3013 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-26 15:21:10.333  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-26 15:21:10.333  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-26 15:21:10.333  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:10.333  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.343  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
,07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D QSpanel : label top:23
,07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:10.353  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:10.473   767  1151 D Tethering: InitialState.processMessage what=4
07-26 15:21:10.473  1303  1303 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-26 15:21:10.473   767  1151 E Tethering: No numeric data
07-26 15:21:10.473   767  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:21:10.473   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:10.473   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.473  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-26 15:21:10.473  1197  1197 D HotspotTile: updateTetherState():false, false
,07-26 15:21:10.473   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-26 15:21:10.473   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.473   767  1145 V NetworkStats: performPollLocked() took 5ms
,07-26 15:21:10.473   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:10.483   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:10.483   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=184 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.File.exists(File.java:363)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563   767  1523 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.k.c(PG:583)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.563  7320  7320 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.io.File.exists(File.java:363)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:10.563  7320  7320 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:10.563   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.563   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:10.593  7320  7353 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-26 15:21:10.603  7360  7360 E Zygote  : MountEmulatedStorage()
07-26 15:21:10.603  7360  7360 E Zygote  : v2
07-26 15:21:10.603  7360  7360 I libpersona: KNOX_SDCARD checking this for 10038
07-26 15:21:10.603  7360  7360 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:10.613  7360  7360 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:10.613  7360  7360 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:10.613  7360  7360 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-26 15:21:10.613   767  1523 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7360 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-26 15:21:10.613   767  1523 I ActivityManager: Killing 6323:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
07-26 15:21:10.623   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-26 15:21:10.623   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-26 15:21:10.623   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.633  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.633  1917  1917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:10.633  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:10.633  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:10.633  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-26 15:21:10.633  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.633  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-26 15:21:10.633  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:10.633  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-26 15:21:10.643  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.643  1197  1197 D HotspotTile: onReceive : 1, 0
,07-26 15:21:10.653  7360  7360 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:10.653  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:10.653  7360  7360 D ActivityThread: Added TimaKeyStore provider
07-26 15:21:10.653   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:10.653   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:10.653   767   767 I ApplicationPolicy: updateDataUsageMap
07-26 15:21:10.653   767   767 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.653  1626  1626 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-26 15:21:10.653  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.663  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:10.663   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.663   767  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.663  1197  1197 D QSpanel : label top:23
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:10.663  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:10.693   767   957 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:10.693   767   957 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.733   767  1482 I art     : Explicit concurrent mark sweep GC freed 55349(3MB) AllocSpace objects, 19(352KB) LOS objects, 30% free, 36MB/52MB, paused 1.332ms total 102.789ms
,07-26 15:21:10.733   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-26 15:21:10.733   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:10.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:10.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:10.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:10.743   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:10.743  7360  7360 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-26 15:21:10.753  7360  7360 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-26 15:21:10.783  1917  4264 I art     : Explicit concurrent mark sweep GC freed 17524(969KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 19MB/32MB, paused 454us total 25.711ms
,07-26 15:21:10.823   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-26 15:21:10.873  7360  7360 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-26 15:21:10.973  7360  7360 E BluetoothHeadset: BTStateChangeCB is registed
,07-26 15:21:10.983   767  1260 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:10.983  7360  7360 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:10.983   767  1426 I ActivityManager: Killing 3830:com.google.android.gms.wearable/u0a15 (adj 15): emptyCount ##41
,07-26 15:21:10.983  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:10.983  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:10.983   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.983  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:10.983   767  1143 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:10.983  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:10.983  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:10.983  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-26 15:21:10.983  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:10.993   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:10.993  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:11.003  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:11.003  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-26 15:21:11.003   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:11.003  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:11.003   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:11.003  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:11.003  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:11.003  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-26 15:21:11.003  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-26 15:21:11.003   767  3783 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,07-26 15:21:11.003   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.003   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.003   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.003   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.003  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-26 15:21:11.043  7383  7383 E Zygote  : MountEmulatedStorage()
07-26 15:21:11.043  7383  7383 E Zygote  : v2
07-26 15:21:11.043  7383  7383 I libpersona: KNOX_SDCARD checking this for 10088
07-26 15:21:11.043  7383  7383 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:11.053   767  3783 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7383 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:11.063  7383  7383 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:11.063  7383  7383 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:11.063  7383  7383 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:11.083  7383  7383 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:11.083  7383  7383 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:11.093  7383  7383 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,07-26 15:21:11.103  7383  7383 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-26 15:21:11.103   767  1115 V AlarmManager: waitForAlarm result :4
,07-26 15:21:11.113  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-26 15:21:11.113  1197  1197 D KeyguardUpdateMonitor: handleTimeUpdate
,07-26 15:21:11.113   767  1482 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-26 15:21:11.113   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.113   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.113   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.113   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.153  7398  7398 E Zygote  : MountEmulatedStorage()
07-26 15:21:11.153  7398  7398 E Zygote  : v2
07-26 15:21:11.153  7398  7398 I libpersona: KNOX_SDCARD checking this for 10192
07-26 15:21:11.153  7398  7398 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:11.153   767  1482 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7398 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:11.163  7398  7398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:11.163  7398  7398 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:11.163   767  1482 I ActivityManager: Killing 6530:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
07-26 15:21:11.163  7398  7398 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:21:11.163  1197  1197 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-26 15:21:11.163  1197  1197 I KeyguardEffectViewController: *** don't update sliding image ***
,07-26 15:21:11.173   359   359 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 326us total 13.827ms
,07-26 15:21:11.183   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 267us total 9.575ms
,07-26 15:21:11.193   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.735ms
,07-26 15:21:11.193  7398  7398 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:11.193  7398  7398 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:11.203  7398  7398 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-26 15:21:11.223  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:11.223  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-26 15:21:11.223  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-26 15:21:11.223  7398  7398 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-26 15:21:11.223  1197  1197 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-26 15:21:11.233  7398  7398 D WifiDirectBR: stopServiceTest : false
,07-26 15:21:11.233  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-26 15:21:11.233   767  1569 I ActivityManager: Killing 6556:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-26 15:21:11.243  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:11.243  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:11.243   767  1260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:11.243  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:11.243   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-26 15:21:11.243  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:11.243  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:11.243  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:11.243  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:11.263   767  1523 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:11.263  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:11.263   767  3783 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-26 15:21:11.263   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.263   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.263   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.263   767  3783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.343  7416  7416 E Zygote  : MountEmulatedStorage()
,07-26 15:21:11.343  7416  7416 E Zygote  : v2
07-26 15:21:11.343  7416  7416 I libpersona: KNOX_SDCARD checking this for 10131
07-26 15:21:11.343  7416  7416 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:11.353   767  3783 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7416 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-26 15:21:11.363  7416  7416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:11.363  7416  7416 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:11.363  7416  7416 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:11.383  7416  7416 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:11.383  7416  7416 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:11.393  7416  7416 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-26 15:21:11.393  7416  7416 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-26 15:21:11.523  2987  3048 D bt_vendor: op for 7
,07-26 15:21:11.583  7416  7445 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-26 15:21:11.583  7416  7445 I Babel   : MmsConfig.loadMmsSettings
07-26 15:21:11.583  7416  7445 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-26 15:21:11.583  7416  7445 I Babel   : MmsConfig.loadFromDatabase
,07-26 15:21:11.593  7416  7445 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,07-26 15:21:11.593  7416  7416 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-26 15:21:11.593  7416  7445 I Babel   : MmsConfig.loadFromResources
,07-26 15:21:11.593  7416  7445 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-26 15:21:11.593  7416  7445 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-26 15:21:11.613   767  1320 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-26 15:21:11.613  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:11.643  7416  7416 I Babel_StickerModule: App launched.
,07-26 15:21:11.643  7416  7416 I Babel_StickerModule: Trying first logged in account.
,07-26 15:21:11.653  7416  7416 W Babel_StickerModule: Unable to load, account not configured.
,07-26 15:21:11.663  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:11.663   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:11.663  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-26 15:21:11.663  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:11.663  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
,07-26 15:21:11.663  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:11.663   314   764 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-26 15:21:11.663   314   764 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-26 15:21:11.663   314   764 W QCamera2Factory: getCameraInfo: X
,07-26 15:21:11.683   314   765 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-26 15:21:11.683   314   765 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-26 15:21:11.683   314   765 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-26 15:21:11.683   314   765 W QCamera2Factory: getCameraInfo: X
,07-26 15:21:11.683  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:21:11.683   767  3783 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-26 15:21:11.683   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@88a0d45, r.packageName :com.android.settings
,07-26 15:21:11.693  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:11.693  4295  4295 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:11.693  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:11.723  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:11.723   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:11.723  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:11.723  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:11.723  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:11.723  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:11.733  7416  7416 W AudioCapabilities: Unsupported mime audio/evrc
,07-26 15:21:11.733  6632  6632 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-26 15:21:11.733  6632  6632 I PCWCLIENTTRACE_PushUtil: sales region : global
07-26 15:21:11.733  6632  6632 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:21:11.733  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:11.733  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-26 15:21:11.743  7416  7416 W AudioCapabilities: Unsupported mime audio/qcelp
,07-26 15:21:11.743  7416  7416 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:21:11.753   767  1482 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-26 15:21:11.753   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.753  7416  7416 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-26 15:21:11.753   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.753   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:11.753  7416  7416 W AudioCapabilities: Unsupported mime audio/mpeg-L2
07-26 15:21:11.753   767  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:11.753  7416  7416 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-26 15:21:11.753  7416  7416 W AudioCapabilities: Unsupported mime audio/x-ima
,07-26 15:21:11.753  7416  7416 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-26 15:21:11.763  7416  7416 W AudioCapabilities: Unsupported mime audio/qcelp
,07-26 15:21:11.763  7416  7416 W AudioCapabilities: Unsupported mime audio/evrc
,07-26 15:21:11.763  7416  7416 W VideoCapabilities: Unsupported mime video/wvc1
,07-26 15:21:11.763  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-26 15:21:11.773  7416  7416 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-26 15:21:11.773  7416  7416 W VideoCapabilities: Unsupported mime video/wvc1
,07-26 15:21:11.773  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-26 15:21:11.773  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-26 15:21:11.783  7416  7416 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-26 15:21:11.783  7416  7416 W VideoCapabilities: Unsupported mime video/mp43
,07-26 15:21:11.783  7416  7416 W VideoCapabilities: Unsupported mime video/sorenson
,07-26 15:21:11.783  7416  7416 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-26 15:21:11.793  7458  7458 E Zygote  : MountEmulatedStorage()
07-26 15:21:11.793  7458  7458 E Zygote  : v2
07-26 15:21:11.793  7458  7458 I libpersona: KNOX_SDCARD checking this for 10144
07-26 15:21:11.793  7458  7458 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:11.793   767  1482 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7458 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:11.833  7458  7458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:11.833  7458  7458 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:11.833  7458  7458 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:11.833  7416  7416 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-26 15:21:11.843  7458  7458 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:11.853  7458  7458 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:11.863   767  1569 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-26 15:21:11.863  7458  7458 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-26 15:21:11.893   767  1320 I ActivityManager: Killing 6575:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-26 15:21:11.913  2987  3154 D bt_upio : ..proc_btwrite_timeout..
,07-26 15:21:11.963  7458  7458 I MusicStore: Database version: 108
,07-26 15:21:11.983   767  1569 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.023  7458  7458 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-26 15:21:12.033  7458  7458 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-26 15:21:12.033  7458  7458 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-26 15:21:12.053  7458  7458 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,07-26 15:21:12.103  7458  7458 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-26 15:21:12.103  7458  7458 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3857becc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
07-26 15:21:12.103  7458  7458 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-26 15:21:12.103  7458  7458 D AndroidMusic: GMSCore installation verified
,07-26 15:21:12.113   767  1320 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.113  7458  7458 I ConfigStore: Config Database version: 1
,07-26 15:21:12.143   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-26 15:21:12.143   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:12.143  7458  7458 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-26 15:21:12.143   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-26 15:21:12.143   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:12.143  7458  7458 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-26 15:21:12.153   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-26 15:21:12.153   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:12.153  7458  7458 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-26 15:21:12.153   767  1143 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-26 15:21:12.153   767  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@1849a04a, r.packageName :com.google.android.music
,07-26 15:21:12.163   767  1569 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.173   767  1446 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:12.183   767   787 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:12.183   767  1633 I AudioService: getStreamVolume 3 index 0
,07-26 15:21:12.183  7458  7458 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-26 15:21:12.193  7458  7458 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-26 15:21:12.203   767  1569 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.203   767   787 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.213   767  1260 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.213   767  1523 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:12.213   767  1143 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-26 15:21:12.213   767  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.213   767  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.213   767  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.213   767  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.263  7491  7491 E Zygote  : MountEmulatedStorage()
,07-26 15:21:12.263  7491  7491 E Zygote  : v2
07-26 15:21:12.263  7491  7491 I libpersona: KNOX_SDCARD checking this for 10004
07-26 15:21:12.263  7491  7491 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:12.263   767  1143 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7491 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:12.273  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:12.273  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:12.273  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:12.293  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:12.293  7491  7491 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:12.303   767  1143 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-26 15:21:12.313  7458  7458 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-26 15:21:12.313   767  1446 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:12.313  7491  7491 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-26 15:21:12.333   767  1569 I ActivityManager: Killing 6596:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-26 15:21:12.363   767  1523 I ActivityManager: Killing 6668:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-26 15:21:12.363   767  1523 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-26 15:21:12.363   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.363   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.363   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.363   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.403  7511  7511 E Zygote  : MountEmulatedStorage()
07-26 15:21:12.403   767  1523 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-26 15:21:12.403  7511  7511 E Zygote  : v2
07-26 15:21:12.403  7511  7511 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:21:12.403  7511  7511 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:12.433  7511  7511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:12.433  7511  7511 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:12.433  7511  7511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:12.453  7511  7511 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:12.453  7511  7511 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:12.473  7511  7511 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-26 15:21:12.503  7511  7511 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-26 15:21:12.523  7511  7511 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-26 15:21:12.623  7511  7511 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-26 15:21:12.633  7511  7511 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-26 15:21:12.633  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:12.633  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-26 15:21:12.693  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-26 15:21:12.703  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-26 15:21:12.723  6990  6990 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-26 15:21:12.733   767  1523 I ActivityManager: Killing 5307:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,07-26 15:21:12.743   767  3013 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:12.743   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@181e4e95, r.packageName :com.google.android.gms
,07-26 15:21:12.743  2281  2281 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-26 15:21:12.753  2281  7535 I iu.SyncManager: SYNC; picasa accounts
,07-26 15:21:12.763  2281  7535 I iu.UploadsManager: num queued entries: 0
,07-26 15:21:12.763  2281  7535 I iu.UploadsManager: num updated entries: 0
,07-26 15:21:12.763   767  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:21:12.763   767  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d170baa, r.packageName :com.google.android.gms
07-26 15:21:12.763  2281  7535 I iu.SyncManager: NEXT; no task
,07-26 15:21:12.763  2281  2281 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
07-26 15:21:12.763  2281  2281 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-26 15:21:12.763  2281  2281 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:21:12.763  2281  2281 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-26 15:21:12.773  4174  4174 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-26 15:21:12.783  4174  4174 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469539272784
,07-26 15:21:12.783  4174  4174 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:12.783   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:12.783   767  1633 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:12.783  4174  4174 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-26 15:21:12.783  4174  4174 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
07-26 15:21:12.783   767  3013 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-26 15:21:12.783   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.783   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.783   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.783   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.833   767  1342 E Watchdog: !@Sync 5
,07-26 15:21:12.863  7538  7538 E Zygote  : MountEmulatedStorage()
,07-26 15:21:12.863  7538  7538 E Zygote  : v2
07-26 15:21:12.863  7538  7538 I libpersona: KNOX_SDCARD checking this for 10036
07-26 15:21:12.863  7538  7538 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:12.873   767  3013 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7538 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-26 15:21:12.883  7538  7538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:12.883  7538  7538 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:12.883  7538  7538 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:12.903  7538  7538 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:12.903  7538  7538 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:12.923  7538  7538 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-26 15:21:12.923  7538  7538 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:21:12.923  7538  7538 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:21:12.943  7538  7538 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-26 15:21:12.953   767  1523 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:12.963   767  1446 I ActivityManager: Killing 6686:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-26 15:21:12.973  7010  7010 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-26 15:21:12.983   767  1473 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-26 15:21:12.983   767  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.983   767  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.983   767  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:12.983   767  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:12.993   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:12.993  3467  7554 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-26 15:21:13.013  7221  7279 I WifiManager: packageName : com.test.thalitest
,07-26 15:21:13.013   767  3013 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-26 15:21:13.013   767  3013 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:13.013   767  3013 D SecContentProvider2: mCursor = null
07-26 15:21:13.013   767  1471 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:13.013  3467  7554 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-26 15:21:13.013  3467  7554 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-26 15:21:13.013   767  3013 D WifiService: setWifiEnabled: true pid=7221, uid=10079
07-26 15:21:13.013   767  3013 W ActivityManager: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-26 15:21:13.013  3467  7554 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-26 15:21:13.013  3467  7554 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-26 15:21:13.013   767  3013 W WifiService: Failed getting userId using ActivityManagerNative
07-26 15:21:13.013   767  3013 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:13.013   767  3013 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-26 15:21:13.013   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-26 15:21:13.013   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-26 15:21:13.013   767  3013 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-26 15:21:13.013   767  3013 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:21:13.013   767  3013 D SettingsProvider: name = wifi_on
,07-26 15:21:13.013   767  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-26 15:21:13.013   296  1055 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-26 15:21:13.013   296  1055 I WifiHW  : module is semco
07-26 15:21:13.013   296  1055 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-26 15:21:13.013   296  1055 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-26 15:21:13.013   296  1055 E WifiHW  : TEMP_FAILURE_RETRY complete
07-26 15:21:13.013   296  1055 D SoftapController: Softap fwReload - Ok
,07-26 15:21:13.023   296  1055 D CommandListener: Setting iface cfg
07-26 15:21:13.023   296  1055 D CommandListener: Trying to bring down wlan0
,07-26 15:21:13.023   296  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:13.023   767  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-26 15:21:13.033   767  1473 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7557 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:13.033   767  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,07-26 15:21:13.043  7557  7557 E Zygote  : MountEmulatedStorage()
07-26 15:21:13.043  7557  7557 E Zygote  : v2
,07-26 15:21:13.043  7557  7557 I libpersona: KNOX_SDCARD checking this for 10043
07-26 15:21:13.043  7557  7557 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:13.043   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:13.063  7557  7557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:13.063  7557  7557 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:13.063  7557  7557 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-26 15:21:13.063  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:13.063  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:13.063  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:13.063   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-26 15:21:13.063  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:13.063  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:13.063  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-26 15:21:13.063  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:13.063  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-26 15:21:13.063  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:13.063  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:13.063  1197  1197 D HotspotTile: onReceive : 2, 0
,07-26 15:21:13.073  7556  7556 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-26 15:21:13.073  7556  7556 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:13.073  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:13.073  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:13.083   389   389 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7556
07-26 15:21:13.083   389   389 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-26 15:21:13.083  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:13.083  7556  7556 I wpa_supplicant: ssSupport state is = 1
07-26 15:21:13.083  7556  7556 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-26 15:21:13.083  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-26 15:21:13.083   389   389 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7556
07-26 15:21:13.083   389   389 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-26 15:21:13.083  1197  1197 D QSpanel : label top:23
07-26 15:21:13.083  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:13.083  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:13.083  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:13.083  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:13.083  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:13.093  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:13.093  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:13.093  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:13.093  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:13.093  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:13.093  7557  7557 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:13.093  7557  7557 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:13.103  7557  7557 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-26 15:21:13.133  7557  7557 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-26 15:21:13.133  7557  7557 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-26 15:21:13.143  7557  7557 D SPPClientService: PushLog.txt file is not deleted.
07-26 15:21:13.143  7557  7557 D SPPClientService: PushLog.txt file is not deleted.
,07-26 15:21:13.143  7557  7557 D SPPClientService: ============PushLog. stop!
,07-26 15:21:13.143  7557  7557 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-26 15:21:13.153  6722  6722 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-26 15:21:13.153   767  1260 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
07-26 15:21:13.153  6722  6722 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-26 15:21:13.153   767  1260 D ActivityManager: caller:android.app.ApplicationThreadProxy@14e82338, r.packageName :com.sec.spp.push
07-26 15:21:13.153  6722  6722 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-26 15:21:13.153  6722  6722 I SA      : [SLFUCHKMGR] constructor called
,07-26 15:21:13.163  6722  6722 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 15:21:13.163  6722  6722 I SA      : [OR] == isSIMCardReady false ==
,07-26 15:21:13.163  6722  6722 I SA      : [SCU] == networkStateCheck == false
07-26 15:21:13.163  6722  6722 I SA      : [OR] onReceive END
07-26 15:21:13.163  7557  7583 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-26 15:21:13.163   767  1446 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-26 15:21:13.163   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:13.163   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.163   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.163   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:13.203  7586  7586 E Zygote  : MountEmulatedStorage()
,07-26 15:21:13.203  7586  7586 E Zygote  : v2
07-26 15:21:13.203  7586  7586 I libpersona: KNOX_SDCARD checking this for 10074
07-26 15:21:13.203  7586  7586 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:13.203   304   304 E SMD     : DCD ON
,07-26 15:21:13.213   767  1446 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7586 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-26 15:21:13.273  7586  7586 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:13.273  7586  7586 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:13.273  7586  7586 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-26 15:21:13.273   767   787 I ActivityManager: Killing 5849:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-26 15:21:13.293  7586  7586 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:13.293  7586  7586 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:13.313  7586  7586 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-26 15:21:13.343   389   389 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-26 15:21:13.363  7586  7586 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-26 15:21:13.363  7586  7586 I SCloudBackupReceiver: Other Intent
07-26 15:21:13.373   767  1633 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,07-26 15:21:13.373   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.373   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.373   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.373   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:13.403  7602  7602 E Zygote  : MountEmulatedStorage()
,07-26 15:21:13.403  7602  7602 E Zygote  : v2
07-26 15:21:13.413  7602  7602 I libpersona: KNOX_SDCARD checking this for 1000
07-26 15:21:13.413  7602  7602 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:13.413   767  1633 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-26 15:21:13.413   767  1633 I ActivityManager: Killing 6744:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-26 15:21:13.423  7602  7602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:13.423  7602  7602 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:13.423  7602  7602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:13.443  7602  7602 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:13.443  7602  7602 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:13.453  7602  7602 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,07-26 15:21:13.453  7602  7602 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:21:13.463  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-26 15:21:13.463  7602  7602 I KnoxUsageLogPro: premStatus:2
,07-26 15:21:13.473  7602  7602 I KnoxUsageLogPro: isEulaShown : false
07-26 15:21:13.473  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 15:21:13.473   767  1523 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-26 15:21:13.473   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.473   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.473   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.473   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:13.513  7617  7617 E Zygote  : MountEmulatedStorage()
,07-26 15:21:13.513  7617  7617 E Zygote  : v2
07-26 15:21:13.513  7617  7617 I libpersona: KNOX_SDCARD checking this for 10104
07-26 15:21:13.513  7617  7617 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:13.523  7617  7617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:13.523  7617  7617 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:13.523  7617  7617 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-26 15:21:13.523   767  1523 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7617 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:13.523   767  1523 I ActivityManager: Killing 5793:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-26 15:21:13.543  7617  7617 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:13.543  7617  7617 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:13.563  7617  7617 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-26 15:21:13.603  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-26 15:21:13.623  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:13.623  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:13.623   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7556
07-26 15:21:13.623   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 15:21:13.623  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:13.623  7556  7556 I wpa_supplicant: ssSupport state is = 1
07-26 15:21:13.623  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:13.623  7556  7556 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:13.623  7556  7556 E wpa_supplicant: SIM READ ERROR
07-26 15:21:13.623  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:13.623  7556  7556 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:13.623  7556  7556 E wpa_supplicant: SIM READ ERROR
07-26 15:21:13.623  7556  7556 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:13.623  7556  7556 I wpa_supplicant: wpa_default_ap_write_once
07-26 15:21:13.623  7556  7556 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-26 15:21:13.623  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:13.623  7556  7556 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-26 15:21:13.623  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:13.623  7556  7556 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-26 15:21:13.623  7556  7556 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:13.633   767  1633 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-26 15:21:13.643   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.643   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.643   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:13.643   767  1633 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:13.683  7633  7633 E Zygote  : MountEmulatedStorage()
07-26 15:21:13.683  7633  7633 E Zygote  : v2
07-26 15:21:13.683  7633  7633 I libpersona: KNOX_SDCARD checking this for 10146
07-26 15:21:13.683  7633  7633 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:13.693  7633  7633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:13.693  7633  7633 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:13.693   767  1633 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7633 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-26 15:21:13.693   767  1633 I ActivityManager: Killing 6788:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-26 15:21:13.693  7633  7633 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:13.713  7633  7633 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:13.713  7633  7633 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:13.733  7633  7633 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-26 15:21:13.933   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-26 15:21:13.933   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:13.933  7633  7654 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-26 15:21:13.933   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-26 15:21:13.933   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:13.933  7633  7654 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-26 15:21:13.943   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-26 15:21:13.943   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:13.943  7633  7656 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-26 15:21:13.943   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-26 15:21:13.943   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:13.943  7633  7656 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-26 15:21:14.113  7633  7633 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-26 15:21:14.113  7633  7633 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-26 15:21:14.123  7633  7633 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 137-139)
,07-26 15:21:14.123  7633  7633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:21:14.133  7633  7633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17469515}
,07-26 15:21:14.133  7633  7633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:21:14.133  7633  7633 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:21:14.153  7633  7633 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:21:14.153  7633  7633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-26 15:21:14.153  7633  7633 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:21:14.273   767  1151 E Tethering: No numeric data
,07-26 15:21:14.273   767  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-26 15:21:14.273   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:14.273   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:14.273   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-26 15:21:14.283   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:14.283  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-26 15:21:14.283  1197  1197 D HotspotTile: updateTetherState():false, false
,07-26 15:21:14.283   767  1145 V NetworkStats: performPollLocked() took 3ms
,07-26 15:21:14.283   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:14.283   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:14.283   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:14.283  7633  7633 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-26 15:21:14.283  7633  7633 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-26 15:21:14.283  7633  7633 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-26 15:21:14.293  7556  7556 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-26 15:21:14.293  7633  7633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-26 15:21:14.293  7633  7633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-26 15:21:14.293  7633  7633 I Adreno-EGL: Build Date: 11/19/14 Wed
07-26 15:21:14.293  7633  7633 I Adreno-EGL: Local Branch: mybranch5813579
07-26 15:21:14.293  7633  7633 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-26 15:21:14.293  7633  7633 I Adreno-EGL: Local Patches: NONE
07-26 15:21:14.293  7633  7633 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-26 15:21:14.333  7556  7556 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:14.333   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7556
07-26 15:21:14.333   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:14.333  7556  7556 I wpa_supplicant: ssSupport state is = 1
,07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-26 15:21:14.333   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7556
07-26 15:21:14.333   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-26 15:21:14.333  7556  7556 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:14.333  7556  7556 I wpa_supplicant: ssSupport state is = 1
07-26 15:21:14.333  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-26 15:21:14.333  7556  7556 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:14.333  7556  7556 E wpa_supplicant: SIM READ ERROR
07-26 15:21:14.333  7556  7556 I wpa_supplicant: wpa_default_ap_write_once
07-26 15:21:14.333  7556  7556 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-26 15:21:14.333  7556  7556 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:14.353  7556  7556 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-26 15:21:14.353  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-26 15:21:14.363  7633  7684 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-26 15:21:14.363  7556  7556 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-26 15:21:14.363  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-26 15:21:14.363   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-26 15:21:14.363   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-26 15:21:14.363  7556  7556 I wpa_supplicant: HOTSPOT20_ENABLE called
07-26 15:21:14.363  7556  7556 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:14.363  7556  7556 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:14.363  7556  7556 E wpa_supplicant: SIM READ ERROR
07-26 15:21:14.363  7556  7556 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:14.373  7633  7633 I NSApplication: Starting up...
,07-26 15:21:14.383   767  1471 I ActivityManager: Killing 6816:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-26 15:21:14.393  7556  7556 I wpa_supplicant: Skip scan - bUseNetwork false
,07-26 15:21:14.393   767  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-26 15:21:14.393   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:14.403   767  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-26 15:21:14.403   767  1148 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:14.403  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:14.403  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:14.403  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:14.403  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:14.403  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:14.403  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:14.403  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:14.403  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:14.403  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:14.403  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:14.413  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:14.413  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:14.413  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:14.413  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-26 15:21:14.413  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:14.413  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:14.413  1197  1197 D HotspotTile: onReceive : 3, 0
,07-26 15:21:14.413   767  1148 E WifiConfigStore: Not a HS20
,07-26 15:21:14.413   767  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:21:14.413   767  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-26 15:21:14.423   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-26 15:21:14.423  7556  7556 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-26 15:21:14.423  7556  7556 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-26 15:21:14.423  7556  7556 I wpa_supplicant: reset timer : RESET_TIMER 0
07-26 15:21:14.423  7556  7556 I wpa_supplicant: P2P: Current p2p state = IDLE
07-26 15:21:14.423  7556  7556 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-26 15:21:14.423  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-26 15:21:14.423  7556  7556 I wpa_supplicant: First Scan Start
,07-26 15:21:14.423  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:21:14.433  7556  7556 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-26 15:21:14.433  1197  1197 D QSpanel : label top:23
07-26 15:21:14.433   767  1148 D WifiNative-HAL: Setting external_sim to 1
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:14.433   767  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:14.433   767  1148 I WifiNative-HAL: startHal
07-26 15:21:14.433   767  1148 E wifi    : getStaticLongField sWifiHalHandle 0x93b9e86c
07-26 15:21:14.433   767  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x701a1a
07-26 15:21:14.433   767  1148 I WifiNative-HAL: Could not start hal
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:14.433  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:14.453   767  1148 E native  : do suspend true
,07-26 15:21:14.453   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-26 15:21:14.453   767   767 D WifiScanningService: SCAN_AVAILABLE : 3
07-26 15:21:14.453   767   767 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:14.453   767  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
07-26 15:21:14.453   767  1167 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:14.453   767  1166 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:14.453   767  1166 I WifiNative-HAL: startHal
,07-26 15:21:14.453   767  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9c7ee99c
07-26 15:21:14.453   767  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x20246a
07-26 15:21:14.453   767  1166 I WifiNative-HAL: Could not start hal
07-26 15:21:14.453   767  1166 E WifiScanningService: could not start HAL
,07-26 15:21:14.453   296  1055 D CommandListener: Setting iface cfg
07-26 15:21:14.453   296  1055 D CommandListener: Trying to bring up p2p0
07-26 15:21:14.453   767  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-26 15:21:14.453   767  1147 D WifiP2pService: P2pEnablingState
07-26 15:21:14.453   767  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
07-26 15:21:14.453   767  1147 D WifiP2pService: P2p socket connection successful
,07-26 15:21:14.453   767  1147 D WifiP2pService: P2pEnabledState
,07-26 15:21:14.453   767  1058 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-26 15:21:14.453   767   767 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-26 15:21:14.453   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:14.453   767  1058 D WifiDisplayController: disconnect
07-26 15:21:14.453   767  1058 D WifiDisplayController: updateConnection
,07-26 15:21:14.463   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:14.463   767  1058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 15:21:14.463   767  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-26 15:21:14.463   767  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-26 15:21:14.463   767  1148 E WifiNative-HAL: invaild command id : 215
,07-26 15:21:14.463   767  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-26 15:21:14.463  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-26 15:21:14.463   767   787 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 15:21:14.463  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-26 15:21:14.463   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:14.463   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-26 15:21:14.463   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.463   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:14.463   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-26 15:21:14.463   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-26 15:21:14.463   767  1147 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:21:14.463   767  1260 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-26 15:21:14.473   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:14.473   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.473   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.473   767  1260 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:14.493  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-26 15:21:14.493   767  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-26 15:21:14.513  7699  7699 E Zygote  : MountEmulatedStorage()
07-26 15:21:14.513  7699  7699 I libpersona: KNOX_SDCARD checking this for 10158
07-26 15:21:14.513  7699  7699 E Zygote  : v2
07-26 15:21:14.513  7699  7699 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:14.513  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-26 15:21:14.513   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:14.513   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:14.523  7699  7699 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:14.523  7699  7699 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:14.523  7699  7699 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:14.523   767  1260 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7699 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-26 15:21:14.523   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:14.523   767  1148 D SecContentProvider2: mCursor = null
07-26 15:21:14.523   767  1147 D WifiP2pService: DeviceAddress: ea:fd:2b
,07-26 15:21:14.533   767  1058 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-26 15:21:14.533   767  1058 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-26 15:21:14.533   767  1058 D WifiDisplayController:  primary type: 10-0050F204-5
07-26 15:21:14.533   767  1058 D WifiDisplayController:  secondary type: null
07-26 15:21:14.533   767  1058 D WifiDisplayController:  wps: 0
07-26 15:21:14.533   767  1058 D WifiDisplayController:  grpcapab: 0
07-26 15:21:14.533   767  1058 D WifiDisplayController:  devcapab: 0
07-26 15:21:14.533   767  1058 D WifiDisplayController:  status: 3
07-26 15:21:14.533   767  1058 D WifiDisplayController:  wfdInfo: null
07-26 15:21:14.533   767  1058 D WifiDisplayController:  groupownerAddress: null
07-26 15:21:14.533   767  1058 D WifiDisplayController:  GOdeviceName: null
07-26 15:21:14.533   767  1058 D WifiDisplayController:  interfaceAddress: 
07-26 15:21:14.533   767  1058 D WifiDisplayController:  SConnectInfo : null
,07-26 15:21:14.543   359   359 I art     : Explicit concurrent mark sweep GC freed 8737(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 17.493ms
,07-26 15:21:14.543  7699  7699 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:21:14.543   767  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
07-26 15:21:14.543   767  1147 D WifiP2pService: InactiveState
,07-26 15:21:14.543   767  1147 D WifiP2pService: InactiveState{ what=143376 }
07-26 15:21:14.543   767  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
07-26 15:21:14.543  7699  7699 D ActivityThread: Added TimaKeyStore provider
07-26 15:21:14.543  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-26 15:21:14.543   767  1147 D WifiP2pService: InactiveState{ what=143376 }
07-26 15:21:14.543   767  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-26 15:21:14.553   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 10.122ms
,07-26 15:21:14.553  7699  7699 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-26 15:21:14.553  7699  7699 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:21:14.553  7699  7699 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-26 15:21:14.553  7699  7699 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-26 15:21:14.563   359   359 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 9.615ms
,07-26 15:21:14.573  7699  7699 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:14.573  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-26 15:21:14.573  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-26 15:21:14.573   767  1523 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
07-26 15:21:14.573   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.573   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.573   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.573   767  1523 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:14.613  7715  7715 E Zygote  : MountEmulatedStorage()
07-26 15:21:14.613  7715  7715 E Zygote  : v2
07-26 15:21:14.613  7715  7715 I libpersona: KNOX_SDCARD checking this for 10186
07-26 15:21:14.613  7715  7715 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:14.623  7715  7715 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-26 15:21:14.623  7715  7715 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:14.623  7715  7715 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:14.623   767  1523 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7715 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-26 15:21:14.633   767  1523 I ActivityManager: Killing 6837:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-26 15:21:14.643  7715  7715 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:14.643  7715  7715 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:14.653  7715  7715 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-26 15:21:14.653  7715  7715 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-26 15:21:14.653  7715  7715 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:14.653  7715  7715 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-26 15:21:14.653  7715  7715 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:21:14.653  7715  7715 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-26 15:21:14.743   767  1320 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:14.773   767  1633 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:14.773   767  3013 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:14.813   767   787 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-26 15:21:14.813   767   787 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.813   767   787 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.813   767   787 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.813   767   787 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:14.823   767  1143 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:14.843   767  1471 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:14.853  7741  7741 E Zygote  : MountEmulatedStorage()
,07-26 15:21:14.853  7741  7741 E Zygote  : v2
07-26 15:21:14.853  7741  7741 I libpersona: KNOX_SDCARD checking this for 10092
07-26 15:21:14.853  7741  7741 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:14.863   767   787 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7741 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-26 15:21:14.873  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:14.873   767  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:14.873  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:14.873  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:14.873  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:14.873  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:14.873  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-26 15:21:14.873  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-26 15:21:14.873   767  1482 I ActivityManager: Killing 6852:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-26 15:21:14.873   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:14.873   767  1446 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
07-26 15:21:14.873   767  1260 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:14.873   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.873   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.873   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:14.873   767  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:14.893  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:14.893  7741  7741 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:14.923  7750  7750 E Zygote  : MountEmulatedStorage()
,07-26 15:21:14.923  7750  7750 E Zygote  : v2
07-26 15:21:14.923  7750  7750 I libpersona: KNOX_SDCARD checking this for 10200
07-26 15:21:14.923  7750  7750 I libpersona: KNOX_SDCARD not a persona
07-26 15:21:14.923   767  1446 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7750 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:14.993  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:14.993  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:14.993  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-26 15:21:14.993   767  3837 I ActivityManager: Killing 6904:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-26 15:21:15.013  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:15.013  7750  7750 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:15.083   767  1471 I art     : Explicit concurrent mark sweep GC freed 39434(2MB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 1.208ms total 87.992ms
,07-26 15:21:15.093  7741  7741 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-26 15:21:15.093  7750  7750 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-26 15:21:15.113  7741  7741 D BadgeProvider: onCreate
,07-26 15:21:15.113  7741  7741 D BadgeProvider: DatabaseHelper
,07-26 15:21:15.123   767  3837 I ActivityManager: Killing 6919:flipboard.app/u0a125 (adj 15): emptyCount ##41
,07-26 15:21:15.123  7741  7749 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-26 15:21:15.143  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:15.143   767  3837 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-26 15:21:15.143  7741  7767 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,07-26 15:21:15.143  1444  1444 D Launcher.Model: reloadBadges entered.
07-26 15:21:15.143  7741  7767 D BadgeProvider: sendNotify, [notify] : null
07-26 15:21:15.143  7741  7767 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-26 15:21:15.143  7741  7767 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-26 15:21:15.143  7741  7767 D BadgeProvider: update, [UpdateCount] : 1
,07-26 15:21:15.153   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.153  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:15.153  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:15.153  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:15.153  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:15.163  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:15.173   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:15.173  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:15.173  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:15.173  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:15.173  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:15.173  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-26 15:21:15.183  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:15.183  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:15.183   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:15.183  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-26 15:21:15.183   767  1633 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.183  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:15.183  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-26 15:21:15.183  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:15.183  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:15.183  7383  7383 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-26 15:21:15.183  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:15.183  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-26 15:21:15.183  7398  7398 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-26 15:21:15.183  7398  7398 D WifiDirectBR: stopServiceTest : false
,07-26 15:21:15.203  7556  7556 I wpa_supplicant: nl80211: Received scan results (27 BSSes)
07-26 15:21:15.203  7556  7556 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-26 15:21:15.203  7556  7556 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-26 15:21:15.203  7556  7556 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,07-26 15:21:15.203  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-26 15:21:15.213   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:15.213   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:15.253  7556  7556 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-26 15:21:15.253  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-26 15:21:15.253  7556  7556 I wpa_supplicant: Associated with F4.99.3E
,07-26 15:21:15.253  7556  7556 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-26 15:21:15.253  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:15.263   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:15.263   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:15.263   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:15.263   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:15.273  7556  7556 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-26 15:21:15.273  7556  7556 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-26 15:21:15.273  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:15.273  7556  7556 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:15.273  7556  7556 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-26 15:21:15.273  7556  7556 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,07-26 15:21:15.273  7556  7556 I wpa_supplicant: Blacklist: Clear (temp) 
07-26 15:21:15.273  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:15.273   767  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-26 15:21:15.283  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:15.283   767  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-26 15:21:15.283   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:15.283   767  1150 D ConnectivityService: Got NetworkAgent Messenger
07-26 15:21:15.283   767  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-26 15:21:15.283   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:15.283   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:15.283   767  1150 D ConnectivityService: NetworkAgent connected
,07-26 15:21:15.283  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:15.283  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:15.283  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:15.283  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:15.283   767  1320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.283  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:15.283   767   788 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:15.283  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:15.283  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:15.283  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-26 15:21:15.293  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:15.293   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:21:15.293   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:15.293  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:15.303   296  1055 D CommandListener: Setting iface cfg
,07-26 15:21:15.303   767  1148 E WifiStateMachine: Start Dhcp Watchdog 2
,07-26 15:21:15.303   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:15.303   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:15.313   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-26 15:21:15.313  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:15.313  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:15.313  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:15.393   767  1148 E native  : do suspend false
,07-26 15:21:15.393   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:15.393   767  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-26 15:21:15.393   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-26 15:21:15.393   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:15.613  7787  7787 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-26 15:21:15.613  7787  7787 I dhcpcd  : version 5.5.6 starting
,07-26 15:21:15.613  7787  7787 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-26 15:21:15.683  7787  7787 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-26 15:21:15.683  7787  7787 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-26 15:21:15.683  7787  7787 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-26 15:21:15.683  7787  7787 I dhcpcd  : bssid match
07-26 15:21:15.683  7787  7787 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-26 15:21:15.693  7787  7787 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,07-26 15:21:15.703  7787  7787 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-26 15:21:15.703   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-26 15:21:16.003   767  1148 E native  : do suspend true
,07-26 15:21:16.013   767  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-26 15:21:16.013   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-26 15:21:16.013   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-26 15:21:16.013   767  1148 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-26 15:21:16.013   767  1148 E WifiStateMachine: VerifyingLinkState enter
,07-26 15:21:16.013  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.013  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.013  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:16.023   767  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-26 15:21:16.023   767  1150 E ConnectivityService: updateNetworkInfo()
,07-26 15:21:16.023   767  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:16.023   767  1150 D ConnectivityService: Adding iface wlan0 to network 503
,07-26 15:21:16.023   767  1161 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-26 15:21:16.023   767  1161 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 15:21:16.023  7221  7279 I WifiManager: packageName : com.test.thalitest
,07-26 15:21:16.023   767  1143 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-26 15:21:16.023   767  1143 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:16.023   767  1143 D SecContentProvider2: mCursor = null
,07-26 15:21:16.023   767  1161 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:16.033   767  1161 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:16.033   767  1161 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:16.033  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.033   767  1143 D WifiService: setWifiEnabled: false pid=7221, uid=10079
,07-26 15:21:16.033   767  1143 D SettingsProvider: name = wifi_on
,07-26 15:21:16.033  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:16.033  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:16.053  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.053  4295  4295 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-26 15:21:16.053   767  1148 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-26 15:21:16.053   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-26 15:21:16.063   767  1150 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,07-26 15:21:16.063   767  1150 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,07-26 15:21:16.063  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.063   767  1150 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,07-26 15:21:16.063   767  1150 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:21:16.063   767  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-26 15:21:16.063  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.063  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:16.063   767  1150 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
,07-26 15:21:16.063   296  1055 V         : QcRouteController
,07-26 15:21:16.063   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-26 15:21:16.063   767   767 I WifiTrafficPoller: mBoosterFLAG : 0
07-26 15:21:16.063   767   767 I WifiTrafficPoller: current booster mode : FullMode
07-26 15:21:16.063   767   767 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-26 15:21:16.073  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:16.073  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-26 15:21:16.073  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.073  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.073   767  1148 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-26 15:21:16.073  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.083   767  1148 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-26 15:21:16.083  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.083  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.083  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.083   296  1055 V         : QcRouteController
,07-26 15:21:16.083  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.083  7556  7556 I wpa_supplicant: reset timer : RESET_TIMER 0
07-26 15:21:16.083  7556  7556 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-26 15:21:16.083  7556  7556 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-26 15:21:16.093   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:21:16.093  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.093  7556  7556 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 15:21:16.103   296  1055 V         : QcRouteController
,07-26 15:21:16.103   767  1148 E native  : do suspend true
,07-26 15:21:16.103   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.103  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.113   767  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-26 15:21:16.113   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-26 15:21:16.123  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:16.123  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-26 15:21:16.123   296  1055 V         : QcRouteController
,07-26 15:21:16.123  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.123  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:16.123   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.123  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-26 15:21:16.123   767  1523 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.123  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:16.123  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:16.123  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:16.123  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:16.133   767  1633 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.133  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.143   296  1055 V         : QcRouteController
,07-26 15:21:16.153  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.153  4295  4295 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-26 15:21:16.163   767  3837 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-26 15:21:16.163   296  1055 V         : QcRouteController
,07-26 15:21:16.163   296  1055 V         : QcRouteController
,07-26 15:21:16.173   767  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.173  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.183   296  1055 V         : QcRouteController
,07-26 15:21:16.183   265   265 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,07-26 15:21:16.203   767  1471 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=767
,07-26 15:21:16.203   296  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:16.203   767  1150 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
07-26 15:21:16.203   767  1150 D ConnectivityService: LTETest block dns file not exists
,07-26 15:21:16.203   767  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-26 15:21:16.203   304   304 E SMD     : DCD ON
,07-26 15:21:16.213   767  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.213   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:16.213   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
,07-26 15:21:16.213   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:16.213   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:16.213   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-26 15:21:16.213   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:16.213   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-26 15:21:16.213   767  1150 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.213   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:16.213   767  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-26 15:21:16.213   767  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-26 15:21:16.213   767  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.213   767  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.213   767  7776 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-26 15:21:16.213   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-26 15:21:16.223   767  1150 D ConnectivityService: currentScore = 0, newScore = 60
,07-26 15:21:16.223   767  1150 D ConnectivityService:    accepting network in place of null
07-26 15:21:16.223   767  1150 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:21:16.223  1428  1428 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.223   767  1150 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,07-26 15:21:16.223   767  1150 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
07-26 15:21:16.223   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-26 15:21:16.223   767  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.233   767  1150 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-26 15:21:16.233   767  1151 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:21:16.233   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:16.233   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:16.233   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:16.233   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.233   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:16.233   767  1145 V NetworkStats: updateIfacesLocked()
07-26 15:21:16.233   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.233   767  1145 V NetworkStats: performPollLocked(flags=0x1)
,07-26 15:21:16.233   767  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-26 15:21:16.233   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.233   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-26 15:21:16.233   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.233   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.233   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.233   767  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-26 15:21:16.233   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.233   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:16.233   767  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,07-26 15:21:16.233   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:16.233   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.233   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:16.233   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:16.233   767  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:16.233   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 15:21:16.233   767  1145 V NetworkStats: performPollLocked() took 5ms
07-26 15:21:16.233   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.243   767  1150 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.243   767  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.243   767  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:16.243   767  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.243   767  1150 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
07-26 15:21:16.243   767  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.243   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:16.243   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.243   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.243   767  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.243   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-26 15:21:16.243  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-26 15:21:16.243   767  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.243  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-26 15:21:16.243  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-26 15:21:16.243  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-26 15:21:16.243  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-26 15:21:16.243   767  1523 I AudioService: getStreamVolume 3 index 0
,07-26 15:21:16.243  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.243  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-26 15:21:16.243   767  1150 E ConnectivityService: updateNetworkInfo()
,07-26 15:21:16.243   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:16.243   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:16.243   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-26 15:21:16.243   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 2
,07-26 15:21:16.243   767  1147 D WifiP2pService: InactiveState{ what=131204 }
07-26 15:21:16.243   767  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-26 15:21:16.253   767  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-26 15:21:16.253   767   767 D WifiScanningService: SCAN_AVAILABLE : 1
07-26 15:21:16.253   767   767 D RttService: SCAN_AVAILABLE : 1
07-26 15:21:16.253   767  1166 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:16.253   767  1167 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-26 15:21:16.253   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.253   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:16.253   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-26 15:21:16.253   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-26 15:21:16.253   767  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-26 15:21:16.253   767   788 D SecContentProvider2: uri = 14 selection = getSealedState
,07-26 15:21:16.253   767   788 D SecContentProvider2: mCursor = null
,07-26 15:21:16.253   767  1058 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-26 15:21:16.253   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:16.253   767  1058 D WifiDisplayController: disconnect
07-26 15:21:16.253   767  1058 D WifiDisplayController: updateConnection
07-26 15:21:16.253   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-26 15:21:16.253   767  1058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 15:21:16.253   767   767 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-26 15:21:16.253   767  1147 D WifiP2pService: P2pDisablingState
07-26 15:21:16.253   767  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
07-26 15:21:16.253   767  1147 D WifiP2pService: p2p socket connection lost
,07-26 15:21:16.253   767  1147 D WifiP2pService: P2pDisabledState
,07-26 15:21:16.253   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.253   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:16.253   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-26 15:21:16.253   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-26 15:21:16.263   767  1473 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-26 15:21:16.263   767  1473 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.263  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:16.263  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.263  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-26 15:21:16.263  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:16.263   767  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.263  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-26 15:21:16.263   767  1633 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.263  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-26 15:21:16.273  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:16.273  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:16.273  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-26 15:21:16.273  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.273  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.273   767  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-26 15:21:16.273   767  1148 E native  : do suspend true
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.283  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.283   767  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
07-26 15:21:16.283   767  1147 D WifiP2pService: DefaultState{ what=143375 }
07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.283   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.283   767   788 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,07-26 15:21:16.283  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.293  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-26 15:21:16.293   767  1446 D SecContentProvider2: uri = 14 selection = getSealedState
07-26 15:21:16.293   767  1446 D SecContentProvider2: mCursor = null
,07-26 15:21:16.293   767  1471 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-26 15:21:16.293   767  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.293  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.293  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.303  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.303  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.303  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.303  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.303  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-26 15:21:16.303   767  1143 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-26 15:21:16.303  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-26 15:21:16.303  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:21:16.303  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:16.303  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:16.303  1197  1197 I PhoneStatusBar: Icon Only
07-26 15:21:16.303  1197  1197 I StatusBar: Icon Only
,07-26 15:21:16.303  1197  1197 D PanelView: There is/are notification(s) 
07-26 15:21:16.303  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:16.313   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.313  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.313  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.313  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:16.313  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:21:16.313  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.313  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:16.313  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
,07-26 15:21:16.313  1197  1197 I PhoneStatusBar: Icon Only
07-26 15:21:16.313  1197  1197 I StatusBar: Icon Only
,07-26 15:21:16.313  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:16.313  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:16.323  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:16.323  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:16.323   767  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-26 15:21:16.323   296  1055 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:21:16.323   767  1150 D ConnectivityService: calling update connectivity
,07-26 15:21:16.323   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.323   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:16.323   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.323   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.323   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.323  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:16.323   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.323   767  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:16.323  7556  7556 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-26 15:21:16.323   767  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-26 15:21:16.323   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:16.323   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:16.323   767  7776 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-26 15:21:16.323   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 15:21:16.323   767  1150 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-26 15:21:16.323   767  1150 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.323  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-26 15:21:16.323   767  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-26 15:21:16.323   767  1150 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=false
07-26 15:21:16.323   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.323   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-26 15:21:16.323   767  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:16.323   767  1523 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.323   767  1145 V NetworkStats: updateIfacesLocked()
07-26 15:21:16.323   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:16.323  1428  1428 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:16.323   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.323   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-26 15:21:16.323   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:16.323   767  1148 D SecContentProvider2: mCursor = null
07-26 15:21:16.323   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.333  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:16.333  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:16.333  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:16.333  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.333   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-26 15:21:16.333  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.333  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-26 15:21:16.333   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:16.333   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:16.333   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-26 15:21:16.333   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-26 15:21:16.333   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.333   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.333   767  1151 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:16.333   767  1320 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.333   767  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.333   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:16.333   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.333   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.333   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.333   767  1145 V NetworkStats: performPollLocked() took 5ms
07-26 15:21:16.333   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.333   767  1446 I AudioService: getStreamVolume 3 index 0
,07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.333   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.333  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.333  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.343  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:16.343   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:16.343  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:16.343  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:16.343  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.343  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-26 15:21:16.343  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:16.343  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:16.343  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:16.343  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:16.343  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:16.343  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:16.343  1197  1197 D HotspotTile: onReceive : 0, 0
,07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-26 15:21:16.343  7383  7383 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-26 15:21:16.343  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:16.343  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-26 15:21:16.343  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.343  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-26 15:21:16.343  7398  7398 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-26 15:21:16.353  7398  7398 D WifiDirectBR: stopServiceTest : false
,07-26 15:21:16.353   767  1446 D SecContentProvider2: uri = 14 selection = getSealedState
07-26 15:21:16.353   767  1446 D SecContentProvider2: mCursor = null
,07-26 15:21:16.353  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-26 15:21:16.353   767  1471 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-26 15:21:16.353   767  1471 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:16.353  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.353  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-26 15:21:16.363  7556  7556 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:16.363  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:16.363  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-26 15:21:16.363   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.363  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:16.363   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.363  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:16.363  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:16.363  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:16.363  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:16.373  1197  1197 D QSpanel : label top:23
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:16.373  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:16.373  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:21:16.383  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:16.383  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:16.383  1197  1197 I PhoneStatusBar: Icon Only
07-26 15:21:16.383  1197  1197 I StatusBar: Icon Only
,07-26 15:21:16.383  7556  7556 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-26 15:21:16.383  1197  1197 D PanelView: There is/are notification(s) 
07-26 15:21:16.383   767  1320 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.383  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:16.383  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.383  7556  7556 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-26 15:21:16.383  7556  7556 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-26 15:21:16.383  7556  7556 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
07-26 15:21:16.383  7556  7556 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-26 15:21:16.393  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.393  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.403  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.403  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.403  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.403  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:16.403  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.413   767  3013 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.413  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:16.413  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:16.413  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:16.413  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:16.413  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.413  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.423  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.423  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.423  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.423  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.433  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.433  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-26 15:21:16.453  7556  7556 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:16.593   767  1151 D Tethering: InitialState.processMessage what=4
,07-26 15:21:16.593   767  1151 E Tethering: No numeric data
07-26 15:21:16.593   767  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-26 15:21:16.593  7556  7556 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-26 15:21:16.593   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:16.593   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.593   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-26 15:21:16.593   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.593  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-26 15:21:16.593  1197  1197 D HotspotTile: updateTetherState():false, false
07-26 15:21:16.593   767  1145 V NetworkStats: performPollLocked() took 3ms
07-26 15:21:16.593   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.593   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:16.593   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:16.693   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-26 15:21:16.693   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-26 15:21:16.693  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:16.693   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:16.693  1917  1917 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:16.693   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:16.703  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:16.703  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:16.703  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:16.703  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:16.703  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:16.703  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-26 15:21:16.703  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.703  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,07-26 15:21:16.703  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:16.703  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:16.703  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:16.703   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.703  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:16.703  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:16.703  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:16.703  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-26 15:21:16.703  1197  1197 D HotspotTile: onReceive : 1, 0
,07-26 15:21:16.723  1197  1197 D QSpanel : label top:23
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:16.723  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:16.733   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.733   767   957 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.733   767   957 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.733   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:16.733   767   767 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-26 15:21:16.733   767   767 D SmartBondingService: SmartBondingReceiver: wifi ap is changed, init speed ratio
07-26 15:21:16.733   767   767 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.733   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:16.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.733   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.733   767  1260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.733   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.743  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:16.743   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:16.743  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:16.743  6632  6632 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-26 15:21:16.743  6632  6632 I PCWCLIENTTRACE_PushUtil: sales region : global
07-26 15:21:16.743  6632  6632 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:21:16.743  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.743  7458  7458 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-26 15:21:16.763  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.763  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-26 15:21:16.833   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.833   767   767 I ApplicationPolicy: updateDataUsageMap
,07-26 15:21:16.833   767  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.833   767  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.833  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:16.833  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:16.833   767   957 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:16.833   767   957 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.843  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-26 15:21:16.843   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:16.843   767   767 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.843   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:16.843   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.843   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:16.843   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:16.843   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-26 15:21:16.843  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-26 15:21:16.843  6990  6990 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-26 15:21:16.853   767   788 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
07-26 15:21:16.853   767   788 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c104b36, r.packageName :com.google.android.gms
,07-26 15:21:16.863  2281  2281 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,07-26 15:21:16.863   767  3837 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:16.863   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@b9eaa37, r.packageName :com.google.android.gms
,07-26 15:21:16.873  2281  2281 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,07-26 15:21:16.873  2281  2281 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-26 15:21:16.873  2281  2281 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:21:16.873  2281  2281 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-26 15:21:16.883  4174  4174 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-26 15:21:16.883  4174  4174 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469539276884
,07-26 15:21:16.883  4174  4174 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:16.883   767  3013 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:16.883   767  1471 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.883  4174  4174 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-26 15:21:16.883  4174  4174 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-26 15:21:16.893   767  3837 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.893   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-26 15:21:16.903   767  1569 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-26 15:21:16.903   767  1569 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f22fd0d, r.packageName :com.samsung.android.app.galaxyfinder
,07-26 15:21:16.903  7010  7010 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-26 15:21:16.923  7557  7557 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-26 15:21:16.933   767  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.933  3467  7889 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-26 15:21:16.933   767  3013 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.933  3467  7889 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-26 15:21:16.933  3467  7889 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-26 15:21:16.933  6722  6722 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
07-26 15:21:16.933  6722  6722 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-26 15:21:16.933  6722  6722 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-26 15:21:16.933  3467  7889 E DBG_POLICYDM: [com.policydm.XDMService(489/isNetworkChanged)] network not changed.... 
,07-26 15:21:16.933  6722  6722 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
07-26 15:21:16.933  6722  6722 I SA      : [OR] == isSIMCardReady false ==
,07-26 15:21:16.933  6722  6722 I SA      : [SCU] == networkStateCheck == false
07-26 15:21:16.933  6722  6722 I SA      : [OR] onReceive END
,07-26 15:21:16.943  7586  7586 I SCloudBackupReceiver: Other Intent
,07-26 15:21:16.943  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-26 15:21:16.943  7602  7602 I KnoxUsageLogPro: premStatus:2
,07-26 15:21:16.943  7602  7602 I KnoxUsageLogPro: isEulaShown : false
07-26 15:21:16.943  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 15:21:16.973  7699  7699 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:16.973  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
07-26 15:21:16.973  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-26 15:21:16.993   767  1320 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:16.993   767  1260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.993  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:16.993  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:16.993  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:16.993  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:16.993   767  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:16.993   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.013   767  3050 D SSRM:n  : SIOP:: AP = 390, PST = 361, CUR = 450
,07-26 15:21:17.013  6632  6632 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-26 15:21:17.013  6632  6632 I PCWCLIENTTRACE_PushUtil: sales region : global
07-26 15:21:17.013  6632  6632 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:21:17.013  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:17.013  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-26 15:21:17.013  7458  7458 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-26 15:21:17.023  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.023  7511  7511 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-26 15:21:17.083  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-26 15:21:17.093  6990  6990 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-26 15:21:17.093  6990  6990 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-26 15:21:17.103   767  3013 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:17.103   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@31a9b2d3, r.packageName :com.google.android.gms
,07-26 15:21:17.103  2281  2281 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false
,07-26 15:21:17.113   767  1523 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:17.113   767  1523 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bef9e10, r.packageName :com.google.android.gms
,07-26 15:21:17.113  2281  2281 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy}
,07-26 15:21:17.113  2281  2281 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.kids.chimera.SystemEventReceiverProxy} to Chimera receiver impl com.google.android.gms.kids.account.SystemEventReceiver
07-26 15:21:17.113  2281  2281 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:21:17.113  2281  2281 I Kids    : [GCoreUtils] Current gmscore version, 7571438 is smaller than the required version 8400000
,07-26 15:21:17.123  4174  4174 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-26 15:21:17.123  4174  4174 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469539277128
,07-26 15:21:17.123   767  1115 V AlarmManager: waitForAlarm result :4
,07-26 15:21:17.123  4174  4174 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
07-26 15:21:17.123   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.123   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.123  4174  4174 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
07-26 15:21:17.123  4174  4174 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-26 15:21:17.133   767  1633 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.143  7010  7010 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-26 15:21:17.153  7557  7557 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-26 15:21:17.153   767  1260 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.153  3467  7891 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-26 15:21:17.153   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.153  3467  7891 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-26 15:21:17.153  3467  7891 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-26 15:21:17.153  3467  7891 E DBG_POLICYDM: [com.policydm.XDMService(489/isNetworkChanged)] network not changed.... 
,07-26 15:21:17.153   767  1473 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
07-26 15:21:17.153   767  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d52a92f, r.packageName :com.sec.spp.push
,07-26 15:21:17.163  6722  6722 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-26 15:21:17.163  6722  6722 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
07-26 15:21:17.163  6722  6722 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-26 15:21:17.163  6722  6722 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,07-26 15:21:17.163  6722  6722 I SA      : [OR] == isSIMCardReady false ==
07-26 15:21:17.163  6722  6722 I SA      : [SCU] == networkStateCheck == false
07-26 15:21:17.163  6722  6722 I SA      : [OR] onReceive END
,07-26 15:21:17.163  7557  7895 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-26 15:21:17.173  7586  7586 I SCloudBackupReceiver: Other Intent
,07-26 15:21:17.173  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-26 15:21:17.173  7602  7602 I KnoxUsageLogPro: premStatus:2
07-26 15:21:17.173  7602  7602 I KnoxUsageLogPro: isEulaShown : false
07-26 15:21:17.173  7602  7602 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-26 15:21:17.203  7699  7699 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:17.203  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-26 15:21:17.203  7699  7699 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-26 15:21:17.223   767  1143 D RCPManagerService: exchangeData() failure , invalid userId
,07-26 15:21:17.223   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.223  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:17.223  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:17.223  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:17.223  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:17.233   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.233   767  1523 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:17.233   767  1150 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-26 15:21:17.253   767  1473 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-26 15:21:17.253   767  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@1247c0c5, r.packageName :com.google.android.music
,07-26 15:21:17.273   767   787 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:17.273   767  1523 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:17.273   767   788 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:17.283   767  3783 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-26 15:21:17.283   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@294f6c3, r.packageName :com.google.android.music
,07-26 15:21:17.283  7458  7902 I MusicLeanback: Conditions not met for autocaching.
07-26 15:21:17.283  7458  7902 I MusicLeanback: Stop autocaching.
,07-26 15:21:17.303   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:17.303   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:17.303   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:17.303   767  3013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:17.343  7905  7905 E Zygote  : MountEmulatedStorage()
07-26 15:21:17.343  7905  7905 E Zygote  : v2
,07-26 15:21:17.343  7905  7905 I libpersona: KNOX_SDCARD checking this for 10015
07-26 15:21:17.343  7905  7905 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:17.353   767  3013 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=7905 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-26 15:21:17.363  7905  7905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:17.363  7905  7905 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-26 15:21:17.363  7905  7905 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:17.363   767  1426 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-26 15:21:17.383  7905  7905 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:17.383  7905  7905 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:17.393  7905  7905 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-26 15:21:17.403  7905  7905 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-26 15:21:17.403  7905  7905 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-26 15:21:17.423  7905  7905 I MultiDex: VM with version 2.1.0 has multidex support
,07-26 15:21:17.423  7905  7905 I MultiDex: install
07-26 15:21:17.423  7905  7905 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:21:17.443  7905  7905 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-26 15:21:17.443   767  3783 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:17.443   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ef66dca, r.packageName :com.google.android.gms
07-26 15:21:17.443  1723  5589 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-26 15:21:17.453  1723  1723 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-26 15:21:17.453  2281  2281 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
07-26 15:21:17.453  7905  7905 D WearableService: callingUid 10015, callindPid: 7905
,07-26 15:21:17.453   767  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:21:17.453   767  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@189c7b3b, r.packageName :com.google.android.gms
,07-26 15:21:17.483   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@23f59c96, r.packageName :com.google.android.gms
,07-26 15:21:17.493  1917  5583 E MDM     : [194] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,07-26 15:21:17.503   767  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:17.503   767  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@16b78c04, r.packageName :com.google.android.gms
07-26 15:21:17.503  2281  7929 D LocationInitializer: Restart initialization of location
,07-26 15:21:17.513   767  1471 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:17.513   767  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@27e805ed, r.packageName :com.google.android.gms
,07-26 15:21:17.513  7458  7919 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-26 15:21:17.513  7458  7458 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-26 15:21:18.953   767  1471 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-26 15:21:18.963  7633  7655 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-26 15:21:19.043  7221  7279 D BluetoothAdapter: enable()
,07-26 15:21:19.043   767  3783 W ActivityManager: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-26 15:21:19.043   767  3783 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 15:21:19.043   767  3783 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:19.043   767  3783 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-26 15:21:19.043   767  3783 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-26 15:21:19.043   767  3783 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-26 15:21:19.043   767  3783 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 15:21:19.043   767  3783 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
07-26 15:21:19.043   767  3783 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-26 15:21:19.043   767  3783 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:19.043   767  3783 D SettingsProvider: name = bluetooth_on
,07-26 15:21:19.053   767  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:19.053   767  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:19.053   767  1057 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-26 15:21:19.053  2987  3042 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-26 15:21:19.053  2987  3042 D BluetoothAdapterProperties: Setting state to 11
07-26 15:21:19.053  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-26 15:21:19.053  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-26 15:21:19.063  2987  3042 D BluetoothAdapterService: updateAdapterState state is 11
07-26 15:21:19.063  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:19.063  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-26 15:21:19.063  2987  3042 D BtConfig.SecureMode: isSecureModeOn:false
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-26 15:21:19.063  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-26 15:21:19.063  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:19.073   767  1633 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:19.073   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aeddd7a, r.packageName :com.android.bluetooth
,07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,07-26 15:21:19.073  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 15:21:19.073  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-26 15:21:19.083   767  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:19.083   767  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@31db5188, r.packageName :com.android.bluetooth
,07-26 15:21:19.083  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,07-26 15:21:19.083  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-26 15:21:19.083  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-26 15:21:19.083   767  3837 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:19.083   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@1dec5746, r.packageName :com.android.bluetooth
,07-26 15:21:19.093  2987  2987 D HeadsetService: Received start request. Starting profile...
,07-26 15:21:19.093  2987  2987 D HeadsetStateMachine: make
,07-26 15:21:19.093  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,07-26 15:21:19.093  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-26 15:21:19.093  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-26 15:21:19.093   767   787 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:19.093   767   787 D ActivityManager: caller:android.app.ApplicationThreadProxy@c97fe34, r.packageName :com.android.bluetooth
,07-26 15:21:19.093  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,07-26 15:21:19.093  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-26 15:21:19.093  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-26 15:21:19.093   767  1426 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:19.093   767  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@3206a1d2, r.packageName :com.android.bluetooth
,07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-26 15:21:19.103   767  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:19.103   767  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@20d0c9a0, r.packageName :com.android.bluetooth
,07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-26 15:21:19.103   767  1523 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:19.103   767  1523 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a09091e, r.packageName :com.android.bluetooth
,07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-26 15:21:19.103  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 15:21:19.103  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-26 15:21:19.103  2987  3042 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-26 15:21:19.113   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.113   767   767 I InputMethodManagerService: [BT Setting State] State =11
,07-26 15:21:19.113  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-26 15:21:19.113  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:19.113  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:19.123  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.123  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:19.123   767  1320 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:19.123   767  1523 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-26 15:21:19.123  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-26 15:21:19.123  2987  2987 E HeadsetStateMachine: # of Max HF connection is 2
,07-26 15:21:19.133   767  1143 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-26 15:21:19.133   767  1473 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-26 15:21:19.133  2987  2987 I bluedroid: get_profile_interface handsfree
,07-26 15:21:19.133  2987  2987 E DualScoManager: Dual Sco Manager already instantiated
,07-26 15:21:19.133  2987  2987 I DualScoManager: Set HeadsetServiceHelper
07-26 15:21:19.133  2987  2987 D BluetoothAtMessage: createCMTIContentObservers
07-26 15:21:19.133   767   788 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-26 15:21:19.133   767   788 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-26 15:21:19.133   767   788 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-26 15:21:19.133   767   788 D SettingsProvider: selectionArgs: false
07-26 15:21:19.133   767   788 D SettingsProvider: selectionArgs: 1002
07-26 15:21:19.133   767   788 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-26 15:21:19.133   767   788 D SettingsProvider: ret = -1
,07-26 15:21:19.133  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:19.143  2987  2987 D A2dpService: Received start request. Starting profile...
07-26 15:21:19.143  2987  2987 V Avrcp   : make
07-26 15:21:19.143  2987  2987 V Avrcp   : Avrcp
07-26 15:21:19.143  2987  2987 I bluedroid: get_profile_interface avrcp
,07-26 15:21:19.143  2987  2987 V Avrcp   : start
,07-26 15:21:19.143  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-26 15:21:19.143  2987  7943 D HeadsetStateMachine: Enter Disconnected: -2
,07-26 15:21:19.143  2987  7943 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-26 15:21:19.153  2987  2987 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:21:19.153  2987  2987 V Avrcp   : ++registerMediaPlayers++
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
,07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:19.153  2987  2987 I Avrcp   : No of Audio players :: 2
07-26 15:21:19.153  2987  2987 I Avrcp   : App Package name is com.google.android.music
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:19.153  1197  1197 D QSpanel : label top:23
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
,07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:19.153  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
07-26 15:21:19.153  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.153  1694  1694 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-26 15:21:19.153  2987  2987 I Avrcp   : App pkg name is Google Play Music
07-26 15:21:19.153  2987  2987 I Avrcp   : Name::Google Play Music
07-26 15:21:19.153  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-26 15:21:19.153  2987  2987 I Avrcp   : App Package name is com.sec.android.app.music
07-26 15:21:19.153  2987  7943 D HeadsetStateMachine: map size, before remove : 0
07-26 15:21:19.153  2987  7943 D HeadsetStateMachine: map size, after remove: 0
07-26 15:21:19.153  2987  7943 D HeadsetStateMachine: mNextConnectingDevice : null
07-26 15:21:19.153  2987  2987 I Avrcp   : App pkg name is Music
07-26 15:21:19.153  2987  2987 I Avrcp   : Name::Music
07-26 15:21:19.153  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-26 15:21:19.153  2987  2987 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
07-26 15:21:19.153  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.153  2987  2987 I Avrcp   : No of Video players :: 1
07-26 15:21:19.153  2987  2987 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
07-26 15:21:19.163  2987  2987 I Avrcp   : Video App pkg name is Video Player
07-26 15:21:19.163  2987  2987 I Avrcp   : Name::Video Player
07-26 15:21:19.163  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-26 15:21:19.163  2987  2987 I Avrcp   : Add tempPlayer
07-26 15:21:19.163  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-26 15:21:19.163  2987  2987 I Avrcp   : Total no of players: 4
07-26 15:21:19.163  2987  2987 V Avrcp   : swapping the samsung player with 1st player
07-26 15:21:19.163  2987  2987 I Avrcp   :  Updating now playing list upon AVRCP Start
07-26 15:21:19.163  2987  7944 V Avrcp   : handleMessage, msg=207
,07-26 15:21:19.163  2987  7944 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
07-26 15:21:19.163  2987  2987 D A2dpStateMachine: make
,07-26 15:21:19.163  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:21:19.163  2987  2987 I bluedroid: get_profile_interface a2dp
07-26 15:21:19.163  2987  7955 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-26 15:21:19.163  2987  2987 E bt-btif : warning : media task started media_task_refcnt 1 
07-26 15:21:19.163  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:19.163  2987  7954 D A2dpStateMachine: Enter Disconnected: -2
07-26 15:21:19.163  2987  2987 D HidService: Received start request. Starting profile...
07-26 15:21:19.163  2987  2987 I bluedroid: get_profile_interface hidhost
07-26 15:21:19.163  2987  2987 D HidService: setHidService(): set to: null
07-26 15:21:19.163  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:19.163  2987  2987 D HealthService: Received start request. Starting profile...
,07-26 15:21:19.163  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:19.163  2987  2987 I bluedroid: get_profile_interface health
07-26 15:21:19.163  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:19.163  2987  2987 D PanService: Received start request. Starting profile...
07-26 15:21:19.163  2987  2987 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:19.163  2987  2987 I bluedroid: get_profile_interface pan
07-26 15:21:19.163  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:19.173  2987  2987 D BluetoothMapService: Received start request. Starting profile...
,07-26 15:21:19.173  2987  7944 D BluetoothMediaBrowser: no now playing list
07-26 15:21:19.173  2987  7944 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-26 15:21:19.173  2987  7944 D Avrcp   :  checkNowPlayingList start
,07-26 15:21:19.183  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:19.183  2987  2987 D SapService: Received start request. Starting profile...
07-26 15:21:19.183  2987  2987 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-26 15:21:19.183  2987  2987 I bluedroid: get_profile_interface sap
07-26 15:21:19.183  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:19.183  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-26 15:21:19.183  2987  2987 D HeadsetStateMachine: Try to query the phonestate on bind
07-26 15:21:19.183  1404  1431 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:21:19.183  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-26 15:21:19.183  2987  2987 D HeadsetStateMachine: Proxy object connected
07-26 15:21:19.183  2987  2987 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-26 15:21:19.183  2987  2987 D HeadsetPhoneState: sendDeviceDataStateChanged
07-26 15:21:19.183  2987  2987 D HeadsetPhoneState: Signal level : previous=0 curr=1
07-26 15:21:19.183  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 15:21:19.183  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-26 15:21:19.183  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-26 15:21:19.183  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-26 15:21:19.183  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
07-26 15:21:19.183  2987  7943 D HeadsetStateMachine: Disconnected process message: 11
07-26 15:21:19.183  2987  7943 D HeadsetStateMachine: Disconnected process message: 18
07-26 15:21:19.183  2987  7943 D HeadsetStateMachine: Disconnected process message: 10
07-26 15:21:19.183  2987  7943 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 15:21:19.183  2987  7943 D HeadsetStateMachine: Disconnected process message: 11
,07-26 15:21:19.193  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-26 15:21:19.193  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-26 15:21:19.193  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-26 15:21:19.193  2987  3042 I bluedroid: enable
,07-26 15:21:19.193  2987  3045 E bt-btif : Calling BTA_HhEnable
,07-26 15:21:19.203  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:19.203  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:19.203  2987  3045 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-26 15:21:19.203  2987  3045 E BluetoothServiceJni: populateRssiValuesNative
07-26 15:21:19.203  2987  3045 I bluedroid: getModelRssiValues
07-26 15:21:19.203  2987  3045 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-26 15:21:19.203  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Name is: Galaxy Note3
07-26 15:21:19.203   767   767 D SettingsProvider: name = bluetooth_name
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-26 15:21:19.203  2987  3045 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-26 15:21:19.203  2987  3045 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,07-26 15:21:19.203  2987  3045 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-26 15:21:19.203  2987  3045 E bt-btif : JVenable fails
07-26 15:21:19.203  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:19.203  2987  3045 D bte_conf: Device ID record 1 : primary
07-26 15:21:19.203  2987  3045 D bte_conf:   vendorId            = 0075
07-26 15:21:19.203  2987  3045 D bte_conf:   vendorIdSource      = 0001
07-26 15:21:19.203  2987  3045 D bte_conf:   product             = 0100
07-26 15:21:19.203  2987  3045 D bte_conf:   version             = 0200
07-26 15:21:19.203  2987  3045 D bte_conf:   clientExecutableURL = 
07-26 15:21:19.203  2987  3045 D bte_conf:   serviceDescription  = 
07-26 15:21:19.203  2987  3045 D bte_conf:   documentationURL    = 
07-26 15:21:19.203  2987  3045 D bte_conf: bte_load_did_conf no section named DID2.
07-26 15:21:19.203  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:19.203  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-26 15:21:19.203  2987  3042 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:21:19.203  2987  3042 D BluetoothAdapterProperties: State =  11
,07-26 15:21:19.203  2987  3048 D bt_upio : proc btwrite assertion
07-26 15:21:19.203  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:19.203  2987  3045 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-26 15:21:19.203   767  3013 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-26 15:21:19.203  2987  3042 D BluetoothAdapterProperties: Setting state to 12
07-26 15:21:19.203  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:19.203  2987  3045 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-26 15:21:19.203   767  1473 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-26 15:21:19.203   767  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-26 15:21:19.203   767  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-26 15:21:19.203   767  1473 D SettingsProvider: selectionArgs: false
07-26 15:21:19.203   767  1473 D SettingsProvider: selectionArgs: 1002
07-26 15:21:19.203   767  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-26 15:21:19.203   767  1473 D SettingsProvider: ret = -1
,07-26 15:21:19.213  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:19.213  2987  3042 D BluetoothAdapterService: updateAdapterState state is 12
07-26 15:21:19.213   304   304 E SMD     : DCD ON
07-26 15:21:19.213   767  1633 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:19.213   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b97f5ce, r.packageName :com.android.bluetooth
,07-26 15:21:19.213  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:19.213  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-26 15:21:19.213  2987  3042 D BluetoothAdapterService: starting service from this receiver
07-26 15:21:19.213  4295  4306 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:19.213   767  1260 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:19.213   767  1260 D ActivityManager: caller:android.app.ApplicationThreadProxy@1769d3fc, r.packageName :com.android.bluetooth
,07-26 15:21:19.213  2987  3042 I BluetoothAdapterState: Entering On State from state = 11
07-26 15:21:19.213   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-26 15:21:19.213  2987  2987 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:19.213   767  1057 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:19.213  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.213  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.213  1428  1615 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:19.213  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:19.213   767  1057 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:19.213   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-26 15:21:19.213  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:19.223  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:19.223  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.223   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:19.223  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:19.223  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.223  2987  2987 I BluetoothPbapService: Handler(): got msg=1
07-26 15:21:19.223  1404  7327 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:19.223   767  3013 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
07-26 15:21:19.223  4295  4304 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:19.223  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.223   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-26 15:21:19.223  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.223  2987  7965 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-26 15:21:19.223   767   767 D BluetoothA2dp: Proxy object connected
07-26 15:21:19.223  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.223  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.223   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:19.233  4295  4306 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  4295  4304 D BluetoothPan: Binding service...
07-26 15:21:19.233  2987  7965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.233  2987  7965 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-26 15:21:19.233  2987  7965 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:19.233  2987  7965 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:19.233  2987  7965 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e1c79cf
07-26 15:21:19.233  2987  7965 D BluetoothSocket: channel: 19
07-26 15:21:19.233  2987  7965 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
07-26 15:21:19.233   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  4295  4295 D BluetoothPbap: Proxy object connected
07-26 15:21:19.233  4295  4295 D PbapServerProfile: Bluetooth service connected
07-26 15:21:19.233  4295  4295 D BluetoothA2dp: Proxy object connected
07-26 15:21:19.233  4295  4295 D A2dpProfile: Bluetooth service connected
,07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-26 15:21:19.233   767  1057 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:19.233  2987  3381 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  4295  4295 D HeadsetProfile: Bluetooth service connected
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.233   767  1057 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  2987  2987 D BluetoothA2dp: Proxy object connected
07-26 15:21:19.233  2987  2987 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-26 15:21:19.233  4295  4304 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  4295  4295 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:19.233  4295  4295 D PanProfile: Bluetooth service connected
07-26 15:21:19.233   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
07-26 15:21:19.233  4295  4306 D Bluetoothsap: onBluetoothStateChange: up=true
07-26 15:21:19.233  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.233  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.233  4295  4306 D Bluetoothsap: Binding service...
,07-26 15:21:19.243  4295  4295 D BluetoothMap: Proxy object connected
07-26 15:21:19.243  4295  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
07-26 15:21:19.243  4295  4295 D MapProfile: Bluetooth service connected
07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-26 15:21:19.243  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.243  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.243  4295  4295 D Bluetoothsap: BluetoothSAP Proxy object connected
07-26 15:21:19.243  4295  4306 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-26 15:21:19.243   767  1057 D BluetoothPan: Binding service...
,07-26 15:21:19.243  4295  4295 D SapProfile: Bluetooth service connected
07-26 15:21:19.243  4295  4295 D Bluetoothsap: getConnectedDevices()
07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-26 15:21:19.243  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.243   767   767 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:19.243  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:19.243  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.243  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.243  1404  1431 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:19.243  3182  3193 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-26 15:21:19.243  4295  4304 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:21:19.243  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.243  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.243  3182  3182 D BluetoothA2dp: Proxy object connected
,07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
07-26 15:21:19.243  2987  3048 D bt_vendor: op for 7
,07-26 15:21:19.243  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.243  4295  4295 D BluetoothInputDevice: Proxy object connected
07-26 15:21:19.243  4295  4295 D HidProfile: Bluetooth service connected
,07-26 15:21:19.243   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-26 15:21:19.253  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.253  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.253  1404  7327 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:19.253  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.253  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.253   767  1057 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-26 15:21:19.253  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.253  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.253  3182  3191 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:19.253  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.253  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.253   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-26 15:21:19.253  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-26 15:21:19.253  1694  1694 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
07-26 15:21:19.253  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@f44d835, true
07-26 15:21:19.253   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.253   767   767 I InputMethodManagerService: [BT Setting State] State =12
07-26 15:21:19.253   767   767 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-26 15:21:19.253  1404  1404 D BluetoothHeadset: registerMessageListener
07-26 15:21:19.253  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-26 15:21:19.253  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.263  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:19.263  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:19.263  2987  7968 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-26 15:21:19.263  2987  3381 D HeadsetService: registerMessageListener
07-26 15:21:19.263  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:19.263  2987  3381 D HeadsetService: registerMessageListener
07-26 15:21:19.263  2987  7943 D HeadsetStateMachine: Disconnected process message: 70
07-26 15:21:19.263  2987  7943 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@4571f5c
07-26 15:21:19.263  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-26 15:21:19.263  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-26 15:21:19.263  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:19.263  2987  7968 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:21:19.263  4295  4295 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-26 15:21:19.263  4295  4295 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-26 15:21:19.263  2987  7943 D HeadsetStateMachine: Disconnected process message: 9
07-26 15:21:19.263  2987  7943 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-26 15:21:19.263  2987  7968 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-26 15:21:19.263  2987  7968 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:19.263  2987  7968 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:19.263  2987  7968 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ce9265
07-26 15:21:19.263  2987  7968 D BluetoothSocket: channel: 5
,07-26 15:21:19.263  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.263  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:19.263  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
07-26 15:21:19.263  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:19.263   314   686 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-26 15:21:19.263   314   686 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-26 15:21:19.263   314   686 V voice   : voice_set_parameters: exit with code(-2)
07-26 15:21:19.263   314   686 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-26 15:21:19.263   314   686 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-26 15:21:19.263   314   686 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-26 15:21:19.263   314   686 V audio_hw_primary: adev_set_parameters: exit
07-26 15:21:19.263  2987  7943 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-26 15:21:19.263   767  3013 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-26 15:21:19.263   767   788 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-26 15:21:19.263  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-26 15:21:19.273  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:19.273   767  1426 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-26 15:21:19.273   767  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@33407fea, r.packageName :com.android.settings
,07-26 15:21:19.273  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:19.273  4295  4295 D DockEventReceiver: finishStartingService: stopping service
07-26 15:21:19.273  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:19.283  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:19.283  2987  2987 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 15:21:19.283   767   788 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:19.283   767   788 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c575178, r.packageName :com.android.bluetooth
,07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D QSpanel : label top:23
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:19.293  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:19.293   767  1446 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-26 15:21:19.303  2987  7974 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:19.303  2987  3048 D bt_vendor: op for 7
07-26 15:21:19.303  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:19.303  2987  7974 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[83]}
07-26 15:21:19.303  2987  7974 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:19.303  2987  7974 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:19.303  2987  7974 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@41aefe1
07-26 15:21:19.303  2987  7974 D BluetoothSocket: channel: 12
07-26 15:21:19.303  2987  7974 I BtOppRfcommListener: Accept thread started.
,07-26 15:21:19.693   265  1570 I SurfaceFlinger: id=14 Removed Uoast (8/9)
,07-26 15:21:19.693   265   347 I SurfaceFlinger: id=14 Removed Uoast (-2/9)
,07-26 15:21:19.703   767  1446 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=767 (0x0)
,07-26 15:21:19.703   767  1446 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=767, ws=WorkSource{10067}) (elapsedTime=3499)
,07-26 15:21:19.933   767  1426 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-26 15:21:19.933   767  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@11dac08d, r.packageName :com.sec.spp.push
,07-26 15:21:20.803  2987  3048 D bt_vendor: op for 7,
,07-26 15:21:20.993   767  3083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-26 15:21:21.203  2987  3154 D bt_upio : ..proc_btwrite_timeout..
,07-26 15:21:21.223   767  1115 V AlarmManager: waitForAlarm result :4
,07-26 15:21:21.254   767  1115 V AlarmManager: waitForAlarm result :4
,07-26 15:21:21.254   767  1115 D ActivityManager: caller:null, r.packageName :com.google.android.googlequicksearchbox
,07-26 15:21:21.293   767   788 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 15:21:21.293   767   788 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-26 15:21:21.293   767   788 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-26 15:21:21.293   767   788 D BatteryService: stay LED for fully charged
,07-26 15:21:21.293   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 15:21:21.293  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 15:21:21.293  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
07-26 15:21:21.293   767   767 I MotionRecognitionService: Plugged
07-26 15:21:21.293   767   767 I MotionRecognitionService: setPowerConnected  = true
,07-26 15:21:21.293  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-26 15:21:21.293  2987  7943 D HeadsetStateMachine: Disconnected process message: 10
,07-26 15:21:21.303  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-26 15:21:21.303  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:21.303  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:21.303  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:21.303  1626  7990 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,07-26 15:21:21.753  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,07-26 15:21:21.773  6632  8009 E PCWCLIENTTRACE_DeviceUtil: Network access is not available: Attempt to invoke virtual method 'boolean android.net.NetworkInfo.isAvailable()' on a null object reference
,07-26 15:21:21.773  6632  8009 W PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - netwrok is not available. action ignored
,07-26 15:21:22.133  7221  7279 D BluetoothAdapter: disable()
,07-26 15:21:22.133   767  3783 D SettingsProvider: name = bluetooth_on
,07-26 15:21:22.153  2987  3042 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-26 15:21:22.153  2987  3042 D BluetoothAdapterProperties: Setting state to 13
07-26 15:21:22.153  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:21:22.153  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:22.153  2987  3042 D BluetoothAdapterService: updateAdapterState state is 13
,07-26 15:21:22.153   767  3837 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.153   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c9f208e, r.packageName :com.android.bluetooth
,07-26 15:21:22.153  2987  2987 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-26 15:21:22.153  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:22.153  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-26 15:21:22.153  2987  3042 D BluetoothAdapterService: terminating service from this receiver
,07-26 15:21:22.163  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1d94e106, channel: 19, state: LISTENING
,07-26 15:21:22.163  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1d94e106, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e1c79cf, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@597d3c7mSocket: android.net.LocalSocket@3715fdf4 impl:android.net.LocalSocketImpl@675a91d fd:FileDescriptor[78]
07-26 15:21:22.163  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3715fdf4 impl:android.net.LocalSocketImpl@675a91d fd:FileDescriptor[78]
,07-26 15:21:22.163  2987  3042 D BluetoothAdapterProperties: onBluetoothDisable()
,07-26 15:21:22.163   767  1471 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-26 15:21:22.163  2987  3042 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-26 15:21:22.173  2987  3045 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:21:22.173  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-26 15:21:22.173  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.173  2987  3048 D bt_upio : proc btwrite assertion
,07-26 15:21:22.173  2987  3042 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-26 15:21:22.173  2987  3042 E bt-btif : cmd socket is not created
,07-26 15:21:22.173  2987  7974 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:21:22.183  2987  3042 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-26 15:21:22.183  2987  3048 D bt_vendor: op for 7
07-26 15:21:22.183  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.183  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.183  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:22.183  2987  3046 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,07-26 15:21:22.183  2987  3048 D bt_vendor: op for 7
07-26 15:21:22.183  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.183  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.183  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.183  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:22.193  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:22.193  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:22.193  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:21:22.193  2987  3046 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-26 15:21:22.193  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:22.193  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:22.193  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:22.193  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.193  2987  3048 D bt_vendor: op for 7
07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.193  2987  3048 D bt_vendor: op for 7
,07-26 15:21:22.193  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:22.203   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:22.203  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-26 15:21:22.203   767   767 I InputMethodManagerService: [BT Setting State] State =13
,07-26 15:21:22.203  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-26 15:21:22.203  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:22.203  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
,07-26 15:21:22.213  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@33e563, channel: 5, state: LISTENING
,07-26 15:21:22.213   304   304 E SMD     : DCD ON
07-26 15:21:22.213  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@33e563, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1ce9265, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@338f0560mSocket: android.net.LocalSocket@fc8ba19 impl:android.net.LocalSocketImpl@29810ade fd:FileDescriptor[80]
07-26 15:21:22.213  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fc8ba19 impl:android.net.LocalSocketImpl@29810ade fd:FileDescriptor[80]
,07-26 15:21:22.213  2987  2987 I BtOppRfcommListener: stopping Accept Thread
,07-26 15:21:22.213  2987  2987 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2f574bf, channel: 12, state: LISTENING
07-26 15:21:22.213  2987  2987 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2f574bf, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@41aefe1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16cf178cmSocket: android.net.LocalSocket@11a1ded5 impl:android.net.LocalSocketImpl@18ef6ea fd:FileDescriptor[83]
07-26 15:21:22.213  2987  2987 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@11a1ded5 impl:android.net.LocalSocketImpl@18ef6ea fd:FileDescriptor[83]
,07-26 15:21:22.213  2987  7974 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-26 15:21:22.213  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
,07-26 15:21:22.213  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:22.213   767  3837 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:22.213   767   787 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-26 15:21:22.213  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-26 15:21:22.213  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:22.213  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:22.223  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:21:22.223  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:22.223  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:22.223  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:22.223  1694  1694 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-26 15:21:22.223  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:22.233  4295  4295 D BluetoothPbap: Proxy object disconnected
,07-26 15:21:22.233  4295  4295 D PbapServerProfile: Bluetooth service disconnected
,07-26 15:21:22.233  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-26 15:21:22.243  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
,07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:22.243  1197  1197 D QSpanel : label top:23
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
,07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:22.243  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:22.243   767   788 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-26 15:21:22.243   767   788 D ActivityManager: caller:android.app.ApplicationThreadProxy@278050af, r.packageName :com.android.settings
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:22.243  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:22.243  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:22.253  4295  4295 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:22.253  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:22.383  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,07-26 15:21:22.383  2987  3042 D BtConfig.SecureMode: isSecureModeOn:false
07-26 15:21:22.383  2987  3042 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
,07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
07-26 15:21:22.383  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:22.383   767   788 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.383   767   788 D ActivityManager: caller:android.app.ApplicationThreadProxy@24c47445, r.packageName :com.android.bluetooth
,07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
07-26 15:21:22.383  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-26 15:21:22.383   767  1633 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.383   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@3570b79a, r.packageName :com.android.bluetooth
,07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
07-26 15:21:22.383  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:22.383  2987  2987 D HeadsetService: Received stop request...Stopping profile...
07-26 15:21:22.383  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-26 15:21:22.383  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.393   767  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:22.393  2987  2987 D A2dpService: Received stop request...Stopping profile...
07-26 15:21:22.393   767  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@340b48cb, r.packageName :com.android.bluetooth
07-26 15:21:22.393  2987  2987 V Avrcp   : doQuit
07-26 15:21:22.393  2987  7954 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:21:22.393  2987  2987 D Avrcp   : Unregistering previous receiver
07-26 15:21:22.393   767   767 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-26 15:21:22.393  4295  4295 D HeadsetProfile: Bluetooth service disconnected
,07-26 15:21:22.393  7360  7360 W BluetoothHeadset: Proxy not attached to service
,07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
07-26 15:21:22.393  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-26 15:21:22.393  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:22.393   767  3013 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.393   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@30fe08a8, r.packageName :com.android.bluetooth
,07-26 15:21:22.393   767   767 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:22.393   767   767 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
07-26 15:21:22.393  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-26 15:21:22.393   767  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.393   767  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@1cbd0fc1, r.packageName :com.android.bluetooth
07-26 15:21:22.393  4295  4295 D BluetoothA2dp: Proxy object disconnected
07-26 15:21:22.393  4295  4295 D A2dpProfile: Bluetooth service disconnected
07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.393  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:22.393   767  1569 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:22.393   767  1569 D ActivityManager: caller:android.app.ApplicationThreadProxy@792b366, r.packageName :com.android.bluetooth
07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
07-26 15:21:22.393  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:22.393  2987  3042 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-26 15:21:22.393   767  1523 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:22.403   767  1523 D ActivityManager: caller:android.app.ApplicationThreadProxy@1303a6a7, r.packageName :com.android.bluetooth
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:22.403  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:22.403  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-26 15:21:22.403  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
07-26 15:21:22.403  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-26 15:21:22.403  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-26 15:21:22.403  2987  3042 D BluetoothAdapterState: Stopping profile services that were post enabled
07-26 15:21:22.403  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-26 15:21:22.403  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-26 15:21:22.403  2987  2987 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,07-26 15:21:22.403  2987  2987 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:21:22.403  3182  3182 D BluetoothA2dp: Proxy object disconnected
,07-26 15:21:22.403  2987  2987 D HidService: Received stop request...Stopping profile...
07-26 15:21:22.403  2987  2987 D HidService: Stopping Bluetooth HidService
07-26 15:21:22.403  2987  2987 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,07-26 15:21:22.403  2987  2987 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-26 15:21:22.403  2987  2987 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.403  4295  4295 D BluetoothInputDevice: Proxy object disconnected
07-26 15:21:22.403  4295  4295 D HidProfile: Bluetooth service disconnected
,07-26 15:21:22.403  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,07-26 15:21:22.403  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-26 15:21:22.403  2987  2987 D BluetoothA2dp: Proxy object disconnected
,07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-26 15:21:22.403  2987  2987 D HealthService: Received stop request...Stopping profile...
07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.403  2987  7955 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,07-26 15:21:22.403  2987  2987 I GKI_LINUX: GKI_exit_task 2 done
07-26 15:21:22.403  2987  2987 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-26 15:21:22.403  2987  2987 V Avrcp   : cleanup
,07-26 15:21:22.403  2987  2987 D PanService: Received stop request...Stopping profile...
07-26 15:21:22.403  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.413   767   767 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-26 15:21:22.413  4295  4295 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-26 15:21:22.413  2987  2987 D BluetoothMapService: Received stop request...Stopping profile...
,07-26 15:21:22.413  4295  4295 D PanProfile: Bluetooth service disconnected
,07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.413  4295  4295 D BluetoothMap: Proxy object disconnected
07-26 15:21:22.413  4295  4295 D MapProfile: Bluetooth service disconnected
,07-26 15:21:22.413  2987  2987 D SapService: Received stop request...Stopping profile...
,07-26 15:21:22.413  2987  2987 D SapService: Stopping Bluetooth SapService
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:22.413  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:22.413  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.413  4295  4295 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-26 15:21:22.413  4295  4295 D SapProfile: Bluetooth service disconnected
07-26 15:21:22.413  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,07-26 15:21:22.413  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.413  2987  2987 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:21:22.413  2987  2987 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-26 15:21:22.413  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:22.413  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.413  2987  2987 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:22.413  2987  2987 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-26 15:21:22.413  2987  2987 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-26 15:21:22.423  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-26 15:21:22.423  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:22.423  2987  2987 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:22.423  2987  2987 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,07-26 15:21:22.423  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-26 15:21:22.423  2987  2987 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
07-26 15:21:22.423  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-26 15:21:22.423  2987  3042 D BluetoothAdapterProperties: Setting state to 10
07-26 15:21:22.423  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-26 15:21:22.423  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:22.423  2987  3042 D BluetoothAdapterService: updateAdapterState state is 10
,07-26 15:21:22.423  2987  2987 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-26 15:21:22.423  2987  2987 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-26 15:21:22.423  4295  4306 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:21:22.423  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:22.423  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-26 15:21:22.423  2987  3042 I BluetoothAdapterState: Entering OffState
,07-26 15:21:22.423   767  1057 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:22.423  4295  7966 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:22.423  2987  7969 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:22.423  4295  7966 D BluetoothMap: onBluetoothStateChange: up=false
,07-26 15:21:22.423  4295  4304 D Bluetoothsap: onBluetoothStateChange: up=false
07-26 15:21:22.423  4295  4304 D Bluetoothsap: Unbinding service...
,07-26 15:21:22.433  3182  3193 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:21:22.433  4295  4306 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-26 15:21:22.433  1694  1694 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-26 15:21:22.433   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.433   767   767 I InputMethodManagerService: [BT Setting State] State =10
07-26 15:21:22.433   767   767 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-26 15:21:22.433  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:22.433  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:22.433  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-26 15:21:22.433  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:22.433  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:22.433  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:22.443  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:22.443  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:21:22.443   767  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-26 15:21:22.443   767  3013 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-26 15:21:22.443   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@17f0754, r.packageName :com.android.settings
07-26 15:21:22.443   767  1320 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-26 15:21:22.443  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-26 15:21:22.443  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:22.453  4295  4295 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:22.453  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D QSpanel : label top:23
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:22.453  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:22.533   767  1473 I ActivityManager: Killing 6339:com.android.vending/u0a33 (adj 15): emptyCount ##41
,07-26 15:21:23.703  2987  3048 D bt_vendor: op for 7
,07-26 15:21:24.174  2987  3154 D bt_upio : ..proc_btwrite_timeout..
,07-26 15:21:25.213   304   304 E SMD     : DCD ON
,07-26 15:21:25.223  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:21:25.223  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:25.714   767  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-26 15:21:27.064   767  3050 D SSRM:n  : SIOP:: AP = 360, PST = 361, CUR = 450
,07-26 15:21:28.213   304   304 E SMD     : DCD ON
,07-26 15:21:28.233  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:28.233  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f3a5339 added. We now have 6 listener(s)
,07-26 15:21:28.233  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:28.243  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:28.253  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3846fd7e added. We now have 7 listener(s)
,07-26 15:21:28.253  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:28.253  7221  7279 I System.out: IsBluetoothEnabled
,07-26 15:21:28.253  7221  7279 D BluetoothAdapter: disable()
,07-26 15:21:28.253   767  1143 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-26 15:21:28.263  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:28.263  7221  7279 D BluetoothAdapter: enable()
,07-26 15:21:28.263   767  3837 W ActivityManager: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-26 15:21:28.263   767  3837 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-26 15:21:28.263   767  3837 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:28.263   767  3837 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-26 15:21:28.263   767  3837 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-26 15:21:28.263   767  3837 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-26 15:21:28.263   767  3837 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-26 15:21:28.263   767  3837 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-26 15:21:28.263   767  3837 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-26 15:21:28.263   767  3837 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:28.263   767  3837 D SettingsProvider: name = bluetooth_on
,07-26 15:21:28.273   767  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:28.273   767  1057 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-26 15:21:28.273   767  1057 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-26 15:21:28.273  2987  3042 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-26 15:21:28.273  2987  3042 D BluetoothAdapterProperties: Setting state to 11
07-26 15:21:28.273  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-26 15:21:28.273  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-26 15:21:28.273  2987  3042 D BluetoothAdapterService: updateAdapterState state is 11
,07-26 15:21:28.273  2987  3042 D BluetoothAdapterService: Autoconnection is available 
07-26 15:21:28.273  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
07-26 15:21:28.273  2987  3042 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
,07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-26 15:21:28.273  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
07-26 15:21:28.273  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
,07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-26 15:21:28.283   767   788 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.283   767   788 D ActivityManager: caller:android.app.ApplicationThreadProxy@26869ff2, r.packageName :com.android.bluetooth
,07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,07-26 15:21:28.283  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-26 15:21:28.283  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-26 15:21:28.283   767  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.283   767  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@386f44c0, r.packageName :com.android.bluetooth
,07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,07-26 15:21:28.293  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-26 15:21:28.293   767  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.293   767  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a5ac93e, r.packageName :com.android.bluetooth
,07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,07-26 15:21:28.293  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-26 15:21:28.293   767  1523 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.293   767  1523 D ActivityManager: caller:android.app.ApplicationThreadProxy@2563ecec, r.packageName :com.android.bluetooth
,07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,07-26 15:21:28.293  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-26 15:21:28.293  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-26 15:21:28.293   767  3783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.293   767  3783 D ActivityManager: caller:android.app.ApplicationThreadProxy@bb63b4a, r.packageName :com.android.bluetooth
,07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-26 15:21:28.303   767  3013 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:28.303   767  3013 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a18ebd8, r.packageName :com.android.bluetooth
,07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-26 15:21:28.303   767  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.303   767  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@34a4c216, r.packageName :com.android.bluetooth
,07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
,07-26 15:21:28.303  2987  3042 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-26 15:21:28.303  2987  3042 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-26 15:21:28.303  2987  3042 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-26 15:21:28.313  2987  2987 D HeadsetService: Received start request. Starting profile...
07-26 15:21:28.313  2987  2987 D HeadsetStateMachine: make
,07-26 15:21:28.313  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:28.313   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.313   767   767 I InputMethodManagerService: [BT Setting State] State =11
,07-26 15:21:28.323  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-26 15:21:28.323  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:28.323  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:28.323   767  1446 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:28.323   767  1482 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-26 15:21:28.323  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-26 15:21:28.323  2987  2987 E HeadsetStateMachine: # of Max HF connection is 2
,07-26 15:21:28.333   767  3013 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-26 15:21:28.333   767   787 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-26 15:21:28.333  2987  2987 I bluedroid: get_profile_interface handsfree
,07-26 15:21:28.333  2987  2987 E DualScoManager: Dual Sco Manager already instantiated
07-26 15:21:28.333  2987  2987 I DualScoManager: Set HeadsetServiceHelper
07-26 15:21:28.333  2987  2987 D BluetoothAtMessage: createCMTIContentObservers
,07-26 15:21:28.333   767  1633 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-26 15:21:28.333   767  1633 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-26 15:21:28.333   767  1633 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-26 15:21:28.333   767  1633 D SettingsProvider: selectionArgs: false
07-26 15:21:28.333   767  1633 D SettingsProvider: selectionArgs: 1002
,07-26 15:21:28.333   767  1633 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-26 15:21:28.333   767  1633 D SettingsProvider: ret = -1
,07-26 15:21:28.333  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:28.343  2987  2987 D A2dpService: Received start request. Starting profile...
07-26 15:21:28.343  2987  2987 V Avrcp   : make
,07-26 15:21:28.343  2987  2987 V Avrcp   : Avrcp
,07-26 15:21:28.343  2987  2987 I bluedroid: get_profile_interface avrcp
,07-26 15:21:28.343  2987  2987 V Avrcp   : start
,07-26 15:21:28.343  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.343  2987  8035 D HeadsetStateMachine: Enter Disconnected: -2
,07-26 15:21:28.343  2987  8035 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-26 15:21:28.343  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.353  2987  8035 D HeadsetStateMachine: map size, before remove : 0
07-26 15:21:28.353  2987  8035 D HeadsetStateMachine: map size, after remove: 0
07-26 15:21:28.353  2987  8035 D HeadsetStateMachine: mNextConnectingDevice : null
,07-26 15:21:28.353  1694  1694 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-26 15:21:28.353  2987  2987 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
,07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D QSpanel : label top:23
07-26 15:21:28.363  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:28.363  2987  2987 V Avrcp   : ++registerMediaPlayers++
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:28.363  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:28.363  2987  2987 I Avrcp   : No of Audio players :: 2
07-26 15:21:28.363  2987  2987 I Avrcp   : App Package name is com.google.android.music
,07-26 15:21:28.363  2987  2987 I Avrcp   : App pkg name is Google Play Music
07-26 15:21:28.363  2987  2987 I Avrcp   : Name::Google Play Music
07-26 15:21:28.363  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-26 15:21:28.363  2987  2987 I Avrcp   : App Package name is com.sec.android.app.music
,07-26 15:21:28.363  2987  2987 I Avrcp   : App pkg name is Music
,07-26 15:21:28.363  2987  2987 I Avrcp   : Name::Music
07-26 15:21:28.363  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-26 15:21:28.363  2987  2987 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-26 15:21:28.363  2987  2987 I Avrcp   : No of Video players :: 1
07-26 15:21:28.363  2987  2987 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-26 15:21:28.363  2987  2987 I Avrcp   : Video App pkg name is Video Player
,07-26 15:21:28.363  2987  2987 I Avrcp   : Name::Video Player
07-26 15:21:28.363  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-26 15:21:28.363  2987  2987 I Avrcp   : Add tempPlayer
07-26 15:21:28.363  2987  2987 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-26 15:21:28.363  2987  2987 I Avrcp   : Total no of players: 4
07-26 15:21:28.363  2987  2987 V Avrcp   : swapping the samsung player with 1st player
07-26 15:21:28.363  2987  2987 I Avrcp   :  Updating now playing list upon AVRCP Start
07-26 15:21:28.363  2987  8046 V Avrcp   : handleMessage, msg=207
07-26 15:21:28.363  2987  8046 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-26 15:21:28.373  2987  2987 D A2dpStateMachine: make
,07-26 15:21:28.373  2987  2987 I bluedroid: get_profile_interface a2dp
,07-26 15:21:28.373  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
07-26 15:21:28.373  2987  8050 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,07-26 15:21:28.373  2987  2987 E bt-btif : warning : media task started media_task_refcnt 1 
07-26 15:21:28.373  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:28.373  2987  8049 D A2dpStateMachine: Enter Disconnected: -2
,07-26 15:21:28.373  2987  2987 D HidService: Received start request. Starting profile...
07-26 15:21:28.373  2987  2987 I bluedroid: get_profile_interface hidhost
07-26 15:21:28.373  2987  2987 D HidService: setHidService(): set to: null
07-26 15:21:28.373  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:28.373  2987  2987 D HealthService: Received start request. Starting profile...
,07-26 15:21:28.383  2987  2987 I bluedroid: get_profile_interface health
,07-26 15:21:28.383  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:28.383  2987  2987 D PanService: Received start request. Starting profile...
07-26 15:21:28.383  2987  2987 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:21:28.383  2987  2987 I bluedroid: get_profile_interface pan
07-26 15:21:28.383  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:28.383  2987  2987 D BluetoothMapService: Received start request. Starting profile...
,07-26 15:21:28.383  2987  8046 D BluetoothMediaBrowser: no now playing list
,07-26 15:21:28.383  2987  8046 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-26 15:21:28.383  2987  8046 D Avrcp   :  checkNowPlayingList start
,07-26 15:21:28.393  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
,07-26 15:21:28.393  2987  2987 D SapService: Received start request. Starting profile...
07-26 15:21:28.393  2987  2987 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-26 15:21:28.393  2987  2987 I bluedroid: get_profile_interface sap
07-26 15:21:28.393  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:28.393  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-26 15:21:28.393  2987  2987 D HeadsetStateMachine: Try to query the phonestate on bind
07-26 15:21:28.393  1404  8022 I Telecom : BluetoothPhoneService: queryPhoneState
,07-26 15:21:28.393  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-26 15:21:28.393  2987  2987 D HeadsetStateMachine: Proxy object connected
07-26 15:21:28.393  2987  2987 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-26 15:21:28.393  2987  2987 D HeadsetPhoneState: sendDeviceDataStateChanged
,07-26 15:21:28.393  2987  2987 D HeadsetPhoneState: Signal level : previous=0 curr=1
07-26 15:21:28.393  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-26 15:21:28.393  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-26 15:21:28.393  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-26 15:21:28.393  2987  8035 D HeadsetStateMachine: Disconnected process message: 11
07-26 15:21:28.393  2987  8035 D HeadsetStateMachine: Disconnected process message: 18
07-26 15:21:28.393  2987  8035 D HeadsetStateMachine: Disconnected process message: 10
07-26 15:21:28.393  2987  8035 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-26 15:21:28.393  2987  8035 D HeadsetStateMachine: Disconnected process message: 11
,07-26 15:21:28.393  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-26 15:21:28.393  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-26 15:21:28.413  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-26 15:21:28.413  2987  2987 E BluetoothAdapterService(158018528): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-26 15:21:28.413  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-26 15:21:28.413  2987  3042 I bluedroid: enable
,07-26 15:21:28.413  2987  3045 E bt-btif : Calling BTA_HhEnable
07-26 15:21:28.413  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:28.413  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:28.413  2987  3045 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: Address is:B0:C5:59:2A:28:2D
07-26 15:21:28.413  2987  3045 E BluetoothServiceJni: populateRssiValuesNative
07-26 15:21:28.413  2987  3045 I bluedroid: getModelRssiValues
07-26 15:21:28.413  2987  3045 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-26 15:21:28.413  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.413   767   767 D SettingsProvider: name = bluetooth_name
07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: Name is: Galaxy Note3
,07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:28.413  2987  3045 D BluetoothAdapterProperties: LE Address is:F0:8B:B2:54:50:5A
07-26 15:21:28.413  2987  3045 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
07-26 15:21:28.413  2987  3045 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:21:28.423  2987  3048 D bt_upio : proc btwrite assertion
07-26 15:21:28.423  2987  3045 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-26 15:21:28.423  2987  3045 E bt-btif : JVenable fails
07-26 15:21:28.423  2987  3045 D bte_conf: Device ID record 1 : primary
07-26 15:21:28.423  2987  3045 D bte_conf:   vendorId            = 0075
07-26 15:21:28.423  2987  3045 D bte_conf:   vendorIdSource      = 0001
,07-26 15:21:28.423  2987  3045 D bte_conf:   product             = 0100
07-26 15:21:28.423  2987  3045 D bte_conf:   version             = 0200
07-26 15:21:28.423  2987  3045 D bte_conf:   clientExecutableURL = 
07-26 15:21:28.423  2987  3045 D bte_conf:   serviceDescription  = 
07-26 15:21:28.423  2987  3045 D bte_conf:   documentationURL    = 
,07-26 15:21:28.423  2987  3045 D bte_conf: bte_load_did_conf no section named DID2.
07-26 15:21:28.423  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.423  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.423  2987  3042 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-26 15:21:28.423  2987  3042 D BluetoothAdapterProperties: ScanMode =  20
,07-26 15:21:28.423  2987  3042 D BluetoothAdapterProperties: State =  11
,07-26 15:21:28.423   767  3783 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-26 15:21:28.423  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.423  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.423  2987  3045 E bt-btif : btif_config_get(L243): assert failed: section && *section && key && *key && name && *name && bytes && type
07-26 15:21:28.423  2987  3045 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-26 15:21:28.423  2987  3042 D BluetoothAdapterProperties: Setting state to 12
07-26 15:21:28.423  2987  3042 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-26 15:21:28.423  2987  3045 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:21:28.423  2987  3045 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:21:28.423   767  1471 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-26 15:21:28.423   767  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-26 15:21:28.423   767  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-26 15:21:28.423   767  1471 D SettingsProvider: selectionArgs: false
07-26 15:21:28.423   767  1471 D SettingsProvider: selectionArgs: 1002
07-26 15:21:28.423   767  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-26 15:21:28.423   767  1471 D SettingsProvider: ret = -1
,07-26 15:21:28.423  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.423  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.423  2987  3042 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-26 15:21:28.423  2987  3042 D BluetoothAdapterService: updateAdapterState state is 12
07-26 15:21:28.423   767  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-26 15:21:28.423   767  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@96fdcc6, r.packageName :com.android.bluetooth
07-26 15:21:28.423  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.423  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.423  2987  3042 D BluetoothAdapterService: Autoconnection is available 
,07-26 15:21:28.423  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.423  4295  7966 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:21:28.423  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.423  2987  3042 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:28.423  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:21:28.423  2987  3042 D BluetoothAdapterService: starting service from this receiver
07-26 15:21:28.423   767  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.433   767  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ed8bfb4, r.packageName :com.android.bluetooth
07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:28.433  2987  3042 I BluetoothAdapterState: Entering On State from state = 11
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.433  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.433  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  2987 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.443  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.443  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.453  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.453  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.453  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.453  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.453  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.453  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.453  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.453  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.453  2987  3048 D bt_upio : BT_WAKE is asserted already
,07-26 15:21:28.523   767  1057 I art     : Explicit concurrent mark sweep GC freed 75630(4MB) AllocSpace objects, 7(112KB) LOS objects, 30% free, 36MB/52MB, paused 1.194ms total 93.854ms
,07-26 15:21:28.523   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-26 15:21:28.533   767  1057 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.533  2987  2987 I BluetoothPbapService: Handler(): got msg=1
,07-26 15:21:28.533  7360  7370 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.533   767   787 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-26 15:21:28.533   767  1057 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.533  1428  1460 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:28.533   767  1057 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:28.533   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-26 15:21:28.533   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.533  2987  8060 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-26 15:21:28.533  4295  4295 D BluetoothPbap: Proxy object connected
07-26 15:21:28.533  4295  4295 D PbapServerProfile: Bluetooth service connected
,07-26 15:21:28.543  1404  7327 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.543  4295  7966 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:28.543   767   767 D BluetoothA2dp: Proxy object connected
,07-26 15:21:28.543  2987  8060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:28.543  2987  8060 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-26 15:21:28.543  2987  8060 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:28.543  2987  8060 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:28.543  2987  8060 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10a5c6d
07-26 15:21:28.543  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.543   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-26 15:21:28.543  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.543  2987  8060 D BluetoothSocket: channel: 19
07-26 15:21:28.543  2987  8060 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-26 15:21:28.543  4295  4295 D BluetoothA2dp: Proxy object connected
07-26 15:21:28.543  4295  4295 D A2dpProfile: Bluetooth service connected
,07-26 15:21:28.543   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.543  4295  4306 E BluetoothHeadset: BluetoothHeadset service is binded
07-26 15:21:28.543  4295  7966 D BluetoothPan: Binding service...
,07-26 15:21:28.543  4295  4295 D HeadsetProfile: Bluetooth service connected
,07-26 15:21:28.543   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-26 15:21:28.553   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.553   767  1057 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.553  2987  2997 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:28.553   767  1057 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-26 15:21:28.553  4295  4295 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:28.553  4295  4295 D PanProfile: Bluetooth service connected
07-26 15:21:28.553  4295  4306 D BluetoothMap: onBluetoothStateChange: up=true
07-26 15:21:28.553  2987  2987 D BluetoothA2dp: Proxy object connected
07-26 15:21:28.553  2987  2987 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-26 15:21:28.553   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-26 15:21:28.553  4295  7966 D Bluetoothsap: onBluetoothStateChange: up=true
07-26 15:21:28.553  4295  7966 D Bluetoothsap: Binding service...
,07-26 15:21:28.553  4295  7966 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-26 15:21:28.553  4295  4295 D BluetoothMap: Proxy object connected
07-26 15:21:28.553  4295  4295 D MapProfile: Bluetooth service connected
07-26 15:21:28.553   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-26 15:21:28.553  4295  7966 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-26 15:21:28.553   767  1057 D BluetoothPan: Binding service...
,07-26 15:21:28.553   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-26 15:21:28.553   767   767 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:21:28.553  4295  4295 D Bluetoothsap: BluetoothSAP Proxy object connected
07-26 15:21:28.553  4295  4295 D SapProfile: Bluetooth service connected
07-26 15:21:28.553  4295  4295 D Bluetoothsap: getConnectedDevices()
,07-26 15:21:28.563   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.563  1404  8022 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.563  3182  3191 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:21:28.563   767  1057 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-26 15:21:28.563  3182  3182 D BluetoothA2dp: Proxy object connected
,07-26 15:21:28.563  4295  4304 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:21:28.563   767  1057 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-26 15:21:28.563  4295  4295 D BluetoothInputDevice: Proxy object connected
07-26 15:21:28.563  4295  4295 D HidProfile: Bluetooth service connected
,07-26 15:21:28.563   767  1057 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-26 15:21:28.563  1404  7327 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.563   767  1057 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-26 15:21:28.563  3182  3193 E BluetoothHeadset: BluetoothHeadset service is binded
,07-26 15:21:28.573   767  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
07-26 15:21:28.573   767   767 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:28.573   767   767 I InputMethodManagerService: [BT Setting State] State =12
07-26 15:21:28.573   767   767 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-26 15:21:28.573  1197  1197 D BluetoothTile:  onBluetoothStateChange:
,07-26 15:21:28.573  1694  1694 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-26 15:21:28.573  4295  4295 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:21:28.573  7360  7360 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:28.573  1197  1197 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-26 15:21:28.573  1197  1197 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:21:28.573  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:28.573  1197  1584 D BluetoothTile:  handleUpdatestate:false name:null
07-26 15:21:28.573  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-26 15:21:28.573  2987  8061 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-26 15:21:28.573  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@282e64ca, true
07-26 15:21:28.583   767  3837 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:28.583  1404  1404 D BluetoothHeadset: registerMessageListener
07-26 15:21:28.583   767  1320 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-26 15:21:28.583  4295  4295 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-26 15:21:28.583  4295  4295 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-26 15:21:28.583  1197  1197 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-26 15:21:28.583  2987  2997 D HeadsetService: registerMessageListener
07-26 15:21:28.583  2987  2997 D HeadsetService: registerMessageListener
,07-26 15:21:28.583  2987  8035 D HeadsetStateMachine: Disconnected process message: 70
07-26 15:21:28.583  2987  8035 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2e0c0a2
07-26 15:21:28.583  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-26 15:21:28.583  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
07-26 15:21:28.583  2987  8061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:28.583  2987  8035 D HeadsetStateMachine: Disconnected process message: 9
07-26 15:21:28.583  2987  8035 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-26 15:21:28.583  4295  4295 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-26 15:21:28.583  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.583  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.583   767  1523 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-26 15:21:28.583  2987  8061 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
07-26 15:21:28.583   767  1523 D ActivityManager: caller:android.app.ApplicationThreadProxy@5fa7ab0, r.packageName :com.android.settings
,07-26 15:21:28.583  2987  8061 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:28.583  2987  8061 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:28.583  2987  8061 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@13af9133
07-26 15:21:28.583  2987  8061 D BluetoothSocket: channel: 5
,07-26 15:21:28.583   314   765 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,07-26 15:21:28.583   314   765 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-26 15:21:28.583   314   765 V voice   : voice_set_parameters: exit with code(-2)
07-26 15:21:28.583   314   765 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-26 15:21:28.593   314   765 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-26 15:21:28.593   314   765 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-26 15:21:28.593   314   765 V audio_hw_primary: adev_set_parameters: exit
,07-26 15:21:28.593  2987  8035 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D QSpanel : label top:23
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:28.593  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:28.593  1723  1723 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:21:28.593  4295  4295 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:21:28.593  4295  4295 D BluetoothNotiBroadcastReceiver: onReceive
,07-26 15:21:28.603  2987  2987 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96b2be0
07-26 15:21:28.603  2987  2987 D BtConfig.SecureMode: isSecureModeOn:false
,07-26 15:21:28.603   767  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-26 15:21:28.603   767  1482 D ActivityManager: caller:android.app.ApplicationThreadProxy@38c648ae, r.packageName :com.android.bluetooth
,07-26 15:21:28.613   767  1482 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-26 15:21:28.623  2987  8067 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:21:28.623  2987  3048 D bt_vendor: op for 7
07-26 15:21:28.623  2987  3048 D bt_upio : BT_WAKE is asserted already
07-26 15:21:28.623  2987  8067 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[84]}
07-26 15:21:28.623  2987  8067 D BluetoothSocket: bindListen(), new LocalSocket 
07-26 15:21:28.623  2987  8067 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-26 15:21:28.623  2987  8067 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f480d8f
07-26 15:21:28.623  2987  8067 D BluetoothSocket: channel: 12
07-26 15:21:28.623  2987  8067 I BtOppRfcommListener: Accept thread started.
,07-26 15:21:29.223   767  1115 V AlarmManager: waitForAlarm result :4
,07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:29.363  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:29.363  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:29.363  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:21:29.363  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24ea82df added. We now have 8 listener(s)
,07-26 15:21:29.363  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:29.373  7221  7279 I WifiManager: packageName : com.test.thalitest
,07-26 15:21:29.373   767  1471 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-26 15:21:29.373   767  1471 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:29.373   767  1471 D SecContentProvider2: mCursor = null
,07-26 15:21:29.373   767  1471 D WifiService: setWifiEnabled: false pid=7221, uid=10079
,07-26 15:21:29.373   767  1471 D SettingsProvider: name = wifi_on
,07-26 15:21:29.383  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:29.383  7221  7279 I WifiManager: packageName : com.test.thalitest
,07-26 15:21:29.383   767  3013 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-26 15:21:29.383   767  3013 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-26 15:21:29.383   767  3013 D SecContentProvider2: mCursor = null
,07-26 15:21:29.383   767  3013 D WifiService: setWifiEnabled: true pid=7221, uid=10079
,07-26 15:21:29.383   767  3013 W ActivityManager: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:29.383   767  3013 W WifiService: Failed getting userId using ActivityManagerNative
07-26 15:21:29.383   767  3013 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7221, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-26 15:21:29.383   767  3013 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-26 15:21:29.383   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-26 15:21:29.383   767  3013 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-26 15:21:29.383   767  3013 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-26 15:21:29.383   767  3013 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-26 15:21:29.383   767  3013 D SettingsProvider: name = wifi_on
,07-26 15:21:29.383   767  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-26 15:21:29.383   296  1055 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-26 15:21:29.383   296  1055 I WifiHW  : module is semco
07-26 15:21:29.383   296  1055 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-26 15:21:29.383   296  1055 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-26 15:21:29.383   296  1055 E WifiHW  : TEMP_FAILURE_RETRY complete
07-26 15:21:29.383   296  1055 D SoftapController: Softap fwReload - Ok
,07-26 15:21:29.393   296  1055 D CommandListener: Setting iface cfg
07-26 15:21:29.393   296  1055 D CommandListener: Trying to bring down wlan0
,07-26 15:21:29.393   296  1055 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:21:29.393   767  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-26 15:21:29.413   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:29.413   767  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-26 15:21:29.413  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:29.413  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:29.413  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-26 15:21:29.413  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:29.423  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:29.423  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-26 15:21:29.423  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-26 15:21:29.423  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:29.423  1197  1197 D HotspotTile: onReceive : 2, 0
,07-26 15:21:29.423  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:29.433   767  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-26 15:21:29.443  1197  1197 D QSpanel : label top:23
,07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
,07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:29.443  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
,07-26 15:21:29.453  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:29.453  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:29.453  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:29.463   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:29.473  8082  8082 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,07-26 15:21:29.473  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-26 15:21:29.473  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:29.473  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
07-26 15:21:29.473  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:29.473  8082  8082 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-26 15:21:29.473  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-26 15:21:29.473  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:29.473   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8082
07-26 15:21:29.473   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,07-26 15:21:29.473  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:29.473  8082  8082 I wpa_supplicant: ssSupport state is = 1
,07-26 15:21:29.483  8082  8082 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-26 15:21:29.483  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-26 15:21:29.483   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8082
07-26 15:21:29.483   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-26 15:21:29.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:29.773   389   389 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-26 15:21:30.033  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-26 15:21:30.073  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-26 15:21:30.073  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-26 15:21:30.073   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8082
07-26 15:21:30.073   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-26 15:21:30.073  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:30.073  8082  8082 I wpa_supplicant: ssSupport state is = 1
07-26 15:21:30.073  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:30.073  8082  8082 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:30.073  8082  8082 E wpa_supplicant: SIM READ ERROR
07-26 15:21:30.073  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:30.073  8082  8082 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-26 15:21:30.073  8082  8082 E wpa_supplicant: SIM READ ERROR
07-26 15:21:30.073  8082  8082 I wpa_supplicant: Blacklist: Clear (all) 
07-26 15:21:30.073  8082  8082 I wpa_supplicant: wpa_default_ap_write_once
07-26 15:21:30.073  8082  8082 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-26 15:21:30.083  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:30.083  8082  8082 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-26 15:21:30.083  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-26 15:21:30.083  8082  8082 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-26 15:21:30.083  8082  8082 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:30.123  2987  3048 D bt_vendor: op for 7
,07-26 15:21:30.423  2987  3154 D bt_upio : ..proc_btwrite_timeout..
,07-26 15:21:30.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:30.733   767  1151 E Tethering: No numeric data
,07-26 15:21:30.733   767  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-26 15:21:30.733   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:30.733   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:30.733   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.733   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-26 15:21:30.733  1197  1197 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-26 15:21:30.733  1197  1197 D HotspotTile: updateTetherState():false, false
,07-26 15:21:30.743   767  1145 V NetworkStats: performPollLocked() took 5ms
,07-26 15:21:30.743   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:30.743   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:30.743   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:30.743  8082  8082 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-26 15:21:30.753  8082  8082 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:30.753   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8082
07-26 15:21:30.753   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:30.753  8082  8082 I wpa_supplicant: ssSupport state is = 1
,07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-26 15:21:30.753   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8082
07-26 15:21:30.753   389   389 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-26 15:21:30.753  8082  8082 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-26 15:21:30.753  8082  8082 I wpa_supplicant: ssSupport state is = 1
07-26 15:21:30.753  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-26 15:21:30.763  8082  8082 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:30.763  8082  8082 E wpa_supplicant: SIM READ ERROR
07-26 15:21:30.763  8082  8082 I wpa_supplicant: wpa_default_ap_write_once
07-26 15:21:30.763  8082  8082 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-26 15:21:30.763  8082  8082 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-26 15:21:30.783   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-26 15:21:30.783   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: HOTSPOT20_ENABLE called
,07-26 15:21:30.783  8082  8082 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-26 15:21:30.783  8082  8082 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-26 15:21:30.783  8082  8082 E wpa_supplicant: SIM READ ERROR
07-26 15:21:30.783  8082  8082 I wpa_supplicant: Blacklist: Clear (all) 
,07-26 15:21:30.803  8082  8082 I wpa_supplicant: Skip scan - bUseNetwork false
,07-26 15:21:30.803   767  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-26 15:21:30.803   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:30.803   767  1148 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:21:30.813   767  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:30.813  7221  7221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:30.813  7221  7221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:30.823  4295  4295 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:30.823  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:30.823   767  1148 E WifiConfigStore: Not a HS20
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:30.823  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:30.833  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:30.833  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:30.833  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:30.833  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:30.833  1197  1197 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-26 15:21:30.833  1197  1197 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-26 15:21:30.833  4949  4949 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-26 15:21:30.833  1197  1584 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-26 15:21:30.833  1197  1197 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-26 15:21:30.833   767  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:21:30.833  1197  1197 D HotspotTile: onReceive : 3, 0
,07-26 15:21:30.833   767  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-26 15:21:30.833   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:30.833  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-26 15:21:30.833  7112  7112 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-26 15:21:30.833  7112  7112 D SecurityLogAgent: StateMachine : Current State = 1
,07-26 15:21:30.833  7112  7112 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-26 15:21:30.843   767  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-26 15:21:30.843  8082  8082 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-26 15:21:30.843  8082  8082 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-26 15:21:30.843  8082  8082 I wpa_supplicant: reset timer : RESET_TIMER 0
07-26 15:21:30.843  8082  8082 I wpa_supplicant: P2P: Current p2p state = IDLE
07-26 15:21:30.843  8082  8082 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-26 15:21:30.843  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-26 15:21:30.843  8082  8082 I wpa_supplicant: First Scan Start
,07-26 15:21:30.843  8082  8082 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-26 15:21:30.843   767  1148 D WifiNative-HAL: Setting external_sim to 1
,07-26 15:21:30.843   767  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-26 15:21:30.843   767  1148 I WifiNative-HAL: startHal
07-26 15:21:30.843   767  1148 E wifi    : getStaticLongField sWifiHalHandle 0x93b9e86c
07-26 15:21:30.843   767  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601f32
07-26 15:21:30.843   767  1148 I WifiNative-HAL: Could not start hal
,07-26 15:21:30.853  7416  7416 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:21:30.853  1197  1197 D QSpanel : label top:23
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:0 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:206 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:412 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:618 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:824 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:1030 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:1236 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:1442 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:1648 top:0 record.row:0
07-26 15:21:30.853  1197  1197 D StatusBar-QSPanel: onLayout left:1854 top:0 record.row:0
,07-26 15:21:30.863   767  1148 E native  : do suspend true
,07-26 15:21:30.863   767  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-26 15:21:30.863   767   767 D WifiScanningService: SCAN_AVAILABLE : 3
,07-26 15:21:30.873   767   767 D RttService: SCAN_AVAILABLE : 3
07-26 15:21:30.873   767  1166 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.873   767  1166 I WifiNative-HAL: startHal
07-26 15:21:30.873   767  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9c7ee99c
07-26 15:21:30.873   767  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601f2a
07-26 15:21:30.873   767  1166 I WifiNative-HAL: Could not start hal
07-26 15:21:30.873   767  1166 E WifiScanningService: could not start HAL
,07-26 15:21:30.873   296  1055 D CommandListener: Setting iface cfg
07-26 15:21:30.873   296  1055 D CommandListener: Trying to bring up p2p0
07-26 15:21:30.873   767  1167 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:30.873   767  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:21:30.873   767  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-26 15:21:30.873   767  1147 D WifiP2pService: P2pEnablingState
,07-26 15:21:30.873   767  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
07-26 15:21:30.873   767  1147 D WifiP2pService: P2p socket connection successful
07-26 15:21:30.873   767  1147 D WifiP2pService: P2pEnabledState
,07-26 15:21:30.873   767  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-26 15:21:30.873   767   767 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-26 15:21:30.873   767  1058 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-26 15:21:30.873   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:30.873   767  1058 D WifiDisplayController: disconnect
07-26 15:21:30.873   767  1058 D WifiDisplayController: updateConnection
07-26 15:21:30.873   767  1058 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-26 15:21:30.873   767  1058 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:30.873  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-26 15:21:30.873   767  1058 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:30.873   767  1058 D WifiDisplayAdapter: onP2pDisconnected
07-26 15:21:30.873   767  1058 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-26 15:21:30.873   767  1058 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-26 15:21:30.873   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:30.873  1197  1197 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-26 15:21:30.873   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-26 15:21:30.873   767  1426 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-26 15:21:30.883  1197  1197 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-26 15:21:30.883   767  1147 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:21:30.883   767  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:d7:fd:2b
,07-26 15:21:30.883   767  1147 D WifiP2pService: DeviceAddress: ea:fd:2b
,07-26 15:21:30.883   767  1058 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy Note3
07-26 15:21:30.883   767  1058 D WifiDisplayController:  deviceAddress: ea:50:8b:d7:fd:2b
07-26 15:21:30.883   767  1058 D WifiDisplayController:  primary type: 10-0050F204-5
07-26 15:21:30.883   767  1058 D WifiDisplayController:  secondary type: null
07-26 15:21:30.883   767  1058 D WifiDisplayController:  wps: 0
07-26 15:21:30.883   767  1058 D WifiDisplayController:  grpcapab: 0
07-26 15:21:30.883   767  1058 D WifiDisplayController:  devcapab: 0
07-26 15:21:30.883   767  1058 D WifiDisplayController:  status: 3
07-26 15:21:30.883   767  1058 D WifiDisplayController:  wfdInfo: null
07-26 15:21:30.883   767  1058 D WifiDisplayController:  groupownerAddress: null
07-26 15:21:30.883   767  1058 D WifiDisplayController:  GOdeviceName: null
07-26 15:21:30.883   767  1058 D WifiDisplayController:  interfaceAddress: 
07-26 15:21:30.883   767  1058 D WifiDisplayController:  SConnectInfo : null
07-26 15:21:30.883   767  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-26 15:21:30.883   767  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-26 15:21:30.883   767  1148 E WifiNative-HAL: invaild command id : 215
,07-26 15:21:30.883  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-26 15:21:30.883  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-26 15:21:30.883   767  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:30.883  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:30.893   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:30.893  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:30.893  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:30.893  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:30.893  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:30.893  7383  7383 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-26 15:21:30.893  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-26 15:21:30.893   767  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-26 15:21:30.893  7398  7398 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-26 15:21:30.893  7398  7398 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-26 15:21:30.893   767  1147 D WifiP2pService: InactiveState
,07-26 15:21:30.893   767  1147 D WifiP2pService: InactiveState{ what=143376 }
07-26 15:21:30.893  7398  7398 D WifiDirectBR: stopServiceTest : false
07-26 15:21:30.903   767  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-26 15:21:30.913  8082  8082 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-26 15:21:30.913  8082  8082 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-26 15:21:30.913   767  1147 D WifiP2pService: InactiveState{ what=143376 }
,07-26 15:21:30.913   767  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-26 15:21:30.933  8082  8082 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-26 15:21:30.933   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:30.933   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:30.933   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-26 15:21:30.933   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.213   304   304 E SMD     : DCD ON
,07-26 15:21:31.343   767  3837 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-26 15:21:31.343   767  3837 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-26 15:21:31.343   767  3837 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-26 15:21:31.343   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-26 15:21:31.353   767   767 I MotionRecognitionService: Plugged
,07-26 15:21:31.353   767   767 I MotionRecognitionService: setPowerConnected  = true
,07-26 15:21:31.353   767  3837 D BatteryService: stay LED for fully charged
,07-26 15:21:31.363  2987  2987 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-26 15:21:31.363  2987  8035 D HeadsetStateMachine: Disconnected process message: 10
,07-26 15:21:31.363  1197  1197 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-26 15:21:31.363  1197  1197 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-26 15:21:31.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:31.363  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:31.373  1197  1197 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-26 15:21:31.373  1197  1197 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:31.463  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:31.473  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:31.473  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@37114d10 Bundle[{}]
,07-26 15:21:31.483  7221  7279 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:21:31.483  7221  7279 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:21:31.483  7221  7279 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-26 15:21:31.493  7221  7279 I System.out: Running OutgoingSocketThread
,07-26 15:21:31.493   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:31.493  7221  8144 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1312)
,07-26 15:21:31.503  7221  8144 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 43272
,07-26 15:21:31.503  7221  8144 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 15:21:31.633  8082  8082 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,07-26 15:21:31.643  8082  8082 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-26 15:21:31.643  8082  8082 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-26 15:21:31.643  8082  8082 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-26 15:21:31.653  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,07-26 15:21:31.683   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:31.683   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.753  8082  8082 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-26 15:21:31.753  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,07-26 15:21:31.753  8082  8082 I wpa_supplicant: Associated with F4.99.3E
07-26 15:21:31.753  8082  8082 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-26 15:21:31.753  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:31.763   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:31.763   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.763   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:31.763   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.773  8082  8082 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-26 15:21:31.773  8082  8082 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-26 15:21:31.773  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:31.773  8082  8082 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:21:31.773  8082  8082 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-26 15:21:31.773  8082  8082 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
07-26 15:21:31.773  8082  8082 I wpa_supplicant: Blacklist: Clear (temp) 
07-26 15:21:31.773  8082  8082 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-26 15:21:31.773   767  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-26 15:21:31.783  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:31.783  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:31.783  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:31.793   767  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-26 15:21:31.793   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:21:31.793   767  1150 D ConnectivityService: Got NetworkAgent Messenger
07-26 15:21:31.793   767  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-26 15:21:31.793   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:31.793   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:31.793   767  1150 D ConnectivityService: NetworkAgent connected
,07-26 15:21:31.803  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:31.803  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-26 15:21:31.803   767  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:21:31.803   767  1446 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:31.803  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-26 15:21:31.803   767  3783 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:31.803  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:31.803  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-26 15:21:31.803  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-26 15:21:31.803  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:31.813   296  1055 D CommandListener: Setting iface cfg
,07-26 15:21:31.813   767  1482 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:31.813   767  1148 E WifiStateMachine: Start Dhcp Watchdog 3
,07-26 15:21:31.823   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:31.823   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.823   767  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-26 15:21:31.833   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-26 15:21:31.833  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:31.833  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-26 15:21:31.833  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:31.833   767  1148 D SecContentProvider2: mCursor = null
,07-26 15:21:31.843  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:31.903   767   975 I ActivityManager: Waited long enough for: ServiceRecord{de4c2 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,07-26 15:21:31.913   767  1148 E native  : do suspend false
,07-26 15:21:31.923   767  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-26 15:21:31.923   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-26 15:21:32.133  8149  8149 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-26 15:21:32.133  8149  8149 I dhcpcd  : version 5.5.6 starting
,07-26 15:21:32.143  8149  8149 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-26 15:21:32.203  8149  8149 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-26 15:21:32.203  8149  8149 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-26 15:21:32.203  8149  8149 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-26 15:21:32.203  8149  8149 I dhcpcd  : bssid match
07-26 15:21:32.203  8149  8149 I dhcpcd  : wlan0: rebinding lease of 192.168.1.119
,07-26 15:21:32.213  8149  8149 I dhcpcd  : wlan0: acknowledged 192.168.1.119 from 192.168.1.1
,07-26 15:21:32.213  8149  8149 I dhcpcd  : wlan0: leased 192.168.1.119 for 172800 seconds
,07-26 15:21:32.213   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-26 15:21:32.493  7221  7279 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1313)
07-26 15:21:32.493  7221  7279 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1313)
07-26 15:21:32.493  7221  7279 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1313)
07-26 15:21:32.493  7221  7279 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1313)
07-26 15:21:32.493  7221  7279 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1318)
07-26 15:21:32.493  7221  7279 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 1318)
07-26 15:21:32.493  7221  7279 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1318)
,07-26 15:21:32.503   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:32.503  7221  7279 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 1319)
,07-26 15:21:32.503  7221  7279 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1321)
,07-26 15:21:32.503  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:21:32.503  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333db2c added. We now have 2 listener(s)
,07-26 15:21:32.503  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.503  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.503  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.503  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.503  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e3e9f5 added. We now have 9 listener(s)
,07-26 15:21:32.503  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:32.513  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:32.513  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:32.513  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:32.513  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:32.513  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:32.513  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.513  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e6dfb added. We now have 3 listener(s)
,07-26 15:21:32.513  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11997e18 added. We now have 10 listener(s)
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.523  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:21:32.523  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.523  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.523  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.523  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@333db2c removed from the list
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e3e9f5 removed from the list
07-26 15:21:32.523  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.523  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:32.523  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19e3e9f5 not in the list
07-26 15:21:32.523  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11997e18 removed from the list
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.523  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.523  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.523  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e6dfb removed from the list
07-26 15:21:32.523   767  1148 E native  : do suspend true
07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:21:32.523  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21563071 added. We now have 2 listener(s)
,07-26 15:21:32.533  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.533  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.533  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.533  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.533  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdb3e56 added. We now have 9 listener(s)
07-26 15:21:32.533  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:32.533  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:32.533  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:32.533  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:32.533   767  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-26 15:21:32.533   767  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-26 15:21:32.533  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:32.533  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:32.533  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.543  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.543   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-26 15:21:32.543   767  1148 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-26 15:21:32.543   767  1148 E WifiStateMachine: VerifyingLinkState enter
07-26 15:21:32.543  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.543  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb463c4 added. We now have 3 listener(s)
,07-26 15:21:32.543   767  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-26 15:21:32.543  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:32.543  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:32.543  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:32.543   767  1150 E ConnectivityService: updateNetworkInfo()
,07-26 15:21:32.543   767  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 15:21:32.543   767  1150 D ConnectivityService: Adding iface wlan0 to network 504
07-26 15:21:32.543   767  1161 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
07-26 15:21:32.543   767  1161 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 15:21:32.543   767  1161 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:32.553   767  1161 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-26 15:21:32.553  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:32.553  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:32.553   767  1161 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 15:21:32.553  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:32.553  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.553  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.553  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.553  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.553  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcc62ad added. We now have 10 listener(s)
07-26 15:21:32.553  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.553  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:32.553  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:32.553  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:32.553  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:21:32.563  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 15:21:32.563  7221  7279 E BluetoothAdapter: bluetooth le advertising not supported
,07-26 15:21:32.563  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:32.563  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:21:32.563   767  1148 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-26 15:21:32.573  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:21:32.573   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 15:21:32.573   767   767 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-26 15:21:32.573   767   767 I WifiTrafficPoller: mBoosterFLAG : 0
07-26 15:21:32.573   767   767 I WifiTrafficPoller: current booster mode : FullMode
07-26 15:21:32.573   767   767 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshViews connected={ } level=1 combinedSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:32.583  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-26 15:21:32.583  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:32.583  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:32.583  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-26 15:21:32.583  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.583  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.583   767  1148 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:32.583  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.583  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:32.583  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.583  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:32.583  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.593  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.593  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21563071 removed from the list
07-26 15:21:32.593  4295  4295 I NearbySettings: MountReceiver.onReceive - Keep current state
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdb3e56 removed from the list
07-26 15:21:32.593  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.593  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:21:32.593  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cdb3e56 not in the list
07-26 15:21:32.593  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.593  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fcc62ad removed from the list
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.593  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.593  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bb463c4 removed from the list
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@975f830 added. We now have 2 listener(s)
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.593  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df97ca9 added. We now have 9 listener(s)
07-26 15:21:32.593  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:32.603   767  1150 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-26 15:21:32.603   767  1150 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-26 15:21:32.603   767  1150 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,07-26 15:21:32.603  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:32.603   767  1150 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:21:32.603   767  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-26 15:21:32.603   767  1150 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.119
07-26 15:21:32.603   296  1055 V         : QcRouteController
,07-26 15:21:32.603  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:32.603  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:32.603  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:32.603  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:32.603  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.603  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291fe1cf added. We now have 3 listener(s)
,07-26 15:21:32.613  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.613  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.613  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.613  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:21:32.613  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.613  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.613  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7a675c added. We now have 10 listener(s)
07-26 15:21:32.613  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.613  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:32.613  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:32.613  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-26 15:21:32.613  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:32.613  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:21:32.623   767   787 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.623  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:21:32.623   296  1055 V         : QcRouteController
,07-26 15:21:32.623  7221  7279 E BluetoothAdapter: bluetooth le advertising not supported
07-26 15:21:32.623  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:32.623  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:21:32.623  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:32.623  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:32.633  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-26 15:21:32.633  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:32.633  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.633  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.633  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.633  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@975f830 removed from the list
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.633  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df97ca9 removed from the list
07-26 15:21:32.633  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.633  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.633  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1df97ca9 not in the list
07-26 15:21:32.633  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.633   296  1055 V         : QcRouteController
,07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.633  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.633  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e7a675c removed from the list
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.633  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.633  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.633  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.633  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@291fe1cf removed from the list
07-26 15:21:32.643  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.643  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f62cbeb added. We now have 2 listener(s)
,07-26 15:21:32.643  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
07-26 15:21:32.643  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.643  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.643  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.643  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f49d48 added. We now have 9 listener(s)
07-26 15:21:32.643  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:32.643  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:32.643  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-26 15:21:32.643  4295  4295 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-26 15:21:32.643   767  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.643  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-26 15:21:32.643  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:32.643   767  3013 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.643  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-26 15:21:32.643  4295  4295 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-26 15:21:32.643  4295  4295 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-26 15:21:32.653  4295  4349 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:32.653  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:32.653  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:21:32.653  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:21:32.653  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:21:32.653  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375de906 added. We now have 3 listener(s)
07-26 15:21:32.653  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.653  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.653   296  1055 V         : QcRouteController
,07-26 15:21:32.653   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:32.653  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
,07-26 15:21:32.653  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.653  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.653  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.653  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30a03bc7 added. We now have 10 listener(s)
07-26 15:21:32.653  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.653  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:21:32.653  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:21:32.653  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:21:32.653  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:21:32.663  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-26 15:21:32.663  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 15:21:32.663  7221  7279 E BluetoothAdapter: bluetooth le advertising not supported
,07-26 15:21:32.663  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:21:32.663  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:21:32.663  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:21:32.663  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:32.663  7221  7279 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-26 15:21:32.673  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:21:32.673  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.673  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.673  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.673  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.673  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f62cbeb removed from the list
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.673  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f49d48 removed from the list
07-26 15:21:32.673  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.673  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.673  4295  4295 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-26 15:21:32.673  4295  4295 I NearbySettings: MountReceiver.onReceive - Keep current state
07-26 15:21:32.673   296  1055 V         : QcRouteController
,07-26 15:21:32.673  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:21:32.673  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.673  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f49d48 not in the list
,07-26 15:21:32.673  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.673  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.673  7221  7279 D BluetoothLeScanner: could not find callback wrapper
07-26 15:21:32.673  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.673  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.673  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30a03bc7 removed from the list
,07-26 15:21:32.683  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.683  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.683  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.683  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.683  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@375de906 removed from the list
,07-26 15:21:32.683  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.683  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245f8f92 added. We now have 2 listener(s)
,07-26 15:21:32.683  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
07-26 15:21:32.683  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.683  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.683  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.683  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375acd63 added. We now have 9 listener(s)
07-26 15:21:32.683  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:21:32.683   767  3013 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-26 15:21:32.683  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:21:32.683  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:21:32.693   296  1055 V         : QcRouteController
,07-26 15:21:32.693   296  1055 V         : QcRouteController
,07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:21:32.693  7221  7279 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:21:32.693   767  1569 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.693  7221  7279 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:21:32.693  7221  7279 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264de219 added. We now have 3 listener(s)
,07-26 15:21:32.693  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:2A:28:2D"
07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26312de added. We now have 10 listener(s)
07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:21:32.693  7221  7221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:21:32.693  4949  4949 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-26 15:21:32.693  7221  7279 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:21:32.693  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:21:32.693  7221  7279 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:21:32.693  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.693  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:21:32.693  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@245f8f92 removed from the list
07-26 15:21:32.693  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.693  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375acd63 removed from the list
07-26 15:21:32.693  7221  7279 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.693  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.703  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.703  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.703  7221  7279 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@375acd63 not in the list
07-26 15:21:32.703  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.703  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.703  7221  7279 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26312de removed from the list
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.703  7221  7279 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.703  7221  7279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.703  7221  7279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.703  7221  7279 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@264de219 removed from the list
,07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-26 15:21:32.703  7221  7279 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:21:32.703   265   265 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,07-26 15:21:32.713   296  1055 V         : QcRouteController
,07-26 15:21:32.713  7221  8215 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1327, name: My test thread name)
,07-26 15:21:32.713  7221  8215 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1327, thread name: My test thread name)
07-26 15:21:32.713  7221  8215 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1327, name: My test thread name)
,07-26 15:21:32.713  7221  8217 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1329, name: My test thread name)
07-26 15:21:32.713  7221  8217 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1329, thread name: My test thread name)
07-26 15:21:32.713  7221  8217 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1329, name: My test thread name)
,07-26 15:21:32.713  7221  7279 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-26 15:21:32.713  7221  7279 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-26 15:21:32.713   767  1426 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=767
07-26 15:21:32.723  7221  7279 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-26 15:21:32.723  7221  7279 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-26 15:21:32.723  7221  7279 D com.test.thalitest.ThaliTestRunner: Total duration: 22945 ms
,07-26 15:21:32.723  7221  7279 I jxcore-log: Total number of executed tests:  84
07-26 15:21:32.723  7221  7279 I jxcore-log: 
07-26 15:21:32.723  7221  7279 I jxcore-log: Number of passed tests:  84
07-26 15:21:32.723  7221  7279 I jxcore-log: 
07-26 15:21:32.723  7221  7279 I jxcore-log: Number of failed tests:  0
07-26 15:21:32.723  7221  7279 I jxcore-log: 
,07-26 15:21:32.723  7221  7279 I jxcore-log: Number of ignored tests:  0
07-26 15:21:32.723  7221  7279 I jxcore-log: 
07-26 15:21:32.723  7221  7279 I jxcore-log: Total duration:  22945
07-26 15:21:32.723  7221  7279 I jxcore-log: 
,07-26 15:21:32.723  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.723  7221  7279 I jxcore-log: 
,07-26 15:21:32.723  7221  7221 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Unsupported return type."", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:21:32.723  7221  7221 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:21:32.723  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.723  7221  7279 I jxcore-log: 
07-26 15:21:32.723  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.723  7221  7279 I jxcore-log: 
07-26 15:21:32.733   767  1150 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
07-26 15:21:32.733   767  1150 D ConnectivityService: LTETest block dns file not exists
07-26 15:21:32.733  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.733  7221  7279 I jxcore-log: 
07-26 15:21:32.733  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.733  7221  7279 I jxcore-log: 
07-26 15:21:32.733  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-26 15:21:32.733  7221  7279 I jxcore-log: 
07-26 15:21:32.733  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:21:32.733  7221  7279 I jxcore-log: 
07-26 15:21:32.743  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.743  7221  7279 I jxcore-log: 
07-26 15:21:32.743   767  1473 I ActivityManager: Killing 5056:com.sec.android.app.shealth/u0a40 (adj 15): emptyCount ##41
07-26 15:21:32.743  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:21:32.743  7221  7279 I jxcore-log: 
07-26 15:21:32.743   767  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-26 15:21:32.743   767  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-26 15:21:32.743   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:32.743   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-26 15:21:32.743   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:32.743   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:32.743   767  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-26 15:21:32.743   767  1150 E ConnectivityService: updateNetworkInfo()
07-26 15:21:32.743   767  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:32.743   767  1150 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-26 15:21:32.743   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:32.743   767  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-26 15:21:32.743   767  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:32.743   767  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-26 15:21:32.743   767  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-26 15:21:32.743   767  8145 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-26 15:21:32.743   767  8145 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-26 15:21:32.743  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.743  7221  7279 I jxcore-log: 
07-26 15:21:32.743   767  3050 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:32.743  7221  7274 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:21:32.743   767  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-26 15:21:32.743   767  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:32.743   767  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:32.743  7221  7221 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:21:32.743  7221  7221 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:21:32.743  7221  7221 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:21:32.753  7221  7221 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:21:32.753  7221  7221 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:21:32.753  7221  7221 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:21:32.753  7221  7221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cb2a63b removed from the list
07-26 15:21:32.753  7221  7221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:21:32.753  7221  7221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e360396 removed from the list
07-26 15:21:32.753  7221  7221 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:21:32.753  7221  7221 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:21:32.753  7221  7221 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
07-26 15:21:32.753   767  1150 D ConnectivityService: currentScore = 0, newScore = 60
07-26 15:21:32.753   767  1150 D ConnectivityService:    accepting network in place of null
07-26 15:21:32.753   767  1150 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
07-26 15:21:32.753  1428  1428 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
,07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
,07-26 15:21:32.753   767  1150 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-26 15:21:32.753   767  1150 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
07-26 15:21:32.753   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:32.753  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.753  7221  7279 I jxcore-log: 
,07-26 15:21:32.753   767  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:32.753   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-26 15:21:32.753   767  1151 D Tethering: MasterInitialState.processMessage what=3
07-26 15:21:32.753   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:32.763   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:32.763   767  1150 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-26 15:21:32.763   767  1145 V NetworkStats: updateIfacesLocked()
07-26 15:21:32.763   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:32.763   767  1145 V NetworkStats: performPollLocked(flags=0x1)
07-26 15:21:32.763   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:32.763   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:32.763   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-26 15:21:32.763   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.763   767  1320 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.763   767  1057 D EntConnectivity: Not allowed due to - mEnabled false
07-26 15:21:32.763   767  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-26 15:21:32.763   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:32.763   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:32.763   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:32.763   767  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:32.763  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-26 15:21:32.763  1197  1197 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-26 15:21:32.763  1197  1197 D StatusBar.NetworkController: updateDataNetType()
,07-26 15:21:32.763  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-26 15:21:32.763   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:32.763   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:32.763   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:32.763   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:32.763   767  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-26 15:21:32.763   767  1145 V NetworkStats: performPollLocked() took 7ms
,07-26 15:21:32.763   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:32.763   767  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-26 15:21:32.773   265  1570 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,07-26 15:21:32.773   767  1473 I AudioService: getStreamVolume 3 index 0
,07-26 15:21:32.773   265   902 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
07-26 15:21:32.773   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:32.773   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
07-26 15:21:32.773  1197  1197 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-26 15:21:32.773  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.773  7221  7279 I jxcore-log: 
,07-26 15:21:32.773  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.773  7221  7279 I jxcore-log: 
,07-26 15:21:32.773   767  3013 D SecContentProvider2: uri = 14 selection = getSealedState
,07-26 15:21:32.773   767  3013 D SecContentProvider2: mCursor = null
,07-26 15:21:32.773  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.773  7221  7279 I jxcore-log: 
,07-26 15:21:32.773   767  3050 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:32.773   767  3783 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = 0
07-26 15:21:32.773   767  3783 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.systemui
,07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 4 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x1 gsm|lte
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=1
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_1 mContentDescriptionPhoneSignal = One bar of phone signal
,07-26 15:21:32.773  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.773  7221  7279 I jxcore-log: 
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: refreshViews connected={ wifi } level=1 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=true combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mQSPhoneSignalIconId=0x7f020131/com.android.systemui:drawable/ic_qs_signal_1 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f02044c/com.android.systemui:drawable/stat_sys_signal_1 mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-26 15:21:32.773  1197  1197 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:32.773  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
,07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
,07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
,07-26 15:21:32.783  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-26 15:21:32.783  1197  1197 D StatusBar.NetworkController: applyOpen
07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
07-26 15:21:32.783  1197  1197 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-26 15:21:32.783  1197  1197 D StatusBar.NetworkController: applyOpen
,07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
07-26 15:21:32.783  1197  1197 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
,07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
07-26 15:21:32.783  7221  7279 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:21:32.783  7221  7279 I jxcore-log: 
,07-26 15:21:32.793  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:32.793  1197  1197 D PersonaManager: isKioskContainerExistOnDevice
07-26 15:21:32.793  1197  1197 I PhoneStatusBar: Icon Only
07-26 15:21:32.793  1197  1197 I StatusBar: Icon Only
,07-26 15:21:32.793  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:32.793  1197  1197 D PanelView: There is/are notification(s) 
,07-26 15:21:32.973  8223  8223 D AndroidRuntime: 
07-26 15:21:32.973  8223  8223 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-26 15:21:32.973  8223  8223 D AndroidRuntime: CheckJNI is OFF
,07-26 15:21:32.973  8223  8223 D AndroidRuntime: readGMSProperty: start
07-26 15:21:32.973  8223  8223 D AndroidRuntime: readGMSProperty: already setted!!
,07-26 15:21:32.973  8223  8223 D AndroidRuntime: readGMSProperty: end
07-26 15:21:32.973  8223  8223 D AndroidRuntime: addProductProperty: start
,07-26 15:21:33.113  8223  8223 E AffinityControl: AffinityControl: registerfunction enter
,07-26 15:21:33.133  8223  8223 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-26 15:21:33.143   767  3837 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-26 15:21:33.143   767  3837 D PackageManager: START PACKAGE DELETE: observer{756544947}
07-26 15:21:33.143   767  3837 D PackageManager: pkg{<packageName>}
07-26 15:21:33.143   767  3837 D PackageManager: user{0}
07-26 15:21:33.143   767  3837 D PackageManager: caller{2000}
07-26 15:21:33.143   767  3837 D PackageManager: flags{2}
07-26 15:21:33.143   767  3837 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-26 15:21:33.143   767  3837 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-26 15:21:33.143   767  3837 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-26 15:21:33.143   767  3837 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-26 15:21:33.143   767  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER,
,07-26 15:21:33.143   767  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-26 15:21:33.143   767  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-26 15:21:33.143   767  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-26 15:21:33.143   767   975 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,07-26 15:21:33.143   767  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-26 15:21:33.143   767   975 I ActivityManager: Killing 7221:com.test.thalitest/u0a79 (adj 9): stop com.test.thalitest cause uninstall pkg
07-26 15:21:33.143   767  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-26 15:21:33.143   767   975 D FocusedStackFrame: Set to : 0
,07-26 15:21:33.203   767  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,07-26 15:21:33.203   767  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.119/24,fe80::ea50:8bff:fed7:fd2b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-26 15:21:33.203   767  1150 D ConnectivityService: identical MTU - not setting
07-26 15:21:33.203   767  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-26 15:21:33.203   767  1150 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fed7:fd2b
07-26 15:21:33.203   296  1055 V         : QcRouteController
,07-26 15:21:33.223   296  1055 V         : QcRouteController
,07-26 15:21:33.223   767  1150 W NetworkManagementService: route cmd failed: 
07-26 15:21:33.223   767  1150 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '115 route replace src v6 wlan0 fe80::ea50:8bff:fed7:fd2b 2 ::' failed with '400 115 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-26 15:21:33.223   767  1150 W NetworkManagementService: '
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:33.223   767  1150 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:21:33.223   767  1150 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-26 15:21:33.223   767  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-26 15:21:33.223   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:33.223   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:33.223   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:33.223   767  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:33.223   767  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-26 15:21:33.223   767  1150 D ConnectivityService: calling update connectivity
07-26 15:21:33.223   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-26 15:21:33.223   767  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-26 15:21:33.223   767  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-26 15:21:33.223  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-26 15:21:33.223  1197  1578 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-26 15:21:33.243   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-26 15:21:33.243   767   767 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.243   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:33.253   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:33.253   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:33.253   767  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-26 15:21:33.253   767  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,07-26 15:21:33.253   767  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:21:33.283  1626  1626 I art     : Explicit concurrent mark sweep GC freed 3385(153KB) AllocSpace objects, 3(60KB) LOS objects, 40% free, 19MB/33MB, paused 628us total 26.220ms
,07-26 15:21:33.293  4949  4949 I art     : Explicit concurrent mark sweep GC freed 2689(151KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 300us total 36.505ms
,07-26 15:21:33.343  5260  5260 I art     : Explicit concurrent mark sweep GC freed 37705(2025KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 363us total 40.324ms
,07-26 15:21:33.343  5740  5740 I art     : Explicit concurrent mark sweep GC freed 711(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 302us total 44.092ms
,07-26 15:21:33.353   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-26 15:21:33.353   767  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-26 15:21:33.363  1917  2341 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-26 15:21:33.363  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-26 15:21:33.363  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:21:33.363  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-26 15:21:33.363   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.363   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.363  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
07-26 15:21:33.363   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.363   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.363   767  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.363   767  1473 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.373   767  1121 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:21:33.373  1694  1694 E SamsungIME: mOCRHelper is null
,07-26 15:21:33.373   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.373   767   788 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.373  1444  1444 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:33.373  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-26 15:21:33.373   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-26 15:21:33.373  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-26 15:21:33.373   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.373   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.373   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-26 15:21:33.373  7458  7458 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-26 15:21:33.383   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-26 15:21:33.383  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-26 15:21:33.383  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:21:33.383  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-26 15:21:33.383  4174  4174 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-26 15:21:33.383   767  3252 E libprocessgroup: failed to kill 1 processes for processgroup 7221
,07-26 15:21:33.383  1626  1626 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-26 15:21:33.383   767  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-26 15:21:33.383   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:33.383   767  1145 V NetworkStats: performPollLocked(flags=0x3)
,07-26 15:21:33.383   767  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-26 15:21:33.383   767  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.393   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.393  1413  1413 D RegisteredServicesCache: empty dynamic service
,07-26 15:21:33.393   767  1145 V NetworkStats: performPollLocked() took 5ms
07-26 15:21:33.393   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:33.393  4174  4174 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469539293398
,07-26 15:21:33.393  4174  4174 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-26 15:21:33.403   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-26 15:21:33.403   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-26 15:21:33.403   767  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-26 15:21:33.413   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-26 15:21:33.433   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-26 15:21:33.443   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-26 15:21:33.443   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-26 15:21:33.453   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-26 15:21:33.453   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-26 15:21:33.453  4174  4174 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-26 15:21:33.483   767  1260 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:33.483   767  1260 D ActivityManager: caller:android.app.ApplicationThreadProxy@3841e8f6, r.packageName :com.google.android.gms
,07-26 15:21:33.493   767  1482 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-26 15:21:33.493   767  1482 D SecContentProvider2: mCursor = null
,07-26 15:21:33.503   372   372 I ServiceManager: Waiting for service AtCmdFwd...
,07-26 15:21:33.503   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-26 15:21:33.513   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-26 15:21:33.513   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.513   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-26 15:21:33.513   767  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.523   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-26 15:21:33.533   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-26 15:21:33.533   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-26 15:21:33.533   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-26 15:21:33.533   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-26 15:21:33.543   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-26 15:21:33.543   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-26 15:21:33.543   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-26 15:21:33.543   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-26 15:21:33.553   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.553   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-26 15:21:33.553   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-26 15:21:33.563   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-26 15:21:33.563   767  1569 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.573   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-26 15:21:33.573   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-26 15:21:33.583   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.583   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-26 15:21:33.583   767  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.593   767   767 D RCPManagerService: PackageReceiver onReceive()
07-26 15:21:33.593   767   767 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-26 15:21:33.593   767   767 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-26 15:21:33.593   767   767 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-26 15:21:33.593   767   767 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:21:33.593   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.593   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-26 15:21:33.593   767   767 V EnterpriseBillingPolicy: uID is 10079
07-26 15:21:33.593   767   767 V EnterpriseBillingPolicy: Removed Packageuid is0
07-26 15:21:33.593   767   767 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-26 15:21:33.603   767   767 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-26 15:21:33.603   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-26 15:21:33.603   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-26 15:21:33.603   767   767 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-26 15:21:33.603   767   767 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-26 15:21:33.603   767  1523 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.603   767  1178 D TaskPersister: removeObsoleteFile: deleting file=38_task.xml
,07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767   767 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:33.603   767   767 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-26 15:21:33.603   767   767 D SmartBondingService: SmartBondingReceiver: wifi ap is changed, init speed ratio
07-26 15:21:33.603   767   767 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:33.603   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:33.603   767  1152 D SmartBondingService: getSBEnabled() enabled =false
07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767   767 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.603   767  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-26 15:21:33.603   767   767 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-26 15:21:33.613   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.623   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.633   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.643   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-26 15:21:33.643   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.653   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.653  4174  4174 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-26 15:21:33.663   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.663   767  3050 I SQLiteConnectionPool: exportDB...
,07-26 15:21:33.663  4174  4174 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-26 15:21:33.663   767   957 D EnterpriseDeviceManagerService: Package has changed for user 0
07-26 15:21:33.663   767   957 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-26 15:21:33.673  7078  7078 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-26 15:21:33.673   767  1471 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-26 15:21:33.673   767  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@3eb7f9bb, r.packageName :com.sec.esdk.elm
,07-26 15:21:33.673   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-26 15:21:33.673  7078  7078 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-26 15:21:33.673   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.683  3554  3554 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-26 15:21:33.683  3554  3554 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-26 15:21:33.683  3554  3554 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-26 15:21:33.683  3554  3554 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-26 15:21:33.683  3554  3554 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-26 15:21:33.683  3554  3554 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,07-26 15:21:33.683  3554  3554 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-26 15:21:33.683  3554  3554 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:33.683   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.683  3554  3554 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:33.683  3554  3554 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
,07-26 15:21:33.683  3554  3554 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:33.683  3554  3554 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:33.683  3554  3554 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:33.683  3554  3554 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-26 15:21:33.683  7078  7078 D elm:14491: ElmAgentService : onCreate()
,07-26 15:21:33.693  7078  8253 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-26 15:21:33.693  7078  8253 D elm:14491: MainReceiver.listeningToPackageRemoved()
,07-26 15:21:33.693  7078  8253 D elm:14491: MDMBridge.getInstance()
07-26 15:21:33.693  7078  8253 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:21:33.693  7078  8253 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-26 15:21:33.693   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.703   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.703   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-26 15:21:33.703   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.713  7078  7078 D elm:14491: ElmAgentService : onDestroy().
,07-26 15:21:33.713   767  3050 I SQLiteConnectionPool: ...exportDB
07-26 15:21:33.713  1723  1723 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
07-26 15:21:33.713  1723  1723 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-26 15:21:33.713   767  1260 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.713   767  3050 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-26 15:21:33.723   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.723   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-26 15:21:33.733   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:21:33.733   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-26 15:21:33.733   767  1633 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,07-26 15:21:33.733   767  1633 D ActivityManager: caller:android.app.ApplicationThreadProxy@89165fa, r.packageName :com.google.android.gms
,07-26 15:21:33.743   767  1260 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.743  2281  8255 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:21:33.743  2281  2281 D ChimeraRcvrProxy: Creating receiver proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy}
07-26 15:21:33.743  2281  2281 D ChimeraRcvrProxy: Proxying container receiver ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesSystemBroadcastReceiverProxy} to Chimera receiver impl com.google.android.gms.games.receiver.PlaySystemBroadcastReceiver
07-26 15:21:33.743  2281  2281 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:21:33.743  2281  2281 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:21:33.743  2281  8255 D AccountUtils: Clearing selected account for com.test.thalitest
,07-26 15:21:33.743   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@b0b4e08, r.packageName :com.google.android.gms
,07-26 15:21:33.753   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.753  2281  2281 D ChimeraSrvcProxy: Creating service proxy ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy}
07-26 15:21:33.753  2281  2281 D ChimeraSrvcProxy: Proxying container service ComponentInfo{com.google.android.gms/com.google.android.gms.games.chimera.GamesAsyncServiceProxy} to Chimera service impl com.google.android.gms.games.service.PlayGamesAsyncService
,07-26 15:21:33.753  2281  2281 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:21:33.753  2281  2281 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:21:33.753   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.753   767  1064 I art     : Explicit concurrent mark sweep GC freed 81136(4MB) AllocSpace objects, 14(224KB) LOS objects, 30% free, 36MB/52MB, paused 4.301ms total 376.059ms
,07-26 15:21:33.763   767  1569 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d383387, r.packageName :com.google.android.gms
,07-26 15:21:33.763   767   779 I art     : WaitForGcToComplete blocked for 235.620ms for cause HeapTrim
,07-26 15:21:33.763   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.763   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-26 15:21:33.763   767  3837 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:21:33.763   767  3837 D ActivityManager: caller:android.app.ApplicationThreadProxy@2773d620, r.packageName :com.google.android.gms
,07-26 15:21:33.763  2281  8255 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-26 15:21:33.773   767  3783 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-26 15:21:33.773   767  1523 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.783   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.783   767  1569 D ActivityManager: caller:android.app.ApplicationThreadProxy@6fcf19b, r.packageName :com.google.android.gms
,07-26 15:21:33.783   767  1260 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:33.783   767  1260 D ActivityManager: caller:android.app.ApplicationThreadProxy@35086d11, r.packageName :com.google.android.gms
,07-26 15:21:33.793   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.793   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-26 15:21:33.803   767  1064 D PackageManager: delete codoeFile: 
,07-26 15:21:33.813   767  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,07-26 15:21:33.813   767  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-26 15:21:33.813  2281  8261 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
07-26 15:21:33.813  2281  8261 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,07-26 15:21:33.813  2281  8261 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
07-26 15:21:33.813  2281  8261 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,07-26 15:21:33.823   767  1320 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
,07-26 15:21:33.823   767   788 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.823  2281  8261 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
07-26 15:21:33.823  2281  8261 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,07-26 15:21:33.823  2281  8261 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,07-26 15:21:33.833  2281  8261 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
07-26 15:21:33.833  2281  8261 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,07-26 15:21:33.833   767  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.833   767  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.833   767  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.833  2281  8261 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
07-26 15:21:33.833   767  1320 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.833   767  1064 D PackageManager: result of delete: 1{756544947}
,07-26 15:21:33.843  8223  8223 D AndroidRuntime: Shutting down VM
,07-26 15:21:33.843   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-26 15:21:33.843   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-26 15:21:33.843   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-26 15:21:33.853   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.853   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-26 15:21:33.853   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-26 15:21:33.863   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,07-26 15:21:33.863   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-26 15:21:33.863   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.863   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:21:33.863   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-26 15:21:33.873   767   957 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-26 15:21:33.873   767   957 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-26 15:21:33.873   767   957 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:21:33.873   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.873   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-26 15:21:33.873  8262  8262 E Zygote  : MountEmulatedStorage()
07-26 15:21:33.873  8262  8262 E Zygote  : v2
07-26 15:21:33.873  8262  8262 I libpersona: KNOX_SDCARD checking this for 10021
07-26 15:21:33.873  8262  8262 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:33.873   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-26 15:21:33.883   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-26 15:21:33.883   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.883   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-26 15:21:33.883   767  1320 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8262 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,07-26 15:21:33.883   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:21:33.883   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-26 15:21:33.893   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-26 15:21:33.893   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-26 15:21:33.893   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-26 15:21:33.893   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.893   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-26 15:21:33.893   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.893   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-26 15:21:33.893   767   957 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-26 15:21:33.903  8262  8262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:33.903  8262  8262 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:33.903  8262  8262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:33.903   767  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.903   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.903   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-26 15:21:33.903   767   957 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-26 15:21:33.913   767  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:33.913   767  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f5b597b, r.packageName :com.google.android.gms
,07-26 15:21:33.913   767   957 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-26 15:21:33.913   767  1260 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.913   767   957 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-26 15:21:33.923   767   957 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-26 15:21:33.923   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.923   767   957 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:21:33.923   767   957 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.923   767   957 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.923  8262  8262 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:33.923  8262  8262 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:33.943   767  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:33.943   767  1446 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f057cf3, r.packageName :com.google.android.gms
,07-26 15:21:33.943  8262  8262 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,07-26 15:21:33.943  1723  1723 I ConfigService: onCreate
,07-26 15:21:33.943  1723  1723 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,07-26 15:21:33.943   767  1143 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:33.943   767  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@1670f54f, r.packageName :com.google.android.gms
,07-26 15:21:33.953  2281  2281 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-26 15:21:33.953  1723  1723 I ConfigService: onBind returning update interface
,07-26 15:21:33.953  1444  1444 D SurfaceWidgetView: destroyHardwareResources():481099062
,07-26 15:21:33.953  1723  1723 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,07-26 15:21:33.953  1723  1723 I ConfigService: onBind returning service broker
,07-26 15:21:33.953   767  1569 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.953   767  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-26 15:21:33.953   767  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@15c039e5, r.packageName :com.google.android.gms
,07-26 15:21:33.953  1444  1444 D Launcher: onRestart, Launcher: 679945740
,07-26 15:21:33.953   767  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-26 15:21:33.953  1444  1444 D Launcher: onStart, Launcher: 679945740
07-26 15:21:33.953  1444  1444 D Launcher.HomeView: onStart
,07-26 15:21:33.953  1444  1444 V ActivityThread: updateVisibility : ActivityRecord{2e5e9f71 token=android.os.BinderProxy@3473f877 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-26 15:21:33.953  1759  1787 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-26 15:21:33.963  1759  2020 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-26 15:21:33.963  1759  2020 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-26 15:21:33.963  2281  8268 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:21:33.973  2281  8268 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:21:33.973   767  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.973   265   265 I SurfaceFlinger: id=16 createSurf (1080x1920),1 flag=4, Mauncher
,07-26 15:21:33.973   767  1320 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:33.983  8262  8262 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-26 15:21:33.983  8262  8262 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-26 15:21:33.983  8262  8262 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,07-26 15:21:33.983   767  1426 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
,07-26 15:21:33.983   767  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.983   767  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.983   767  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:33.983   767  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:34.023  8284  8284 E Zygote  : MountEmulatedStorage()
07-26 15:21:34.023  8284  8284 E Zygote  : v2
07-26 15:21:34.023  8284  8284 I libpersona: KNOX_SDCARD checking this for 10025
07-26 15:21:34.023  8284  8284 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:34.033   767  1426 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8284 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-26 15:21:34.043  8284  8284 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:34.043  8284  8284 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:34.043   767  1320 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-26 15:21:34.043   767  1320 D ActivityManager: caller:android.app.ApplicationThreadProxy@3304c09d, r.packageName :com.google.android.gms
,07-26 15:21:34.043  8284  8284 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:34.043  2281  8283 I PeopleContactsSync: CP2 sync disabled
,07-26 15:21:34.043   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.053  2281  4063 I Icing   : doRemovePackageData com.test.thalitest
,07-26 15:21:34.053   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.053  2281  2281 I ConfigFetchService: service connected
,07-26 15:21:34.073   767   788 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.073   767  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2098b08a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t35} time:190084
,07-26 15:21:34.073   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.073  8284  8284 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:34.073  8284  8284 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:34.083   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.093   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.093   767  1064 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-26 15:21:34.093   767  1064 D PackageManager: userId{-1}
07-26 15:21:34.093   767  1064 D PackageManager: andCode{true}
,07-26 15:21:34.093   767  1064 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-26 15:21:34.093  8284  8284 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,07-26 15:21:34.093   767  1064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.093   767  1064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.093   767  1064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.093   767  1064 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:34.103  8284  8284 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-26 15:21:34.113  8284  8284 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,07-26 15:21:34.123  8284  8284 D MVFD_interface: <<<  caMVFace_FaceInit
,07-26 15:21:34.133  8301  8301 E Zygote  : MountEmulatedStorage()
07-26 15:21:34.133  8301  8301 E Zygote  : v2
07-26 15:21:34.133  8301  8301 I libpersona: KNOX_SDCARD checking this for 10007
07-26 15:21:34.133  8301  8301 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:34.143   767  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8301 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-26 15:21:34.153  8301  8301 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:34.153  8301  8301 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:34.163  8301  8301 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-26 15:21:34.163   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.163   767  1569 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.173   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.173   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.183  8301  8301 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:34.183  8301  8301 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:34.193   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.193   767  3837 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.203  8301  8301 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-26 15:21:34.203   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.213   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.213   304   304 E SMD     : DCD ON
,07-26 15:21:34.223   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
07-26 15:21:34.223   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:34.223  8284  8284 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,07-26 15:21:34.223   264   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
07-26 15:21:34.223   264   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-26 15:21:34.223  8284  8284 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,07-26 15:21:34.223   767  1633 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.223   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.233   767  1121 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-26 15:21:34.243   767  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.243   767  1260 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.253  8284  8324 E Volley  : [1306] DiskBasedCache.initialize: Unable to create cache dir /data/data/sstream.app/cache/volley
,07-26 15:21:34.253   767  3013 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.253   767  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.253  8284  8284 E SharedPreferencesImpl: Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
,07-26 15:21:34.263   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.263   767  1482 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.273   767  1121 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-26 15:21:34.283   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.283   767  3783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.293   767  1446 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.293   767   787 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.303  8284  8284 D HockeyApp: Current handler class = sstream.app.util.Log$1
,07-26 15:21:34.303   767  1473 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-26 15:21:34.303  1723  1749 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f0a1c8d in tid 1749 (Binder_2)
,07-26 15:21:34.313   767  1121 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-26 15:21:34.323  8284  8284 E SharedPreferencesImpl: Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
,07-26 15:21:34.353   767  1121 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-26 15:21:34.383  8284  8333 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-26 15:21:34.383  8284  8333 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-26 15:21:34.383  8284  8333 E SQLiteLog: (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
07-26 15:21:34.383  8284  8333 E SQLiteLog: (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
07-26 15:21:34.383  8284  8333 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-26 15:21:34.383  8284  8333 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/sstream.app/databases/sstream.db) - 
,07-26 15:21:34.383  8284  8333 E SQLiteDatabase: Failed to open database '/data/data/sstream.app/databases/sstream.db'.
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:980)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:484)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:428)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
07-26 15:21:34.383  8284  8333 E SQLiteDatabase: 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,07-26 15:21:34.383  8284  8284 E SQLiteLog: (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
07-26 15:21:34.383  8284  8284 E SQLiteLog: (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
07-26 15:21:34.383  8284  8284 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-26 15:21:34.383  8284  8284 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/sstream.app/databases/sstream.db) - 
,07-26 15:21:34.383  8284  8284 E SQLiteDatabase: Failed to open database '/data/data/sstream.app/databases/sstream.db'.
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:34.383  8284  8284 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-26 15:21:34.393  8284  8284 D AndroidRuntime: Shutting down VM
,07-26 15:21:34.393  6632  6632 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-26 15:21:34.393  6632  6632 I PCWCLIENTTRACE_PushUtil: sales region : global
07-26 15:21:34.393  6632  6632 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-26 15:21:34.393  6632  6632 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-26 15:21:34.393   767  1569 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,07-26 15:21:34.393   767  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.393   767  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.393   767  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.393   767  1569 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:34.403   767  1121 I EventHub: Removing device '/dev/input/event10' due to inotify event
,07-26 15:21:34.403  8284  8284 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/b61c26a5-51bb-4591-b24e-c30ba7de6c78.stacktrace
,07-26 15:21:34.403  8284  8284 E HockeyApp: Error saving exception stacktrace!
07-26 15:21:34.403  8284  8284 E HockeyApp: 
07-26 15:21:34.403  8284  8284 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/b61c26a5-51bb-4591-b24e-c30ba7de6c78.stacktrace: open failed: EROFS (Read-only file system)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-26 15:21:34.403  8284  8284 E HockeyApp: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:21:34.403  8284  8284 E HockeyApp: 	... 7 more
,07-26 15:21:34.403  8284  8333 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/349f80a9-7559-45a4-9dd1-28de852cb217.stacktrace
,07-26 15:21:34.403  8284  8333 E HockeyApp: Error saving exception stacktrace!
07-26 15:21:34.403  8284  8333 E HockeyApp: 
07-26 15:21:34.403  8284  8333 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/349f80a9-7559-45a4-9dd1-28de852cb217.stacktrace: open failed: EROFS (Read-only file system)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-26 15:21:34.403  8284  8333 E HockeyApp: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-26 15:21:34.403  8284  8333 E HockeyApp: 	... 7 more
,07-26 15:21:34.413   297   297 I DEBUG   : failed to create /data/tombstones: Read-only file system
07-26 15:21:34.413   297   297 I DEBUG   : failed to open /data/tombstones: No such file or directory
07-26 15:21:34.413   297   297 E         : ro.product_ship = true
07-26 15:21:34.413   297   297 E         : ro.debug_level = 0x4f4c
,07-26 15:21:34.413  1901  1901 E audit_log: File locking failed. error= Bad file number
,07-26 15:21:34.423  2987  3043 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-26 15:21:34.433  8337  8337 E Zygote  : MountEmulatedStorage()
07-26 15:21:34.433  8337  8337 I libpersona: KNOX_SDCARD checking this for 10033
07-26 15:21:34.433  8337  8337 E Zygote  : v2
07-26 15:21:34.433  8337  8337 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:34.443   767  1121 I EventHub: Removing device '/dev/input/event11' due to inotify event
,07-26 15:21:34.443   767  1569 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8337 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-26 15:21:34.443   767  1569 I ActivityManager: Killing 5966:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-26 15:21:34.473  8337  8337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:34.473  8337  8337 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:34.473  8337  8337 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:34.483   767  1121 I EventHub: Removing device '/dev/input/event12' due to inotify event
,07-26 15:21:34.503  8337  8337 D TimaKeyStoreProvider: TimaSignature is unavailable
07-26 15:21:34.503   372   372 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-26 15:21:34.503  8337  8337 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:34.513  2281  8260 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@3c01b401
,07-26 15:21:34.513   767  1471 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10015, pid=1723, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=208)
,07-26 15:21:34.513   767  1523 I ActivityManager: Process com.google.process.gapps (pid 1723)(adj 1) has died(401,1424)
,07-26 15:21:34.513   767  1523 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
07-26 15:21:34.513   767  1523 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 10999ms
07-26 15:21:34.513   767  1523 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
07-26 15:21:34.513   767  1523 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,07-26 15:21:34.513   767  1482 D CountryDetector: No listener is left
,07-26 15:21:34.523   767  1121 I EventHub: Removing device '/dev/input/event13' due to inotify event
07-26 15:21:34.523   767  1471 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-26 15:21:34.523   767  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.523   767  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.523   767  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-26 15:21:34.523   767  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-26 15:21:34.533  8337  8337 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Phonesky/Phonesky.apk
,07-26 15:21:34.533  8337  8337 W ContextImpl: Unable to create files subdir /data/data/com.android.vending/cache
07-26 15:21:34.533  8337  8337 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-26 15:21:34.563   767  1121 I EventHub: Removing device '/dev/input/event14' due to inotify event
,07-26 15:21:34.573   359   359 I Zygote  : Process 1723 exited due to signal (7)
,07-26 15:21:34.603   767  1471 I ActivityManager: Start proc com.google.process.gapps for service com.google.android.gms/.gcm.http.GoogleHttpService: pid=8353 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-26 15:21:34.603  8353  8353 E Zygote  : MountEmulatedStorage()
07-26 15:21:34.603  8353  8353 I libpersona: KNOX_SDCARD checking this for 10015
07-26 15:21:34.603  8353  8353 E Zygote  : v2
07-26 15:21:34.603  8353  8353 I libpersona: KNOX_SDCARD not a persona
,07-26 15:21:34.613   767  1473 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-26 15:21:34.613   767  1569 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,07-26 15:21:34.663  8353  8353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-26 15:21:34.663  8353  8353 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-26 15:21:34.663  8353  8353 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-26 15:21:34.673  8353  8353 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-26 15:21:34.683  8353  8353 D ActivityThread: Added TimaKeyStore provider
,07-26 15:21:34.693  8353  8353 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GmsCore/GmsCore.apk
,07-26 15:21:34.703  8353  8353 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-26 15:21:34.703  8353  8353 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-26 15:21:34.703  8353  8353 W ContextImpl: Unable to create files subdir /data/data/com.google.android.gms/cache
07-26 15:21:34.703  8353  8353 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-26 15:21:34.723  8353  8353 I MultiDex: VM with version 2.1.0 has multidex support
,07-26 15:21:34.723  8353  8353 I MultiDex: install
07-26 15:21:34.723  8353  8353 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-26 15:21:34.723  8353  8353 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-26 15:21:34.733   265   535 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-26 15:21:34.733  8353  8353 I GservicesProvider: Gservices pushing to system: true; secure/global: true
07-26 15:21:34.733  8353  8353 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gsf/databases/gservices.db" with flag (131138) and mode_t (0) due to error (30)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gsf/databases/gservices.db'.
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:34.743  8353  8353 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:34.743  8353  8353 D AndroidRuntime: Shutting down VM
,07-26 15:21:34.743  8353  8353 E AndroidRuntime: FATAL EXCEPTION: main
07-26 15:21:34.743  8353  8353 E AndroidRuntime: Process: com.google.process.gapps, PID: 8353
07-26 15:21:34.743  8353  8353 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.content.ContentProvider,.attachInfo(ContentProvider.java:1685)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
07-26 15:21:34.743  8353  8353 E AndroidRuntime: 	... 11 more
07-26 15:21:34.743   767  3837 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.process.gapps
,07-26 15:21:34.743  8353  8353 I Process : Sending signal. PID: 8353 SIG: 9
,07-26 15:21:34.743   767  8368 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
07-26 15:21:34.743   767  8368 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-26 15:21:34.743   767  8368 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-26 15:21:34.743   767  8368 E AndroidRuntime: 	... 5 more
,07-26 15:21:34.763   767  8368 E android.os.Debug: ro.product_ship = true
07-26 15:21:34.763   767  8368 E android.os.Debug: ro.debug_level = 0x4f4c
,07-26 15:21:34.763   767  8368 E AndroidRuntime: Error reporting crash
07-26 15:21:34.763   767  8368 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-26 15:21:34.763   767  8368 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-26 15:21:34.763   767  8368 E AndroidRuntime: 	... 11 more
07-26 15:21:34.763   767  8368 I Process : Sending signal. PID: 767 SIG: 9

```
